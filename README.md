# Hero Card Project

This project is a simple **hero card** built using **HTML** and **Tailwind CSS**. The card features a quote from Marcus Aurelius, along with an image, and demonstrates the use of Tailwind CSS utilities for layout, spacing, typography, and responsive design.

## Project Overview

The Hero Card project showcases:

- A responsive layout using **Tailwind CSS**.
- An image background with a circular shape on small screens and a square shape on larger screens.
- Typography styling for the quote, author, and source.

## Technologies Used

1. **HTML**: The basic structure of the card is built using semantic HTML5 elements.
2. **Tailwind CSS**: Tailwind CSS is used extensively to apply utility-first styles directly within the HTML.

## Key Features

1. **Responsive Design**:
   - The layout adjusts based on the screen size. On small screens, the card elements are stacked vertically and centered, while on larger screens, the image and text are arranged side by side.
   - The `md:` prefix in Tailwind is used to apply styles for medium and larger screens.

2. **Image Styling**:
   - The image is styled as a circle on small screens (`rounded-full`) and switches to a rectangular format on larger screens (`md:rounded-none`).
   - The image uses a `bg-cover` and `bg-center` class to ensure proper scaling and positioning.

3. **Typography**:
   - The quote is styled with **bold text** (`font-bold`), larger font size (`text-lg`), and white color (`text-white`).
   - The author's name is emphasized with **blue text** (`text-blue-400`), while the source is styled with **gray text** (`text-gray-400`).

4. **Container and Spacing**:
   - The card is wrapped inside a responsive container (`container mx-auto`) to center it on the page.
   - Padding is applied at different levels for consistent spacing (`p-1`, `p-4`, `md:p-5`), with `p-0` used to adjust for no padding on specific screen sizes.

## How to Run

To see the hero card in action:

1. Copy the HTML code and paste it into an `.html` file.
2. Include a link to the **Tailwind CSS CDN** in the `<head>` section of your file:

   ```html
   <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
   ```

3. Open the HTML file in a web browser.

## Possible Enhancements

1. **Interactive Features**: Add hover effects or animations to make the card more dynamic.
2. **Dark Mode**: Tailwind’s dark mode feature could be incorporated to make the card adapt to system-level themes.
3. **Additional Content**: The card could include links or buttons for more interaction.

## Skills Demonstrated

- **HTML structuring**: Using semantic elements to create accessible and clean markup.
- **Tailwind CSS**: Leveraging utility-first CSS for rapid and responsive design development.
- **Responsive Design**: Adapting the layout for different screen sizes using media query utilities in Tailwind.
