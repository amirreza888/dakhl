/submit/expense/
    Post , return a json
    input :date (optinal), text , amount , user
    output : status:ok
    
    
/submit/income/
    Post , return a json
    input :date (optinal), text , amount , user
    output : status:ok
    
    
    
 /accounts/register/
    step1:
        POST
        input: username, email, password
        output: status: ok
    step2:
        GET
        input: email, code
        
 /query/generalstat/
    POST, return a json
    input: fromdate(optional), todate(optional), token
    output: json from some general stats related to this user 
    