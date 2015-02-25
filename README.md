#### Modeling Practice

bundle

rake db:create db:migrate db:seed

Data model: Look at Schema

No need to create migrations or alter the schema.

###### Stories

- The last dev team left this app mid build. It is a review website for products and companies.

- Don't worry about Edit pages.

- The Authentication/Session controller is very basic with no password for authentication. Don't worry about this. It is there to add the current_user's ID to the review they are writing.












- The last devs wrote no Validations. We need to add Validations on Product, ProductReview and CompanyReview:

-  Product MUST have a company_id.

-  ProductReview MUST have  title, description, product_id, user_id and a rating.

-  CompanyReview MUST have title, description, company_id,  user_id and   rating.
