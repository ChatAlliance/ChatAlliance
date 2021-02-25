# Chat Alliance

## What could be the cooperation space?

- unified identity 
- common identity directory
- common transport API
- forward messages to app with deep linking
- message pivoting
- compatibility of types
- common apps
- public conformance levels
- collaborative chat features comparison list
- open transport layers to other applications


### Unified Identity

The possibility to unify user identities per transport under one unique ID, used to address a user irrespective of transport.

This concept of unified identity does not impeed the user to have multiple such identities and is agnostic of individual privacy preferences.

### Common Identity Directory

Bidirectional connection user unique identity <-> transport identity.

Used by projects to forward messages to other projects.


### Forward messages to app with deep linking

Projects must support ChatAlliance deep linking:
- show users ChatAlliance apps that can be used to handle a certain message
- support a general message description format if the project cannot handle the message format itself
- forward the message to the app chosen by the user

#### Forward messages to app plugins

An app can forward a message to a specific plugin of another app.

### Message pivoting

Users registered with multiple transport services can act as a pivot for seding messages between users with no direct transport link.
E.g. A uses transport T1, B uses transport T2, C is registered with both T1 and T2. C can receive a message from A on T1 and forward it to B, on T2.

### Common apps

Universal clients:
- allow users to enable transports in order of preference
- allow users to exclude specific transports or categories of transports (e.g. centralized, server-based transports or non-encrypted transports)

### Conformance Levels

A table of ChatAlliance features must be kept, showing if and how each app/protocol implements them.

### Collaborative Feature Comparisons

A collaborative list of public chat features, used to objectively compare projects.

- every app has the liberty to propose features, that will be used to compare all projects
- announce other projects when new features are added, so they have time to respond, before making public announcements

Self-driven comparison lists such as https://threema.ch/en/messenger-comparison,  https://our.status.im/private-messengers-what-can-they-really-see/ will be collated.


### Open Transport To Other Applications

In other words, decouple the client from the transport, so other applications can use your transport layer.

For example, games can use one or more of the existing transport layers instead of creating their own siloed chats.


## Alliance Values and Principles

These are principles that each member promises to uphold, in relation to its ChatAlliance collaboration:

- all technical discussions are public
- all technical discussions are summarized in writing
- each technical idea that is implemented must be traceable to origin
- project implementation made after the ChatAlliance protocols must be open source, to be considered part of the ChatAlliance
- projects must publish an accurate list of features and trade-offs about themselves
- member projects must not contain features that are targeted to block one or more of the other alliance members
- member projects must support the alliance agreed upon API, in an exact manner


### Traceable to origin

- a public git-like system must be used, to keep the history of changes for both protocol implementation and architecture.
- an implemented idea must be traceable up to the initial person who proposed it, along with the discussions that molded that idea.



## Transport Protocols

### Transport API

## Chat Session Primitives

## Types

## Members


## Invited Members

* Signal - @signalapp
* Reddit - @reddit
* Status - @ethstatus
* Threema - @threemaapp
* Berty - @berty
* Whatsapp - @whatsapp


(https://twitter.com/lorecirstea/status/1364256404870225920)

* Element - @element_hq, https://twitter.com/mr_ligi/status/1364541931083223042
* Bluesky - @bluesky, https://twitter.com/_franzihei/status/1364541250255400960
