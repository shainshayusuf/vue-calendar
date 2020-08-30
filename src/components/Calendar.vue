<template>
  <div>
    <table>
      <th>Choose a Date</th>
      <tbody>
        <tr>
          <td>
    <b-form-datepicker id="datepicker-placeholder" placeholder="Choose a date" v-model="value" local="en"></b-form-datepicker>
      <p>value:{{value}}</p>
          </td>
        </tr>
      </tbody>
    </table>
    
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
 data() {
    return {
        value: '',
        
      }
    }
}
</script>

