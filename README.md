# amp
Automated Materials Production

The Automated Material Production process, or A.M.P., allows advocates to make multi-media materials, including paper hand-outs, videos, presentations for meetings, an audio file, and a workbook, from a spreadsheet or an outline in Word.  A.M.P. guides an advocate to make effective, useful multimedia materials for clients without special graphic design knowledge or video production skills, while providing the ability to customize information to the client's specific jursidiction.

A.M.P. uses a variety of open-source programs
  
##Design Principles
+ Creates multimedia educational materials to meet the different needs of our client population
+ Hand-outs match videos and presentation, providing a reminder clients can take with them
+ Easy to change and update all multimedia at once, based on feedback or changes in law.  The modular nature of the process allows A/B testing.
+ Breaks multimedia production tasks into simple roles
+ Provides the foundation for future projects to allow more personalized, usefuul educational materials

##How Do I Use A.M.P.?

__template.svg__

The template provides the design of the educational materials, and can be created in Inkscape.

To work with SVGGVS, templates must contain specific layers and each text or image object must have a Label that matches a corresponding tag in data.odt

To work with Sozi, templates should have a layer of frames

__data.ods__

SVGGVS uses a spreadsheet saved as an .ods file to customize the template.  The first row in the spreadsheet is a list of the labels in the template.  The subsequent rows contain the content that will be inserted.  If you are only making one. TABS

**images**
Most images in the templates have the same square ratio, which allows a library of images to be used interchangeably without distortion.  These are standard images with a common design element that make the hand-out more readable and connect the hand-out to other multimedia materials.  Images provide context clues to aid in literacy, add emphasis, break-up text  and create links and connections across materials.  

Templates may also use a document image, to reference a form or court document that the user may recognize.

**video.blend**
This Blender file can be opened in Blender's Video Sequence Editor

Steps:
 1. [SVGGVS](https://github.com/johnbintz/svggvs) creates a customized SVG from the template.svg, data.ods and images resources.  The SVG can be exported to pdf for a paper hand-out.
 2. Next, convert text to path in SVG using [this tool](https://github.com/senshu/Sozi/tree/master/tools/texts2paths).  The SVG can now be used as a presentation software similar to Prezi.
 3. Record a separate audio clip for each frame of the presentation.  If the audio files are named correctly and placed in a file, the files will be automatically imported into Blender.
 4. [This adapted tool](https://github.com/grytafey/Sozi-export) will export the presention into frames that can then be imported into Blender.
 5. Additional images, animation or video can be added to the VSE in Blender.
 6. WORKBOOK


