<h1>Data Scientist Assignments </h1>
<h3>Data Science with Python</h3>
 <b>Assignments - Customer Service Requests Analysis</b><br

 <div _ngcontent-hif-c48="" class="project-description sl-ck-editor"><p _ngcontent-hif-c48="">DESCRIPTION</p><div _ngcontent-hif-c48=""><p><strong>Background of Problem Statement :</strong></p>

<p>NYC 311's mission is to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests are received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responds to the request, addresses it, and then closes it.</p>

<p><strong>Problem Objective :</strong></p>

<p>Perform a service request data analysis of New York City 311 calls. You will focus on the data wrangling techniques to understand the pattern in the data and also visualize the major complaint types.<br>
Domain: Customer Service</p>

<p><strong>Analysis Tasks to be performed:</strong></p>

<p>(Perform a service request data analysis of New York City 311 calls)&nbsp;</p>

<ol>
	<li>Import a 311 NYC service request.</li>
	<li>Read or convert the columns ‘Created Date’ and Closed Date’ to datetime datatype and create a new column ‘Request_Closing_Time’ as the time elapsed between request creation and request closing. (Hint: Explore the package/module datetime)</li>
	<li>Provide major insights/patterns that you can offer in a visual format (graphs or tables); at least 4 major conclusions that you can come up with after generic data mining.</li>
	<li>Order the complaint types based on the average ‘Request_Closing_Time’, grouping them for different locations.</li>
	<li>Perform a statistical test for the following:</li>
</ol>

<p>Please note: For the below statements you need to state the Null and Alternate and then provide a statistical test to accept or reject the Null Hypothesis along with the corresponding ‘p-value’.</p>

<ul>
	<li>Whether the average response time across complaint types is similar or not (overall)</li>
	<li>Are the type of complaint or service requested and location related?</li>
</ul>

<p>Dataset Description :</p>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td><strong>Field</strong></td>
			<td><strong>Description</strong></td>
		</tr>
		<tr>
			<td>Unique Key</td>
			<td>(Plain text) - Unique identifier for the complaints</td>
		</tr>
		<tr>
			<td>Created Date</td>
			<td>(Date and Time) - The date and time on which the complaint is raised</td>
		</tr>
		<tr>
			<td>Closed Date</td>
			<td>(Date and Time) &nbsp;- The date and time on which the complaint is closed</td>
		</tr>
		<tr>
			<td>Agency</td>
			<td>(Plain text) - Agency code</td>
		</tr>
		<tr>
			<td>Agency Name</td>
			<td>(Plain text) - Name of the agency</td>
		</tr>
		<tr>
			<td>Complaint Type</td>
			<td>(Plain text) - Type of the complaint</td>
		</tr>
		<tr>
			<td>Descriptor</td>
			<td>(Plain text) - Complaint type label (Heating - Heat, Traffic Signal Condition - Controller)</td>
		</tr>
		<tr>
			<td>Location Type</td>
			<td>(Plain text) - Type of the location (Residential, Restaurant, Bakery, etc)</td>
		</tr>
		<tr>
			<td>Incident Zip</td>
			<td>(Plain text) - Zip code for the location</td>
		</tr>
		<tr>
			<td>Incident Address</td>
			<td>(Plain text) - Address of the location</td>
		</tr>
		<tr>
			<td>Street Name</td>
			<td>(Plain text) - Name of the street</td>
		</tr>
		<tr>
			<td>Cross Street 1</td>
			<td>(Plain text) - Detail of cross street</td>
		</tr>
		<tr>
			<td>Cross Street 2</td>
			<td>(Plain text) - Detail of another cross street</td>
		</tr>
		<tr>
			<td>Intersection Street 1</td>
			<td>(Plain text) - Detail of intersection street if any</td>
		</tr>
		<tr>
			<td>Intersection Street 2</td>
			<td>(Plain text) - Detail of another intersection street if any</td>
		</tr>
		<tr>
			<td>Address Type</td>
			<td>(Plain text) - Categorical (Address or Intersection)</td>
		</tr>
		<tr>
			<td>City</td>
			<td>(Plain text) - City for the location</td>
		</tr>
		<tr>
			<td>Landmark</td>
			<td>(Plain text) - Empty field</td>
		</tr>
		<tr>
			<td>Facility Type</td>
			<td>(Plain text) - N/A</td>
		</tr>
		<tr>
			<td>Status</td>
			<td>(Plain text) - Categorical (Closed or Pending)</td>
		</tr>
		<tr>
			<td>Due Date</td>
			<td>(Date and Time) - Date and time for the pending complaints</td>
		</tr>
		<tr>
			<td>Resolution Action Updated Date</td>
			<td>(Date and Time) - Date and time when the resolution was provided</td>
		</tr>
		<tr>
			<td>Community Board</td>
			<td>(Plain text) - Categorical field (specifies the community board with its code)</td>
		</tr>
		<tr>
			<td>Borough</td>
			<td>(Plain text) - Categorical field (specifies the community board)</td>
		</tr>
		<tr>
			<td>X Coordinate</td>
			<td>(State Plane) (Number)</td>
		</tr>
		<tr>
			<td>Y Coordinate</td>
			<td>(State Plane) (Number)</td>
		</tr>
		<tr>
			<td>Park Facility Name</td>
			<td>(Plain text) - Unspecified</td>
		</tr>
		<tr>
			<td>Park Borough</td>
			<td>(Plain text) - Categorical (Unspecified, Queens, Brooklyn etc)</td>
		</tr>
		<tr>
			<td>School Name</td>
			<td>(Plain text) - Unspecified</td>
		</tr>
		<tr>
			<td>School Number</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Region</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Code</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Phone Number</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Address</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School City</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School State</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Zip</td>
			<td>(Plain text) &nbsp;- Unspecified</td>
		</tr>
		<tr>
			<td>School Not Found</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>School or Citywide Complaint</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Vehicle Type</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Taxi Company Borough</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Taxi Pick Up Location</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Bridge Highway Name</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Bridge Highway Direction</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Road Ramp</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Bridge Highway Segment</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Garage Lot Name</td>
			<td>(Plain text) &nbsp;- Empty Field<br>
			&nbsp;</td>
		</tr>
		<tr>
			<td>Ferry Direction</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Ferry Terminal Name</td>
			<td>(Plain text) &nbsp;- Empty Field</td>
		</tr>
		<tr>
			<td>Latitude</td>
			<td>(Number) - Latitude of the location</td>
		</tr>
		<tr>
			<td>Longitude</td>
			<td>(Number) - Longitude of the location</td>
		</tr>
		<tr>
			<td>Location</td>
			<td>(Location) - Coordinates (Latitude, Longitude)</td>
		</tr>
	</tbody>
</table>
</div>
</div></div>
