# Eternal-Liquidity-Protocol-DAO

Eternal Liquidity Dao Protocol - open source code to enhance EOS ecosystem by increasing liquidity of EOS-based tokens as well as adding deflationary pressure to EOS 

Permanent liquidity AMM trading relays directed by token governed DAO

 1. Governance tokens are created by ongoing dutch style auctions paid in EOS

 2. The EOS received from auctions is utilized to create permanent liquidity pools of various EOS project tokens, liquidity is directed to tokens selected by voting of ELP token holders.

/**For example if there is a 100 ELP token supply and 50 ELP tokens vote for BOX, if the daily auction receives 100 EOS, 50 EOS will be assigned to the BOX/EOS LP, therefore 25 EOS will buyback BOX, 25 EOS will serve as the other half of the relay and both sides will be deposited and locked in the relay permanently. **/

 3. Fees will be taken in terms of EOS on both buy and sell orders, 100% of fees  from the relays will be used to buyback and burn ELP from the ELP/EOS relay, allowing for a sustainable enclosed system. 

How does this benefit EOS?

When creating locked liquidity pools of various tokens, and in the event those tokens rise in price, they will lock even more EOS into the relays. The EOS residing inside the relay will not be able to be withdrawn in the same way as in open liquidity protocols which ‘rent’ liquidity from holders. The EOS will remain locked and will only dissipate if the token in the other half of the relay falls in price. This will create liquidity for EOS projects as well as apply deflationary pressure to the EOS token. 

Anyone can list a token 
(Once a token has accumulated a certain threshold of liquidity from daily auctions with votes, a relay will be opened- mechanism for aquiring non-eos liquidity will need to be developed)

This code will be very useful and can serve as the foundation for other ideas to build upon such as investment DAOs which would allow for the liquidity of individual projects to be shifted/sold at voter discretion, allow custody and open liquidity, and perhaps enable token holders to burn governance tokens to claim back a pro rata share of protoocl owned assets. This particular code implementation focuses on a permanent liquidity as a public good and does not plan to expand to these ideas. 



Relays will use constant product formula pricing algorithm

![image](https://user-images.githubusercontent.com/51843516/147984482-5275aca4-4104-495c-9fb6-0bfdc0e9b10a.png)

![image](https://user-images.githubusercontent.com/51843516/147985649-cb0b0279-83af-40f1-9bdc-068482cc1e0a.png)

![image](https://user-images.githubusercontent.com/51843516/147985828-2b310594-26b7-451c-809e-9397bd21cf77.png)





