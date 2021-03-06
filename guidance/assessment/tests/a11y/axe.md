You need to run the aXe tool on each page you test. You also need to run it for each viewport because different responsive designs may present different accessibility errors.

1. Run the aXe extension in Chrome by opening the developer tools. To find them, right-click and choose inspect. 

2. Along the top line you should be able to select aXe, if you have it installed. (You may have to hit the &gt;&gt; toggle on the right of the toolbar to reveal the “aXe” option.)

	![Screenshot showing location of aXe extension in Chrome](https://govtnz.github.io/web-standards/assets/img/aXe-button.jpg) 

3. Hit the 'Analyze' button. 

4. In the aXe summary pane (where the issues are summarised), change the drop-down option from 'show:all' to 'show: violations'.

5. Select the list of issues including the number of violations.

    ![Screenshot showing how to select the list of issues](https://govtnz.github.io/web-standards/assets/img/aXe.jpg) 

6. Copy and paste the results into the appropriate single cell for desktop-size results in the Self-Assessment report spreadsheet. 

7. Resize your browser window to simulate an iPad (768x1024). If there is no change in the page content or layout, choose 'no change' in the cell for tablet-size results. Otherwise, run 'Analyze' again, and copy and paste those results in the appropriate cell.

8. Finally, resize to simulate an iPhone 5 (320x568). If there is no change in the page content or layout, choose 'no change' in the cell for phone-size results. Otherwise, run 'Analyze' again, and copy and paste those results in the appropriate cell.