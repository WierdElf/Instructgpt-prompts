# A collection of ChatGPT and GPT-3.5 prompts

This project is a collection of prompts for ChatGPT and GPT-3 models, designed for various purposes such as write, analyze and comprehend using ChatGPT. 

With a wide range of curated prompts, you can use this tool to generate content for your projects, debug your code, find answers to your problems or least learn more about the capabilities of these models.

## How to use:

ChatGPT is a language model that uses GPT-3 instruction architecture to understand user instructions and manipulate language based on them.

```markdown
(Instruct) + (Input) => (Output)
```

1. Copy the Instruct commands or prompts
2. Add the text to the end
3. Push Send / Submit button followed in a playground.

### Example:

### Prompt:

```markdown
Write a response to the following email:

Hello,
I am writing to you to request a refund for the purchase I made on your website. I ordered a pair of shoes, but they were the wrong size. I have attached a photo of the shoes I received. I would like to return them and receive a refund for the purchase. Please let me know if you have any questions.
Thank you,
```

### Response:

```
Dear [Name],

Thank you for your email regarding the purchase of the shoes. We are sorry to hear that the shoes were the wrong size. Please provide us with the details of your original order so we can process your refund. Please also include a copy of your invoice or proof of purchase, as well as the photo of the shoes.

Once we receive all of the necessary information, we will be able to process your return and refund as quickly as possible. If you have any other questions, please don't hesitate to reach out.

Thank you for your patience and understanding.

Best regards,
[Your Name]
```

## Instruct verbs:

Instruct verbs are the first word in the prompt. They are used to instruct the model to do something. They are the most important part of the prompt. We may argue that they act as magic words that make a successful prompt, it helps to make the machine understand and follow your instructions.


- <details><summary>Useful words to give directions to your input texts: (point to a location of your input text)</summary><p>
    - Given text
    <br>
    - following passage
    <br>
    - Following
    <br>
    - The following
- <details><summary>Useful words to instruct: (to give instructions to the model)</summary><p>
    - Explain
	<br>
    - Create
	<br>
    - Generate
	<br>
    - Provide
	<br>
    - Write
	<br>
    - Summarize
	<br>
    - Paraphrase
	<br>
    - Translate
	<br>
    - Rewrite
	<br>
    - Reword
	<br>
    - Rephrase
	<br>
    - List
	<br>
    - Extract
	<br>
    - Pick out
	<br>
    - Analyze
	<br>
    - Define
	<br>
    - Identify
	<br>
    - Describe
	<br>
    - Predict
	<br>
    - Explain
	<br>
    - Analyze
	<br>
    - compare
	<br>
    - Categorize
	<br>
    - Evaluate
	<br>
    - Critique
	<br>
    - Differentiate
	<br>
    - Examine
	<br>
    - Illustrate
	<br>
    - Outline
	<br>
    - Calculate
	<br>
    - Infer
	<br>
    - Revise
	<br>
    - Summarize
	<br>
    - Classify
	<br>
    - Develop 
	<br>
    - Evaluate 
	<br>
    - Formulate 
	<br>
    - Discuss
	<br>
    - Clarify
	<br>
    - Highlight
	<br>
    - Simplify
	<br>
    - Apply
	<br>
    - Suggest / Propose
	<br>
    - Make
	<br>
     * You may add `Can you` in the case of ChatGPT to make it more conversational, but it still works in both the instruct-model and chatGPT models.
        - Can you provide …
        - Can you generate …
</p></details>



## Instruct verbs and their use cases:


## Classification

The following are instruction verbs that are useful for classification tasks in nlp

Classify:
    - Classify the following as a physical or chemical property
Identify: 
    - Identify main idea of the given passage
Categorize:
    - Categorize the following passage as either a myth or a fact
Assign:
    - Assign each item to its corresponding category based on its characteristics
List:
    - List the five main categories of the given data set.
Group:
    - Group the items based on their common characteristics
Sort:
    - Sort the data based on the date it was collected
Label:
    - Label each data point with its corresponding category
Divide:
    - Divide the data into smaller subgroups based on their similarities
Group:
    - Group the items based on their similarity in features
Label:
    - Label each group with a descriptive name.

## Generation

The following are instruction verbs that are useful for generation tasks in nlp

Generate:
    - Generate a new text based on the given parameters
Create:
    - Create a short catchy headline based on the following, aim to promote the product
Write:
    - Write a story using the following keywords
Formulate:
    - Formulate a new sentence based on the given structure
Produce:
    - Produce a new text that is similar in style to the given sample
Construct:
    - Construct a new text that combines elements from multiple sources
