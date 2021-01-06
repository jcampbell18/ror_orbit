# Orbit

## Summary

1. The ability to add a new team member:
    1. First Name
    2. Surname
    3. Department
    4. Job Role
    5. Team
    
2. View/Show all team members

3. The ability to leave reviews/feedback for a team member
    1. Grade
    2. Content
    3. User_ID
    
4. View/Show all reviews/feedback

5. The ability to add areas of sucess as defined by client
    1. Area 1: Project Delivery
    2. Area 2: Communications
    3. Area 3: Training
    4. Area 4: Objectives
    5. Area 5: Resourcing

6. View/Show all client areas of success

7. The ability to view performance metrics

## Tips

### WSL

#### Heroku

- Installation
   - `curl https://cli-assets.heroku.com/install.sh | sh`
   
- Credentials
   - `heroku login`
   
- Create
   - `heroku create`
      - secret-peak-64851
   - `git push heroku main`
      - https://secret-peak-64851.herokuapp.com/

## Tutorial

`rails new ror_orbit`
`rails g controller HtmlPages home help`