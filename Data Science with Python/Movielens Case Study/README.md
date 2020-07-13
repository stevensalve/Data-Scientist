<h1>Data Scientist Assignments </h1>
<h3>Data Science with Python</h3>
 <b>Assignments -  Movielens Case Study</b><br>

 <div _ngcontent-hif-c48="" class="project-description sl-ck-editor"><p _ngcontent-hif-c48="">DESCRIPTION</p><div _ngcontent-hif-c48=""><p><strong>Background of Problem Statement :</strong></p>

<p>The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Members of the GroupLens Research Project are involved in many research projects related to the fields of information filtering, collaborative filtering, and recommender systems. The project is led by professors John Riedl and Joseph Konstan. The project began to explore automated collaborative filtering in 1992 but is most well known for its worldwide trial of an automated collaborative filtering system for Usenet news in 1996. Since then the project has expanded its scope to research overall information by filtering solutions, integrating into content-based methods, as well as, improving current collaborative filtering technology.</p>

<p><strong>Problem Objective :</strong></p>

<p>Here, we ask you to perform the analysis using the Exploratory Data Analysis technique. You need to find features affecting the ratings of any particular movie and build a model to predict the movie ratings.</p>

<p><strong>Domain</strong>: Entertainment</p>

<p><strong>Analysis Tasks to be performed:</strong></p>

<ul>
	<li>Import the three datasets</li>
	<li>Create a new dataset [Master_Data] with the following columns MovieID Title UserID Age Gender Occupation Rating. (Hint: (i) Merge two tables at a time. (ii) Merge the tables using two primary keys MovieID &amp; UserId)</li>
	<li>Explore the datasets using visual representations (graphs or tables), also include your comments on the following:</li>
</ul>

<ol style="margin-left:40px">
	<li>User Age Distribution</li>
	<li>User rating of the movie “Toy Story”</li>
	<li>Top 25 movies by viewership rating</li>
	<li>Find the ratings for all the movies reviewed by for a particular user of user id = 2696</li>
</ol>

<ul>
	<li>Feature Engineering:</li>
</ul>

<p>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Use column genres:</p>

<ol style="margin-left:40px">
	<li>Find out all the unique genres (Hint: split the data in column genre making a list and then process the data to find out only the unique categories of genres)</li>
	<li>Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre.&nbsp;</li>
	<li>Determine the features affecting the ratings of any particular movie.</li>
	<li>Develop an appropriate model to predict the movie ratings</li>
</ol>

<p><strong>Dataset Description :</strong></p>

<p>These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.</p>

<p><strong>Ratings.dat</strong><br>
&nbsp;&nbsp; &nbsp;Format - UserID::MovieID::Rating::Timestamp</p>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td><strong>Field</strong></td>
			<td><strong>Description</strong></td>
		</tr>
		<tr>
			<td>UserID</td>
			<td>Unique identification for each user</td>
		</tr>
		<tr>
			<td>MovieID</td>
			<td>Unique identification for each movie</td>
		</tr>
		<tr>
			<td>Rating</td>
			<td>User rating for each movie</td>
		</tr>
		<tr>
			<td>Timestamp</td>
			<td>Timestamp generated while adding user review</td>
		</tr>
	</tbody>
</table>
</div>

<ul>
	<li>UserIDs range between 1 and 6040&nbsp;</li>
	<li>The MovieIDs range between 1 and 3952</li>
	<li>Ratings are made on a 5-star scale (whole-star ratings only)</li>
	<li>A timestamp is represented in seconds since the epoch is returned by time(2)</li>
	<li>Each user has at least 20 ratings
	<p>&nbsp;</p>
	</li>
</ul>

<p><strong>Users.dat</strong><br>
Format - &nbsp;UserID::Gender::Age::Occupation::Zip-code</p>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td>Field</td>
			<td>Description</td>
		</tr>
		<tr>
			<td>UserID</td>
			<td>Unique identification for each user</td>
		</tr>
		<tr>
			<td>Genere</td>
			<td>Category of each movie</td>
		</tr>
		<tr>
			<td>Age</td>
			<td>User’s age</td>
		</tr>
		<tr>
			<td>Occupation</td>
			<td>User’s Occupation</td>
		</tr>
		<tr>
			<td>Zip-code</td>
			<td>Zip Code for the user’s location</td>
		</tr>
	</tbody>
</table>
</div>

<p>All demographic information is provided voluntarily by the users and is not checked for accuracy. Only users who have provided demographic information are included in this data set.</p>

<ul>
	<li>Gender is denoted by an "M" for male and "F" for female</li>
	<li>Age is chosen from the following ranges:</li>
</ul>

