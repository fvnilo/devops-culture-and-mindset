# The Importance of Loosely Coupled Architecture Teams

- Even the smallest scaled project can be complex.
- Vendor software add even more complexity
- We end up with a monolith

## Coupling

- Refers to dependencies between various mecanisms in a system.
- Can be **tight** or **loose**
  - Tightly coupled means that components are heavily reliant on other components in the system
    - They require highly detailed knowledge of other co-operating components
    - The level of integration is high
    - One change to one part of the system would require changes throughout the system to work properly
    - Example: Often POS in retail are highly coupled to other systems. They are rarely APIs or service-based
      - Very limiting during digital transformation
  - Loosely coupled means that components are appropriately **isolated**
    - We can modify and test **independently**
    - There is still collaboration and communication to send messages between teams
    - Changes can be readily implemented without impacting other components in the system

Switching the thinking about design and development to be more about data flow and how system can be desined to be asynchronous is another key idea. One component will then wait for data for another component which allows team to spend more time working on improving their component.

## The Benefits of a Loosely Coupled Architecture

- Horizontal scale
- Streamlines testing
- Allow for speed and agility

### Example from Nordstrom

- Rewrote commerce stack in a loosely coupled way
  - Prior to that approach, most feature requests required 5 or more teams and months of development
- Isolated functionality to deploy independently
  - Began with the outfit functionality
    - Every browse and checkout flow required testing the outfit functionality to make sure it did not break
- Changes were then made more frequently
- Iterative approach prepares to tackle the next functionality

### Example from Starbucks

- A lot of functionality were loosely coupled to the POS software
  - Due to years of building functionality into the POS
- When building another component into the cloud, functionalities were extracted out of the POS
  - Loyalty functionality: Most of the rules to apply rewards happened in the POS
    - Broken down into components
    - Rules were scaled

## Takeaways

- Assign an individual to track and manage dependencies
- It is important to work on reducing the dependencies
  - Focus on contracts
