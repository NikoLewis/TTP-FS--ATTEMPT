# Data Modeling

###  table relations

* users
   * has one profile


* profiles
      * belongs to one user
      * has many transactions
      * has one portfolio

* transactions
    * has many stocks owned
    * belongs to one profile

* portfolios
       * belongs to one profile
       * has many stocks owned

*  stock owned
      * belongs to many transactions
      * belongs to one portfolio


### tables
1.  users
  * id (PRIMARY)
  * password or password_digest
  * email
  * profile id

* Profile
  * id
  * user id
  * transaction ids
  * portfolio id
  * account balance

* Portfolio
  * id
  * profile id
  * stock id
  * # of stock id owned

* transactions
  * id
  * profile id
  * stock id
  * # purchased
  * price purchased at
  * total cost
  * date
  * time

* stocks
 * id
 * ticker symbol
 * company name
 * latest price
 * opening price