<p>&nbsp;</p>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td><strong>Value</strong></td>
			<td><strong>Description</strong></td>
		</tr>
		<tr>
			<td>1</td>
			<td>"Under 18"</td>
		</tr>
		<tr>
			<td>18</td>
			<td>"18-24"</td>
		</tr>
		<tr>
			<td>25</td>
			<td>"25-34"</td>
		</tr>
		<tr>
			<td>35</td>
			<td>"35-44"</td>
		</tr>
		<tr>
			<td>45</td>
			<td>"45-49"</td>
		</tr>
		<tr>
			<td>50</td>
			<td>"50-55"</td>
		</tr>
		<tr>
			<td>56</td>
			<td>"56+"</td>
		</tr>
	</tbody>
</table>
</div>

<p>&nbsp;</p>

<ul>
	<li>Occupation is chosen from the following choices:</li>
</ul>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td><strong>Value</strong><br>
			&nbsp;</td>
			<td><strong>Description</strong></td>
		</tr>
		<tr>
			<td>0</td>
			<td>"other" or not specified</td>
		</tr>
		<tr>
			<td>1</td>
			<td>"academic/educator"</td>
		</tr>
		<tr>
			<td>2</td>
			<td>"artist”</td>
		</tr>
		<tr>
			<td>3</td>
			<td>"clerical/admin"</td>
		</tr>
		<tr>
			<td>4</td>
			<td>"college/grad student"</td>
		</tr>
		<tr>
			<td>5</td>
			<td>"customer service"</td>
		</tr>
		<tr>
			<td>6</td>
			<td>"doctor/health care"</td>
		</tr>
		<tr>
			<td>7</td>
			<td>"executive/managerial"</td>
		</tr>
		<tr>
			<td>8</td>
			<td>"farmer"</td>
		</tr>
		<tr>
			<td>9</td>
			<td>"homemaker"</td>
		</tr>
		<tr>
			<td>10</td>
			<td>"K-12 student"</td>
		</tr>
		<tr>
			<td>11</td>
			<td>"lawyer"</td>
		</tr>
		<tr>
			<td>12</td>
			<td>"programmer"</td>
		</tr>
		<tr>
			<td>13</td>
			<td>"retired"</td>
		</tr>
		<tr>
			<td>14</td>
			<td>&nbsp;"sales/marketing"</td>
		</tr>
		<tr>
			<td>15</td>
			<td>"scientist"</td>
		</tr>
		<tr>
			<td>16</td>
			<td>&nbsp;"self-employed"</td>
		</tr>
		<tr>
			<td>17</td>
			<td>"technician/engineer"</td>
		</tr>
		<tr>
			<td>18</td>
			<td>"tradesman/craftsman"</td>
		</tr>
		<tr>
			<td>19</td>
			<td>"unemployed"</td>
		</tr>
		<tr>
			<td>20</td>
			<td>"writer”</td>
		</tr>
	</tbody>
</table>
</div>

<p><br>
<strong>Movies.dat</strong><br>
Format - MovieID::Title::Genres</p>

<div>
<table class="table" style="width:100%">
	<tbody>
		<tr>
			<td>Field</td>
			<td>Description</td>
		</tr>
		<tr>
			<td>MovieID</td>
			<td>Unique identification for each movie</td>
		</tr>
		<tr>
			<td>Title</td>
			<td>A title&nbsp;for each movie</td>
		</tr>
		<tr>
			<td>Genres</td>
			<td>Category of each movie</td>
		</tr>
	</tbody>
</table>
</div>

<p>&nbsp;</p>

<ul>
	<li>&nbsp;Titles are identical to titles provided by the IMDB (including year of release)</li>
</ul>

<p>&nbsp;</p>

<ul>
	<li>Genres are pipe-separated and are selected from the following genres:</li>
</ul>

<ol style="margin-left:40px">
	<li>Action</li>
	<li>Adventure</li>
	<li>Animation</li>
	<li>Children's</li>
	<li>Comedy</li>
	<li>Crime</li>
	<li>Documentary</li>
	<li>Drama</li>
	<li>Fantasy</li>
	<li>Film-Noir</li>
	<li>Horror</li>
	<li>Musical</li>
	<li>Mystery</li>
	<li>Romance</li>
	<li>Sci-Fi</li>
	<li>Thriller</li>
	<li>War</li>
	<li>Western</li>
</ol>

<ul>
	<li>Some MovieIDs do not correspond to a movie due to accidental duplicate entries and/or test entries</li>
	<li>Movies are mostly entered by hand, so errors and inconsistencies may exist</li>
</ul>

&nbsp;</p>
</div></div>
