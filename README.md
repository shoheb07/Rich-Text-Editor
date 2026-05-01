# Rich-Text-Editor
simple Rich Text Editor built using HTML, CSS, and JavaScript. It includes basic formatting features like bold, italic, underline, lists, alignment, and links.

📝 Rich Text Editor

A simple and lightweight Rich Text Editor built using HTML, CSS, and JavaScript. This editor allows users to format text directly in the browser with common editing tools.

---

🚀 Features

- Bold, Italic, Underline formatting
- Text alignment (Left, Center, Right)
- Ordered and Unordered lists
- Insert hyperlinks
- Clear formatting
- Editable content area (WYSIWYG)

---

📂 Project Structure

rich-text-editor/
│── index.html   # Main editor file

---

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

▶️ How to Run

1. Download or copy the code into a file named "index.html"
2. Open the file in any modern web browser (Chrome, Edge, Firefox)
3. Start typing and use the toolbar to format text


🧠 How It Works

- The editor uses a "contenteditable" "<div>" to allow direct text editing.
- Formatting actions are applied using:
  document.execCommand()
- Toolbar buttons trigger different formatting commands like "bold", "italic", etc.


⚠️ Limitations

- Uses "document.execCommand()", which is deprecated (but still supported in browsers)
- Limited advanced editing features
- No built-in saving or exporting functionality


🔮 Future Enhancements

- Add font size, font family, and text color options
- Add undo/redo functionality
- Save content to local storage or database
- Export content as HTML/PDF
- Replace deprecated API with modern editor libraries


📚 Alternatives (Advanced Editors)

For production-level applications, consider:

- Quill.js
- TinyMCE
- Draft.js


📜 License

This project is open-source and free to use for learning and personal projects.


🙌 Contribution

Feel free to improve this project by adding new features or optimizing the code.
