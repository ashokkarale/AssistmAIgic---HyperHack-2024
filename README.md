# AssistmAIgic
![image](https://github.com/user-attachments/assets/c02c6c87-ee98-48c3-a1fd-d799448723b4)

## Overview

AssistmAIgic is an AI-driven solution designed to automate and enhance the email handling process for customer support teams. By leveraging advanced AI capabilities, it ensures efficient, accurate, and high-quality communication with customers across multiple languages.

## Features

- **Continuous Email Monitoring**: Constantly monitors the support team's inbox for new emails.
- **Multilingual Translation**: Detects and translates non-English emails into English for internal processing.
- **Email Summarization**: Provides concise summaries of email content.
- **Contextual Understanding**: Analyzes the context of emails to generate precise responses.
- **Human Validation**: Allows support agents to review, edit, and approve drafted responses.
- **Automated Reply**: Sends responses in the original language of the received email.

## Benefits

- **Enhanced Efficiency**: Reduces the time and effort required for email handling.
- **Accuracy**: Ensures high accuracy in language detection, translation, and response generation.
- **Consistency**: Maintains consistent communication, reducing the risk of errors.
- **Scalability**: Easily scales to handle increasing volumes of emails.
- **Customer Satisfaction**: Improves customer satisfaction through timely and relevant responses.
- **Agent Empowerment**: Reduces cognitive load on support agents, preventing burnout and improving job satisfaction.

## Prerequisits
Active UiPath [Pro Trail](https://cloud.uipath.com/portal_/register?subscriptionPlan=trial) license
## Components
### Integrations Service Connectors
1. UiPath GenAI Activities
2. Microsoft Outlook 365
   
![image](https://github.com/user-attachments/assets/39b73ece-0756-40fd-9579-900233dd831c)

### Automations
1. Email_Processing_Performer
2. GetRepliedMailMessageId
3. MarkEmailActioned
4. AM_Mailbox_Watchman
5. Language_Translator
6. Content_Generation
7. Rewrite_Content
8. SendAcknowledgement

![image](https://github.com/user-attachments/assets/87229ecf-137c-4e18-a251-995cabf95342)

### Data Services
1. AM_Emails
2. LanguageBase

### App
1. AssistmAIgic

## Installation
### Context Grounding
Follow the steps in below animation to generate Context grounding Index

![Setup Context Grounding](https://github.com/user-attachments/assets/6ee1c2fc-20d9-405a-864a-28ae518e9bda)

### Import Entities
Follow the steps in below animation to import entities in Data Services

![Import Entities](https://github.com/user-attachments/assets/a8f8b0c8-9513-4c25-b70b-161a29585e37)

### Integrations Service Connectors
Setup below listed Integrations Service Connectors
1. UiPath GenAI Activities
   **Specific settings**: Nothing
2. Microsoft Outlook 365
   **Specific settings**: Nothing for now. We will be setting a trigger in upcoming step.
   
### Automations
Import, verify no error in the code due to enviornment change and publish the Automations to the UiPath Orchestrator Folder. Follow these steps:

![Import   Publish](https://github.com/user-attachments/assets/fc011213-bbf6-41e1-83cc-64dbba0ca6ec)

_If Any error in any code, check iof previous steps are followed correctly for Integration Service connections, Importing entity etc._
   


