Project Description:

Create a responsive photo gallery using HTML and CSS, showcasing a collection of images in a visually appealing layout. The gallery will utilize CSS Flexbox for easy alignment and flexibility in handling different screen sizes.

HTML Structure:
Use HTML5 structure with appropriate semantic elements like <header>, <div>, and <img> tags.
Include necessary meta tags for character set and viewport settings.
CSS Styling:
Utilize a separate CSS file (styles.css) for styling the gallery.
Apply a global box-sizing rule for consistency (* { box-sizing: border-box; }).
Set a background color and font for the body, ensuring readability (body { ... }).
Header Styling:
Style the header (<header>) with a centered layout, uppercase text, padding, background color, and a border at the bottom.
Gallery Layout:
Create a flexbox container for the gallery (<div class="gallery">) with row direction, wrapping, centered content, and spacing between items.
Limit the maximum width of the gallery and center it horizontally on the page (max-width: 1400px; margin: 0 auto;).
Image Styling:
Style the gallery images (<img>) to have a responsive width, a maximum width of 350px, a fixed height of 300px, and a cover object-fit to maintain aspect ratio and cover the entire space.
Add a border-radius for rounded corners.
Accessibility:
Ensure the gallery is accessible by using descriptive alt attributes for images (<img src="..." alt="Description">).
Additional Enhancements:
Add hover effects, transitions, or other visual enhancements to make the gallery interactive.
Consider adding a lightbox feature for a better viewing experience.