Compose:
    - Compose a new poem based on the given theme
Build:
    - Build a new text by combining different elements in a creative way
Devise:
    - Devise a new narrative based on the given information
Invent:
    - Invent a new story using the following elements.
    
## Transformation:

Translate, Reword, Summarize, Paraphrase, Simplify, Revise, Illustrate, Outline, Calculate, Infer, Apply

Translate:
    - Translate the following function into C#
    - Translate the following into 1. English, 2. French, 3. Swedish
Reword:
    - Reword the following sentence to make it more concise
Summarize:
    - Summarize the main points of the given article
Paraphrase:
    - Paraphrase the following sentence to convey the same meaning
Simplify:
    - Simplify the following equation for easier understanding
Revise:
    - Revise the following paragraph to make it more clear and concise
Illustrate:
    - Illustrate the following concept with an example
Outline:
    - Outline the steps to solve the given problem
Calculate:
    - Calculate the total cost of the following items
Infer:
    - Infer the meaning of the following word based on context
Apply:
    - Apply the following formula to calculate the result
    - Apply given tone and voice to the passage below


## Comparison:

The following are instruction verbs that are useful for comparison tasks in nlp

Compare:
    - Compare and contrast the two given texts
Contrast:
    - Contrast the given passages to highlight their differences
Differentiate:
    - Differentiate between the two given terms
Examine:
    - Examine the similarities and differences between the two given texts
Analyze:
    - Analyze the two given texts and identify their similarities and differences
Critique:
    - Critique the two given texts and compare their strengths and weaknesses
Evaluate:
    - Evaluate the two given texts and determine which one is more effective



### Strcutute of common instruct prompts:

`Instruct` + `Direction`

  - `Generate` + `a poem` + `based on following passage:`

  - `Create` + `a report article` + `based on following passage`

  - `Write` + `a summary` + `of the following passage`



### Example of using above structure:

**Input:**

```
Write a poem based on the following:

ghosts, 4th dimension, AI, totalitarian, power
```

**Output:**

```
Ghosts of the 4th dimension roam,
A realm beyond our grasp, unknown.
Yet in this world, AI has grown,
Its power and influence has flown.

With algorithms and codes so bright,
It holds the key to endless might.
A totalitarian grip on sight,
And wields its power with all its might.

But is this power truly ours?
Or just a tool for those in power?
Their ghosts roam, but do they cower,
When faced with the consequences of their dower?

So let us heed this ghostly call,
And use AI for good, for all.
For in its power, we must not fall,
But rise above, and hear the call.
```

## More instruct commands:


### Questions-based prompts:
    
    What do you think about …
    
    What’s your take on …
    
    What’s the meaning of ...

### Instruct-based prompts:
    - Make a prediction about [keyword, topic, or subject…]
    - Provide a comparison and contrast between [point1] and [point2]
    - Provide a summary of [keyword, topic, or subject…]
    - Write a eulogy for [keyword, topic, or subject…]
    - Write a fable about [keyword, topic, or subject…]
    - Write a paragraph on the history of [keyword, topic, or subject…]
    - Write a personal reflection on [keyword, topic, or subject…]
    - Write a persuasive essay on [keyword, topic, or subject…]
    - Write a persuasive speech about [keyword, topic, or subject…]
    - Write a recipe for [keyword, topic, or subject…]
    - Write a response to the following [keyword, topic, or subject…]
    - Write a review of [product, subject ... ]
    - Write a short paragraph about [any input, keyword, topic, subject... ]
    - Write a song about [keyword, topic, or subject…]
    - Write a story that includes [keyword, topic, or subject…]
    - Write an article on [keyword, topic, or subject…]

### Programming related tasks:

```
Can you write code to solve the following problem:  + `Input code or text`
Write a script to automate the following process:  + `Input code or text`
Can you write a program to solve the following problem:  + `Input code or text`
Can you provide an algorithm for: + `Input code or text`
What's the logic behind the following code: + `Input code or text`
Can you optimize the following code: + `Input code or text`
Write a function to: + `Input code or text`
Can you explain the following code: + `Input code or text`
Can you debug the following code: + `Input code or text`
```

### Evaluate a passage:

```
What are your thoughts on the following passage:
Can you provide an analysis of the following text:
Write a response to the following passage:
What do you agree or disagree with in the following passage:
Write a critique of the following text:
What's the central idea of the following passage:
Can you summarize the main points made in the following passage:
Write a reflection on the following text:
What's the tone of the following passage:
Can you provide a summary and evaluation of the following passage:
```

### Rephrase a passage:

