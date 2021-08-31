# Safe Travel

### Problem

As the world struggles to re-open allowing for safe cross border travel, the challenge is to keep up and stay up-to-date with the latest in Travel advisory & Restrictions.

Covid-19 specific information especially Vaccination, Health & Quarantine conditions are paramount for any Travel to take place. The information has been standardised up to an extent but still exists in silos. Apparently not ALL relevant information is accessible from one place.

### Solution

The IDEA is to have a simple ChatBot application stitching data points together for Travellers and Travel planners to access content easily.

Link to Mockup: https://drive.google.com/file/d/1L0bzK1-llrjCEdyuNdWTYnp26az_8k53/view?usp=sharing

### How to use

- Create a new agent in Dialogflow CX following the steps [here](https://cloud.google.com/dialogflow/cx/docs/quick/build-agent#create-agent)
- To use this SafeTravel bot, import the file [exported_agent_SafeTravel2.blob](../main/exported_agent_SafeTravel2.blob) to the created agent following these [steps](https://cloud.google.com/dialogflow/cx/docs/quick/build-agent#optional_agent_import)
- Try out the flow by clicking on **Test Agent** button on the top right of screen. Once the window opens, say "Hi" or "Hello"

### Data source

https://www.iatatravelcentre.com/  
https://www.unwto.org/unwto-iata-destination-tracker  
https://www.travel-advisory.info/

### Disclaimer

There are no free APIs available at the time of submitting this concept.
APIs must be sourced directly from content providers so that relevant information can be integrated directly into chat flow.

### Note

Sadly the web demo only supports plain text responses, so adding an clickable url within chatbot for the webdemo won't work.
Luckily, this is a limitation for web demo alone, other integrations that support URL's in chats will work on click.
