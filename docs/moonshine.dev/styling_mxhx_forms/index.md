---
title: Styling MXHX Forms
permalink: /docs/moonshine.dev/styling_mxhx_forms
layout: docpage
---

### Styling MXHX Forms

Welcome back to our series on mastering UI design with [Moonshine.dev](https://www.moonshine.dev/)! In [Part 2](/docs/moonshine.dev/diving_into_mxhx), we explored MXHX's powerful capabilities for defining UI components and layouts directly in the code tab. We covered layout types like AnchorLayout, HorizontalLayout, and VerticalLayout to help you build structured interfaces.

Now, in Part 3, we're focusing on making your UIs look amazing by diving into advanced styling techniques. We’ll show you how to use MXHX to apply custom styles that enhance the visual appeal of your applications. Let’s get started and make your interfaces shine!

#### Creating a Feedback Form

1. While in the **Design Tab**, drag a **Form Container** onto the Canvas.
2. In the **Common Properties** tab, set its ID to `"FeedbackForm"` for easy identification.

   ![Screenshot: Giving ID](./img/giving-id.png)

3. Adjust the form's dimensions to a width of **500px** and a height of **300px**.
4. Apply a **VerticalLayout** with a **5px gap** and set all **paddings to 20px**.

   The form should look like this:

   ![Screenshot: Blank Feedback Form](./img/feedback-form.png)

5. Check the **Outline Tab** to verify that the form with ID `"FeedbackForm"` is listed. This helps you select it if other elements are in the way.

#### Put the Form Elements in Place

1. Drag a **Label** component into the **Feedback Form** and set its text to **"Give Us Your Feedback"**.
2. Drag another **Label** component and set its text to **"Name:"**.
3. Drag a **TextInput** component below the "Name:" label.
4. Drag another **Label** and set its text to **"Feedback:"**.
5. Drag a **TextArea** component below the "Feedback:" label.
6. Drag a **Button** and set its text to **"Submit"**.

   The result should look like this:

   ![Screenshot: Feedback Form with Elements](./img/feedback-form-elements.png)

#### Styling Header

1. Select the **"Give Us Your Feedback"** header by clicking on its element in the **Design Tab** or selecting its name in the **Outline Tab**.
2. In the **Properties Panel**, go to the **Common Properties** tab and locate the **Text Styles** section.
3. Set the font to **\_sans**.
4. Change the font size to **24**.
5. Set the color to **0x0c4a6e**.

   ![Screenshot: Text Styles](./img/text-styles.png)

   The result should look like this:

   ![Screenshot: Styled Header](./img/header.png)

#### Styling Labels

1. Select the **Name** label.
2. Set the font to **\_sans**.
3. Change the font size to **10**.
4. Set the color to **0x0c4a6e**.
5. Apply the **Bold** style.

6. Repeat the same steps for the **Feedback** label.

   The result should look like this:

   ![Screenshot: Styled Labels](./img/labels.png)

#### Styling the Fields

We can style the text fields to take up the entire width of our form. To do this:

1. Select the **Name** `TextInput` field.
2. In the **Properties Panel**, navigate to the **Position & Size** section.
3. Set the **Width** to **100** and the units to **%**.

   ![Screenshot: Setting width to 100 percent](./img/100-percent.png)

4. Repeat the same steps for the **Feedback** `TextArea`.

   The result should look like this:

   ![Screenshot: Full Width](./img/full-width.png)

#### Styling the Form

1. Select the **FeedbackForm** container. If you have trouble selecting it in the **Designer Tab**, you can also find it in the **Outline Tab** by the ID we assigned earlier.
2. In the **Properties Panel**, go to the **Background** section.
3. Set the **SkinType** to **RectangleSkin**. New properties should appear.
4. Set the **FillStyle** to **SolidColor** and assign it the color **0xf0f9ff**.
5. Set the **Border LineStyle** to **SolidColor** and configure the following:

   - Thickness: **2**
   - Color: **0x0c4a6e**
   - Corner Radius: **10**

   ![Screenshot: Background Properties](./img/background-properties.png)

   The result should look like this:

   ![Screenshot: Form Border](./img/form-border.png)

#### Styling the Button

To style the button, we will adjust both the text styles and the background properties.

##### Text Styling

1. Set the font to **\_sans**.
2. Set the font size to **14**.
3. Set the text color to **0xffffff**.
4. Apply the **Bold** style.

##### Background Styling

For now, we'll focus on styling the button's default state. It's possible to apply different styles for states like **Up**, **Hover**, **Down**, and **Disabled**.

1. Set the state to **Default**.
2. Choose **RectangleSkin** for the skin type.
3. Set the fill to a solid color of **0x0284c7**.
4. Set the **Border LineStyle** to **SolidColor** with the following properties:

   - Thickness: **2**
   - Color: **0x0c4a6e**
   - Corner Radius: **5**

5. Also, set the button width to **150px** and height to **30px**.

The result should look like this:

![Screenshot: Styled Button](./img/button.png)

#### Conclusion

In Part 3, we took a deep dive into advanced styling techniques with [Moonshine.dev](https://www.moonshine.dev/) and MXHX. You learned how to make your user interfaces not only functional but also visually stunning. By applying custom styles, you can now create cohesive and attractive designs that stand out.

With these styling skills under your belt, you’re ready to tackle Part 4, where we’ll focus on nested layouts. This next step will teach you how to build more complex and responsive designs, taking your UI development to the next level.

Stay tuned for more exciting tips and tricks as we continue our journey in UI design. For more resources, check out:

- [mxhx.dev](https://mxhx.dev/)
- [feathersui.com](https://feathersui.com/)
