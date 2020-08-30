<script lang="ts">
  export let title;
  export let subtitle;
  export let url;
  export let image;
  export let description;
  import {
    Card,
    CardBody,
    CardHeader,
    CardSubtitle,
    CardText,
    CardTitle
  } from "sveltestrap";
  import Button from "./Button.svelte";
</script>

<Card class="mb-3">
  <CardHeader>
    <CardTitle>{title}</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle>{subtitle}</CardSubtitle>
    <CardText>
      {description}
    </CardText>
    <Button href={url}/>
  </CardBody>
</Card>
