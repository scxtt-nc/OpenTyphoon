# OpenTyphoon

This project is a AI chatbot that can be run either as a **Discord bot** or locally in the **console**. It uses the **OpenTyphoon API** to handle user interactions and can modify its behavior based on specific keywords.

## Function Used

| Function                            | Present in Script           |
|-------------------------------------|-----------------------------|
| **Input**                           | :white_check_mark:          |
| **Output**                          | :white_check_mark:          |
| **Operator**                        | :x:                         |
| **Condition**                       | :white_check_mark:          |
| **Loop**                            | :white_check_mark:          |
| **Function**                        | :white_check_mark:          |
| **Container**                       | :white_check_mark:          |
| **String Operation**                | :white_check_mark:          |
| **File Handling**                   | :white_check_mark:          |
| **Python Standard Library Modules** | :white_check_mark:          |

## How to Use

### 1. Run Locally in the Console
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your **OpenTyphoon API Key** and add it to the script.
4. Run the script and select option **2** to run the bot locally:
   ```bash
   python main.py
   ```

4. Interact with the bot directly in the console. Type `exit()` to quit.

### 2. Run as a Discord Bot
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your **OpenTyphoon API Key and Discord Bot Token** and add it to the script.
4. Run the script and select option **1**:
   ```bash
   python main.py
   ```
5. The bot will now connect to your Discord server and start responding to user messages.

## API Integration

This chatbot integrates with the **OpenTyphoon API** to provide intelligent responses based on the user's input. It can adapt its behavior depending on specific keywords like `[seo]`, `[ethdev]`, `[terminal]`, etc., which trigger different system prompts.

## Custom Commands

- **Local Bot Commands**:
  - `exit()` to exit the bot.
  - `restart()` to restart the chatbot locally.

- **Discord Bot Command**:
  - `!chat <your_message>`: Sends a message to the bot and receives a response.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

This `README.md` includes the project description, features, usage instructions for both local and Discord bot options, API integration details, and commands. Feel free to adjust it based on your specific requirements!
