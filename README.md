# ARIN 121 Assignment 3 — AI Travel Planner

## Project Overview
This AI travel planner helps travellers create personalized travel itineraries and compare potential destinations based on their budget, interests, trip duration, and travel preferences.

This project extends the Assignment 2 travel planner by incorporating conversational techniques from Lecture 9 and version control practices from Lecture 10.

## Supported Activities

### 1. Create a Personalized Travel Itinerary
The assistant collects relevant trip information and generates a personalized day-by-day itinerary.

Features include:
- Destination disambiguation.
- Confirmation of assumptions and trip scope.
- Budget-aware cost estimates and savings suggestions.
- Personalized travel pace.
- Travel-time awareness and activity grouping.

### 2. Compare Travel Destinations
The assistant helps travellers compare two or three potential destinations through a structured multi-turn interaction.

The assistant:
- Collects potential destinations and travel priorities.
- Compares advantages, disadvantages, estimated costs, and suitability.
- Provides a preliminary recommendation.
- Asks about remaining concerns.
- Refines its recommendation using additional information.

## Menu and Conversation Navigation
The assistant displays a menu when the traveller has not clearly selected an activity.

Travellers can select an activity using:
- A menu number.
- An activity name.
- A request expressed in their own words.

Travellers can switch activities at any point. The assistant carries forward relevant information, including budget, duration, interests, and travel preferences.

The assistant also handles side questions, corrections, and misunderstandings.

## How to Use
1. Open Google AI Studio Playground.
2. Copy the complete contents of system-prompt.md.
3. Paste the prompt into the System instructions field.
4. Start a conversation with the assistant.
5. Select an activity or describe your travel request.
6. Respond to the assistant's questions to receive personalized travel assistance.

## Repository Files
- system-prompt.md: Complete system instructions for the AI travel planner.
- README.md: Project overview, features, usage instructions, and limitations.

## Limitations
- The assistant is restricted to travel-related requests.
- Travel costs and travel times are estimates and may vary.
- Recommendations depend on the accuracy and completeness of the information provided by the traveller.
- The assistant cannot guarantee future prices, availability, or travel conditions.

## Testing
The updated system prompt was tested in Google AI Studio through two conversations:
- Test 1: Menu selection and multi-turn destination comparison.
- Test 2: Activity switching and retention of previously established travel information.

## Version Control
The original Assignment 2 prompt is preserved in the repository's commit history. New conversational features were developed on the conversational-features branch before being reviewed for integration into main.
