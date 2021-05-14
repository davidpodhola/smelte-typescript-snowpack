<script>
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import App from "../App.svelte";
</script>

<Meta
  title="Example/App"
  component={App}
  argTypes={{
  }}
/>

<Template let:args>
  <App {...args}  />
</Template>

<Story
  name="Primary"
  args={{

  }}
/>
