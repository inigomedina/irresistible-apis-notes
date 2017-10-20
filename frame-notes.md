I started to develop an overall definition for platforms with irresistible APIs.
Platforms that offered amazing developer experiences.

I came to realize that an irresistible API needs more than excellent, consistent interfaces.
It's hard to succeed without great documentation, fantastic sample code, and an enthusiastic support structure.

     * great documentation
     * fantastic sample code
     * enthusiastic support structure

More recommendations:

     * treating your API as a first-class product, rather than shunting it off to the side of your main application


# Understanding web APIs

## What makes an API irresistible?

Many of APIs have being developed without the end user in mind. That results in a frustrating developer experience. And thus in a less successful web API.

Irresistible API:

	     * easy to use
	     * well documented
	     * well supported
	     * supported use cases are communicated and demonstrated well

A RESTful API is a platform that exposes data as resources on which to operate.

KEY: the developer experience for your customers is the most important factor in the success of your API.

## What is a web API?

Creating internal APIs without excellent documentation and tutorials will result in a huge support burden as your consumers struggle to write their implementation and flounder without understanding how best bet to use your APIs.

### Share goals with the users

A great developer experience begins with understanding your goals for your API communicating those to the developers you want to engange.

The more information you can share with them, the better able they will to decide whether they want to use your APIs.

Developers are giving you their time. You must give your best to build trust.


### Think about use cases and metrics

Possible metrics: user engagement, number of end users, use increase...

Providing tools, example code, and tutorials is also crucial to the developer experience.

KEY: put a basic goal. For instance, Twilio has a goal that any developer entering its site should be able to make a successful call from its system within five minutes. 5-10 minutes of great experience.


### Versioning

Versioning is one of the hardest facets of API management.

It's a part that is out of your control once you release a version. Once developer have made an integration or application with your system, they're not likely to me motivated to move to a new, incompatible version.

You need to take your first version seriously, knowing that you may be supporting that version for a long time.


### Marketing to developers

Make sure your marketing is targeted appropriately to developers. Developers want to play with toys.


### Common mistakes

#### Lack of vision

Netflix API version 1 want to generate money for the developers who create apps over it. Documentation was minimal, and pretty focused on what the API did rather than providing tutorials and use cases. The company's goal for the API was unfocused. And legal side of the story was not matched to promotion side: so the people cannot create the apps Netflix promised.

Through partner use of its APIs, integrating Netflix into various video devices, Netflix discovered that the API was an excellent way to establish market dominancec by creating efficient integrations into devices (xbox, smart tvs, etc.) and products (windows, etc.).

Netflix Open API declined step by step, starting to offer new features just to partners and device manufacturers. Eventually open API was decommissioned entirely.


#### Prioritizing the developer experience

Twitter started with a pretty basic API for developers. Twitter wanted they to create apps over it, and over the time Twitter started to take ideas from these apps. There was a moment in which Twitter created a new Terms of Use, not allowing such kind of integrations, and leaving the developers community pretty unhappy.

Twitter has made decisions too on backward-incompatible version changes, and it took a long time to "sunset" the older API.


#### Bad API design

Flick was one the first APIs. It was attempting to create a RESTful API, but it created an API that worked with actions instead of objects. Many developers had already implemented the first API, so in the time Flickr wanted to change for improving it, they couldn't use their apps.

Example:

	BAD: GET /photos/1234/delete_photo
	GOOD: GET /photos/1234

That kind of inconsistency isn't good for users since they don't understand and the system becomes a "surprise" system. Nobody wants it.

Nouns are always better than verbs, so that a developer is free to imagine new and creative uses for that data.

Your customers may be familiar with how REST APIs tend to work, and whenever you change the way things work, they may well get confused or make incorrect assumptions.

KEY: the more similar your API is to other existing APIs, the better the developer experience will be.


### API creation process


			API Creation Process
		---------------------------------------------------
		   |		|		|		|
		   |		|		|		|
		   |		|		|		|
		   |		|		|		|
		Business      Metrics         Use	      API Design
		Value	      		      Cases	      schema, model



#### Business Value

Why do we have an API?

    * increase user engagement?
    * establish industry leadership?
    * move activity off the main product to the API?
    * engage and retain partners?


#### Choose your metrics

It depends heavily on the business value.

You want to have a business value that's meaningful to people outside of the API team.
Metrics can play that role.

Example.


	Usage			Partner retention		Product integration
	-----			-----------------		-------------------

	- user updates		- dashboard integrations	- social/sharing activity
	- visitor statistics	- API use vs. Main product	- Dashboard integrations



#### Define your use cases

Partner engagement is also a strong candidate for use cases.