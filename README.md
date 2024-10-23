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
