# Common use cases for lists
Lists are useful for a number of tasks, two very representative use cases are the following:
- Remember the latest updates posted by users into a social network.(lrange)
- Communication between processes, using a consumer-producer pattern where the producer pushes items into a list, and a consumer (usually  a worker) consumes those items and executed actions. Redis has special list commands to make this use case both more reliable and efficient.
- Lists have a special feature that make them suitable to implement queues, and in general as a building block for inter process communication systems: blocking operations
