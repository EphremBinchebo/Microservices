# Microservices

Product service
The product service manages product information and describes each product with
the following attributes:
• Product ID
• Name
• Weight

Review service
The review service manages product reviews and stores the following information
about each review:
• Product ID
• Review ID
• Author
• Subject
• Content

Recommendation service
The recommendation service manages product recommendations and stores the
following information about each recommendation:
• Product ID
• Recommendation ID
• Author
• Rate
• Content

Product composite service
The product composite service aggregates information from the three core services
and presents information about a product as follows:
• Product information, as described in the product service
• A list of product reviews for the specified product, as described in the review
service
• A list of product recommendations for the specified product, as described in
the recommendation service
