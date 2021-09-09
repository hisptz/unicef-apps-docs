# BNA App interventions configurations

The BNA interventions management (settings) options are only available to users who are created with the administration privileges

Bottleneck analysis application can be found in the Apps menu. if the
application has not yet been installed in your DHIS2 instance or
installation has issues, refer to the installation instructions (Chapter
2) of this documentation for further guidance, or contact the
DHIS2 administrator for your instance.

![bottleneck analysis application on the DHIS2 app menu](resources/images/image34.png){width=50%}

## Starting an Intervention

Once open, the bottleneck analysis application will bring a list of
created interventions, or when no intervention exists, a quick create
button will display for the user to create and add a new intervention.

The new intervention dashboard will display blank templates pending data
selection and filtering.                        

![Bottleneck analysis dashboard with blank chart and table templates](resources/images/image003.png)

> **NOTE**
>
> If bottleneck analysis application is taking
too long to load, and you’re not slow on network, make sure you have
cleared your browser cache. See [BNA App Maintenance](#bna-app-maintenance) for
additional information on clearing browser cache.

The bottleneck app makes good use of cached files for better offline
experience, as a result, when installing higher versions, the bottleneck
app may use older version of cached files and thus break down while
loading.

## Intervention Settings
The administrator user can make data selections from the global filters by simply selecting Settings tab. Currently the  BNA Application supports data selections of Indicators and Functions. Clicking the Settings filter control opens a panel with a list of indicators complemented with a list of data dimension groups. When a user selects an indicator or a function from the list of available data items the selected data items will be populated to the active data dimension group.

![Settings tab for accessing BNA setting options](resources/images/image_set.png)

![BNA  Settings Layout](resources/images/image004.png){ width=70% } ![](resources/images/image43.png)

> **NOTE:**
> Long indicators can be shortened by entering alternative display names as indicated above. This will ensure your chart is readable and easily interpretable.

### Period configuration

Each intervention to be analyzed must be linked with a specific period for which the determinants members will be analyzed.

To access option for configuring period for intervention’s bottleneck analysis click on “Bottleneck period type”

![Accessing option for configuring intervention period for analysis](resources/images/image_p.png)

![Selecting period type for intervention configuration](resources/images/image_t.png)

### Legend Configurations

The administrative user can set legend for each indicator in every intervention to show low, medium and high bands with their cut-off points. An administrator can set colors for each band for visualization. Currently the BNA App uses three classes of colors to present indicator performance as per defined cut-off points. Red shows low performance, with yellow and green showing medium and good performance respectively. To manage the Legend, the administrator must can legend label and colour

![Managing Legends for Indicators in the BNA App](resources/images/image_l1.png)

![Adding color classes and  setting cut-off points in Legends management in BNA App ](resources/images/image_l2.png)

![Modifications made on the legend set management will require the  administrator to save the changes ](resources/images/image_l3.png)

> **NOTE:**
> For any changes made, administrative user must click update button displayed in the working window and save changes for persistence, or just close the message in case of rejecting the changes

### Determinants members management

For each determinant (Commodities, Human resources, Geographic accessibility, Initial utilization and Continuous utilization) up to three members (indicators or functions) can be selected for analysis.

![Accessing option for adding an indicator for the determinants](resources/images/image_d1.png)


![Selecting members (indicators or functions) for each determinant](resources/images/image_d2.png)

After selecting the member, the administrator will get options for further configuration of the member selected which includes defining display label and setting up minimum and maximum values for sub level analysis.

![Defining member display label and minimum and maximum values for sub level analysis](resources/images/image_d3.png)

To save changes made, scroll to the bottom of the configuration screen and click Update

![Saving changes after configuring options for selected member of the determinant](resources/images/image_d4.png)

To add another member (maximum allowable is three) to the same determinant click on the + as shown on figure 3.2.3-E below

![Adding another member to the determinant or deselecting added members](resources/images/image_d5.png)

### Sharing interventions configuration settings

The defined interventions can be shared and made accessible to multiple users within the system. To share the intervention settings click on Share with option and define people or groups you want to share the configuration with. Only people or groups who will be selected will have access to the configured intervention

![Accessing interventions sharing options](resources/images/image_s1.png)

![Selecting users or user groups and assigning access privileges for each shared intervention](resources/images/image_s2.png)

### Deleting interventions configuration

To delete created interventions configuration click on delete icon and follow deletion steps

![Click on delete icon to delete configured intervention](resources/images/image_s3.png)

![Click on DELETE button to confirm deletion or CANCEL to reject deletion](resources/images/image_s4.png)
