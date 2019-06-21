# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

コメントを解除したことでサイトを開くとき上に文字が表示された

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」
参照　windowが定義されてない


## Chromeデベロッパーツール：Consoleの実行結果

```
Good morning.
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
VM125 main.js:4 Good morning.
index.html:18 おはよう！
index.html:53 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:53
Navigated to http://127.0.0.1:5500/index.html
VM147 main.js:4 Good morning.
index.html:18 おはよう！
index.html:53 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:53
Navigated to http://127.0.0.1:5500/index.html
VM169 main.js:4 Good morning.
index.html:18 おはよう！
index.html:53 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:53
Navigated to http://127.0.0.1:5500/index.html
VM191 main.js:4 Good morning.
index.html:18 おはよう！
index.html:1 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
Navigated to http://127.0.0.1:5500/index.html
VM213 main.js:4 Good morning.
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
VM235 main.js:4 Good morning.
VM235 main.js:7 Neet
index.html:18 おはよう！
for (let i=1; i <= 20; i++){
    console.log(i+"ちんかす山本”）;
VM348:2 Uncaught SyntaxError: Invalid or unexpected token
for (let i=1; i <= 20; i++){
    console.log(i+"ちんかす山本”）;}
VM353:2 Uncaught SyntaxError: Invalid or unexpected token
for (let i = 1; i <= 20; i++){
    console.log(i+"ちんかす山本”);
VM365:2 Uncaught SyntaxError: Invalid or unexpected token
for (let i = 1; i <= 20; i++){
    console.log(i+"ちんかす山本”);}
VM369:2 Uncaught SyntaxError: Invalid or unexpected token
for (let i = 1; i <= 20; i++){
    console.log(i+ "ちんかす山本");
}
VM411:2 1ちんかす山本
VM411:2 2ちんかす山本
VM411:2 3ちんかす山本
VM411:2 4ちんかす山本
VM411:2 5ちんかす山本
VM411:2 6ちんかす山本
VM411:2 7ちんかす山本
VM411:2 8ちんかす山本
VM411:2 9ちんかす山本
VM411:2 10ちんかす山本
VM411:2 11ちんかす山本
VM411:2 12ちんかす山本
VM411:2 13ちんかす山本
VM411:2 14ちんかす山本
VM411:2 15ちんかす山本
VM411:2 16ちんかす山本
VM411:2 17ちんかす山本
VM411:2 18ちんかす山本
VM411:2 19ちんかす山本
VM411:2 20ちんかす山本
undefined
Navigated to http://127.0.0.1:5500/index.html
main.js:4 Good morning.
main.js:7 Neet
index.html:18 おはよう！
```

## ターミナルの実行結果

```
Last login: Fri Jun 21 10:32:40 on ttys001
You have new mail.
-bash: source: No such file or directory
yamamotoyuukinoMacBook-Pro:~ yamamotoyuuki$ cd ~/fujiwara
yamamotoyuukinoMacBook-Pro:fujiwara yamamotoyuuki$ git clone git@github.com:yamamotoyuukii/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
yamamotoyuukinoMacBook-Pro:fujiwara yamamotoyuuki$ cd learning-javascript-01
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$yayamamotyyayayyayyamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
-bash: node: command not found
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ nodebrew ls
-bash: nodebrew: command not found
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ curl -L git.io/nodebrew | perl - setup
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0
100 24634  100 24634    0     0   8284      0  0:00:02  0:00:02 --:--:--  8284
Fetching nodebrew...
Installed nodebrew in $HOME/.nodebrew

========================================
Export a path to nodebrew:

export PATH=$HOME/.nodebrew/current/bin:$PATH
========================================
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.bashrc
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ source ~/.bashrc
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ nodebrew
nodebrew 1.0.1

Usage:
    nodebrew help                         Show this message
    nodebrew install <version>            Download and install <version> (from binary)
    nodebrew compile <version>            Download and install <version> (from source)
    nodebrew install-binary <version>     Alias of `install` (For backward compatibility)
    nodebrew uninstall <version>          Uninstall <version>
    nodebrew use <version>                Use <version>
    nodebrew list                         List installed versions
    nodebrew ls                           Alias for `list`
    nodebrew ls-remote                    List remote versions
    nodebrew ls-all                       List remote and installed versions
    nodebrew alias <key> <value>          Set alias
    nodebrew unalias <key>                Remove alias
    nodebrew clean <version> | all        Remove source file
    nodebrew selfupdate                   Update nodebrew
    nodebrew migrate-package <version>    Install global NPM packages contained in <version> to current version
    nodebrew exec <version> -- <command>  Execute <command> using specified <version>

Example:
    # install
    nodebrew install v8.9.4

    # use a specific version number
    nodebrew use v8.9.4
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ nodebrew ls
v12.4.0

current: v12.4.0
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ nodebrew use latest
use v12.4.0
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
Goodmorning, Node.js!!
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ 
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yamamotoyuuki/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
Goodmorning, Node.js!!
yamamotoyuukinoMacBook-Pro:learning-javascript-01 yamamotoyuuki$ node node-main.js
Goodmorning, Node.js!!
```

