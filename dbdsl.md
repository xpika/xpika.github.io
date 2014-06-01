database haskell dsl
==============
wip 

key value haskell domain specific language

eg. 

```haskell
main = do
  dbFileConnect "mydatabase.db" $ do
    results <- do 
               guard $   isPrime (id user)
                      <> odd (street_number address user)
               return (user (email <> account . balance))
    io $ print results
    add order ( (id product) "shoe-1234" <> quantity (length results)) results
```
