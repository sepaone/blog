---
layout: post
title: "How do I implement SEPA Direct Debit for my Business?"
date: 2014-08-19T18:51:10+02:00
permalink: /http://blog.sepaone.com/2014/08/19/how-do-i-implement-sepa-direct-debit-for-my-business
---
<p>There are 2 ways to set up SEPA Direct Debit for your business.</p>
<p>a. Do it yourself<br />
b. Use a Direct Debit enabler, such as<a href="www.sepaone.com" target="_blank"><span style="color:#61acb1;"> SEPAone </span></a></p>
<p>There are various steps to be taken and technological processes to be implemented before you can successfully start using SEPA Direct Debit for your business. We have outlined below what the process might look like for you. Please note that the process may vary based on your location and government regulations.</p>
<p>&nbsp;</p>
<h4>1. <span style="color:#61acb1;">Have a bank account within the SEPA zone</span></h4>
<p>A bank account within the SEPA zone is required to use SEPA Direct Debits for your business.</p>
<hr />
<h4>2. <span style="color:#61acb1;">Acquire a Creditor Identifier:</span></h4>
<p>A Creditor Identifier is a unique code that is used as a reference for every SEPA Direct Debit merchant. The process and timing of acquiring a Creditor Identifier depends on the country you are registered. For example:</p>
<blockquote>
<ul>
<li><span style="color:brown;">Germany</span> &#8211; The merchant has to visit the <a href="https://extranet.bundesbank.de/scp/" target="_blank">Deutsche Bundesbank</a> webpage where they can apply for a Creditor Identifier. The process takes 1 business day.</li>
<li><span style="color:brown;">France &amp; Italy </span> &#8211; The merchant has to contact their own bank and request for a Creditor Identifier, which will in turn apply for one, on the merchant’s behalf.</li>
<li><span style="color:brown;">UK</span> &#8211; The merchant has to contact their own bank and request for a Creditor Identifier, which will in turn apply for one, on the merchant’s behalf. Some banks may have certain requirements that merchants need to meet (monetary reserves, expertise/knowledge of SEPA Direct Debit)</li>
</ul>
</blockquote>
<hr />
<h4>3. <span style="color:#61acb1;">Implement Click Mandates:</span></h4>
<p>Once you have the Creditor Identifier, you need to get your bank to accept Click Mandates (only certain banks provide this capability or are willing to do so).</p>
<p><em>SEPAone works with partner banks that accept Click Mandates.</em></p>
<hr />
<h4>4. <span style="color:#61acb1;">Manage Credit risk:</span></h4>
<p>The bank will require protection against any possible risks from chargebacks on their behalf. Banks will set a credit limit and some may even ask for collateral.</p>
<p><em>SEPAone can manage the credit risk for you, by monitoring transactions and chargeback rates.</em></p>
<hr />
<h4>5. <span style="color:#61acb1;">Implement the Technology:</span></h4>
<p>You will need to go through a complex, time consuming and expensive process of connecting your Frontend and Backend to the bank, through different technological frameworks such as <span style="color:brown;">EBICS or HBCI </span>(depending on what the bank offers and your legacy software requirements), in order to activate Direct Debit.</p>
<p><em>SEPAone has developed the required technology; all you need to do is use our simple API and start receiving payments through SEPA Direct Debit.</em></p>
<hr />
<h4>6. <span style="color:#61acb1;">Convert to IBAN/BIC format:</span></h4>
<p>Most customers do not know their <span style="color:brown;">IBAN and BIC </span>and do not have them handy at checkout. They are used to their legacy credentials such as their Account number and (in many countries) Bank Sorting number.</p>
<p>To prevent this<span style="color:brown;"> IBAN conversion killer</span>, you might want to implement an IBAN/BIC converter.</p>
<p><em>SEPAone accepts IBAN, BIC or the legacy account details. Your customer can decide what they prefer to enter.</em></p>
<hr />
<h4>7. <span style="color:#61acb1;">Implement a Mandate Management System: </span></h4>
<p>Specific guidelines set out by European Payment Council have to be followed in order to manage Mandates. In general:</p>
<blockquote>
<ul>
<li>All <span style="color:brown;">Paper Mandates</span> must be stored by the Business either in the original form or as a digitized document. The data in <span style="color:brown;">Click Mandates</span> must be stored as presented by the customer.</li>
<li>These mandates must be stored for as long as they are valid, or for a <span style="color:brown;">minimum of 14 months</span> after the last collection.</li>
<li>Both the customer and the Business can modify a Mandate at any time, in some cases based on mutual agreement.</li>
</ul>
</blockquote>
<p>If you have used Direct Debit before SEPA, you will need to review all the existing mandates and make sure they fit the SEPA Direct Debit requirements, as well as allowing for the creation of new mandates. Any missing information fields will need to be updated, and a unique reference must be assigned to the mandate.</p>
<p><em>SEPAone can handle all of your Mandate Management needs, including but not limited to:</em></p>
<blockquote>
<ul>
<li><em>Creation of one-off and recurring mandates.</em></li>
<li><em>Generating mandate references.</em></li>
<li><em>Handling cancelled and expired mandates.</em></li>
</ul>
</blockquote>
<hr />
<h4>8. <span style="color:#61acb1;">Implement Credit Scoring/ Risk Management:</span></h4>
<p>Though optional, this is an important feature to have in order to reduce your financial risk. By implementing a scoring system, you can greatly reduce your chargeback rates, fraud and credit risk.</p>
<p><em>SEPAone has a user scoring system which we use to validate each request, thus reducing your risk.</em></p>
<hr />
<h4>9. <span style="color:#61acb1;">Decide between the Core and COR1 Scheme: </span></h4>
<p>Depending on your location and the schemes offered by your bank, you may have the option of implementing the faster COR1 scheme. The availability of COR1 consumer accounts is almost<span style="color:brown;"> 100% in Germany and Austria, with Spain following at over 90%</span>, whereas it is still growing in availability in other SEPA member states countries.</p>
<p><em>Please refer to our SEPA Direct Debit Availability Research for more information.</em></p>
<hr />
<h4>10. <span style="color:#61acb1;">Implement Pre-notification processes: </span></h4>
<p>In general customers must be notified <span style="color:brown;">14 days in advance</span> of any payment collection. It is however possible to reduce this advance notification period through mutual agreement with a customer. We advise to do so in your terms and conditions.</p>
<p><em>SEPAone can send pre-notifications to customers on your behalf, through both eMails as well as Snail Mails. We also provide you with a standard language that you can use in your terms and conditions to shorten the pre-notification period.</em></p>
<hr />
<h4>11. <span style="color:#61acb1;">Implement Transaction and R-Transaction processes: </span></h4>
<p>You will need to implement robust Transaction and R-Transaction processes. As a merchant or a customer, you have the possibility to request cancellation of a SEPA Direct Debit request that you have already initiated. A transaction that has already been processed can be reversed afterwards.</p>
<p>Here is a summary of the various possibilities for R-Transactions:</p>
<table class="data-table">
<tbody>
<tr>
<th class="border-top border-bottom border-left border-right">Initiated By</th>
<th class="border-top border-bottom border-right">Before Due Date</th>
<th class="border-top border-bottom border-right">After Due Date</th>
</tr>
<tr>
<td class="border-bottom border-left border-right">Merchant</td>
<td class="border-bottom border-right">Revocation; Request for Cancellation</td>
<td class="border-bottom border-right">Reversal: within 5 Business days</td>
</tr>
<tr>
<td class="border-bottom border-left border-right">Customer or Customer&#8217;s Bank</td>
<td class="border-bottom border-right">Refusal by Customer or Customer&#8217;s Bank</td>
<td class="border-bottom border-right">Return by Bank within 5 Business days; Refund for Customer within 8 weeks; Refund for Unauthorized Transaction within 13 months</td>
</tr>
</tbody>
</table>
<p>Refusal by Customer can occur due to reasons such as:</p>
<blockquote>
<ul>
<li>Customer has <span style="color:brown;">blocked a merchant</span> from collecting SEPA Direct Debits from their account</li>
<li>Customer has set a <span style="color:brown;">maximum payment amount</span> and/or <span style="color:brown;">payment period</span>.</li>
</ul>
</blockquote>
<p>Refusal by Customer’s bank can occur due to the several reasons such as:</p>
<blockquote>
<ul>
<li><span style="color:brown;">Account number problems</span> (Incorrect/Closed/Blocked, etc)</li>
<li><span style="color:brown;">Mandate problems</span> (Non-existent/Expired/Missing Information, etc)</li>
</ul>
</blockquote>
<p>In case of an R-transaction you may want to contact the customer and give them the opportunity to pay with another payment method within a period of time.</p>
<p>Apart from R-Transaction handling, the following processes may also be implemented:</p>
<blockquote>
<ul>
<li><span style="color:brown;">Collection handovers</span> &#8211; In case the customer hasn’t paid even after the additional amount of time, you might want to have an external party take care of the collection process.</li>
<li><span style="color:brown;">Monitoring system</span> for the above processes</li>
</ul>
</blockquote>
<p><em>With SEPAone you have support for all of this, as well as:</em></p>
<blockquote>
<ul>
<li><em>Support for both CORE and COR1 schemes.</em></li>
<li><em>Plausibility checks.</em></li>
<li><em>Pre-notification emails to customers.</em></li>
<li><em>Handling R-transactions and Reporting through API.</em></li>
</ul>
</blockquote>
<hr />
<h4>11. <span style="color:#61acb1;">Implement a Refund processes: </span></h4>
<p>Imagine a situation where a customer returns a good, six days after the due date. You would like to refund this customer. In this case you have to extract your customer account details and transfer back the money to his account. This is a usual bank transaction.</p>
<p>There is a fraud risk involved here, because the customer can still send a refund request through his bank.</p>
<p><em>With SEPAone you have support for creating a robust Refund process, as well as:</em></p>
<blockquote>
<ul>
<li><em>Easy initiation of a refund with reference to initial Direct Debit transaction</em></li>
<li><em>Monitoring and alerts for R-Transaction after refunds</em></li>
</ul>
</blockquote>
<hr />