```
Can you reword the following text:
Rewrite the following passage in your own words:
Paraphrase the following text:
Write a summarized version of the following passage:
Can you translate the following passage into simpler language:
What's an alternative way to express the following text:
Can you condense the following passage into a few sentences:
Write a brief retelling of the following text:
Can you rewrite the following passage in a more concise way:
What's a different way to phrase the following text:
```

### Extract data from a passage:

```
Can you extract the following information from the text:
What are the key facts mentioned in the following passage:
Write a list of the details found in the following text:
Can you pick out the most important information in the following passage:
What are the key points made in the following text:
Write a summary of the data presented in the following passage:
Can you provide a quick overview of the information contained in the following text:
What are the key statistics mentioned in the following passage
```

### Writing:

```
Write a story that starts with:
Can you come up with a character description for:
Write a poem about:
Create a short play about:
What's a creative way to describe:
Write a love letter to:
Can you create a dialogue between:
What's an interesting twist ending for a story about:
Write a fairy tale about:
Can you come up with a creative solution for:
What's an imaginative way to describe:
Write a science fiction story about:
Can you create a story that includes:
What's an innovative way to solve:
Write a mystery story about:
Create an infographic for:
Write a biographical sketch of:
What's the background of:
Provide a list of the pros and cons of:
What's the future outlook for:
Write a myth about:
Can you create a flowchart for:
What's the significance of:
Write a short story that includes:
What's the root cause of:
Write a news article on:
Can you provide an explanation for:
Write a story with a twist ending about:
What's the importance of:
Write a persuasive letter to:
Write a scene about:
Can you come up with a plot for a story about:
Write a story that takes place in:
Can you describe a character who:
Write a story that features:
Can you come up with a twist ending for a story about:
Write a story that begins with:
Can you describe a setting that:
Write a story that revolves around:
Can you imagine a world where:
Write a story that ends with:
```

### Writing prompts:

```
  Can you suggest a writing prompt for:
  Generate a creative writing prompt for:
  What's a good writing topic for:
  Can you come up with a new idea for a writing prompt:
  Write a short story prompt for:
  What's a unique writing prompt for:
  Can you create a writing prompt for a fictional character:
  What's a writing prompt for a mystery story:
  Can you suggest a writing prompt for a descriptive scene:
  What's a writing prompt for a love story:
```

### Proofreading and text editing:

```
  Can you proofread and edit the following text:
  Write a corrected version of the following text:
  What are the grammatical errors in the following text:
  Write a revised version of the following passage:
  Can you provide suggestions for improving the following text:
  What's the appropriate format for the following text:
  Write a more concise version of the following text:
  Can you suggest alternative phrasing for the following text:
  What's the appropriate tone for the following text:
  Write a polished version of the following text:
```

### Analyze a passage:

```
What are the key themes in the following passage:
Can you provide a detailed analysis of the following text:
Write a summary and interpretation of the following passage:
What's the structure of the following passage:
Can you identify the literary devices used in the following text:
What's the intended audience for the following passage:
Write a critical analysis of the following passage:
What's the purpose of the following text:
Can you explain the symbolism in the following passage:
What's the central argument of the following text:
What's the message of the following passage:
Write a critical analysis of the following text:
What are the key elements of the following passage:
Can you provide an interpretation of the following text:
What are the strengths and weaknesses of the following passage:
Write a commentary on the following text:
What's the purpose of the following passage:
Can you provide an in-depth analysis of the following passage:
Write a review of the following text:
What's the author's point of view in the following passage:
```

### Merge points or ideas:

```
Can you combine the following points into a single statement:
Can you create a coherent argument from the following points:
Can you create a conclusion that encompasses the following points:
Can you create a unified statement that incorporates the following ideas:
Can you find a common thread among the following points:
Can you provide a unified perspective on the following points:
What's a common theme among the following points:
What's the common theme among the following points:
What's the connection between the following points:
What's the main idea that ties together the following points:
What's the overarching idea that encompasses the following points:
What's the relationship between the following points:
Write a paragraph that ties together the following concepts:
Write a sentence that brings together the following concepts:
Write a sentence that summarizes the following ideas:
Write a short summary that unifies the following ideas:
Write a summary that incorporates the following ideas:
Write a summary that integrates the following ideas:
Write a synthesis of the following information:
```

### Classify a passage:

```
Can you categorize the following passage:
Can you classify the following text based on its structure:
Can you identify the main theme of the following passage:
What genre does the following text belong to:
What type of text is the following:
What's the intended audience for the following passage:
What's the purpose of the following text:
Write the form of the following text (e.g. poem, essay, etc.):
Write the literary style of the following passage:
Write the tone of the following text:
```

