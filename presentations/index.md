---
layout: page
title: Presentations
tags: [javascript, emberjs, presentation]
modified: 2015-08-21T10:16:07.573882-07:00
comments: true
image:
  feature: moro_bay.jpg
  credit: DavidCMitchell
---
Here is a list of presentations I've done, or proposal ideas.

## Ember in the deep end

- Proposal for: [UtahJS Conf][utahjsconf]

**Blurb**: The Ember.js website says: "Ember.js is built for productivity. Designed with developer ergonomics in mind, its friendly APIs help you get your job done—fast." Join us as we go through a mission-critical Ember application and see if this is the case.

### What exactly is a 'large' JavaScript application?

> Before we begin, let us attempt to define what we mean when we refer to a JavaScript application as being significantly 'large'. This is a question I've found still challenges developers with many years of experience in the field and the answer to this can be quite subjective.
> 
> As an experiment, I asked a few intermediate developers to try providing their definition of it informally. One developer suggested 'a JavaScript application with over 100,000 LOC' whilst another suggested 'apps with over 1MB of JavaScript code written in-house'. Whilst valiant (if not scary) suggestions, both of these are incorrect as the size of a codebase does not always correlate to application complexity - those 100,000 LOC could easily represent quite trivial code.
> 
> My own definition may or may not be universally accepted, but I believe that it's closer to what a large application actually represents.
> 
> In my view, large-scale JavaScript apps are non-trivial applications requiring significant developer effort to maintain, where most heavy lifting of data manipulation and display falls to the browser.

Addy Osmani, http://addyosmani.com/largescalejavascript/

Large as in?

- Size (Codebase)
- Complexity
- Developer Count (Contributors)
- Business Centricity


### Project stats

- Project started: 16 December 2013
- Beta rollout: 4 February 2014
- Production rollout: 30 March 2014
- v2 refactor started: 11 November 2014
- v2 Beta rollout: 19 February 2015
- v2 Production rollout: 13 March 2015

### Code Breakdown

- .js LOC: 6,227
- .html LOC: 1,574
- .css LOC: 646
- Total LOC: 8,447

### Technology

- Ember version: 1.7.0
- Uses require.js for dependencies
- Major portions rewritten or refactored earlier this year (see the timeline)
- Uses EmberData to communicate via REST to C#.NET backend. C# in turn aggregates data from Salesforce(CRM) and Zuora(Billing & Subscription) via SOAP calls. It also created subscriptions and customer records in both.

### Challenges:

- Salesforce governor limits
- Salesforce query limits (both number of queries you can execute and table joins per query)
- Zuora API documentation
- Zuora subscription data model
- Salesforce frontend working with EmberJS (hint: it's not easy)
- Time 

### dsd

- Routing is your friend
- Customized RESTAdapter. Helped us do dev on local machines with disconnected data, or use data in any environment we wanted.
- proxy.php helped avoid CORS issues
- 


**Target Audience**: Experienced Developers

[utahjsconf]: http://conf.utahjs.com/schedule