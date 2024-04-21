**OpenAPI Docs page example data mismatch**: While updating the OpenAPI documentation for user login and registration, we encountered an issue where the example user data didn't match the actual data required for user creation. This caused login errors, affecting user experience. To resolve this, we aligned the example data with the actual requirements, ensuring consistency across the documentation and improving the application's usability.

link [https://github.com/lovkyasushya/event_manager/pull/2](https://)

**error in dependencies**: In this update, we discovered that certain functions within the AsyncSession were undefined or outdated. This required us to refactor the code using updated packages and functions. Additionally, we improved the validation of usernames to accept only lowercase letters. These changes were not initially pushed to the repository, highlighting a need for better version control practices.

link [https://github.com/lovkyasushya/event_manager/pull/4](https://)

**password validation**: We addressed an issue where the application incorrectly accepted passwords with an extra space. By modifying the code to strictly enforce input rules and updating associated test cases, we enhanced security and reliability in the password validation process.

link [https://github.com/lovkyasushya/event_manager/pull/8](https://)

**server error**: During user registration, missing lines of code led to internal server errors. By adding necessary variables and functions and resolving import errors, we eliminated these disruptions, allowing for smoother user registration.

link [https://github.com/lovkyasushya/event_manager/pull/6](https://)

**deleting issue**: We fixed errors in the user deletion function related to HTTP status codes and output inconsistencies. The corrections included code modifications and the addition of new test cases to verify the functionality's effectiveness.

link [https://github.com/lovkyasushya/event_manager/pull/10](https://)


**github action issue**: The Docker image build process was failing due to errors in the Docker file creation and configuration. Changes were made to correct these issues, ensuring successful image builds and deployments.

link [https://github.com/lovkyasushya/event_manager/pull/12](https://)


Through Homework 10, I gained substantial insights into both technical problem-solving and team collaboration. Correcting the OpenAPI documentation mismatch taught me the importance of accuracy in software documentation. Refactoring code in the AsyncSession highlighted the need to stay updated with technology and adapt to new tools. The necessity of thorough testing and proper version control was underscored through the experiences of resolving password validation and user deletion issues. Additionally, fixing the Docker configuration and resolving server errors reinforced the critical nature of attention to detail. Collaboratively, these tasks improved my project management and communication skills, emphasizing regular updates and structured practices for a more effective team environment.

![Screenshot (44)](https://github.com/lovkyasushya/event_manager/assets/158232938/97654b29-125b-42e6-97a8-846744920a8c)
