# django-form-hw1

Watch the video here: https://youtu.be/6oOHlcHkX2U

Below, write out how to create a form in a new views method using any of the classes/models we used today.

In views tab you set a new variable called form,make it request to post meaning users input onto it and its saved. Then make an if statement that asks for validation from another function. it the input proves valid, next what the users input is saved. then return a render (display) of the form with your customized settings 
example from video)
form = FormFunction(request.POST or None)
if form.is_valid():
  form.save ()
return render(request, "products/product_create.html",context)
