<template>
<div>
    <v-content fluid class="c1">
        <v-row>
            <v-col class="inp" align="middle">
                <h2 class="stext">Stepdemy SD</h2>
            </v-col>
        </v-row>
        <v-row>
            <v-col align="middle">
                <v-autocomplete class=" sbox" placeholder="Пошук.." rounded>

                </v-autocomplete>
                <v-text-field style="display:none" placeholder="Dense & Rounded" rounded class=" sbox"></v-text-field>
                <input style="display:none" class=" sbox" type="text" placeholder="Пошук..">
            </v-col>
        </v-row>

    </v-content>
    <v-container fluid class="mb-12 sm">
        <v-row>
            <v-col class="mn">
                <div class="smen">
                    <div class="ib">
                        <v-icon class="iblc" size="140px">mdi-account</v-icon>
                        <p class=" itext">Викладачі</p>
                    </div>
                </div>
            </v-col>
            <v-col class="mn">
                <div class="smenb">
                    <div class="ibl">
                        <svg xmlns="http://www.w3.org/2000/svg" width="65" height="85" viewBox="0 0 99 135">
                            <g id="Polygon_2" data-name="Polygon 2" transform="translate(99) rotate(90)" fill="#fff">
                                <path d="M 106.617919921875 96.5 L 28.38208389282227 96.5 C 25.95551681518555 96.5 23.72024917602539 95.86758422851563 21.73836708068848 94.62030029296875 C 19.89376640319824 93.45940399169922 18.36956596374512 91.80667114257813 17.3305835723877 89.84075164794922 C 16.29159927368164 87.87483978271484 15.78468322753906 85.68447113037109 15.86464977264404 83.50642395019531 C 15.95058345794678 81.16630554199219 16.6872673034668 78.96320343017578 18.05423355102539 76.95829010009766 L 57.17214965820313 19.58535385131836 C 58.37675094604492 17.818603515625 59.93083190917969 16.44108772277832 61.79123306274414 15.49102020263672 C 63.53856658935547 14.59870338439941 65.51263427734375 14.12705421447754 67.5 14.12705421447754 C 69.48736572265625 14.12705421447754 71.46143341064453 14.59870338439941 73.20876312255859 15.49102020263672 C 75.06916809082031 16.44108772277832 76.62325286865234 17.818603515625 77.82785034179688 19.58535385131836 L 116.9457702636719 76.95830535888672 C 118.3127517700195 78.96320343017578 119.049430847168 81.16630554199219 119.1353530883789 83.50640106201172 C 119.2153167724609 85.68445587158203 118.7084197998047 87.87483978271484 117.66943359375 89.84073638916016 C 116.6304321289063 91.80665588378906 115.1062469482422 93.45940399169922 113.2616348266602 94.62030029296875 C 111.2797698974609 95.86758422851563 109.0445022583008 96.5 106.617919921875 96.5 Z" stroke="none" />
                                <path d="M 67.5 16.62705230712891 C 64.14128112792969 16.62705230712891 61.12979888916016 18.2186279296875 59.23771667480469 20.99369049072266 L 20.11979675292969 78.36663055419922 C 19.02242279052734 79.97612762451172 18.43132019042969 81.73626708984375 18.36296081542969 83.59815216064453 C 18.29904174804688 85.3388671875 18.70635986328125 87.09358978271484 19.54087829589844 88.67259216308594 C 20.37538146972656 90.2515869140625 21.59571838378906 91.57662963867188 23.06996154785156 92.50443267822266 C 24.64679718017578 93.49681091308594 26.43405914306641 93.99999237060547 28.382080078125 93.99999237060547 L 106.617919921875 93.99999237060547 C 108.5659408569336 93.99999237060547 110.3531799316406 93.49681091308594 111.9300231933594 92.50443267822266 C 113.4042816162109 91.57662963867188 114.6246185302734 90.2515869140625 115.4591217041016 88.67259216308594 C 116.2936172485352 87.09356689453125 116.7009429931641 85.3388671875 116.6370239257813 83.59812927246094 C 116.5686645507813 81.73626708984375 115.9775772094727 79.97612762451172 114.8801803588867 78.36663055419922 L 75.76226043701172 20.99369049072266 C 73.87017822265625 18.2186279296875 70.85870361328125 16.62705230712891 67.5 16.62705230712891 M 67.5 11.62705230712891 C 72.20808410644531 11.62705230712891 76.91616058349609 13.81037139892578 79.89340209960938 18.17700958251953 L 119.0113220214844 75.54994964599609 C 125.8002777099609 85.50707244873047 118.6692199707031 98.99999237060547 106.617919921875 98.99999237060547 L 28.382080078125 98.99999237060547 C 16.33075714111328 98.99999237060547 9.199722290039063 85.50707244873047 15.98866271972656 75.54994964599609 L 55.10658264160156 18.17700958251953 C 58.08383178710938 13.81037139892578 62.79191589355469 11.62705230712891 67.5 11.62705230712891 Z" stroke="none" fill="#707070" />
                            </g>
                        </svg>

                    </div>
                    <div class="sbtext">
                        <p class="text-center">Уроки</p>

                        <p>Some text must be placed here</p>
                    </div>
                </div>

            </v-col>
            <v-col class="mn">
                <div class="smenc">
                    <div class="ibl">
                        <v-icon>mdi-account</v-icon>
                    </div>
                    <div class="sctext">
                        <p>Предмети</p>
                    </div>
                </div>
            </v-col>

        </v-row>

    </v-container>
    <v-container class="mb-12">
        <p v-if="isLoading"  >Loading......</p>
        <v-row class="courses " v-if="!isLoading" justify="center" align="center">
            <v-col cols="3" v-for="x in topLessons" :key="x.videoUrl" class="mb-7" >
                <v-card class="card">
                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg" width="65" height="85" viewBox="0 0 99 135">
                            <g id="Polygon_2" data-name="Polygon 2" transform="translate(99) rotate(90)" fill="#fff">
                                <path d="M 106.617919921875 96.5 L 28.38208389282227 96.5 C 25.95551681518555 96.5 23.72024917602539 95.86758422851563 21.73836708068848 94.62030029296875 C 19.89376640319824 93.45940399169922 18.36956596374512 91.80667114257813 17.3305835723877 89.84075164794922 C 16.29159927368164 87.87483978271484 15.78468322753906 85.68447113037109 15.86464977264404 83.50642395019531 C 15.95058345794678 81.16630554199219 16.6872673034668 78.96320343017578 18.05423355102539 76.95829010009766 L 57.17214965820313 19.58535385131836 C 58.37675094604492 17.818603515625 59.93083190917969 16.44108772277832 61.79123306274414 15.49102020263672 C 63.53856658935547 14.59870338439941 65.51263427734375 14.12705421447754 67.5 14.12705421447754 C 69.48736572265625 14.12705421447754 71.46143341064453 14.59870338439941 73.20876312255859 15.49102020263672 C 75.06916809082031 16.44108772277832 76.62325286865234 17.818603515625 77.82785034179688 19.58535385131836 L 116.9457702636719 76.95830535888672 C 118.3127517700195 78.96320343017578 119.049430847168 81.16630554199219 119.1353530883789 83.50640106201172 C 119.2153167724609 85.68445587158203 118.7084197998047 87.87483978271484 117.66943359375 89.84073638916016 C 116.6304321289063 91.80665588378906 115.1062469482422 93.45940399169922 113.2616348266602 94.62030029296875 C 111.2797698974609 95.86758422851563 109.0445022583008 96.5 106.617919921875 96.5 Z" stroke="none" />
                                <path d="M 67.5 16.62705230712891 C 64.14128112792969 16.62705230712891 61.12979888916016 18.2186279296875 59.23771667480469 20.99369049072266 L 20.11979675292969 78.36663055419922 C 19.02242279052734 79.97612762451172 18.43132019042969 81.73626708984375 18.36296081542969 83.59815216064453 C 18.29904174804688 85.3388671875 18.70635986328125 87.09358978271484 19.54087829589844 88.67259216308594 C 20.37538146972656 90.2515869140625 21.59571838378906 91.57662963867188 23.06996154785156 92.50443267822266 C 24.64679718017578 93.49681091308594 26.43405914306641 93.99999237060547 28.382080078125 93.99999237060547 L 106.617919921875 93.99999237060547 C 108.5659408569336 93.99999237060547 110.3531799316406 93.49681091308594 111.9300231933594 92.50443267822266 C 113.4042816162109 91.57662963867188 114.6246185302734 90.2515869140625 115.4591217041016 88.67259216308594 C 116.2936172485352 87.09356689453125 116.7009429931641 85.3388671875 116.6370239257813 83.59812927246094 C 116.5686645507813 81.73626708984375 115.9775772094727 79.97612762451172 114.8801803588867 78.36663055419922 L 75.76226043701172 20.99369049072266 C 73.87017822265625 18.2186279296875 70.85870361328125 16.62705230712891 67.5 16.62705230712891 M 67.5 11.62705230712891 C 72.20808410644531 11.62705230712891 76.91616058349609 13.81037139892578 79.89340209960938 18.17700958251953 L 119.0113220214844 75.54994964599609 C 125.8002777099609 85.50707244873047 118.6692199707031 98.99999237060547 106.617919921875 98.99999237060547 L 28.382080078125 98.99999237060547 C 16.33075714111328 98.99999237060547 9.199722290039063 85.50707244873047 15.98866271972656 75.54994964599609 L 55.10658264160156 18.17700958251953 C 58.08383178710938 13.81037139892578 62.79191589355469 11.62705230712891 67.5 11.62705230712891 Z" stroke="none" fill="#707070" />
                            </g>
                        </svg>
                    </div>
                </v-card>
                <div class="play-data" align="center">
                    <p class="urok">{{x.title}}</p>

                    <div class="teacher">
                        <p>{{x.author}}</p>
                        <v-spacer></v-spacer>
                        <v-icon>mdi-account</v-icon>
                    </div>
                    <div class="teacher">
                        <star :rating="x.rating"></star>
                    </div>
                    <div class="teacher">
                        <p class="ldate"> {{new Date().toLocaleString()}}</p>
                    </div>
                </div>
            </v-col>
        </v-row>
    </v-container>

