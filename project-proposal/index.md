# Project Proposal


## Introduction

Web design is of great importance in historical conversation, but the archival of user interfaces is inadequately addressed. While web design is a fairly recent topic that has only come into existence since the 1990s, the development of this subject is rapid and volatile. There is an archival urgency of preserving UI in this context, as the transient nature of digital media makes it extremely vulnerable to being "lost". More specifically, while everything on the internet is preserved and persists after deletion, many forget that this applies more so to content rather than context- regular web scraper parsing is not documented or structured for the human eye. The subtle design decisions, navigation, user flow, and data organization is lost and forgotten when websites disappear or front-end codebases are overwritten.

In this paper, I will propose the development of a user interface archive that will track changes in popular digital media websites and applications. Users will be able to interact with different snapshots of various websites at different points in time, preserving "clips" rather than snapshots of popular social media platforms and websites. The user interface archive will focus on archiving the navigation and user flow of the website rather than content, accompanied by user stories and reports that provide historic context. Regular monitoring of various websites will be performed, and versions of a website will be stored upon any significant UI change, along with detailed accounts of each individual change. Community comment sections will be established for contributors to provide further information, opinions, and context about various design decisions on each individual version's page. These snapshots will be categorized and timelined in order to maintain a more established and documented web design archive.

## Methods (500 words)

Initially, working local copies of webpages will be downloaded to obtain the css, html, javascript, and images on the page. Various CLI commands can be utilized to perform this task, including wget -p -k [WEBSITEURL]. Since this command changes the downloaded files to refer to relative links while referring to the full internet address of files that were not downloaded, local browsing is possible. However, server side code will be lost through this process and limitations are brought upon dynamic code. HTTrack is a free software offline browser that can also be utilized to perform this same task. However, the aforementioned limitations in conjunction with copyright claims will make this portion of archival difficult.

Regardless, these local copies will be downloaded and stored during the development of this archive. In the interim, various video clips will be compiled for each version of a website, documenting any changes in web design, guiding viewers through various UI interactions, and modeling navigation flow for each website. A community comment section will exist for each website version for contributors to provide further information, opinions, and context about various design decisions.

During this time, research will be conducted in order to review Copyright laws and regulations in order to better understand the requirements for this project. Research will also have to be conducted in order to determine how best to utilize the downloaded website code to reproduce working copies of the website. After preliminary work is conducted to form this web design archive, various companies will be contacted in order to request for compliance in archival efforts, in the hopes that some websites will be open to providing bare-bone copies of the websites for archival purposes. This will yield results similar to the simulation of the very first website created by Berners-Lee [4].

After some time, research into web design can be conducted to gain insight on the digital and world history. Parallels in turning points and advancements in each topic can be analyzed and established, and these results can be disseminated by the website and in various digital history journals.

Existing resources such as http://web.archive.org will be utilized to facilitate the project and to access screenshots of various website at different points in time. Unfortunately, this resource preserves screenshots but does not provide further information about navigation and website flow. Similarly, Web Archiving and Digital Libraries publications will be used to research advances in technology, web scraping, and archiving. 

## Timeline (500 words)

The preliminary work for this code will consist of archiving the code for a large number of social media websites and storing them for archival purposes. These websites will have to be regularly monitored for any announcements about UI changes, and any subsequent versions will have to be stored with comments about each change. Video clips with voiceovers describing website navigation and flow will also be created during this time. It is expected that this initial process will take upwards of two months, with the expectation that a single individual will take 3 days to archive a single website. The individual would have to analyze the website, collect any necessary information, and create and edit multiple video files describing the user interface. At this pace, 10 versions of websites could be archived by one person each month. Crowdsourcing could be utilized as a means of collecting more collaborators, maintaining two content creators as the core of this archival effort.

During this time, a developer would be required to create the website for this archive, developing a website that would display timelines for the different versions of each website, with individual pages and comment sections for each version of the webpage. It is expected that such a webpage would take two months to build.

After the website is established, a team would be formed to deal with Copyright laws and legal ramifications. The team will contact various companies and websites to request for compliance with archival efforts by pitching the archive and demonstrating its potential. It is expected that these talks would take upwards of a year.

After this point, it is expected that we will have established a substantially sized archive, upon which further research can be conducted to draw ties and parallels to digital, human, and technological history.


## Importance (500 words)

#### The Beginning
Since the advent of the world wide web, the evolution of web design has been dramatic and rapid. We have come a long way from the single-column, text-based websites of olde- back when the first website was published on August 6th, 1991 by Tim Berners-Lee [2]. There are multiple prominent checkpoints in the history of the web design, which includes the advent of tables and multi-column websites back in the mid-1990s and the advent of Javascript [2]. This movement from text-based websites to dynamic multi-column websites was dramatic- but this was just the beginning.

#### Change
Then came the mid 2000's; a time when the websites that we have come to know today were first developed [3]. Top and left navigation bars, as well as CSS became the standard, and web designers discovered that there was a strong demand for categorization [3]. It was no longer acceptable for websites to consist of a single wall of unorganized text- no longer acceptable for users to have to endlessly scroll to get to the content that they desired. User needs evolved over time. The advent of mobile and tablet technology brought new challenges: how could we format websites to fit such a large range of devices and specifications while maintaining content parity [1]? The uprising of mobile devices led to the standardization of the 960 grid system and 12-column division, and the advent of Responsive Design [1]. Ironically enough, there has been a movement to flat design- replacing fancy graphics and prioritizing content, which is more reminiscent of the web in its humble beginnings [3].

#### Why is UI Important?

Documenting these changes is vital, as design matters. Changes in web design can be brought upon by multiple reasons, such as changes in user demographics and needs and advances in technology. They can be used to provide insight into the digital divide and digital evolution, turning points in UI history can be used to further analyze and explain historic moments in time. World and digital history can be used to provide context into the different UI design decisions and trends that exist at a point in time. Content on the web does not exist as disembodied heads but as an interface which structures our relations to data. Changes in the rapidly evolving field of web design reflect a change in the demands and needs of users, which has a broader scope in historical conversation. Turning points in web design are often associated with technological breakthroughs and changes in society. Arguably, these changes are a reflection of the the transformations brought upon by the digitalization of society. Research, documentation, and archival of this data is vital to better understand and enhance historical analysis and research.


##Budget
| Item | Description | Quantity | Cost | Total |
|---|---|---|---|---|
| Domain Name | Register the archiveofwebdesign.com | 1 | 14.99/year | 14.99/year |
| Web Hosting| Host website | 1 | 44.66/month | 535.92/year |
| Content Creator | Collaborators who will download local copies of webpages, document the current UI/changes, record and edit videos | 2 | 35,000/year | 70,000|
| Student Lawyer | Osgoode law school student to research Copyright laws and regulations in order to better understand the requirements for this project. | 1 | Volunteer | Volunteer |
| Developer | Create and maintain the website | 1 | 40,000/year | 40,000|
| Office space | School | 1 | Free | Free |
| Total | |  | | 110,550.91/year |


[1]:http://blog.froont.com/brief-history-of-web-design-for-designers/
[2]:https://blog.kissmetrics.com/evolution-of-web-design/
[3]:https://www.webalive.com.au/web-design-trends/
[4]:http://info.cern.ch/
