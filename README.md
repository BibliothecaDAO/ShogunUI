## ShogunUI

> Shogun is still in conceptual stage, all feedback is welcome!

Shogun is a modular and hierarchical component system designed to work seamlessly with [Dojo](https://github.com/dojoengine/dojo) - the Autonomous Worlds engine. 

To maximize developer efficiency and enhance modularity, Shogun adheres to stringent design patterns. This rigor ensures that users can quickly and easily adopt the framework.

The design of Shogun allows the easy prototyping of Autonomous Worlds interfaces, whilst also being flexible enough to use in production enviroments. The system is structured with five main levels, each representing a specific level of granularity and organization: 

#### Elements (stateless): 
The smallest and most basic building blocks, like buttons, icons, and text labels. These elements are responsible for handling simple interactions and displaying information. 

#### Components (stateful): 
Collections of Elements that come together to create more complex and functional components, such as forms, lists, and navigation menus. Components define the structure and behavior of multiple Elements working together. Components are where the networking exists and are reactive. 

#### Modules (stateless, except for UI): 
Aggregations of Components that create complete and reusable modules for specific purposes, such as a user profile section or an in-game inventory, or defining an Entity based off the Dojo worlds schema. Modules are responsible for managing Components and maintaining consistency across instances. 

#### Containers (stateless, except for UI): 
Containers that hold collections of Modules and position them on the screen. Containers define the layout and organization of Modules on a given screen, ensuring proper alignment and responsiveness. 

#### Layouts (stateless, except for UI): Represent the final layout of an entire screen, where multiple Containers are arranged to create a coherent and functional user interface. Layouts ensure a consistent experience across different screens and manage overall navigation and user flow. 


### Contributing
To contribute to the Shogun component system, familiarize yourself with the conventions and hierarchy outlined above. Start by working with Elements and progress through the levels as you gain experience and understanding of the system. This will ensure a consistent and efficient development process, making it easier for everyone to collaborate and maintain the system.
