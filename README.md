# RAGSystem
### Purpose
Using RAG (Retrieval-Augmented Generation) to revamp the original MIS (Management Information System) offers the following key benefits:
1. Enhanced User Experience
2. Increased Intelligence and Automation
3. Lower Training Costs
4. Improved Efficiency
5. Adaptability to Complex Scenarios
6. Reduced Human Errors
7. Scalability and Integration
8. Dynamic Knowledge Updates
This transformation shifts the MIS system from a traditional manual operation model to an intelligent, automated, and user-friendly platform, significantly boosting operational efficiency and user satisfaction.
### Virtual environment construction & system operation
### Installation dependency
### RAG theory 
1. One of the core secrets of RAG applications is the *conversational mode*, enabling interaction between users and AI through dialogue-based exchanges.

2. RAG (Retrieval-Augmented Generation) leverages external knowledge bases or datasets to assist the generation process, encompassing four stages: *retrieval*, *encoding*, *fusion*, and *generation*.

3. In RAG applications, knowledge retrieved from external knowledge bases must be linguistically assembled and then combined with the user’s question for the AI to respond.

4. The conversational mode can be implemented in code by defining roles for the user, assistant, and system, represented through corresponding messages.

5. The RAG application workflow includes the user asking a question, retrieving relevant knowledge, assembling the language, and passing it to the AI for a response.

6. In RAG applications, memory is achieved by the AI interpreting the user's intent based on prior conversations and correctly answering subsequent questions.

### Return structured data
1. Another core aspect of RAG applications is enabling AI to return structured data, such as Boolean values, integers, floats, arrays, and JSON formats, to meet program requirements.  

2. Large models can help programs interpret and process results by returning data in various formats, such as Boolean values, integers, floats, arrays, or JSON.  

3. By configuring the `content` value of the user role in a conversational mode, you can instruct the model to return data in specific formats, such as Boolean values, integers, floats, arrays, or JSON.  

4. Using a universal method to return JSON-formatted data can help solve problems and provide auxiliary information to understand the model’s output, facilitating debugging and verifying the correctness of the output.  

5. Providing the model with an example to mimic significantly increases the likelihood of it outputting structured data.  

6. In practical applications, even with the above methods, the model may sometimes fail to produce structured data correctly. In such cases, alternative solutions can be explored.  

7. The results returned in a conversational mode are human-readable language, but these outputs need to be converted into structured data that programs can recognize, with JSON being the ideal format.  

8. Sometimes, the AI needs a sample to correctly generate outputs based on the given example.


### UI Implementation and Integration with Free Large Models


