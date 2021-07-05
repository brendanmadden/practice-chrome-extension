getElementbyID()

.innerText (not as good as .textContent)

.textContent

.innerHTML

- include and set the contents of an HTML element with JS

addEventListener()

```javascript
const inputBtn = document.getElementById("input-btn");

inputBtn.addEventListener("click", function () {
  myLeads.push(inputEl.value);
  console.log(myLeads);
});
```

createElement()

append()

### DOM manipulation has a COST

template strings/string literals = backticks - `

created my first JSON object for deploying chrome extension

learned about working with localStorage

- localStorage.setItem("Key", "Value");
- localStorage.getItem("Key");
- localStorage.clear();

* Key and Value need to be strings

JSON.stringify() turn to string

JSON.parse() - turn into not string
