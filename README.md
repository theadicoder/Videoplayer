
Here's a Markdown description for the provided code:

```markdown
# Admin Video Upload - Suggested Videos

This project provides a dynamic admin video upload interface integrated with a Wistia video player and a sleek UI built using **Tailwind CSS**. The dashboard supports video management features, a responsive navigation menu, and a pop-up welcome message. Below is a detailed overview of the features included in this project:

---

## Features

### 1. **Responsive Side Navigation**
- A hamburger menu icon toggles the side navigation.
- Links to key sections like Home, About, Services, and Contact.
- Integrated **social media icons** with hover effects for platforms like Facebook, Twitter, and Google.

### 2. **Video Player Integration**
- Embedded video player using **Wistia API**.
- Dynamically fetches and displays videos via the Wistia platform.
- Progress bar to track video completion.
- Previous and Next buttons for seamless navigation between tutorials.

### 3. **Suggested Videos Section**
- A searchable list of related or suggested videos.
- User-friendly input box to filter videos dynamically.
- Displayed as an organized list for quick access.

### 4. **Welcome Popup**
- A stylish modal popup welcomes users to the dashboard.
- Includes a **"Get Started"** button for user interaction.
- Smooth animations with fade-in effects.

### 5. **Live Video Highlight**
- Videos marked as "live" have a red glowing border for visual distinction.
- Custom styles ensure live videos grab the user's attention.

### 6. **Modern Design**
- Powered by **Tailwind CSS** for a responsive and visually appealing interface.
- Supports mobile and desktop screen sizes with adaptive styles.
- Includes Font Awesome icons for interactive and accessible design.

---

## How It Works

### **1. Welcome Popup**
- Automatically appears when the page loads.
- Can be manually closed by the user.

### **2. Navigation**
- The hamburger icon toggles the side navigation.
- The `Login` button and social media links are easily accessible.

### **3. Wistia Video Player**
- Fetches video data using Wistia’s REST API.
- Displays the first video as the main player content.
- Suggested videos are populated dynamically from the API response.

---

## API Integration

### Wistia API
- The project uses the Wistia API to fetch video content dynamically.
- **Authorization**: Requires an API key for authenticated requests.

**Sample API Request**:
```javascript
const response = await fetch('https://api.wistia.com/v1/medias.json', {
    headers: { 'Authorization': `Bearer ${API_KEY}` }
});
```

---

## Styles and Animations

- **Glow Effect**: Live videos feature a red glowing border and box-shadow.
- **Popup Animation**: The welcome popup slides in with a fade effect.
- **Hover Effects**: Buttons and social icons provide feedback on hover.

### Example CSS for Live Video
```css
.wistia_embed.live-video {
    box-shadow: 0 0 15px 5px rgba(255, 0, 0, 0.8);
    border: 2px solid red;
    background-color: rgba(255, 0, 0, 0.1);
}
```

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/theadicoder/Videoplayer.git
```

### 2. Install Dependencies
This project primarily uses **HTML, CSS, and JavaScript**. No additional dependencies are required.

### 3. Run the Project
Open the `index.html` file in your browser to view the dashboard.

---

## Future Enhancements

- Add user authentication for better access control.
- Enable video upload functionality for admins.
- Implement analytics for video performance tracking.

---

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---
```

This Markdown file provides a clear and structured overview of the project. Let me know if you'd like to customize or refine it further!
