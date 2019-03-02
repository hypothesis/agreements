# Partner Service Level Agreement

## What We Provide (Service Scope)

Hypothesis provides several services that work in concert to provide a means for annotating the web. These include the following:

*   API: Application Programming Interfaces used to interact with our backend systems (e.g., telling the server to create a new annotation).
*   Via: Proxy service used to inject the Hypothesis client into a web page.
*   Sidebar/client: User interface used to add annotations to web pages and PDFs.
*   Browser Extensions: Software that extends the native browser experience to enable annotation through the Hypothesis Sidebar.

All Hypothesis user data is currently stored on servers in the United States.

## Service Availability

Hypothesis will use commercially reasonable efforts to make our services available with the applicable monthly service availability percentage (as defined below) during any calendar month.

Monthly service availability percentage (sometimes referred to as “uptime”) is defined as follows:

> (maximum available minutes − minutes of unavailability) ∕ maximum available minutes

*   99.9% monthly service availability for business-critical services (e.g., the ability to annotate a web page)
*   99% monthly service availability for non-business-critical services (e.g., real-time updates)

For example, 99.9% service availability equates to no more than 43 minutes of unavailability in a 30-day month.

## Support

### Responding to Outages

Partners can file support requests in the [Help section of our website](https://web.hypothes.is/help/) or email them to [support@hypothes.is](mailto:support@hypothes.is). Partners can expect written incident reports for severe incidents (SEV1 and SEV2, as defined below) that result in service unavailability of 15 minutes or more.

Hypothesis defines our core business hours as 8:00am to 4:00pm USA Eastern Time, Monday through Friday. Non-core business hours are hours that fall outside those ranges plus Hypothesis-observed holidays.

#### Hypothesis-observed Holidays

1.  New Year’s Day: 1 January
2.  Martin Luther King, Jr. Day (USA): third Monday in January
3.  Presidents’ Day (USA): third Monday in February
4.  Good Friday: Friday before Easter
5.  International Workers’ Day aka Labour Day (EU): 1 May
6.  Europe Day (EU): 9 May
7.  Memorial Day (USA): last Monday in May
8.  Independence Day (USA): 4 July
9.  Assumption Day: 15 August
10.  Labor Day (USA): first Monday in September
11.  German Unity Day: 3 October
12.  All Saints’ Day: 1 November
13.  All Soul’s Day: 2 November
14.  Thanksgiving Day (USA): fourth Thursday in November
15.  Christmas Day: 25 December
16.  Christmas Week: 26–30 December
17.  New Year’s Eve: 31 December

### Severity Levels

How we respond to availability problems depends on the severity of the incident. The following is a summary of the severity levels we use to classify incidents:

*   SEV1: A severity 1 incident is one in which business-critical parts of our system are unavailable or substantially degraded for large numbers of users.
*   SEV2: A severity 2 incident is one in which any functionality is unavailable or substantially degraded for even a small number of users.
*   SEV3: A severity 3 incident is one in which the product is not functioning as intended, but the malfunction does not materially impact the ability of large numbers of users to use the product.
*   SEV4: A severity 4 incident is one in which the product is operating in a degraded state, but without user impact. Typically this will be a redundant component failure or the failure of a system off the critical path such as a monitoring or logging component.

### Response Times

The amount of time partners can expect Hypothesis to take to respond to unavailability incidents is a factor of the severity of the incident and whether the incident occurs during core business hours.

#### Partners

Partners can expect the following maximum response times to unavailability incidents:

<table class="h-blog">

<tbody>

<tr>

<th rowspan="2">Severity Level</th>

<th colspan="2">Initial Contact</th>

<th colspan="2">Status Update</th>

</tr>

<tr>

<th>Business Hours</th>

<th>Non-business Hours</th>

<th>Business Hours</th>

<th>Non-business Hours</th>

</tr>

<tr>

<td>SEV1</td>

<td>1 hour</td>

<td>4 hours</td>

<td>4 hours</td>

<td>8 hours</td>

</tr>

<tr>

<td>SEV2</td>

<td>2 hours</td>

<td>8 hours</td>

<td>12 hours</td>

<td>24 hours</td>

</tr>

<tr>

<td>SEV3 & SEV4</td>

<td>24 hours</td>

<td>24 hours</td>

<td>48 hours</td>

<td>48 hours</td>

</tr>

</tbody>

</table>

Initial contact is defined as the first response by a Hypothesis support engineer or manager after an incident has been brought to our attention via filing a support ticket. Partners can expect a first status update within the timeframe specified above with subsequent updates at that interval until the incident is resolved.

Hypothesis will use reasonable efforts to resolve all service requests as soon as possible.

#### End Users

End users can expect the following maximum response times to support requests:

<table class="h-blog">

<tbody>

<tr>

<th>Contacts</th>

<th>Business Hours</th>

<th>Non-business Hours</th>

</tr>

<tr>

<td>Initial contact with the end user</td>

<td>12 hours</td>

<td>48 hours</td>

</tr>

<tr>

<td>Second contact with the end user</td>

<td>24 hours</td>

<td>60 hours</td>

</tr>

</tbody>

</table>

### Monitoring and Reporting of Service Availability

Partners will be subscribed to [outages@list.hypothes.is](mailto:outages@list.hypothes.is) to receive monthly reports on service availability percentages as well as notices of planned outages and reports on unplanned outages.

## Limitations

This SLA does not apply to any availability issues:

*   Due to factors outside our reasonable control (for example, natural disaster, war, acts of terrorism, riots, government action, or a network or device failure external to our data centers, including at your site or between your site and our data center);
*   That result from the use of services, hardware, or software not provided by us, including, but not limited to, issues resulting from inadequate bandwidth or related to third-party software or services;
*   Caused by your use of Hypothesis after we advised you to modify your usage, if you did not modify your use as advised;
*   During or with respect to preview, pre-release, or beta versions of Hypothesis (as determined by us);
*   That result from your unauthorized action or lack of action when required, or from your employees, agents, contractors, or vendors, or anyone gaining access to our network by means of your passwords or equipment, or otherwise resulting from your failure to follow appropriate security practices;
*   That result from your failure to adhere to any required configurations, use supported platforms, follow any policies for acceptable use, or your use of Hypothesis in a manner inconsistent with our features and functionality (for example, attempts to perform operations that are not supported) or inconsistent with our published guidance;
*   That result from faulty input, instructions, or arguments (for example, requests to access files that do not exist); or,
*   That result from your attempts to perform operations that exceed prescribed quotas or that resulted from our throttling of suspected abusive behavior.

## Questions About This Service Level Agreement

Email: [support@hypothes.is](mailto:support@hypothes.is)

## **Versions**

1.  **Current:** 1 March 2019
