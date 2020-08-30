<script lang="ts">
  import { Col, Container, Row } from 'sveltestrap'
  import Card from './Card.svelte'
</script>

<Container >
 <Row>
    <Col><Card title="Yoga"/></Col>
    <Col><Card title="Empowerment"/></Col>
    <Col><Card /></Col>
    <Col><Card /></Col>
  </Row>
   <Row>
    <Col><Card /></Col>
    <Col><Card /></Col>
    <Col><Card /></Col>
    <Col><Card /></Col>
  </Row>
</Container>