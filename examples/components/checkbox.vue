<script>
import { BeCheckbox, BeCheckboxGroup } from '@'
import doc from 'docs/checkbox.md'

export default {
  name: 'comp-checkbox',
  data() {
    return {
      checkbox: true,

      checkbox1: ['北京'],
      list1: ['北京', '天津', '上海'],

      checkbox2: ['北京', '广州'],
      list2: [{
        value: '北京',
        disabled: false
      }, {
        value: '天津',
        disabled: false
      }, {
        value: '上海',
        disabled: false
      }, {
        value: '深圳',
        disabled: true
      }, {
        value: '广州',
        disabled: true
      }]
    }
  },
  template: '<div class="comp-demo-wrapper">' + doc + '</div>',
  components: {
    BeCheckbox,
    BeCheckboxGroup
  }
}

</script>
