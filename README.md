# Chat in Norsk Bokmål with a conversational agent using OpenAI API

This repository contains code for building a conversational agent using the OpenAI API. The conversational agent utilizes the powerful capabilities of OpenAI's language model to generate human-like responses and engage in dynamic conversations. For the most part the agent should converse in Norsk Bokmål. In case the agent responds in English, remind that it is supposed to respond in Norsk in the subsequent user input.

## Installation

To get started, follow these instructions:

1. Clone the repository to your local machine using the following command:
   
   ```
   gh repo clone your-username/repository-name
   ```

2. Install the required dependencies by navigating to the project's root directory and running:
   
   ```
   pip install -r requirements.txt
   ```

3. Follow the instructions in the `config` folder to set up the openAI API key.

## Usage

1. Navigate to the folder containing `norskGPT.py` and run the script using:
   ```
   py norskGPT.py
   ```
2. Immediately, norskGPT asks for User input. A sample conversation is given below.
   ```
    User: Hei
    norskGPT: Hei! Hvordan kan jeg hjelpe deg i dag?


    User: Kan vi snakke om havvind?
    norskGPT: Ja, selvfølgelig! Hva vil du vite om havvind?


    User: Hva vet du om havvind?
    norskGPT: Havvind er en form for fornybar energi som utnytter vindkraft fra havet.    Havvindparker består av store vindturbiner som er montert på plattformer eller stolper som  er festet til havbunnen. Disse turbinene kan generere store mengder elektrisitet som kan  overføres til land og brukes til å drive hjem og bedrifter.

    Havvind er en viktig del av kampen mot klimaendringer, da det er en ren og fornybar energikilde som ikke produserer utslipp av klimagasser. Havvind kan også bidra til å redusere avhengigheten av fossile brensler og øke energisikkerheten.

    Det er imidlertid noen utfordringer knyttet til havvind, inkludert høye kostnader for installasjon og vedlikehold, samt potensielle miljømessige konsekvenser for sjølivet og fiskeriene. Det er derfor viktig å gjennomføre grundige miljøvurderinger og samarbeide med lokale samfunn og interessenter for å sikre at havvindutvikling skjer på en bærekraftig måte.


    User: quit()
   ```
3. As shown above, you can input `quit()` to end your conversation. You could also save the chat transcript as `output.docx` or `output.txt` file.
4. Along the way, you would be asked if you want to continue if the total tokens exceed a maximum number of tokens (1000, by default; you can change this value. Refer to `.\config\README.md`)

