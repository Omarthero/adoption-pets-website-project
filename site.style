// JavaScript for Webpage Layout

document.addEventListener("DOMContentLoaded", () => {
    // Select buttons and add click events
    const buttons = document.querySelectorAll("header .buttons button");

    buttons.forEach((button, index) => {
        button.addEventListener("click", () => {
            alert(`Button ${index + 1} clicked!`);
        });
    });

    // Example of adding dynamic content to the main image section
    const mainImageSection = document.querySelector(".main-image");
    mainImageSection.addEventListener("click", () => {
        mainImageSection.innerHTML = `<h1>New Images Loaded!</h1>`;
    });

    // Add hover effects for image boxes
    const imageBoxes = document.querySelectorAll(".image-box");

    imageBoxes.forEach((box) => {
        box.addEventListener("mouseenter", () => {
            box.style.backgroundColor = "#bbb";
        });
        box.addEventListener("mouseleave", () => {
            box.style.backgroundColor = "#ddd";
        });
    });
});
