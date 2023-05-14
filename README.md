# Virtual GPT

## CODE AND GAME FILES CAN BE FOUNDS AT 
https://drive.google.com/drive/folders/1EgcKL3s2E_Gg-BflZGjyN_newW4qruOJ?usp=share_link
Unity resources are large in size (greater than ~3 GB) which cannot be accomodated by GitHub. Please check the above link for accessing the required files.

**Gamified interaction with some quirky virtual NPCs based on ChatGPT** 

Submission to [Warpspeed Generative AI Hackathon 2023](https://warpspeed2023.devfolio.co/overview)
Team Members: Deepthy Rose Jose, Akash Sharma (Team optimus)

Interact with time travelers Ada Lovelace, Charles Babbage, Marie Curie and Leonardo Da Vinci through text-to-text conversations in game! 
Characters inspired by famous GPT LLM models.

## Tech Stack Used
- Unity Engine 2021
- Stability Diffusion for character generation 
- Ready Player Me for avatar generation
- Unity ChatGPT Integration Plugin
- Mixamo Character Animations

## Challenges Faced
- Time constraint has been the biggest challenge that we faced considering we had decided to work on XR media with GenAI capabilities.
- Another challenge was checking feasibility of ideas that we thought of along with various softwares we wanted to utilize. Following are some ideas and softwares which we tried and had to drop eventually -
  - Creating XR assets using Nvidia Omniverse (Lack of a strong GPU was a problem but we'll admit it was a bit ambitious :) ).
  - We also experimented with 3D storyboards using movie scripts. One particular challenge was to define the scene with modular assets such as characters, buildings (if any), camera movements etc. 
  - GPT-Actor/Gymnast, an XR GPT agent capable of following your commands to do tasks like performing gymnastics or acting out a scene from user's direction.
  - Loading new environments into the Unity engine was quite harrowing because of rendering pipeline issues, so we ended up using a default map. 

## References

To figure out how to put a GPT wrapper for characters in Unity, we followed the tutorial series as in https://www.youtube.com/watch?v=Cg4k-XPBC2Q&t=4078s&ab_channel=Sarge 
