# Utilitários 
Este documento serve como meu dicionário pessoal de implementações. Aqui, catalogo todos os métodos, atributos, operadores e módulos que já explorei e apliquei em projetos. 
## Manipuladores do DOM
### Seleção 
* `document.getElementById()`
* `document.getElementsByTagName()`
	* `HTMLCollection`
* `document.getElementsByClassName()`
	* `HTMLCollection`
* `document.querySelector(seletorCSS)`
* `document.querySelectorAll(seletorCSS)`
	* `NodeList`
* `element.parentElement`
* `element.children` 
	* `HTMLCollection`
* `element.nextSibling`
* `element.previousSibling`

### Propriedade dos elementos 

* `element.innerText`
* `element.textContent`
* `element.innerHTML`
* `element.value`
* `HTMLElementInput.select()`
* `element.style`
* `element.contains(element)`
* `element.dataset`
	* `DOMStringMap`
	* `data-nome` = `dataset.nome`
	* `data-user-id` = `dataset.userId`
* `window.getComputedStyle(elemento)`
* `element.classList`
	* `DOMTokenList`
	* `element.classList.add()`
	* `element.classList.remove()`
	* `element.classList.toggle()`
	* `element.classList.contains()`
* `element.getAttribute()`
* `element.setAttribute()`
* `element.contains()` 

### Criar elementos 
* `parentElement.appendChild(element)`
* `parentElement.append(element1, element2, ...)`
* `parentElement.prepend(element1, element2, ....)`
* `parentElemente.removeChild(element)`
* `element.remove()`
* `document.createElemente()`

### Propriedade da pagina 
* `window.innerWidth`
* `window.innerHeight`
* `window.location`
	* `{href, protocol, hostname, pathname, search, hash} = window.location`
	* `window.location.replace(url)`
	* `window.location.reload([true])`
### Eventos 
* `element.addEventListener("event", callback)`
	* `"keypress"`
	* `"keyup"`
	* `"keydown"`
	* `"submit"`
	* `"input"`
	* `"change"`
	* `.preventDefault()`
	* `event.target`
	* `event.key`
	* `event.type`
* `window.addEventListener("event", callback)`
	* `hashchange`
### Atributos
* `element.id`
* `element.class`
* `element.value`
* `element.checked`
* `element.href`
* `element.src`
* `element.placeholder`
* `element.style.color`

## Métodos String
* `toUpperCase()`
* `toLowerCase()` 
* `trim()` 
* `indexOf(substring)` 
* `slice(startIndex, [endIndex])`
* `replace(search, replacement)`
* `Math.round(num)`
* `Math.floor(num)`
*  `Math.random()`
* `parseInt()` 
* `parseFloat()`
* `.replaceAll()`

## Métodos de array
* `push()`
* `pop()`
* `unshift()` 
* `shift()`
* `concat()`
* `includes(valor, [fromIndex])`
* `indexOf(valor, [fromIndex])`
* `reverse()`
* `join([separador])`
* `slice([inicio], [fim])` 
* `splice(inicio, deleteCount, [item1, item2, ...])` 
* `sort()` 
* `forEach()`
* `map()` 
* `find()` 
* `filter()` 
* `every()`
* `some()`
* `sort()`
* `reduce()`
* `Array.at()`
* `Array.from()`

## Outros método
* `setTimeout()` e `clearTimeout()`
* `setInterval()` e `clearInterval()`
* `alert()`
* `fetch()`
* `new Promise(callback(resolve, reject)).then().catch()`
* `JSON.parse()`
* `JSON.stringfy()`
* `Promise.all()`
* `btoa()` e `atob()`
* `Object.assign(record, attrs)`
* `Promise.any([...])`
* `isNaN()`
 
## Operadores
* `+`, `-`, `*`, `/`, `**`, `%`
* `+=`, `-=`, `*=`. `/=`, `||=`, `&&=`, `??=`
*  `i++`, `++i`, `i--`, `--i`
* `typeof`
* `===` e `!==`
* `>`, `<`, `>=` e `<=`
* `!`, `&&` e `||`
* `condição ? true : false`
* `bind`, `call` ou `apply` ???
* Rest e spread `...`
* `instanceof`
* `?.`
* x `??` y, x `&&` y, x `||` y 


## Módulos de terceiros
* `axios`
	* HTTP request
* `chalk` 
	* Colorir saída terminal
* `chokidar`
	* Monitorar um diretorio
* `lodash`
	* `lodash.debounce` - retorna uma função de debouce
* `caporal` 
	* Gerenciador de argumentos do terminal com manual
* `cookie-session`
	* Lidar com cookie sem seção 
* `multer`
	* Lidar com `multpart/form-data`


## Node modules
* `fs`
	* `fs.readdir(dirname, callback)`
		* `fs.promises.readdir`
	*  `fs.lstat(filename, callback)`
		* `fs.promises.lstat;`
	* `fs.access(dirname, callback)` 
		* `fs.promises.access` 
	* `fs.writeFile(filename, callback)
		* `fs.promises.writeFile
	* `fs.readFile(filename, { encoding: "utf8" })
		* `fs.promises.readFile
* `process`
	* `process.cwd()`
	* `process.args`
* `util`
	* `util.promisify(fs.lstat);`
* `path`
	* `path.join(targetDir, filename)`
* `child_process`
	*  `spawn(programa, params, retorno-terminal)`
* `crypto`
	* `crypto.randomBytes().toString('hex').
	* `crypto.scrypt(password, salt, keylen)`
