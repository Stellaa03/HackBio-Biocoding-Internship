# Stage 0 Task

## Task Instructions
- Form a team of at least 5 people with different programming languages.
- Using either R or Python. (i.e., produce the solution with only one of R and Python.)
- Use any data structure of your choice to organize the following information:
  - Your names
  - Your Slack username
  - Your email
  - Your hobby
  - Your countries
  - Your discipline
  - Your preferred programming language
- **Do not use functions, loops, conditionals or any complex concepts.**
- Your code should include a final print statement that prints the organized output in a logical and understandable way.

## Sample Solution (Python)
Below is an example solution written in Python:

```python
# Organizing the information using a list of dictionaries
team = [
    {
        "Name": "Alice Example",
        "Slack Username": "alice123",
        "Email": "alice@example.com",
        "Hobby": "Reading",
        "Country": "USA",
        "Discipline": "Biology",
        "Preferred Programming Language": "Python"
    },
    {
        "Name": "Bob Sample",
        "Slack Username": "bob456",
        "Email": "bob@example.com",
        "Hobby": "Gaming",
        "Country": "Canada",
        "Discipline": "Chemistry",
        "Preferred Programming Language": "R"
    },
    {
        "Name": "Carol Demo",
        "Slack Username": "carol789",
        "Email": "carol@example.com",
        "Hobby": "Cooking",
        "Country": "UK",
        "Discipline": "Physics",
        "Preferred Programming Language": "Python"
    },
    {
        "Name": "Dave Test",
        "Slack Username": "dave101",
        "Email": "dave@example.com",
        "Hobby": "Cycling",
        "Country": "Australia",
        "Discipline": "Mathematics",
        "Preferred Programming Language": "R"
    },
    {
        "Name": "Eve Demo",
        "Slack Username": "eve202",
        "Email": "eve@example.com",
        "Hobby": "Photography",
        "Country": "Germany",
        "Discipline": "Engineering",
        "Preferred Programming Language": "Python"
    }
]

# Since loops are not allowed, we use a single print statement
print("""
Team Information:

Name: Alice Example, Slack: alice123, Email: alice@example.com, Hobby: Reading, Country: USA, Discipline: Biology, Language: Python
Name: Bob Sample, Slack: bob456, Email: bob@example.com, Hobby: Gaming, Country: Canada, Discipline: Chemistry, Language: R
Name: Carol Demo, Slack: carol789, Email: carol@example.com, Hobby: Cooking, Country: UK, Discipline: Physics, Language: Python
Name: Dave Test, Slack: dave101, Email: dave@example.com, Hobby: Cycling, Country: Australia, Discipline: Mathematics, Language: R
Name: Eve Demo, Slack: eve202, Email: eve@example.com, Hobby: Photography, Country: Germany, Discipline: Engineering, Language: Python
""")
```

## Note
This sample solution is provided as an example. You can modify the team details as needed, but be sure to adhere to the restrictions (no functions, loops, conditionals, or complex concepts).
