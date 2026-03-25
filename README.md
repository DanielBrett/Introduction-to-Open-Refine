![Tool Logo](Introduction-to-Open-Refine.jpg)


# Introduction to Open Refine
This workshop is meant to give you a basic foundation on how to use the tool and navigate the interface.  It will cover:
- How to run the Open Refine tool
- How to use the Facet and Filter features to identify errors
- How to split and join columns of your data
- How to use GREL commands on your data
- And how to export your data back out of Open Refine  
  
*Estimated workshop length: 1.5 hours*
  
----
## Setup Instructions
In preparation for this workshop, you will need to download and unzip the Open Refine package. The steps to do this are:
- Go to the [downloads page for Open Refine](https://openrefine.org/download.html)
- Click the Highlighted text that represents your operating system (If you are using windows and are unsure if you have java, choose the option that comes with Java)
- Save the file to your computer in a location that you have access to
- Unzip the file using your preferred zipping tool (right click on the folder and choose the program to unzip with like 7zip or WinZip)
- (Optional) Make a shortcut on your desktop by opening the folder, right clicking openrefine.exe (blue gem symbol) and clicking "create shortcut" (you may need to move the new shortcut to your desktop manually depending on your operating system)

You will also need to download the dataset for the workshop by clicking [HERE](https://github.com/BrockDSL/Introduction-to-Open-Refine/raw/master/Booklist1.xlsx)

----
## Helpful Materials
A great resource to keep handy when working in Open Refine is the [Open Refine Manual](https://docs.openrefine.org/) which covers every aspect of the tool from the most basic [data transformations](https://docs.openrefine.org/manual/transforming), to complex [GREL functions](https://docs.openrefine.org/manual/grelfunctions).


----
## Workshop Tasks

**Task Set #1**  
1. Run Open Refine  
2. Connect to the "BookList1.xlsx" data  
3. Check that the settings are correct and click "Create Project"  

  
**Task Set #2**  
1. Make a text facet for Book Title using the dropdown (Facet>Text Facet) then sort it by count instead of name  
2. Remove extra spaces by going to the Book Title dropdown (Edit Cells>Common Transform>First option)  
3. Cluster results and merge similar fields  


  
**Task Set #3**  

1. Split the multi-valued cells in Author (Dropdown>Edit cells>Split multi-valued cells)  
2. Clean the data by trimming whitespace and clustering (remember to use both ngram-fingerprint and metaphone3)  
3. Switch the view to show records instead of rows  
4. Combine your split cells (Dropdown>Edit cells>Join multi-valued cells)  


  
**Task Set #4**  

1. Open the transform window for Publication Date using Dropdown>Edit Cells>Transform  
2. Remove the (US) and (UK) terms using the .replace command  
3. Remove the whitespace using the .trim command  
4. Replace the .0 with blanks  
4. Grab just the year using the .substring command then click OK to make the changes  

  

----
## Next Steps
Once you have finished this workshop, the next step would be to try cleaning some of your own data with Open Refine!  If you don't have any datasets of your own, you can practice on the second book list found [HERE](https://github.com/BrockDSL/Introduction-to-Open-Refine/blob/master/BookList2.xlsx) or go find some free data to practice on from a site like [Kaggle.com](https://www.kaggle.com/).

