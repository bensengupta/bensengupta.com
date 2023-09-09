---
title: 'Co-op Work Term Report - Wave'
description: 'Co-op Work Term Report - Summer 2023 - Wave Financial'
pubDate: 'Sept 04 2023'
heroImage: '/images/blog-coop-work-term-report-1-wave.jpg'
---

This summer I had the opportunity to work at Wave Financial, a Toronto-based company that provides financial software for small businesses.

Wave advertises itself as a one-stop shop for all things small business money management. Wave offers a wide array of services, including invoicing & estimates, payments, accounting, and payroll to name a few.

###### Wave's Single Page App (SPA)

![Wave's React SPA](/images/blog-coop-work-term-report-1-spa.png)

During my onboarding and for the first two months of my co-op, I joined the Payments team that is tasked with overseeing payment transactions and integrating with third-party partners to enable businesses to receive payments via Apple Pay, credit card, debit (ACH/EFT), and more. While on the Payments team, I worked on adding scheduled debit (recurring ACH) as a payment method for recurring invoices.

At around the halfway point, I worked closely with the ARCS team, which I eventually joined, to migrate estimates from legacy Django views to Wave’s Single Page App (SPA) built with React.

#### Goals and learning outcomes

##### Contribute to frontend technologies

I’ve long had a passion of discovering and tinkering with new technologies and features. I especially love exploring different patterns and tools for building websites. As a result, one of my goals after I joined Wave was to contribute towards bettering the frontend tech stack.

I joined the JS working group where I learnt & shared best practices, bounced ideas, and made suggestions about standardizing functionality that was being re-invented in numerous places in the codebase.

While I was implementing my first few tickets, I would often run into minor annoyances, which I would later fix. An area that affected me the most while iterating on my code changes was testing, which would often take 10+ seconds to run a single unit test. I enabled ts-jest’s `isolatedModules` flag for a 40-50% speedup across our entire test suite! I fixed logic that caused flaky tests in a widely used component in Wave’s UI library to minimize workflow interruptions. I made upgrades to Prettier, TypeScript, Jest, and Webpack to take advantage of the latest features and better performance.

I think it’s safe to say I have accomplished this goal.

##### Collaborate and sync up with teammates

Another goal I set was to collaborate with teammates. This was an area I was a little worried about because up until I started work this summer, most of my work was done on my own without much involvement with others. In hindsight, I realized that being able to work through problems on my own is a great asset! I also found that I have a good grasp on when to reach out for help. That being said, frontend work is my greatest expertise, so I feel that I rarely need to request help. One of the milestones I had down was that other teammates would ask to sync up with me to work on their problems. That didn’t happen (lol). I think part of why I haven’t had anyone ask for my help is that I haven’t offered it, and maybe also because as the intern I have less experience. My plan going forward on how to achieve this is to pay attention to the description of future tickets and try to think about potential roadblocks to pre-emptively offer my help during the implementation.

I believe I have fulfilled what I have set out to do with this goal.

##### Stepping out of my comfort zone - trying my hand at the backend

My third and final goal was to dip my feet into an area I had little experience working in: the backend infrastructure.

As I have stated before, I have a lot of experience building frontend applications, but I have spent comparatively little time immersing myself in backend technologies. Wave has a microservice architecture and makes use of Django and Protobufs to communicate with other services. This was a perfect opportunity for me to learn more about the trade-offs of adopting microservices versus a monolith architecture. Unfortunately, I ran into some roadblocks. Firstly, I initially loved writing in TypeScript so much that I was not very interested in working with Python; I have since come to be more interested in learning Django. Secondly, when I joined the ARCS team, most of the backend work was done and what was left to be done was frontend in nature.

Thus, this last goal was a bust; but I’m making the most of it because backend work will be the focus of my Fall work term at Wave.

#### Conclusion

I loved working at Wave! My team and manager are categorically awesome, I like tackling difficult challenges, and I still enjoy finding ways to make implementing features easier and more enjoyable. I got to hone my skills of creating PRs as well as spotting issues in code reviews. This being my first time working professionally in a software role, I also became familiar with the lifecycle of a feature, from idea to Pull Request. This was also the first time I pushed a bug to production and got to fix it. Thank you for the amazing work term Edan, Patrick, Mitchell, Rehman, Natasha, Anthony, Julia, Jerry, Coral, Dylan, and all the great folks from the ARCS and Payments teams!