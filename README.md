
---

🛠️ Tools & Software Used

| Tool         | Description                         |
|--------------|-------------------------------------|
| **SolidWorks**   | 3D CAD software for modeling the enclosure |
| **Cura Ultimaker** | Slicing software to generate G-code for 3D printing |
| **GrabCAD**     | To find the 3D model of the sensor module |


---

🚀 How to Use

1. 📐 Design Preparation
- Search for your sensor model online (e.g., MLX90641).
- Download its datasheet and check pin layout, size, and mounting holes.
- Optionally, download a reference 3D model from [GrabCAD](https://grabcad.com).

2. 🧰 CAD Modeling (SolidWorks)
- Create new parts: Top and Bottom cover.
- Use smart dimensions, sketch tools, and features like **Boss-Extrude**, **Cut-Extrude**, and **Evaluate → Measure**.
- Use **Appearances → Decals** to add your logo.
- Save parts and assemble using **Mate** in SolidWorks.

3. 🧪 Section & Export
- Use `Section View` to inspect internal fitting.
- Save your model as `.STL` for 3D printing.

4. 🖨️ 3D Printing (Cura Ultimaker)
- Import STL files into Cura.
- Adjust orientation to reduce support material.
- Set infill: 30% is typical, use higher for mechanical load.
- Generate G-code and transfer to 3D printer via SD card.

---

📏 Design Notes

- Sensor used: **MLX90641 IR Array (8x8 pixels)**
- Typical temperature range: 0°C – 80°C
- Case thickness: **1–2 mm**
- Allow spacing for:
  - Sensor header pins
  - Heat dissipation (use vents or heat sink)
  - Camera aperture via circular cutout

---

🧠 Tips & Considerations

- Ensure the enclosure is not trapping heat — thermal sensors require ventilation.
- If you're planning to integrate this into a larger system (with a microcontroller, for example), consider leaving room for wiring.
- Keep the design modular with nut-and-bolt hooks for easy mounting.

---

📷 Screenshots

| Assembly Preview | 
|------------------|
Check the files in the repo to find relevant screenshots and views . Happy Learning !

---

🙌 Acknowledgements

- **[GrabCAD](https://grabcad.com/library/grove-thermal-imaging-camera-mlx90614-1)** – For sensor model references.
- **[Cura Ultimaker](https://ultimaker.com/software/ultimaker-cura/)** – Free slicing software.
- **YouTube Viewers** – Thanks for supporting and subscribing!

---

📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

🌟 Show Your Support

If you found this helpful:

⭐ Star this repo  
🔔 Subscribe on Youtube Edge Neuron Channel  https://www.youtube.com/@EdgeNeuron

🛠️ Remix or fork this project

Stay tuned for upcoming updates where we connect this sensor to microcontroller

If you have any Queries or want to develop a custom casing of your own , write to kalpruh.original@gmail.com

