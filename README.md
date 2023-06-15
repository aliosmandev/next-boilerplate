# Next Boilerplate

This project is a Next.js boilerplate with the following features:

- Supabase implementation
- Server-side authentication
- Private authorization pages
- Storybook integration
- Cypress test integration

## Features

- **Supabase implementation**: Connects the project to Supabase, a Backend-as-a-Service platform that provides database and authentication services. It enables data management using Supabase's database functions.

- **Server-side authentication**: Implements a server-side authentication system to manage user authentication. It includes functionalities such as user registration, login, and session management.

- **Private authorization pages**: Allows the protection of certain pages based on user access permissions. Private authorization pages are accessible only to users with specific roles or authorizations.

- **Storybook integration**: Integrates Storybook into the project for component-driven development and UI testing. Storybook provides an isolated environment to develop, showcase, and test UI components independently of the main application.

- **Cypress test integration**: Includes integration with Cypress, a JavaScript end-to-end testing framework. Cypress allows you to write and run tests for your application's UI and behavior.

## Usage

Follow the steps below to use the project:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/your-username/next-boilerplate.git
   ```

2. Install the dependencies:

   ```shell
   cd next-boilerplate
   npm install
   ```

3. Configure Supabase:

   - Create a Supabase project and obtain your API credentials (API URL and API Key).
   - Update the Supabase configuration file (`supabase.js` or similar) with your API credentials.

4. Run the development server:

   ```shell
   npm run dev
   ```

   The project will be accessible at `http://localhost:3000`.

5. Explore the different features of the project:

   - Supabase implementation: Use Supabase functions to interact with the database and authentication services. Refer to the Supabase documentation for more details on how to use their SDK.
   - Server-side authentication: Use the provided authentication endpoints to handle user registration, login, and session management.
   - Private authorization pages: Add the necessary authorization checks to protect specific pages based on user roles or authorizations.
   - Storybook integration: Run Storybook using the following command:

     ```shell
     npm run storybook
     ```

     Open your browser and navigate to `http://localhost:6006` to access Storybook's UI and view the showcased components.

   - Cypress test integration: Write and run unit tests for your application's components and functions using Cypress. Cypress tests can be added to the `cypress` directory, specifically the `integration` folder. To run the tests, use the following command:

     ```shell
     npm run test:unit
     ```

     Cypress will execute the unit tests and provide the results in the command line.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).
