# Phase II: Refining interaction and designing wireframes

## Introduction

In this phase, our team focused on defining our user interface layout and how users will interact with our app. While we had previously established several baseline features that our app should provide, the planned layout was incomplete and contained features differing from those we planned to implement. The second phase of our project sought to rectify such issues, focusing on simplifying the app's layout by more directly prioritizing specific features. Rather than reorganizing music playlists, our app's new goal is to create new playlists by providing song recommendations from a database.

## Methods

<!-- !!! Describe research methods you used to discover new insights, which explains the purpose of each. Provide enough detail that someone would be able to faithfully reproduce your research. Only include research methods in here, not design documents/techniques/artifacts !!! -->

Our team utilized **informal feedback** and **cognitive walkthroughs** to gather external insight into our designs.

The informal feedback first involved presenting a working product demonstration to an audience (n=35) of undergraduate software engineering students. During the demonstration, our software engineering team (n=6) executed key tasks within the app to highlight its different features. Following this showcase, our team asked the audience a single question to collect feedback.

Our software engineering and usability teams collaborated to determine which prompt question to present to the audience. Ultimately, we selected a question that would provide insights into requested future functionalities. Specifically, our software engineering team asked, "What characteristics would you care about most in the recommendation algorithm?" This question is especially relevant to us because our app revolves around recommending songs with similar characteristics to users.

Our team also conducted cognitive walkthroughs to receive qualitative feedback about the usability of our wireframes. First, our team submitted completed drafts for our wireframes in the communication platform Slack. Each team in the Slack discussion group (n=30) submitted wireframes, personas, and scenarios for review. The professor overseeing all the teams tasked each team with performing cognitive walkthroughs for two other apps. Therefore, the testers involved in the cognitive walkthrough for our app voluntarily provided their feedback, and our team did not choose which people would perform the cognitive walkthroughs.

In the posting for our cognitive walkthrough request, our team provided four personas that testers could use to contextualize their cognitive walkthroughs. Each persona had one scenario associated with them. Testers chose the persona and scenario that interested them the most. Each tester then assumed the role of the persona they chose and navigated through our wireframes aiming to complete the goal of the associated scenario.

At each step of completing the goal, testers noted which actions they took, describing whether their persona would understand what to do at each step and whether they could confirm that they made progress towards completing their goal.

Following each simulated persona's attempt to complete the designated goal, regardless of whether they succeeded or discontinued the process, the testers would reply to our posting in Slack with the notes they compiled during the cognitive walkthrough.

Our app received four cognitive walkthroughs that simulated three unique personas and scenarios. The testers did not provide solutions to their difficulties during their cognitive walkthrough. Instead, our usability team analyzed the confusion or satisfaction testers noted at each step and identified potential changes we could introduce to our wireframes to address these difficulties.

## Findings

Our software engineering team received six responses from the informal feedback. The first respondent asked for a locking mechanism for categories to receive consistent recommendations. The second respondent requested our app to incorporate genre similarity into our recommendation algorithm.

The informal feedback also provided the novel consideration of including a filter for ranges of release dates of songs. Moreover, another audience member requested a language filter to ensure users could receive recommendations in a common language. Finally, the last respondent concluded that our app lacked support for creating a queue of apps that tracks which songs the user wished to preserve.

Results from the cognitive walkthroughs identified areas of confusion in our app. One tester noted that the search bar to select a song did not signal a large enough call for action. The search bar's visual design suggests that users interact with the bar to query for information rather than being the core first step of using our app.

Another tester noted that our choice to initially populate our recommendation table with the words "No matching songs" created confusion for the user upon first entering the app. They also highlighted the ambiguity of different functionality in our app. The "Export" button does not provide enough information about what, where, or how our app exports information. The Plus and Minus buttons are ambiguous in how they will affect each list of songs. Finally, the user's confusion around how our app defined song metrics like "Liveliness" and "Loudness" indicated that our app did not provide sufficient context and clarification to support their understanding.

The third tester expressed satisfaction with specific features in the app, specifically, they enjoyed the ability to filter by song release year and save filter presents. Again, this tester expressed that users get overwhelmed and confused upon starting the app. Eventually, this tester discerned that the app required them to interact with the search bar as the first step. Ultimately, this tester concluded that their persona would understand how to make progress in our app and achieve their goal. However, they noted dissatisfaction with the Advance Filters being separated to a different page from the main page, inconveniently requiring the user to navigate between two pages.

The final cognitive walkthrough revealed confusion about our app's account and storage functionality. Our initial wireframes did not include a sign-up page, which made it ambiguous how a user would create and use an account. This feedback highlighted a key user need for storing generated playlists and other information. The feedback also highlighted that our app's current interaction sequence assumes the user has already identified which song they would use for the recommendation algorithm. This assumption overlooks the needs of users who do not have an input song in mind or are unfamiliar with song titles. The user also became frustrated because our app did not provide any way to remove a song that the user disliked from the recommendation list. Finally, the user could not determine whether they made an enjoyable playlist because our app lacked the functionality to play the song.

<!-- !!! For each research method, detail each of the findings to clarify new discoveries of users' needs !!! -->

## Conclusions

<!-- !!! Discoveries derived from the methods and their findings. Interpret how the findings translate into new insights into UX design recommendations. Describe those recommendations and how they should shape future work. In this section, include the new design recommendations based on the latest user insights. !!! -->

As a result of the findings from our research, we planned numerous changes for our current and future design artifacts. The informal feedback enabled us to fine-tune our basic and advanced filter systems more effectively to include criteria that our users care about, including date range and genre similarity filters. An interesting proposition is matching the language of lyrics, which will be a beneficial feature we will recommend to our software engineering team.

From the cognitive walkthrough, we observed flaws in our wireframe and planned improvements for them. Our wireframes should highlight that the search bar is necessary to initialize a playlist when no other tracks are present. We will make the song search a **call to action** by making it larger and positioning it more visibly within the interface. We will also add text indicating that the search bar is the starting point when opening the app. The cognitive walkthrough also reinforced the necessity to add tooltips to help users understand what specific metrics mean; our algorithm measures "danceability" and "liveliness," but if users cannot understand them, our app's song recommendations will fail to match their expectations. Finally, future wireframes will implement login and sign-up pages. Further, they will inform the user that an account is only required to access specific functionalities within the app.

## Caveats

The limited diversity of audience members restricted the depth of our informal feedback. We presented our demonstration and questions to a classroom of undergraduate software engineering students with an approximate average age of 20. As such, many respondents had above-average technical ability. Because of this, their feedback could potentially overlook introductory features that would be helpful for less adept users. Finally, our software engineering team showcased a demonstration of our product that lacked crucial features they planned to implement. Because of this, the audience could not fully comprehend our app's goals and possibilities.

Our cognitive walkthroughs may not have faithfully captured how our personas would have interacted with our app. Instead of allowing testers to navigate our app from their perspective, we asked them to take the role of the personas we provided. As such, we may have received responses that reflected the testers' interpretations of personas rather than genuine user behaviors, potentially limiting the accuracy and authenticity of the feedback collected.

Additionally, our wireframes lacked interactivity, and we did not provide any instruction to the testers. Those who performed the cognitive walkthroughs personally had to decipher how we intended our app to flow based exclusively on the Figma wireframes we created. Testers may not have fully understood how specific user actions transitioned between frames.

<!-- !!! Considerations and/or limitations to the methods you chose and the findings/conclusions drawn from them. In other words, give warnings if there are limitations to your research such as not being able to find enough users of a particular demographic, the methods not being able to expose certain information, assumptions you made, etc. !!! -->
