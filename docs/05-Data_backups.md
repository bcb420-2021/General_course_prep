# Data Backup Best Practice {#backup}
(Data backup technologies and best practice)
 
## Overview 
### Abstract:

### Objectives:
This unit will provide a brief introduction to backup problems and methods to solve them.

### Outcomes:
After working through this unit you ...

  * have a sensible and effective strategy for backing up your computer;
  * have demonstrated that you can recover data.

### Deliverables:
**Time management**: Before you begin, estimate how long it will take you to complete this unit. Then, record in your course journal: the number of hours you estimated, the number of hours you worked on the unit, and the amount of time that passed between start and completion of this unit.

**Journal**: Document your progress in your Course Journal. Some tasks may ask you to include specific items in your journal. Don't overlook these.

**Insights**: If you find something particularly noteworthy about this unit, make a note in your insights! page.


## Data backups
When was the last time you made a full backup of your computer's hard-drive? Too long ago? I thought so.

<div class="rmd-task">
<ol style="list-style-type: decimal">
<li>Backup your hard-drive now.</li>
</ol>
</div>

Risk is probability times damage. The annualized probability of hard drive failure is on the order of 3%. This means about three of your classmates in this course will lose all their data this year. It is a bit better for solid state drives (SSD), perhaps only 0.3 failures per year. But what is the damage? All your essays, coursework, all the pictures on your computer, that email from your first love... There is no question you need to have plans in place to protect your data. After all, storage failure is not a question of if, but when.

Enterprise-scale data in bioinformatics labs need dedicated solution and that is actually an increasing problem. For your small scale, personal backup needs you have a variety of options;

  * Cloud backup may be bandwidth limited;
  * Mac OS X has things well covered with thier Time machine / Time capsule, I don't know what the best equivalent is for other systems;
  * off-machine storage in removable disk is a questionable startegy because everything that is not fully automatic is liable to fall victim to complecancy;
  * Whenever possible, make differential backups. And remember: NO backup is a backup unless recovery of data has been tested and shown to work.

## Task:
<div class="rmd-task">
<ul>
<li>Use this Google Search for links to recent articles about backup options.</li>
<li>Read a few articles that are relevant for your computer.</li>
<li>Decide on a backup strategy for your computer.</li>
<li>Implement your strategy.</li>
<li>Create a test file.</li>
<li>Backup your computer.</li>
<li>Delete your test file.</li>
<li>Recreate the file from your last backup.</li>
</ul>
</div>

## Self-evaluation
## Notes
## Further reading, links and resources
Use this Google Search for links to recent articles about backup options.
 
**If in doubt, ask!**<br>
If anything about this learning unit is not clear to you, do not proceed blindly but ask for clarification. Post your question on the course mailing list: others are likely to have similar problems. Or send an email to your instructor.

 
\BeginKnitrBlock{rmd-original-history}<div class="rmd-original-history"><br>**Author**: Boris Steipe <boris.steipe@utoronto.ca> <br>
**Created**: 2017-08-05<br>
**Modified**: 2017-09-11<br>
Version: 1.0<br>
**Version history**:<br>
1.0 Completed to first live version<br>
0.2 Begin development from legacy material; points only<br>
0.1 Material collected from previous tutorial<br>
 </div>\EndKnitrBlock{rmd-original-history}

### Updated Revision history

Revision   Author          Date         Message                                                                                                                                                            
---------  --------------  -----------  -------------------------------------------------------------------------------------------------------------------------------------------------------------------
f56a24c    Ruth Isserlin   2019-12-23   Added new git info to each fileAdded new git info to each file (in addition to the original version history copied over from Boris's wiki).                        
8950904    Ruth Isserlin   2019-12-22   Initial check in of converted wiki pages from Boris Steipe's bcb420 course material pagewiki pages were converted to bookdown and formatted to the bookdown format 