</div>
</template>


<script>
import Star from './Stars'
export default {
    data() {
        return {
        }
    },
    computed:{
        topLessons(){
           
            return this.$store.getters.getTopLessons
        },
        isLoading(){
            return this.$store.getters.loading
        }
    },
  async  beforeCreate() {     
    await    this.$store.dispatch('getAllLessons')
    },
    components:{
        star:Star
    }
}
</script>
<style scoped>
.teacher {
    display: flex;
    width: 275px;
    height: 30px;
    border: 1px solid black;
}

.urok {
    margin-bottom: 3px;
    margin-top: 14px;
    font-size: 22px;
    font-weight: bold;

}

.sbtext {
    margin-top: 40px;

}

.sctext {
    margin-top: 20px;
}

.sctext>p {
    font-size: 45px;
}

.sbtext>p:first-child {
    font-size: 45px;
}

.stext {
    font-size: 50px;
}

.txt {
    font-size: 50px;
}

.ib {
    display: flex;

    flex-direction: column;

    justify-content: center;

    align-items: center;
}

.c1 {
    height: 550px;
    width: 100%;

}

.ldate {

    text-align: left;
}

.itext {

    padding-top: 20px;
    font-size: 40px;
    font-weight: lighter;
}

.courses>div {
    display: flex;
    justify-content: center;
    align-items: center;

}

