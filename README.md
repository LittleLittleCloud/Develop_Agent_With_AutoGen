## Developing AI Agents using AutoGen
### Before you start
- Install python >= 3.8
- Install VSCode
- Create and activate your virtual environment
```bash
# windows
python -m venv venv
venv\Scripts\activate

# linux or mac
python3 -m venv venv
source venv/bin/activate
```
- Install the required packages
```bash
pip3 install -r requirements.txt
```

### Notebooks (Order matters here)
- [x] [Hello World](HelloWorld.ipynb): Create your first AutoGen agent. We use this notebook to walk through AutoGen primitives (agent, agent runtime, message handlers) as well as helping student onboard to OpenAI account/setting up python environment.
- [x] [Human in the loop](./HumanInTheLoop.ipynb) Add human user to the conversation. We extend the hello world example from single-agent to two agent conversation by introducing user agent.
- [x] [Tool call](./ToolCall%20and%20MultiModa.ipynb): We use this notebook to show how to introduce tool call to agent.
- [x] [MultiModal](./MultiModal%20chat.ipynb): We use this notebook to show how to introduce multi-modal capability to agent.
- [x] [Multi-agent Group Chat](./Multi-agent%20GroupChat.ipynb): A notebook that uses all building blocks above. We build a group chat with four agents: User, assistant, ImageAssistant and WeatherAssistant, orchestrated by a group chat admin.
 
