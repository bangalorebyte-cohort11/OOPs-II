# OOPs-II
Inheritance

Resources:

  - To revisit inheritance, please read chapter 18 of Think Python.
  - The logic gate visuals are in the same powerpoint as used yesterday in OOPs -I.
  - To revisit decorators please look at section 11.3.6 in Core Python. 
  
Exercises: 

1) Complete the LogicGate problem. Ensure that you get the correct response to the following sequences:  
    
    + Two And Gates --> One OR Gate --> Not Gate
    + Four And Gates --> Two OR Gate ---> Two Note Gate --> One OR Gate
    
2) **Stock Reports**. A block of publicly traded stock has a variety of attributes, we'll look at a few of them. A stock has a ticker symbol and a company name. Create a simple dict with ticker symbols and company names.

For example:

```stockDict = { 'GM': 'General Motors', 
 'CAT':'Caterpillar', 'EK':"Eastman Kodak" }
 ```
 
Create a simple list of blocks of stock. These could be tuples with ticker symbols, prices, dates and number of shares. For example:

```
purchases = [ ( 'GE', 100, '10-sep-2001', 48 ), 
 ( 'CAT', 100, '1-apr-1999', 24 ), 
 ( 'GE', 200, '1-jul-1998', 56 ) ]
 ```
 
Create a purchase history report that computes the full purchase price (shares times dollars) for each block of stock and uses the stockDict to look up the full company name. This is the basic relational database join algorithm between two tables.

Create a second purchase summary that which accumulates total investment by ticker symbol. In the above sample data, there are two blocks of GE. These can easily be combined by creating a dict where the key is the ticker and the value is the list of blocks purchased. The program makes one pass through the data to create the dict. A pass through the dict can then create a report showing each ticker symbol and all blocks of stock.

3) Complete the database challange from yesterday. 
