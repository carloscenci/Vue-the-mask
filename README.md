# Vue-the-mask

############ Instalar:

===================================================

############ No package.json

dependencies {
  vue-the-mask
}

devDependencies {
  @types/vue-the-mask
}

=====================================================

########## Importando no componente

<v-text-field v-mask="'##/##/####'"
>
</v-text-field>


import { mask } from 'vue-the-mask'

@Component({
  directives: { mask },
}) 
