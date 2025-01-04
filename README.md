### IDAI-103-2405460-Pravar-Golecha

# Personalized Fashion Recommender System using Generative A.I

## Problem Definition

*In today’s fast-paced world, personalized fashion recommendations are becoming increasingly important. Consumers demand tailored suggestions that match their unique preferences, body types, and lifestyle needs. Current fashion recommendation systems often lack deep personalization, failing to consider diverse user inputs such as preferred materials, occasion-specific needs, or cultural influences. This results in generic suggestions that may not resonate with individual users.*

*The goal of this project is to develop a Personalized Fashion Recommender System powered by Generative AI. The system will leverage user-provided data, such as body type, height, favorite colors, and occasion, to generate tailored fashion recommendations. By integrating the Gemini 1.5 Pro API, the system will dynamically adapt to real-time inputs and evolving fashion trends, providing users with accurate, context-specific suggestions.*

## Research Findings

#### Current Landscape of Fashion Recommendation Systems:-

##### Existing Solutions:

*- Platforms like Stitch Fix and Zalando use machine learning algorithms for personalized fashion suggestions.*

*- Major e-commerce players rely on collaborative filtering and content-based filtering but often lack deep personalization.*

##### Market Gaps:

*- Limited consideration of body type and occasion-specific needs.*

*- Inability to process real-time fashion trends dynamically.*


#### Factors Influencing Fashion Choices:-

##### Body Type:

*- Different body shapes (e.g., pear, hourglass, rectangular) require tailored styling to enhance comfort and aesthetics.*

*- Research indicates that clothing fit plays a critical role in user satisfaction.*

##### Lifestyle and Occasions:

*- Professional attire, casual wear, and event-specific outfits (e.g., weddings, vacations) drive varied user requirements.*

*- Seasonal changes influence material preferences (e.g., breathable fabrics for summer, layered options for winter).*

##### Demographic Preferences:

*- Cultural, age-related, and regional fashion trends shape user choices.*

#### Relevant Fashion Trends:-

##### Sustainability:

*- Increasing demand for eco-friendly materials and ethically produced clothing.*

*- Focus on longevity and minimalism in wardrobe selection.*

##### Customization:

*- Users prefer tailored recommendations that account for individual uniqueness.*

##### Tech Integration:

*- Use of AI in analyzing personal style and generating recommendations is an emerging trend in fashion tech.*

#### Data Sources:-

##### User Inputs:

*- User-provided details such as height, weight, body shape, favorite colors, and current style images.*

###### Fashion Datasets:

*- Open datasets on fashion trends and clothing attributes.*

*- Seasonal trend reports from industry leaders.*

## In-Depth Research:-

*- Understanding User Behavior*

##### Fashion Psychology:

*- Study user preferences based on psychological factors, such as color theory and personal identity.*

*- Analyze how users’ self-perception and cultural background influence their clothing choices.*

###### Feedback Loops:

*- Incorporate real-time feedback from users to improve recommendations dynamically.*

*- Understand pain points in current fashion recommendation systems through surveys and interviews.*

#### Technological Analysis

##### Generative AI in Fashion:

*- Explore how generative models, like Gemini 1.5 Pro, are used for text-to-image or image-to-text applications.*

*- Investigate the use of advanced deep learning techniques for image analysis to determine clothing styles and fits.*

##### Competitor Analysis:

*- Benchmark against existing platforms such as Stitch Fix, leveraging studies on their recommendation algorithms.*

*- Evaluate how they incorporate fashion trends and personalization.*

#### Trends in Fashion Technology

##### AI and Sustainability:

*- Investigate the role of AI in promoting sustainable fashion choices.*

*- Study the lifecycle of clothing items to suggest eco-friendly alternatives.*

##### Augmented Reality (AR):

*- Research AR tools for virtual try-ons, which complement personalized recommendations.*

## Key Data Requirements

##### Dynamic Trend Updates:

*- Use APIs to pull real-time data from fashion blogs, social media, and e-commerce sites.*

*- Ensure the system accounts for fast-changing seasonal and cultural trends.*

##### Visual Analysis:

*- Train models on datasets containing diverse clothing styles, materials, and demographics.*

*- Include user-uploaded images for personalized recommendations.*

## Research Objectives

