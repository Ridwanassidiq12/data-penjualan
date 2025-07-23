# data-penjualan
Penggabungan Dan Cleaning Data Multi-Sheet ke dalam Satu Laporan Utama :

1.Pull all data from the Customer_Info file into the Main_Ecommerce file on the Order_Data sheet.

2.Pull data from the Product_Catalog file, but first clean the Stock_Unit column, then transfer all the data along with the key to the Main_Ecommerce file on the Order_Data sheet.

3.Pull data from the Order_Records file, but you must fill in the Total_Amount column using information from the Product_Catalog file. Then transfer all the data along with the  key into the Main_Ecommerce file on the Order_Data sheet.

4.Pull data from the Review_Data file, but first clean the Review_Text column based on the Rating, and add an 'Anomaly' column based on whether the review reason is positive or negative but does not match the given
rating. The Anomaly column (with content based on your idea) should highlight any semantic mismatch that implies a specific task or issue.

5.Pull data from the Shipping_Info file based on the key into the Main_Ecommerce file on the Order_Data sheet.
