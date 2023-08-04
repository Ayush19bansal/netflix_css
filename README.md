# Hosted link https://ayush19bansal.github.io/netflix_css/

# html
![image](https://github.com/Ayush19bansal/netflix_css/assets/118842033/6b4f59e7-f23b-47e9-871b-6317f6ad050a)

This HTML code represents the structure of a webpage, likely for the Netflix streaming service landing page. Let's break down the different parts of the code:

1. **Structure**: The code starts with the `body` tag, which indicates the start of the webpage's content. Inside the body, there's a `div` element with the ID "shadow." This could be a container for the main content area of the webpage.

2. **Header Section (Heading)**: Within the "shadow" `div`, there's another `div` with the ID "heading." This could represent the header section of the webpage. Inside the "heading" `div`, there are two child `` elements.

   a. **Image**: The first child `div` with the ID "image" contains an `img` tag. This image tag displays the Netflix logo, which is retrieved from an external source. The `width` and `height` attributes set the dimensions of the image.

   b. **Buttons**: The second child `div` with the ID "buttons" contains two `button` elements. These buttons are labeled "Sign In" and "Register."

3. **Main Content Section (Main)**: Following the "heading" section, there's another `div` with the ID "main." This section seems to be the main content area of the webpage.

   - An `h1` tag displays the text "Unlimited movies, TV shows and more."
   - The first `p` tag with the ID "p1" displays the text "Watch anywhere. Cancel anytime."
   - The second `p` tag with the ID "p2" displays the text "Ready to watch? Enter your email to create or restart your membership."
   - A `form` element with the class "email-signup" represents an email subscription form.
     - Inside the form, there's an `input` field with the `type` attribute set to "email" and a placeholder indicating "Email address." The `required` attribute makes it mandatory to fill out.
     - A `button` element with the type "submit" is included for submitting the form, labeled "Get Started."

In summary, this HTML code creates a basic structure for a landing page that promotes the Netflix streaming service. It includes a header with the Netflix logo and sign-in/register buttons, as well as a main content area with a headline, description paragraphs, and an email subscription form. The structure is organized using `` elements and various IDs and classes for styling and scripting purposes.

# css
![image](https://github.com/Ayush19bansal/netflix_css/assets/118842033/e6e31235-0a90-4d0c-b7f5-63dd92d725e0)
![image](https://github.com/Ayush19bansal/netflix_css/assets/118842033/93bbd38f-f028-4f20-8f8c-c5d89ce33f5c)
![image](https://github.com/Ayush19bansal/netflix_css/assets/118842033/1fb60a0d-35d5-4aee-9e9e-88077b1a858c)

This CSS code is responsible for styling the HTML structure you provided earlier, which seems to be a landing page for Netflix. Let's break down the code:

1. **Background and Body Styling**:
   - The `body` element's background is set to an image using the `url` property. This image likely serves as the background of the webpage.
   - The `margin` is set to 0 to remove default margin around the page.

2. **Header (Heading) Styling**:
   - The `#heading` ID represents the header section of the webpage. It has a height of 20% of the viewport height and uses the `flex` display property to arrange its content horizontally.

3. **Heading (h1) Styling**:
   - The `h1` elements (headings) have a large font size of 55px and no margin. This could be the main headline of the page.

4. **Shadow Div Styling**:
   - The `#shadow` ID represents a container div that creates a semi-transparent overlay to enhance readability of the content. It covers the entire viewport height (`100vh`).

5. **Image and Buttons Styling**:
   - The `#image` ID represents a container for the Netflix logo or image. It takes up 40% of the header's width, and the content is centered using `justify-content`.
   - The `#buttons` ID represents a container for the "Sign In" and "Register" buttons. It occupies 60% of the header's width, and the buttons are right-aligned using `text-align`.

6. **Main Content Styling**:
   - The `#main` ID represents the main content area of the webpage. It uses flex properties to vertically center and align its content.

7. **Button Styling (Sign In)**:
   - The `#signin` ID represents the "Sign In" button. It has a red background color, white text color, padding, border-radius, and bold font weight.

8. **Paragraph Styling**:
   - Paragraphs (``) have a margin of 13px and a font weight of 400.

9. **Paragraph (p1) Styling**:
   - The `#p1` ID represents a specific paragraph that might contain a larger font size (28px).

10. **Paragraph (p2) Styling**:
    - The `#p2` ID represents another specific paragraph that could have a slightly smaller font size (23px).

11. **Email Signup Form Styling**:
    - The `.email-signup` class styles the email subscription form. It has a white background, rounded corners, margin at the top, and flex display properties.
    - The input field within the form has flexible width (`flex: 1`) to expand within its container, and no borders or outlines.
    - The button inside the form has a red background, white text, padding, and cursor pointer.

In summary, this CSS code is used to style the elements within the HTML structure you provided, creating a visually appealing landing page for Netflix. It uses a combination of positioning, sizing, colors, and typography to achieve the desired look and feel.