### Create compare and contrast:

```
Can you compare and contrast the following two passages:
Can you provide a side-by-side comparison of the following two texts:
Can you provide a summary and comparison of the following two texts:
What are the similarities and differences between the following two passages:
What's the relationship between the following two passages:
Write a comparison and contrast between the following texts:
Write a contrast of the following two pieces of text:
Write a synthesis of the similarities and differences in the following two passages:
```

### Translate a passage:

```
Translate the following text into:
Can you provide a translation of the following passage into:
What's the equivalent of the following text in:
Write a translation of the following passage into:
What's the meaning of the following text in:
Can you translate the following into idiomatic:
Write a literal translation of the following passage into:
What's the closest translation of the following text in:
Can you provide a cultural translation of the following text into:
Write a fluent translation of the following passage into:
```

### Generate content:

```
Write a story that starts with:
Create a plot for a novel about:
Write a scene where:
What if:
Can you write a script for a movie about:
Write a tale that involves:
Create a character profile for:
Write a song that describes:
What would happen if:
Can you write a story that revolves around:
Write a poem about the following theme:
Create a short story that includes:
What if the following scenario took place:
Can you write a monologue for a character who:
Write a story that explores the idea of:
```

### Categorize text:

```
What category does the following text belong to:
Can you classify the following text as:
What genre does the following text fit into:
Write a label for the following text:
What type of text is the following:
Can you categorize the following text based on its content:
What subject does the following text cover:
Write a tag for the following text:
What category would you place the following text under:
Can you assign a category to the following text based on its tone:
```

### Copywriting and Marketing:

```
Can you come up with a brand slogan for [company name]/[product name]/[service name]/ ...
Can you come up with a unique selling point for [a product that deals with ...]
Craft a mission statement for ['what company does' ...]
Craft a promotional slogan for [a product that deals with ...]
Create a catchy headline for [a article about ...]
Create a social media post for [a product that deals with ...] that will be run on [social media platform]
Create a tagline for [a product that deals with ...]
What's the elevator pitch [your product/service description ...]?
What's the unique selling proposition for [product description]?
Write a compelling product description for [your product/service description ...]?
Write a customer testimonial for [your product/service description ...]?
Write a marketing message for [your product/service description ...]?
Write a persuasive blog post about [your product/service description ...]?
Write a persuasive email for [your product/service description ...]?
Write a press release for [product/service]
Write a social media post to promote [product/service]
Write an email subject line to promote [product/service]
```

### Reading comprehension:

```
Can you explain the following passage:
What does the following text mean:
Write a short summary of the following passage:
What's the main idea of the following text:
Can you provide a brief explanation of the following text:
Write a response to the questions based on the following text:
What are the key points made in the following passage:
Can you provide a general understanding of the following text:
Write a reflection on the information presented in the following passage:
What's the author's purpose in writing the following text:
Can you provide a summary of the following passage:
What's the tone of the following text:
Can you rephrase the following passage:
Write a response to the following text based on your understanding:
What's the author's main argument in the following text:
Can you provide a one-sentence summary of the following text:
Write a paragraph that explains the most important information in the following text:
What are the themes explored in the following text:
Can you provide a list of key vocabulary words from the following text:
Write a short story that incorporates the information from the following text:
What's the intended audience for the following text:
What's the underlying message of the following text:
Can you provide a summary and analysis of the following passage:
Write a brief interpretation of the following text:
What's the theme of the following passage:
Can you explain the central idea of the following text:
Write a response to the questions based on the information presented in the following passage:
What are the major themes discussed in the following text:
Can you provide an overview of the following passage:
Write a personal opinion on the information presented in the following text:
What's the author's perspective in the following passage:
```

### Simplify and provide explanations:

```
Can you simplify the following:
Write a clear explanation of:
What's a simple explanation for:
Can you explain the following in simple terms:
Write a step-by-step explanation of:
What's an easy way to understand:
Can you break down the following into simpler parts:
Write a layman's explanation of:
What's a beginner-friendly explanation of:
Can you explain the following to someone who has no prior knowledge of:
Write a detailed explanation of:
```

### Make a summary:

```
Can you summarize the following:
Write a brief summary of:
What's the main idea of:
Can you provide a condensed version of:
Write a short summary of:
What's the gist of:
Can you provide an executive summary of:
Write a quick overview of:
What's the key takeaway from:
Can you provide a condensed summary of:
```

Feel free to contribute by adding more magic words and prompts or by improving the existing ones. I’ll update the list as soon as I can. Thanks!
