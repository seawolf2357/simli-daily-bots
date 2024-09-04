# Create Simli App
This starter is an example of how to create a composable Simli interaction that runs in a Next.js app.
<<<<<<< Updated upstream
The project consists of a Next.js app that uses the Simli SDK (`simli-client`) and a server `server.js` that handles the interaction with other services such as speech-to-text (STT), large language models (LLMs) and text-to-speech (TTS). 
=======
The project consists of a Next.js app that uses the Simli SDK (`simli-client`) and [dailybots](https://docs.dailybots.ai) a voice agent API, to construct a video agent interaction.
>>>>>>> Stashed changes

### Start by putting in environment variables
Create a `.env.local` file in the root of the project and add the following environment variables:

```bash
SIMLI_API_KEY=your-simli-api-key
GROQ_API_KEY=your-groq-api-key
DEEPGRAM_API_KEY=your-deepgram-api-key
ELEVENLABS_API_KEY=your-elevenlabs-api-key
```

If you want to try Simli but don't have API access to these third parties, ask in Discord and we can help you out with that. 

### Alternative STT, TTS and LLM providers 
You can of course replace Deepgram and Elevenlabs with AI services with your own preference, or even build your own.
The only requirement for Simli to work is that audio is sent using PCM16 format and 16KHz sample rate. If you're having trouble getting nice audio, feel free to ask for help in Discord.  


To run the back-end and the app, run the following command:



```bash
npm run start
```

### Characters
You'll start with Einstein but you can add more characters by [creating your own](simli.com) or finding one that you like in the [docs](docs.simli.com). 

![alt text](images/image.png) ![alt text](images/image-4.png) ![alt text](images/image-2.png) ![alt text](images/image-3.png)


## Deploy on Vercel

The easiest way to deploy your avatar interaction to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme). 
