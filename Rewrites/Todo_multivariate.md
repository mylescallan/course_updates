

## **Course: Data Visualization with Matplotlib and Seaborn**, _Multivariate Exploration of Data_
  - This is also relevant for parts of _Bivariate Exploration of Data_ (of the same course) and for the sections of **Practical Statistics** relating to the sampling distribution.

***

### To Do:

1. Rewrite the entire lesson so that it is consistent with what is expected in the project. Namely:
  - Showing how to Generate Multivariate visualizations using approaches that are most easily reproducible _(currently, the examples are overly complicated (for no beneficial reason) & there are errors in the supplied code)_.
  - For issues that are unique to multivariate visualizations, explain how to ensure visualizations are appropriate for the data type _(avoiding overplotting, and plotting with ordinal data are two key examples)_
2. For each of the sections, have "Essential" &  "Extensions" pages 
  - Currently, each page contains sequences of examples _(information overload)_, which are a mixture of basic and complex approaches.
  - Instead, there should be "basic" pages _(information sufficient to complete the project)_ followed by pages showing how to finese the simple approaches (explaining the benefits of the proposed extensions).
      - That is, the main pages should offer enough guidance for the student to complete the relevant section of the project.
      - The optional pages will offer extensions.


***

### Future To Dos

As noted, there are similar issues in the _Bivariate Exploration of Data_ pages. 

- One example, the [heatmap](https://learn.udacity.com/paid-courses/cd12532/lessons/de891e39-61f8-4c96-a420-5a22f2b6a5a4/concepts/66697993-748f-41d2-825a-48429f8092ef) page shows how to annotate _matplotlib's_ _`.hist2d()`_ plot and mentions at the end that this can also be done using _seaborn's_ _`.heatmap()`_.  It is easier to use  _seaborn's_ _`.heatmap()`_ so it is unclear why a more complex method is used.

Throughout the _sampling distribution_ lessons in the **Practical Statistics** course, there is a similar mixture of basic and complex ideas. Restructuring those pages would help students see _"the wood for the trees"_

