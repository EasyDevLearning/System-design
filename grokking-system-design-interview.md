# Grokking the system design interview
System design is the process of designing the architecture using key components, interfaces, and data shared between these components to meet a certain set of (functional and nonfunctional) requirements.
A typical system design architecture looks something similar to this image:
<p align="center">
  <img src="https://github.com/EasyDevLearning/System-design/blob/main/streaming-300.png" alt="streaming service (youtube) system design" width="700" height="400">
</p>

## System design interviews
- [What is a system design interview?](https://www.linkedin.com/pulse/from-zero-system-design-hero-educativeios-blueprint-ekanathan-6nyfc)
- [Basics of system design interview](https://www.youtube.com/watch?v=uw-gcK9bjkk) 
- [Why does system design interview matter?](https://www.educative.io/blog/faang-system-design-interview-guide)
- [How is it different from the coding interview?](https://www.educative.io/blog/faang-system-design-interview-guide)



## Steps to prepare for the system design interviews
Following are some straightforward steps to prepare for the system design interviews:

### Step-01: Understand the basics
It is obvious that you need to understand the basics of system design, especially the prerequisite concepts of computer networks, operating systems, distributed systems, and architecture design. 
* [System design fundamentals](https://www.educative.io/blog/complete-guide-to-system-design#systemdesignfundamentals)
  * [Horizontal and vertical scaling](https://www.educative.io/answers/what-is-horizontal-and-vertical-scaling)
  * [Microservices](https://cloud.google.com/learn/what-is-microservices-architecture)
  * [Proxy servers](https://www.educative.io/answers/what-is-a-proxy-server)
  * [Redundancy](https://www.linkedin.com/advice/0/how-can-you-design-new-system-redundancy-mind-eterf)
* [Distributed systems](https://www.educative.io/courses/distributed-systems-practitioners)
  * [Partitioning](https://www.educative.io/courses/distributed-systems-practitioners/partitioning)
  * [Replication](https://www.educative.io/courses/distributed-systems-practitioners/replication)
  * [ACID transactions](https://www.databricks.com/glossary/acid-transactions)
  * [Consensus algorithms](https://www.educative.io/answers/what-is-a-consensus-algorithm)
  * [Security](https://www.einfochips.com/blog/designing-robust-and-secure-systems-considerations-for-effective-system-design/) and [privacy mechanisms](https://www.linkedin.com/advice/3/how-do-you-secure-privacy-distributed-systems)
  * [Communication protocols](https://sybase91.medium.com/system-design-basics-part-2-network-protocols-e6c3487779d2)
* [Computer networks](https://learning.oreilly.com/library/view/computer-networks-5th/9780123850591/)
* [Computer network basics](https://www.educative.io/blog/computer-networking-basics)
* [Essentials of AWS](https://www.educative.io/blog/amazon-aws-best-services#good-parts)
* [Advanced network protocols](https://www.linkedin.com/pulse/system-design-chapter-2-understanding-computer-networks-mishra-x3lcc)


### Step-02: Beat the key topics targetted in the system design interviews
* [Consistency models](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/spectrum-of-consistency-models)
* [Failure models](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/the-spectrum-of-failure-models)
* [Important non-functional requirements](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/availability)
* [PACELC theorem](https://www.educative.io/blog/complete-guide-system-design-interview#pacelc)
* [Heartbeat protocol](https://www.educative.io/blog/complete-guide-system-design-interview#heartbeat)
* [WebSocket protocol](https://www.educative.io/blog/complete-guide-system-design-interview#websockets)
* [Consistent hashing](https://www.educative.io/answers/what-is-consistent-hashing)
* [Trie data structure](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/data-structure-for-storing-prefixes)
* [Quad tree](https://dev.to/karanpratapsingh/system-design-geohashing-and-quadtrees-1fe7)
* [Bloom filter](https://www.educative.io/answers/what-is-a-bloom-filter)
* [Quoram](https://www.educative.io/answers/what-is-quorum-in-distributed-systems)
* [Distributed systems basics](https://www.educative.io/courses/distributed-systems-practitioners)
* [Operating systems basics](https://www.geeksforgeeks.org/introduction-of-operating-system-set-1/)
* [Web and Software Architecture](https://www.educative.io/blog/how-to-design-a-web-application-software-architecture-101)


### Step-03: Understand the essential components used in a system design
* [Domain name system (DNS)](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/introduction-to-domain-name-system-dns) to translate hostnames into IP addresses.
* [Load balancers](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/introduction-to-load-balancers) for distributing load evenly across multiple servers. 
* [Key-value store](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-key-value-store)
* [Blob storage](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-a-blob-store) to store unstructured data as binary large objects. 
* [CDN](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-content-delivery-network-cdn) to place the content closer to the users.
* [Databases](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/introduction-to-databases) for durability of data.
* [Sequencer](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-sequencer) for unique IDs generation
* [Distributed cache](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-cache) to allow fast access to data. 
* [Monitoring system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-distributed-monitoring) to monitor and report failures in a complex infrastructure.
* [Messaging queue](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-messaging-queue) as an intermediate component between producers and consumers.
* [Pub-sub system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-pub-sub-abstraction) to enable asynchronous communication between services and messages delivery.
* [Rate limiter](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-rate-limiter) to avoid DDoS attacks and put a limit on incoming requests.
* [Search system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-search) to search relevant content in a system.
* [Logging system](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-distributed-logging) to log the activities occurring in a system.
* [Task scheduler](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-distributed-task-scheduler) to schedule different types of tasks for processing.
* [Sharded counters](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-sharded-counters) to count events in a system 

### Step-04: Top system design interview problems
[Here is a good resource](https://github.com/yasir-educative/system-design-interview/blob/main/SDI%20questions.md) that will guide you to prepare top system design problems asked in the system design interviews at FAANG/MAANG. However, it would help if you practiced the following questions to prepare for the system design interview:
* [Design YouTube System](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-youtube)
* [Design Quora](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-quora)
* [Design Google Maps](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-maps)
* [Design Proximity Service/Yelp](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-yelp)
* [Design Uber](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-uber)
* [Design Twitter](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-twitter)
* [Design a Newsfeed System](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-newsfeed-system)
* [Design Instagram](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-instagram) 
* [ Design TinyURL](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-tinyurl)
* [Design a Web Crawler System](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-web-crawler)
* [Design WhatsApp](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-whatsapp)
* [ Design a Typeahead System](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-the-typeahead-suggestion-system)
* [Design Google Docs](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/system-design-google-docs)

### Step-05: Learn advanced concepts to ace the interview
The first four steps are enough for you if you are preparing for a mid-level or senior role. This step is crucial for staff-level engineers and above appearing in the system design interview. 
* [File systems](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-distributed-file-systems)
* [Advanced distributed databases](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-distributed-databases)
* [Concurrency managment](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-concurrency-management)
* [Big data processing systems](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/introduction-to-big-data-processing-systems)
* [Advanced consensus algorithm](https://www.educative.io/courses/grokking-the-principles-and-practices-of-advanced-system-design/consensus-prerequisites-and-two-generals-problem)
  

#### Best System Design Resources

* System design interview detailed course: [Grokking Modern System Design Interview for Engineers & Managers](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/what-is-a-system-design-interview) (medium-long term preparation)
* [System design interview crash course:](https://www.educative.io/courses/system-design-interview-prep-crash-course) (short-medium term preparation)
* I had a lot of time to prepare for the interview, so I gave a read to [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) to thoroughly understand the concepts. 

### Step-06: Mock interviews
* There are mock interviews available with real people. But very expensive ($200-$400 for a single attempt). Try this inexpensive variant with many attempts [system design mock interviewer](https://www.intervue.io/pricing) to know your standing and preparation level. But a feasible way is to use an amazing [AI interviewer](https://www.educative.io/mock-interview) developed by Educative. A low price mock interviewer simulating a real-time interview experience with detailed feedback at the end.
  

## Additional resources to enhance system design concepts
* If you are looking for a free resource, then [System design tutorial](https://www.geeksforgeeks.org/system-design-tutorial/) is the one. But of course free resources tell you the basics only. 
* [Grokking Modern System Design Interview for Engineers & Managers](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers): A comprehensive, interactive and end-to-end course for system design. I liked their feature of AI assessments; you'd love it, too. 
* [Advanced System Design for principal engineers](https://www.educative.io/blog/advanced-system-design-for-principal-engineers): A guide to enhance your skill set of system design concepts. 
* [Acing the system design interview](https://learning.oreilly.com/library/view/acing-the-system/9781633439108/): Some concepts are discussed in a good way, but it could be improved with many illustrations. A dry one to stick to it for a long time! 


