# Khan Academy Take Home Assignment (Write-Up)

## Respository Author: Kevin Womack

### [Link to Data Discovery Write-Up](https://github.com/kwomackcodes/Khan-Academy-Write-Up/blob/main/Analysis.ipynb)

### [Link to Dashboard](https://public.tableau.com/views/KhanAcademyTakeHomeAssignmentProgramAnalysis/DistrictLevelView?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Dashboard Design and Development

With the data validated and assumptions registered (see data discovdery write-up), the design of the dashboard could begin. As mentioned earlier, it was clear right away that delivering a complete product would require two views with distinctly different purposes and audiences.

#### *District Level View*
The first view allows for both internal and external users to view usage growth in a given district over the course of the semester year. Additionally, lines for both pre- and post-program usage growth are plotted against each other so that the intervention effectiveness can be seen more clearly.

![District Level Image](https://github.com/kwomackcodes/Khan-Academy-Write-Up/blob/main/images/District%20Level%20View.jpg)

**Observations**
- Sometimes looking at *Very Active Learners* alone doesn't tell the whole story, for example:
  - District N, *Active Learners*
  - District V, *Rostered Learners* 

#### *Program Level View*
The second view is intended primarily for internal stakewholders who are interested in examining program effectiveness across district and program characteristics. The parameters in this view were designed to give specialized analysts with highly customizable views of intervention success.

![Program-Level View](https://github.com/kwomackcodes/Khan-Academy-Write-Up/blob/main/images/Program%20Level%20View.jpg)

**Observations**
- Both Model A and Model B appear to have greater positive effects on usage growth.
- Model A appears to be slightly more effective than Model B

#### Future Work/Unanswered Questions
- Does program effectiveness vary by grade level? Or district size?
- Do certain subjects/topics retain more/less active and very active learners than others?
- For the second view could we add columns/change the calculation to return a weighted average?

