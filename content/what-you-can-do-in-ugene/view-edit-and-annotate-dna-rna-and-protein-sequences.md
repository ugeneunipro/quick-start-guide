---
title: "View, Edit and Annotate DNA, RNA, and Protein Sequences"
weight: 100
---

# View, Edit, and Annotate DNA, RNA, and Protein Sequences

**DNA, RNA, or protein sequences (_Sequence View_).** The _Sequence View_ is one of the major object views in UGENE
designed to visualize and edit DNA, RNA, or protein sequences along with their properties like annotations,
chromatograms, 3D models, statistical data, etc. For each file, UGENE analyzes the file content and automatically opens
the most appropriate view. To activate the _Sequence View_, open any file with at least one sequence. For example, you
can use the $_ugene/data/samples/Genbank/murine.gb_ file provided with UGENE. After opening the file in UGENE, the
_Sequence View_ window appears:

![](/images/2883698/3080195.gif)

_Sequence View_ - an object view designed to visualize DNA, RNA, or protein sequences along with their properties like
annotations, chromatograms, 3D models, statistical data, etc.

_Project View_ - a visual component used to manage active projects and bookmarks.

_Annotations Editor_ - contains tools to manipulate annotations for a sequence.

_Options Panel_ - a panel with different information tabs and tabs with settings for Sequence View.

_Task View_ - shows active tasks, for example, algorithm computations.

_Log View_ - shows the program log information.

_Notifications_ - shows notifications for task reports.

After the view is opened, you can see a set of new buttons in the toolbar area. The actions provided by these buttons
are available for all sequences opened in the view. These actions are also available from the context menu. Many
instruments and algorithms are available:

* Find pattern
* Find ORFs
* Find annotated regions
* Build dotplot
* Find repeats
* Find tandems
* Find restriction sites
* Primer 3
* Find high DNA flexibility regions
* ...

**Example 1**: Finding patterns in your sequence. Do the following steps:

Open the _ugene/data/samples/murine.gb_ by the _File–>Open_ menu, for example. Sequence View with murine.gb opens.
Select the _Search in Sequence_ tab of the _Options Panel_. Click _Show more options_, and more options appear. Insert,
for example, "TTCCGAGGGACACTAGGCTGACTCCATC" pattern into the _Search for:_ field and choose annotation parameters. For
example, as in the picture below:

![](/images/2883698/3080213.gif)

After that, click the _Search_ button. If the pattern is present in the sequence, it appears as new annotation(s):

![](/images/2883698/3080198.gif)
