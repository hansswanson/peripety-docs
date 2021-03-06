# Rack and Device Import

## Rack

Navigate to the rack tab of the import helper spreadsheet.

![Rack List](../img/import/rack_list.png)

For each rack add the required information:

* site: Which site the racks are in.
* width: Rail-to-rail width (in inches). If unknown, put 19.
* u_height: Height in rack units. If unknown, put 42. Check the device tab and see what the highest occupied ru of any rack. If that value is larger than 42 and set that as the height for all racks.

Copy the rack tab into a new excel spreadsheet and save it as a csv file.

![Rack CSV](../img/import/rack_csv_1.png)

![Rack CSV](../img/import/rack_csv_2.png)

Navigate to the rack import tab of Peripety

![Rack Import Tab](../img/import/rack_import_tab.png)

Open the csv file with notepad or a text editor of your choice, copy it into the rack import page on Peripety, and Select the import button.

![Rack Import](../img/import/rack_import_1.png)

![Rack Import](../img/import/rack_import_2.png)

## Device

Navigate to the device tab of the import helper spreadsheet.

![Device List](../img/import/device_list.png)

For each Device add the required information:

* site: Which site the devices are in.
* status: Operational status. If unknown, put active.
* event: Move event. If unknown, put followup.

For any information that does not belong in any of the other fields that is important to capture in an audit, like devices mounted in strange orientations, make note of it in the comments field.

If you are dealing with a large data set, it is recommended that you break the data into smaller chunks before going through the import process, importing each chunk individually. Breaking the devices up by manufacturer is a good way to go about this.

Copy the Device tab into a new excel spreadsheet.

![Device CSV](../img/import/device_csv_1.png)

Remove the verbose headers in the second row.

![Device Delete](../img/import/device_delete.png)

Save the data as a csv file.

![Device CSV](../img/import/device_csv_2.png)

Navigate to the device import tab of Peripety

![Device Import Tab](../img/import/device_import_tab.png)

Open the csv file with notepad or a text editor of your choice, copy it into the device import page on Peripety, and select the import button.

![Device Import](../img/import/device_import_1.png)

![Device Import](../img/import/device_import_2.png)
