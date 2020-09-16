# Taxonomy for the Representation of Privacy and Data Control Signals

A graphical depiction of the taxonomy is available here:  https://app.lucidchart.com/documents/view/dcc2b794-80ed-4dfc-8da8-7679eb8923ae

(The representation is also visible in the 'Issues' to this repository).

<h3>Table 1: A Tabular Depiction of the Taxonomy.</h3>

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Dimensions (Level 1)</th>
    <th class="tg-0lax">Dimensions (Level 2)</th>
    <th class="tg-0lax">Comments </th>
    <th class="tg-0lax">Attributes</th>
    <th class="tg-0lax">Dimensions (Level 3)</th>
    <th class="tg-0lax">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax" rowspan="26">Data and Control</td>
    <td class="tg-0lax" rowspan="15">Types of Data Collected</td>
    <td class="tg-0lax" rowspan="15">We try to keep this agnostic to the characteristics of the data, which we separate into a different dimensions, or the sensors from which it is collected. This level of abstraction is selected to best allow for the open texture of the Documentation. </td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Technical Meta-data</td>
    <td class="tg-0lax">(Device information, network information, app information)<br></td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User Contact details</td>
    <td class="tg-0lax">(Email address, Home address, Phone Number, Social Media handle)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Registration data</td>
    <td class="tg-0lax">(Name, birthdate, gender)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Basic Account Data</td>
    <td class="tg-0lax">(username, password)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Images and Videos</td>
    <td class="tg-0lax">(Profile pictures, uploaded images, uploaded videos)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Approximate Location data </td>
    <td class="tg-0lax">(Eg.: Time Zone, Country level TLD)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Precise Location data </td>
    <td class="tg-0lax">(GPS-based, WiFi-based, Bluetooth-based)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Physical activity data</td>
    <td class="tg-0lax">(Steps, Pace, Heartbeat, Calories)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Social data</td>
    <td class="tg-0lax">(Contacts, Social activity)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User interests and motivation</td>
    <td class="tg-0lax">(Health Goals, Fitness Goals)<br></td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User opinions and preferences<br></td>
    <td class="tg-0lax">(Reviews)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Physical attributes</td>
    <td class="tg-0lax">(Sizes, Height, Weight)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User behaviour</td>
    <td class="tg-0lax">(App or service usage behaviour, Browsing behaviour, Device usage behaviour, Other behaviour)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Electronic identifiers</td>
    <td class="tg-0lax">(Device-based identifiers, Identifier assigned by service provider, identifier assigned by third-party)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Payment data</td>
    <td class="tg-0lax">Eg: (Payment provider, payment method, price, VAT, payment status, discount)</td>
  </tr>
  <tr>
    <td class="tg-0lax">Active Audience</td>
    <td class="tg-0lax">The anonymity a user has while using a platform is separate from the risk the user runs of the service provider of the platform sharing their data with a third party, for instance for commercial purposes or for legal compliance. Therefore, we create separate categorisations for both. </td>
    <td class="tg-0lax">(User only, Selected other users of the Service, All other users of the service, Public)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Data Collected From</td>
    <td class="tg-0lax">The source from which data about the user is collected. </td>
    <td class="tg-0lax">(User, Third-party, Public data)</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Timing of Data Collection</td>
    <td class="tg-0lax">The time at which the data collection takes place.</td>
    <td class="tg-0lax">(On sign up, When shared by user, During usage of functionality, On integration of third-party services)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="3">Data Characteristics</td>
    <td class="tg-0lax" rowspan="3">Since we have kept the ’type of data collected’ agnostic of its characteristics, it becomes necessary to consider these characteristics in a separate dimension.</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Identification Risks</td>
    <td class="tg-0lax">(Non-personal data, Direct identification, Indirect identification, Direct or indirect identification)<br></td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Sensitivity of Data </td>
    <td class="tg-0lax">(Financial data, Health Data)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Licensability of Data </td>
    <td class="tg-0lax">(Yes, No, Maybe)</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="3">User Control</td>
    <td class="tg-0lax" rowspan="3">This is arguably one of the most important aspects of this taxonomy, and is divided into three further dimensions.</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User Control Options </td>
    <td class="tg-0lax">(Turn functionality on or off, change audience, opt-in, opt-out, right to access, right to restrict, right to rectify, right to object, right to data portability, right to erasure/deletion, limit, change or delete specific data, right to file a complaint, Do Not Track)<br></td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User Control Channels</td>
    <td class="tg-0lax">(via device settings, via third-party app or service settings, via app settings, via service provider's website, via contacting service provider)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">User Control Limitations </td>
    <td class="tg-0lax"> This includes any limitations that may be put on the user's control over their own data, and/or on its deletion. Eg: ('Certain profile information is available at all times, 'Not all types of data can be rectified', 'Not all data is deleted')</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Retention</td>
    <td class="tg-0lax" rowspan="2">Details regarding the retention of the data.<br></td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Period</td>
    <td class="tg-0lax">Ideally, this should be represented in fixed units of time (Eg: 48 hours). In practice, the sample set tends to use variables periods, eg: 'as long as your account remains active'. This can also be 'None'.</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Location</td>
    <td class="tg-0lax">At the basic level, this has the attributes (On device, Off device, None), which informs the user whether the data is stored on the device, under the control of the user, or off-device, or not at all. However, this can also be expanded to indicate which exact entity is storing the data, if such information is available.</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="8">Processing and Usage</td>
    <td class="tg-0lax">Legal Basis</td>
    <td class="tg-0lax">The legal basis under which the data is collected, as per Art. 6(1) of the GDPR. This is an important category because each basis carries with a different set of conditions. 'Legitimate interest (of the service provider or third party)', for instance, requires a balancing test between the interests of the users and the service provider. This is only applicable if the 'basis' is explicitly mention. </td>
    <td class="tg-0lax">(Consent, Performance of a contract, compliance with a legal obligation, vital interests of natural persons, public interests, legitimate interests).</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Purpose</td>
    <td class="tg-0lax">We identify two distinct but related types of signals in the Documentation. The first is the ’purpose’, the more abstract claim about the purpose of the processing. Eg: (Access to services, provision of services, commercial purposes...)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Functionalities</td>
    <td class="tg-0lax">The second is functionalities, which includes the aspects of technical implementation. Functionality and ’purpose’ go hand in hand, but are not entirely the same. The ’Purpose’ category, in its abstraction, allows for the usage of broader terminology that the functionality does not. For instance, the ’Purpose’ can be ’provision of service’ - but the ’Functionality’ category then asks ’which part (or functionality) of the service?’. For instance, the purpose for the collection of a user’s account data and location data, both, can be ’provision of service’. This is fair - a user needs an account to be able to access the service, and she needs to provide location data for tracking fitness activities. The distinction between the two is in the functionality: ’account creation’, and ’fitness activity tracking’ respectively.
    <p>Thus, for example, from the Runtastic privacy policy: 
    [To operate the Products and provide the services, including] specifies the purpose while [to authenticate your access to an account], [track and display your health and fitness activities], [show your training progress and statistics] each specify a functionality. 
    </P></td>
    <td class="tg-0lax">Eg:&nbsp;&nbsp;(Account Creation, Fitness activity tracking, Fitness activity performance analysis, Communication with user, Sponsored content, Customer support. Leaderboard, Registration via third-party service, Sharing via third-party applications, Social Network, Personalisation of Service, Integration of third-party services, Creation of segments and routes, Placing orders, Third-party device integration, Events, Privacy Zone, Challenges, Third-party social media integration, Marketing trend analysis, Usage trend analysis, usage, Profiling)<br></td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
    <tr>
    <td class="tg-0lax">Processing Roles</td>
    <td class="tg-0lax">This covers the 'Roles' of the processing entity with which data is shared. From the sample set, we identify the following 'Processing Roles' [(Service Provider),(Third-party processor), (Third-party service provider), (Other third party)]. 'Processor' here refers to Data Processor as defined by the GDPR.</td>
    <td class="tg-0lax">(Service provider, third-party processor, third-party service provider, other third-party)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">License Claimed</td>
    <td class="tg-0lax">This indicates whether the service provider claims a license over the licenseable data it collects from its users. At the basic level, this is dimension with binary attributes (’Yes/No’). It can also, however, be extended to include the terms of the license such as duration, revocability, commercial usage, etc. This is identified from the Terms and Conditions and not the privacy policy.</td>
    <td class="tg-0lax">(Yes/No)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Data Shared With</td>
    <td class="tg-0lax">List of entities data is shared with. This is meant to be used with individual or grouped entries from 'Types of data collected', to specify what data is shared with which entities. </td>
    <td class="tg-0lax">[List of entities]</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Data Security</td>
    <td class="tg-0lax">('Reasonable measures')</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Actions on Data</td>
    <td class="tg-0lax">We identify six 'actions' on data from the sample set. Anonymisation at the basic level indicates if anonymisation is conducted or not (Yes/No), but can be expanded to include the method of anonymisation if such information is available. (Generation/Transfer?)<br></td>
    <td class="tg-0lax">(Collection, Transfer, Retention, Aggregation of multiple users' data, correlation of user data with other available data Psuedonomysation or anonymisation(Method of anonymisation))</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="10">Policy Meta-data</td>
    <td class="tg-0lax">Commitments or Indemnities</td>
    <td class="tg-0lax">This is where we include the abstract `Commitments' made by the service, for instance, "We do not sell your personal information". This statement cannot quite be operationalised, but represents an important communication from the service provider to the user.</td>
    <td class="tg-0lax">Eg: ('We do not sell your personal information','We never share special categories of personal data for advertising purposes', ''We will contest legal demands for your data when we believe that the requests are overbroad, vague, or lack proper authority')</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Compliance Information</td>
    <td class="tg-0lax">The regulations and/or security standards the entity complies with.</td>
    <td class="tg-0lax">Eg: (GDPR, CCPA)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Policy Change Information</td>
    <td class="tg-0lax" rowspan="2">Information regarding how changes to the policy are made, and whether they are communicated to the user or not. n most cases, this service providers state that they can make changes to their policy at their discretion and the obligation is on the users to track changes to the policy. In [2/4] cases, the service provider stated that they would inform users in case of any significant changes.</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">How changes will be made</td>
    <td class="tg-0lax">(At the service provider's discretion)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Will the user be informed or not</td>
    <td class="tg-0lax">(Service provider will inform you in case we make significant changes to the policy, but user needs to check for non-significant changes, User is obligated to check the privacy policy for changes)</td>
  </tr>
  <tr>
    <td class="tg-0lax">Date Last Updated</td>
    <td class="tg-0lax">The date the policy was last updated.</td>
    <td class="tg-0lax">(Date)</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">-</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="3">Service Provider details</td>
    <td class="tg-0lax" rowspan="3">Details regarding the service provider. The service provider's contact details are often necessary from a consumer perspective, for instance for customer support. Information regarding the service provider's 'affiliates' are necessary because the affiliates potentially have access to the user's data as well. The DPO's contact details, separate from the service provider's details, are necessary from the perspective of the GDPR.</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Contact</td>
    <td class="tg-0lax">(Physical address, Email address, Telephone number, Social media details, Website)<br></td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Affiliates</td>
    <td class="tg-0lax">[List of Entity Names]</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">DPO</td>
    <td class="tg-0lax">(Email address, physical address, telephone number)</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Jurisdiction Information</td>
    <td class="tg-0lax" rowspan="2">This covers the 'applicable jurisdiction' for the data collection and asks whether data is transferred outside that jurisdiction - and if is, to which jurisdiction. This information is important because a user's legal rights and risks often differ between jurisdictions.</td>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Applicable Jurisdiction</td>
    <td class="tg-0lax">[Name of Jurisdiction]. Eg: (Netherlands, Ireland)</td>
  </tr>
  <tr>
    <td class="tg-0lax">-</td>
    <td class="tg-0lax">Transfer outside Jurisdiction</td>
    <td class="tg-0lax">(Yes/No) - if yes, name of jurisdiction data is transferred to and the legal mechanism used to validate the transfer. Eg: (Yes, to the US, Standard Contractual Clauses)</td>
  </tr>
</tbody>
</table>
</div>



<h3>Table 2: Taxonomy validation from the checklist by Perera et al. in <cite> <a href="https://arxiv.org/abs/1606.08480">Privacy Knowledge Modelling for Internet of Things: A Look Back</cite></a></h3>


<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">S. No.</th>
    <th class="tg-0pky">Checklist Questions<br></th>
    <th class="tg-0pky">Relevant to the Taxonomy</th>
    <th class="tg-0pky">   <br>Answered by the Taxonomy <br></th>
    <th class="tg-0pky">Taxonomy Codes that answer this question</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>1&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>A description of the data collected and how it is used by consumers should be available to data owners.   <br></td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Type of data collected', paired with 'Functionality' and 'Purpose'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>2&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data owners should be able to agree with the collection of their data before it happens.   </td>
    <td class="tg-0pky">   <br><span style="background-color:">No</span>; this question relates to timing of notice, not content.<br></td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br> &nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>3&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The techniques used to collect a data item should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">No</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">We identify the source the data is collected from, 'Data Collected from', but not the technique used.</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>4&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The collector (data consumer) of a data item should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky"> 'Data Shared with' and 'Processing Roles'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>5&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The purposes for which a data item is collected should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Purpose', 'Functionality' and 'Legal Basis'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>6&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The entities (a third party, for example) to which a data item is disclosed by its   collector should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Data Shared with'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>7&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The data items to be collected should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Types of data Collected'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>8&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>The retention time of a data item should be identified.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Retention: Time' and 'Retention: Location'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>9&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data consumers should indicate if data owners are allowed to complete, correct, and update their retained data.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'User Control: Right to Rectify'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>10&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data consumers should indicate if data owners can request records on how their data have been used, in formats understandable by data owners and with known delays and charges.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'User Control: Right to Access'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>11&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data consumers should indicate if data owners are able to request copies of data on them, in formats understandable by data owners and with known delays and charges.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'User Control: Right to Access'</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>12&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data consumers should clearly inform data owners regarding what kind of knowledge is expected to be discovered using their data.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">No</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">While 'purposes' are specified, this information is not available in the documentation.</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>13&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data owners should know the risks—their impact level of sharing  (trading)—regarding a particular type of data before sharing (trading)   occurs.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Yes</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Data Characteristics: Sensitivity of Data, Identification Risk and Licenseability of data'<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>14&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data owners and consumers should come to an agreement regarding the reward that the data owners might receive as a return for taking the risks of sharing data.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Partially</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">We specify 'functionalities', which are arguably a part of the 'reward' that data subjects receive. However, there can be monetary rewards as well though they were not available in the sample space.</td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>15&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Reward types associated with sharing data need to be identified clearly before any sharing occurs.   </td>
    <td class="tg-0pky">   <br><span style="background-color:">No</span>; this is again a question relevant for timing, and not content.<br></td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br> &nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>16&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data owners should be able to apply data-quality-reduction techniques before data is sent to the data consumers to reduce privacy risks.   </td>
    <td class="tg-0pky">   <br><span style="background-color:">No</span>; this is again a timing question, and not content.<br></td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br> &nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>17&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">   <br>Data owners and consumers should agree on which data-quality-reduction techniques will be used.   </td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br>Yes&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">&nbsp;&nbsp;&nbsp;<br><span style="background-color:">Partially</span>&nbsp;&nbsp;&nbsp;</td>
    <td class="tg-0pky">'Anonymisation and psuedonimysation' at the basic level indicates if data-quality-reduction techniques are used or not (Yes/No) , but can also include the type of reduction applied, if such information is available. </td>
  </tr>
</tbody>
</table>

<h3>Table 3: Sample Application of the Taxonomy Codes from Document Samples</h3>

<div class="tg-wrap"><table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">S. No.</th>
    <th class="tg-0pky">Sample Text</th>
    <th class="tg-0pky">Taxonomy Codes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">OpenTracks does <span style="background-color: 	#008080"> only store data on the local device</span> that is <span style="background-color:#FFDAB9">relevant for tracking your sport exercise</span>. <span style="background-color:#ffb3b3">Stored data is not transmitted from the app itself to a third party<span>.</td>
    <td class="tg-0pky"><span style="background-color: 	#008080">retention_location: on device</span> <span style="background-color: #FFDAB9"><br>functionality: activity tracking<br></span><span style="background-color:#ffb3b3">type_of_data_collected: [none]<span></td>
  </tr>
  <tr>
    <td class="tg-0pky">2</td>
    <td class="tg-0pky"><span style= "background-color: #33acff ">For the performance of our agreement with you</span>:  <p>In order to <span style= "background-color: #FFDAB9">manage and handle your purchases (online and in our stores) </span> and <span style= "background-color: #9acbed">to provide you with the Services you <span style= "background-color: #FFDAB9"> requested from us </span>, including handling your requests, we use your <span style= "background-color: #ffb3b3">contact details, your account and electronic  identiǼication data, information regarding your purchases in our stores and online, information regarding your  leisure activities, interest and events, information regarding your training and running data (including your Ǽitness  activities), your Contest data, your communication data and – after your consent thereto – information regarding  your Personal measurement, your running specifics, your tests, measurement results, and your location data.</span></p>
</td>
    <td class="tg-0pky"><span style="background-color: #33acff">legal_basis: performance of 
    contract</span><br>
    <span style="background-color: #FFDAB9">functionalities: online purchases, offline purchases, purchase fulfilment, handling user requests</span><br>
    <span style="background-color: #9acbed">purpose:provision of requested services</span><br>
    <span style="background-color: #ffb3b3">types_of_data_collected: User Contact Details, Electronic Identifier, User Behaviour, User Opinion and Preferences, Physical activity data, Physical attributes, [Precise] location data. </span>
    </td>
  </tr>
  <tr>
    <td class="tg-0pky">
   <span style="background-color: #FFDAB9"><b>Profile</b></span>. Your profile is <span style="background-color: #ff9900">fully visible to your friends on Runtastic by default</span>. This means, <span style="background-color: #FFDAB9">as soon as  you add friends in the products</span>, those people will be able to see your profile, including when you  <span style="background-color:  #ffb3b3">join groups and events</span>. <span style="background-color: #99e699">In your privacy settings</span> you can also <span style="background-color: #009933">set your profile visibility to “Only me” or  “Everybody”</span>. <span style="background-color: #ffb3b3">Please note that your first name, last name, and profile picture </span> are <span style="background-color: #d6f5d6">visible to everybody  at all times</span>. This is necessary to enable others to send you a friend request.
    </td>
    <td class="tg-0pky">
    <span style="background-color: #FFDAB9">functionalities: User Profile, Social Network
    </span>
    <span style="background-color: #ffb3b3">types_of_data_collected: Registration Data (Name), Images and Videos (Profile Picture), User Behaviour (App Usage activity)</span>
    <span style="background-color: #ff9900">active_audience: selected other users of service
    </span><br>
    <span style="background-color: #009933"> User Control Option: change audience;    </span><br>
    <span style="background-color: #99e699"> User Control Channel: via app settings </span><br>
    <span style="background-color: #d6f5d6"> User Control Limitation: types_of_data_collected(Name, Profile Picture) are visible to everybody at all times.
    </td>
    <td class="tg-0pky"></td>
  </tr>
</tbody>
</table>
</div>