# GO

* func (w http.ResponseWriter, r *http.Request): template from package
* template.Must: wrapper function for error catching
* template.ParseFiles: parse html

# HTMX

* hx-post="/add-film/": specify the api route
* hx-target="#film-list": specify the element which when receiving the response, that element will be swap with new response data                
* hx-swap="beforeend": by default, the swapping use innerHTML, but it can be changed to append beforeend/afterend/beforebegin 
* hx-indicator="#spinner": specify the element that will have the htmx-request class added to it for the duration of the request, used for waiting spinner