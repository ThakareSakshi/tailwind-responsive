# tailwind-responsive
hosted link:-https://thakaresakshi.github.io/tailwind-responsive/
![image](https://github.com/ThakareSakshi/tailwind-responsive/assets/86354291/141e4960-9b09-4ef3-9963-1e0c7858abd2)


1. **Header Section (`<header>`)**:
   - `w-full`: Sets the width of the header to 100% of its container.
   - `px-4`: Adds horizontal padding of 1rem on each side.
   - `py-1`: Adds vertical padding of 0.25rem on the top and bottom.
   - `flex`: Turns the header into a flex container.
   - `justify-between`: Justifies content between the flex items.
   - `items-center`: Aligns items vertically at the center.
   - `max-md:flex-col`: Changes the flex direction to column on screens with a maximum width of the "md" breakpoint.
   - `max-md:items-center`: Centers items vertically on screens with a maximum width of the "md" breakpoint.

2. **Logo Section (`<div>` inside header)**:
   - `flex`: Turns the div into a flex container.
   - `m-2`: Adds margin to the div.
   - `w-10`, `h-10`: Sets the width and height of the SVG icon to 2.5rem.
   - `text-white`: Sets the text color to white.
   - `p-2`: Adds padding to the SVG icon.
   - `bg-green-500`: Sets the background color to a shade of green.
   - `rounded-full`: Rounds the corners of the div.

3. **Logo Text (`<span>` inside header)**:
   - `font-medium`: Sets the font weight to medium.
   - `m-3`: Adds margin to the span.
   - `text-xl`: Sets the font size to extra-large.

4. **Navigation List (`<div>` inside header)**:
   - `list-none`: Removes list styles (bullets/numbers) from the list.
   - `flex`, `gap-4`: Creates a flex container with spacing between items.
   - `items-center`: Aligns items vertically at the center.
   - `justify-start`: Aligns items to the start of the container.
   - `flex-grow`: Allows the list to grow and take up available space.
   - `text-gray-700`: Sets the text color to gray.
   - `border-s-4`: Adds a border to the right side with a specific spacing.

5. **Navigation List Items (`<li>` inside navigation list)**:
   - `hover:text-gray-900`: Changes the text color to dark gray on hover.

6. **User Button (`<div>` inside header)**:
   - `px-3`, `py-2`: Adds horizontal and vertical padding.
   - `bg-gray-200`: Sets the background color to a shade of gray.
   - `text-gray-700`: Sets the text color to gray.
   - `rounded-md`: Rounds the corners of the button.
   - `m-3`: Adds margin to the button.

7. **Main Content Section (`<main>`)**:
   - `flex`: Turns the main section into a flex container.
   - `items-center`: Aligns items vertically at the center.
   - `p-10`, `px-12`: Adds padding to the main section.
   - `justify-center`: Centers content horizontally.
   - `max-md:flex-col`: Changes the flex direction to column on screens with a maximum width of the "md" breakpoint.

8. **Text Content (`<div>` inside main section)**:
   - `flex-col`: Arranges child elements in a column.
   - `font-bold`: Sets the font weight to bold.
   - `text-3xl`: Sets the font size to 1.875rem.
   - `py-2`, `px-2`: Adds padding to the text.
   - `w-1/2`, `max-md:w-full`: Sets the width to half the parent container on larger screens and full width on smaller screens.
   - `p-2`, `my-2`: Adds padding and margin to the text.

9. **Buttons (`<button>` inside text content)**:
   - `bg-green-500`: Sets the background color to green.
   - `py-2`, `px-6`: Adds padding to the buttons.
   - `text-white`: Sets the text color to white.
   - `rounded-md`: Rounds the corners of the buttons.
   - `hover:bg-violet-900`: Changes the background color to violet on hover for the "Yes" button.
   - `text-gray-500`: Sets the text color to gray for the "No" button.
   - `hover:bg-gray-200`: Changes the background color to gray on hover for the "No" button.

10. **Image (`<img>` inside main section)**:
    - `w-2/5`, `max-md:w-full`: Sets the width to 40% of the parent container on larger screens and full width on smaller screens.

These Tailwind CSS classes provide styling and responsiveness to the HTML elements, making it easy to create a visually appealing and responsive webpage.
