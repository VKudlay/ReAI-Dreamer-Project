# ReAI Object Dreamer Project

This repo is a variation of my group's final project repo for CSCI 2951X: Reintegrating AI. This course is a project-based course with the objective of experimenting with two normally-unintegrated subfields of AI and trying to see if they can work together. This one sought to combine DreamerV2 (a model-based RL formulation that reasons directly on rgb image inputs without a more condensed human-specified state abstraction) and modern object detection models for tasks like foreground/background separation and agent identification (in our case, [WSDDNs](https://arxiv.org/pdf/1511.02853.pdf) and the pre-trained [SPACE model](https://github.com/zhixuan-lin/SPACE)).

This project has been moved to [Shreyas's repo](https://github.com/ShreyasRaman-01/CS2951X_Final_Project) since he was using his repo to sync up with his GCP experiments. I'm gonna keep this up there just for ease of accesibility. 

### Distribution of labor: 
- The notebooks for baseline/SPACE integration work was done within Colab (w/ GPUs) by [Vadim](https://github.com/VKudlay) ([LinkedIn](https://www.linkedin.com/in/vadim-kudlay/)). 
- The WSDDN experiments were done in GCP's GPU-enabled VEs by [Shreyas](https://github.com/ShreyasRaman-01) ([LinkedIn](https://www.linkedin.com/in/shreyas-raman-167a2a142)) in [his repo](https://github.com/ShreyasRaman-01/CS2951X_Final_Project).
- A good amount of brainstorming and the paper start-up was done by Anoop ([LinkedIn](https://www.linkedin.com/in/anoop-reddi-b5873ba5)).

### Content Drive
As the notebooks and log files are very large, we put them into a [public Google Drive folder](https://drive.google.com/drive/folders/1_mKAnqVkWnYuUojFn89AQw1QLfkP0Kqc?usp=sharing). Feel free to check them out! 

Included is a pulled-apart version of [DreamerV2](https://github.com/danijar/dreamerv2) which can be modified easily while still being able to run in colab. This was necessary because we had M1 MacBooks and thereby could not use gym locally. Of note, you may need to restart the environment after upgrading PIL for the first time. In one of the notebooks, this has been moved to the top. Feel free to do that subsequently. Following a successful run (or if you want to just look at our log files), feel free to check out the TensorBoard Explorer file :)

### Special Thanks To [Dr. George Konidaris](https://cs.brown.edu/people/gdk/) for an awesome semester!
