Sample-based motion planning approaches, such as RRT\*, have been widely adopted in robotics due to their support for high-dimensional state spaces and guarantees of completeness and optimality. This paper introduces an RRT\* approach (ORRT\*) that leverages opportunism to (1) find solutions quickly, (2) reduce wasted compute, and (3) improve data efficiency. The key insight of the approach is to make the most of compute when expanding the search tree by adding the last viable configurations found when connecting new nodes rather than rejecting the sampled nodes outright, allowing for more productive exploration of the space. We evaluate the proposed approach in a set of mobility and manipulator postural control domains, contrasting the performance of the opportunistic approach with state-of-the-art RRT\* variants. Our analysis shows that such an approach has desirable characteristics and warrants further exploration.

<object data="/orrt/assets/orrt.pdf" width="100%" height="100%" type="application/pdf"/>
