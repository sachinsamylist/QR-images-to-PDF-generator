# QR Code PDF Generator 🧾

This project is a **Python script** that creates a print-ready PDF from a folder of QR code images. It arranges the images in a **grid layout on A4-sized pages** and adds **cut marks** to assist with manual cutting.

## ✨ Features

- Automatically detects QR code images (`.png`, `.jpg`, `.jpeg`)
- Customizable number of rows and columns per page
- Adds crop/cut marks around each QR code
- Centers the grid layout on A4 paper
- Supports high-quality export for printing

## 📁 Folder Structure

```
📂 your-folder/
├── qr_code_001.png
├── qr_code_002.png
├── ...
```

## 🛠️ Requirements

- Python 3.x
- [`reportlab`](https://pypi.org/project/reportlab/)

Install dependencies:
```bash
pip install reportlab
```

## 🚀 How to Use

1. Update the `folder_path` and `output_pdf` in the script to match your paths.
2. Customize the number of rows, columns, or QR size if needed.
3. Run the script:
   ```bash
   python generate_qr_pdf.py
   ```

## 🧩 Example Use Cases

- Generating QR labels for product packaging
- Creating ID tags with QR codes
- Bulk printing of event badges

## 📌 Customization

You can easily tweak:
- Page size (`A4`, `letter`, etc.)
- QR size
- Spacing between QR codes
- Cut mark length

## 📄 License

This project is open-source and available under the MIT License.

---

✅ Generated with 💡 by [Sachin Samy](https://github.com/sachinsamylist/QR-images-to-PDF-generator)

