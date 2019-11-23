# Finite State Machine Designer - Now With A Save Option!

The original [Finite State Machine Designer](https://github.com/evanw/fsm), published on http://madebyevan.com/fsm/, is truly awesome aside from two main bugs: The PNG export does not work properly, and you cannot have multiple diagrams saved in memory.

The former one matters little to me, but the latter is a bit annoying. Solution: Separate the saved local storage into different pieces, and allow the user to name each one of them with a human-readable name - thus allowing for a (somewhat) persistent storage (in `LocalStorage`) of the diagrams.

Her's the published final version:
