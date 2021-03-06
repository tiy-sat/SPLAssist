# SLPAssist - Group Week - MVP (minimally viable product)
# MVP
<ul>
  <li>[x] Deploy to web</li>
    <ul>
      <li>[x] Domain name</li>
      <li>Host site</li>
    </ul>
  <li>[x] SLP role</li>
  <li>[x] Database</li>
  <li>[x] Dashboard</li>
    <ul>
      <li>[x] List of students 5/11/16</li>
        <ul>
          <li>[x] Student</li>
          <ul>
            <li>[x] Name</li>
            <li>[x] Single score</li>
          </ul>  
        </ul>
  </ul>
    <ul>
      <li>[ ] Add student  - accessed on Dashboard 5/12/16</li>
      <ul>
        <li>[ ] Student name</li>
        <li>[ ] Initial score</li>
      </ul>
    </ul>
    <ul>
      <li>[ ] Edit score modal - triggered by button in student area 5/13/16</li>
    </ul>
</ul>
# Stretch
<ul>
  <li>[ ] SLP login</li>
    <ul>
      <li>[ ] Login page</li>
      <li>[ ] Token login (be specific if this is taken on)</li>
    </ul>
  <li>[ ] Search student</li>
  <li>[ ] Multiple scores and data visualization </li>
</ul>

<ul>
  <li> License information</li>
    <ul>
      <h3>Back-end software</h3>
      <li> Python: https://docs.python.org/3/license.html#psf-license-agreement-for-python-release</li>
      <li> psycopg2: http://initd.org/psycopg/license/</li>
      <li> bottle: http://bottlepy.org/docs/dev/index.html</li>
      <h3>Front-end software</h3>
      <li> Javascript: https://www.mozilla.org/en-US/foundation/licensing/</li>
      <li> JQuery: https://www.tldrlegal.com/l/cc0-1.0</li>
      <li> SASS: http://sass-lang.com/documentation/file.MIT-LICENSE.html</li>
      <li> HTML, CSS: https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document</li>
      <li> Browserify: https://github.com/substack/node-browserify/blob/master/LICENSE</li>
      <li> Node JS: https://raw.githubusercontent.com/nodejs/node/master/LICENSE</li>
      <li> Brew: https://github.com/Homebrew/legacy-homebrew/blob/master/LICENSE.txt</li>

    </ul>
</ul>



## Running Python locally (for AJAX dev)
- `$ python3 mybottlecheck.py` (will start local instance of python webserver and tell you what URL to see this in chrome, _should_ be *0.0.0.0:5000*)
- All ajax calls should have a string value of just `/routename` which are listed [here](https://github.com/tiy-sat/SLPAssist/blob/master/mybottlecheck.py#L7) for example `/dashboard`

##To start off  make sure you go to use these sources:
- http://sass-lang.com/install
- http://browserify.org/#install
- https://github.com/substack/watchify make sure to run npm install

##links for http://slpassist-dev.herokuapp.com

http://slpassist-dev.herokuapp.com/login
http://slpassist-dev.herokuapp.com/dashboard
http://slpassist-dev.herokuapp.com/add-student
http://slpassist-dev.herokuapp.com/dashboard/settings
