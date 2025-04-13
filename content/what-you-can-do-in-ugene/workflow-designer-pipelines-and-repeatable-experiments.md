---
title: "Workflow Designer: Pipelines and Repeatable Experiments"
weight: 500
---

# Workflow Designer: Pipelines and Repeatable Experiments

**Workflow Designer.** UGENE _Workflow Designer_ is a central part of [UGENE](http://ugene.unipro.ru/) that allows a
molecular biologist to create and run complex computational workflows, even if they are not familiar with any
programming language.

A workflow comprises a reproducible, reusable, and self-documented research routine, with a simple and unambiguous
visual representation suitable for publications. A workflow can be run both locally and remotely, either using a
graphical interface or launched from the command line. Elements in the workflow correspond to algorithms integrated
into [UGENE](http://ugene.unipro.ru/). Additionally, you can create custom workflow elements using an integrated
scripting language or by connecting arbitrary external command line utilities.

To launch the Workflow Designer, select the _Tools ‣ Workflow Designer_ item in the UGENE main menu. The following
window appears:

![](/images/2883782/3080206.gif)

**Example 4**: You can find a pattern in a sequence or sequences and save it as annotations using the following
workflow:

![](/images/2883782/3080207.gif)

Create the workflow, choose parameters, and click the _Run_ button. If you want to search for patterns in many
sequences, you can add these sequences into the _Read Sequence_ element. After the process ends, a report appears. The
report includes all information about the workflow.

![](/images/2883782/3407874.gif)

All your workflows are saved, and you can navigate between them and use them with the help of the _Dashboards Manager:_

![](/images/2883782/3080212.gif)

Note that workflows in UGENE are easy to read and share, can be reused multiple times, and compiled into separate
standalone command line tools!

For more detailed information about the Workflow Designer, use the
_[Workflow Designer Documentation](https://ugene.unipro.ru/wiki/display/WDD/Workflow+Designer+Manual)._
