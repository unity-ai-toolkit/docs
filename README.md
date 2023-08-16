
# AI toolkit for Unity

* This asset enables the use of image-generating AI such as Stable Diffusion WebUI,  and LLM-based AI directly in Unity.

## purpose

* While many tools utilizing generative AI are being developed, its application in game development is not yet being rapidly advanced.
* 'AI toolkit for Unity' will continue to grow to provide direct assistance in game development through continuous improvement.

## key features

* c# sourcce code included.
* Currently, only basic functions have been implemented to easily use Stable Diffusion WebUI.

### text-to-image

* By inputting text, images can be generated through AI,
  * ![image](Pictures/2023-08-16%20161907.png)

### random prompts

* random prompts are provided to help with difficult prompts.
  * ![image](Pictures/2023-08-16%20162019.png)

### capture game scene and modify it

* a scene with existing game assets being worked on can be captured and modified into a new image.
  * ![image](Pictures/2023-08-16%20161438.png)

### Intermediate AI Servers

* To easily implement difficult functions, the Unity client does not directly call the AI server, but is carried out through an AI intermediate server.
* contact me if you want to build your own AI server.

* active remote cloud server addresses 
  * https://fa16-121-135-219-85.ngrok-free.app

* swagger api documentation
  * https://fa16-121-135-219-85.ngrok-free.app/docs

## plans for future

* all popular features of Text2Image, Image2Image generation
* personal management of generated images
* more user friendliness
* more direct use case for game asset developments

### ToDo

* source code documentations
* license 
* llama-index based chatbot

