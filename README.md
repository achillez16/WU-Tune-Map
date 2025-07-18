Tune Map Data Extractor: User Guide
1. Summary
The Tune Map Data Extractor is a simple yet powerful web-based tool designed to streamline the process of collecting and organizing financial data. It allows users to copy a block of text containing parameters and statistics from Wealth Umbrella’s Tune Map platform and instantly convert it into a structured, spreadsheet-ready table.

This tool is built to handle specific text formats, including data points that are on the same line as their labels (e.g., "Hit Rate: 50%") and those where the value appears on the line below the label (e.g., "Symbol: \n AAPL").

2. Use Cases
This tool is ideal for:

Financial Analysts & Traders: Quickly compile performance data from multiple backtests into a single table for comparison and analysis.

Researchers: Efficiently gather and organize data for academic or personal research projects on trading strategies.

Hobbyists: Easily track the results of different trading algorithm parameters without manual data entry.

3. How to Use the Tool
The workflow is designed to be as simple as possible:

Copy Text: Navigate to the Tune Map page and select and copy the block of text containing the "Parameters" and "Statistics" you want to extract.

Paste Text: Paste the copied text into the large text box in the extractor tool.

Process: Click the "Process Text" button.

Review: The tool will instantly parse the text and display it as a new row in the "Extracted Data" table below.

Repeat: The text box will automatically clear, allowing you to paste a new block of text to add another row.

Copy Data: Once you have extracted all the desired data, click the "Copy Table Data" button to copy the entire table to your clipboard, ready to be pasted into a spreadsheet.

4. Core Functionalities
Adding Data:
To add a new row of data, simply paste a new block of text into the input box and click "Process Text." The tool will add the newly extracted data as a new row at the bottom of the table. There is no practical limit to the number of rows you can add.

Removing Data:
If you make a mistake or wish to remove a specific entry, simply hover your mouse over the row you want to delete. A red × will appear in the leftmost column. Clicking this × will immediately and permanently delete that row from the table.

Copying the Table:
The "Copy Table Data" button is designed for easy export to spreadsheet applications like Google Sheets or Microsoft Excel. It copies only the data from the table (not the headers or the delete buttons) and formats it with tabs between each cell. When you paste this into a spreadsheet, the data will automatically populate the correct columns.

5. Technical Details & Known Limitations
Parsing Logic: The tool works by recognizing labels that end with a colon (:). It can handle values that are on the same line as the label or on the immediately following line.

Duplicate Labels: The tool is designed to handle duplicate labels (like "Hit Rate") by processing the text in order and filling the columns from left to right.

Capitalization: The "Symbol" value is automatically converted to uppercase for data consistency.

Limitations: The tool's accuracy depends on the formatting of the pasted text. It may fail to extract data correctly if:

A label is missing its colon.

A value itself contains a colon (e.g., a strategy named My:Strategy).

The data is not under a recognized header from the template.

For best results, always copy the text directly from the source without making manual edits.
