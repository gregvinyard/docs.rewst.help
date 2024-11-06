# Troubleshooting Halo Integration Setup

## Customers are Not Showing Up When Refreshing Options

If you are running into an issue where Customers are not showing when refreshing options, this is due to an issue with permissions. Make sure to check that both the User and API user have the following permissions, at minimum:&#x20;

* View Customers
* View Support Tickets
* Add Time Entries
* Create Support Tickets

{% hint style="danger" %}
You may need to uninstall and reinstall the halo integration for the new permissions to take place.&#x20;
{% endhint %}

## Boards and Teams are Not Visible In Configure Organizational Variable Form

If you can't see boards or teams in the configure organizational variable form, this is due to incorrect permissions. In order to resolve this issue, you will need to add the API User to the teams that you want to see in the form.&#x20;

## Email, Name, Department, etc is Missing or CAB ID is Invalid

If you run into an issue where the Email, Name, Department, or other information is missing or you see that the CAB ID is either invalid or mandatory, this is due to custom fields used in creating tickets. In order to use these custom ticket fields, you have a couple of options:

* The Custom Field IDs need to be added as an organization variable
* The Custom Field should not be marked as mandatory

