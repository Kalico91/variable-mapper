# Variable Mapper

A web-based tool for standardizing variables in Excel files, perfect for systematic reviews and meta-analyses.

## 🚀 Live Tool

**[Click here to use Variable Mapper](https://Kalico91.github.io/variable-mapper/)**

## 📋 Features

- Upload a single sheet Excel file (.xlsx or .xls)
- Select which column contains variables to standardize
- Create standardization mappings interactively
- Export code to create a new column within your dataset for R (CSV output) or Python (Excel output)
- Works entirely in your browser - no data uploaded to servers


## 🎯 Use Cases

- Systematic reviews requiring variable harmonization
- Meta-analyses with inconsistent variable naming
- Data cleaning and standardization projects
- Research data preparation

## 💻 How to Use

1. **Upload** - Drag and drop or browse for your Excel file
2. **Select** - Choose the column containing variables to standardize
3. **Map** - Click values to assign them to standard categories
4. **Export** - Copy R or Python code to apply standardizations

## 🔒 Privacy

All processing happens in your browser. No data is sent to any server.

## 📝 Example Workflow

1. Upload: `research_data.xlsx`
2. Select column: `measurement_type`
3. Map similar values:
   - "height", "Height", "HEIGHT" → "Height"
   - "weight", "wt", "Weight" → "Weight"
4. Export code and run on your full dataset

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.

## 📄 License

This tool is free to use and modify.
