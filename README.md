# HAIEC Hugo Site

This project is a Hugo-based website featuring a login page with user authentication connected to Supabase. Below are the details and instructions for setting up and running the project.

## Project Structure

- **archetypes/default.md**: Template for new content types.
- **assets/**: Directory for storing images, fonts, and other assets.
- **config.toml**: Main configuration file for site settings.
- **content/_index.md**: Content for the homepage.
- **layouts/index.html**: Layout for the homepage.
- **layouts/login/login.html**: Layout for the login page, including HAIEC logo and authentication fields.
- **static/css/style.css**: CSS styles for the site.
- **themes/**: Directory for Hugo themes.

## Setup Instructions

1. **Install Hugo**: Make sure you have Hugo installed on your machine. You can download it from [Hugo's official website](https://gohugo.io/getting-started/quick-start/).

2. **Clone the Repository**: Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:
   ```
   cd haiec-hugo-site
   ```

4. **Run the Hugo Server**: Start the Hugo server to view the site locally:
   ```
   hugo server
   ```

5. **Access the Site**: Open your web browser and go to `http://localhost:1313` to view the site.

## Features

- **Login Functionality**: The login page allows users to enter their credentials and authenticate via Supabase.
- **Responsive Design**: The site is designed to be responsive and user-friendly.

## Contributing

Feel free to submit issues or pull requests to improve the project. 

## License

This project is licensed under the MIT License. See the LICENSE file for more details.