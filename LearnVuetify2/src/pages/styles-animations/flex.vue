<template>
  <div class="d-flex bg-surface-variant mb-2">
    <div class="ma-2 pa-2 bg-white">d-flex ></div>
    <div class="ma-2 pa-2 bg-white">d-flex ></div>
  </div>

  <div class="d-inline-flex bg-surface-variant mb-2">
    <div class="ma-2 pa-2 bg-white">d-inline-flex ></div>
    <div class="ma-2 pa-2 bg-white">d-inline-flex ></div>
  </div>

  <div class="d-flex flex-wrap bg-surface-variant mb-2">
    <div class="flex-1-0 ma-2 pa-2 bg-white">d-flex flex-wrap > flex-1-0</div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-wrap ></div>
    <div class="flex-1-1-100 ma-2 pa-2 bg-white">d-flex flex-wrap > flex-1-1-100</div>
  </div>

  <div class="d-flex flex-row mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex flex-row ></div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-row ></div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-row ></div>
  </div>

  <div class="d-flex flex-row-reverse bg-surface-variant mb-2">
    <div class="ma-2 pa-2 bg-white">d-flex flex-row-reverse ></div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-row-reverse ></div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-row-reverse ></div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red"  />
  <div class="d-flex flex-column bg-surface-variant mb-2">
    <div class="ma-2 pa-2 bg-white">d-flex flex-column > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-column > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-column > 3</div>
  </div>

  <div class="d-flex flex-column-reverse bg-surface-variant mb-2">
    <div class="ma-2 pa-2 bg-white">d-flex flex-column-reverse > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-column-reverse > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex flex-column-reverse > 3</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red"  />
  <div class="d-flex justify-start mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-start > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-start > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-start > 3</div>
  </div>

  <div class="d-flex justify-end mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-end > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-end > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-end > 3</div>
  </div>

  <div class="d-flex justify-center mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-center > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-center > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-center > 3</div>
  </div>

  <div class="d-flex justify-space-between mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-between > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-between > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-between > 3</div>
  </div>

  <div class="d-flex justify-space-around mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-around > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-around > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-around > 3</div>
  </div>

  <div class="d-flex justify-space-evenly mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-evenly > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-evenly > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex justify-space-evenly > 3</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red"  />
  <div class="d-flex align-start mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex align-start > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-start > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-start > 3</div>
  </div>

  <div class="d-flex align-end mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex align-end > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-end > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-end > 3</div>
  </div>

  <div class="d-flex align-center mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex align-center > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-center > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-center > 3</div>
  </div>

  <div class="d-flex align-baseline mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex align-baseline > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-baseline > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-baseline > 3</div>
  </div>

  <div class="d-flex align-stretch mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex align-stretch > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-stretch > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-stretch > 3</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red"  />
  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-start">d-flex > align-self-start</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-end">d-flex > align-self-end</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-center">d-flex > align-self-center</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-baseline">d-flex > align-self-baseline</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-auto">d-flex > align-self-auto</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant" style="height: 100px">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white align-self-stretch">d-flex > align-self-stretch</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red"  />
  <div class="d-flex mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white me-auto">d-flex > me-auto</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white me-auto">d-flex > me-auto</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex mb-2 bg-surface-variant">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 2</div>
    <div class="ma-2 pa-2 bg-white ms-auto">d-flex > ms-auto</div>
  </div>

  <div class="d-flex flex-column mb-2 bg-surface-variant" style="height: 300px;">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white mb-auto">d-flex > mb-auto</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 3</div>
  </div>

  <div class="d-flex flex-column mb-2 bg-surface-variant" style="height: 300px;">
    <div class="ma-2 pa-2 bg-white">d-flex > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex > 2</div>
    <div class="ma-2 pa-2 bg-white mt-auto">d-flex > mt-auto</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red" />
  <div class="d-flex align-start flex-column bg-surface-variant mb-2" style="height: 300px;">
    <div class="ma-2 pa-2 bg-white mb-auto">d-flex align-start flex-column > mb-auto</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-start flex-column > 2</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-start flex-column > 3</div>
  </div>

  <div class="d-flex align-end flex-column bg-surface-variant mb-2" style="height: 300px;">
    <div class="ma-2 pa-2 bg-white">d-flex align-end flex-column > 1</div>
    <div class="ma-2 pa-2 bg-white">d-flex align-end flex-column > 2</div>
    <div class="ma-2 pa-2 bg-white mt-auto">d-flex align-end flex-column > mt-auto</div>
  </div>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red" />
  <v-sheet
    class="d-flex flex-nowrap py-3 bg-surface-variant mb-2"
    width="125"
  >
    <v-sheet
      v-for="n in 5"
      :key="n"
      class="ma-2 pa-2"
    >
    d-flex flex-nowrap > {{ n }}
    </v-sheet>
  </v-sheet>

  <v-sheet class="d-flex flex-wrap bg-surface-variant mb-2">
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      d-flex flex-wrap {{ n }}
    </v-sheet>
  </v-sheet>

  <v-sheet class="d-flex flex-wrap-reverse bg-surface-variant mb-2">
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      d-flex flex-wrap-reverse {{ n }}
    </v-sheet>
  </v-sheet>

  <v-sheet class="d-flex flex-wrap bg-surface-variant">
    <v-sheet class="order-3 pa-2 ma-2">
      d-flex flex-wrap > order-3
    </v-sheet>
    <v-sheet class="order-2 pa-2 ma-2">
      d-flex flex-wrap > order-2
    </v-sheet>
    <v-sheet class="order-1 pa-2 ma-2">
      d-flex flex-wrap > order-1
    </v-sheet>
  </v-sheet>

  <v-divider :thickness="10" class="border-opacity-100 ma-5" color="red" />
  <span>d-flex align-content-start flex-wrap</span>
  <v-sheet
    class="d-flex align-content-start flex-wrap bg-surface-variant mb-2"
    min-height="200"
  >
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      bla > {{ n }}
    </v-sheet>
  </v-sheet>

  <span>d-flex align-content-end flex-wrap</span>
  <v-sheet
    class="d-flex align-content-end flex-wrap bg-surface-variant mb-2"
    min-height="200"
  >
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      bla > {{ n }}
    </v-sheet>
  </v-sheet>

  <span>d-flex align-content-center flex-wrap</span>
  <v-sheet
    class="d-flex align-content-center flex-wrap bg-surface-variant mb-2"
    min-height="200"
  >
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      bla > {{ n }}
    </v-sheet>
  </v-sheet>

  <span>d-flex align-content-space-around flex-wrap</span>
  <v-sheet
    class="d-flex align-content-space-around flex-wrap bg-surface-variant mb-2"
    min-height="200"
  >
    <v-sheet
      v-for="n in 20"
      :key="n"
      class="ma-2 pa-2"
    >
      bla > {{ n }}
    </v-sheet>
  </v-sheet>

  <v-divider :thickness="10" color="error" class="border-opacity-100 ma-5" />
  <span>flex-nowrap</span>
  <v-row
      class="flex-nowrap bg-surface-variant"
      no-gutters
    >
      <v-col
        class="flex-grow-0 flex-shrink-0"
        cols="2"
      >
        <v-sheet class="ma-2 pa-2">
          flex-grow-0 flex-shrink-0
        </v-sheet>
      </v-col>

      <v-col
        class="flex-grow-1 flex-shrink-0"
        cols="1"
        style="min-width: 100px; max-width: 100%;"
      >
        <v-sheet class="ma-2 pa-2">
          flex-grow-1 flex-shrink-0
        </v-sheet>
      </v-col>

      <v-col
        class="flex-grow-0 flex-shrink-1"
        cols="5"
        style="min-width: 100px;"
      >
        <v-sheet class="ma-2 pa-2">
          flex-grow-0 flex-shrink-1
        </v-sheet>
      </v-col>
    </v-row>
</template>
