---
title: I-D document process
layout: main
---

This is the home page of the [IETF](https://www.ietf.org/) Building Blocks for HTTP APIs (HTTPAPI) Working Group.

{: .banner}
This repository aims to create a diagram for I-D process that might be incorporated into the [IETF Datatracker](https://datatracker.ietf.org.

## Current and Upcoming Work

The group is currently working on the following specifications (in the GitHub repository indicated). The step in the progress graph with an orange circle represents the current state of the document. The pink colour indicates the status at the last IETF meeting :

#### [Problem Details for HTTP APIs](https://datatracker.ietf.org/doc/draft-ietf-httpapi-rfc7807bis/) - _[repository](https://github.com/ietf-wg-httpapi/rfc7807bis)_
```mermaid
graph LR
    classDef current fill:orange
    classDef lastIETF fill:pink

    WG-Adopt ---> WGLC
    WGLC ----> AD-Review
    AD-Review ---> IESG-Review
    IESG-Review --> IETF-LC
    class IETF-LC lastIETF
    IETF-LC --> IANA-Review 
    IETF-LC --draft-06--> IESG-Review((IESG-Review))
    class IESG-Review current
    IANA-Review --draft-04--> IESG-Review
    IESG-Review --> RFC-Editor
    RFC-Editor --> RFC

## Who Should Participate

We think that the following sorts of people will be able to effectively contribute to this work:

* **HTTP standards experts**: Those with deep understanding of and experience with the protocol
* **API practitioners**: Those who create, operate, and use HTTP APIs often
* **API vendors**: Those who provide products (commercial or Open Source) for serving, designing, securing, etc. APIs

Others are, of course, welcome to join.


## How to Participate

**Everyone who participates needs to understand the [IETF NOTE WELL](https://www.ietf.org/about/note-well/) conditions**. This includes the Intellectual Property terms, code of conduct, and other important policies.

If you plan on actively participating, subscribing to the [working group mailing list](https://www.ietf.org/mailman/listinfo/httpapi) is encouraged but not required.

Anyone can make comments or pull requests to the specification repositories (see above).
