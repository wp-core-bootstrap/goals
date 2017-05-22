# Goals Progress Tracker

> Work done in the context of the [Nextgen Bootstrap/Load Feature Project](https://make.wordpress.org/core/2017/02/22/nextgen-bootstrap/).

This repository serves as a collection tool and progress tracker for detailing and executing the individual goals of the Nextgen Bootstrap/Load feature project.

The [issue tracker](https://github.com/wp-core-bootstrap/goals/issues) is used to collect all feedback/ideas/challenges/problems/use cases related to the Bootstrap/Load component.

Issues can be turned into specific action items by assigning them to one of the [phases of the project](https://github.com/wp-core-bootstrap/goals/milestones), which are represented by GitHub milestones. However, every action should also be clearly aligned with one of the main goals of the project. This can be tracked by assigning the corresponding [labels](https://github.com/wp-core-bootstrap/goals/labels) to the issue.

The main goals are:

### 1. Documentation

**The component has proper documentation for every step of the process.**

Documentation will include both clear comments in the source as well as an external documentation space that includes reference material, execution flow diagrams, best practices and examples of usage.

### 2. Modernized Flow

**The component models a modernized flow which still provides same sane defaults, but enables advanced use cases in a supported way.**

Customizing high-volume sites or specialized applications should be less “hacky”, and all of the major subsystems should provide reliable means of configuration/extension.

### 3. Contextual Optimization

**The component adapts to differing contexts to optimize both performance and memory consumption where possible.**

The system should be able to intelligently load only the parts of the code that are strictly necessary for the current requests, through means of conditional execution flows, smart routing, proxy objects and autoloading. Special consideration should be given to the WP REST API endpoints to make them as fast and efficient as possible.

### 4. Unified Structure

**The component offers a coherent way of supporting all versions of multisite (networks), reducing some of the idiosyncrasies that currently exist.**

The difference between single sites, networks of sites and networks of networks should be kept as small as possible so that less care needs to be taken to have the code work reliably with all of them.

### 5. Compatibility

**The component considers both backward compatibility as well as forward compatibility.**

It is of paramount importance that existing sites do not break due to the changes that will be proposed with this project. However, forward compatibility needs to be taken into account just as well, to create a next version of the bootstrap component that can easily grow with future requirements in a controlled way.