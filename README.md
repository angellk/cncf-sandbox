# Sandbox
![CNCF Sandbox](https://github.com/cncf/artwork/blob/master/other/cncf-sandbox/horizontal/color/cncf-sandbox-horizontal-color.png)

This repository is designed to allow projects seeking to join the CNCF as a :package: [Sandbox](https://github.com/cncf/toc/blob/main/process/sandbox.md) :package: project to submit their applications. It is still a work in progress and we welcome PRs on this repo to automate assignments, improve the process, etc.  If you have any questions, please reach out in the [TOC Slack Channel](https://cloud-native.slack.com/archives/C0MP69YF4) or file an [issue](https://github.com/cncf/sandbox/issues/new) on the repo.

For information on the sandbox process please check out the [details on our sandbox application process below](#how-applications-are-reviewed).

## How to apply

Applying is as easy as 1-2-3!

1. Open a new [Sandbox Application](https://github.com/cncf/sandbox/issues/new) using the linked issue form. 
1. Complete all sections of the form.
1. Submit the issue.

## What's next?

Your project's application is placed in the backlog for triaging. You can view the status of your application and others at anytime by checking out our [Project Board](https://github.com/orgs/cncf/projects/14).

When the TOC meets to review applications, more details on [frequency here](#frequency), your application will be pulled up and discussed. Your application may receive one of several statuses:
* `New` - It is a brand new application and is in the backlog for an upcoming review.
* `Approved` - The application has been reviewed and been approved by the TOC. The issue will be closed.
* `Declined` - The application has been reviewed and been declined by the TOC. The comments on the issue will reflect the TOC decision and the issue will be closed.
* `Need-Info` - The application has been reviewed and requires more information in order for the TOC to further discuss the application.  For instructions on what to do, please jump down to [Need-Info](#Need-Info).
* `TAG-Assigned` - The application has been reviewed and the TOC would like a TAG to review or consult with the project prior to further discussions.  For instructions on what to do, please jump down to [TAG-Assigned](#TAG-Assigned).
* `Postponed` - The application has been reviewed and the TOC has determined the project (as it exists at time of review) is not ready for inclusion within the CNCF. For instructions on what to do, please jump down to [Postponed](#Postponed)
* `Returning` - The application has been reviewed previously, was affixed a `Need-Info` or `TAG-Assigned` label, and that work has been completed and is ready for re-review.  For instructions on what to do, please jump down to [Returning](#Returning).

### Label statuses defined

#### Need Info

If your project is assigned a `Need-Info` label, the TOC will comment on the issue with the specific additional information needed.  It will then be placed in the `Waiting` status of the [Project Board](https://github.com/orgs/cncf/projects/14).

Please provide the additional information requested as a comment on the issue. Once you have done this, **remove the `Need-Info` label and affix the `Returning` label**, this lets the TOC know it is ready to be reviewed again. It will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

#### TAG Assigned

If your project is assigned an `TAG-Assigned` label, the TOC will comment which TAG(s) and provide specific details on what is requested. The TAG Co-Chair(s) will be tagged on the issue. Depending on the details of the comment, the TAG or the project will update the issue with a comment containing any pertinent information. This may include links to a presentation recording, as summary of a discussion with the TAG, or recommendations.

Once a comment has been added,  **remove the `TAG-Assigned` label and affix the `Returning` label**, this lets the TOC know it is ready to be reviewed again. It will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

##### TAG(s)

If the issue is affixed the `TAG-Assigned` label and you have been assigned the issue as a TAG co-chair, please review the comments for the specific asks regarding the project. When completed, please provide a comment containing any pertinent information. This may include links to a presentation recording, as summary of a discussion with the TAG, or recommendations. 

Once the comment has been added,  **remove the `TAG-Assigned` label and affix the `Returning` label**, this lets the TOC know it is ready to be reviewed again. It will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

#### Postponed
 
 If the issue has been affixed with the `Postponed` label it will be closed as the TOC has determined the project at the time of discussion is not ready for inclusion into the CNCF. There will be a comment on the issue that annotates the expectations in order for the project to *reopen the issue and apply the `Returning` label* to be re-reviewed by the TOC. When the project has met the conditions or resolved the expectations laid out on the issue, the author of the issue should (1) reopen the issue (2) add the `Returning` label and (3) remove the `Postponed` label. This will place the issue on the list for an upcoming review.

#### Returning

Issues affixed with the `Returning` label are placed in the `Upcoming` status on the [Project Board](https://github.com/orgs/cncf/projects/14) for an updated discussion at the next Sandbox Application meeting.

## How applications are reviewed

### Frequency

The TOC reviews sandbox applications approximately **every two months** as of June 2020 in a non-public meeting; referred to as "session" hereafter. 

### Quantity

The TOC attempts to work through approximately 7-10 applications per session. How many are actually reviewed in a session varies greatly between each session as every project is unique and different areas of attention may be elevated for more in depth discussion depending on the nature and function of the project.

Each TOC member prepares for these sessions by performing an independent review of those projects scheduled for discussion at the next meeting. They'll keep their notes on hand for when the project is up for discussion.

### Review order

Sandbox applications are traditionally reviewed in a First In, First Out (FIFO) ordering as they appear on the **🏗 Upcoming** Column of the [Sandbox Application Board](https://github.com/orgs/cncf/projects/14/views/1) by their corresponding issue number. The only exception is where projects are `Returning` for review. Projects that are `Returning` are prioritized for re-review as they had previously been subject to a review and have completed their outstanding asks.

Applications are moved from `New` to `Upcoming` approximately two weeks prior to the next scheduled session by the TOC or support staff.

### Discussions and decision

During the course of the session, the TOC will actively discuss the project based on the information provided in the issue as well as other observations the TOC has about the project. Those observations vary greatly and may be subject to each TOC member's area of domain expertise, personal experience, community feedback, or other factors. During the course of active discussion, the TOC may identify areas the project needs to work on, complete, or allow to happen that could inhibit its acceptance into the CNCF. These areas will be captured succinctly and affixed the corresponding label ([see Label statuses defined](#label-statuses-defined) for more information). The issue will also receive a comment that details the additional areas that correspond with the label.

#### Examples

All project and organization names in the examples are fictional and are not intended to reflect any existing project past or present.

##### Scuppers

The TOC reviews and discusses Scuppers. The TOC determines Scuppers doesnt have enough clear direction or indicators on what the project does or how it does it. The TOC concurs that Scuppers should present at the correct TAG to gather input to improve the clarity of what the project does and improve the documentation on how it does it in a cloud native way. The TOC will summarize the two items that need completed on the issue as checkbox items, affix the `Need-Info` and `TAG-Assigned` label. The TAG chairs are then tagged on the issue by their GitHub handle. The application is then moved to the **⏲ Waiting** Column of the [Sandbox Application Board](https://github.com/orgs/cncf/projects/14/views/1). Scuppers then presents to the assigned TAG and incorporates their feedback into the project information and updates the application issue with the more clear details. They or the TAG may then check off the corresponding item and affix the `Returning` label. The project board will then move the issue to the **🏗 Upcoming** Column of the [Sandbox Application Board](https://github.com/orgs/cncf/projects/14/views/1) so it is included at the next session.

##### Isobars

The TOC reviews and discusses Isobars. The TOC determines that Isobars is a *very* early project; having existed less than 6 months, and doesn't appear to clearly decoupled from the sponsoring company's flagship product. The TOC affixes the `Postponed` label and comments on the issue the need for greater maturity, more distinguished separation of the project from the product, and an estimated timeframe to reopen the issue for re-review. The issue is then closed. The project maintainers work for several months to decouple the project from the product and during that time the project fills out its documentation, use cases, and begins growing its community. The maintainers then reopen the issue, edit the content of the issue to reflect the changes or comment with updates, add the `Returning` label and remove the `Postponed` label. Isobars is then placed on the **🏗 Upcoming** Column of the [Sandbox Application Board](https://github.com/orgs/cncf/projects/14/views/1) so it is included at the next session.

## Acceptance and annual reviews

Once projects are accepted into the Sandbox, projects are subject to an [Annual Review](https://github.com/cncf/toc/blob/main/process/sandbox-annual-review.md).
