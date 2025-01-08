# TINA

**TINA** -- Text to Image to New Asset -- is a workflow for putting generated 3D models into Unreal Engine from text prompts using various AI services.

### Necessary Tools
- Generative Image Software: Grok, DALL-E, etc.
- Tripo AI: https://www.tripo3d.ai/
- Game Engine: Unreal Engine

### Workflow
1. Use a generative image software to create an image from a text prompt.

2. Upload the resulting image into Tripo AI and click "Create" to generate a 3D model of the image. Download the model after it is generated.

3. In Unreal Engine, import the model via "File > Import Into Level" and select the downloaded model. Select a folder to put the model into and click "Import" in the next window. Finally, drag and drop the static mesh of the model from the Content Drawer into the level.
