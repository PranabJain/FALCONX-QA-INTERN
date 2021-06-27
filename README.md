# FALCONX-QA-INTERN
Assignment for the recruiment drive for the position of Quantative Analyst Intern

How to run assignment:-
1) Upload the file "FALCON_V3" to jupiter notebook.
2) Restart and Run all Cells(Although you can directly view the results).

Considerations kept while making assignment:-
1)	I was not clear with inherent meaning of side(buy/sell) so I created an additional logic:-
If(amount0_in>0)
Transaction->buy;
Else
Transaction->sell;
So I added an extra column and then appended buy/sell according to the above logic.
Also, I deduced whenever amoun0_in>0; amount1_in is always 0 and same reasoning goes for amount1_in and amoun1_out. So, I think there was need of only two variables (amount_in and amount_out to convey the meaning to user/developer).

2)	Liquidity in Pool: For liquidity in pool, I was not sure if you want reserve USD for the pair or the individual token’s liquidity in every pair. So, I fetched both the above data.


ANALYTICS:-
I have plotted a pie chart of top 10 liquid transaction pairs. This analysis could be beneficial for a trading firm to evaluate performance of various pairs and which trading pair is most poular duirng a specefic period of time.
