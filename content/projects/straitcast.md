---
title: "Straitcast"
date: 2018-05-01T15:30:19-04:00
draft: false
roles: ["Frontend Dev", "Backend Dev"]
duration: "3 Months"
tagline: "A no frills web-based podcast player built on react and powered by firebase"
card: "/images/straitcast_card.png"
headerImage: "/images/straitcast-macbook.png"
toc: false
gradient: "#e85184"
weight: 1

---

## About the project

Straitcast is a web based podcast player that aims to provide a convenient, no-frills user interface for searching and finding single podcast episodes. It is powered by React in the frontend,served by a Node.js server and deployed on a heroku dyno. Firebase is used as a caching layer.

## Tech Stack
- Frontend
    - React
    - Redux
- Backend
    - Node.js (Express)
- Database
    - Firebase

</br>
## App Screenshots
{{< figure src="/images/project-images/straitcast-image2.png" title="Straitcast search result screen">}}

{{< figure src="/images/project-images/straitcast-image1.png" title="Straitcast podcast channel screen">}}

## Project Links

*Note that the project is hosted in a free Heroku dyno, which sleeps when there is no traffic. It occasionally take additional time load due to the dyno waking up.*

---
{{< projectLink src="https://straitcast.herokuapp.com" >}}
    View Live Site
{{< /projectLink >}}

{{< projectLink src="https://github.com/garycheung13/straitcast" >}}
    Source Code
{{< /projectLink >}}