<p align="center">
    <img src="https://i.imgur.com/FGC8LP5.png" />
</p>

<p align="center">
    Sluggo is a work-in-progress, free-and-open-source issue tracker built for 
    small teams.
</p>

Features include *(note: most features in progress)*:
* Issue tracking via tickets, including the ability to assign tickets, track
  custom statuses on tickets, and track subtickets.
* Flexible tagging system on tickets to enable easy division of issues between
  teams. 
* Intelligent homepage feeds which enable team members to easily view tasks they
  should work on, or may be of interest to them.
* Team member tracking, including information such as bios.
* Modern interfaces across all applications
* REST API out-of-the-box for custom scripting and integration, with first-class
  citizen support to your custom scripts - they'll interact with the tracker the
  same way the official applications do!
* Freely available under the Apache 2.0 License, enabling the flexibility to
  freely use, modify, and redistribute the tracker in your organization, or to
  contractors.

## Getting Started
Currently, the project is in early development (indev) stage, and thus is not
ready for use in organizations. 

However, a good place to start is the
[**Sluggo**](https://github.com/Sluggo-Issue-Tracker/Sluggo) repo, which
includes build scripts that assemble the backend/frontend together into a
complete web application.

As we get closer to an alpha stage, we will publish more guides on how to
configure the software.

## Projects
Sluggo is architected as a single REST API server which is capable of talking to
many different frontends. Thus, our projects are organized as follows:

### Backend (API)
Our API is available in the
[**Sluggo-API**](https://github.com/Sluggo-Issue-Tracker/Sluggo-API) repo. It's
built using Django and Python.

### Sluggo-SPA (Frontend, Web)

[**Sluggo-SPA**](https://github.com/Sluggo-Issue-Tracker/Sluggo-SPA) is the
primary web frontend for Sluggo. It's written in Vue 3 and TypeScript, and is
the frontend delivered through the official
[**Sluggo**](https://github.com/Sluggo-Issue-Tracker/Sluggo) distribution.

The web frontend serves as the main way to use Sluggo, and is intended to
receive feature support in tandem with the API. Our goal is to enable this
frontend to be used across desktop and mobile, and ensure universal usage of the
issue tracker.

### Sluggo-iOS (Frontend, Mobile, iOS)
[**Sluggo-iOS**](https://github.com/Sluggo-Issue-Tracker/Sluggo-iOS) is the
primary iOS frontend for Sluggo. It's written in Swift/SwiftUI, targeting iOS
16, and is in early development.

### Sluggo (Distribution/Infrastructure)
The [**Sluggo**](https://github.com/Sluggo-Issue-Tracker/Sluggo) repository
serves as the repo to store build code for the overall web application,
incorporating Sluggo-API and Sluggo-SPA into a usable and deployable
distribution.

## Project Wishlist
We currently do not have frontends for these platforms, but they are on our
radar for the long term:
* Android
* Slack
* Discord

## Contributing
We don't currently have good mechanisms to coordinate work with third-party
contributors, but we are working on getting ready for third-party contribution
soon. Watch this space.

## License
All Sluggo projects, as well as the overall distribution, are available under
the permissive Apache 2.0 LICENSE.
