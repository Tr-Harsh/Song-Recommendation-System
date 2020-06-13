# Song-Recommendation-System
Collaborative and Content song recommendation using Graph traversal. Used Neo4j a GUI graph database for storing data as a visual graph.

To make your own song recommender systems, on must have a basic knowledge of database systems, graph theory, big data computing and graph databases.

To make your own songs recommender graph database system, follow the below instructions

1. Install neo4j
For windows, go to the link:  
	https://neo4j.com/download/community-edition/
And click the download button:

For linux or other debain based unix systems, Open the terminal and type the following ccommands
	wget -O - https://debian.neo4j.org/neotechnology.gpg.key | sudo apt-key add -
	echo 'deb https://debian.neo4j.org/repo stable/' | sudo tee /etc/apt/sources.list.d/neo4j.list
	sudo apt-get update

For MAC OS Systems, go to the link:
		https://neo4j.com/download/community-edition/
In other OS download, select the link that relates to your OS version

2. Start the Neo4j server. Then go to any of your browser and in the URL tab go to the link
	localhost:7474

3. The neo4j server page will open. Obeserve the CQL shell prompt. This is where you will type the CQL codes and queries.

4. To create your songs database, copy all the codes in the file "music.txt" and paste it in the CQL prompt and run the commands. You will observe a complete graph of your songs database template created in your system.

5. From the file "queires.docx" pick up any command and run the query in the CQL prompt. The corresponding output will be returned by the server system.

To understand the nodes creation and the commands, anyone can learn CQL from the following sites;
	https://neo4j.com/developer/get-started/
	http://www.tutorialspoint.com/neo4j/
	https://www.youtube.com/channel/UCEtZkI2uCVgfm6xLsPFyaRw
