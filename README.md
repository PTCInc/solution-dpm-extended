# Disclaimer

To broaden collaboration and facilitate the adoption and expansion of customer solutions, PTC is sharing several field-developed IoT components. 

These artifacts are built using ThingWorx best practices, including the Building Block structure where appropriate, and are available to PTC Customers, Partners, and Customer Success for incorporation and enhancement as needed for specific use cases.

Please note, these components are not covered by PTC Technical Support and are not subject to any Technical Support Service Level Agreements (SLAs). 

However, PTC Customer Success teams and resources will, on a best-effort basis:

* Maintain and manage functionality across ThingWorx platform version releases.
* Actively address reported bugs.
* Continue to enhance functionality opportunistically and by request where possible.

ThingWorx subscription users can continue to log technical support tickets. ThingWorx Platform Technical Support will assist in isolating root causes and addressing platform-related product issues through standard ThingWorx platform maintenance. 

If the issue pertains to this specific component offered via PTC GitHub, PTC Support will direct inquiries to the appropriate internal PTC teams for further assistance.

These shared components are provided "as is," without any warranty, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

# Overview

DPM Extended contains a group of customizations that solve common problems found across multiple customers. The following list details each customization:

* Multi-Machine Management (MMM): A customization that allows for data entry at every work unit as well as handling multiple pacemakers working in parallel. Use this solution to:
  * Collect data at every work unit both manually and using automation
  *	Mark multiple work units as pacemakers working in parallel
    
* Job Order Steps: A customization that allows for individual step tracking within each work unit

* Status Timeline Chart: A customization that displays a timeline of the status of the machine on the Production Dashboard
  * Used either with Automation or with the Manual Availability Events customization

* Manual Availability Events: A customization that allows the operator to enter specific start and end times for loss events
  * Used in conjunction with the Status Timeline Chart customization

* Editable Automation Events: A customization that allows the user to modify automation events to change the reason, comment, and work unit causing event

* Enable/Disable Metrics: A customization that allows the user to enable or disable certain metrics so that they do not appear in the Scorecard List

* New Custom Metrics: A customization that adds many new metrics to the Scorecard view including APQ and Loss Percentages

* New Custom Reports: A customization that adds new reports to DPM including the Shift Summary, Summary Dashboard, and Time Loss Pareto reports


All content is provided as "Releases" and is not directly in the Git Repo.  Cloning this Git Repo will not provide any content.

# License

## PTC Proprietary Freeware License

I accept the PTC End User License Agreement (https://www.ptc.com/en/documents/legal-agreements/on-premise-license-agreements) and agree that any software downloaded/utilized will be in compliance with that Agreement.  However, despite anything to the contrary in the License Agreement, I agree as follows:

I acknowledge that I am not entitled to support assistance with respect to the software, and PTC will have no obligation to maintain the software or provide bug fixes or security patches or new releases.

The software is provided “As Is” and with no warranty, indemnitees or guarantees whatsoever, and PTC will have no liability whatsoever with respect to the software, including with respect to any intellectual property infringement claims or security incidents or data loss.
