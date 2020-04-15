## node.js , npm 설치

## create-react-app

npm, node를 설치한 후에는 본격적으로 react app을 생성한다.

~~~ 
npm install -g create-react-app
~~~ 

위 명령어를 실행하면 많은 양의 파일과 폴더들이 해당 디렉토리에 설치된다. 

이제 module을 설치했으니 설치한 module create-react-app을 통하여 react project를 설치해보자. 

~~~
create-react-app project_name
~~~

create-react-app 명령어 뒤에는 본인이 진행하는 project의 이름을 넣어주면 된다. 

프로젝트 생성에 성공하면 아래와 같은 문구가 보이게 될 것이다. 

~~~
Success! Created start at /Users/bagminseo/Desktop/coding/react/start/start
Inside that directory, you can run several commands:

  yarn start
    Starts the development server.

  yarn build
    Bundles the app into static files for production.

  yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd start
  yarn start

Happy hacking!
~~~

필자는 yarn이 나오지만, npm이 나오는 경우도 많이 있을 것이다. 사실, 둘 중 어떤 것을 사용,선택해도 괜찮다. 

지금까지의 단계를 마무리 하면 총 3개의 폴더가 설치됨을 알 수 있다. 
~~~
directory
    |
    |
    |----- node_modules
    |
    |----- public
    |       |
    |       |-------- favicon.ico
    |       |
    |       |-------- index.html
    |       |
    |       |-------- logo192.png
    |       |
    |       |-------- logo512.png
    |       |
    |       |-------- manifest.json
    |       |
    |       |-------- robots.txt
    |
    |----- src
    |       |
    |       |-------- App.css
    |       |
    |       |-------- App.js
    |       |
    |       |-------- App.test.js
    |       |
    |       |-------- index.css
    |       |
    |       |-------- index.js
    |       |
    |       |-------- logo.svg
    |       |
    |       |-------- serviceWorker.js
    |       |
    |       |-------- setupTests.js
    |
    |----- .gitignore
    |
    |----- package.json
    |
    |----- README.md
    |
    |----- yarn.lock
~~~

다음으로는 앞서 보였던 명령어 중 npm start (혹은 yarn start)를 실행해준다. 실행을 하게 되면 아래와 같은 문구와 함께 웹 페이지가 실행되는 것을 볼 수 있을 것이다. 

~~~
Compiled successfully!

You can now view start in the browser.

  Local:            http://localhost:3000/
  On Your Network:  http://172.30.1.46:3000/

Note that the development build is not optimized.
To create a production build, use yarn build.
~~~

사진 첨부 

위의 각 폴더가 어떤 역할을 하는지 정확하게 설명하는 것은 마지막 목록인 부록에 넣어놓을 것이다. 