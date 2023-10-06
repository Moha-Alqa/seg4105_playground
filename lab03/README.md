# Identification:
### Name: Mohammad ALqahtani
### Student ID: 300249098

# **Pitch: Shop-Centric Display for the Weed Delivery Website**

## **Problem**
The current website design displays all products on a single page without any differentiation regarding their origin or provider. Feedback indicates that customers prefer to purchase from trusted providers based on prior experiences. Not differentiating between stores leads to ambiguity and may prevent customers from making informed decisions. A majority of customers prefer to purchase from specific providers due to previous satisfactory experiences or perceived quality. Providers are also seeking better visibility and a dedicated space for promotions.

### *Overwhelming Navigation Experience*
The current layout, which groups all products together, overwhelms customers. They're met with a barrage of options without any clear organization, making it challenging to differentiate products based on their trusted sources.

### *Lack of Brand Loyalty Recognition*
Many customers return to purchase based on prior satisfactory experiences with specific providers. The current design does not cater to this preference, causing potential friction in the buying process. This oversight may deter repeat purchases.

### *Impaired Quality Assurance and Feedback*
When a customer isn't satisfied with a product, the present design doesn't allow them to easily identify its source. This complicates their ability to provide feedback or seek alternatives from other trusted providers. On the other hand, when they're pleased with a product, they face hurdles in exploring more options from the same trusted provider.

### *Missed Personalized Experience*
By not highlighting trusted providers or giving options to bookmark or "follow" certain providers, the platform misses out on offering a personalized shopping experience. This can lead to reduced engagement and decreased time spent on the platform.

### *Provider Recognition*
From a business perspective, providers, who are essentially the backbone of this platform, are not given due prominence. They are relegated to the background, with only their products taking the forefront. This lack of recognition can demotivate providers from continuing their association with the platform or from actively promoting their presence on it.


## **Appetite**
We're looking to implement this feature within a 6-week cycle. The focus is to streamline the customer's shopping experience by prioritizing provider recognition.

Within these 6 weeks, our primary goal is to:

1. Design: Spend the first week on design mock-ups and get feedback on user experience and provider interfaces.
2. Backend Development: Dedicate two weeks to developing the necessary database structures, APIs, and other backend components to support the new feature.
3. Frontend Development: Dedicate another two weeks for the frontend - creating the provider cards, detailed pages, and ensuring mobile responsiveness.
4. Testing and Iteration: Use the last week for testing, getting feedback, making necessary changes, and preparing for launch.


## **Solution**
Introduce a shop-centric layout, taking inspiration from popular food delivery apps. The main page will now spotlight different provider shops, making them the top-level category instead of individual weed strains.

### *Key Components of the Solution:*

1. **Provider Shop Display**:
   - **Homepage** will show tiles/cards for different weed shops featuring:
     * Shop logo
     * Shop name
     * Brief description or tagline
     * Average rating (if available)

2. **Shop-specific Pages**:
   - Dedicated page for each shop, showcasing:
     * All weed strains offered with descriptions, prices, and images.
     * Shop history, mission, or other relevant information.
     * Customer reviews/ratings for that shop.

3. **Flexible Shop Management for Providers**:
   - Providers get a dashboard or interface to:
     * Modify their shop page.
     * Add or remove strains.
     * Respond to customer reviews (if such a system exists).

    
## **Rabbit Holes**:
* Customization Features: Diving too deep into allowing providers to customize every aspect of their page can lead us astray. We need to set clear limits on customization options.

* Rating System Complexity: We aim for a simple rating system based on user feedback. Avoiding over-complicating it with too many parameters is essential.

* Advanced Provider Analytics: While it would be useful to give providers insights into their product performance and customer engagement, developing a detailed analytics system could consume a significant portion of our 6-week cycle. We should avoid diving into this.

* Multiple Design Iterations: While it's essential to achieve a good design, spending too much time iterating on design choices can delay the development phase. Set clear feedback loops with design teams to avoid this.

* Over-Engineering the Backend: Given our time frame, we should avoid building complex backend structures that anticipate future requirements. Focus on what's essential for this feature rollout.

## **No Gos**:
* Live Chat Feature: Introducing a real-time chat system involves a lot of complexities ranging from backend infrastructure to frontend user experience. This is out of scope for our current cycle.

* Integrated Marketing Tools: Building tools for providers to run marketing campaigns, like discount systems or loyalty programs, will be a considerable task. It's best tackled in a separate cycle.

* Multi-language Support: If the platform operates in regions with multiple languages, adding multi-language support for provider pages might seem beneficial. However, this introduces complexities in design, backend management, and potential translation costs. It won't be part of this iteration.


## **Benefits/Intended Outcomes**:

- **For Customers**:
  - Easier identification of products from trusted providers.
  - More consistent quality experiences.
  - Informed decisions when trying new providers.

- **For Providers**:
  - Enhanced brand visibility and promotion.
  - Direct control over their shop's representation and product listings.
  
- **For the Platform**:
  - Improved user experience potentially leading to increased user retention and sales.
  - Strengthened relationships with providers through better visibility.


## **Constraints/Risks**:

- **UI Overhaul**: Implementing this change may need a significant frontend redesign.
  
- **Provider Engagement**: Providers must be introduced and familiarized with this new system.
  
- **Performance Issues**: The need for performance optimization becomes pivotal with each shop having its page and a potential abundance of products.


## **Next Steps**

1. **Prototype Design**: Create a visual representation of the new main page and individual shop pages.
2. **Provider Feedback Loop**: Engage with some trusted providers for feedback on the new design and understand their needs for the shop management tool.
3. **Development & Testing**: Start the development phase with an emphasis on the core features before moving to provider management tools. Extensive testing, especially around user experience and performance, is paramount.
