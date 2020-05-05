<template>
  <div class="container">
    <div class="back">
      <router-link to="/"><i class='fas fa-arrow-left' style='font-size:40px; color: #737373; margin: 5px 0 0 -0;'></i></router-link>
    </div>
    <div class="go" v-on:click="confirm = !confirm, wax_color = false, background_image = false">
      <i class='far fa-play-circle' style='font-size:48px;color: #676767;'></i>
    </div>
    <div class="row justify-content-center">
      <div class="container background_image pt-3" v-if="background_image" style=" width: 340px; background-color: #c7c7c7; border: 2px solid; margin-top: 50px;">
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">Ambience room</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">Ambience hall</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">Ambience wild</span>
          </div>
        </div>
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">Background 1</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
        </div>
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">Background 2</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
        </div>
      </div>
      <div class="container wax_color pt-3" v-if="wax_color" style=" width: 340px; background-color: #c7c7c7; border: 2px solid; margin-top: 50px;">
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">Wax color red</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">Wax color blue</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">Wax color white</span>
          </div>
        </div>
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">color</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">color</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">color</span>
          </div>
        </div>
        <div class="d-flex justify-content-around pb-4">
          <div class="">
            <div class="d-flex pl-2" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="margin-left: -15px; font-size: 14px;">Background 1</span>
          </div>
          <div class="">
            <div class="d-flex pl-3" style="padding-right: 5px;">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
          <div class="">
            <div class="d-flex pl-3">
              <img class="pr-1" src="../assets/image_icon.png">
              <input type="checkbox" style="width: 16px; height: 16px;">
            </div>
            <span style="font-size: 14px;">pic</span>
          </div>
        </div>
      </div>
      <div class="pb-3" v-if="confirm" style=" width: 300px; height: 150px; background-color: #c7c7c7; border: 2px solid; margin-top: 100px;">
        <div class="ok justify-content-center">
          <div class="justify-content-center align-items-center pt-3">
            Duration for <input class="pl-1" style="border: 2px solid; width: 35px" value="3" maxlength="2"> mins
          </div>
          <button class="mt-5 pl-3 pr-3 mr-3" v-on:click="confirm = !confirm" style="font-weight: bolder; background-color: #c7c7c7">Cancel</button>
          <router-link to="/about"><button class="mt-5 pl-4 pr-4" style="font-weight: bolder; background-color: #c7c7c7">OK</button></router-link>
        </div>
      </div>
      <div class="d-flex col-12 col-sm-8 col-md-6 col-lg-5 myroom" v-if="myroom">
        <button class="flex-fill d-flex justify-content-center align-items-center" style="color: #000000;">
          <div class="col-11">My room</div>
          <div v-on:click="myroom = !myroom, myroom_edit = !myroom_edit"><i class="fa fa-caret-up" style="font-size: 30px;"></i></div>
        </button>
      </div>
      <div class="col-12 col-sm-8 col-md-6 col-lg-4 pb-4 myroom_edit" v-if="myroom_edit" style="background-color: #c7c7c7; border: 2px solid;">
        <div class="d-flex justify-content-center align-items-center pt-2">
          <input class="pl-1" style="border: 2px solid;" value="My room is editable!">
        </div>
        <div class="d-flex justify-content-end" style="margin-top: -32px;" v-on:click="myroom_edit = !myroom_edit, myroom = !myroom">
          <i class="fa fa-caret-down" style="font-size: 30px;"></i>
        </div>
        <div class="d-flex pt-4">
          <div class="col-6 d-flex flex-column">
            <div class="rangecontainer">
              <input type="range" min="1" max="100" value="50" class="range" name="flame_size">
            </div>
            <span class="" style="font-size: 17px;">Flame size</span>
          </div>
          <div class="col-6 d-flex flex-column">
            <div class="rangecontainer">
              <input type="range" min="1" max="100" value="50" class="range" name="flame_brightness">
            </div>
            <span class="" style="font-size: 17px;">Flame brightness</span>
          </div>
        </div>
        <div class="d-flex pt-3">
          <div class="col-6 d-flex justify-content-start">
            <span class="pr-2" style="font-size: 17px;">Background 1</span><i v-on:click="background_image = !background_image, wax_color = false, confirm = false" class='far fa-snowflake' style='font-size:30px'></i>
          </div>
          <div class="col-6 d-flex justify-content-start">
            <span class="pr-2" style="font-size: 17px;">Wax color red</span><i v-on:click="wax_color = !wax_color, background_image = false, confirm = false" class="fa fa-fire" style="font-size:30px"></i>
          </div>
        </div>
        <div class="pt-4">
          <div class="col-6 d-flex justify-content-start">
            <span class="pr-2" style="font-size: 17px;">Animation</span>
            <label class="switch">
              <input type="checkbox" checked>
              <span class="slider round"></span>
            </label>
          </div>
        </div>
        <!-- <div class="ok justify-content-center">
          <div class="pt-3">
            Duration for <input class="pl-1" style="border: 2px solid; width: 35px" value="3" maxlength="2"> mins
          </div>
          <button class="mt-5 pl-3 pr-3" style="font-weight: bolder; background-color: #c7c7c7">OK</button>
        </div> -->
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: 'Candle',
  data () {
    return {
      myroom: true,
      myroom_edit: false,
      background_image: false,
      wax_color: false,
      confirm: false
    }
  }
}
 
</script>

<style>
  body{
    background-color: #ffff;
    color: #000;
  }
  .back {
    position: fixed;
    top: 20px;
    left: 20px;
  }
  .go {
    position: fixed;
    bottom: 100px;
    right: 20px;
  }
  .background_image img, .wax_color img {
    width: 70px;
  }
  .myroom, .myroom_edit {
    position: fixed;
    bottom: 10px;
  }
   /* ============= Range ============ */
  .rangecontainer {
    width: 100%; /* Width of the outside container */
  }
  .range {
    -webkit-appearance: none;
    width: 100%;
    height: 5px;
    border-radius: 5px;
    background: #000;
    outline: none;
    -webkit-transition: .2s;
    transition: opacity .2s;
  }

  .range:hover {
    opacity: 1;
  }

  .range::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 18px;
    height: 18px;
    border-radius: 50%;
    background: rgb(255, 255, 255);
    cursor: pointer;
  }

  .range::-moz-range-thumb {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: #4CAF50;
    cursor: pointer;
  }


  /* // ================ Animation button =============== */
  /* The switch - the box around the slider */
 .switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
}

/* Hide default HTML checkbox */
.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

/* The slider */
.slider {
  position: absolute;
  cursor: pointer;
  width: 61px;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #848383;
  -webkit-transition: .4s;
  transition: .4s;
}

.slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  -webkit-transition: .4s;
  transition: .4s;
}

input:checked + .slider {
  background-color: #2196F3;
}

input:focus + .slider {
  box-shadow: 0 0 1px #2196F3;
}

input:checked + .slider:before {
  -webkit-transform: translateX(26px);
  -ms-transform: translateX(26px);
  transform: translateX(26px);
}

/* Rounded sliders */
.slider.round {
  border-radius: 34px;
}

.slider.round:before {
  border-radius: 50%;
}
</style>
