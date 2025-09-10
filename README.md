The project aims at applying modern deep learning algorithms for the image inpainting capability that allows for changing certain areas of the image like backgrounds, faces, or clothes. This remarkable inpainting pipeline integrates Meta’s Segment Anything Model together with the Hugging Face Diffusers library. With the help of Segmenting Model, the system enables one to select and modify definite parts of an image with the help of textual descriptions, which is possible due to accurate masking and segmentation. The following application is a strong and highly adjustable option that gives users with different degrees of skill sets potential to enhance image cleverness via through picture editing powers. 
The user interface is created through Gradio in order to present an easily navigable interface for the image inpainting tools. The primary feature is that selecting the pixels and creating masks and segmentations of such pixels become much easier for the users and are integrated into a single interface for editing. The project also investigates an improved inpainting pipe using tailored ControlNet implementation with better outcomes and featured additions such as segmentation blocks, backgrounds, and effective prompt management. The current version of segmentation model looks sleek, sensible and effective, proving the idea of using AI tools in creation and designing of the Image.

OUTPUT-1:
<img width="1243" height="805" alt="image" src="https://github.com/user-attachments/assets/ad43915d-4e8f-4f15-b30f-eb76c4b66cb9" />

Step-by-Step Breakdown:
• Original Image (Input Panel) : The user supplied the program with a photograph
showing a group made up of five members.
• Mask Generation (Mask Panel) : The user applied SAM segmentation to select and
mask the shirt of the person at the far left with white. The white mask allows precise
modifications on the shirt alone.
• Segmentation Map (Segmentation Panel) : During its operation the SAM model
analyzes images to create multi-colored maps that automatically detect and segment
all objects present (peoples and garments and backgrounds and other elements).
• Prompt Used : Prompt: a green shirt with a floral pattern
• Negative Prompt: (left blank) : The system allowed users to define their preferred shirt
transformation through spoken words.
• Output (Output Panel) : Using our selection the shirt changed into a green shirt
featuring floral design elements that now displayed instead of the original plain shirt
while leaving all other image elements untouched. The inpainted area maintains visual
consistency while matching the image context and keeps accurate illuminatioN
patterns and body outline shapes.

OUTPUT-2:
<img width="1230" height="698" alt="image" src="https://github.com/user-attachments/assets/62bb5845-9209-4247-8a88-9be559f0e4f7" />

Step-by-Step Breakdown:
Original Image (Input Panel) : The input presents a wood path where a person walks
within an expansive grassland area which extends to distant hills during a cloudy
afternoon.
• Mask Generation (Mask Panel) : The full-scene segmentation technique separated the
background from the person so they remained unharmed. The person in the photo
remains visible in the black mask space on the right side while the white background
section will undergo modification.
• Segmentation (Segmentation Panel) : The SAM segmentation map enables the system
to identify person, landscape and sky together with other elements which leads to
improved background precision in segmentation.
• Prompt Used : An outdoor landscape shows mountains under snowy conditions with
present clouds in the scene
• Negative Prompt: (left empty)
• The Background Toggle function was enabled through a checked status (instead of
object editing).
• Output (Output Panel) : This operation successfully substituted the background
segment with a snowy mountainous scene which integrated harmoniously with the
original path elements and person who walked through it. Natural photo perspectives
and realistic textures of snow appear in this transformed mountainscape.


download the segment model from this link
https://drive.google.com/file/d/1XRk4WCcl9WymnciTgsr1j5dCGEdH2sTs/view?usp=drive_link
