# Taxonomy_Privacy_Data_Control_Signals

A graphical depiction of the taxonomy is available here:  https://app.lucidchart.com/documents/view/dcc2b794-80ed-4dfc-8da8-7679eb8923ae

(The representation is also visible in the 'Issues' to this repository).

<h1>Table 1: Tabular depiction  of the Taxonomy:</h1>

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Dimensions (Level 1)</th>
    <th class="tg-0pky">Dimensions (Level 2)</th>
    <th class="tg-0pky">Comments and Attributes</th>
    <th class="tg-0pky">Dimensions (Level 3)</th>
    <th class="tg-0pky">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="12">Data and Control</td>
    <td class="tg-0pky">Types of Data Collected</td>
    <td class="tg-0pky">We try to keep this agnostic to the characteristics of the data, which we separate into a different dimensions, or the sensors from which it is collected. This level of abstraction is selected to best allow for the open texture of the Documentation. </td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">'Location Data', 'Profile Data', 'Technical Meta-data', 'Physical activity Data', 'Social Data', 'Behaviour Data', 'Electronic Identifier' 'Basic Account Data', 'Photos and Videos' and 'User Registration Data/Contract Details'<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">Active Audience</td>
    <td class="tg-0pky">The anonymity a user has while using a platform is separate from the risk the user runs of the service provider of the platform sharing their data with a third party, for instance for commercial purposes or for legal compliance. Therefore, we create separate categorisations for both. (User only, Selected other users of the Service, All other users of the service, Public)</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0pky">Data Collected From</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Timing of Data Collection</td>
    <td class="tg-0pky">The time at which the data collection takes place. (On sign up, When shared by user, During usage of functionality, On integration of third-party services)</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="3">Data Characteristics</td>
    <td class="tg-0pky" rowspan="3">Since we have kept the ’type of data collected’ agnostic of its characteristics, it becomes necessary to<br>consider these characteristics in a separate form.</td>
    <td class="tg-0pky">Identification Risks</td>
    <td class="tg-0pky">(Non-personal data, Direct identification, Indirect identification, Direct or indirect identification)<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">Sensitivity of Data </td>
    <td class="tg-0pky">(Financial data, Health Data)</td>
  </tr>
  <tr>
    <td class="tg-0pky">Licensability of Data </td>
    <td class="tg-0pky">(Yes/No)</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="3">User Control</td>
    <td class="tg-0pky" rowspan="3">This is arguably one of the most important aspects of this taxonomy.</td>
    <td class="tg-0pky">User Control Options </td>
    <td class="tg-0pky">(Opt-in, Opt-out, Change audience, Right of access...)</td>
  </tr>
  <tr>
    <td class="tg-0pky">User Control Channels</td>
    <td class="tg-0pky">(via email, via website, via device settings, via third party settings, via multi-platform settings page...)</td>
  </tr>
  <tr>
    <td class="tg-0pky">User Control Limitations </td>
    <td class="tg-0pky">('Not all types of data can be rectified')</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Retention</td>
    <td class="tg-0lax" rowspan="2"></td>
    <td class="tg-0lax">Period</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Location</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="8">Processing and Usage</td>
    <td class="tg-0lax">Legal Basis</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Processing Entities</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Purpose</td>
    <td class="tg-0pky">We identify two distinct but related types of signals in the Documentation. The first is the ’purpose’, the more abstract claim about the purpose of the processing. (Access to services, provision of services, commercial purposes...)</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0pky">Functionalities</td>
    <td class="tg-0pky">The second is functionalities, which includes the aspects of technical implementation. Functionality and ’purpose’ go hand in hand, but are not entirely the same. The ’Purpose’ category, in its abstraction, allows for the usage of broader terminology that the functionality does not. For instance, the ’Purpose’ can be ’provision of service’ - but the ’Functionality’ category then asks ’which part (or functionality) of the service?’. For instance, the purpose for the collection of a user’s account data and location data, both, can be ’provision of service’. This is fair - a user needs an account to be able to access the service, and she needs to provide location data for tracking fitness activities. The distinction between the two is in the functionality: ’account creation’, and ’fitness activity tracking’ respectively.</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0pky">License Claimed</td>
    <td class="tg-0pky">This indicates whether the service provider claims a license over the licenseable data it collects from its users. At the basic level, this is dimension with binary attributes (’Yes/No’). It can also, however, be extended to include the terms of the license such as duration, revocability, commercial usage, etc. This is<br>identified from the Terms and Conditions and not the privacy policy.</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Data Shared With</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Data Security</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Actions on Data</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="10">Policy Meta-data</td>
    <td class="tg-0pky">Commitments</td>
    <td class="tg-0pky">This is where we include the abstract `Commitments' made by the service, for instance, "We do not sell your personal information". This statement cannot quite be operationalised, but represents an important communication from the service provider to the user.</td>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">-</td>
  </tr>
  <tr>
    <td class="tg-0lax">Compliance Information</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Policy Change Information</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">How changes will be made</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">Will the user be informed or not</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">Date Last Updated</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="3">Service Provider details</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">Contact</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">Affiliates</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">DPO</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="2">Jurisdiction Information</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">Applicable Jurisdiction</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">Transfer outside Jurisdiction</td>
    <td class="tg-0lax"></td>
  </tr>
</tbody>
</table>


<h1>Table 2: Taxonomy applied to the checklist by Perera et al. in <cite> <a href="https://arxiv.org/abs/1606.08480">Privacy Knowledge Modelling for Internet of Things: A Look Back</cite></a></h1>


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
    <td class="tg-0pky">'Processing Entity'</td>
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
    <td class="tg-0pky">We specify 'functionalities', which are arguable a part of the 'reward' that data subjects receive. However, there can be monetary rewards as well though they were not available in the sample space.</td>
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

<h1> Table 3: Taxonomy samples from Documentation</h1>


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
    <td class="tg-0pky">OpenTracks does <span style="background-color: 	#008080"> only store data on the local device</span> that is <span style="background-color:#FFDAB9">relevant for tracking your sport exercise</span>. <span style="background-color:#670A0A">Stored data is not transmitted from the app itself to a third party<span>.</td>
    <td class="tg-0pky"><span style="background-color: 	#008080">retention location: local</span> <span style="background-color: #FFDAB9"><br>functionality: activity tracking<br></span><span style="background-color:#670A0A">typeofdatacollected: [none]<span></td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
</tbody>
</table></div>

