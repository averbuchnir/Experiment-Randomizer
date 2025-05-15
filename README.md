# Array Randomizer

Array Randomizer is a Python desktop application for generating randomized experimental layouts, such as block designs or full randomizations, commonly used in plant science and agricultural experiments. The application provides a graphical user interface (GUI) built with Tkinter, allowing users to input experimental parameters and export randomized layouts and maps as CSV files.

## Features

- **Block Design and Full Randomization:** Supports both block design and full randomization of treatments.
- **Customizable Parameters:** Input the number of lines, treatments, repetitions, and rows.
- **CSV Export:** Outputs randomized layouts and maps to CSV files for further analysis or printing.
- **Image Export:** Save the generated table as an image.
- **File-Based Input:** Option to load experiment parameters from an `Info.csv` file.
- **User-Friendly GUI:** Intuitive interface with clear instructions and error messages.
- **YouTube Guide:** Link to a video tutorial for additional help.

## Requirements

- Python 3.x
- numpy
- pandas
- pygetwindow
- Pillow

Install dependencies with:

```sh
pip install numpy pandas pygetwindow Pillow
```

## Usage

1. **Run the Application:**

   ```sh
   python "Randomizer 3.1.py"
   ```

2. **Input Parameters:**
   - Enter the number of lines, treatments, repetitions, and rows.
   - Fill in the names for each line and treatment.
   - Choose between Block Design or Full Randomization.

3. **Export Results:**
   - Click the relevant buttons to generate and export CSV files.
   - Use the "Save Table Image" feature to export the layout as an image.

4. **File-Based Workflow:**
   - Use the "Take me to my files" button to open the working directory and edit `Info.csv` for batch input.

## Notes

- Do **not** use commas `,`, underscores `_`, or dashes `-` in line or treatment names.
- All output files are saved in the same directory as the program.
- Close all output files before running a new randomization to avoid file access errors.

## Troubleshooting

- If you encounter an error about open files, close the relevant CSV or image files and try again.
- For detailed instructions, watch the [YouTube Guide](https://youtu.be/B_aKeMaB5yU).

## License

This project is provided as-is for research and educational purposes.

---

**Author:**  
Nir Averbuch  
averbuch.nir@gmail.com

If you use this tool in your research, please cite appropriately.