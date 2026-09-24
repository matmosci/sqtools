# SQTools
**CorelDRAW addon for print industry**  

## License

SQTools is free to use, including for commercial and professional work.

Reselling SQTools or modified versions of SQTools is not permitted
without the author's written permission.

See [LICENSE.md](LICENSE.md) for details.

## Overview

#### What is SQTools?
> SQTools is a CorelDRAW addon containing tools that help with DTP processing files in the print industry.

![sqtools1](https://user-images.githubusercontent.com/1834154/120624160-b0f9d680-c460-11eb-9edb-5895f2d3e841.png)
![sqtools2](https://user-images.githubusercontent.com/1834154/120624173-b48d5d80-c460-11eb-845e-b7ffc38a3549.png)
![sqtools3](https://user-images.githubusercontent.com/1834154/120624186-b9521180-c460-11eb-9c8d-011d4d9c4b03.png)

#### Quick demo
> Process print files in no time

![sqt_demo](https://user-images.githubusercontent.com/1834154/120624656-32516900-c461-11eb-8be8-234884ead303.gif)

## Features

#### Step and repeat imposition
> Multiple layout options available:  
full width, sheets split, sider sheet (fill blank space with smaller sheet), single sheets, combine sheets

![step_and_repeat](https://user-images.githubusercontent.com/1834154/120624226-c3741000-c460-11eb-913a-df691cf8a35a.gif)

#### Sort print and cut layer tool
> Separate layers for printting and cutting plotters

![sort](https://user-images.githubusercontent.com/1834154/120624285-d850a380-c460-11eb-92c5-d5c9373c7f71.gif)

#### Set cutlines order to S-snake pattern algorithm
> Reducing cut process time

![s-pattern](https://user-images.githubusercontent.com/1834154/120624306-dc7cc100-c460-11eb-9d94-6bb4cb8edf27.gif)

#### Single cutline algorithm
> Reducing cut process time for solid background rectangular shapes

![semi_cut_line](https://user-images.githubusercontent.com/1834154/120624325-e0a8de80-c460-11eb-9de3-a6b5d82d74fb.gif)

#### Single click page tools
> Rotate/margin/crop

![page_names](https://user-images.githubusercontent.com/1834154/120624419-f9b18f80-c460-11eb-8d6a-fecce01d8c51.gif)

#### Page merge/duplicate tools
> Combine or duplicate your pages keeping print and cut layers separated

![merge_duplicate](https://user-images.githubusercontent.com/1834154/120624400-f3bbae80-c460-11eb-8457-bdec56d909c9.gif)

#### Print marks generators
> Crop marks | banner eyelets | summa opos markers | round markers | etc.

![eyelets](https://user-images.githubusercontent.com/1834154/120624275-d4248600-c460-11eb-9027-f34a3c00766c.gif)

#### Page name helper
> Use custom text (eg. order number), imported objects names and pages indexes to create **labels** - very usefull to identify your jobs after printing

![rotate](https://user-images.githubusercontent.com/1834154/120624378-eef6fa80-c460-11eb-849d-57373999ef12.gif)

#### Find all objects with specified parameters
> Sort/select/delete specified objects on multiple pages depending on their type, fill & outline colors, width & height

![memorize](https://user-images.githubusercontent.com/1834154/120624497-0c2bc900-c461-11eb-9101-4ab7185e702d.gif)

## Installation
#### Requirements
CorelDRAW with Visual Basic for Applications (VBA) support.  
*Hint: Run CorelDRAW, go to Tools > Macros - if options there are available that means VBA is enabled.*  
> CorelDRAW Special Editions **do not** support VBA.

#### Instruction
1. Download **SQT.gms** and **sqt_ico.bmp** from repository.  
1. Locate the CorelDraw GMS directory under following path:  
**C:\Users\username\AppData\Roaming\Corel\CorelDRAW Graphics Suite XX\Draw\GMS**  
(Show hidden files, folders, and drives checkbox in folder options must be enabled).  
*Hint: type **%appdata%** in your explorer path field to get to AppData\Roaming directory.*  
1. Place downloaded **SQT.gms** file into the GMS folder.  
1. Run CorelDRAW.  
1. Show Options window **CTRL+J**, goto Customization > Commands > select **Macros** from dropdown list.  
1. Find **sqTools.run** and drag'n'drop it on convenient place in your workspace.  
1. To set the Toolbar icon for your SQTools button, go to Appearence tab > Import dropdown list > File and select downloaded **sqt_ico.bmp**

#### How to
Hover your mouse over any button to see a description of how it works.
