[![HC Logo](http://test2.human-connection.org/images/hc_logo_with_subline.svg)](http://start.humanconnection.org/)
# Human Connection - The Social Knowledge- and Action Network
[![Join the chat at https://gitter.im/HumanConnectionNetwork](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/HumanConnectionNetwork/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
![Source code status](https://img.shields.io/badge/source-closed-red.svg)

[Project site](http://start.humanconnection.org/) |
[Pre-Beta](http://beta.humanconnection.org/) |
[Bugtracker](http://beta.humanconnection.org/tools/bugs_tracker) |
[Donation](http://start.humanconnection.org/donate/)

__Dear Contributors__,

welcome and thank you for visiting the Human Connection Github Site. 
We are a small team, but with a great idea to develop a network that will serve the people.

Human Connection is an upcoming, new generation social network focused on local and global positive change. The collaborative non-profit platform is designed to promote the sharing of useful news, ideas, causes and values as well as smart know-how and experiences that can benefit everyone and meet mankind´s needs.

__On board are:__

- Dennis Hack, CEO
  - [info@humanconnection.org](mailto:info@humanconnection.org)

- Dennis Fasche, Frontend Developer & Andrey Buldakof, Backend Developer
  - [developer@humanconnection.org](mailto:developer@humanconnection.org)
  
## Contribute

To keep Human Connection growing and improving we need all help we can get. Whether you can contribute code, ideas, [translations](http://beta.humanconnection.org/tools/translation), [bug reports](http://beta.humanconnection.org/tools/bugs_tracker) or simply make a [donation](http://start.humanconnection.org/donate/)
, your help is welcome!
[![Join the chat at https://gitter.im/HumanConnectionNetwork](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/HumanConnectionNetwork/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# FAQ

## Why is the code still closed source?

We need time to rework and documentate the source. You can help us, when you are backend developer or software architect. For access to source code contact us at [developer@humanconnection.org](mailto:developer@humanconnection.org).

## What we have worked so far?

Early stage prototype > [Pre-Beta](http://beta.humanconnection.org/)

## Current used web technologies ?
- PHP
- MySQL
- jQuery

## Architecture idea

[![Architecture Preview](http://test2.human-connection.org/images/HC_network_architecture.png)]
(http://test2.human-connection.org/images/HC_network_architecture.png)

__Global API:__ API for communication between networks

__Interface API:__ API for frontend with ajax/websocket

__PHP class core:__ Base classes for all parts of the network

__HC World:__ Admin tools and manangement for example mail templates

__HC Javascript Object:__ JS Object to store all fronted data

## Next steps?

- Rework and documentate code
- Create Interface API
- Frontend prototype in [Vue.js 2.0](https://vuejs.org/)
- Communicaton service(Chat,Notification...)


## Is Human Connection charitable organization?

Our work is officially recognized by the German tax institution as to be promoting international understanding and attitude as well as tolerance in all spheres of culture

# [Pre-Beta](http://beta.humanconnection.org/) features functionality (updated: 27/12/16)
For further information please visit our [release notes] (http://beta.humanconnection.org/releases_note)
## User Account
- [x] Create new Account
- [x] Delete Account
- [x] Change Password
- [x] Email Confirmation (optional)
- [x] Change Language
- [x] Upload Avatar
- [x] Recover Password (confirmed)


## Post Tools

### Default Post
- [x] Create new post
- [x] Delete own Post
- [x] Upload attachment
- [x] Add Tags
- [x] Choose language
- [x] Change topic
- [x] Rate post(emojis)
- [x] Megaphone
- [x] Create automatic preview from an URL
- [x] Multiple asynchron file upload
  - [x] Drag&Drop
  - [x] Preview for audio file
  - [ ] Preview for PDF document
  - [x] Mark explicit content
  - [x] Choose picture title
- [ ] More Info
- [ ] Take Action



### Pro Contra Post
- [x] Create new Pro&Contra Discussion
- [x] Delete your own Pro&Contra Discussion
- [x] Add new Argument with attachment
- [x] Delete argument when 0 UpVote
  - [x] Author from the discussion
  - [x] Author from the argument
- [x] UpVote an argument

### Organization
- [x] Add new organization to OrgaDatabase(need confirmation)
- [x] Edit organization in the OrgaDatabase
- [x] Confirm from moderator
- [x] Search and filter

### Chat
- [x] Create new chatroom
- [x] Notification for new chat message
- [x] Notification for new private message
- [x] Upload attachment to chatroom
- [ ] Search chatrooms

### Dashboard
- [x] List all posts
- [x] Change column
- [x] Cockpit preview
- [x] Open single post in modal window


### Profile
- [x] Send private message
- [ ] List user posts 


### Translation tool
- [x] Translate string in multiple languages

More info here
<https://github.com/HumanConnection/documentation/wiki>
