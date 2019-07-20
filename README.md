# heroku-julia-sample
A sample project to deploy julia on heroku using [julia-buildpack](https://github.com/Optomatica/heroku-buildpack-julia)

just make sure that `julia app.jl $port` works synchronously and does not quit just after starting about the web server. In Mux.jl, we use `fetch(serve(test,parse(Int,ARGS[1])))`. Make the same test before deploy if you use another framework
