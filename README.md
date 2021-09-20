https://expressjs.com/en/starter/installing.html

Steps taken to produce this demo:

1. Add a directory for the example app
    ```mkdir myapp```

2. Enter that directory
    ```cd myapp```

3. Initialize the project
    ```npm init```

4. Install express
    ```npm install express --save```

5. Add code to index.js:
    ```
    const express = require('express')
    const app = express()
    const port = 3000

    app.get('/', (req, res) => {
    res.send('Hello World!')
    })

    app.listen(port, () => {
    console.log(`Example app listening at http://localhost:${port}`)
    })
    ```

6. Run express
    ```node index.js```

7. Change some code in index.js

8. See if it updates live