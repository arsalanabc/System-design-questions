# System Design Questions

## Before you start
 - Keep it simple, stupid (KISS)!
 - Divide and Conquer
 - Think out loud
 - Know how to back your suggestions
 - No changes without a reason
 - Don't rush: bad complete is better than the best incomplete

## Features and clarifying questions
    What is the starting point?
    one complete user journey
    Are we creating E2E experience or just the API?
    Any requirements such as holding sessions, caching?
    Is application single node or distributed?
    Do we want control or outsource for simplicity?
    Tell me the list of all the key features?
    Inhouse vs cloud?
    
    - user login, storing items bucket, user storing any data, async requests etc
    
You should have a good understanding of what needs to be achieved.
    
## Database
    Do you need it or can you get by with static files?
    Structure or unstructured?
    Complex joins queries or simple fast lookup
    Any real-time updates?
    Consistency, Availability, Partition-Tolerance?
    SQL VS NoSQL 

Time to pick SQL or NoSQL or no DB at all.

## API
    Behind the DNS or local server?
    Do we any API exposure or a single application will be fine?
    Endpoints and their responsibilities?
    Any async requests?

## Scaling
    What are some bottlenecks?
    is the cost of scaling vs complexity?
    Does the application have a state to hold?
    what are load intensive operations ie read, write or computing?
    DB needs to be fast, huge or both?