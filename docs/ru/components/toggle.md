# Toggle

## Использование

<script setup>
import VToggle from '../../../src/components/VToggle/VToggle.vue';
</script>

<VToggle label="Toggle" />

```vue
<v-toggle label="Toggle" />
```

## Props

| Prop              | Тип                   | По умолчанию | Описание                                       |
| ----------------- | --------------------- | ------------ | ---------------------------------------------- |
| **label**         | string                | undefined    | Заголовок компонента                           |
| **labelPosition** | top/right/bottom/left | bottom/left  | Положение заголовок относительно компонента    |
| **color**         | string                |              | Цвет активного компонента                      |
| **disabled**      | boolean               | false        | Отключить возможность использования компонента |
