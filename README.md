# eventdb
simple nosql key/value database


Sample USE

from eventdb import EventDB

mydb = EventDB("./mydb.db")

mydb.insert("name" , "McLaurin") #Inserts a Value

mydb.read("name")

'McLaurin'

