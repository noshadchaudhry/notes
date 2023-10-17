
### 2.4-binding-options-and-paging
Using Paged Templates (Pagination)
1. Add an options object as Arg3 to .loadTemplate()
 - Use eg slideshow code below
```
$("#ContainerId1").loadTemplate("htmlFilePath.html", data, optionalOptionsObj);

var optionalOptionsObj = {
	paged: true,
	pageNo: 1, // Current page to render.
	elemPerPage: 5
}
```
 - Or use eg .html file used code below.
```
$("#container").loadTemplate($("#itemTemplate"), data["employees"],
	{paged: true, pageNo: pageNo, elemPerPage: 1}
);
```
2. Create an HTML button `<button id="prevPage">Previous</button>`
 - Create an event listener for the button that will call a custom func (w u have to create as well) called we Instructors was renderTemplates(templateData, --curPage);
3. idk
4. odk
