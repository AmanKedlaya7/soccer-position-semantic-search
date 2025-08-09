# Soccer Position Semantic Search

## Overview
This Python project uses SentenceTransformers to create a semantic search tool for soccer position descriptions. Users can input natural language questions about soccer roles, and the system returns the most relevant position descriptions by comparing embeddings with cosine similarity. It helps coaches, analysts, and fans quickly understand specific soccer position roles.

## Installation
Make sure Python is installed on your machine.  
Install the required packages:  
- `sentence-transformers` for semantic embeddings  
- `torch` for tensor operations and similarity calculations  

You can install them with:  
`pip install sentence-transformers torch`

## Usage
Run the script `soccer_position_search.py`.  
When prompted, type a question about any soccer position (e.g., "What does a central defensive midfielder do?").  
The program will display the top 3 matching position descriptions with similarity scores.  
Type `exit` to quit.

## Example Queries
- What is the role of a goalkeeper?  
- Who creates chances for the striker?.  
- Which role combines recovery, wide coverage, and attacking support during transitions on the flank?  
- What responsibilities does a central attacking midfielder have?

## Dataset
The project uses detailed textual descriptions for 11 common soccer positions, ranging from Goalkeeper (GK) to Striker (ST).

