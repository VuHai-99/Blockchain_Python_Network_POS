### Overall

Small Project about PoS Blockchain Network using Python.

<!-- GETTING STARTED -->
## ER Diagram


<!-- USAGE EXAMPLES -->
## Usage

1. Running the initial node with prefix genesisPrivateKey
   ```sh
   python Main.py localhost 10001 5000 keys/genesisPrivateKey.pem
   ```
2. Running the second node ( or as many side node as you want ) without prefix PrivateKey. See the connection between initial node with second node.
   ```sh
   python Main.py localhost 10002 5001
   ```
3. Running the third node ( or as many side node as you want ) without prefix PrivateKey. See the connection between initial node with third node.
   ```sh
   python Main.py localhost 10003 5002
   ```
4. Running the Interaction script to execute example transaction
   ```sh
   python Interaction.py
   ```
5. Running the fourth node ( or as many side node as you want ) without prefix PrivateKey. See the connection between initial node with third node and all the previous transaction being updated ( check through API in port 5000 - localhost:5000/blockchain )
   ```sh
   python Main.py localhost 10003 5002
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