*- Explore the intersection of AI and fashion to identify the most effective approaches for personalized recommendations.*

*- Analyze user behavior and preferences to develop a comprehensive model.*

*- Understand the technical capabilities of Gemini 1.5 Pro API to ensure smooth integration.*

*- Benchmark against existing solutions to identify unique selling points and innovation opportunities.*

## Objectives

*- Personalization: Ensure the system delivers recommendations that cater to individual user preferences and needs.*

*- Dynamic Adaptability: Incorporate real-time fashion trends and seasonality into the model’s outputs.*

*- User-Friendliness: Create an intuitive interface for users to input data and receive recommendations effortlessly.*

*- Trend Awareness: Maintain alignment with contemporary fashion styles and cultural trends.*

## Creating Google Gemini API Key

*-Step 1:First, we need to get an API key from the Google AI for Developers page (make sure you are logged in to your Google account). We can do this by clicking the Get an API key in Google AI studio button.*
![image](https://github.com/user-attachments/assets/c98a1e00-14a5-495e-a842-9549969a9142)

*-Step 2:Then, we will be redirected to 'Google AI Studio' and on that page we have to click on 'Create API Key'.*
![image](https://github.com/user-attachments/assets/9553f4d1-0203-4474-a138-2fbf07e4dd75)

*- Step 3:After clicking on it we need to type 'Gemini API' on 'Search Google Cloud Projects'(it will show like this).*
![image](https://github.com/user-attachments/assets/8ed57e5b-692a-461d-9455-0c4d937d9dbe)

*- Step 4:Then, click on 'Create API Key'.*
![image](https://github.com/user-attachments/assets/2bb19b4d-9578-43e3-9858-d5bd207adcb0)

*- Step 5:At last then copy your API key use it whereever you need it and do not share  it with anyone else.*
![image](https://github.com/user-attachments/assets/b34087c5-1932-488e-8570-6d9e8a889b36)

## Implementing Google Gemini API Key

*- Step 1: Let’s first install the Gemini Python API package using pip(use this command first)*

 ![Screenshot 2025-01-05 004612](https://github.com/user-attachments/assets/d6be9819-9283-4c07-935e-80a75f93d2d1)

*- Step2: Configure the API Key in the Python Code*

![image](https://github.com/user-attachments/assets/cb59f496-a349-48c7-9741-278b131c3cc4)
 
*- Step 3: Create a Generative Model Instance*

![image](https://github.com/user-attachments/assets/5ada75d4-ba0b-40a7-9a68-597e68c3b463)

*- Step 4: Taking output from Gemini API*

![image](https://github.com/user-attachments/assets/029ccc82-560b-4b19-bfe7-649d6642f0a2)

Note: In the place of 'What is Python?' you need to put your prompt and run it 

## Model Integration and Hyperparameter Tuning

### Hyperparameter Tuning
*Hyperparameter tuning optimizes a model's performance by selecting the best values for predefined settings (e.g., learning rate, batch size, number of layers).*

*-Key Techniques:*

*1)Manual Tuning: Adjust parameters iteratively based on performance.*

*2)Grid Search: Tests all combinations of hyperparameter values in a predefined grid.*

*3)Random Search: Samples random combinations, faster than grid search.*

*4)Bayesian Optimization: Efficiently finds optimal hyperparameters by modeling the objective function.*

*5)Hyperband: Dynamically allocates resources to promising configurations.*


### Model Integration
*Model integration is the process of embedding a trained model into a production system to make predictions or perform tasks.*

*-Steps:*

*1)Model Deployment:*
*Use frameworks like Flask, FastAPI, or Django for deploying as an API.*
*Containerize using Docker for scalability.*

*2)API Endpoint:*
*Expose the model via REST or gRPC endpoints for real-time usage.*

*3)Input/Output Processing:*
*Preprocess inputs (e.g., scaling or tokenization).*
*Postprocess outputs for user-friendly results.*

*4)Monitoring:*
*Track metrics like response time and accuracy.*
*Implement feedback loops for model updates.*

## Images of Prompting

