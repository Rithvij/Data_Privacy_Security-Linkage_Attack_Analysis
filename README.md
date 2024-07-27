# Data Privacy and Security : Linkage Attack Analysis
While publishing the sensitive data online, it is very crucial to secure the information of the individuals from being identified uniquely in a database. The released data might provide many valuable insights for various users of it but there is always potential identity disclosure in these scenarios. **"K-anonymity"** and **"L-diversity"** are implemented in this context to limit the disclosure and potential linkage of data given the adversaries background knowledge. **"T-closeness"** has been proposed later to further improve the level of anonymity by considering the distribution of the sensitive attribute in an equivalence class.<br> 
**"Mondrian's greedy algorithm"** is a method used to achieve desired level of anonymity in data privacy. 
Mondrian's algorithm aims to achieve anonymity by recursively partitioning the dataset into smaller regions while ensuring desirable number of records in each region.The partitioning is done in a way that minimizes information loss and maintains the balance among the partitions<br>
**"Linkage attacks"** are potential threats given the prior knowledge of an adversary to link attribute values in an anonymized dataset to extract sensitive information of individuals. Hence the linkage attack scenarios have been simulated and analyzed for various values of ‘k’, ‘l’ and ‘t’ and further studied to gain valuable insights on the level of data anonymization to achieve desirable level of privacy and security

Two linkage attack scenarios on the anonymized data -
  <li>One where the attacker has all the attributes known ( ideal scenario)</li>
  <li>Another where the attacker only has some attributes known</li>
<br>

**Key Observations-**
<li>Anonymization has been achieved for various ‘k’, ‘l’ and ‘t’ values on Adult dataset using Mondrian’s algorithm.</li>
<li>Respective counts have been calculated and analyzed for when correct linkage has been done.</li>
<li>Larger values of ‘k’, ‘l’ and ‘t’ will make the anonymized data more redundant and saturation can be observed at one point.</li>
<li>Although increases in ‘k’ value and ‘l’ value result in better privacy, it is not always the
case that the anonymized data that we obtain in this process is always secure and resistant to attack. Sometimes even smaller values of ‘k’ also might provide better security against an attack.</li>
<li>Attack-scenario-2 which is a more possible adversary scenario will have a lesser number of correct linkages as the anonymity level increases when compared to attack-scenario-1.</li>
