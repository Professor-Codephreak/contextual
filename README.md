# Contextual

`Contextual` is a Textual-based terminal application that provides an interactive interface for managing configurations, sending messages, and monitoring progress within a command-line environment


contextual aware terminal utterance based on the work by <a href="https://github.com/Web3dGuy/textual-ui-example/tree/main">web3Dguy</a> and <a href="https://gregorylmagnusson.medium.com/pythai-pai-2024-professor-codephreak-mit-licence-b9f6be1c9ef0">Gregory L. Magnusson</a><br />


## Features

- Interactive input fields for ChromaDB Directory, Collection Name, Embedding Model, and Chat Model.
- Radio buttons to select between `Ollama` and `Hugging Face` for embedding and language models.
- Start, Stop, and Send buttons to control operations.
- Progress bar to display progress for ongoing tasks.
- Rich log panel for displaying chat messages and status updates.

## Requirements

- **Python** 3.8 or higher.
- **Textual** library.

## Installation

Follow these steps to install the Textual library and set up `Contextual`.

### Step 1: Clone or Download the Repository

1. Clone the repository or download the `contextual.py` file directly.

```bash
git clone https://github.com/Professor-Codephreak/contextual/
cd contextual
```

Step 2: Create and Activate a Virtual Environment (Optional)

It is recommended to create a virtual environment to manage dependencies.

```bash
python3 -m venv contextual
source contextual/bin/activate  # On Windows, use `venv\Scripts\activate`
```
Step 3: Install Textual

Install the Textual library via pip:

```bash
pip install textual
```
If you plan to develop further or customize the application, you may also install the Textual development tools:

```bash
pip install textual-dev
```

Step 4: Prepare contextual.py

Ensure contextual.py and style.tcss (if needed) are in the same directory.
Step 5: Run the Application

Launch Contextual by running:

```bash
python contextual.py
```

Usage

    Input Fields: Enter information in the fields labeled for ChromaDB Directory, Collection Name, Embedding Model, and Chat Model.
    Embedding and Language Model Types: Use the radio buttons to choose between Ollama and Hugging Face.
    Send Button: Use this to send a message from the TextArea.
    Start/Stop Buttons: Control the start and stop of the main process, updating progress and status in the app.
    Rich Log: Monitor logs and status updates in real time.

Customization

    Modify the styles in style.tcss for customizing the UI appearance
    ├── Set border using a value of the form <bordertype> <color>                
       │     e.g. border: solid red;                                                
       │     e.g. border: dashed #00ee22;                                           
       ├── Valid values for <bordertype> are:                                       
       │   'ascii', 'blank', 'dashed', 'double', 'heavy', 'hidden', 'hkey', 'inner',
       │   'none', 'outer', 'panel', 'round', 'solid', 'tall', 'thick', 'vkey', or  
       │   'wide'                                                                   
       └── Colors can be specified using hex, RGB, or ANSI color names           

Troubleshooting

If you encounter any issues:

    Ensure Python and Textual are correctly installed.
    Check the terminal compatibility, as Textual requires a modern terminal with support for 16.7 million colors.

License

contextual (c) 2024 Professor Codephreak MIT License
