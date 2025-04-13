---
title: "Workflow Designer: pipelines and repeatable experiments"
weight: 500
---


# Workflow Designer: pipelines and repeatable experiments

**Workflow Designer.** UGENE _Workflow Designer_ is a central part of [UGENE](http://ugene.unipro.ru/)  that allows a molecular biologist to create and run complex computational workflows even if he or she is not familiar with any programming language.

A workflow comprises reproducible, reusable and self-documented research routine, with a simple and unambiguous visual representation suitable for publications. A workflow can be run both locally and remotely, either using graphical interface or launched from the command line.  Elements in workflow correspond algorithms integrated into [UGENE](http://ugene.unipro.ru/). Additionally you can create custom workflow elements using integrated scripting language, or by connecting arbitrary external command line utility.

 To launch the Workflow Designer select the _Tools ‣ Workflow Designer_ item in the UGENE main menu. The following window appears:


![](/images/2883782/3080206.gif)

**Example 4**: You can find pattern in a sequence or in sequences and save it as annotations using the following workflow:


![](/images/2883782/3080207.gif)

Create the workflow, choose parameters and click the _Run_ button. If you want to search pattern in many sequences you can add these sequences into _Read Sequence_ element. After the end of the running process a report appears. The report include all information about workflow.


![](/images/2883782/3407874.gif)

All your workflows have been saved and you can navigation between it and use it with a help of the _Dashboards Manager:_


![](/images/2883782/3080212.gif)

Note that workflows in UGENE are easy to read and share, can be reused multiple times and compiled into a separate standalone command line tools!

For more detailed information about Workflow Designer use the _[Workflow Designer Documentation](https://ugene.unipro.ru/wiki/display/WDD/Workflow+Designer+Manual)._
