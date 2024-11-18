# encode-week3 rough notes 
haiku generating app with characters, genre and tone, using different LLMs run locally on 7860,5000 and 3000

Modified the storytelling app, from week 2, which was run locally with the OpenAI api.
This uses the React framework for the front end, and run on localhost3000.

in the Route.ts, the baseURL is changed to point to 5000, so we dont need an OpenAI api
Using clone of Oobabooga text-generation-webui we downloaded and tested different models to 7860, such as Smol and TinyLlama, and set various parameters

The models run very slowly on a cpu, so instead of stories i used short haiku


<img width="930" alt="haiku Screenshot 2024-11-18 023602" src="https://github.com/user-attachments/assets/06650baf-2d62-46e9-a8e1-0ab18ebb9c83">
<img width="946" alt="haiku 7860 notebook Screenshot 2024-11-18 023832" src="https://github.com/user-attachments/assets/443a3287-648d-4171-8fa5-3253c06c320b">


