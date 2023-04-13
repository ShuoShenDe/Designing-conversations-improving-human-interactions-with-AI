# ChatGPT Prompts Guide
The ChatGPT Prompts Guide is a repository of curated Prompts to help people get desired complex responses from OpenAI's ChatGPT language model. Prompts cover a wide range of topics and can be customized to generate responses for specific use cases.

# Homepage
[![homepage](https://www.klippa.com/wp-content/uploads/2023/01/ChatGPT-preview.jpg)](https://openai.com/blog/chatgpt)

# Getting Started
To get started with the ChatGPT Prompts Guide, you can browse the available prompts in the repository and select the ones that are relevant to your use case. Each prompt is provided as a text and includes a description of the prompt and example inputs.

Once you have selected a prompt, you input it into [chatGPT](https://chat.openai.com/chat), and get your result.


# Examples: Let ChatGPT help you
1. [debug](./debug.md)
2. [translate your code into another language](./translateLanguage.md)
3. [write introduction for something](./writeIntroduction.md)
4. [Write a function](./function.md)
5. [help you write the correct reference cite format](./reference.md)
6. [Search papers and summarize](./paperseach.md)


# Technical handbook
1. Choose a platform or service that provides access to the ChatGPT API, such as OpenAI, Hugging Face, or IBM Watson. Each platform may have different pricing plans, features, and API endpoints, so you should choose the one that best fits your needs.

2. Create an account or sign up for the platform. You may need to provide your payment information, credentials, or other personal information to access the API.

3. Obtain an API key or access token from the platform. This key or token is a unique identifier that allows you to authenticate and access the ChatGPT API endpoints.

4. Choose a programming language or library that supports HTTP requests and JSON parsing, such as Python, JavaScript, or Ruby. You can use these languages to send requests to the ChatGPT API and process the response.

5. Write code that sends a request to the ChatGPT API, specifying the input text, context, or other parameters. You may also need to specify the API endpoint, HTTP method, headers, and other configuration options.

6. Receive the response from the ChatGPT API, which should include the generated text, error messages, or other data. You can then parse or display the response as needed.

## Example Code
    ```python
    import openai

    openai.api_key = "YOUR_API_KEY"

    prompt = "Hello, how are you today?"
    model = "text-davinci-002"
    response = openai.Completion.create(
    engine=model,
    prompt=prompt,
    max_tokens=50,
    n=1,
    stop=None,
    temperature=0.5,
    )

    print(response.choices[0].text)
    ```






# Contributing
We welcome contributions to the ChatGPT Prompts Guide. If you have a prompt that you would like to share, please fork this repository and submit a pull request with your new prompt. Before submitting a pull request, please ensure that your prompt is well-written and meets our quality standards.


# Contact
If you have any questions or comments about the ChatGPT Prompts Guide, please contact us at shuo.shen@tum.de