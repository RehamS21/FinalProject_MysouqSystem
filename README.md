# Musouq  (مُسوق)

A brief description of what this project does and who it's for

The idea of the project is a platform that combines the supplier, the marketer, and the shopper in the same place

So the benefit that each of these users will get is :
* Supplier / Through our platform he/she can get many marketers for his products with a marketing percentage, he determines it for each category of his products, whether they are few or many

* Marketer /The marketer can get a supplier where he markets his products and gets the marketing percentage. As a result, the marketer does not take the trouble of buying products or even looking for warehouses to store them!!!. He can sell the products through our platform, by marketing them only.

* Shopper /The shopper through our platform can get many products through many marketers, as he can get the product he wants at different prices and offers, and every marketer offers discount coupons, which is excellent!!!








## 🔗 Authors
[![@AmalGho](https://img.shields.io/badge/@AmalGho-F7A072?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.github.com/AmalGho)
[![@RehamS21](https://img.shields.io/badge/@RehamS21-F7A072?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.github.com/RehamS21)
[![@RahafMohammed1](https://img.shields.io/badge/@RahafMohammed1-F7A072?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.github.com/RahafMohammed1)




## LOGO

![Logo](https://github.com/AmalGho/MusouqSystem/blob/main/musouq-logo.png)


## Class digram 

![class diagram](https://github.com/AmalGho/MusouqSystem/blob/main/musouq-class.drawio.png)




## Usecase Digram

![usecase diagram](https://github.com/AmalGho/MusouqSystem/blob/main/musouq-usecase.drawio.png)





## Project Details

- First the admin will add the categories of products

- The supplier will add his product according to the categories the admin added, and he will determine the marketing percentage for every category.

- The Marketer will select a suppplier To marketing his products.

- The Marketer should send a marketing request to the supplier 

- The supplier can accept or reject the marketer's request

- If the supplier accepts the marketer's request, then the marketer can choose a product from the supplier's products and do marketing for it otherwise the marketer can't do these steps.

- The marketer can add a discount on specific products

- The marketer can add coupons 

- There is two types of coupon general for all his shoppers or special for special shoppers.

- The marketer can activate and deactivate his coupons.

- The shopper can review all the marketers registered on the site and then review the products and offers they offer

- After the shopper selects a marketer he can make orders and add all products he wants to the order 

- The shopper can apply coupons from his marketer on his order 

- The shopper can view shipping company and their shipping prices and select one of them to ship his order

- The supplier ships the order to the shipping company and changes the status of the order form processing to shipped

- If the order reaches the shopper, he confirms its delivery, and then the order status changes from shipped to delivered.




## Tools 

- intellij IDEA
- MySQL
- Springboot
- postman
- DataGrip




## Springboot Dependency

- Spring Web
- Lombok
- Validation
- Spring Secuirty
- Spring Data JPA
- Mysql Driver




##  Project Presentation
[Project Presentation](https://www.canva.com/design/DAFt-RjJPRg/IViq2TcqG7FPyrOiw3kDjQ/edit?utm_content=DAFt-RjJPRg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)




## API Documentation (postman)
[API Documentation (postman)](https://documenter.getpostman.com/view/28984368/2s9YC1XETh)




## Figma
[Figma](https://www.figma.com/proto/29jAKsedWTK1xrg2r6RjYM/%D9%85%D9%8F%D8%B3%D9%88%D9%82?type=design&node-id=38-240&t=5DlmXUWUksbPqiwl-0&scaling=min-zoom&page-id=0%3A1)



# My Individual work:

# the non - technical work:
- Presenation Slides
- Figma (Design HomePage, Shopper flow process)
- Usecase : Supplier usecase.
- Class diagram, draw the following classes with its relations:
Supplier class
Shopper class
Review Marketer class
Review Order class
make different relations (1:n) (1:1).


# the technical work
- Class: Shopper, Orders, Review Marketer, Review Order.
- Secuirty Configuration
## My endpoints is:
- 1. Marketer gets all shoppers: The marketer can view all shoppers who buy from him 
3. Shopper complete profile: After the shopper registers, he/she must complete the profile
4. Shopper update profile: The shopper can update the profile information 
5. Shopper deletes a profile: The shopper can delete the profile
6. Shopper select marketer: The shopper selects the marketer to view the marketer profile and buy the product from a marketer 
7. Shopper makes order: The shopper creates the order when he/she wants to put products on it 
8. Shopper add product: The shopper adds products to the order 
9. Shoppers get the total amount: The shopper can view the total amount of products selected 
10. Shoppers select the shipping company: The shopper can select the shipping company that will ship his/her order 
11. Shopper completes the order: After selecting the product and determining the shipping company, in this endpoint, the order confirms his/her order, and the system will determine the (order date, and order status “by default processing”) 
12. Admin updated the order status to delivered 
13. Shoppers view all his/her review orders 
14. Shoppers can add a new review order and give the order rate 
15. Shoppers can update the review order information 
16. Shopper can delete his/her review order from the system 
17. Shoppers can view his/her marketer rating 
18. Shoppers can add rates to the marketers 
19. Shoppers can update the rate of the marketers 
20. Shoppers can delete his/her rate to the  marketer 
21. Marketers can view the average his/her shopper's rating  












 
