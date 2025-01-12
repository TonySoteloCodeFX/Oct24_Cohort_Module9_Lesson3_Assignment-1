
---

### **Fonts:**
- **njnaruto.ttf**: Custom font for Naruto-themed text.
  - Located in `fonts` folder.
  - Applied via the `@font-face` rule in **index.css** to ensure the font loads properly.

---

### **Images:**
- **Character Images**: Various character images are used as backgrounds for cards.
  - **Images Used**:
    - Naruto, Sasuke, Kakashi, Sakura, Madara, Orochimaru, Pain, Itachi (all these images are stored in `/images`).
  
---

### **CSS Breakdown:**

- **default.css**:
  - **Global styles**: Resets margin, padding, and sets box-sizing for consistency.
  - **Body Styles**: Background set to a **linear gradient** from dark to orange, creating a Naruto-inspired color scheme.
  - **Dark Theme Layout**: Uses **CSS Grid** to organize the layout into a header, main content, and footer section.

- **index.css**:
  - **Font Import**: The custom `NJNaruto` font is applied using `@font-face`.
  - **Main Content Styling**:
    - Text headings use **Naruto’s gradient** (a mix of orange shades).
    - The **card** components display images of characters like Naruto, Sasuke, Kakashi, etc.
    - **Flip card effect**: On hover, the front and back of the card flip with text animation.

---

### **HTML Structure:**

- **Main Layout**:
  - **Header**: Contains a **navbar** with links (Home, Submit Your Character).
  - **Main Section**: Displays the **Top 8 Characters** using **flexbox** for layout and **flip card effect** to show character details.
    - Characters include: Naruto, Sasuke, Kakashi, Sakura, Madara, Orochimaru, Pain, and Itachi.
  - **Footer**: A simple **navbar** for social media links (Facebook, Instagram).

---

### **Key Features**:
- **Naruto Theme**: The font and gradient colors align with Naruto’s aesthetic (orange, red, and black).
- **Responsive Design**: The navbar and main content adjust to different screen sizes (via Bootstrap’s grid system).
- **Interactive Cards**: Character cards flip to reveal more information about each character.

---

This is a **Naruto-themed website** where the characters are showcased using a stylish card layout, cool hover effects, and bright, Naruto-inspired colors. The custom font and background gradients help give it that distinct vibe! 😊