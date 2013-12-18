### Inbound Properties

[PROFILE FIELDS](http://developer.linkedin.com/documents/profile-fields#profile)

**basic profile fields(r_basicprofile)**
<table>
	<tr>
		<th>Field name </th>
		<th>Object Builder mapping in the connector</th>
	</tr>
	<tr>
		<td>id</td>
		<td>ID</td>
		
	</tr>
	<tr>
		<td>first-name</td>
		<td>FIRST_NAME</td>
		
	</tr>
	<tr>
		<td>last-name</td>
		<td>LAST_NAME</td>
		
	</tr>
    <tr>
		<td>headline</td>
		<td>HEADLINE</td>
		
	</tr>
	<tr>
		<td>location</td>
		<td>LOCATION</td>
		
	</tr>
	<tr>
		<td>location:(name)</td>
		<td>LOCATION_NAME</td>
		
	</tr>
	<tr>
		<td>location:(country:(code))</td>
		<td>LOCATION_COUNTRY_CODE</td>
		
	</tr>
	<tr>
		<td>industry</td>
		<td>INDUSTRY</td>
		
	</tr>	<tr>
		<td>distance</td>
		<td>DISTANCE</td>
		
	</tr>	<tr>
		<td>relation-to-viewer:(distance)</td>
		<td>RELATION_TO_VIEWER_DISTANCE</td>
		
	</tr>
	<tr>
		<td>current-share</td>
		<td>CURRENT_SHARE</td>
		
	</tr>	<tr>
		<td>connections</td>
		<td>CONNECTIONS</td>
		
	</tr>	<tr>
		<td>num-connections</td>
		<td>NUM_CONNECTIONS</td>
		
	</tr>	<tr>
		<td>num-connections-capped</td>
		<td>NUM_CONNECTIONS_CAPPED</td>
		
	</tr>	<tr>
		<td>summary</td>
		<td>SUMMARY</td>
		
	</tr>	<tr>
		<td>specialties</td>
		<td>SPECIALTIES</td>
		
	</tr>	<tr>
		<td>positions</td>
		<td>POSITIONS</td>
		
	</tr>	<tr>
		<td>picture-url</td>
		<td>PICTURE_URL</td>
		
	</tr>	<tr>
		<td>site-standard-profile-request</td>
		<td>SITE_STANDARD_PROFILE_REQUEST</td>
		
	</tr>	<tr>
		<td>api-standard-profile-request:(url)</td>
		<td>SITE_STANDARD_PROFILE_REQUEST_URL</td>
		
	</tr>
	<tr>
		<td>public-profile-url</td>
		<td>PUBLIC_PROFILE_URL</td>
		
	</tr>

</table>

**Full Profile Fields(r_fullprofile)**

<table>
<tr>
<td>
proposal-comments
</td>
<td>
PROPOSAL_COMMENTS
</td>
</tr>
<tr>
<td>
associations
</td>
<td>
ASSOCIATIONS
</td>
</tr>
<tr>
<td>
honors
</td>
<td>
HONORS
</td>
</tr>
<tr>
<td>
interests
</td>
<td>
INTERESTS
</td>
</tr><tr>
<td>
publications
</td>
<td>
PUBLICATIONS
</td>
</tr><tr>
<td>
patents
</td>
<td>
PATENTS
</td>
</tr><tr>
<td>
languages
</td>
<td>
LANGUAGES
</td>
</tr><tr>
<td>
skills
</td>
<td>
SKILLS
</td>
</tr><tr>
<td>
certifications
</td>
<td>
CERTIFICATIONS
</td>
</tr><tr>
<td>
educations
</td>
<td>
EDUCATIONS
</td>
</tr><tr>
<td>
three-current-positions
</td>
<td>
THREE_CURRENT_POSITIONS
</td>
</tr><tr>
<td>
three-past-positions
</td>
<td>
THREE_PAST_POSITIONS
</td>
</tr><tr>
<td>
num-recommenders
</td>
<td>
NUM_RECOMMENDERS
</td>
</tr><tr>
<td>
recommendations-received
</td>
<td>
RECOMMENDATIONS_RECEIVED
</td>
</tr><tr>
<td>
date-of-birth
</td>
<td>
DATE_OF_BIRTH
</td>
</tr><tr>
<td>
member-url-resources
</td>
<td>
MEMBER_URL_RESOURCES
</td>
</tr><tr>
<td>
member-url-resources
</td>
<td>
MEMBER_URL_RESOURCES
</td>
</tr>
<tr>
<td>
member-url-resources:(url)
</td>
<td>
MEMBER_URL_URL
</td>
</tr>
<tr>
<td>
member-url-resources:(name)
</td>
<td>
MEMBER_URL_NAME
</td>
</tr>
</table>

[GROUP FIELD](http://developer.linkedin.com/documents/groups-fields)

<table>

	<th>Field name </th>
		<th>Object Builder mapping in the connector</th>
	</tr>
	<tr>
		<td>id</td>
		<td>ID</td>
		
	</tr>
	<tr>
		<td>name</td>
		<td>NAME</td>
		
	</tr>
	<tr>
		<td>short-description</td>
		<td>SHORT_DESCRIPTION</td>
		
	</tr>
	<tr>
		<td>description</td>
		<td>DESCRIPTION</td>
		
	</tr>
	<tr>
		<td>relation-to-viewer:(membership-state)</td>
		<td>RELATION_TO_VIEWER_MEMBERSHIP_STATE</td>
		
	</tr>
	<tr>
		<td>relation-to-viewer:(available-actions)</td>
		<td>RELATION_TO_VIEWER_AVAILABLE_ACTIONS</td>
		
	</tr>
	<tr>
		<td>posts</td>
		<td>POSTS</td>
		
	</tr>
	<tr>
		<td>counts-by-category</td>
		<td>COUNTS_BY_CATEGORY</td>
		
	</tr>
	<tr>
		<td>is-open-to-non-members</td>
		<td>IS_OPEN_TO_NON_MEMBERS</td>
		
	</tr>	<tr>
		<td>category</td>
		<td>CATEGORY</td>
		
	</tr>	<tr>
		<td>website-url</td>
		<td>WEBSITE-URL</td>
		
	</tr>
	<tr>
		<td>site-group-url</td>
		<td>SITE-GROUP-URL</td>
		
	</tr>	<tr>
		<td>locale</td>
		<td>LOCALE</td>
		
	</tr>
	<tr>
		<td>location:(country)</td>
		<td>LOCATION_COUNTRY</td>
		
	</tr>	<tr>
		<td>location:(postal-code)</td>
		<td>LOCATION_POSTAL_CODE</td>
		
	</tr>
	<tr>
		<td>allow-member-invites</td>
		<td>ALLOW_MEMBER_INVITES</td>
		
	</tr>
	<tr>
		<td>small-logo-url</td>
		<td>SMALL_LOGO_URL</td>
		
	</tr>
	<tr>
		<td>large-logo-url</td>
		<td>LARGE_LOGO_URL</td>
		
	</tr>

</table>

[POST FIELDS](http://developer.linkedin.com/documents/groups-fields)
<table>
<th>Field name </th>
<th>Object Builder mapping in the connector</th>
<tr>
<td>id</td>
<td>ID</td>
</tr>
<tr>
<td>type</td>
<td>TYPE</td>
</tr>
<tr>
<td>category</td>
<td>CATEGORY</td>
</tr>
<tr>
<td>creator</td>
<td>CREATOR</td>
</tr><tr>
<td>title</td>
<td>TITLE</td>
</tr>
<tr>
<td>sumamry</td>
<td>SUMMARY</td>
</tr>
<tr>
<td>creation-timestamp</td>
<td>CREATION_TIMESTAMP</td>
</tr><tr>
<td>relation-to-viewer:(is-following)</td>
<td>RELATION_TO_VIEWER_IS_FOLLOWING</td>
</tr>
<tr>
<td>relation-to-viewer:(is-liked)</td>
<td>RELATION_TO_VIEWER_IS_LIKED</td>
</tr>
</tr>
<tr>
<td>relation-to-viewer:(available-actions)</td>
<td>RELATION_TO_VIEWER_AVAILABLE_ACTIONS</td>
</tr>
</tr>
<tr>
<td>likes</td>
<td>LIKES</td>
</tr>
</tr>
<tr>
<td>comments</td>
<td>COMMENTS</td>
</tr>
</tr>
<tr>
<td>attachment</td>
<td>ATTACHMENT</td>
</tr>
</tr>
<tr>
<td>site-group-post-url</td>
<td>SITE_GROUP_POST_URL</td>
</tr>
</table>

[COMMENT FIELDS]()

<table>
<th>Field name </th>
<th>Object Builder mapping in the connector</th>
<tr>
<td>id</td>
<td>ID</td>
</tr>
<tr>
<td>text</td>
<td>TEXT</td>
</tr>
<tr>
<td>creator</td>
<td>CREATOR</td>
</tr>
<tr>
<td>creation-timestamp</td>
<td>CREATON-TIMESTAMP</td>
</tr><tr>
<td>relation-to-viewer:(available-actions)</td>
<td>RELATION_TO_VIEWER_AVAILABLE_ACTIONS</td>
</tr>

</table>

[GROUP MEMBERSHIP FIELDS](http://developer.linkedin.com/documents/groups-fields)

<table>
<th>Field name</th>
<th>Object Builder mapping in the connector</th>
<tr>
<td>person</td>
<td>PERSON</td>
</tr>
<tr>
<td>group:(id)</td>
<td>GROUP_ID</td>
</tr>
<tr>
<td>group:(name)</td>
<td>GROUP_NAME</td>
</tr><tr>
<td>membership-state</td>
<td>MEMBERSHIP_STATE</td>
</tr>
<tr>
<td>show-group-logo-in-profile</td>
<td>SHOW_GROUP_LOGO_IN_PROFILE</td>
</tr>
<tr>
<td>allow-messages-from-members</td>
<td>ALLOW_MESSAGES_FROM_MEMBERS</td>
</tr><tr>
<td>email-digest-frequency</td>
<td>EMAIL_DIGEST_FREQUENCY</td>
</tr>
<tr>
<td>email-for-every-new-post</td>
<td>EMAIL_FOR_EVERY_NEW_POST</td>
</tr>
<tr>
<td>posts</td>
<td>POSTS</td>
</tr>
</table>


[COMPANY FIELDS](http://developer.linkedin.com/documents/company-lookup-api-and-fields)

<style type="text/css">
	table.tableizer-table {
	border: 1px solid #CCC; font-family: Arial, Helvetica, sans-serif
	font-size: 12px;
} 
.tableizer-table td {
	padding: 4px;
	margin: 3px;
	border: 1px solid #ccc;
}

}
</style><table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Field name </th><th>Object Builder mapping in the connector</th></tr>
 <tr><td>id</td><td>ID</td></tr>
 <tr><td>name</td><td>NAME</td></tr>
 <tr><td>universal-name</td><td>UNIVERSAL\_NAME</td></tr>
 <tr><td>email-domains</td><td>EMAIL\_DOMAINS</td></tr>
 <tr><td>company-type</td><td>COMPANY\_TYPE</td></tr>
 <tr><td>ticker</td><td>TICKER</td></tr>
 <tr><td>website-url</td><td>WEBSITE\_URL</td></tr>
 <tr><td>industries</td><td>INDUSTRY</td></tr>
 <tr><td>status</td><td>STATUS</td></tr>
 <tr><td>logo-url</td><td>LOGO\_URL</td></tr>
 <tr><td>square-logo-ur</td><td>SQUARE\_LOGO\_URL</td></tr>
 <tr><td>blog-rss-url</td><td>BLOG\_RSS\_URL</td></tr>
 <tr><td>twitter-id</td><td>TWITTER\_ID</td></tr>
 <tr><td>employee-count-range</td><td>EMPLOYEE\_COUNT\_RANGE</td></tr>
 <tr><td>specialties</td><td>SPECIALTIES</td></tr>
 <tr><td>locations</td><td>LOCATIONS</td></tr>
 <tr><td>locations:(description)</td><td>LOCATIONS\_DESCRIPTION</td></tr>
 <tr><td>locations:(is-headquarters)</td><td>LOCATIONS\_IS\_HEADQUARTERS</td></tr>
 <tr><td>locations:(is-active)</td><td>LOCATIONS\_IS\_ACTIVE</td></tr>
 <tr><td>locations:(address)</td><td>LOCATIONS\_ADDRESS</td></tr>
 <tr><td>locations:(address:(street1))</td><td>LOCATIONS\_ADDRESS\_STREET1</td></tr>
 <tr><td>locations:(address:(street2))</td><td>LOCATIONS\_ADDRESS\_STREET2</td></tr>
 <tr><td>locations:(address:(city))</td><td>LOCATIONS\_ADDRESS\_CITY</td></tr>
 <tr><td>locations:(address:(state))</td><td>LOCATIONS\_ADDRESS\_STATE</td></tr>
 <tr><td>locations:(address:(postal-code))</td><td>LOCATIONS\_ADDRESS\_POSTAL\_CODE</td></tr>
 <tr><td>locations:(address:(country-code))</td><td>LOCATIONS\_ADDRESS\_COUNTRY\_CODE</td></tr>
 <tr><td>locations:(address:(region-code))</td><td>LOCATIONS\_ADDRESS\_REGION\_CODE</td></tr>
 <tr><td>locations:(contact-info)</td><td>LOCATIONS\_CONTACT\_INFO</td></tr>
 <tr><td>locations:(contact-info:(phone1))</td><td>LOCATIONS\_CONTACT\_INFO\_PHONE1</td></tr>
 <tr><td>locations:(contact-info:(phone2))</td><td>LOCATIONS\_CONTACT\_INFO\_PHONE2</td></tr>
 <tr><td>locations:(contact-info:(fax))</td><td>LOCATIONS\_CONTACT\_INFO\_FAX</td></tr>
 <tr><td>description</td><td>DESCRIPTION</td></tr>
 <tr><td>stock-exchange</td><td>STOCK\_EXCHANGE</td></tr>
 <tr><td>founded-year</td><td>FOUNDED\_YEAR</td></tr>
 <tr><td>end-year</td><td>END\_YEAR</td></tr>
 <tr><td>num-followers</td><td>NUM\_FOLLOWERS</td></tr>
</table>


[JOBS FIELDS](http://developer.linkedin.com/documents/job-lookup-api-and-fields)

<style type="text/css">
	table.tableizer-table {
	border: 1px solid #CCC; font-family: Arial, Helvetica, sans-serif
	font-size: 12px;
} 
.tableizer-table td {
	padding: 4px;
	margin: 3px;
	border: 1px solid #ccc;
}
}
</style><table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Field name </th><th>Object Builder mapping in the connector</th></tr>
 <tr><td>id</td><td>ID</td></tr>
 <tr><td>customer-job-code</td><td>CUSTOMER\_JOB\_CODE</td></tr>
 <tr><td>active</td><td>ACTIVE</td></tr>
 <tr><td>posting-date</td><td>POSTING\_DATE</td></tr>
 <tr><td>expiration-date</td><td>EXPIRATION\_DATE</td></tr>
 <tr><td>posting-timestamp</td><td>POSTING\_TIMESTAMP</td></tr>
 <tr><td>expiration-timestamp</td><td>EXPIRATION\_TIMESTAMP</td></tr>
 <tr><td>company:(id)</td><td>COMPANY\_ID</td></tr>
 <tr><td>company:(name)</td><td>COMPANY\_NAME</td></tr>
 <tr><td>position:(title)</td><td>POSITION\_TITLE</td></tr>
 <tr><td>position:(location)</td><td>POSITION\_LOCATION</td></tr>
 <tr><td>position:(job-functions)</td><td>POSITION\_JOB\_FUNCTIONS</td></tr>
 <tr><td>position:(industries)</td><td>POSITION\_INDUSTRIES</td></tr>
 <tr><td>position:(job-type)</td><td>POSITION\_JOB\_TYPE</td></tr>
 <tr><td>position:(experience-level)</td><td>POSITION\_EXPERIENCE\_LEVEL</td></tr>
 <tr><td>skills-and-experience</td><td>SKILLS\_AND\_EXPERIENCE</td></tr>
 <tr><td>description-snippet</td><td>DESCRIPTION\_SNIPPET</td></tr>
 <tr><td>description</td><td>DESCRIPTION</td></tr>
 <tr><td>salary</td><td>SALARY</td></tr>
 <tr><td>job-poster:(id)</td><td>JOB\_POSTER\_ID</td></tr>
 <tr><td>job-poster:(first-name)</td><td>JOB\_POSTER\_FIRST\_NAME</td></tr>
 <tr><td>job-poster:(last-name)</td><td>JOB\_POSTER\_LAST\_NAME</td></tr>
 <tr><td>job-poster:(headline)</td><td>JOB\_POSTER\_HEADLINE</td></tr>
 <tr><td>referral-bonus</td><td>REFERRAL\_BONUS</td></tr>
 <tr><td>site-job-url</td><td>SITE\_JOB\_URL</td></tr>
 <tr><td>location-description</td><td>LOCATION\_DESCRIPTION</td></tr>
</table>

[NETWORK UPDATE TYPES](http://developer.linkedin.com/documents/get-network-updates-and-statistics-api)

<style type="text/css">
	table.tableizer-table {
	border: 1px solid #CCC; font-family: Arial, Helvetica, sans-serif
	font-size: 12px;
} 
.tableizer-table td {
	padding: 4px;
	margin: 3px;
	border: 1px solid #ccc;
}
}
</style><table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Field name </th><th>Object Builder mapping in the connector</th></tr>
 <tr><td>APPS</td><td>APPLICATION\_UPDATE</td></tr>
 <tr><td>CMPY</td><td>COMPANY\_FOLLOW\_UPDATE</td></tr>
 <tr><td>CONN</td><td>CONNECTION\_UPDATE</td></tr>
 <tr><td>JOBS</td><td>JOB\_UPDATE</td></tr>
 <tr><td>JGRP</td><td>GROUP\_UPDATE</td></tr>
 <tr><td>PICT</td><td>PICTURE\_UPDATE</td></tr>
 <tr><td>PFOL</td><td>Not Supported</td></tr>
 <tr><td>PRFX</td><td>EXTENDED\_PROFILE\_UPDATE</td></tr>
 <tr><td>RECU</td><td>RECOMMENDATION\_UPDATE</td></tr>
 <tr><td>PRFU</td><td>PROFILE\_UPDATE</td></tr>
</table>
