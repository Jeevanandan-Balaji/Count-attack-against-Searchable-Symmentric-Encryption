# Count-attack-against-Searchable-Symmentric-Encryption

Case study I: given a document set {d1, d2, d3, d4, d5, d6}, and d1 = {w1, w2, w3, w4, w6}, d2 = {w1, w2, w3, w6}, d3 = {w1, w2, w4, w6}, d4 = {w1, w4, w6}, d5 = {w4, w5, w6}, d6 = {w4, w6}, and assume that the adversary knows the above information about the document set. Then the adversary starts to launch count attacks for the document set encrypted by an SSE scheme. He observed the following query response from the server.

<img width="571" alt="Screenshot 2023-05-27 at 10 10 31 am" src="https://github.com/Jeevanandan-Balaji/Count-attack-against-Searchable-Symmentric-Encryption/assets/58244207/a3613ea4-0a68-464c-b4f3-ad1ed2336e55">

Case study II: given a document set {d1, d2, d3, d4, d5, d6}, and d1 = {w1, w2, w3, w4, w6}, d2 = {w2, w3, w6}, d3 = {w1, w3, w4, w6}, d4 = {w1, w4, w6}, d5 = {w4, w5, w6}, d6 = {w5}, and assume that the adversary knows the above information about the document set. Then the adversary starts to launch count attacks for the document set encrypted by an SSE scheme. He observed the following query response from the server.

<img width="575" alt="Screenshot 2023-05-27 at 10 11 12 am" src="https://github.com/Jeevanandan-Balaji/Count-attack-against-Searchable-Symmentric-Encryption/assets/58244207/6ea43c2c-1880-4b02-8448-b738a30e930b">

Case study III: given a document set {d1, d2, d3, d4, d5, d6}, and d1 = {w1, w2, w3, w6}, d2 = {w2, w3, w4, w6}, d3 = {w1, w2, w3, w4, w6}, d4 = {w1, w3, w4, w6}, d5 = {w5, w6}, d6 = {w5, w6}, and assume that the adversary knows the above information about the document set. Then the adversary starts to launch count attacks for the document set encrypted by an SSE scheme. He observed the following query response from the server.

TASK:
Recover the underlying keyword of each query step by step, and write down the mapping between queries and keywords.
Can the count attack recover all queries? If not, please explain the reason.

