-> [Documentation](https://trailheadacademy.salesforce.com/pt-BR/certificate/exam-b2b-commerce-developer-ap---AP-202)

---
# [Exam Guide](https://help.salesforce.com/s/articleView?id=005298777&type=1)
**Checkout Flow Development: 10%**
- *Customize existing **[checkout flows](https://help.salesforce.com/s/articleView?id=platform.flow_ref_elements_b2b_comm_actions_list.htm&type=5)** in order to address the most common customer needs and provide an optimal Storefront experience.*
**Reference Implementations: 15%**
* *Code implementations against the 4 crucial reference implementations used in checkout and payment interfaces with in-depth knowledge of all supported actions.*
**Basic Lightning Web Component Development: 20%**
* *Improve the Storefront experience with enhancements to Lightning Web Components.*
**Advanced Lightning Web Component Development: 30%**
- *Improve the Storefront experience by creating new Lightning Web Components.*
**Data Management: 15%**
- *Manage data intelligently with regard to relationships and integrations as needed to support getting a B2B Storefront established and running.*
**Error Handling and Diagnostics: 10%**
- *Troubleshoot the B2B Commerce system using available tools.*
---
# Salesforce B2B Commerce
***[Salesforce B2B Commerce](https://help.salesforce.com/s/articleView?id=commerce.comm_intro.htm&type=5)*** is a unified platform that helps businesses connect with their customers. Quickly create a customer-friendly B2B store. Take advantage of the store templates to create and customize your store with Experience Builder. Use standard Lightning functionality to set up checkout and payment and configure store settings. Define customer experiences, including search, carts, and checkouts. Import commerce data for accounts, products, price books, and entitlements using a CSV file.
https://trailhead.salesforce.com/content/learn/modules/b2b2c-commerce-basics/b2b2c-explore?trailmix_creator_id=dkoshedzhiyska&trailmix_slug=b2b-commerce-cloud
---
## The Store Object
The Store object represents your website. Think of the Store object as the commerce transaction hub, with transaction elements placed around it like spokes. This framework gives you maximum flexibility for your business requirements.
![[Pasted image 20260618203724.png]]
### Catalogs
Catalogs are the organizational object that enables you to offer products in a store. Each B2B store has a specific catalog of products.

### Categories
Categories play a crucial role in organizing and presenting products to customers. In the Commerce app data model, the Category object represents categories and subcategories. This object controls how customers search for a product.

Categories have a hierarchical structure that typically represents a parent-child relationship. A single catalog includes categories and subcategories up to five levels. Use the tree-like structure to create product groupings that make it easier for customers to navigate and find products that are similar or belong to a specific category.
![[Pasted image 20260618205805.png]]

### Price Books
The Price Book object is where you manage and organize product prices. It plays a crucial role in helping you determine the unit prices of products or services. A price book is required to display prices for opportunities, quotes, and orders.
![[Pasted image 20260618205825.png]]

### Buyers and Buyer Groups
A buyer is an individual or a contact associated with a business or organization that purchases products or services. Buyers are assigned roles, responsibilities, and permissions related to the buying process. A Buyer can be associated with a specific account or buyer group.

A buyer group is a collection of individual buyers who share common characteristics or attributes. Buyer groups are often organized based on factors such as the type of business, industry, or purchasing preferences. Buyer groups simplify the management of buyers with similar needs, so consider collecting buyers with the same roles, entitlement policies, and contract pricing into a buyer group.

### Entitlement Policies
An Entitlement Policy is an object that enforces specific conditions for buyer access to certain products and prices. Buyer groups are linked to entitlement policies. For example, an entitlement policy can specify that a buyer group in a certain tier or with a specific subscription level is entitled to access premium products or services.
![[Pasted image 20260618205855.png]]

## Bringing It Together to Connect the Data
The Commerce data model includes objects, underlying objects, and features that support B2B business functions. With the store as your hub, organize your products into categories that enhance customer navigation and product search.