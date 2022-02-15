## **TRAINSLATOR - A React translator app**
This sample shows how to integrate the Azure Speech service, translator and Web Speech API into a A React translator app. This app allows user to set recognition language and target language, captures audio from a microphone, editing the text before translating into the target language in text and audio.

## **Wireframes**

Here’s a simple diagram of the planning of our single page app [https://excalidraw.com/#room=0033d610261027abdef8,TLgiZOsG87e9iAF40wBpuQ](https://excalidraw.com/#room=0033d610261027abdef8,TLgiZOsG87e9iAF40wBpuQ).

## **Prerequisites**

1. You’ll need to have an Azure account and Speech service subscription. You’ll need to create API key for both the Speech service and the translator, the translator key had the global region during the development.
2. Ensure you have [Node.js] (https://nodejs.org/en/download/) installed.

## **How to run the app**

1. Clone this repo, then change directory to the project root and run `npm install` to install dependencies.
2. Create a .env file under the root directory, having the following content, and replace the placeholder text with your API keys.:

```jsx
REACT_APP_SPEECH_KEY=your_Azure_speech_key
REACT_APP_SPEECH_REGION=your_Azure_speech_region
REACT_APP_TRANSLATOR_KEY=your_Azure_translator_key
REACT_APP_TRANSLATOR_REGION=global
```

3. To run the Express server and React app together, run `npm run dev`.
