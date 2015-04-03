# neo4j-flask
A microblog application written in Python powered by Flask and Neo4j. Extension of [Flask's microblog tutorial](http://flask.pocoo.org/docs/0.10/tutorial/).

## Tutorial

[Here](http://nicolewhite.github.io/neo4j-flask/)!

## Usage

Make sure [Neo4j](http://neo4j.com/download/) is running first!

**If you're on Neo4j >= 2.2, make sure to set environment variables `NEO4J_USERNAME` and `NEO4J_PASSWORD`
to your username and password, respectively:**

```
export NEO4J_USERNAME=username
export NEO4J_PASSWORD=password
```

Then:

```
git clone https://github.com/nicolewhite/neo4j-flask.git
cd neo4j-flask
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python run.py
```

[http://localhost:5000](http://localhost:5000)
