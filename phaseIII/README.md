# Phase III: Prototypes and User Testing

## Introduction

<!-- !!! Describe the general problem that the project is trying to
solve and the focus of this interval of work !!! -->

## Methods

Our team utilized **informal feedback** and **user tests** to gather
external insights into our designs.

The informal feedback first involved presenting a working product
demonstration to an audience (n=35) of undergraduate software
engineering students. During the demonstration, our software
engineering team (n=6) executed key tasks within the app to highlight
its different features. Following this showcase, our team asked the
audience a single question to collect feedback.

Our software engineering and usability teams collaborated to determine
which prompt question to present to the audience. Ultimately, we
selected a question that would provide insights into the accessibility
and layout of our user interface. Specifically, our software
engineering team asked, "Does the placement of the search bar feel
natural to you, or would you expect it somewhere else?" Our usability
team would consider the answers to this question when refining our
wireframes and prototypes.

Our team also conducted several user tests to receive both qualitative
and quantitative feedback from users regarding our user interface.
First, our team developed prototypes of our app that users could
interact with. Then, our team selected six (n=6) total participants
for our user tests. The user tests involved having one member of our
team moderate a 30-minute testing session with one of the
participants. In the sessions, our moderator provided the
prototype to the participant and assigned them several tasks to
complete by interacting with the prototype.

During the participant interactions, our moderator encouraged the
participant to voice their thoughts with every interaction. Our
moderator took notes of how the participant navigated our app and
summarized their thoughts. Following each task, our moderator asked
the participant to subjectively rate the difficulty of the task on a
scale from one to five to gather quantitative data about our
interface.

The actual procedure for the user tests involved more intricacies such
as confidentiality of participants. For full details regarding the
procedure of our user tests, see the [attached protocol
PDF](protocol.pdf).

<!-- !!! Describe research methods you used to discover new insights,
which explains the purpose of each. Provide enough detail that someone
would be able to faithfully reproduce your research. Only include
research methods in here, not design documents/techniques/artifacts
!!! -->

## Findings

<!-- !!! For each research method, detail each of the findings to
clarify new discoveries of users' needs !!! -->

Responses to our informal feedback implied that the search bar should
be the first interface element we present to users. Most respondents
disagreed with our placement of the search bar. One recommended that
we place the search bar at the top of the screen since most users read
from top to bottom. Another respondent appreciated our placement of
the search bar and requested no changes to the layout.

Among the six (n=6) participants from the user studies, two
participants failed to complete Task 1, while the other four
successfully completed Task 1. All six participants successfully
completed Tasks 2 through 5.

![Completion Rate Stacked Bar
Chart](completion-count-stacked-bar-chart.png)

Participant reports of perceived difficulty for tasks determined that
Task 2 challenged participants the most when using our app.
Participants found Task 3 to be the easiest task to complete. Detailed
counts for difficulty ratings are shown in the graph below:

![User-Perceived Difficulty for
Tasks](diff-ratings-stacked-bar-chart.png)

Qualitative findings from the user studies identified that
participants commonly read the tooltips describing the song parameters
(Energy, Danceability, Loudness) before interacting with the sliders
or buttons. One user also interacted with the "Help" button before
interacting with the main slider and button content. A common first
action for users is to explore our app's documentation and help
screens.

## Conclusions

<!-- !!! Discoveries derived from the methods and their findings.
Interpret how the findings translate into new insights into UX design
recommendations. Describe those recommendations and how they should
shape future work. In this section, include the new design
recommendations based on the latest user insights. !!! -->

Based on the informal feedback, our usability team recommends creating
a separate frame for when the user first opens the app. This frame
should only contain the song search bar. By isolating the search bar
in this introductory frame, users would have less confusion over which
element of the user interface they should interact with first.

Four participants did not interact with the sliders in Task 1.
Some participants commented that the sliders felt like a distraction
and that they should be removed from the main page and stored in the
Advanced Filters menu.

Only two participants ever used the Advanced Filters menu. Other
participants either only interacted with the three sliders on the main
page or never interacted with sliders.

None of the participants ever changed the input song. When
participants wanted contrast, they only adjusted the sliders.

Two participants identified that they expected the Export button to be
closer to the tables because the data they expect to export is related
to the table data.

## Caveats

The limited diversity of audience members restricted the depth of our
informal feedback. We presented our demonstration and questions to a
classroom of undergraduate software engineering students with an
approximate average age of 20. As such, many respondents had
above-average technical ability. Because of this, their perception of
the user interface could differ from the perception of less
technologically adept users.

The lack of demographic diversity in participants limited our insights
from the user tests. All six of our participants were male usability
engineering students with a background in technology and an
approximate average age of 20. Because of this, our user study is not
exhaustive of all possible users.

<!-- TODO: Add stimulations to the conclusions we made -->

<!-- !!! Considerations and/or limitations to the methods you chose
and the findings/conclusions drawn from them. In other words, give
warnings if there are limitations to your research such as not being
able to find enough users of a particular demographic, the methods not
being able to expose certain information, assumptions you made, etc.
!!! -->
