## 45. Revoking the Lab Guide Image Page That Opens in a New Window – Bug Fix

### Feature Requirement

Prevent the Lab Guide image from opening in a new browser window when clicked.

### Implementation

When a user clicks an image in the Lab Guide, the zoomed image should open in the **same page**, providing an enhanced view without launching a separate window.

### Inject Key for the Lab Guide URL

1. Log in to the CL portal and navigate to the required tenant (WIZ). On the left-hand side of the page, you will see the ODL section.

2. Navigate to the **ODL (1)** section in the left menu, open your respective ODL, click the **Users (2)** button, and deploy the user.

   ![](./Img/01.png)

3. Once the user is deployed, go to any image in the Lab Guide and click on it. The image will zoom in, providing a clearer and larger view.

   ![](./Img/02.png)

4. At the bottom of the zoomed image, there is currently an option to open the image in a **new window**. This option will now be removed as part of the fix, ensuring the image remains within the same page.

   ![](./Img/03.png)

