<h1>Google Ads - Spent budget report script </h1>
<p>This script is designed to pull data from a Google Ads campaign and populate a Google Sheet with information on campaign performance during a selected month. The data includes the campaign name, cost, advertising channel type, and conversion value, and is sorted by channel type and campaign name. The script also formats the sheet by highlighting each channel type and merging the appropriate cells. This can help advertisers better analyze and understand their campaign performance for a given period.</p>
<ol>
  <li>Open a Google Sheet where you want the data to be dumped.</li>
  <li>Go to the "Tools" menu and select "Script editor".</li>
  <li>Paste the script into the editor.</li>
  <li>Replace the URL in line 2 with the URL of your Google Sheets document.</li>
  <li>Replace the sheet name in line 3 with the name of the sheet where you want the data to be dumped.</li>
  <li>Save the script.</li>
  <li>Go to the "Run" menu and select "main".</li>
  <li>If prompted, authorize the script to access your Google Ads and Sheets accounts.</li>
  <li>Once authorized, the script will run and populate the sheet with data.</li>
</ol>
<p>To use the script, select the month you want to analyze in cell E4 of the sheet. The script will pull data for the selected month and populate the sheet with campaign performance metrics. Make sure to re-run the script each time you want to analyze a different month's data.</p>
