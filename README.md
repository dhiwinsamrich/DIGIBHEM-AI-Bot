<h1 align="center">Interactive ChatBot using DialogFlow and DialogFlow CX</h1>
<h2 align="center">Zyra The Flight Assistant </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a3c0e077-547e-4c12-8be9-774a2dd5466e" alt="DigitalBhem" width="800" height="200"/>
</p>

<p align="center">
  <img src="https://seeklogo.com/images/D/dialogflow-logo-0A51D7BA7B-seeklogo.com.png" alt="DialogFlow Logo"/>
  <img src="https://voiceaiconnect.audiocodes.com/hs-fs/hubfs/VoiceAI%20Connect%20Mini%20Site/DialogflowCX-Logo.png?width=650&name=DialogflowCX-Logo.png" alt="DialogFlow CX Logo" />
</p>

<p align="center">Welcome to the DIGIBHEM-AI-Bot repository! This project showcases Zyra, an advanced AI bot developed using DialogFlow CX with cutting-edge Machine Learning capabilities. Zyra is designed to provide seamless interactions, offering a superior user experience for various applications. 🚀</p>

This project is a part of my internship at **Digital Bhem**, where I am honing my skills in AI and Machine Learning to create innovative solutions.

## 🎯 Features

### 🛠️ Flows
1. **Default Start Flow**
   - Initiates the conversation and sets the context for the user interaction.
2. **Address Collection**
   - Gathers user address information accurately and efficiently.
3. **Feedback**
   - Collects feedback from users to improve services.
4. **Waiting Room**
   - Manages user interactions while they wait, providing updates and engaging content.

### 🔍 Intents
Zyra is equipped with 38 well-defined intents to handle a wide range of user interactions. These intents include, but are not limited to:
- Greeting users
- Booking flights
- Managing user profiles
- Providing travel recommendations
- Handling cancellations and changes

### 🗂️ Entity Types
To accurately capture and utilize user data, Zyra uses several entity types:
- **airport-code**: Recognizes and processes airport codes.
- **departure date**: Understands and extracts departure dates.
- **destination city**: Identifies and uses destination cities.
- **flight option**: Handles different flight options.
- **flight type**: Differentiates between various flight types (e.g., one-way, round-trip).
- **frequent flyer account**: Manages frequent flyer account information.
- **origin city**: Captures the origin city of the user.
- **return date**: Processes return dates for round-trip flights.

## 📂 Repository Structure

DIGIBHEM-AI-Bot/
<br> >-- flows/
   <br>&emsp;&emsp;├── default_start_flow.json
   <br>&emsp;&emsp;├── address_collection.json
   <br>&emsp;&emsp;├── feedback.json
   <br>&emsp;&emsp;└── waiting_room.json
<br> >-- intents/
   <br>&emsp;&emsp;├── intent_1.json
   <br>&emsp;&emsp;├── intent_2.json
   <br>&emsp;&emsp;├── ...
   <br>&emsp;&emsp;└── intent_38.json
<br> >-- entities/
   <br>&emsp;&emsp;├── airport_code.json
   <br>&emsp;&emsp;├── departure_date.json
   <br>&emsp;&emsp;├── destination_city.json
   <br>&emsp;&emsp;├── flight_option.json
   <br>&emsp;&emsp;├── flight_type.json
   <br>&emsp;&emsp;├── frequent_flyer_account.json
   <br>&emsp;&emsp;├── origin_city.json
   <br>&emsp;&emsp;└── return_date.json
<br> >-- README.md

## 🚀 Getting Started

Follow these steps to set up and run Zyra on your local machine:

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/DIGIBHEM-AI-Bot.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd DIGIBHEM-AI-Bot
    ```

3. **Import the flows, intents, and entities into DialogFlow CX**
    - Open DialogFlow CX console.
    - Import the JSON files from the `flows`, `intents`, and `entities` directories.

4. **Customize and Train Zyra**
    - Use the DialogFlow CX console to fine-tune the bot according to your specific needs.
    - Train the bot to improve its understanding and response accuracy.

5. **Deploy and Test**
    - Deploy Zyra to your preferred platform (e.g., web, mobile, messaging apps).
    - Test its functionalities to ensure it meets your requirements.

## 🤖 Usage

Zyra is designed to handle various tasks seamlessly. Here are some key interactions:

- **Booking Flights** ✈️
    - Users can inquire about flights, book tickets, and manage their bookings.
- **Collecting Addresses** 📍
    - Zyra efficiently collects and manages user address information.
- **Providing Feedback** 📝
    - Users can provide feedback about their experiences.
- **Waiting Room Management** ⏳
    - Zyra can manage waiting room interactions, keeping users informed and engaged.

## 📈 Project Overview

### Goals
- To create a highly interactive and intelligent chatbot that can handle a variety of user queries and tasks.
- To leverage advanced Machine Learning techniques to improve user experience.
- To integrate seamlessly with various platforms, providing a consistent and reliable service.

### Technologies Used
- **DialogFlow CX**: For designing and managing the bot's conversational flows and intents.
- **Machine Learning**: For enhancing the bot's understanding and response capabilities.
- **Python**: For any additional scripting and backend integrations.

## 💡 Contribution

We welcome contributions to improve Zyra. Here’s how you can help:

1. **Fork the repository**
2. **Create a new branch**
    ```bash
    git checkout -b feature/new-feature
    ```
3. **Make your changes**
4. **Commit your changes**
    ```bash
    git commit -m "Add new feature"
    ```
5. **Push to the branch**
    ```bash
    git push origin feature/new-feature
    ```
6. **Create a Pull Request**

## 📞 Support

For any queries or support, please contact [Dhiwin Samrich](dhiwinsamrichj@gmail.com).

## 🙌 Acknowledgements

Special thanks to the team at **Digital Bhem** for their support and to all contributors who have helped improve Zyra.
