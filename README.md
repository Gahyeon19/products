# products
<상품>
|기능|매서드|URI|method|view|redirect URI|
|--------|-----|-----|-----|------|-------|
|상품 목록 조회|get|/products?action=list|list()|productList.jsp|
|상품 상세 조회|get|/products?action=info|info()|productInfo.jsp|
|상품 추가 (등록)|get|/products?action=insert|insert()|productInsert.jsp|
|				|post|/products?action=insert|insert()|productInsert.jsp|/products?action=list|
|상품 수정|get|/products?action=update&id=1|update()|productUpdate.jsp|	
|				|post|/products?action=update&id=1|update()|productUpdate.jsp|/products?action=info&id=1|
|상품 삭제|post|/products?action=delete&id=1|delete()|productList.jsp|/products?action=list|


#DB
|id|name|price|maker|date|
|--|----|-----|-------|-------|
|1|Galaxy S10|10000|Samsung|2024-10-10|
|2|Galaxy S23|200000|Samsung|2024-10-15|
|3|Galaxy S24|150000|Samsung|2024-10-18|
|4|IPhone XS|250000|Apple|2024-10-21|
