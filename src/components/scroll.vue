<template>
  <div>
    <p>{{test}}</p>
			<div class="scrollfather" id="scrollfather1" >
				<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>0</p>
				<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>0</p>
				<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>0</p>
				<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>0</p>
				<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>0</p>
			</div>
  </div>
</template>

<script>
  import '../../node_modules/scroll_me/src/css/index.css'
  import {ShineonScroll} from 'scroll_me/src/Plugins_es6_scroll_2.0.js'
  export default {
    mounted () {
      this.el = ShineonScroll()

      console.log(this)
    },
    data () {
      return {
        test: 123,
        el: undefined
      }
    }
  }
</script>
