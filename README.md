<h1>Detection as Code</h1>

<h2>Automated Dashboard - View by Subject</h2>

<h3>MITRE ATT&CK</h3>

- [T1566 - Phishing](https://attack.mitre.org/techniques/T1566/)

<h3>Instructions</h3>

- <b>Line 7</b>
    - Contains the [parameter](https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-parameters) named <i>Subject-Line</i> that's used to collect input from the incident.

- <b>Line 8</b>
    - Needs to contain the proper TenantID of the company you work for, that set of characters is a placeholder.

<p>This is a KQL to add to a Sentinel Workbook to visualize email security gateway logs by a given subject line.</p>
<p>Of course, you can use an easier version to simply search emails by subject as this query is too verbose for simply hunting or research purposes. This Sentinel dashboard will display a set of information about a given incident. You can create a playbook to generate this dashboard. This is the subject section of the dashboard.</p>
