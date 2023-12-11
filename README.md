# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
(fill in your description and goals here)

## Process
#### Step 1
Started by checking out the API documentation and testing out a provided endpoint.
Ran the below GET req via Postman to confirm working data.
http://api.citybik.es/v2/networks?fields=EcoBici,name,company
Went back and hid the client ID as well. Seemed like a risk
JSON(fsq_response) this was really helpful visualize, how much workflow affects efficiency
### (your step 2)

## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

## Challenges 
(discuss challenges you faced in the project)
I couldnt figure out for the life of me why my df was objects or tuples. thanks to larry i found out i had extra commas in my for loop when grabbing the data
ChatGPT: The issue you're facing might be related to the extra commas in your assignment statements. When you use a comma at the end of an assignment, Python creates a tuple instead of a single value. This might result in unexpected behavior, especially when building a list of dictionaries for a DataFrame

## Future Goals
(what would you do if you had more time?)
