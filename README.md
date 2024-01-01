# Astro-blog-template

This project is an Astro.js template for creating content-rich blogs with SEO capabilities and integrated Netlify CMS.

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Adhishtanaka/Astro-blog-template.git
   cd astro-blog-template```

2. Install dependencies:
     
     ```bash
     npm install
     ```
3. Host it in Netlify.

4. Enable Netlify Identity:

-  Go to the Netlify dashboard.
- Select your site and goto site configuration.
- Navigate to the "Identity" tab.
- Enable Identity and configure the settings.

5. Configure GitHub Gateway:

- Scroll down to the "Services" section.
- Click "Enable Identity" and "Git Gateway."
- Follow the prompts to authorize Netlify with your GitHub account.

6. Configure Registration:

- Scroll down to the "Registration/ExternalProvider" section.
- Click "Add Provider" and select github
- after that Scroll down to the "Registration/Registration preferences" section.
- select invite only.
- after everything done you can invite you as a team member & sign in to CMS.
### Usage

     ```bash
     npm run dev
     ```

### Contributing
If you would like to contribute to this project, please follow our Contribution Guidelines.

