<!-- This file was automatic generated. Do not edit it manually -->

<PropsTable :data="[
  {
    'name': 'as',
    'description': '<p>The element or component this component should render as. Can be overwrite by <code>asChild</code></p>\n',
    'type': 'AsTag | Component',
    'required': false,
    'default': '\'div\''
  },
  {
    'name': 'asChild',
    'description': '<p>Change the default rendered element for the one passed as a child, merging their props and behavior.</p>\n<p>Read our <a href=\'https://www.radix-vue.com/guides/composition.html\'>Composition</a> guide for more details.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'defaultValue',
    'description': '<p>The value of the tab that should be active when initially rendered. Use when you do not need to control the state of the tabs</p>\n',
    'type': 'number',
    'required': false,
    'default': '1'
  },
  {
    'name': 'dir',
    'description': '<p>The reading direction of the combobox when applicable. &lt;br&gt; If omitted, inherits globally from <code>DirectionProvider</code> or assumes LTR (left-to-right) reading mode.</p>\n',
    'type': '\'ltr\' | \'rtl\'',
    'required': false
  },
  {
    'name': 'linear',
    'description': '<p>Whether or not the steps must be completed in order</p>\n',
    'type': 'boolean',
    'required': false,
    'default': 'true'
  },
  {
    'name': 'modelValue',
    'description': '<p>The controlled value of the tab to activate. Can be bound as <code>v-model</code>.</p>\n',
    'type': 'number',
    'required': false
  },
  {
    'name': 'orientation',
    'description': '<p>The orientation the tabs are laid out.\nMainly so arrow navigation is done accordingly (left &amp; right vs. up &amp; down)</p>\n',
    'type': '\'vertical\' | \'horizontal\'',
    'required': false,
    'default': '\'horizontal\''
  }
]" />

<EmitsTable :data="[
  {
    'name': 'update:modelValue',
    'description': '<p>Event handler called when the value changes</p>\n',
    'type': '[payload: number]'
  }
]" />

<SlotsTable :data="[
  {
    'name': 'modelValue',
    'description': '<p>Current step</p>\n',
    'type': 'number | undefined'
  }
]" />
