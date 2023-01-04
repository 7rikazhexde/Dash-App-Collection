# Download_Plotly_Dataset
This application selects [plotly / datasets](https://github.com/plotly/datasets) from the Dropdown component and displays it in the DataTable component.The displayed Dataset (DataFrame object) is saved as a csv file by executing the Button component.

## Usage
1. Get project
```
% git clone https://github.com/7rikazhexde/Dash-App-Collection.git
```
2. Setup of virtual environment
```
% cd Download_Plotly_Dataset/dlPlotlyDataset
% poetry install
```
3. Execute the program in a virtual environment
```
% cd app
% poetry shell
% python dl_plotly_datasets.py
```
4. Application Launch

Please access the URL displayed.
```
Dash is running on http://127.0.0.1:8050/

 * Serving Flask app 'dl_plotly_datasets'
 * Debug mode: on
```

If you get an interpreter error using vscode, open and start dlPlotlyDataset with the folder designation.

## Note
* Dataset information may differ from the latest information. If the expected dataset does not exist, please add it. See the comments in plotly_datasets_info.py for details.
* An error may occur when drawing the layout.
If you cannot start with the error, please reload your browser.