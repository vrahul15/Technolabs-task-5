# 🥗 Healthy Recipes Website

Welcome to the **Healthy Recipes** project! This website showcases a delicious and nutritious Kale Caesar Quinoa Salad with Roasted Chicken, styled with modern CSS for an engaging and responsive user experience.

---

## 🌟 Features

- **Modern Glassmorphism Design**  
  Elegant cards with blur and shadow effects for ingredients and preparation steps.

- **Vibrant SeaGreen Accents**  
  SeaGreen is used throughout for headings, buttons, and highlights.

- **Animated Elements**  
  Smooth fade-ins, floating images, and interactive hover effects.

- **Responsive Layout**  
  Looks great on all devices, from desktops to smartphones.

- **Accessible & Readable**  
  Clear font choices and color contrasts for easy reading.

---

## 📋 Tasks Completed

### 1. **Image Styling**
- The top image is made smaller and floats gently for visual appeal.
- CSS:
  ```css
  img {
    height: 150px; /* Responsive on mobile */
    /* ...other styles... */
  }
  ```

### 2. **Recipe Description**
- The description uses a vibrant purple color and larger font for emphasis.
- CSS:
  ```css
  .description {
    font-size: 22px;
    color: #8e24aa;
  }
  ```

### 3. **Total Time Highlight**
- The total time is bold and SeaGreen for quick visibility.
- CSS:
  ```css
  #cook-time {
    font-weight: bold;
    color: #2e8b57;
  }
  ```

### 4. **Ingredients List**
- Ingredients use square bullets and a salad emoji for fun.
- CSS:
  ```css
  .ingredients li {
    list-style: square;
    color: #2e8b57;
  }
  ```

### 5. **Preparation Step Times**
- Each step’s time appears in gray, turning SeaGreen on hover.
- CSS:
  ```css
  p.time {
    color: gray;
  }
  ol li:hover p.time {
    color: #2e8b57;
  }
  ```

### 6. **External Recipe Link**
- The link is styled as a modern, glassy SeaGreen button with a gradient and hover effect.
- CSS:
  ```css
  .external-link {
    color: #fff;
    background: linear-gradient(90deg, #2e8b57 0%, #43e97b 100%);
    /* ... */
  }
  ```

### 7. **Font Family**
- All main text uses Helvetica for a clean, modern look.
- CSS:
  ```css
  h1, h2, p, li {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
  ```

### 8. **Responsive Design**
- The layout, font sizes, and paddings adjust for tablets and mobile screens.
- CSS:
  ```css
  @media (max-width: 700px) { ... }
  @media (max-width: 400px) { ... }
  ```

---

## 🚀 How to Use

1. **Clone or Download** this repository.
2. Open `index.html` in your browser.
3. Explore the beautiful, animated, and responsive recipe page!

---

## 👩‍💻 Tech Stack

- **HTML5**
- **CSS3 (with animations and responsive design)**

---

## 💡 Credits

Created for the **TechnoCollabs Team** as part of Task 5: Healthy Recipes.

---

> _Eat healthy, code happy!_
