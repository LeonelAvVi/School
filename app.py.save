from flask import Flask

@app.route("/<string:name>")
def hello(name):
	return "<h1>Hola,{}</h1>".format(name)

app = Flask(__name__)
@app.route("/")
def home():
	return redirect("/tu nombre")

if __name__ ==  "__main__":
	app.run()
