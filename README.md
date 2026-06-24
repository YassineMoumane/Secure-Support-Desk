a small desktop application called Secure Support Desk to help a
company manage cybersecurity-related support tickets. The company receives daily requests such
as suspicious logins, malware alerts, VPN issues, and account creation requests, and these must be
tracked in an organized way. Each ticket has key information such as an ID, type, priority, status,
department, assignee, date, and tags, and the data is stored in a CSV file so it can be reused
between sessions. Your application will load the CSV file, display tickets in a simple interface, and
let users work with the data without editing the CSV manually. The interface will allow searching,
filtering by status and priority, and sorting to quickly find urgent items. In later steps, the user will
be able to create new tickets and save changes back to the CSV file. Internally, the project will
gradually move from working with raw dictionaries to using a clean Ticket class, so the code
becomes easier to understand and maintain. The goal is to practice real-world programming habits:
organizing data, reusing functions from earlier work, and connecting Python logic to a graphical
interface. By the end, you will have a functional mini tool similar to what an IT or security team
could use to track incidents and requests.
