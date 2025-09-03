# VLM-UI-Element-Locator
## 1. Project overview
  # 1.1 Project requirement and outcome
    This project demonstrates how a Vision Language Model (VLM) can be used to understand and interact with graphical user interfaces (GUIs). The primary goal is to take a screenshot of a website or application and locate the precise coordinates of a specific UI element based on a user's natural language description.
    Here is the workflows
      - 1. *Input*: The user provides an image of a UI (e.g., a website screenshot).
      - 2. *Query*: The user describes the target element they want to find, such as "the blue login button" or "the search bar."
      - 3. *Output*: The model processes both the image and the text query, returning the exact (x, y) coordinates for the center of that element.
  #  
 ```mermaid
flowchart TD
        A(["Start"])
        A([Start]) --> B[Survey Image with VLM to Create UI Map];
        B --> C[/Input: UI Element/];
        C --> D{"Element Found in Map?"};
        D -- Yes --> E[Calculate & Display Click Coordinates];
        D -- No --> F[Display 'Not Found' Message];

        E --> G([End]);
        F --> G;
```
  # Setup and runcode 
## 2. What I learned
  ### 2.1 How Multimodal Models Work
  ### 2.2 Reading documents and examples
  ### 2.3 Prompt Engineering: 
## 3. Limitations
  ### 3.1 Bounding box 
  ### 3.2 Model's hallucination
  
  

