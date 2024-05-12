### Creating a Deepfake Video 

Dive into the world of deepfake technology fueled by AI advancements. While making unique content is more accessible, ethical use is vital. This post guides you through creating a deepfake responsibly with free AI tools.

As we explore the fascinating world of deepfake technology, it's imperative that we approach this powerful tool with a sense of responsibility and ethics. Remember, with great power comes great responsibility.

![DALL-E-2023-11-22-12 09 42---Create-a-3_2-aspect-ratio--high-resolution-header-image-for-an-educational-project-titled--Creating-a-Deepfake-Video---The-Trailer- -The-image-should-](https://github.com/mejbass/Deep-Fake/assets/130122304/bbac0264-5239-4de9-8d9e-4133960d2a79)

**Exemple:**

I integrated my face into a scene from Mr. Robot, putting a personalized twist on Rami Malek's iconic role.



https://github.com/mejbass/Deep-Fake/assets/130122304/bc2e66da-3412-4621-a451-bddce603eab9



**Tips for Responsible Deepfake Creation**

- **Consent is Key:** Always obtain explicit consent from individuals whose likenesses you wish to use.
- **Integrity Matters:** Ensure that the content you create is never harmful or defamatory.
- **Purposeful Creation:** Strive to make content that is fun or serves a productive purpose.
- **Reflect Before You Act:** Before publishing or sharing a deepfake video, consider its impact.

This project is a profound opportunity to engage with AI in a way that can illuminate its potential for good. Let's set an example for the responsible use of AI and build a community that prioritizes ethical considerations in all our technological endeavors.

We trust in your judgment and creativity.

Remember:

- **Consent is Key**
- **Integrity Matters**
- **Purposeful Creation**
- **Reflect Before You Act**

## Content Preparation

Before delving into the creation process, gather the essential files required for a seamless deep fake video production:

- **Source Video:** Select a video that you wish to deep clone.
- **Target Faces Images:** Obtain images of the faces you intend to manipulate.
- **Replacement Faces Images:** Collect images of the faces that will replace the original faces in the target video.

## Refacer

To facilitate the deepfake creation process, we’ll be using a tool called Refacer. You can check out the Tool on [GitHub](https://github.com/xaviviro/refacer).

This tool enables you to create deepfakes with multiple faces with just one click! It is powered by the excellent Insightface and inspired by Roop.

For instructions on how to use Refacer, refer to the [Refacer Documentation](#).

## Instantiating and Running Refacer on Google Colab

Initiate the installation and setup process by clicking the play button on the Refacer Colab notebook. This action allocates the necessary resources and installs the required packages.

![AAI-P001-01](https://github.com/mejbass/Deep-Fake/assets/130122304/fa1b0692-cafc-4b55-b790-28c2a9914d72)


![AAI-P001-02](https://github.com/mejbass/Deep-Fake/assets/130122304/bf9dede3-2d55-4867-96cc-bc4bee1075ac)


## Accessing Refacer Webapp

After completion, the program will provide a link to access the application used for deep clone creation. This is a temporary link that you can use to use Refacer on the web.

![AAI-P001-03](https://github.com/mejbass/Deep-Fake/assets/130122304/12b62bee-3a8d-49db-ab07-e0825893d2d3)


## Running Refacer Locally

In case you face difficulties running Refacer on Google Colab, follow the below steps to running it locally on your computer.

In case you face difficulties running Refacer on Google Colab. Follow the below steps to running it locally on your computer.

First create a folder that you will put your files in. Then go ahead and download this file inswapper_128.onnx and place it inside the folder you just created.

Then open the terminal and navigate to the folder you just created and copy paste the following commands one by one to run them.

1. **Clone the Refacer repository:** Use the following command to clone the Refacer repository from GitHub:
   ```
   git clone https://github.com/xaviviro/refacer.git
   ```

2. **Navigate to the refacer directory:** Depending on your operating system, use one of the following commands:
   - For Linux/Mac:
     ```
     cd refacer
     ```
   - For Windows:
     ```
     chdir refacer
     ```

3. **Update requirements.txt:** Open the `requirements.txt` file and replace `gradio==3.33.1` with `gradio==3.36.1`. Save and close the file.

4. **Install packages:** Install the required packages by running the following command:
   ```
   pip install -r requirements.txt
   ```

5. **Run the app:** Start the Refacer application by executing the following command:
   ```
   python app.py
   ```

6. **Access the application:** Finally, open your web browser and navigate to the following address:
   ```
   http://127.0.0.1:7680
   ```

You're now ready to use Refacer locally on your computer!

Finaly, open your web browser and navigate to the following address:
http://127.0.0.1:7680

## Through Google Colab

You can access the Refacer through Google Colab by following this link: [refacer_colab.ipynb](https://colab.research.google.com/drive/1gyhEp2WDvFhPJ5YthN2W0XccU700TSJv?usp=sharing&ref=alxappliedai.com)


## Introducing the Refacer Webapp

The Refacer web application comprises four main sections:

1. Original Video Upload
2. Target Faces Placement
3. Replacement Faces Placement
4. Output File Display

![AAI-P001-04](https://github.com/mejbass/Deep-Fake/assets/130122304/a303cb32-4434-465c-8c09-0408c2db8f29)

## Upload the required files

Upload the respective files to their designated sections and click “Reface” (The big orange button at the bottom of the page). This action initiates a process that will “reface” all frames in the video using the provided faces. Please note that this process may take some time.

## Refacing - Let's Go!!

Upon clicking “Reface” the process begins, showcasing the transformation of the video frames. Monitor the progress as the deepfake video takes shape.

![AAI-P001-07](https://github.com/mejbass/Deep-Fake/assets/130122304/dc6feeea-a27a-46df-b6f4-ddd239d9e1d7)


## Accessing the Output File

The output file is accessible on the Refacer web app. However, if the video does not appear promptly, check the Colab file for a completion message indicating the location of the refaced video.

![AAI-P001-08](https://github.com/mejbass/Deep-Fake/assets/130122304/dda342f4-5453-4ca6-99a2-c5c8043f2427)

![AAI-P001-09](https://github.com/mejbass/Deep-Fake/assets/130122304/c05944a1-077c-4c90-bcc2-7d6b6d2df467)



## Refacer Not Working?

If you have difficulty with Refacer, try out these alternative tools.

- [Magic Hour: Generative AI Tools for Video Content Creation](https://magichour.ai/?ref=alxappliedai.com)
- [AI Face Swap Online Free: Photo, Video, GIF Face Swap](https://www.vidnoz.com/face-swap.html?ref=alxappliedai.com)
- [Free AI Face Swap Online for Videos & Photos | MioCreate](https://www.miocreate.com/face-swap.html?ref=alxappliedai.com)

## Done!

Congratulations, you have successfully created your first deepfake video. 

Remember:

- **Consent is Key**
- **Integrity Matters**
- **Purposeful Creation**
- **Reflect Before You Act**

Questions? Feedback? Requests? Discord: Samej2023

## Disclaimer for Refacer

> :warning: This software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

> :warning: This software is intended for educational and research purposes only. It is not intended for use in any malicious activities. The author of this software does not condone or support the use of this software for any harmful actions, including but not limited to identity theft, invasion of privacy, or defamation. Any use of this software for such purposes is strictly prohibited.

> :warning: You may only use this software with images for which you have the right to use and the necessary permissions. Any use of images without the proper rights and permissions is strictly prohibited.

> :warning: The author of this software is not responsible for any misuse of the software or for any violation of rights and privacy resulting from such misuse.

> :warning: To prevent misuse, the software contains an integrated protective mechanism that prevents it from working with illegal or similar types of media.

> :warning: By using this software, you agree to abide by all applicable laws, to respect the rights and privacy of others, and to use the software responsibly and ethically.
