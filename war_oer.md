Widening Access to OERs (WAR) 
=============================

#### Abstract:

This project seeks to explore ways of increasing the “surface area” of open educational resources (OERs) through the use of: i) contextual content recommendations using technologies such as ad servers and Twitter bots, and ii) network building social recommendations through social network analysis. One quick way of identifying context is through textual analysis, using identified terms as hooks for relating OERs to other relevant documents. As well as exploring “frictionless” social and ad-served recommendations, the project will also seek to expand the horizons of OER usage outside the traditional, specifically educational context through the notion of “OER inside, educationally enriched” public consultation exercises such as may be used in support of evidence based policy development activities. 

#### Project Description:

The project is based around the ideas of increasing access to OERs wherever they may useful in part through the appropriation of technologies and techniques more usually associated with marketing and advertising.

The first aim is to demonstrate the extent to which certain technologically driven marketing and advertising approaches can be used to increase the targeted reach of OERs by treating the resources and links to the resources as if they were adverts or marketing communications. This will be achieved through using the tools of the marketers as the technical infrastructure for delivering targeted, contextualised educational content and links to such content. Drawing inspiration from the idea that the best ads are indistinguishable from relevant content, we  will explore the use of ad servers to deliver not adverts, per se, but links to contextually relevant OER content (“OER-ads”). Note that the intention is NOT to pay for the placement of ads to OER content, rather it is to make use of open source ad engines in order to deliver (links to) OER content as if they were ads. As well as exploring the extent to which ad servers can be used to place links to relevant OER content in a contextually meaningful way, we also hope to be able to report on the extent to which the sorts of campaign management tools supported by ad serving platforms may be relevant when reporting engagement with OERs. We will also explore the extent to social network analysis techniques inspired by ideas relating to audience segmentation can be used to support the discovery of experts and resources associated with particular topic areas, and how these approaches may be used at a personal level to support network building activities.

The second aim is to try to position OERs as resources that can be used in support of the formulation of, and engagement with, public consultation documents in evidence based policy areas. This will be achieved through trialling the delivery of “OER-ads” in the context of public consultation documents and demonstrates a use-case that seeks expand the traditional reach of OERs.

#### Dissemination

Project activities will be communicated via regular blog posts on both a specific project blog as well as personal blogs of project team members (where available). Discussion around project activity will be encouraged using online social networks such as Twitter and Google+. Software will be maintained within a public Github repository.

#### Use Case

1. Promoting the frictionless use of OERs in evidence based policy making and public consultations

One of the potential benefits of releasing educational resources in public and under open license is that they can be put to use outside the context of formal academic education. One possible use case for wider adoptions of OERs is in the support evidence based policy making, particularly in the context of public consultation exercises. OERs may have a role to play in the following areas:

a) in the initial review of the policy area or the shaping of policy options offered for consultation, evidence based research will often include desk based research and literature review. Educational materials, particularly at postgraduate level, may provide useful summaries of key points relevant to the policy area and provide a way in to the literature as well as the relevant academic community.

b) when framing the consultation document, explanatory sections or relevant examples may be required to set the context of policy area or review key technical issues. This provides a good opportunity for reusing educational resources in the production of a new resource (the consultation document).

c) public consultations provide not only an opportunity to engage an expert civic audience in policy making, but also an opportunity to engage with the citizenry more widely. As well as soliciting personal opinions and responses, the consultation exercise provides an opportunity to engage and even educate participants in the issues at stake in the policy area (issues which may include technical considerations as well as social, political, legal, ethical, cultural, historical and financial ones). The use of proven, academically sourced, independently produced educational resources may go some way to defusing claims that any such educational activity is in fact part of a propaganda exercise, and may provide an opportunity for citizens to participate in the consultation exercise from a better informed position than might otherwise have been the case.
 
Two scenarios within the use case will be considered:

1) using network analysis to identify: i) academic communities associated with a particular subject area through their social network activity, and, ii) related sets of resources through the analysis of the “social life” of resources, and then using the results of these analysis as a basis for socially mediated resource discovery. Strapline: helping folk find folk.

2) the automated, contextual recommendation of open educational resources in a variety of contexts, such as: i) annotations to recently published public consultation documents; ii) automated robot (“bot”) responses to social network updates taking place in an online discussion within a particular policy area that trigger a content recommendation with a high degree of confidence; iii) recommendations based on email content. Strapline: Related? [OER]


#### Technology Choice/Selection

Wherever possible, the project team will make use of as high level rapid prototyping tools as possible using free software tools. Where possible, open source software will be used and open standards adhered to. The intention here is twofold: firstly, to allow the project team to spend as much time as possible exploring the combination space of pre-existing building blocks joined together by simple representations (for example, Atom/RSS feeds, or JSON representations); secondly, to demonstrate as far as possible how much can be achieved at a rapid prototyping level without the need to write low level software code. If a particular combination is shown to work in principle, demonstrates a need and develops a user community, but is let down in terms of performance, then we can call on the coders to develop a robust, performance optimised version of the code against a working reference model, albeit one defined only at a high level of functional abstraction.
Work Packages

Note that the intention of the project is not focussed on the development of a production or even pilot service. The aim is to explore the bounds of what it possible using current tools and open up different ways of thinking about how technology might be appropriated and used in potentially unintended or unanticipated ways, in the context how OERs might be discovered, disseminated and have social activity around them tracked. The aim of the project it to try out things we haven't thought of yet because we arenlt familiar enough with the technology yet...

#### Ad Server

