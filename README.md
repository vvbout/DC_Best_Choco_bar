# FINDING THE BEST CHOCOLATE BARS
A specialty foods import company wants to expand into gourmet chocolate bars. There is a demand:
1. to research the market
2. to inform the initial approach to potential suppliers

## Project task:
* To explore if the chocolate bars with the highest ratings share any characteristics that could help to narrow the search for suppliers (e.g., cacao percentage, bean country of origin, etc.)
* To create a report to summarize the research

Data preparation, EDA, data visualisation

**Language:** Python

**Libraries:** Pandas, Numpy, Matplotlib, Seaborn

## Conclusions:
The analysis of data based on chocolate products Review & Rating (2006 - 2021) allow the following initial approach to potential suppliers:

1. The market offers high rating manufacturers in all regions (USA, Canada, Latin America, Australia, Europe); the final choice depends on the marketing strategy: to offer local product or to offer something exotic:
>
>IF USA: Zokoko (avg rating 3.875), Patric (avg rating 3.792), Kah Kow (avg rating 3.75)
>
>IF Australia: Matale (avg rating 3.813)
>
>IF Latin America: Nikoa / Ecuador (avg rating 3.75), Cuna de Piedra / Mexico (avg rating 3.75)
>
>IF Europe: Ocelot / Scotland (avg rating 3.875), Idilio (Felchlin) / Switzerland (avg rating 3.775), Utopick / Spain (avg rating 3.75)
>
are recommended to be contacted first.

2. To meet the customer "high quality" expectations the product should possess the following characteristics:
>
> **cocoa content** - 70% is recommended
> 
> **number of ingredients** - in average 3 ingredients meet the customer expectations: Beans (B), Sugar (S), Cocoa Butter (C); Lecitin (L) may be included, may be not, its presence does not influence the top ratings
> 
> **bean origin** - we recommend the double approach, concidering ratings & market volumes; the recommended list is: Vietnam, Papua New Guinea, Madagascar, Brazil, Guatemala, Nicaragua, Trinidad, Tanzania, Beliz; beans imported from these countries belong both to TOP20 in ratings & TOP20 in frquency that gives the feeling of reliability and chance to negotiate the best price offer
>
3. To make the final choices in favor of some products it is recommended to run tastings and to check if the custemer reviews contain key success words:
> cocoa
> fruit
> nutty
> creamy
> rich
