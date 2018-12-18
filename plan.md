# Uni C# project

Have to make a piece of software which has genuine usage for my company (ACN), looking to emulate car parking system for offices. 
- choose user type (security/employee)

- for employee, options (starting work/leaving work)

- starting work - enter car registration & ID
- car is "parked". 
- when parking spaces have ran out, choose which car the newly parked car is blocking in (actually happens) 
- thank you! 

- leaving work - enter car registration
- car is "free/blocked". 
- if blocked, user given car registration it is blocked by and told to contact security

- security - can add car registration, check blocked by, notify staff member giving ID (won't actually do anything) 
- repeating menu (add cars, who's parked etc., clear data)
- see all cars parked in list ( and ones blocking ) 
- remove car registrations (person left work without chance to it) 
- clear db (file), day has ended.

# Uni spec

1. It must be Forms based, with appropriate user interaction and input validation.
2. It must demonstrate the use of variables, including constants.
3. It must have an appropriate flow of control, through the use of repetition, and selection.
4. It must be a multi-function application.
5. It must allow users to add, display and edit data.
6. It must demonstrate data persistence through saving / reading data to / from to a file.
7. It must demonstrate your ability to develop application logic, for example through: Mechanisms for ensuring duplicate data cannot be added, Mechanisms for sorting, filtering and displaying data, Mechanisms for ensuring a finite number of data entries can be added, or, Development of a multi-user system (for example a system that provides different functionality for users with different access privileges.)

# Meeting spec 

1. Will start with button for which type of user it is (Security/Employee), using form inputs/outputs/buttons to enter, edit, see and remove data.
2. Variables will be neeeded in program as per usual but CONST will be things like car parking spaces, maximum cars in lot)
3. flow will be controlled by user type selection, giving appropriate options, repeating menu and using data from that "day" - file will be cleared by "security" at the end of the day. 
4. put in cars as parked, check if they're blocked, clear data etc.
5. add cars parked, car parked blocked by, display all parked cars and who's blocked by who, edit cars parked / blocked by
6. file i/o will be used for data
7. will use limited loops and consts to limit data entered. will sort, fitler and display data using i/o methods. multi-user system.
