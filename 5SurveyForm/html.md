```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Survey</title>
  </head>
  <body>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description">Thank you for taking the time to help us improve the platform</p>
    <form id="survey-form">
      <div class="elements">
        <label id="name-label" for="name">Name</label>
        <input id="name" type="text" placeholder="Enter your name" required />
      </div>
      <div class="elements">
        <label id="email-label" for="email">Name</label>
        <input id="email" type="email" placeholder="Enter your Email" required />
      </div>
      <div class="elements">
        <label id="number-label" for="number">Age</label>
        <input id="number" type="number" placeholder="Age" min="13" max="120" required />
      </div>
      <div class="elements">
        <p>Which option best describes your current role?</p>
        <select id="dropdown" name="role" class="form-style" required>
        <option disabled selected value>Select option</option>
        <option value="">Student</option>
        <option value="">Full Time Job</option>
        <option value="">Full Time Learner</option>
        <option value="">Prefer not to say</option>       
        <option value="">Other</option>             
        </select>
      </div>
      <div class="elements">
        <p>Would you recommend freeCodeCamp to a friend?</p>
          <label>
            <input type="radio" name="user-recommend" value="definitely" class="input-radio" checked>Definitely
          </label>
          <label>
            <input type="radio" name="user-recommend" value="maybe" class="input-radio" checked>Maybe
          </label>
          <label>
            <input type="radio" name="user-recommend" value="not sure" class="input-radio" checked>Not sure
          </label>
      </div>
      <div class="elements">
        <p>What is your favorite feature of freeCodeCamp?</p>
          <label>
            <input type="checkbox" name="prefer" value="challenges" class="input-checkbox">Challenges<br>
          </label>
          <label>
            <input type="checkbox" name="prefer" value="projects" class="input-checkbox">Projects<br>
          </label>
          <label>
            <input type="checkbox" name="prefer" value="community" class="input-checkbox">Community<br>
          </label>
          <label>
            <input type="checkbox" name="prefer" value="open-source" class="input-checkbox">Open Source<br>
          </label>
      </div>
      <div class="elements">
        <p>What would you like to see improved? (Check all that apply)</p>
        <label>
          <input type="checkbox" name="prefer" value="frontend-projects" class="input-checkbox">Front-end Projects<br>
        </label>
        <label>
          <input type="checkbox" name="prefer" value="backend-projects" class="input-checkbox">Back-end Projects<br>
        </label>
        <label>
          <input type="checkbox" name="prefer" value="data-visualization" class="input-checkbox">Data Visualization<br>
        </label>
        <label>
          <input type="checkbox" name="prefer" value="challenges" class="input-checkbox">Challenges<br>
        </label>
        <label>
          <input type="checkbox" name="prefer" value="opensource-community" class="input-checkbox">Open Source Community<br>      </label>
      </div>
      <div class="elements">
        <p>Any comments or suggestions?</p>
          <textarea id="comments" class="input-text-area" name="comment" placeholder="Enter your  comments here">
          </textarea>
      </div>
      <div class="elements">
        <button type="submit" id="submit" class="submit-button">Submit</button>
      </div>
    </form>
  </body>
</html>
```