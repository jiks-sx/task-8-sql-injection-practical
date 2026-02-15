# Identifying Injectable Parameters

Example vulnerable URL:

http://testphp.vulnweb.com/listproducts.php?cat=1

Manual test:

'
1' OR '1'='1

If page behavior changes or error appears → injectable parameter confirmed.
