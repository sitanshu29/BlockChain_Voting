                                                      Our Idea

For our project, we tried to create a system that doesn’t entirely replace the current voting but rather integrates within a current system, so that the voting can be accessed by the majority of the population.

i.)	Registration 

The first part of our solution is the registration process. In our web based registration process, we made sure that someone’s identity isn’t being misused for fraudulent purposes, especially when voting is considered, where each and every voter matters.
To register for the voting process, the potential voter could either use the existing way of getting registered in a nearby Election Ofiice or instead use the much efficient and less cumbersome web based system designed by us.

In order to register with the voting process, the user requires an Adhaar ID, postal address proof, mobile no., email id, password and some other basic information. All of this information then forms a transaction for the user agreeing with the government that they are asking to vote; this transaction is then created on the blockchain.
Mobile no. and email verification is been done using OTPs.
Once someone has registered, a government supervisory authority verifies the detail of the voter. The authority makes the decision as to whether to verify the voter or not. If the user is verified, they will be sent a ballot card with their information on it to both their home address and email address. A random password will also be generated to be used on the polling stations or the web. 
During this process, the blockchain is used to keep the record of both transactions taking place at each stage of this process for each voter:
1.	Firstly, a transaction is created when a user ‘registers’.
2.	The next transaction is created when the the authority authorizes the user’s right to vote.
The user when approved is given a single vote which can be used in the upcoming elections in their constituency.

ii.)	Voting Process

At the time to vote, authentication of user requires three pieces of evidence; their Adhaar Number, the password supplied on registration and the ballot card containing a unique ID.  As there are two methods of voting (web browser, physical polling station) the way the user will input the authentication details shall differ; however, in order to vote they are required to provide all three pieces of information. It is also important to note that each user will have been registered at a certain constituency so they will only be able to vote at a local polling station within that constituency or via the internet at 
the URL provided on the ballot card. 
Behind the scenes, the blockchain will ensure that the voter has not already used up their vote. If the user does have a vote, then the station will then allow the user to continue to the voting screen. If not, then system will respond to the user appropriately.
Once the vote has been confirmed( the polling station/web portal) will then generate a transaction to remove the user’s vote within the voter blockchain. 

The important part of the Electoral process is to keep up with the anonymity of the vote that has been casted. Keeping this is mind, once the vote is casted, only the count of vote is increased in a separate database which has the list of all the candidates taking part in the election constituency. No information is being stored regarding the information of the vote casted by the voter.

Further to this, we also need to ensure they are not forced to vote in a particular way so we have incorporated a double-check service where by users shall be prompted a second time to confirm their submission before the vote is sent; this also then allows us to almost eradicate accidental votes.
Also, we have tried to make our mechanism very difficult to gain access to all the votes without first taking control of the entire service network.
