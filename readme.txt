| | |
| ------------- | ------------- |
| Spec reference: JDA Id or versions  |  |
| <b> Story reference JIRA id & Its state </b><br>Story state to be in progress & Predesign task state to be in review state |  |
| <b> Impediments </b> raised |  |
| <b> DEPENDENCIES</b> - HLD, RTE, COM, DIAG, MEET, AUTOSAR, HMI, MW, ALERTS, DISPLAY, BSP, GIP INFRA |  |
| If dependency is there , then <b>respective TT Story is linked as blocker in JIRA ?</b> |  |
| <b> Story: Change Points Review  </b><br> - all change points mentioned in story description can be covered by Alerts ? |  |
| <b> If any change point that will not be covered in this story</b> implementation -> should be discussed with STL & highlight to resp. team & PL in the EPIC  |  |
| Any additional changes found other than the mentions in Change points in EPIC/Story 
	- In the provided spec, no mentions but some changes could be found <br> 
	- during spec analysis or comparison of old and new specs                                                         |  |
| <br>Affected Files</br> list & its affected Func/Block in each file  |  |
| <br>Design Decision</br> for either Manual code update & MATLAB design update |  |
| Any <b>build changes</b> required to adapt this changes ? <br>cmake update or conditional compilation or stub changes |  | 
| <b>Impact Analysis of Changes:<b><br>  
-affected components  to be identified and include In testing scope <br>
-if affected component in in other FG, then  provide task for resp. APP component for IA & testing if required |  |
| <b>Static Analysis</b> required or not ? <br>
   -If required, then existing count to be taken from latest release KW report and<br>check for any functional impact warning or Critical/Error warning that can be fixed  - only for programs not in PT1 stage,<br>confirm it with STL |  |
| <b>FTP</b> availability : Reuse from other programs or need to update   |   |  
| <b>UTP</b> availability : Reusable from other programs or need to update ? |  |
| <b>UTP Existing Coverage if applicable:</b><br> either VCAST or MBD covera |  |
| <b>Testing Scope</b> - impacted components, abnormal scenarios, sleep wakeup, any long run testing, any automated<br> testing required, special HW tools required. |  |
| <b>Sweep Review required ?</b> <br>
   -If required, Create separate task under story and provide the task id reference |  |
| <b>Manifest Update required ?</b><br>
     Required for Bookshelf components, then IA of tag update to be done such as<br>  
	-If any tag jump . JIRA item cloned in this program to take up the latest tag,<br>
	-HLD or build  update required to adapt the tag,<br>  
	-Tag naming convention to be followed and decide tag name during MR review in case of new tag creation<br> 
	-Master branch tag to be updated in manifest,<br> 
	-any program specific DEP MR linked as DEP MR,<br>  
	-Tag comment to be updated with proper & valid & meaningful comments as it cannot be modified later<br>
	and tag comment shall be useful for future ref                                                                 |   |
|<b>Delivery Stream :</b><br> 
	-If new stream, then variant specific changes to be taken care  if applicable |   |
