# To do: Rubric Items With High Fail Rates


Based on: [Potential Rubric Issues](Potential Rubric Issues.md) for examples of each:

1. The reviewers do not interpret the rubric item correctly.
2. The rubric item is not clear
3. The lessons do not help complete the rubric item

_1. & 2. are less well defined than 3., so I will begin with 3._



***

### _**3. The lessons do not help complete the rubric item.**_

- **Course: Data Visualization with Matplotlib and Seaborn**, _Multivariate Exploration of Data_
  - This is also relevant for parts of _Bivariate Exploration of Data_ (of the same course) and for the sections of **Practical Statistics** relating to the sampling distribution.

***

##### Reason for proposed changes
- Currently, the pages in this lesson appear disorganized. 
  - This is primarily because basic instructions (sufficient to complete the project) are intermingled with more complex ideas.
- Many of the examples use code that is overly complicated.


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

As noted, there are some similar issues in the _Bivariate Exploration of Data_ pages. 

- One example, the [heatmap](https://learn.udacity.com/paid-courses/cd12532/lessons/de891e39-61f8-4c96-a420-5a22f2b6a5a4/concepts/66697993-748f-41d2-825a-48429f8092ef) page shows how to annotate _matplotlib's_ _`.hist2d()`_ plot and mentions at the end that this can also be done using _seaborn's_ _`.heatmap()`_.  It is easier to use  _seaborn's_ _`.heatmap()`_ so it is unclear why a more complex method is used.

Throughout the _sampling distribution_ lessons in the **Practical Statistics** course, there is a similar mixture of basic and complex ideas. Restructuring those pages would help students see _"the wood for the trees"_

***

# As noted, the other two issues are less well defined:
***



### _**1. The reviewers do not interpret the rubric item correctly.**_

Reason to address this:

- Reduce the fail rate.
- Avoid discouraging students
  -  Inconsistent evaluations will confuse students (they will be unclear about how to meet a rubric item that they may feel that they have met).


***

1. _(Known Issues)_
  - If there are known issues of interpretation/learned inconsistancies (like the example in the file linked): 
      - i) Add clearer review tips (directly addressing issues found) to the rubric; and/or 
      - ii) Contact reviewers for that project with the same information.
2. _(Extension - Feasibility?)_ **Sampling**
  - For rubric items with high failure rates, randomly select reviews that fail these items, for **different** reviewers.
  - Check if the evaluations are consistent with the rubric.
  - If evaluations are not consistent with the rubric, are there **common** inconsistencies across different reviewers?
      - Resolve issues of inconsistancy in the same way as with "Known Issues"

***


## _**2. The rubric item is not clear.**_

Review all project rubrics _(Preferably this would be done by more than one person)_:

- For each rubric item, flag any items that are not actionable statements (suggestions, like _"ideally you should ..."_ etc, can be included in the _Project Details_ section of the project).
- Cross-check the flagged items, if done by more than one person.
- Decide whether flagged items should be: i) Rephrased so that they are actionable; or ii) Removed from the rubric (possibly moved, as suggestions, to another part of the project site). That is, determine:
  -  Is the item important to the overall aim of the project (and is just poorly phrased)? 
  - Or, is the item a suggestion that is better placed elsewhere?
- Edit the rubric accordingly.
