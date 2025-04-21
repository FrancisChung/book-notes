# Book Notes: Software Architecture for Developers

## Book Information
- **Title:** Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy
- **Author:** Vlad Khononov
- **Publisher:** Leanpub
- **Publication Year:** 2021
- **URL:** http://leanpub.com/software-architecture-for-developers

## Summary
- **Main Purpose:**  The book is for developers who want to learn Domain Driven Design, but are struggling with the books by Eric Evans and Vaughn 

- **Key Takeaways:**  

## Chapter Summaries

- **Key Concepts:**  
	- **Chapter 1**<br>
      - ***Business Domain*** - A company’s main area of activity. Generally speaking, it’s the service the company provides to its clients.<br><br>
      - ***Subdomain*** -  A subdomain is a fine-grained area of business activity. All of a company’s subdomains form its business domain. <br><br>
        - **Core Subdomain*** - A core subdomain is what a company does differently from its competitors.
          - Example : For Google, the ranking algorithm is a core subdomain 
          - Although the search engine is not a paid service, it serves as the largest display platform for Google Ads.
          - Its ability to provide excellent search results is what drives traffic, and subsequently, it is an important component of the Ads platform.
          - Core subdomains are naturally complex
          - There should be high entry barriers for a company’s core business; it should be hard for competitors to copy or imitate the company’s solution
          - Core subdomains are not necessarily technical.
            - Example : A jewelry maker selling its products online. The online shop is important, but it’s not a core subdomain. The jewelry design is<br><br>
        - ***Generic Subdomain*** - Business activities that all companies are performing in the same way. 
          - Like core subdomains, generic subdomains are generally complex and hard to implement.
          - Do not provide any competitive edge for the company.
          - Example : Most systems need to authenticate and authorize their users. Instead of inventing a proprietary authentication mechanism, it makes more sense to use an existing solution<br><br>
        - ***Supporting Subdomain**** - Support the company’s business, but  do not provide any competitive advantage.
          - Example : An online advertising company whose core subdomains include matching ads to visitors, optimizing the ads’ effectiveness, and minimizing the cost of ad space. However, to achieve success in these areas, the company needs to catalog its creative materials.
          - The creative catalog is essential for implementing the company’s advertising management and serving systems. That makes the content cataloging solution one of the company’s **supporting subdomains**
          - Supporting subdomains are simple
                - Their business logic resembles mostly data entry screens and ETL (extract, transform, load) operations; that is, the so-called CRUD (create, read, update, and delete) interfaces.
   
	
- **Notable Quotes/Excerpts:**  

	- "TBD" - Author TBD
		
 

## Personal Reflections
- TBD


## Overall Rating
- **Content Relevance:** [1–5]  
- **Clarity:** [1–5]  
- **Practical Usefulness:** [1–5]  