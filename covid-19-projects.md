# Covid-19 Projects

How we respond to challenging times is what makes us the most human. Several of us are taking this time to give back to the community by putting in efforts to build solutions to help others in these times. In the past few months, the community has contributed to myriads of initiatives related to COVID-19. 

We want to show our love by amplifying the work of some of the creators who are contributing to this collective effort. Here are a few of many such projects that exemplify how the community is responding to COVID-19 by building web & software solutions. 

## 1. [Fieldfusion](https://corona.fieldfusion.io/) 🔗

Fieldfusion is a free & online tool built to help Field Service professionals make faster, data-driven decisions and ensure the safety of their technicians by analysing the effect of COVID-19 in the region of operation. Although, Fieldfusion's primary aim is to help Field Service professionals, it is also freely available for public usage.

Fieldfusion enables users to upload/enter and search for a specific postal code to help visualise the number of active COVID-19 cases in the region and analyse how severely coronavirus is affecting various geographic regions in the UK. The tool utilises publicly available data from Public Health England (PHE), the Office for National Statistics (ONS), and Ordnance Survey (OS). Fieldfusion lists the most severely affected regions by comparing the number of confirmed cases to the total population in specific areas.

**Note**: Fieldfusion is currently only for use in UK and the accuracy of the data is limited to England.
 

### Tech Stack 🥞

🏗 Built using Hasura, Vue.js, Websockets, & Netlify.


### Team Fieldfusion 💪

* **[Graham Sawell](https://www.linkedin.com/in/grahamsawell/)** — *Founder and Head of Development at Fieldfusion*
* **[Dave Westbrook](https://www.linkedin.com/in/david-westbrook-60742b3b/)** — *Founder and Head of Development at Fieldfusion*
* **[John Hunter](https://www.linkedin.com/in/john-hunter-1a4b65160/)** — *Development Lead*
* **[Lewis Garner](https://www.linkedin.com/in/lewis-garner-687586143/)** — *Product Manager*
* **[Sam Packham](https://www.linkedin.com/in/samuel-packham-883104195/)** — *Customer Success Manager*
* **[Chantelle Sawell](https://www.linkedin.com/in/chantelle-sawell-435272183/
)** — *Operations Manager*


## 2. [Survive Together](https://survivetogether.org/) 🔗

As a result of the lockdowns in certain countries, the citizens heavily rely on home deliveries for essential items. The Surive Together website helps ou discover open stores, services, & areas in which these servies are available. You can add your requirements under a particular store listed by a vendor & the service will appropriately be provided to you. 

**Note**: survivetogether.org is currently only for use in Sri Lanka.


### Tech Stack 🥞

🏗 Built using React, Hasura, & TypeScript.


### Team Survive Together 💪

survivetogether.org is brought to us by a 4 member team working at LeafyCode, a startup based in Sri Lanka.

* **[Nipun Ravisara](https://github.com/RavisaraDev)** - *Design and UI development*
* **[Kalana Elapatha](https://github.com/kalanaelapatha)** - *Translations*
* **Navoda Thathsarani** - *Translations and content*
* **[Pubudu Kodikara](https://github.com/thpubs/)** - *Development*

### Open Source 🗃

The code has been made open-source by the team for developers to use and draw inspiration from. If you are looking to build something similar to help people in this global pandemic, check out their [GitHub repository](https://github.com/LeafyCode/survive-together-web).


## 3. [Urgent Hub](https://urgent-hub.com/) 🔗

Urgent Hub is a web app built to aid safe COVID-19 screening by connecting patients and medical care providers. As of end of April Urgent Hubs support 2.5 million people between dental and eye care in states of Arkansas and Colorado. Urgent Hub was built in the short span of 6 days.

**Note**: Urgent Hub is currently available in Arkansas, Colorado (USA).


### Tech Stack 🥞

🏗 Built using Views, React, Circle CI, Hasura, Postgres, Node, Lambdas, AWS Fargate, Docker, Amplitude.


### Team Urgent Hub 💪

* **Dario Cravero (@dariocravero)** - *Product Engineer*
* **Tom Parandyk (@tombreakshit)** - *Product Designer*
* **Rob Callaham** - *Product Owner*
* **Josh Matthews** - *Product Owner*
* **Jake Gulick** - *Product Owner*

## 4. [Helpmate](https://play.google.com/store/apps/details?id=storesOpenIn.com) 🔗


Helpmate is a crowdsourced app that helps you list local stores that sell essentials as open including hawkers & small shops. The next time you go out shopping, help people find the store you shopped from by adding it on Helpmate. With Helpmate you can also become a volunter to help your neighbourhood. Elderly people & others, who can’t step out can call volunteers & seek support. Helpmate is doing its bit. Let's do ours with Helpmate. 💜

**Note**: Helpmate is a hyper-local app for use in only a small region of India.

### Tech Stack 🥞

🏗 Built using Hasura, Firebase, Kotlin (Android app)

### Team Helpmate 💪

Helpmate is built by a small team of developer buddies who share the same empathy & zeal to bring us solutions through code in times of distress.

* **[Shankar](https://twitter.com/i_shankar)** - *Backend Developer*
* **[Bala](https://twitter.com/BalakrishnanPT)** - *Backend Developer*
* **[Naveen](https://twitter.com/NorthJaw)** - *Android Developer*

## Reduce Time-to-Market with Hasura 🚀

The above projects have served as useful case studies to learn how Hasura & its features help devlopers bring their ideas to life and build them faster. Let's see what our users had to say about their experience building with Hasura! 

### Fieldfusion 

Fieldfusion founder Graham Sawell took the project from conception to live in <24 hours. Further development work from the rest of the Fieldfusion team took the current build time to ~3 days.

"One of the great features of Hasura is the attention and thought that has gone into permission and role structures. Making use of the public role that hasura exposes, we were able to rapidly create extra tables to support the data, create the gql queries and simply make the data available to the front-end through websockets without concern.

It's often hard as a developer to identify when you are truly separating concerns or dividing them. Hasura is the toolkit that we as developers need to allow us to focus what we do best, without worrying about technicalities being obfuscated."

### Survivetogether

The developers at Leafycode were able to build & deploy the survivetogether.org website in the short span of a week.

"We are using Hasura as the API for our system. Due to the time restrictions, we did not build any admin panel. Actually, we don't have to since the Hasura console provided everything we need to handle to project for the time being."

### UrgentHub

In a similar timeframe, UrgentHub was brought to life with the help of Hasura.

"We depend heavily on Hasura. CRUD automation GraphQL gets us up and running really fast. Events and actions helped us model all of our backend logic in a clear and declarative way. The permissions model helped us restrict access to the different parts of the system in a simple way too."

### Helpmate

"The out of the box support for geography type solved most of the problems as it is a location aware app. I've said this multiple times: you folks are awesome!".

Helpmate was built in 12 days and one of he backend developers had a very interesting bit to share about how he built the entire backend in no time.

"One of my friends approached me with this idea, couple of weeks ago. He's a designer and doesn't have much understanding of backend architechtures, so he asked me to build it. The amazing thing here is,  I was able to build the whole backend before he could finish the wireframes. All thanks to you folks!"

___________________________________________________________________________________________________________

Let's celebrate the works of these creators and spread the word so that these solutions reach the people who need them and can inspire others who would want to build such solutions! 

If you are building one such project to extend help in any form to fight COVID-19, please let us know by tweeting to us at @[Hasura](https://twitter.com/HasuraHQ) or reaching us at *enter email id*.
