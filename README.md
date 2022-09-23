# SVT Robotics - Take Home Recruiting Assessment

We have an api that will return a list of robots, as well as their battery level and x,y coordinates in a warehouse. Using this API, we need to display all of these robots in an HTML application.

This is the endpoint to retrieve a list of robots in our robot fleet: https://60c8ed887dafc90017ffbd56.mockapi.io/robots. Note: if that URL doesn't work, a mirror is available here - https://svtrobotics.free.beeceptor.com/robots.

Here is an example robot object:
```
{
    robotId: 58,
    distanceToGoal: 49.9, //Indicates how far the robot is from the load which needs to be moved.
    batteryLevel: 30 //Indicates current battery level of the robot.
}
```

The technologies you choose are largely up to you. Your submission will be assessed for functionality, basic proficiency in HTML and CSS (we highly recommend you use Bootstrap), and code cleanliness and organization.

For bonus, we'd like to know what other features or functionality you would like to implement if you had more time.

Your submission must be a Github repo that we can fork, so basic version control skills are also needed.

### Requirements

1. HTML application that makes an API call to retrieve the robots in our fleet.
2. Robots are displayed in a table, filterable by robotId, and sortable by all attributes.
3. Description of what features, functionality, etc. you would add next and how you would implement them. We want to know what you'd do next (and how you'd do it) if you had more time
4. Use git and GitHub for version control
5. Have fun! We're interested in seeing how you approach the challenge and how you solve problems with code. The goal is for you to be successful, so if you have any questions or something doesn't seem clear don't hesitate to ask. Asking questions and seeking clarification isn't a negative indicator about your skills - it shows you care and that you want to do well. Asking questions is always encouraged at SVT Robotics, and our hiring process is no different.

Deliverables Checklist

1. Functional HTML app written in any language you prefer
2. Repo README has instructions for running the app
3. (BONUS) Repo README has information about what you'd do next
4. Create a new public GitHub repo and upload its url to the link you received in your test invite.