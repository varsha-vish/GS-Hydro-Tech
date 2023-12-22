<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="6">
            <div style="position: relative" class="mt-16">
              <!-- <h1 class="text-grey">Hello,</h1> -->
              <br/>
              <p class="text-white">We understand the critical role that quality plays in the functionality and longevity of our products. As a committed dealer and manufacturer, we adhere to stringent quality control measures, guaranteeing that every product leaving our facility meets the highest industry standards. Our commitment to excellence is unwavering, providing you with the confidence that comes from knowing you have reliable partners in your corner.</p>
              <br/>
              <p1 class="text-white">Hydraulic Valves, Fittings, Automobile Parts, Heavy Duty Truck Trailers, Hydraulic Pumps, Axles, Suspensions, fabricator, Dealer and Manufacturer</p1>
              <!-- <span class="text-grey">Web Designer & Developer</span><br /> -->

              <!-- <v-btn tile dark class="text-yellow mt-8" variant="outlined">
                Contact me
              </v-btn> -->
            </div>
          </v-col>
          <v-col cols="1">
            <div
              style="
                position: absolute;
                z-index: 9999;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
              class="mt-16"
            >
              <v-icon>fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
          <v-col cols="5">
            <div style="position: relative; z-index: 9999" class="mt-9">
              <v-img src="../assets/image1.jpg" max-height="300"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16" id="about">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div class="egg">
                <v-img src="../assets/image2.jpg" max-height="400"></v-img>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
              <h3 class="mt-16">About Us</h3>
              <div style="width: 120px">
                <v-slider
                  v-model="slider2"
                  color="yellow"
                  label="track-color"
                ></v-slider>
              </div>
              
              <!-- <h4 class="">And Developer</h4> -->
              <p class="text-grey">
                Welcome to GS Hydro Tech, where innovation meets reliability in the world of hydraulic solutions and automotive excellence. As a seasoned player in the industry, we take pride in being your one-stop destination for a comprehensive range of products and services.
              </p>
              <br />
              <h4 class="mt-5">Our Expertise:</h4>
           
              <p class="text-grey">
                At GS Hydro Tech, we specialize in providing top-notch hydraulic valves, fittings, and pumps that set the benchmark for performance and durability. Whether you're in need of precision-engineered automobile parts or heavy-duty truck trailers, we've got you covered. Our expertise extends to axles, suspensions, and a dedicated team of fabricators, ensuring that you receive tailor-made solutions for your specific requirements.
              </p>
             
              <h4 class="mt-5">Why Choose GS Hydro Tech?</h4>
              <p class="text-grey mb-10">
                <ul>
                <li>Extensive Range: From hydraulic valves to heavy-duty truck trailers, we offer a comprehensive product lineup.</li>
                <li>Quality Assurance: Our products undergo rigorous quality checks to ensure superior performance and longevity.</li>
                <li>Innovation: Stay ahead with our innovative solutions that incorporate the latest technological advancements.</li>
                <li>Customer Satisfaction: Your success is our success, and we go the extra mile to ensure your satisfaction.</li>
                <br/>
                We don't just provide products; we deliver solutions that drive your success. Partner with us, and experience the difference of reliability, innovation, and excellence in every hydraulic component and automotive part.
                </ul>
              </p>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <v-divider></v-divider>
      <v-col cols="12" sm="12" id="products">
        <div class="d-flex justify-center mt-5 mb-6">
          <v-btn color="#FBDF7E" class="mr-2">OUR PRODUCTS</v-btn>
          <!-- <v-btn class="mr-2" variant="tonal">Web Design</v-btn>
          <v-btn class="mr-2" variant="tonal">Front Design</v-btn>
          <v-btn class="mr-2" variant="tonal"> Photography</v-btn>
          <v-btn variant="tonal"> Illustration</v-btn> -->
        </div>
      </v-col>
   
        <div class="pre">
          <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="../assets/eqp1.jpg" height="200px" cover></v-img>
                

                <v-card-title> Equipment 1 </v-card-title>

                <!-- <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle> -->
                <v-card-text>
                  VOLTZ TOJ-5T Toe Jack 2.5/5 ton Hydraulic Machine Toe Jack Lift Ton Track Cylinder Hard Chrome Welded Steel
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="../assets/eqp2.jpg" height="200px" cover></v-img>

                <v-card-title> Equipment 2 </v-card-title>

                <!-- <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle> -->
                <v-card-text>
                  VOLTZ TOJ-5T Toe Jack 2.5/5 ton Hydraulic Machine Toe Jack Lift Ton Track Cylinder Hard Chrome Welded Steel
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="../assets/04.jpg" height="200px" cover></v-img>

                <v-card-title> Equipment 3 </v-card-title>
<!-- 
                <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle> -->
                <v-card-text>
                  VOLTZ TOJ-5T Toe Jack 2.5/5 ton Hydraulic Machine Toe Jack Lift Ton Track Cylinder Hard Chrome Welded Steel
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
     
      <v-col cols="12" sm="12" class="px-16 contact" id="contact">
        <v-row>
          <v-col cols="12" sm="4">
            <div class="child">
              <h1>Contact info.</h1>
              <v-btn
                icon="fas fa-map-marker-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">New Model Town Ward No.9, Sahnewal, Punjab 141120 </span
              ><br />
              <v-btn
                icon="fas fa-phone-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">999999999 </span> <br />
              <!-- <span class="text-caption">00235 - 6521 </span> <br /> -->
              <v-btn
                icon="fas fa-envelope"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">satish01@yahoo.com </span> <br />
            </div>
          </v-col>
          <v-col cols="12" sm="8">
            <h1 class="mt-8">Send your message</h1>
            <v-divider></v-divider>
            
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Name"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Message"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <v-btn color="#FBDF7E" class="mt-2">Submit Now</v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-container>
    <FooterView />
  </v-app>
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";


// Components
//import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: "HomeView",
  setup() {
    return {
   
      slider2: 50,

    };
  },
  components: {
    NavBar,
    FooterView
},
});
</script>
<style scoped>
.v-container {
  padding: 16px 0 16px 0;
}

.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}
.head:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}
.egg {
  display: block;
  margin-left: 100px;
  margin-top: 50px;
  width: 356px;
  height: 300px;
  background-color: #fbdf7e;
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
.first {
  width: 100%;
  height: 280px;
  text-align: center;
  padding: 2rem 2rem;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
  margin-right: 8px;
}
.imgHover {
  padding: 0 200px;
}
.pre {
  width: 100%;
  height: 380px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
.contact {
  width: 100%;
  padding: 0 200px;
  background-color: #e2e6f3;
 
}

</style>
