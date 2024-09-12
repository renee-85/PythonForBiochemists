# Jupyter Notebooks: Getting Started

## __<font color=blue>Using Google Colab</font>__
---

__Google Colab__ (short for Colaboratory) is a Jupyter notebook environment that __runs in your browser__ using Google Cloud. You do not have to download or install any software. Your notebooks are stored in your Google Drive and can be shared with others.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabLogo.png
:alt: Google Colab Logo
:width: 100px
:align: center
```

- Go to [Google Colab](https://colab.research.google.com/). To create a new notebook, click “New notebook”. You can also upload an existing Jupyter notebook from your PC by dragging and dropping it in the Upload window.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabUploadNew.png
:alt: Google Colab Uploading a Jupyter Notebook and Creating a New Notebook
:width: 600px
:align: center
```

- Data files (Excel or text) used in the Jupyter notebook need to be uploaded too! Go to your [Google Drive](https://drive.google.com/drive/my-drive) and find the directory in which the Jupyter notebook is stored (“My Drive – Colab Notebooks” by default). You can upload the data file from your PC by dragging and dropping it in the window.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabDragDropData.png
:alt: Google Colab Uploading a Data File
:width: 600px
:align: center
```

- Loading files does require you to mount your Google Drive in your Colab notebook. First, open the file browser on the left-hand side. It will show a “Mount Drive” button. Click and follow the instructions.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabMountDrive.png
:alt: Google Colab Mounting Your Drive
:width: 600px
:align: center
```

- You can now interact with your Drive files in the file browser side panel. Click on the "three dots” icon next to a file to find _e.g_. the path information.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabFilePath.png
:alt: Google Colab Finding File Path Information
:width: 600px
:align: center
```
 
- The following figure shows you how to insert, change type, edit, and run cells.
   - Recall that a Jupyter notebook consists of code cells that allow you to write and run programming code and text (=Markdown) cells that allow you to describe your workflow.
   - You can run any cell, code or text. Running a code cell will display the result or output below the code cell that you run. When you run a text cell, the text formatted using Markdown syntax will be rendered as stylized text.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabMenu.png
:alt: Google Colab Menu Options
:width: 600px
:align: center
```
 
- Each Jupyter notebook uses a kernel. The kernel runs your code in a specific programming language, in our case, Python. It also maintains the state of your notebook’s computations. If your code is acting weird, sometimes it is best to clear all outputs and restart the kernel. This will clear all in memory objects and restart your code from the beginning of your notebook. The following figure shows you how.

```{image} ./Images-JupyterNotebooksGettingStarted/GoogleColabMenuKernel.png
:alt: Google Colab Kernel Options
:width: 600px
:align: center
```


## __<font color=blue>Examples and Exercises</font>__
---

### __<font color=red>Data</font>__
---

- Get the data needed for these examples and exercises [here](https://github.com/renee-85/PythonForBiochemists/tree/master/data).

- Store the data somewhere you know, _e.g._ in a BIOC0003 folder on your Google Drive.


### __<font color=red>Jupyter Notebooks</font>__
---

- Start a Jupyter Notebook file in Google Colab to try out the exercises in the following chapters.

- Use the 'copy code to clipboard' symbol visible in the top right corner of code code cells when hovering over them to copy and paste code from the exercises to your Jupyter Notebook.

```{image} ./Images-JupyterNotebooksGettingStarted/CopyToClipboard.png
:alt: Copy code to clipboard symbol
:width: 600px
:align: center
```

- Use markdown cells and comment lines to explain the purpose of your Jupyter Notebook and code. 

- Execute code cells by placing your cursor in the code cell and hitting Shift and Enter. The result will print out in the Raw NBConverter output cell. 