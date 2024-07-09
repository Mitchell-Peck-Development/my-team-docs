# In-App Linking

Many of MyTeam's features can be directly linked to, both from within the app as well as externally. Most features that support linking will also have link buttons, with buttons to copy either the internal link or external link, as well as a QR code that can be scanned by members to open the linked item.

To link to features in the app internally, in items like Announcements, the link scheme does not need anything in front of it. Just start with the feature, like `forms/view`.

To link to features in the app externally, like in a post online that you want your users to be able to open form responses from, the link scheme needs the app's url in front of it. Linking to `forms/view` would look like `myteam://route#to=forms/view`.

***

## Feature Link Schemes

## Forms

The Forms scheme is `forms`.

#### Link to a template to start a new submission

`forms/complete/{template-id}`

#### Link to form responses

`forms/view`

#### Link to responses for a particular template

`forms/view#temp={template-id}`

#### Link to a particular response

`forms/view/{submission-id}`

***

### Messages

The Messages scheme is `messages`.

#### Link to an existing chat

`messages/chat/{chat-id}`

#### Link to an existing group

`messages/group/{group-id}`

#### Link to an announcement

`messages#announcement={announcement-id}`

***

### Tasks

The Tasks scheme is `tasks`.

#### Link to a suite

`tasks/viewSuite/{suite-id}`

***

### Practices & Events

The Practices & Events scheme is `practices&events.`

***

### Hours

The Hours scheme is `hours`.

***

### Teams Registry

The Teams Registry scheme is `registry`.

#### Link to a team's registry profile

`registry#team={team-id}`.

***

### Settings

The Settings scheme is `settings`.

#### Link to a specific tab on the settings page

`settings#tab={"app"|"team"}`
