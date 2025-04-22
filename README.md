# 🎨 Image Stylizer

A simple and fun tool to stylize your images using **ordered dithering** and custom color palettes.

Try it out live 👉 [Z3's Image Stylizer](https://z3.pythonanywhere.com/)

![Demo Screenshot](https://github.com/user-attachments/assets/6de6f14a-5d66-472b-b6b0-d0e30d10acb1)

---

## ✨ Features

- Apply **ordered dithering** to any image.
- Choose from randomly generated but pretty palettes.
- Fast and easy to use via a web interface.
- Ideal for **artistic filters**, retro effects, or experimentation with image quantization.

---

## 🚀 Getting Started

### 🔧 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Z3R0C1PH3R/image-stylizer.git
cd image-stylizer
pip install -r requirements.txt
```

### ▶️ Running the App

Navigate to the webapp directory and start the server:

```bash
cd webapp
python3 app.py
```

The app will be available at `http://localhost:5000/`.

---

## 🖼️ Example

Upload an image, generate a palette, tweak a few sliders—**and watch your image transform**!

<table>
  <tr>
    <td><strong>Original Image</strong></td>
    <td><strong>Stylized with Palette 1</strong></td>
    <td><strong>Stylized with Palette 2</strong></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/6687f0ee-30c6-4cf2-9c42-012fc2f85f99" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/cfdabda9-c130-4944-aac7-9510f32b96ae" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/37e33230-7bad-42cb-87da-4f1c02764e55" width="250"/></td>
  </tr>
</table>

> 🎨 **Palettes**  
> - *Palette 1*: `#58415e, #7c497a, #9d4e89, #b9598a, #cb6c88, #db8388, #e8a89c, #f2ceb8`  
> - *Palette 2*: `#516148, #577e50, #569f5c, #63b87d, #77cba3, #8ddbc8, #a6e8e7, #c2e9f3`

> ⚙️ **Settings used for both styles**  
> - Dithering Spread: `9%`  
> - Bloom: Radius `10%`, Threshold `65%`, Amount `30%`  
> - Resize: `30%` (Interpolation: *Area*)

---

## 📜 License

**No license has been specified for this project yet.**  
Feel free to explore and use it for personal or educational purposes, but please reach out before using it in commercial projects or redistributing.

---

## 🙌 Contributing

Contributions are welcome! Feel free to submit issues, fork the repo, or open pull requests.
