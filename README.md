 ),
    body: Container(
      padding: EdgeInsets.all(60),
      decoration: BoxDecoration(
          border: Border.all(width: 10,color: Colors.pink)
      ),
      child: Column(
        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
        crossAxisAlignment: CrossAxisAlignment.center,

        children: <Widget> [
          Image.asset("imagens/verdura.png"),
          Padding(padding: EdgeInsets.only(top: 10),
            //ignore: deprecated_member_use
            child: RaisedButton(
              color: Colors.pinkAccent,
              textColor: Colors.black,
              child: Text("DELETAR",
                style: TextStyle(fontSize: 20),
              ),
              onPressed: letrasGeradas,
            ),
          ),
          Image.asset("imagens/futra.png"),
          Padding(padding: EdgeInsets.only(top: 10),
            //ignore: deprecated_member_use
            child: RaisedButton(
              color: Colors.lightBlueAccent,
              textColor: Colors.purple,
              child: Text("DELETAR",
                style: TextStyle(fontSize: 20),
              ),
              onPressed: letrasGeradas,
            ),
          ),
          Image.asset("imagens/planeta.png"),
          Padding(padding: EdgeInsets.only(top: 10),
            //ignore: deprecated_member_use
            child: RaisedButton(
              color: Colors.lightBlueAccent,
              textColor: Colors.purple,
              child: Text("DELETAR",
                style: TextStyle(fontSize: 30),
              ),
              onPressed: letrasGeradas,
            ),
          ),
        ],
      ),
    )
);
} }
