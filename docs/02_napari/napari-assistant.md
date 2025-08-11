# The Napari Assistant

The Napari Assistant is a plugin for napari that allows you setting up an image processing workflow.

Start Napari from the command line like this:

```bash
conda activate embo25

napari
```

![](images/terminal.jpg)

The napari window will open. Start the Napari Assistant from the `Tools > Utilities > Assistant (na)` menu.

![](images/napari-assistant1_.jpg)

 Drag & drop Lund.tif ([Download here](../01_juypter_notebooks/data/Lund.tif))

![](images/napari-assistant03.jpg)

You can explore this dataset by clicking on the `2D/3D` view button.

![](images/napari-assistant04.jpg)

Within the `Assistant` panel, click on the `Remove background` button.

![](images/napari-assistant05.jpg)

Click on the `Eye` buttons in the layer list to switch between the original image and the result of the `Remove background` step.

![](images/napari-assistant06.jpg)

Click on the `Label` button in the Assistant panel to add a new step to the workflow that generates a label image from the current layer.

![](images/napari-assistant07.jpg)

Toggle 2D/3D view and layer visibility to explore the result of the `Label` step.

![](images/napari-assistant08.jpg)

After switching back to 2D view, click the `Label` button in the Assistant and choose the operation `Connected component labeling (clEsperanto)`.

Explore other options and parameters.

![](images/napari-assistant09.jpg)





