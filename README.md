Bhavna
======

This repository hosts the code for the Bhavna NGO website. Since it's in the prototyping phase, no server is included yet. Eventually, a NodeJS server with an Nginx reverse proxy for serving static assets will be added.

### Website Layout
The website consists of two sections: A single page landing and a custom WordPress blog.

The landing page will display featured initiatives, contact information, donation form and information about each founder. Each featured initiative will also link to it's corresponding blog post which will contain more details and a gallery.

#### Landing Page

| Section | Description |
|---------|-------------|
| Splash | This section has the main navigation and a carousel featuring each featured initiative. Each slide must have a high-quality image, title, caption highlighting impact of the initiative and a link to a detailed blog post.|
| Contact | This section has two forms: One form for contact and another for making donations. The contact form will accept the users email and a message and will be protected by a CAPTCHA. **The donation form fields still need to be finalized, however a CAPTCHA should be included.** In addition to the forms, we should probably also display accreditation information here so that potential donors can verify the NGO before donating.  |
| About | This section will include the name, picture and description of each founder |
| Footer | The footer will contain secondary branding and navigation, a short description of the NGO, copyright and accreditation information. |

#### Blog

We'll be using a custom skinned WordPress blog. The blog should have a detailed blog post for each event along with selected images. We can also host guest blog posts about relevant issues and opinions.
