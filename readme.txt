What's For Lunch 
1) design a RESTful app with basic html views (minimal styling)
2) Use github \ heroku \ Spring \ hibernate
3) Then write a JavaScript based client \ modify app as needed

Domain Objects

User
  String email
  String password
  List LunchGroups
  List Destinations

LunchGroup
  List of Users

Destinations
  String location
  Date time

LunchPlan
  Owner (user who suggested it)
  LunchGroup
  List of destinations
  boolean votingOpen (can be ended by timer or owner of lunch plan)
  HashMap with username as keys \ value is destination (display users who have voted and totals next to the destination)
** Members of the lunch group should be able to add destinations

Views
login
create account
reset password
my account
  * create lunch groups
  * create destinations
create lunch plan (add lunch group, add destinations) \ sends notification
lunch plan
