Introduction to Go
========

Go is an open source project developed by a team at Google and many 
[contributors](http://golang.org/CONTRIBUTORS) from the open source community.

Go is distributed under a [BSD-style license](http://golang.org/LICENSE).

What you will learn today
------------------------

- How to install Go for Mac (or windows if we must)
- Understanding of the cli tools
  - Download
  - Format (fmt)
  - Vet
  - Build
  - Test
  - Run
- Build CLI program using flags and environment variables
- Builds a simple HTTP API with JSON

Target Audience
----------

- Some programming experience in at least one language.
- Experience working at the command line


Resources
----------

- [GO+](https://plus.google.com/communities/114112804251407510571) This community is really picking up and has a lot of great posts and resources
- [go-nuts mailing list](https://groups.google.com/forum/#!forum/golang-nuts)
- [GO wiki](https://code.google.com/p/go-wiki/) A little about everything here.  Check here first if you are looking for more resources on go
- [golang.org](http://golang.org/) The official site for the GO language
- [Go Playground](http://play.golang.org/) Create and share go snippets
- [Go Tour](http://tour.golang.org/#1) Great way to learn go for the first time
- [Effective Go](http://golang.org/doc/effective_go.html) 
This is a MUST read for anybody learning go as an experienced developer
- [Additional Effective Go Notes](https://groups.google.com/forum/#!msg/golang-nuts/xbFLvvvvyUo/Iw8MC9MRX3YJ) 
- [10 Things you (probably) didn't know about go](http://goo.gl/L5lDv) - Amazing quick tips for making you a better go programmer.
This is a post in response to most people new to go and what they have an "alergic" reaction to.  MUST READ for new developers!
- [Golang Videos](http://blog.golang.org/2012/07/go-videos-from-google-io-2012.html) Amazing videos explaining key areas and concepts about go. The first video about Concurrency is amazing!
- [loader.io](http://loader.io/) Just released, this is a cloud based load testing tool.  Very impressive tool.
- [Go By Example](https://gobyexample.com/)
- [Golang-book](http://www.golang-book.com/)
- [Go book app spot](http://go-book.appspot.com/)


How to get help
--------------

- **Step 1:** Use [play.golang.org](http://play.golang.org) to create an example of your problem (make sure it runs if it's supposed to.
- **Step 2:** Post on  [GO+](https://plus.google.com/communities/114112804251407510571) or [go-nuts mailing list](https://groups.google.com/forum/#!forum/golang-nuts)
- **Step 3:** State your problem clearly, and link to the example on the go playground you creatd in step 1.
- Be respectful.  Most people have a willingness to help, but there are arrogant jerks out there that you can feel free to ignore.

If all else fails, you can use twitter to reach out to us.

About The Organizers
--------------

### Levi Cook
[linked-in](http://www.linkedin.com/in/levicook)
[twitter](https://twitter.com/levicook)
[g+](https://plus.google.com/100303354759468796601/posts)
[github](https://github.com/levicook)
> Levi Cook is a founder and Chief Technology Officer at [SupportLocal](http://www.supportlocal.com) and is in charge of leading the company’s engineering team.  
Mr. Cook is a seasoned open-source programmer. He has been a featured speaker at numerous programming conferences and regional software groups. 
He is also the author of a number of published articles, including IBM Developer Works. He has over 13 years of experience in developing software applications. 
He is a specialist in development practices required for building large-scale Internet-based applications. An Internet industry veteran, Mr. Cook has 
contributed to dozens of open source software projects and has helped many organizations adopt and succeed with agile developmental practices.
Prior to SupportLocal, Mr. Cook served as a lead developer for Alice.com, a top home supplies - direct from manufacturer, e- commerce company. 
At Alice, he led a diverse team of technicians and was responsible for large-scale rails development including real time demographic targeting 
engines and inventory and warehouse management systems.
Prior to [Alice](http://www.alice.com), Mr. Cook served as Development Engineer and Integration Architect at WEA Trust where he developed actuarial and 
claim and benefit management systems, as well as serving as a Senior IT Consultant at Isthmus Group and Greenbrier & Russell.

###Cory LaNou
[linked-in](http://www.linkedin.com/in/corylanou)
[twitter](https://twitter.com/corylanou)
[g+](https://plus.google.com/117716200974674608040/posts)
[github](https://github.com/corylanou)
>Cory LaNou is a Founder and Chief Information Officer at [SupportLocal](http://www.supportlocal.com) and is responsible for leading all application development efforts.
Prior to SupportLocal, Mr. LaNou was the founding engineer of LocalLaunch. At LocalLaunch, he was responsible for leading and implementing the first 
set of core architecture including customer relationship management tools, automated billing, product setup and configuration, API integrations with Google and Yahoo, 
in addition to all reporting interfaces. Mr. LaNou played the key role in the technology and architecture of the award-winning LocalLaunch software platform.
Mr. LaNou has over 14 years of industry experience in software and network engineering. Prior to LocalLaunch, Mr. Lanou founded and served as CIO of Pulsity, Inc. a 
leading Internet strategy firm. At Pulsity, Inc. he lead all application development efforts and oversaw the build of over a hundred Internet based software applications. 
Previously, Mr. Lanou served as lead application developer at Computer Discount Warehouse ([cdw.com](http://www.cdw.com)), where he played a key role in executing the 
strategy behind Microsoft’s first e-commerce partner venture, code named “Nitro”. Mr. LaNou also consulted with industry leaders such as 3com, Hewlett Packard, and IBM. 
He also architected and wrote CDW’s leading extranet and intranet solutions.