![Screenshot 2025-01-05 011302](https://github.com/user-attachments/assets/278c1a8d-d272-4a7a-b5fc-e6b5b3f00d53)

![Screenshot 2025-01-05 011411](https://github.com/user-attachments/assets/a3a979ba-334f-44ea-ae25-02096e7f3dcb)

![Screenshot 2025-01-04 195406](https://github.com/user-attachments/assets/617cdbe9-a7e1-43aa-b6b8-f0978b83211f)

![image](https://github.com/user-attachments/assets/c0f944f1-2996-4937-995e-af18193223c8)

![image](https://github.com/user-attachments/assets/f89b4578-2985-4a75-b320-318d2f5c0df1)

## Example of the response:-

1) Prompt 1:Please suggest a casual summer outfit for a 20-year-old male who is 180 cm tall and prefers lightweight, trendy styles. Provide outfit details that focus on breathable fabrics and summer-appropriate colors.
![Screenshot 2025-01-04 205101](https://github.com/user-attachments/assets/aa6cce80-327d-470b-adfd-2686c26ae429)![Screenshot 2025-01-04 205121](https://github.com/user-attachments/assets/9ee31394-f4a3-4003-9f3a-c7522d759b9b)

2) Prompt 2:Generate a winter outfit recommendation for a female user with a pear-shaped body who prefers sustainable fashion. The user is looking for lightweight fabrics that still provide warmth for cold weather. Please include details on eco-friendly materials and layering options.
![Screenshot 2025-01-04 205744](https://github.com/user-attachments/assets/2cdce2a2-6bc4-4538-8aad-c8ce1611b200)![Screenshot 2025-01-04 205806](https://github.com/user-attachments/assets/bde1f4d1-7530-4cc0-aab1-91db67efaf79)![Screenshot 2025-01-04 205840](https://github.com/user-attachments/assets/44bc6825-117d-47d5-b2cf-cabb17f7cab4)![Screenshot 2025-01-04 205854](https://github.com/user-attachments/assets/a2ede7f8-d51b-4ead-9ab0-6339523a17dd)

3) Prompt 3: Recommend a formal outfit for a male user attending a business conference. The user prefers slim-fit suits and neutral colors. Please suggest a complete outfit, including accessories, that fits a professional setting.
![Screenshot 2025-01-04 210346](https://github.com/user-attachments/assets/734c46b2-8a94-46ed-a3c2-f298e8875b2e)![Screenshot 2025-01-04 210409](https://github.com/user-attachments/assets/edcac0c8-f9b2-437c-acfc-fc59c9c2d93c)

4) Prompt 4:Provide a vacation wardrobe for a user going to a tropical beach holiday. The user enjoys casual, breathable outfits with vibrant colors. Include recommendations for sun protection and light, airy fabrics.
![Screenshot 2025-01-04 210902](https://github.com/user-attachments/assets/95d31544-cc65-45d7-b070-346ed7fb3adc)![Screenshot 2025-01-04 210932](https://github.com/user-attachments/assets/bc41f019-10e8-40f4-b7c2-570a5f7525ef)![Screenshot 2025-01-04 211018](https://github.com/user-attachments/assets/c10d39c3-5a6a-4ae7-afd5-8056aba0302f)

5) Prompt 5: Recommend a traditional outfit for a female user attending a cultural festival. The user prefers elegant and minimalistic styles. Please include recommendations for appropriate accessories and footwear
![Screenshot 2025-01-04 212010](https://github.com/user-attachments/assets/6414763c-e405-40bd-8ba0-c4a47fe2e090)![Screenshot 2025-01-04 212026](https://github.com/user-attachments/assets/bc9bb914-fc9b-488c-ba45-35bbe9ef8d84)

6) Prompt 6: Suggest a smart-casual outfit for a 30-year-old male attending a weekend brunch. The user prefers earthy tones and breathable fabrics. Provide a complete look including shoes and accessories suitable for a relaxed yet stylish appearance
![Screenshot 2025-01-04 212608](https://github.com/user-attachments/assets/1c5fc2dc-e2ba-4676-8cb3-23c6e9e50156)

7) Prompt 7: Recommend an activewear outfit for a female user who enjoys yoga and running. The user is 165 cm tall, prefers vibrant colors, and lightweight, stretchable fabrics. Include options for footwear and any relevant accessories for a comfortable workout session.
![Screenshot 2025-01-04 212820](https://github.com/user-attachments/assets/502aa971-4ee2-470f-beac-68f82ce09e49)![Screenshot 2025-01-04 212838](https://github.com/user-attachments/assets/ca24725a-ada0-4fdd-ad52-1e018149ac04)![Screenshot 2025-01-04 212914](https://github.com/user-attachments/assets/78f72182-b125-4910-b30c-417a5e6f6427)

8) Prompt 8: Generate an outfit recommendation for a 28-year-old female attending an evening winter party. The user prefers elegant dresses, warm materials, and subtle colors. Include outerwear and accessories suitable for a cold-weather formal event
![Screenshot 2025-01-04 213240](https://github.com/user-attachments/assets/ce78bd2b-00fa-4b76-afc6-6f3f262c5a2f)![Screenshot 2025-01-04 213258](https://github.com/user-attachments/assets/364cb11f-9392-403b-8035-ecc2643c6fb2)

9) Prompt 9: Provide a beachwear outfit for a male user going on a family vacation. The user enjoys light, airy fabrics and prefers a mix of pastel and bright colors. Suggest a complete wardrobe including footwear and sun-protective accessories.
![Screenshot 2025-01-04 213500](https://github.com/user-attachments/assets/e8b0bc3e-f5cd-4b23-8ead-9904a332bbda)![Screenshot 2025-01-04 213518](https://github.com/user-attachments/assets/de51e667-a424-40dd-b8dc-b2106bf80966)![Screenshot 2025-01-04 213530](https://github.com/user-attachments/assets/f361708f-3899-425c-89c9-f01212a2f584)

10) Prompt 10: Suggest a professional outfit for a 35-year-old female attending a tech conference. The user prefers minimalistic styles, neutral colors, and comfortable fabrics. Include accessories such as a laptop-friendly bag and shoes suitable for long hours
![Screenshot 2025-01-04 213806](https://github.com/user-attachments/assets/db94687b-6560-400f-bace-3d2839aae9c4)![Screenshot 2025-01-04 213817](https://github.com/user-attachments/assets/96700754-74cc-4c63-aa06-ef72f133bc5c)

## Analyzing and Interpreting Outputs:

*1. Reviewing Outputs*
*Check if the recommendations align with user inputs like occasion, preferences, and body type.*
*Example: A summer outfit should suggest breathable fabrics and lightweight materials.*
*Ensure outputs are practical and relevant for the given context.*

*2. Aligning with Trends*
*Compare outputs with current fashion trends (use resources like blogs and social media).*
*Validate seasonal relevance (e.g., layering for winter or light fabrics for summer).*

*3. Gathering Feedback*
*Share recommendations with test users.*
*Ask: "Do these suggestions match your style preferences?" or "What would you change?"*
*Use feedback to identify areas for improvement.*

*4. Metrics for Evaluation*
*Accuracy: Does the output match the prompt?*
*Creativity: Are the suggestions diverse?*
*Practicality: Are the recommendations wearable?*
*Trend Awareness: Do they reflect modern fashion trends?*

*5. Example Analysis*
*Prompt: Formal outfit for a business meeting, slim-fit suits, neutral colors.*
*Output: Navy slim-fit suit, white shirt, black shoes, minimalist belt and tie.*
*Analysis: Matches the prompt, includes professional attire, and aligns with current trends.*


## Model Validation and Optimization

#### Explanation of the Steps done in the code:

*- Data Preprocessing:*
*We scale the features using StandardScaler, as many machine learning algorithms require data to be on the same scale.*

*-Train-Test Split:*
*The data is split into training and testing sets (80% for training and 20% for testing).*

*-Cross-Validation:*
*We use 5-fold cross-validation (cross_val_score) to assess the model's performance before any hyperparameter tuning.*

*-Hyperparameter Tuning:*
*We use GridSearchCV to search for the best hyperparameters. This step performs an exhaustive search over the hyperparameter grid and returns the best combination based on cross-validation performance.*

*-Feature Selection:*
*We use RFE (Recursive Feature Elimination) to select the most important features, reducing the dimensionality and potentially improving the model’s performance.*

*-Model Training and Evaluation:*
*After selecting the best parameters and features, we train the final model and evaluate it using accuracy and a detailed classification report (precision, recall, F1-score).*

*-Model Saving:*
*The best-trained model is saved using joblib for later use.*

