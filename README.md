# github-actions-test
let's test/study github actions


repository_dispatch event => when you need to invoke the build manually (a POST request to github api)
see variables: github.token, secrets.something etc

filters:
 'feature/*' -> /feature/xxx .. 
 'feature/**' => /feature/xxx /feature/yyy/zzz ...