As befits a Rapid Innovation project, the majority of effort will be spent exploring:
1) the services offered by one or more ad servers such as OpenX;
2) the extent to which OER content or content fragments need packaging in order to publish them through the default ad server settings;
3) the extent to which the ad server can be appropriated in order to serve different content types to the typical range of advertising content atoms;
4) the extent to which any campaign management or reporting tools or ideas available within the ad server context suggest new ways for reporting on the tracking of OER usage and impact for OERs published more generally via institutional repositories, VLEs etc.

Publication of a variety of content types will be explored - text, images, video. In addition, we will explore the extent to which content at various levels of granularity can be published through both as-is and (where possible) “customised” versions of the ad-server. As source material, we intend to make use of the “raw” XML formatted OpenLearn materials from The Open University, not least because:

1) the XML format offers flexibility in terms of reuse and repackaging;
2) materials are published at unit level but can also be decomposed into smaller granularity components (such as individual sections, webpages, exercises etc); 
3) materials include a range of asset types (text, images, audio, video, Flash assets);
4) courses are tagged with both subject terms and parent module codes (codes that are also used on OU course catalogue/prospectus pages, and that appear in OU XCRI feeds).

If required, consultation documents will also be passed through semantic term extraction engine such as Reuter’s OpenCalais service in order to identify terms associated with each section of a document that can be used as subject query terms to drive the ad engine.

#### Twitter bot/autoresponder and GMail Contextual Ads 

Proof of concept demonstrations of a Twitter bot/autoresponder and GMail contextual ad server will be developed based primarily on simple term extraction and recognition with rule based content delivery. Using any available time remaining within this workpackage, we will explore the extent to which term/keyword extraction from tweets/email messages might be used to drive more complex OER content recommendations, for example via the ad server package, or via searches into custom search engines or OER repositories, etc.

#### Social Mapping

A major aim of this project is to explore ways of improving the discoverability of open educational content creators and resources in particular subject or interest areas via open social networks.

One of the most effective ways of discovering an appropriate resource for a particular task is to ask someone either explicitly or “invisibly” who has already gone through a discovery, review and selection process in a similar context what resource(s) they recommend. This project will explore a variety of techniques for mapping emergent social networks around: 1) shared educational resources; 2) academic subject areas. The generation of community maps can then be used to support social navigation of the subject area.

[ http://infteam.jiscinvolve.org/wp/2011/12/01/oerri_extract/ refers to online social profiles and social recommendations. ]

The project will also explore what we might term the social life of resources, identifying social networks that arise around particular resource instances (for example, the set of people who have all shared the same resource on a social bookmarking site such as Delicious or social network such as Twitter). Development will focus on creating a series of rapidly prototyped open source tools to support and manage active sharing of resources via social networks.

The social mapping tools will allow users to tap in to and develop open social sharing through:

- mapping of social networks around resources;
- mapping of social networks around interest areas;
- mapping of social networks around one or more known individuals.

The work will formalise, reconcile, rationalise and document work done to date informally and severally into a structured extensible toolkit that will be published as a bootstrap open source project on Github.

#### Social life of resources

1) Visualising folksonomic tags and social networks around socially bookmarked resources on Delicious:
- to develop and document a lightweight tool that can support sensemaking around: the tags used to describe known item resources; the often unrecognised emergent communities that form around a common resource (in sense of eg A, B, C and D all bookmark X; A and B follow each other but don’t know about C, who maybe follows A and B is and followed by D who also follows A and B).

- mapping delicious using thejit:
http://ouseful.open.ac.uk/blogarchive/014544.html
http://ouseful.open.ac.uk/blogarchive/014547.html
- mapping delicious using gephi:
http://blog.ouseful.info/2011/01/08/visualising-delicious-tag-communities-using-gephi/
http://blog.ouseful.info/2011/01/27/tags-associated-with-other-tags-on-delicious-bookmarked-resources/
- mapping delicious using TAGExplorer

The aim of this work package is to: a) explore ways of visually mapping emergent social and descriptive structures around bookmarked resources on delicious. Aim is: 1) develop framework architecture along lines of: get data, normalise representation, render; 2) demonstrate it in context of delicious and at least one other network (Twitter would be easy eg searching around sharing of link; also contrasts a dynamic “sharing now” analysis with a static/longer term analysis using Delicious?)? Maybe also provide a list of other social object networks (flickr, youtube etc) and extent to which their apis (can be forced to) export appropriate info? Use this as a working list for building additional importers if time allows?

2) Mapping tag communities: as more and more practitioners come online, provide tools that can support community development through eg friend recommendations based on social networks around particular subject areas. (Basically a catch all for the Twitter tagexplorer and social mapping stuff).

Twitter network community building/friend recommendation...

Community development around special interest subject areas;
Used for supporting community development/friend recommendation around particular subject areas, with interest in subject defined through engagement with a particular hashtag or sharing of a particular link (see previous use case), for example, or via implicit peer recommendation (folk followed by folk an individual trusts within a particular area).

Maybe work up ideas around triangulation? cf http://www.flickr.com/photos/psychemedia/6704245649


#### Visual analytics

Explore a series of visual analytics approaches relating to the tracking of social engagement with OERs, and referrals to institutional websites from socially shared links to OERs. Where possible, visual analytics tools will be constructed around data sourced from public APIs such as bit.ly, the Tiwtter search API, the Facebook Likes API, etc etc. The project will also explore the extent to which data from several sources maybe fused or combined. 

??Is there anywhere that reviews commercial offerings around social media analytics/dashboards? Is it possible to get free demos *and blog the results publisly*, or are the vendors protective over who gets to see what? I guess we also wouldn't want to be accused of reverse enginerring or copying commercial systems with free solutions hacked together from stuff on the web with bits of string and glue?!