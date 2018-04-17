# barsplit
Small script to split a scanned PDF into separate group PDFs of X pages, based on a barcode on the first page of each group.

This utility was created so that student grading sheets could be sent to students easily, by simply inserting a student cover sheet at the start of the sheets for that student. For example, if there were two grading sheets being returned to each student, the cover sheets could be added, resulting in 3 sheets per student.

The output of the script is a directory, ./output, which contains one PDF for each input barcode, named with that barcode. These files can easily be emailed out, or processed in some other way.

The cover sheets can be generated using a tool such as glabels.
