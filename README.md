# FloatingInput Component

This Vue component, `FloatingInput`, is designed to create an input field with a floating label. The label appears inside the input field and moves above it when the user starts typing. This component enhances the user experience by providing a cleaner and more interactive form interface.

## Props

The `FloatingInput` component accepts the following props:

- **id** (String, required): The unique identifier for the input element.
- **label** (String, required): The text to be displayed as the floating label.
- **placeholder** (String, optional, default: ''): The placeholder text for the input element.

## Component Structure

The component consists of a `div` element with a `relative` class to position the input field and label correctly. The input field and label are styled to achieve the floating effect using Tailwind CSS classes and some additional styles.

# SelectDropdown Component

The `SelectDropdown` component is a Vue component designed to create a stylized select dropdown menu with a floating label. This component is useful for providing a clean and user-friendly interface for selecting options from a list.

## Props

The `SelectDropdown` component accepts the following props:

- **id** (String, required): The unique identifier for the select element.
- **label** (String, required): The text to be displayed as the floating label.
- **options** (Array, required): An array of objects representing the options available in the dropdown. Each object should have a `value` and a `label` property.

## Component Structure

The component consists of a `div` element with a `relative` class for positioning. It includes a `select` element for the dropdown options and a `label` element for the floating label effect.

![Sample Preview](https://github.com/AroshaRavishan/Floating-Input-Dropdown-Common-Components-/blob/main/Sample%20Preview.png)

