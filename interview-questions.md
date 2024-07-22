# System Design Interview Questions

A few months ago, preparing for system design interviews, especially for top-tier companies like FAANG, was a journey that pushed me to explore the depths of scalable distributed systems. 
Drawing from my own experience and the resources I found invaluable, this GitHub repository is a curated collection of system design interview questions for folks like me. 
My goal is to provide a comprehensive resource that prepares you for the intricacies of system design interviews.

## How I strategized system design questions

In preparing for system design interviews, I strategically approached my preparation in phases. I started by mastering common system design problems
to build a solid foundation. From there, I categorized my study into specific domains like social media or e-commerce systems. I then focused on 
practical use cases and adapted my solutions to varying seniority levels and difficulty levels. This structured approach not only deepened my understanding 
but also prepared me comprehensively for the challenges of FAANG-level interviews.<br><br>
![SDI](https://github.com/ibrahimEd/system-design-interview-questions/blob/main/system-design-interview-questions.png)

Let’s start with the common system design questions that are asked in the FAANG companies.
<br>

## Popular/common System Design Questions
While preparing, I figured out some common or popular system design problems that are being discussed on the internet through different resources. I got inspiration from a blog titled [Top 14 System Design Interview Questions for Software Engineers](https://www.educative.io/blog/top-10-system-design-interview-questions). I’d suggest you read it to know how to approach design problems. My list is given below, comprising of blogs and course links I found helpful:

- [Design a content delivery network (CDN)](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-content-delivery-network-cdn)
- [Design a distributed file system](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-gfs)
- [Design a search engine](https://towardsdatascience.com/system-design-cheatsheets-elasticsearch-673b98eebfff)
- [Design a messenger app](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-whatsapp)
- [Design a collaborative editor](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-docs)
- [Design a social media app—Instagram/X](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram)
- [Design a distributed messaging queue](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-messaging-queue)
- [Design a URL-shortening service](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-tinyurl)
- [Design a payment gateway](https://www.educative.io/courses/grokking-the-api-design-interview/requirements-of-the-stripe-api)
- [Design a video streaming service](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-youtube)
- [Design a chess game–learn with AI](https://www.educative.io/courses/grokking-the-api-design-interview/chess-api-design-ai-mentor-beta), [Without AI-1](https://www.geeksforgeeks.org/design-a-chess-game/), [Without AI-2](https://github.com/tssovi/grokking-the-object-oriented-design-interview/blob/master/object-oriented-design-case-studies/design-chess.md)
- [Design Google maps](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-maps)
- [Design an online multiplayer game backend](https://www.educative.io/courses/grokking-the-api-design-interview/requirements-of-the-gaming-api)
- [Design price tracking application–CamelCamelCamel](https://www.educative.io/courses/grokking-the-api-design-interview/requirements-of-the-camelcamelcamel-api)—This is a new design problem, and I only found it here. 
- [Design a distributed cache system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-cache)
- [Design a typeahead](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-typeahead-suggestion-system)
- [Design a newsfeed system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram)
- [Design a Twitter](https://www.geeksforgeeks.org/design-twitter-a-system-design-interview-question/)
- [Design a web crawler](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-web-crawler)
- [Design a ride-hailing service](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-uber)

## Categories of System Design Questions

System design problems like YouTube, Netflix, and Amazon Prime Video look different but fall into the same category, sharing similar functionalities–streaming services. So, we can have the following main categories of system design problems:
- Video streaming systems
  - [YouTube streaming service](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-youtube)
  - Netflix streaming service
  - Amazon Prime Video streaming service

- Real-time communication systems
  - [Real-time messaging apps, such as WhatsApp, Telegram, Messenger, etc.](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-whatsapp)
  - Video conferencing systems, such as Zoom, Google Meets, etc.
  - Online gaming systems

- Ride-hailing systems
  - [Uber system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-uber)
  - Lyft system
  - Uber-Eats system
  - DoorDash system

- Feed-based social network system
  - [Instagram system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram)
  - LinkedIn system
  - TikTok system
  - Facebook reels
    
- Cloud-based collaborative systems
  - [Google Docs](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-docs)
  - Google Drive system
  - One drive system
  - Microsoft Office 365
  - Trello or MDC for project management

You’ll find interviewers getting into details of a specific design problem, and I’ve categorized them under use case-specific questions, as discussed in the subsequent section. 

## Use case-specific Questions
Now, after categories, I wanted to explore the in-depths of a system based on use cases like scaling, achieving low latency, etc. 
The following questions are categorized based on system design aspects such as scalability, performance, and security. I've listed limited aspects, and you can think of similar use cases while preparing these design problems.
### Scalability
> [How would you design a system to handle millions of concurrent users?](https://www.educative.io/blog/scalable-systems-101)
### Performance
> [How would you optimize a database for read-heavy workloads?](https://blog.bitsrc.io/optimizing-sql-databases-for-read-heavy-operations-14c5402955d9)
### Reliability
> [How would you design a system for 99.999% uptime?](https://www.educative.io/blog/complete-guide-to-system-design)
### Security
> [How would you secure user data in a large-scale system?](https://maddevs.io/blog/big-data-security-best-practices/)
### Database Design
> [How would you design a NoSQL database schema for a social media application?](https://www.mongodb.com/resources/basics/databases/nosql-explained/data-modeling)
### Data Processing
> [How would you design a real-time data analytics platform?](https://www.mongodb.com/resources/basics/real-time-analytics-examples)
### Microservices
> [How would you manage inter-service communication in a microservices architecture?](https://www.educative.io/blog/why-use-microservices)

## Seniority-Based Questions
These questions are tailored to different experience levels, from junior to principal engineers. The questions can be the same as the provided list in the common system design questions, but the talking points and expectations differ. You should consider the following points while preparing for your relevant level and the system design questions.
### Junior Engineers
#### Talking points
- Describe each component and its interaction with other components
- Describe the complete life cycle of a request (e.g., from client to server to back-end services)
- Dive deep into 1 or 2 areas
- Discuss trade-offs
#### System design questions
- [Design a content delivery network (CDN)](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-content-delivery-network-cdn)
- [YouTube streaming service](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-youtube)
- [Design Newsfeeds such as Instagram](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram)
- [Design URL shortening](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-tinyurl)
- [Design a web crawler](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-web-crawler)
### Senior Engineers
#### Talking points
- Identify the critical components of the system
- Identify potential choke points and bottlenecks in the system
- Identify potential scaling issues and propose solutions
- Align the trade-offs with the desired product goals and user experience
#### System design questions
- [Design a messenger app](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-whatsapp)
- [Design a collaborative editor](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-docs)
- [Design a social media app—Instagram/X](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram)
- [Design Uber](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-uber)
- [Design Quora](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-quora)
### Principal Engineers
#### Talking points
- Focus on immediate needs along with future scalability
- Discuss user experience during failures and its impact on SLAs
- Address real-world consequences of deployed solutions
- Discuss data center failovers, regional backups, and disaster recovery plans
- Analyze usage patterns, manage peak loads, handle DDOS attacks, and ensure graceful service degradation
- Address the impact of security breaches and service outages on the company’s reputation and manage SLA expectations
 #### System design questions
- [Design Google maps](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-maps)
- [Video streaming systems](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-youtube)
- [Design a proximity service like Yelp](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-yelp)
- [Design a collaborative editor](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-docs)
- [Design a messenger app](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-whatsapp)

## Difficulty-Based Questions
These questions are categorized by difficulty to help you progressively build your system design skills.
### Easy
- [Design a Distributed Messaging Queue](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/requirements-of-a-distributed-messaging-queues-design)
- [Design Distributed cache](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-cache)
- [Design a content delivery network (CDN)](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-content-delivery-network-cdn)
- [Design a search engine](https://towardsdatascience.com/system-design-cheatsheets-elasticsearch-673b98eebfff)
### Medium
- [Design pub-sub](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-pub-sub-abstraction)
- [Design a rate-limiter](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-rate-limiter)
- [Design a distributed task scheduler](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-task-scheduler)
- [Design Twitter](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-twitter)
### Hard
- [Design Google file system](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-gfs)
- [Design a Typeahead](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-typeahead-suggestion-system)
- [Design Google Chubby Locking service](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-chubby)
- [Design Amazon’s DynamoDB](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-dynamodb)
- [Design Facebook’s tectonic file system](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-tectonic)

## FAANG Specific Questions
This is the most important section, as preparing company-specific system design questions can give you an edge in the system design interview. For that, I'll prepare another resource to give you a full list of design problems. 


## Resources
1. The first resource that I’d like to mention here is a book [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/), which talks about different aspects of designing data-intensive applications. It’ll teach you concepts, not designs. 
2. One of my friends from Meta, who referred me for an interview, suggested I go for [Grokking Modern System Design Interviews](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers). Believe me, it was worth trying. The lists I curated above are from the same resource. The best feature that let me evaluate myself are their AI assessments within the course (it’s like talking and arguing like we do in interviews) and [AI mock Interviewer](https://www.educative.io/mock-interview).
3. The last resource to mention is Alex Xu's [System Design Interview—An Insider's Guide](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119). It’s an interesting read requiring more time; you might feel bored but the concepts are comprehensively discussed. I’d not recommend you to go for this if you have a short time to prepare for your interview. 

