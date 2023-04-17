# GPTman

This script uses ChatGPT to generate optimized documentation for Unix command-line utilities, libraries, system calls and more. Designed to be an AI-powered alternative to the 'man' utlity.

## Installation

Clone the repo:

```bash
git clone https://github.com/bigkahuna00/GPTman
```

Install the requirements:

```
pip3 install -r requirements.txt
```
Export your OpenAI API key as an environment variable:
```
OPENAI_API_KEY=<KEY>
export OPENAI_API_KEY
```
Or alternatively, change the value of the 'openai_api_key' variable to your API key:

```python
openai.api_key = "<KEY>"
```

## Usage

```
python3 GPTman.py <QUERY>
```

## Image
![Screenshot](https://i.imgur.com/OwfT8vo.png)

## License
[MIT](https://github.com/bigkahuna00/GPTman/blob/main/LICENSE)
