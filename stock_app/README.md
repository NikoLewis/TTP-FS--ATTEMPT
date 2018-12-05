# stock_portfolio_app

web  based  stock  portfolio  app, for the  purpose  of  this  exercise  a  stock  is  simply  an  asset  that  can  be  bought  or  sold(like  a  house)  at  a  price  that  continuously  rises  and  falls  throughout  the  day. Data provided for free by [IEX](https://iextrading.com/developer)IEX. View IEX’s [Terms of Use](https://iextrading.com/api-exhibit-a/).”

## Heroku Deployment


## How to Run App Locally
 1. Clone repo
 2.  use terminal to cd inside repo then use script ### `npm start` to run app i
 3. Open [http://localhost:3000](http://localhost:8000) to view app in the browser.


## Technologies Used
- JavaScript
- jQuery
- Psql
- Express
- Flexbox


## Wire Frames:


## User Stories:

- [ ] *1.*  As  a  user  I  want  to  create  a  new  account  with  my  name,  email,  and  password  sothat  I  can  buy  and  trade  stocks.Default  the  user’s  cash  account  balance  to  $5000.00  USD.A  user  can  only  register  once  with  any  given  email.

- [ ] *2.*  As  a  user  I  want  to  authenticate  via  email  and  password  so  that  I  can  access  myaccount.

- [ ] *3.*  As  a  user  I  want  to  buy  shares  of  stock  at  its  current  price  by  specifying  itsticker  symbol  and  number  of  shares  so  that  I  can  invest.A  user  can  only  buy  whole  number  quantities  of  shares.A  user  can  only  buy  shares  if  they  have  enough  cash  in  their  account  for  agiven  purchase.A  user  can  only  buy  shares  if  the  ticker  symbol  is  valid.

- [ ] *4.*  As  a  user  I  want  to  view  a  list  of  all  transactions  I’ve  made  to  date(trades)  so  thatI  can  perform  an  audit.

- [ ] *5.*  As  a  user  I  want  to  view  a  list  of  all  the  stocks  I  own  along  with  their  currentvalues  so  that  I  can  review  performance.Current  values  should  be  based  on  the  latest  price  and  quantity  owned  for  agiven  stock.

- [ ] *6.*  As  a  user  I’d  like  to  see  the  font  color  of  stock  symbols  and  current  prices  in  myportfolio  change  dynamically  to  indicate  performance.Display  red  when  the  current  price  is  less  than  the  day’s  open  price.Display  grey  when  the  current  price  is  equal  to  the  day’s  open  price.Display  green  when  the  current  price  is  greater  than  the  day’s  open  price.
