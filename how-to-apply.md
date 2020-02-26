# GSoC @ Arduino: Application Instructions

## Before you apply

If you are a student interested in submitting a proposal to CC, start by checking out our [Project Ideas](ideas.md) page to find an idea that you would like to write a proposal to work on during GSoC.

Take a look at the [Arduino website](https://arduino.cc) to learn more about what we do. Also look at our GitHub organizations ([arduino](https://github.com/arduino) and [arduino-libraries](https://github.com/arduino-libraries)) and our [forum](https://forum.arduino.cc) to get a sense of the code and projects we work on. Making a successful contribution to one of our projects will help us get a sense of your work and is highly recommended.

## Expectations

### During the application phase (February 20th - March 31st)

_These tips can help your application! They are not strictly required._

* Read the official [GSoC student guide](https://google.github.io/gsocguides/student/) and the [GSoC FAQ](https://developers.google.com/open-source/gsoc/faq).
* Review our [ideas list](ideas.md) and ask questions about projects you're potentially interested in on the [issue tracker](https://github.com/arduino/summer-of-code/issues)
* Introduce yourself on our [GSoC issue tracker](https://github.com/arduino/summer-of-code/issues) - **The issue will be the communication channel between you and us from now on.**
* Fix a bug in one of our repositories, submit a Pull Request and link it in your introductive post. We suggest you pick one of the bugs listed in one of these repositories:
    * https://github.com/arduino/Arduino
    * https://github.com/arduino/arduino-cli
    * https://github.com/arduino/ArduinoCore-samd
    * https://github.com/arduino/ArduinoCore-avr
    * any repo in https://github.com/arduino-libraries
* Get feedback from us (via the issue tracker) before you submit a final application.
* If you're proposing a project that's not on our official ideas list, please talk to us to see if there is any mentor interested in mentoring that project before you put any work into the proposal.

### During the community bonding period (April 27th - May 18th)

* Continue to plan your project with your mentor and the community.
* Get an Arduino board (an original one!) and familiarize with it so that you know what you're working for.

### During the summer (May 18th - August 17th)

* Write a short report for us every week in your GitHub issue.
* Work 30-40 hours per week (or agree on a different plan with your mentor ahead of time).
* Commit early and commit often! Push to a public GitHub repository so that we can see and review your work.
* Actively work on our project timeline and communicate with us during the community bonding period.
* If there is a reason why you can't work or can't contact us on a regular basis please make us aware of this in advance.
* If you don't communicate with us regularly, we will fail you.
* Set a realistic goal for all evaluation deadlines. If you fail to meet your own goal we are more likely to fail you in the evaluations.
* Be proactive about asking for help, especially when you're stuck.

## Applying

### How to write a great proposal

Your proposal must be submitted through the Google Summer of Code website. It is a good idea to submit drafts and get feedback from mentors before you submit your final proposal.

Please read and follow the [GSoC student guide on writing proposals](https://google.github.io/gsocguides/student/writing-a-proposal). Also:

* Don't be afraid to give us lots of detail about how you would approach the project.
* Your application should make us believe that you are capable of completing the project and delivering the functionality to our users. If you aren't sure about anything, get in touch with us, we're happy to advise you.

You can use our [base template](proposal-template.md) to draft your application in Markdown format. If you don't know what Markdown is, we recommend you familiarize with it anyway ;-)

Your final proposal must be submitted to GSoC as a PDF file, so you can use Pandoc to generate one from your Markdown file:

```
$ pandoc -f markdown -t pdf your-name.md
```
