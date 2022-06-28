# github-actions-test
let's test/study github actions


repository_dispatch event => when you need to invoke the build manually (a POST request to github api)
see variables: github.token, secrets.something etc

filters:
 'feature/*' -> /feature/xxx .. 
 'feature/**' => /feature/xxx /feature/yyy/zzz ...


functions
${{ contains('hello', 'll') }}
${{ toJson('something') }}
${{ format('hi {0} {1}', 'qqq', 'bbb') }}


instead of container use services (and docker-compose syntax) to run multiple containers


actions/cache
actions/upload-artifact


custom js actions
custom docker actions

see github actions marketplace
