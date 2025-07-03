| Step | Command       | Error Log |
|------|---------------|-----------|
| 1    | `npm install` | <code>npm ERR! code EACCES<br>npm ERR! syscall symlink<br>npm ERR! path ../lib/node<br>npm ERR! errno -13</code> |
| 2    | `npm run build` | <details><summary>Show log</summary><code>ERROR in ./src/index.js<br>Module not found: Can't resolve 'react-dom' in '/workspace/app/src'<br><br>webpack 5.96.0 compiled with 1 error in 6043 ms</code></details> |

