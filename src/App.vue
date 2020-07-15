<template>
  <div id="app">
    <ComponenteMenu
    :links=links
    />
  </div>
</template>

<script>
import ComponenteMenu from './components/ComponenteMenu.vue';

export default {
  name: 'App',
  components: {
    ComponenteMenu
  },
  data () {
    return {
      links: [
            {
                id: '1',
                title: 'Preguntas más frecuentes',
                imagen: require('./static/media/icons/GroupDudas.svg'),
                to: '/preguntas-frecuentes/'
            },
            {
                id: '2',
                title: 'Planes de Viaje Seguro',
                imagen: require('./static/media/icons/Group19Copy.svg'),
                to: '/preguntas-frecuentes/planes-viaje-seguro'
            },
            {
                id: '3',
                title: 'Cómo comprar Viaje Seguro',
                imagen: require('./static/media/icons/Group18Copy.svg'),
                to: '/preguntas-frecuentes/como-comprar-viaje-seguro'
            }, 
            {
                id: '4',
                title: 'Cobertura de Viaje Seguro',
                imagen: require('./static/media/icons/Group15Copy.svg'),
                to: '/preguntas-frecuentes/cobertura-viaje-seguro'
            },
            {
                id: '5',
                title: 'Modificación de Viaje Seguro',
                imagen:require('./static/media/icons/Group11Copy.svg'),
                to: '/preguntas-frecuentes/modificacion-viaje-seguro'
            },
            {
                id: '6',
                title: 'Utilización del seguro',
                imagen: require('./static/media/icons/Group2Copy.svg'),
                to: '/preguntas-frecuentes/utilizacion-viaje-seguro'
            },
            {
                id: '7',
                title: 'Trámites',
                imagen: require('./static/media/icons/Group9Copy2.svg'),
                to: '/preguntas-frecuentes/tramites'
            },
            {
                id: '8',
                title: 'Sobre COVID-19',
                imagen: require('./static/media/icons/logocoronavirus.svg'),
                to: '/preguntas-frecuentes/sobre-covid-19'
            },
        ],
    }
  }
}
</script>

<style>

</style>
