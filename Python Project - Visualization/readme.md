# 2019 LF Company Business Travel Data Analysis

## Background
L&F Company (L&F) is a multinational corporation which span the entire global supply chain 
for consumer goods including trading, logistics, distribution and retail. Because of the 
business nature, staffs of L&F from different departments travel frequently throughout the year. 
The company spends quite an amount of cost in this area.

To manage cooperate travel in a systematic way such as giving regulation in buying flight ticket 
and litmiting travel expenses, L&F appointed different travel agencies in its operating regions to 
manage cooperate travel matters of the company. These travel agencies expert in Corporate travel management(CTM), 
which is the function of managing a company’s strategic approach to travel, day-to-day operation 
of the corporate travel program, traveler safety and security, and travel and expenses data management. 
In other words, CTM helps L&F to decide on the class of service which employees are allowed to fly, 
negotiates corporate fares/rates with airlines and hotels and determines how the travel budget to be used.
 
## Dataset
This dataset is prepared by L&F Company, contained approximately 31,000 travel application record of L&F 
in 2019 from travel agencies of different operating regions. Data invloved privacy such as name and 
staff number have been removed or replaced by code.

## Interest
I'm interested in two aspects. The first is to figure out the travel pattern of L&F in 2019 by 
4W1H - What(trip purpose), Who(operating group), When(departure date), Where(destination), How(airline). 
The second is to focus on flight expenses such as the top spending operating groups and how much 
did they spend on business trip yearly, and even deeply in which period the operating groups 
spent the most and the expenses they spend on traveling to some popular destination.

## List of Findings
Travel pattern:
- Top 5 frequent traveler(in order): SCS2, LF Asia Direct, SCS3, LF Logistics, SCS4.
- Top 5 travel purpose(in order): Costomer Visit, Quality Control, Supplier Visit, Internal Meeting, Others.
- L&F as a Hong Kong based company, Hong Kong(HKG) is the most frequent travled destination with no surprise.
- Four of the five following most frequent travled destinations are from China including Shanghai(SHA&PVG), 
Shenzhen(SZX) and Guangzhou(CAN), the only exception is Ho Chi Minh City(SGN), which is at the fourth position
- Almost all the popular destination are Asian cities, only London(LHR) and New York(JFK) are the on the top 20 list.
- Cathay Pacific(CX) and Dragonair(KA) are two of the most frequently used carriers, following by China Eastern(MU), 
China Southern(CZ) and Turkish Airlines(TK).
- Number of short haul flight was almost 10 times more than long haul flight
- SCS2 mostly traveled with carriers which are operated in China(MU/CZ)
- Some carriers seems specialized for certain operating groups such as LF Logistics with PR, LF Asia Direct with TK
and SCS series with VN.
- Shangha, Guangzhou and Shenzhen are frequently visited by most of the operating groups, especially SCS2 and LF Products
- Also some destinations are especially popular to certain operating groups such as LF Europre to Hangzhou, 
Meiyume to Singapre and SCS3 to Jarkata.
- Supplier Visit, Customer Visit and QC are the main trip purpose for those frequent travel operating group 
such as SCS2, SCS3, SCS4 and LF Asia Direct, but distribution are slightly different.

Travel expenses:
- Net fare mostly distribute between 100USD and 220USD. There is also a tiny hill between 3,000USD and 5,000USD.
- Premium mostly distributebetween 30USD and 100USD. The highest in 2019 is about 14,000USD.
- Both Discount and Premium have a positive correlation with Net Fare. 
- Discount has a weak positive correlation (0.34) with Net Fare, which is mostly come from SCS2, and partly from 
LF Logistics and LF Asia Direct.

- Premium has a high positive correlation(0.88) with Net Fare, while FG, SCS3 and LF Asia Direct contribute the most.
- Top 5 spending operating group(in order): LF Asia Direct, SCS2, SCS3, LF Logitics, FG
- Top 5 destinations with most expenses(in order): Hong Kong, Shanghai, New York, London, Los Angeles
- Top 5 carriers with most expenses(in order): CX, KA, AA, MU, CZ
- Top 5 overpay operating group(in order): FG, LF Asia Direct, SCS2, LF Logistics, LF Products
- Except FG, the average spending of the top 10 spending operating groups are quite close.
- Average premium of FG was much higher than the other operating groups, which means, the group had high average spending,
received very less discount, but also overpay a lot.
- FG is a big fan of CX, it spent far more than other operating groups on the carrier, following by SCS3 and LF Asia Direct.
- FG, SCS3 and LF Asia Direct are also the three operating groups who spent most on long haul flight.
- LF Asia Direct and SCS3 show a similar pattern on travel expenses by month of year - spent especially more on 
long haul flight in the second half of the year.
- LF Logistics and SCS2 focus on business in Asia heavily as their expenses on short haul flight are higher than 
on long haul flight throughout the year.

## Key Insights for Presentation
For the presentation, I focus on just the travel pattern and expenses of operating groups. Other variables such as
destination and carrier are mentioned but they are not the focal point here and just serve for discovering the 
travel pattern of those frequent travel operating groups. Also discount is almost not mentioned in the presentation 
since I found that it is too random and the relationship with net fare is not very close.

Since travel pattern and travel expenses are quite different things so I divided the presentation into two partly
just like the list of finding above and the listing of visualization is slightly different with the exploratory analysis.
Firstly I present the travel frequency of different variables to give some basic concepts and high level insight 
to the audience of what kind of features and names will appear oftenly in the following slides. Then we will discuss about 
the popular destinations and favored carriers of the operating groups to see any interesting combination there. 
For cooperate travel agencies, it is very important to know the travel habit of different operating groups in order to
set up travel policies and bargain discount with airlines. In the second part, we will also have a big picture with 
a distribution of L&F travel expenses and overpay in 2019. Then we take a deeper look to flight expenses of different
operating groups. In this steps, you will see the difference of frequency of travel and travel expenses. Some groups
are obviously traveled not much but with huge spending. The following is more like a comparison. I discuss about which 
operating groups are potential danders for L&F finance by looking at which operating groups contributed the rise of 
premium the most and received less discount than others. Then I add destinations and carriers to the expenses charts
to see any combination would make higher expenses. Finally, I put the operation group's expenses chart by monthly to see 
any trend of their spending.

## Reference
Thanks to the following pages to help me in solving tasks in the project:

https://stackoverflow.com/
https://www.geeksforgeeks.org/
https://www.kite.com/python
https://www.twblogs.net/c/5b7abdbf2b7177392c96b93c/
https://www.w3schools.com/python/


These sites bisically solve all the difficulties. Awesome! 

## Disclaimer
This project and related data is only for educational purpose and will not be posted anywhere. 
There will be no other readers or users of my data or project analysis beyond the Udacity instructors and reviewers.