# What and why?
With this website we aim to help you and your peers get familiar with follow the sun development. There is a lot of information already available about Follow-the-sun development, such as [here](https://en.wikipedia.org/wiki/Follow-the-sun) and [here](https://follow-the-sun.github.io). However, a short introduction explaining what Follow-the-sun development actually is before jumping into the guidelines should be helpful as a quick refresher.

## What is Follow-the-sun?
[Follow-the-sun](https://en.wikipedia.org/wiki/Follow-the-sun) development, a sub-field of [globally distributed software engineering (GDSE)](https://en.wikipedia.org/wiki/Distributed_development#Globally_Distributed_Software_Engineering), allows teams all over the world to actively cooperate on the same product. This is achieved by having multiple development teams in different time zones. When ever one development team stops their work for the day, a different team is immediately available to continue the work. This means that the amount of active development over time can be drastically increased. For example, if there are 3 teams who all work 8 hour days and start right after each other, the active development time over 24 hours would be 24 hours!

## Why a daily handoff?
A major part of Follow-the-sun development is the daily handoff (also referred to as the daily hand-off or daily handover). These daily handoffs are meant to transfer the knowledge of the system from a development team which is stopping for the day to a team which is just starting for the day, normally taking the form of a video call between teams. This is necessary as all development teams should know the goal of the system, and know what the current development status is.

## Guidelines
With these guidelines we aim to help you start performing your daily handoffs efficiently, as they are important topics you should keep in mind. By this we hope you and your peers can become more productive, and effectively use Follow-the-sun development in practice.

### Be concise
The overlap in time you and your peers have might be limited. In order to use this time effectively, make sure to stay concise during your handoff. Taking a lot of time discussing minute details wastes the limited amount of communication time you have with your peers, which may result in important details being overlooked!

### Be precise
Transferring your knowledge is difficult, but is the cornerstone of the daily handoff. Miscommunications are difficult to be resolved as you are no longer working even though your peers across the globe are. To make sure your peers can work productively it is important to be precise in the information you share, and making sure they understand the tasks at hand.

### Be prepared
This might seem like stating the obvious, but you should be prepared for your daily handoff before you start the meeting. Spending time deciding on what information you need to transfer to your peers wastes precious time which could be used to ensure everyone is up to speed on the development!

### Test your communication
This follows nicely from being prepared. Be sure the methods you are using to communicate with your peers work correctly! Spending time troubleshooting during your daily handoff wastes time, and should obviously be avoided!

### Use a fixed structure
Use a structured way of transferring your knowledge to your peers. Having every handoff be in the same format allows you to not waste time determining what to discuss next, as all meetings will follow the same workflow.

### Allow written handoffs
At times it might be impossible to perform your daily handoff with a video conference. This might be the case because the next team has started their weekend, has a national day off, or are on vacation. Even though it is less than ideal to write everything down, make sure you and your peers use a structure of communicating where this is possible as it will inevitably happen.

### Work test driven
This is great advice for Follow-the-sun development in general, but is especially important for the daily handoff! Having your requirements defined as tests means there is an unambiguous language you can use when communicating with your peers. This means less time needs to be spent on discussing the details of every task, and more time can be spent expanding the general knowledge of the project. This also has the benefit of easily seeing which tasks have been finished and which are still open by looking at the delivered test results during the handoff.

### Experiment
Experiment with the guidelines provided. If you and your peers can work more effectively by ignoring or altering one or more of the methods described, please do so! The goal of the daily handoff is the fast and effective sharing of knowledge between you and your peers all over the globe. If you find ways which work better for you and your team, adopt them and evolve them!

## And in practice?
Some services which should help you follow these guidelines in practice are described in the lists below.
### Communication
 - [Slack](https://slack.com/)
 - [Mattermost](https://mattermost.com/)
 - [Flowdock](https://www.flowdock.com/)
 - [Zulip](https://zulipchat.com/)
 - [Google Hangouts](https://hangouts.google.com/)
 - [Skype](https://hangouts.google.com/)

### Keeping knowledge organised
 - [Trello](https://trello.com/)
 - [Jira](https://www.atlassian.com/software/jira)

These services should improve the communication between you and your peers. In practice, starting a video chat whenever possible will greatly improve the efficiency of the communication between you and your peers. If you want all your communication centralised Slack should fit your needs perfectly. It is also possible to integrate both Trello and Jira with Slack, meaning you can link all your services together to even further improve communication.

<hr>

#### Disclaimer
All guidelines described on this site are based on our literature findings. All the sources we consulted in order to derive these guidelines can be found in the [sources](#sources) section on this site. As the guidelines are derived from our interpretation of the literature it is not clear which source inspired which guideline. However, if you want further information we would recommend reading the paper _"FTSPRoc: A process to alleviate the challenges of projects that use the follow-the-sun strategy"_ (Hess & Audy, 2012), as it covers most of the guidelines discussed on this webpage.

 As already noted previously, all these guidelines should be taken as a jumping off point when performing your daily handoff. They should not be seen as rules which you _need_ to follow. If they do not work for you and your team, please do not use them!  

#### Additions
Did we miss something? Do you have a guideline you believe should be added? Do you believe a guideline could be clearer? Please do let us know! [This site is open source, and can be found here.](https://github.com/geweldig/daily-handoff) You can either open a pull request yourself, or send us an issue informing us of what should be altered or added!

#### Sources
Carmel, E., Dubinsky, Y., & Espinosa, J. (2009). Follow the sun software development: New perspectives, conceptual foundation, and exploratory field study. *Proceedings of the 42nd Hawaii International Conference on System Sciences*, 1–9. <https://doi.org/10.1109/HICSS.2009.218>

Hess, E. R., & Audy, J. L. N. (2012). FTSProc: A process to alleviate the challenges of projects that use the follow-the-sun strategy. *2012 ieee seventh international conference on global software engineering*, 56–64. <https://doi.org/10.1109/ICGSE.2012.27>

Kroll, J., & Audy, J. L. N. (2012). Follow-the-sun strategy: A process for global software development. *2012 ieee seventh international conference on global software engineering workshops*, 76–78. <https://doi.org/10.1109/ICGSEW.2012.15>

Kroll, J., Hashmi, S. I., Richardson, I., & Audy, J. L. N. (2013). A systematic literature review of best practices and challenges in follow-the-sun software development. *2013 ieee 8th international conference on global software engineering workshops*, 18–23. <https://doi.org/10.1109/ICGSEW.2013.10>

Kroll, J., Richardson, I., Audy, J. L. N., & Fernandez, J. (2014). Handoffs management in follow-the-sun software projects: A case study. *2014 47th hawaii international conference on system sciences*, 331–339. <https://doi.org/10.1109/HICSS.2014.49>

Prashanth G.L, Santosh Malagi, Laurens Van Den Bercken, Ade Setyawan Sajim and Bernd Kreynen. (2019). Follow the Sun. Retrieved from <https://follow-the-sun.github.io/>

Treinen, J. J., & Miller-Frost, S. L. (2006). Following the sun: Case studies in global software development. *IBM Systems Journal*, *45*(4), 773–783. <https://doi.org/10.1147/sj.454.0773>

Zendesk. (2018). How to follow the sun and provide great global support. Retrieved from <https://relate.zendesk.com/education/follow-sun-provide-great-global-support/>

Zendesk. (2019). Improve remote support with a follow the sun model. Retrieved from <https://www.zendesk.nl/blog/improve-remote-support-follow-sun-model/>
