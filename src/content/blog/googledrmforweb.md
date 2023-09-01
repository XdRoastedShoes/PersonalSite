---
draft: false
title: "Google's DRM for the web"
snippet: " Yes, you read the title correct, Google is trying to introduce a DRM for the web and we have to make sure they fail."
publishDate: "2023-07-23 15:39"
category: "DRM"
author: "Vinayak Arora"
tags: [drm, open, web]
---
- Yes, you read the title correct, Google is trying to introduce a DRM for the web and we have to make sure they fail.
- In the last few weeks a new github repository has come to light. This Github repo is made by four engineers currently working at google and is entitled "Web-Environment-Integrity".
- In the introduction of the explainer they talk about how "trust is the backbone of the open internet" and the first example which they give for trust is the following-
- "- Users like visiting websites that are expensive to create and maintain, but they often want or
  need to do it without paying directly. These websites fund themselves with ads, but the advertisers  
  can only afford to pay for humans to see the ads, rather than robots. This creates a need for human  
  users to prove to websites that they're human, sometimes through tasks like challenges or logins."  
- In the first few lines the real reason for this spec has become apparent - money. Google has a big horse in the race with ads and they want to make sure that everyone sees ads and that the people who buy ads continue to buy even more.
- The solution they propose is to introduce a third party "attester" in the middle who can verify whether the client says who it is or not. The web server will then verify this "attestation" and decide to allow or not allow the user to browse the site. One example which they give of an "attester" is Google Play.
- Now the fundamental problem which I and many others have with this proposal is that it will allow too much power to fall into the hands of these already large mega corporations. This proposal also raises the concern that a lot of people will be locked out of the web entirely.
- Let's say Google Play is the attester on android, does that mean people with a custom android rom without google play services installed will not be allowed to browse the internet, or an older device with an older version of google play not be able to browse the web.
- We can also presume that the attesters on Windows will be Microsoft and on IOS and Mac OS it will be Apple, but what of Linux? Linux now days makes up 3% of the desktop market, does that mean 3% of the users of the open web will be blocked out of browsing the web.
- Also any tampering to the browser will be not allowed and it raises the concern of ad blockers, will ad blockers simply die out? and if that is the case what does Google plan to do of all the inappropriate ads which plague the web. There are ads for all kinds of things from scams to viruses, which exist even on Youtube. The proposal also has guts to mention security of the user, when it destroys one of the best security practices on the web.
- Even privacy focused browsers might have to implement this feature. If websites actually adopt this proposal then a user on a browser which does not implement the API will not be able browse these sites, which will in turn make the browsers pointless. The only real solution which I can think off is to cut off Google entirely and use something non chromium based. There is also a chance EU law will not allow for this to implemented but we will have to wait to see that.
- This proposal is one of the sad realities of the world which we live in today and it feels like a death by 100  cuts of the Open web. The open web originally was not conceived for this. It was made to ensure that people can have access to information and be independent with everyone having their own "chunk" on the web.