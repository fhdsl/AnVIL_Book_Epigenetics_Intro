# Billing

Modules about billing and Billing Projects on Google Cloud Platform and Terra.

<br>

## Create Google Billing Account


1. Log in to the [Google Cloud Platform](https://console.cloud.google.com/) console using your Google ID. **Make sure to use the same Google account ID you use to log into Terra.**  

1. If you are a first time user, don’t forget to claim your free credits! If you haven't been to the console before, once you accept the Terms of Service you will be greeted with an invitation to "Try for Free."

    <img src="00-billing_modules_files/figure-html//1tGpzZaQxoTAcxs_nyyNL2FOqypjEofEnMVpBtZiAw4A_g116ca06e27d_0_0.png" alt="Screenshot of the Google Cloud Console with the 'Try for Free' button highlighted." width="480" />

1. Follow the instructions to sign up for a Billing Account and get your credits. 

1. Choose “Individual Account”. This “billing account” is just for managing billing, so you don’t need to be able to add your team members. You will need to give either a credit card or bank account for security. Don't worry! **You won't be billed until you explicitly turn on automatic billing**.

    <img src="00-billing_modules_files/figure-html//1tGpzZaQxoTAcxs_nyyNL2FOqypjEofEnMVpBtZiAw4A_g116ca06e27d_0_146.png" alt="Screenshot of the Google Cloud Billing Account Setup, with 'Individual Account' highlighted.  Also highlighted is text stating 'You won't be charged unless you manually upgrade to a paid account'." width="480" />

1. You can view and edit your new Billing Account, by selecting “Billing” from the left-hand menu, or going directly to the billing console [console.cloud.google.com/billing](https://console.cloud.google.com/billing) 

    <img src="00-billing_modules_files/figure-html//1tGpzZaQxoTAcxs_nyyNL2FOqypjEofEnMVpBtZiAw4A_g116ca06e27d_0_293.png" alt="Screenshot of the Google Cloud Console dropdown menu, with 'Billing' highlighted." width="480" />

1. Clicking on the Billing Account name will allow you to manage the account, including accessing reports, setting alerts, and managing payments and billing.

    <img src="00-billing_modules_files/figure-html//1tGpzZaQxoTAcxs_nyyNL2FOqypjEofEnMVpBtZiAw4A_g116ca06e27d_0_437.png" alt="Screenshot of the Google Cloud Console Billing Page, with the name of the new billing account highlighted." width="480" />

At any point, you can create additional Billing Accounts using the **Create Account** button.  We generally recommend creating a new Billing Account for each funding source.

## Add Terra to Google Billing Account


This gives Terra permission to create projects and send charges to the Google Billing Account, and must be done by an administrator of the Google Billing Account.

Terra needs to be added as a "Billing Account User":

1. Log in to the [Google Cloud Platform](https://console.cloud.google.com/) console using your Google ID.
1. Navigate to [Billing](https://console.cloud.google.com/billing)

    <img src="00-billing_modules_files/figure-html//1OqSVH5Y4v97-OKMnEDGGuhKBJwc9fyXc-Q1-ivbeZmA_g115e284bdc2_0_144.png" alt="Screenshot of the Google Cloud Console drop-down menu, with 'Billing' highlighted." width="480" />

1. You may be automatically directed to view a specific Billing Account.  If you see information about a single account rather than a list of your Billing Accounts, you can get back to the list by clicking "Manage Billing Accounts" from the drop-down menu.
 
    <img src="00-billing_modules_files/figure-html//1OqSVH5Y4v97-OKMnEDGGuhKBJwc9fyXc-Q1-ivbeZmA_g115e284bdc2_0_295.png" alt="Screenshot of an individual Google Cloud Billing Account with the drop-down menu item 'Manage Billing Accounts' highlighted." width="480" />

1. Check the box next to the Billing Account you wish to add Terra to, click "ADD MEMBER".

    <img src="00-billing_modules_files/figure-html//1OqSVH5Y4v97-OKMnEDGGuhKBJwc9fyXc-Q1-ivbeZmA_g116e2c647a7_0_151.png" alt="Screenshot of Google Cloud Billing Accounts Overview. The checkbox next to the name of a Billing Account is checked and highlighted, and the 'Add Member' button is highlighted." width="480" />

1. Enter `terra-billing@terra.bio` in the text box.  In the drop-down menu, mouse over Billing, then choose "**Billing Account User**".

    <img src="00-billing_modules_files/figure-html//1OqSVH5Y4v97-OKMnEDGGuhKBJwc9fyXc-Q1-ivbeZmA_g116e2d0fe67_0_0.png" alt="Screenshot of the dialogue box for adding a member to a Google Cloud Billing Accounts. The text box is highlighted and has been filled in with 'terra-billing@terra.bio'.  In the drop-down menu labeled 'Select a Role', the item 'Billing' and the submenu item 'Billing Account User' are highlighted." width="480" />

1. Click "SAVE".

    <img src="00-billing_modules_files/figure-html//1OqSVH5Y4v97-OKMnEDGGuhKBJwc9fyXc-Q1-ivbeZmA_g116e2d0fe67_0_146.png" alt="Screenshot of the dialogue box for adding a member to a Google Cloud Billing Accounts. The Save button is highlighted." width="480" />

## Create Terra Billing Project


1. [Launch Terra](https://anvil.terra.bio/#workspaces) and sign in with your Google account.  If this is your first time logging in to Terra, you will need to accept the Terms of Service.

1. In the drop-down menu on the left, navigate to "Billing". Click the triple bar in the top left corner to access the menu. Click the arrow next to your name to expand the menu, then click "Billing".  You can also navigate there directly with this link: https://anvil.terra.bio/#billing

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g116f8d759be_0_2.png" alt="Screenshot of the Terra drop-down menu.  Three items are highlighted: 1) the 'hamburger' button for extending the drop-down menu, 2) the arrow next to your username, for extending the drop-down submenu, and 3) the submenu item 'Billing'." width="100%" />

1. On the Billing page, click the "+ CREATE" button to create a new Billing Project. Select GCP Billing Project (Google's Platform). If prompted, select the Google account to use and give Terra permission to manage Google Cloud Platform billing accounts.

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g116f8d759be_0_149.png" alt="Screenshot of the Terra Billing Page.  The 'plus' button next to 'Billing Projects' is highlighted." width="100%" />

1. Enter a **unique** name for your Terra Billing Project and select the appropriate Google Billing Account. The name of the Terra Billing Project must:
    + Only contain lowercase letters, numbers and hyphens
    + Start with a lowercase letter
    + Not end with a hyphen
    + Be between 6 and 30 characters

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g116f8d759be_0_293.png" alt="Screenshot of the Terra Add Billing Project dialog box." width="100%" />
    
1. Select the Google Billing Account to use.  All activities conducted under your new Terra Billing Project will charge to this Google Billing Account.  If prompted, give Terra permission to manage Google Cloud Platform billing accounts.

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g2105956e909_0_0.png" alt="Screenshot of the Terra Add Billing Project dialog box.  The dropdown menu labeled 'Select billing account' is highlighted." width="100%" />

1. Click "Create".

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g116f8d759be_0_438.png" alt="Screenshot of the Terra Add Billing Project dialog box.  The button labeled 'CREATE BILLING PROJECT' is highlighted." width="100%" />


1. Your new Billing Project should now show up in the list of Billing Projects Owned by You.  You can add additional members or can modify or deactivate the Billing Project at any time by clicking on its name in this list.

    <img src="00-billing_modules_files/figure-html//1POwxqv4p6AfPHJlN9VNq0TaT44fA2RAFSpIERIMHdWU_g2105956e909_0_16.png" alt="Screenshot of the Terra Billing Projects menu.  The submenu 'Owned by you' is highlighted and has been expanded, showing a list of Billing Projects below.  One of the Billing Project names is highlighted." width="100%" />

The page doesn't always update as soon as the Billing Project is created.  If it's been a couple of minutes and you don't see a change, try refreshing the page.

## Add Members to Google Billing Account


Anyone you wish to add to the Billing Account will need their own Google ID.

To add a member to a Billing Project:
  
1. Log in to the [Google Cloud Platform](https://console.cloud.google.com/) console using your Google ID.
1. Navigate to [Billing](https://console.cloud.google.com/billing)

    <img src="00-billing_modules_files/figure-html//1j1wRbaDyHJJhZQcWcP4xeYgIoaIBRIF3LIZpiDPBumw_g115e284bdc2_0_144.png" alt="Screenshot of the Google Cloud Console drop-down menu, with 'Billing' highlighted." width="480" />

1. You may be automatically directed to view a specific Billing Account.  If you see information about a single account rather than a list of your Billing Accounts, you can get back to the list by clicking "Manage Billing Accounts" from the drop-down menu.

    <img src="00-billing_modules_files/figure-html//1j1wRbaDyHJJhZQcWcP4xeYgIoaIBRIF3LIZpiDPBumw_g115e284bdc2_0_295.png" alt="Screenshot of an individual Google Cloud Billing Account with the drop-down menu item 'Manage Billing Accounts' highlighted." width="480" />

1. Check the box next to the Billing Account you wish to add a member to, click "ADD MEMBER".

    <img src="00-billing_modules_files/figure-html//1j1wRbaDyHJJhZQcWcP4xeYgIoaIBRIF3LIZpiDPBumw_g116e2c647a7_0_151.png" alt="Screenshot of Google Cloud Billing Accounts Overview. The checkbox next to the name of a Billing Account is checked and highlighted, and the 'Add Member' button is highlighted." width="480" />

1. Enter their Google ID in the text box. In the drop-down menu, mouse over Billing, then choose the appropriate role.

    <img src="00-billing_modules_files/figure-html//1j1wRbaDyHJJhZQcWcP4xeYgIoaIBRIF3LIZpiDPBumw_g116e2c647a7_0_296.png" alt="Screenshot of the dialogue box for adding a member to a Google Cloud Billing Accounts. In the drop-down menu labeled 'Select a Role', the item 'Billing' and the submenu item 'Billing Account Viewer' are highlighted." width="480" />

1. Click "SAVE".

    <img src="00-billing_modules_files/figure-html//1j1wRbaDyHJJhZQcWcP4xeYgIoaIBRIF3LIZpiDPBumw_g116e2c647a7_0_441.png" alt="Screenshot of the dialogue box for adding a member to a Google Cloud Billing Accounts. The Save button is highlighted." width="480" />

## Set Alerts for Google Billing


1. Log in to the [Google Cloud Platform](https://console.cloud.google.com/) console using the Google ID associated with your Google Cloud projects.

1. Open the dropdown menu on the top left and click on [Billing](https://console.cloud.google.com/billing).

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_144.png" alt="Screenshot of the Google Cloud Console drop-down menu, with 'Billing' highlighted." width="480" />

1. You may be automatically directed to view a specific Billing Account. If you see information about a single account (and it’s not the one you’re interested in), you can get back to the list of all your Billing Accounts by clicking "Manage Billing Accounts" from the drop-down menu.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_295.png" alt="Screenshot of an individual Google Cloud Billing Account with the drop-down menu item 'Manage Billing Accounts' highlighted." width="480" />

1. Click on the name of the Billing Account you want to set alerts for.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_150.png" alt="Screenshot of Google Cloud Billing Accounts Overview. A Billing Account name is highlighted." width="480" />

1. In the left-hand menu, click "Budgets & alerts".
 
    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_442.png" alt="Screenshot of an individual Google Cloud Billing Account with the left-hand menu item 'Budgets &amp; alerts' highlighted." width="480" />

1. Click the "Create Budget" tab.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_587.png" alt="Screenshot of the budgets and alerts page for a Google Cloud Billing Account. The 'Create Budget' button highlighted." width="480" />

1. Enter a name for your budget, and then choose which projects you want to monitor. Then click "Next".

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_732.png" alt="Screenshot of the form for setting budget scope for a Google Cloud Billing Account. Three things are highlighted:  1) the box for entering a 'Name' for the budget, 2) the dropdown menu labeled 'Projects' for selecting which Billing Projects are part of the budget, and 3) the 'Next' button." width="480" />

1. For Budget Type, select "Specified amount". Enter the total budget amount for the month (you will set alerts at different thresholds in the next step). Click "**Next**" (do not click "Finish").

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_878.png" alt="Screenshot of the form for setting budget amount for a Google Cloud Billing Account.  The drop-down menu labeled 'Budget type' is highlighted and 'Specified amount' is selected.  Also highlighted are the text box labeled 'Target amount' and the 'Next' button." width="480" />

1. Enter the threshold amounts where you want to receive an alert. We recommend starting with 50% and 90%. You can set other alerts if you prefer.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_1025.png" alt="Screenshot of the form for setting budget actions for a Google Cloud Billing Account.  The boxes for entering 'Percent of budget' or 'Amount' are highlighted.  The drop-down menu labeled 'Trigger on' is highlighted and 'Actual' is selected." width="480" />

1. Check the box for "Email alerts to billing admins and users", then click "**Finish**". Now you (as the owner and admin), along with anyone you added with admin or user privileges (e.g. lab managers) will receive alerts when your lab members reach the specified spending thresholds. These emails will be sent to the Gmail accounts associated with the Billing Account.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_1169.png" alt="Screenshot of the form for setting budget alerts for a Google Cloud Billing Account.  The checkbox labeled 'Email alerts to billing admins and users' is highligheted and checked.  The 'Finish' button is highlighted." width="480" />

1. You can edit your budgets at any time by going to Billing > Budgets & alerts, and clicking on the name of the budget you want to edit.

    <img src="00-billing_modules_files/figure-html//1GBYTx25VzBFh7kI_elgMC0fmOMm4YhcfW8wIJ1EkmKY_g115e284bdc2_0_1314.png" alt="Screenshot of the Google Cloud Billing Account Budgets and alerts overview.  Four items are highlighted illustrating how to view and edit an existing budget: 1) The top-left 'hamburger' button for extending the drop-down menu, 2) the drop-down menu item 'Billing', 3) the submenu item 'Budgets &amp; alerts', 4) the name of a budget." width="480" />

## View Spend for Google Billing


You can always check your current spend through the Google Billing console, but remember

- There is a reporting delay (~1 day), so you cannot immediately see what an analysis cost
- Costs are reported at the level of Workspaces, so if there are multiple people using a Workspace, you will not be able to determine which of them was responsible for the charges.

The Google Billing console displays information by Billing Account.  To view spending:
  
1. Log in to the [Google Cloud Platform](https://console.cloud.google.com/) console using the Google ID associated with your Google Cloud projects.

1. Open the dropdown menu on the top left and click on [Billing](https://console.cloud.google.com/billing).

    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g115e284bdc2_0_144.png" alt="Screenshot of the Google Cloud Console drop-down menu, with 'Billing' highlighted." width="480" />

1. You may be automatically directed to view a specific Billing Account. If you see information about a single account (and it’s not the one you’re interested in), you can get back to the list of all your Billing Accounts by clicking "Manage Billing Accounts" from the drop-down menu.

    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g115e284bdc2_0_295.png" alt="Screenshot of an individual Google Cloud Billing Account with the drop-down menu item 'Manage Billing Accounts' highlighted." width="480" />

1. Click on the name of the Billing Account for the project you want to view.

    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g115e284bdc2_0_150.png" alt="Screenshot of Google Cloud Billing Accounts Overview. A Billing Account name is highlighted." width="480" />

1. Look at the top of the **Overview** tab to see your month-to-date spending.
    
    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g1149729109c_0_0.png" alt="Screenshot of a Google Cloud Billing Account Overview." width="480" />

1. Scroll further down the **Overview** tab to show your top projects.
    
    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g1149729109c_0_143.png" alt="Screenshot of a Google Cloud Billing Account top projects." width="480" />

1. Click on the **Reports** tab to see more detailed information about each of your projects.  This is probably the most useful tab for exploring costs of individual projects over time.

    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g1149729109c_0_433.png" alt="Screenshot of a Google Cloud Billing Account Reports tab." width="480" />

1. Click on the **Cost table** tab to obtain a convenient table of spending per project.
    
    <img src="00-billing_modules_files/figure-html//1Ofs1As7XZWmxnaBOZvNYzAiuuaYgn1ce700eHyCNg2Y_g1149729109c_0_577.png" alt="Screenshot of a Google Cloud Billing Account Cost table tab." width="480" />

