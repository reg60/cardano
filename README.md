Guide: How to build a Cardano Stake Pool
https://www.coincashew.com/coins/overview-ada/guide-how-to-build-a-haskell-stakepool-node

KEYS (https://www.coincashew.com/)

'   |   KEYS     |  OFFLINE  |  PRODUCER | 
'   --------------------------------------
'  |kes.vkey    |    C     <=    Y      |
   |kes.skey    |           |    Y      |
   |node.vkey   |    Y      |           | ~/cold-keys
   |node.skey   |    Y      |           | ~/cold-keys
   |node.counter|    Y      |           | ~/cold-keys
   |node.cert   |    Y      =>   C      |
   |vrf.skey    |           |    Y      |
   |vrf.vkey    |           |    Y      |
   |stake.vkey  |    Y      |           |
   |stake.skey  |    Y      |           |
   |stake.addr  |    Y      |           |
   |stake.cert  |    Y      =>   C      | 
   |payment.vkey|    Y      |           |
   |payment.skey|    Y      |           |
   |payment.addr|    Y      |           |
   |pool.cert   |    Y      =>   C      |
   |deleg.cert  |    Y      =>   C      |

*C= copie

