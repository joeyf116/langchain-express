# LangChain Express API Boilerplate 🚀

A feature-packed boilerplate for building expressive and powerful APIs using LangChain and Express.js. This boilerplate provides a solid foundation for creating your own custom API with a wide range of functionalities. Get started quickly and build amazing APIs with ease! 🎉

<img alt="Automatically Generated API Frontend" src="https://github.com/Texterous/LangChainJS-ExpressJS-Boilerplate/blob/main/resources/boilerplate.gif" width="400"/>

<img alt="Automatically Generated API Documentation" src="https://github.com/Texterous/LangChainJS-ExpressJS-Boilerplate/blob/main/resources/openapi.gif" width="400"/>

## 🌈 Features

- 📦 Example implementations of common large language model tasks (e.g., translation, poem generation)
- 📋 Clear and simple structure for adding new methods
- 📚 Auto-generated API documentation using OpenAPI and Swagger UI
- 🚦 Rate limiting and input validation for API routes
- 📈 Logging and error handling
- 🎨 Beautiful and autogenerated frontend for testing your API
- 🚀 Easy deployment to your favorite hosting platform
- 🐳 Docker-ready for smooth deployment

## 🎓 Getting Started

1. Clone this repository:

```bash
git clone https://github.com/Texterous/LangChainJS-ExpressJS-Boilerplate.git
```

2. Install dependencies:

```bash
cd langchain-express-boilerplate
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:

```ini
OPENAI_API_KEY=your_openai_api_key_here
```

4. Start the development server:

```bash
npm run start
```

5. Open your browser and navigate to `http://localhost:3000` to see the frontend and test your API.

6. Check out the auto-generated API documentation at `http://localhost:3000/api-docs`.

## 🛠 Adding New Methods

1. Open the `methods.js` file in the root directory.

2. Add a new method object to the `methods` array. The method object should have the following properties:

   - `id`: A unique identifier for the method (e.g., "translation").
   - `route`: The API route for the method (e.g., "/translate").
   - `method`: The HTTP method for the route (e.g., "post").
   - `description`: A brief description of the method.
   - `inputVariables`: An array of input variable names (e.g., ["Input Language", "Output Language", "Text"]).
   - `execute`: An async function that takes the input variables and returns the result.

3. In the `execute` function, you can use the `LangChain` library to create your Large Language Model chain. Check out the existing methods for examples.

4. Save the file and restart the development server. Your new method will be automatically added to the API and the documentation.

## 📖 Documentation

- [LangChainJS Documentation](https://js.langchain.com/docs/)
- [OpenAI API Reference](https://beta.openai.com/docs/api-reference/introduction)
- [Express.js Documentation](https://expressjs.com/)
- [Swagger UI Documentation](https://swagger.io/tools/swagger-ui/)

## 🚢 Deployment

You can easily deploy your LangChain Express API to your favorite hosting platform (e.g., Heroku, AWS, Google Cloud, etc.). Just follow the platform-specific deployment instructions and make sure to set the `OPENAI_API_KEY` environment variable in your deployment environment. You can also use Docker.

## 🤝 Contributing

We welcome contributions to the LangChain Express Boilerplate! If you have any ideas, suggestions, or bug reports, please feel free to open an issue or submit a pull request.

## 📃 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---------------------------------------

Made with ❤️ by Thomas Übellacker and the [Texterous](https://texterous.com) Team
