# Features and specification

## Context
When people are traveling, or perhaps once they have returned from a trip, they want to casually share their experiences in a low stakes/pressure way with audiences to 1) have a travel log for themselves of their travel events and 2) keep their friends updated.

## Users
**PROFILE-01:** As someone who travels casually, PROFILE-01 is someone who wants a fast way to combine all their travel highlights and updates into one place so their friends can come along the journey with themm, but not be bombarded by frequent updates over more commonplace applications. They desire a low-pressure location to share their pictures, thoughts, and recommendations. Today, they usually text photos, stories, and specific location recommendations directly over messaging apps. This current approach is unsatisfying because sending scattered text messages is fragmented and could be annoying for the receiver (pressure to respond). One thing to consider is the desire for a response, so including a comment section so the sharing is more interactive for both parties.

**PROFILE-02:** As an active social media user who enjoys documenting their travels, they want a way to evaluate generate visually appealing travel logs that match design standards but maybe doesn't have a image restriction or as much of a pressure-environment. They want a place to showcase highlights into curated reviews that document their trip aesthetically. They searched for itinerary ideas from numerous tools and is meticulous with photos they takes from their events. This current approach is constrained because they are limited to high-pressure sharing environments where shared thoughts are often short or non-existent.

## Scope
Included behavior and explicit non-goals:

**Included behavior**
* Users select a category (Food, Activity, Landmark) and choose from previously pictures items what they liked more in that category from that trip to auto-calculate an item score.
* Closing out a completed trip then allows the user to rank that city/location against past trips including a map that shows their top ranked cities. 
* Trip logs require start/end dates and have a "Traveled With" companion tag so tagged friends can link trip dates while still having their own rankings.
* Shareable link prompted after you finish out a trip to share with friends.

**Explicit non-goals:**
* No sort of traveling booking done through the application.
* No chat in app, only commenting. 

### Kano hypotheses
Provide at least six features. For each, name the user segment, date, category, and evidence-based reasoning. These are tentative hypotheses, not validated survey findings.

| Feature ID | Feature | Kano hypothesis | Segment / date | Evidence and reasoning |
|---|---|---|---|---|
| F-01 | Category-Based Ranking | Must-be | 01, 02 | Main app usage, people can rank things they've done |
| F-02 | Text Reviews | Must-be | 01, 02 | Main app usage, people want to share their thoughts on events |
| F-03 | Upload/Sharing | Performance | 01 | Sharing with friends over text |
| F-04 | "Traveled with" | Attractive | 01, 02 | Can coincide their updates with their friends that they travel with |
| F-05 | Activity Feed | Indifferent | 02 | Can appeal to the social and friend sharing aspect, but not to make that a priority in the app |
| F-06 | In-App Photo Editing | Indifferent | 01, 02 | Neither expressed a desire for it, but common for many social-related apps |

## Behavior
Sequence, conditions, actions, and visible outcomes:
* **Sequence:** The user starts a trip by selecting a location and logging start dates. As they progress through their trip, they add pictures of their activities, landmarks they visit, and food they eat. They then rank each thing in their respective categories and at the end they can see their food rank list, etc. Finally, they can mark their trip complete and rank the city against their over trips. The user is also prompted at the end, something along the lines of: "Yay! Trip ended! Share with friends?"
* **Conditions:** A user can't rank things unless they have other thinks to rank against (activities and city)
* **Actions:** They input their start date, select category, input pictures, write reviews, rank spots. They can tag companions and rank the final city.
* **Visible outcomes:** It calculates a rank number for each thing and city rankings after you select. It also shows the cities you've visited on a map. A scrolling feed of your own with reviews and things you've done compiled in one place.

## Constraints
* **Platform:** App ideally that would be supported on IOS and Android.
* **Data:** Share what you want to, need email/phone number to register account.
* **Privacy:** Location sharing so you don't have to manually input city.
* **Relevant limits:** Ability to work offline, if not able to upload then at least have save draft options. 

## Acceptance

- Ubiquitous: The system shall [show the number ranking of all things uploaded].
- Event-driven: When [an item is ranked], the system shall [automatically suggest other things they've done in that category/city combo to rank against and then auto-calculate a rank number].
- State-driven: While [a trip is in progress], the system shall [mark the city on a map with its ranking against others].
- Unwanted: If [start/end dates aren't selected], then the system shall [not prompt ranking and will simply just allow you to upload a picture/review].
- Optional: Where [users select "Traveled with"], the system shall [prompt the companion to start the same trip with them].

## Handoff reflection
If I handed this document off, they would still need to understand how to calculate the ranking number with the ranking system. In addition, what each page of the app would look like along with what would be highlighted on each page.

## AI assistance
I used AI to help me summarize my interview bullets a bit and made sure to rewrite the summary afterwards. I also used it to help me ideate some new things to build upon the application idea I had.
