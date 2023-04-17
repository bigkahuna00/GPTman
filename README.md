# GPTman

A simple tool that is designed to be an AI-powered alternative to man pages.

## 🌟 Advantages compared to man pages (as written by GPT-4)

1. **User-friendly language**: Generates documentation using natural language, making it easier for users, especially beginners, to understand the purpose and functionality of Unix utilities.
2. **Reduced technical jargon**: Avoids excessive technical terminology, making the documentation more accessible to a wider range of users.
3. **Dynamic generation**: Generates up-to-date documentation on-the-fly, potentially providing more current information than static 'man' pages.
4. **Customizable base prompt**: Allows adjusting the base prompt to focus on specific aspects of the utilities, tailoring the generated documentation to the user's needs.
5. **Examples and use cases**: Provides specific examples and use cases, helping users better understand how to use the utilities in real-world scenarios.

## 🛠️ Installation

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

## 📚 Usage

```
python3 GPTman.py <QUERY>
```

## 📷 Screenshot
![Screenshot](https://i.imgur.com/OwfT8vo.png)

## 📄 License
[MIT](https://github.com/bigkahuna00/GPTman/blob/main/LICENSE)