.iblc {

    width: 162px;
    height: 162px;
    border: 1px solid black;
    margin-top: 20px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.ibl {
    width: 262px;
    height: 162px;
    border: 1px solid black;
    margin-top: 20px;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.mn {
    justify-content: center;
    display: flex;
}

.sm {
    border: 1px solid black;
    background: #4E5256
}

.smen {
    width: 300px;
    height: 300px;
    margin-top: 50px;
    border-radius: 10px;
    background: white;
    display: flex;
    justify-content: center;

}

.smenc {
    width: 300px;
    height: 300px;
    margin-top: 50px;
    border-radius: 10px;
    background: white;
    display: flex;
    flex-direction: column;
    align-items: center;

}

.smenb {

    background: white;
    width: 300px;
    height: 400px;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.blackt {
    height: 130px;
    background: rgba(0, 0, 0, 0.75);
    background-size: 100%;
    width: 100%;
    margin-top: 60px;

    justify-content: center;
}

.courses {
    display: flex;
    justify-content: space-between;
}

.comp {
    width: 500px;
    height: 45px;
    background: rgba(128, 128, 128, 0.5);
    font-size: 20px;

}

.courses>div {
    flex-direction: column;

}

.courses>div>div {
    justify-content: center;

    align-items: center;
}

.courses>div>div:first-child {
    border: 1px solid black;
    height: 175px;
    width: 275px;
    border-radius: 20px;

}

.ft {
    background: black;
}

.sbox {
    background: white;
    color: black;
    height: 50px;
    width: 500px;
    font-size: 25px;
    padding-left: 30px;
    /*border-radius: 20px;*/
    border: 1px solid black;
}

.sbtext>p,
.sctext>p {
    font-weight: lighter;
}

.card {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
