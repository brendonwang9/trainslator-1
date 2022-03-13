## **TRAINSLATOR - A React translator app**
https://trainslator2022.herokuapp.com/ \
Trainslator is a front-end speech and text react translator tool using Microsoft Cognitive services APIs. Set up a input and output langauge and speak into the microphone to translate your text into a desired langauge using Microsoft AI-langauge processing tools and Google Cloud Platform supported languages.\

Project was completed with an exceptionally talent and focused team @ **[enyacat](https://github.com/enyacat)”** and **[HarryPdot](https://github.com/HarryPdot)**
## **Wireframes**

Here’s a simple diagram of the planning of our single page app [https://excalidraw.com/#room=0033d610261027abdef8,TLgiZOsG87e9iAF40wBpuQ](https://excalidraw.com/#room=0033d610261027abdef8,TLgiZOsG87e9iAF40wBpuQ).

## **How to run the app**
1. You’ll need to have an Azure account and Speech service subscription. You’ll need to create API key for both the Speech service and the translator, the translator key had the global region during the development.
2. Ensure you have [Node.js] (https://nodejs.org/en/download/) installed.
3. Clone this repo, then change directory to the project root and run `npm install` to install dependencies.
4. Create a .env file under the root directory, having the following content, and replace the placeholder text with your API keys.:

```jsx
REACT_APP_SPEECH_KEY=your_Azure_speech_key
REACT_APP_SPEECH_REGION=your_Azure_speech_region
REACT_APP_TRANSLATOR_KEY=your_Azure_translator_key
REACT_APP_TRANSLATOR_REGION=global
```

5. To run the Express server and React app together, run `npm run dev`.
