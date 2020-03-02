Возвращает идентификатор документа по его alias
```
string getIdFromAlias(string $alias);
```
**$alias** - псевдоним документа

### Пример
```
	$id = $modx->getIdFromAlias('folder/folder/doc')
	//id документа doc.html
```
