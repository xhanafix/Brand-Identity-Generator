Brand Identity Generator
This is a web-based Brand Identity Generator that helps users quickly generate core brand elements such as Vision, Mission, Core Values, and Purpose based on their product name and details. It leverages large language models (LLMs) to create coherent and resonant brand identities in a structured format.

Features
Product Information Input: Users can input their product's name and detailed description, including functions, benefits, target audience, and unique selling points.

AI Model Selection: Choose from various LLMs provided by OpenRouter (e.g., Mistral Mixtral 8x7B, GPT-3.5 Turbo, Llama 3 70B) or Google (e.g., Gemini Pro, Gemini 2.0 Flash). Custom model options are also available for both providers.

API Key Management: Securely save and load your OpenRouter or Google API key using local storage, eliminating the need to re-enter it for every session.

Chunked Generation with Progress: The brand identity is generated section by section (Vision, Mission, Core Values, Purpose) with real-time progress updates, providing a responsive user experience.

Formatted Output: The generated brand identity is presented in a clean, readable format using Markdown-like styling within the HTML.

Output Actions:

Copy: Easily copy the generated content to the clipboard.

Export TXT: Download the generated content as a plain text file.

Export PDF: Generate and download a PDF document of the complete brand identity, including input details.

Responsive Design: The interface is built with Tailwind CSS, ensuring it adapts well to various screen sizes, from mobile to desktop.

Custom Message Box: Utilizes a custom modal for user messages instead of browser alert() or confirm() for a better user experience.

How to Use
Input Product Information:

Enter the Nama Produk (Product Name) in the designated field.

Provide Butiran Produk (Product Details) in the textarea. This should include key aspects like functions, benefits, target audience, and unique qualities.

Select AI Model:

Choose your preferred AI model from the Model AI dropdown.

If you select a Model Tersuai (Custom Model), an additional input field will appear where you can enter the specific model name (e.g., anthropic/claude-3-opus for OpenRouter or gemini-1.5-pro for Google).

Enter API Key:

Input your respective API Key (for OpenRouter or Google) in the API Key field.

Click Simpan API Key & Model to save your API key and chosen model to your browser's local storage. You won't need to re-enter it unless cleared from storage.

Generate Brand Identity:

Click the Jana Identiti Jenama button.

The application will start generating each section of the brand identity sequentially, and a progress bar will update in real-time.

Review and Export:

Once generated, the full brand identity will be displayed.

Use the Salin, Export TXT, or Export PDF buttons to copy, save as a text file, or export as a PDF document, respectively.

Reset:

Click Reset Input to clear all input fields and the generated output, allowing you to start a new generation.

Technologies Used
HTML5: Structure of the web page.

Tailwind CSS: For rapid and responsive styling.

JavaScript (ES Modules): Core logic for interacting with the AI API, handling user input, and updating the UI.

html2pdf.js: Library used for client-side PDF generation.

OpenRouter API / Google Gemini API: For interacting with various large language models to generate text.

API Key Security
Your API key is stored in your browser's localStorage for convenience. While this is generally secure for single-user applications, it's not recommended for highly sensitive data or public-facing applications without server-side handling.
