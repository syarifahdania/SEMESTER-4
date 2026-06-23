## 📝 Individual Reflection for Project


**Role:** Flowchart Design, Bitmap & Grouping Implementation, Literature Review, Documentation, and Testing

This project provided an invaluable opportunity to connect core Operating System principles to modern cloud storage paradigms. By simulating traditional disk block management methods within a cloud environment analogy, my team and I bridged the gap between textbook theory and practical software execution.

#### Key Contributions & Learnings:
* **System Design & Flowcharts:** Co-designed the core system architecture and visual project management flowcharts. This process required mapping out explicit logical branches for both allocation and deallocation operations across multiple distinct classes.
* **Algorithm Implementation:** Collaborated closely on the Python implementation of the **Bitmap** and **Grouping** strategies. Translating conceptual tracking (such as list-of-lists partitioning for block addresses) into functional, error-free Python code taught me a great deal about state management and collaborative debugging.
* **Literature Review & Research:** Conducted academic research on how legacy and modern file systems handle storage. Integrating these findings into our documentation allowed us to contextualize the trade-offs of each system—such as the memory overhead of Bitmaps versus the pointer overhead of Linked Lists.
* **Testing & Visualization:** Participated in rigorous trial runs, analyzing real-time disk states generated via `matplotlib`. Observing these color-coded visualizations under intense allocation and deallocation requests made the abstract concept of external fragmentation immediately tangible.

#### Collaboration & Future Directions
Our team maintained excellent synergy throughout the semester. Every member was highly accountable, allowing us to successfully compile our results, clear code bugs, and produce our final video presentation on schedule. 

If given the opportunity to expand this repository in the future, I plan to enhance the project by:
1. Simulating variable file sizes and tracking distinct file attributes (e.g., file types and creation history).
2. Implementing precise performance benchmark metrics, such as calculating exact metadata memory usage and time complexity logs under heavily fragmented workloads.
