# vue-modules
Module component and Modules wrapper component for Vue 2.

## Installation

    npm install @nylira/vue-modules

## Usage

    <template>
      <modules>
        <module>
          <div slot="title">Module Header Title</div>
          <div slot="menu"><a href="#">Random Link</a></div>
          <div>
            This is the main body area.
          </div>
          <div slot="footer">Here is the module footer</div>
        </module>
        <module>
          <div slot="title">Module Two</div>
          <div>
            This is the other body area.
          </div>
          <div slot="footer">Here is the other footer</div>
        </module>
      </modules>
    </template>

    <script>
      import { Module, Modules } from '@nylira/vue-modules'
      export default {
        name: 'key-values-demo',
        components: {
          Module, Modules
        }
      }
    </script>
