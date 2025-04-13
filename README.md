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
3. Set up your **OpenTyphoon API Key** in a `.env` file by adding:
      ```
      OPENTYPHOON_API_KEY = "Your OpenTyphoon API Key"
      ```
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
3. Set up your **OpenTyphoon API Key and Discord Bot Token** in a `.env` file by adding:
      ```
      OPENTYPHOON_API_KEY = "Your OpenTyphoon API Key"
      DISCORD_BOT_TOKEN = "Your Discord Bot Token"
      ```
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

This project is licensed under the GNU General Public License v3.0 License. See the [LICENSE](LICENSE) file for details.

### Third-Party License Notice & Special Thanks

This repository includes a system prompts inspired by the [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) repository. Special thanks to the contributors of this repository for their valuable work in curating these prompts.

See [`LICENSE.CC0v1`](./LICENSE.CC0v1) for the full license text of the system prompts file.
