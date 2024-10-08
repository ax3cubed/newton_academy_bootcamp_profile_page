# newton_academy_bootcamp_profile_page
## Project Overview

This project is a simple and responsive portfolio webpage built using HTML, CSS, and Flexbox. The portfolio showcases various projects and is designed to be flexible and adaptive across different screen sizes.

## Table of Contents

- [Project Overview](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [Technologies Used](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [File Structure](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [Getting Started](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [Portfolio Section Explanation](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [Responsive Design](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [Enhancements](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)
- [License](https://www.notion.so/Web-Design-Portfolio-717841544f6c450791915db94c1307f4?pvs=21)

## Technologies Used

- **HTML5**: For structuring the content on the web page.
- **CSS3**: For styling the webpage, including Flexbox for layout management.
- **JavaScript** (optional): For adding interactivity and form validation.

## File Structure

```graphql
graphqlCopy code
web-design-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
└── README.md           # Project documentation

```

## Getting Started

To view the portfolio webpage, simply clone this repository and open `index.html` in your web browser.

### Clone the Repository

```bash
bashCopy code
git clone https://github.com/your-username/web-design-portfolio.git

```

### Open the File

Open `index.html` in your preferred web browser to see the webpage in action.

## Portfolio Section Explanation

The portfolio section is designed using **Flexbox** to create a responsive grid layout that adapts to different screen sizes. Here's a breakdown of how the section works:

- **HTML Structure**: The portfolio items are wrapped inside a `div` container with the class `portfolio-container`. Each project is represented by a `div` with the class `portfolio-item`.
- **Flexbox Layout**:
    - The `.portfolio-container` is set to `display: grid` with `grid-template-columns: repeat(auto-fit,minmax(200px, 1fr));` to allow the items to wrap onto the next line if necessary.
    - Each `.portfolio-item` uses `grid-template-columns: repeat(auto-fit,minmax(200px, 1fr));` to ensure it takes up approximately one-third of the container's width, minus spacing.
- **Responsive Adjustments**:
    - On screens smaller than 768px, the items adjust to `calc(50% - 2rem)` to stack two items per row.
    - On screens smaller than 480px, the items take up the full width of the container.

## Responsive Design

The portfolio section is designed to be fully responsive:

- **Media Queries**: Used to adjust the layout for different screen sizes.
    - **768px and below**: Items stack two per row.
    - **480px and below**: Items stack one per row, taking up the full width of the screen.

This ensures the portfolio looks great on desktops, tablets, and mobile devices.

## Enhancements

Here are some potential enhancements you could implement:

- **Lightbox Effect**: Clicking on a portfolio image could open a larger view in a modal window.
- **Lazy Loading**: Implement lazy loading for images to improve performance.
- **Animations**: Add CSS animations for hover effects or when portfolio items load.

## License

This project is licensed under the MIT License - see the LICENSE file for details.