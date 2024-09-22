👋 Hi, I’m @AndreCoutinhoBueno, a data scientist with expertise in agronomy, particularly in the fertilizer market.  
👀 I am interested in collaborating with individuals or companies on any data science projects.  
🌱 I am currently learning about GitHub Pages.  
📫 You can reach me at: andrecoutinhobueno@hotmail.com  
😄 Pronouns: He/Him  
⚡ Fun fact: I love it!  

From my repository [Pricing-Fertilizer](https://andrecoutinhobueno.github.io/Pricing-Fertilizer/), here are some examples where I have applied machine learning and data science concepts:

### Handling Big Data:

Technique: Reading in Chunks

During the extraction of the main zipped file, the technique of reading in chunks was employed.

[Script](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/codes/extra%C3%A7%C3%A3o/Comexstat/IMP_NCM/Baixa_Extrai.ipynb)


Additionally, another script was developed to ensure that updates only require downloading the most recent part of the file, thereby increasing processing speed.

Conclusion:
The technique of reading in chunks provides an efficient solution for handling large ZIP files, significantly reducing memory usage and enhancing the performance and scalability of data processing. This approach enables systems with limited memory to process large volumes of data efficiently and flexibly, avoiding the issues associated with loading entire files into memory.

### Normalization:

Technique: Clustering

Different products traded under the same international commerce code were identified, not only to understand their individual behavior but also to achieve better prediction scores for each one.

An example of product data in this situation is the imports of MAP, which, before the clustering process, appeared as follows:

![MAP without normalization](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/DB/Comexstat/graphs/fertilizers_imports0.png)

The central theorem was not accomplished, characterizing an abnormal distribution of weight in the imports of this product.

After clustering, three groups were identified:

* Very low imports and lower outliers which should be dropped
* A type of MAP that is more expensive, with smaller imports, corresponding to a highly purified product used for foliar spray
* The most common MAP, widely applied in the soil.

![MAP with normalization](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/DB/Comexstat/graphs/fertilizers_imports.png)


### Classification: 
Predicting which set of import characteristics will occur at a given time.

### Regression: 
Determining the quantity, in weight or value, with the highest probability density, as well as the measure of dispersion around it.






















- 👋 Hi, I’m @AndreCoutinhoBueno, a data scientist with expertise in agronomy, especially in the fertilizer market.
- 👀 I’m interested in collaborating with people or companies on any data science projects.
- 🌱 I’m currently learning about GitHub Pages.
- 📫 How to reach me: andrecoutinhobueno@hotmail.com
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I love it!

From my repository [Pricing-Fertilizer](https://andrecoutinhobueno.github.io/Pricing-Fertilizer/), here are some examples where I have applied machine learning and data science concepts:



1. Handling Big Data:

    Technique: Reading in Chunks

    During the extraction of the main zipped file, the technique of reading in chunks was employed.

    [Script](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/codes/extra%C3%A7%C3%A3o/Comexstat/IMP_NCM/Baixa_Extrai.ipynb)

    Additionally, another script was developed to ensure that updates only require downloading the most recent part of the file, thereby increasing processing speed.

    Conclusion:  
    The technique of reading in chunks provides an efficient solution for handling large ZIP files, significantly reducing memory usage and enhancing the performance and scalability of data processing. This approach enables systems with limited memory to process large volumes of data efficiently and flexibly, avoiding the issues associated with loading entire files into memory.  



2. Normalize:

    Techinique:Clustering
    
    Different products traded under the same international commerce code was identifyed, not only to know the individual comportament but also to reach better scores of predictions for each one.

    An exemple of product data in that situation is the imports of MAP which, before the clustering process was like that:

    ![MAP sem normalização](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/DB/Comexstat/graphs/fertilizers_imports0.png)

    The central teorem wasn't be acomplished, caracterizing an unnormal distribuitions of weight in the imports of this product.

    After clusterization, three groups are seen:
    * low outliers which shiould be droped
    * A kind of MAP that is more expensive, with smaller imports, which correspond to high purified produtct used by foliar spray
    * A most comomn MAP, applied in the soil widely.


    ![MAP com normalização](https://github.com/AndreCoutinhoBueno/Pricing-Fertilizer/blob/main/DB/Comexstat/graphs/fertilizers_imports.png)




3. Classification: Predicting which set of import characteristics will occur at a given time.

4. Regression: Determining the quantity, in weight or value, with the highest probability density, as well as the measure of dispersion around it.
