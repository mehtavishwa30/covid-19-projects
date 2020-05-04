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

* **[John Hunter](https://www.linkedin.com/in/john-hunter-1a4b65160/)** — *Development Lead*

* **[Lewis Garner](https://www.linkedin.com/in/lewis-garner-687586143/)** — *Product Manager*

* **[Sam Packham](https://www.linkedin.com/in/samuel-packham-883104195/)** — *Customer Success Manager*
 
* **[Chantelle Sawell](https://www.linkedin.com/in/chantelle-sawell-435272183/
)** — *Operations Manager*


## 2. [Survive Together](https://survivetogether.org/) 🔗

Due to the prevailing curfew in many countries, people living in certain areas are finding it difficult to get groceries, vegetables, fruits, and other essential items. Through this website, vendors can inform people about their services and people can state their needs as well.

At the moment, for some of us, the only way to obtain food and groceries is through deliveries. No one can go out of their house for weeks. While there are many delivery options in some areas, we noticed that most of the areas won't get anything. Those people are helpless. One of the main targets of this website is to gather enough information to identify those key areas and make sure everyone gets what they need.

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
* **Rob Callaham** - *Product Owner*
* **Josh Matthews** - *Product Owner*
* **Jake Gulick** - *Product Owner*

## 4. [Helpmate](https://play.google.com/store/apps/details?id=storesOpenIn.com) 🔗

Helpmate: we built a community benefiting app that helps you list local shops & enables you to volunteer for others during this lockdown. Using Helpmate, you can discover all the stores, kiranas, mandi’s and thelas around you that are open and selling essentials. When you go out shopping, you can add stores and help people around you. You also have an option to volunteer and shop essentials for the elderly people and others around you who are unable to step out.

Helpmate is a crowdsourced app that lists open stores as well as volunteers around you. It also provides an option for a user to add a store or become a volunteer to help the community. Elderly people & others, who can’t step out can call these volunteers & seek support.

During these tough times, it’s our resilience and compassion which will shine through. Let’s build a better community. Let’s do our bit 🙂

**Note**:

### Tech Stack 🥞

🏗 Built using Hasura, Firebase, Kotlin (Android app)

### Team Helpmate 💪

Helpmate is built by a small team of developer buddies who share the same empathy & zeal to bring us solutions through code in times of distress.

* **[Shankar](https://twitter.com/i_shankar)** - *Backend Developer*
* **[Bala](https://twitter.com/BalakrishnanPT)** - *Backend Developer*
* **[Naveen](https://twitter.com/NorthJaw)** - *Android Developer*

## Reduce Time-to-Market with Hasura

The above projects have served as useful case studies to learn how Hasura & its features help devlopers bring their ideas to life and build them faster.

### Fieldfusion 

Fieldfusion founder Graham Sawell took the project from conception to live in <24 hours. Further development work from the rest of the Fieldfusion team took the current build time to ~3 days.

The <24 hour development has proved a useful case study for Hasura enabling Fieldfusion to build and deploy effectively and at speed.

One of the great features of Hasura is the attention and thought that has gone into permission and role structures. Normally when faced with this kind of challenge the temptation is spin up yet another under-utilised VPS, go through the deployment steps, secure it, attach a domain, and create another 'thing' out there that goes untouched until you get a dependency security alert 6 months later. It's often hard as a developer to identify when you are truly separating concerns or dividing them. Hasura is the toolkit that we as developers need to allow us to focus what we do best, without worrying that technicalities are being obfuscated.

Making use of the public role that hasura exposes, we were able to rapidly create extra tables to support the data, create the gql queries and simply make the data available to the front-end through websockets without concern. The built-in aggregations work perfectly to display the statistical summary data that we needed in this instance.

We ended up opting to build a node.js microservice to poll and refresh the data because actions were still in beta, but all of our testing with Hasura actions has been great, my hope down the line we will be able to migrate.

### Survivetogether

1 week
We are using Hasura as the API for our system. Due to the time restrictions, we did not build any admin panel. Actually we don't have to since the Hasura console provided everything we need to handle to project for the time being.

### UrgentHub

1 week
We depend heavily on Hasura. CRUD automation GraphQL gets us up and running really fast. Events and actions help us model all of our backend logic in a clear and declarative way. The permissions model help us restrict access to the different parts of the system in a simple way too.

### Helpmate

12 days
The out of the box support for geography type solved most of the problems as it is a location aware app. I really wanted to use Actions, but the curernt set of features didn't warrant. I've said this multiple times: you folks are awesome!

___________________________________________________________________________________________________________

Let's celebrate the works of these creators and spread the word so that these solutions reach the people who need them and can inspire others who would want to build such solutions! 

If you are building one such project to extend help in any form to fight COVID-19, please let us know by tweeting to us at @[Hasura](https://twitter.com/HasuraHQ) or reaching us at *enter email id*.
