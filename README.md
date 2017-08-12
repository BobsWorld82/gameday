# gameday
CSS File for Gameday Daynasty
*-------------------------------------------------*/
/* Rules for HTML selectors.                       */
/*-------------------------------------------------*/
body {
  font-size: 11px; 
  font-family: DIN Alternate; 
  color: black;
  margin-top: 25px;
  padding: 0px;
}
a:link, a:visited, a:active {
  color:black;
  font-weight: bold;
  text-decoration: none;
  }
   
a:hover,li a:hover{
  color:#A3A3A3;
  text-decoration:underline;}
 
th {
  white-space: nowrap;
  color: white;
  font-family: Din Alternate;
  font-size: 18px;
  font-style: normal;
  background:#2B2C2D;
  box-shadow:1px 1px 3px black;
  border-bottom: 3px solid #DD0000;
  text-align: left;
  padding-left:10px;
  height: 20px;
  line-height: 20px;
  padding-top:5px;
  padding-bottom:5px;
  
}
td{
  color:black;
}
 
td a:link,.two_column_layout a{
  color:black;
}
.report td{
  color:black;
}
 
#body_options_01 td,#body_options_197 a,#body_options_197 td,#body_options_40 td{
  color:black;
}
 
 
th a:link, th a:visited, th a:active {
  color: white;
  background: transparent;
}
 
th a:hover {
   color:#A3A3A3;
  background: transparent;
}
 
h3 {
  font-size: 14pt;
  font-weight: bold;
  color: white;
  background-color: #000;
  border: none;
}
 
h3 a:link, h3 a:visited, h3 a:active {
  color: whitesmoke;
}
  
h3 a:hover {
  color: #A3A3A3;
  background:transparent;
}
  
textarea {width: 98%;}
 
 
 
/*-------------------------------------------------*/
/* General page setup rules                        */
/*-------------------------------------------------*/
 
#fantasy_preview .articlepicturetable{
  width:30%;
}
 
 #options_52.pagebody,#options_07.pagebody,#options_08.pagebody,#top.pagebody{
  width:100%;
}
.pageheader{
  visibility: none;
  max-width: 1100px;
  width:100%;
    margin-right: auto;
    margin-left: auto;
  margin-top:20px;
  margin-bottom: 20px;
  height: px;
    background:url(https://dl.dropboxusercontent.com/u/276877713/logo-header-football.png?dl=1);
    background-position:center;
  background-color:transparent;
     background-repeat: no-repeat;
    overflow:hidden;}
    :root { overflow-y: scroll !important; 
}
 
#home div#hsubmenu{
  background:white;
  position:absolute;
  top:250px;
  height:25px;
  font-size:12px;
  width:83.5%;
  box-shadow:0px 4px 4px #AFAFB1;
}
 
#home #hsubmenu ul{
  margin-left:-100px;
}
 
#hsubmenu a:hover{
  text-decoration:underline;  
  color:black;
  text-decoration-color: #DD0000;
  text-decoration-style
}
 
#hsubmenu{
   background:white;
  height:25px;
  margin-bottom:20px;
  font-size:12px;
  box-shadow:0px 4px 4px #AFAFB1;
}
 
.pagebody{
   width:88%;
   font-size: 12px; 
   font-family: Din Alternate,
   margin-right: auto;
     margin-left: auto;
     margin-top:0px; 
   padding-top:1px;  
   margin: auto;    
   background: transparent;
   opacity: .90;
   padding-top:15px;
   margin-bottom:10px;
   overflow:hidden;
   box-shadow: 0px 0px 40px silver;
}
 
 
:root { overflow-y: scroll !important; }
     
     
 
body{   
  border: 0px; 
  font-size: 13px; 
  font-family: 'Ubuntu', sans-serif; 
  color: black; line-height: 1.5; 
  margin: 10px; 
  padding: 20px 10px 30px; 
  text-align:; max-width: 95%; 
  min-width: 800px; 
  margin: 0 auto; 
  border-radius: 5px; 
  background:#EDEEF0;
  background-size: cover;
  background-repeat:no-repeat;
  background-position: center;
  background-attachment: fixed; /* force image to stay put */
    /* styles for narrow screens */
}
 
 
}
 
 
.pagefooter, .pagefooter a{
  background-color:transparent;
  color: black;
}
 
.eventablerow {background-color: transparent;}
.oddtablerow {background-color: transparent;}
.homepagemodule {border:1px solid black;}
 
#homepagecolumn2,#homepagecolumn1,#homepagecolumn3,#tabcontent4,#tabcontent7{
  padding-top:25px;
  background:transparent;
}
#tabcontent0,#tabcontent1{
  padding-top:20px;
}
#tabcontent6,#tabcontent7{
  padding-top:40px;
}
.welcome, .welcome a:visited, .welcome a:link, .welcome a:active {
color:black;
 white-space: nowrap;
  padding-top:10px;
  padding-bottom:5px;
}
.pageheader{
  box-shadow: none;
  width:85%;
  margin:1px;
}
td.welcome{
  box-shadow: none;
}
 
 
 
/*-------------------------------------------------*/
/* Hidden Elements                                 */
/*-------------------------------------------------*/
.pagetitle h1{
  font-size:32px;
  font-weight:bold;
  display: none;
}
.brandlogo a {
background-image:;
visibility: hidden;
}
.brandlogo img{
display: none;
}
 
.bannerimage img{
  display:none;
}
 .homepagemessage {
   display:none;
}
.module_expand{
  display: none;
}
 
/*-------------------------------------------------*/
/* Rules for the tabs.                             */
/*-------------------------------------------------*/
.myfantasyleague_tabmenu #homepagetabs li,.myfantasyleague_tabmenu ul#homepagetabs {
  background:#2B2C2D;
  font-weight:bold;
}
 
.myfantasyleague_tabmenu .currenttab{
  background:#DD0000;
  font-weight:bold;
}
.myfantasyleague_tabmenu #homepagetabs li:hover{
   background:#B2B3B4;
}
#home #hsubmenu{
  background:white;
  position:absolute;
  top:140px;
  height:25px;
  font-size:12px;
  width:83.5%;
  box-shadow:0px 4px 4px #AFAFB1;
}
 
/*--------------------------------------------------*/
/* Rules for the floating menu.                     */
/*--------------------------------------------------*/
.mfl-icon{
  visibility:hidden;
}
 
.myfantasyleague_menu ul,.myfantasyleague_menu{
  background:black;
  border-bottom:none;
  width:auto;
}
 
.myfantasyleague_menu ul{
  position: relative;
  margin-left:auto;
  margin-right:auto;
}
 
 
}
.myfantasyleague_menu ul li a, .myfantasyleague_menu ul li:hover ul li a, .myfantasyleague_menu ul li ul li:hover ul li a,.myfantasyleague_menu ul li ul li:hover a, .myfantasyleague_menu ul li ul li ul li:hover a{
  font-weight:normal;
  text-transform: none;
}
 
.myfantasyleague_menu .no-sub,.myfantasyleague_menu .has-sub{
  background:black;
}
 
.myfantasyleague_menu a.no-sub:hover,.myfantasyleague_menu li:hover > a,.myfantasyleague_menu .has-sub a:hover{
  background:#2B2C2D;
  border:none;
  border-bottom:none;
}
 
.myfantasyleague_menu li:hover > a,.myfantasyleague_menu ul li ul{
  background:transparent;
  border:none;
  text-decoration: none;
}
/*-------------------------------------------------*/
/* Home Page Settings                              */
/*-------------------------------------------------*/
#body_options_69 .inputlabel,#body_options_69 td{
font-size: 15px;
  padding:3px;
  background:;
  border-bottom:1px solid black;
  color:black;
  font-weight:bold;
  text-align: left;
}
 
#body_options_69 .two_column_layout{
  width:50%;float:left;
}
 
 
#poll th{
  height:100%;
  font-size:15px;
  line-height: 1;
  position:relative;
  width:350px;
  display:inline-block;
  white-space: normal;
}
 
#poll{
  border-collapse: collapse;
}
#poll td{
  text-align: left;
}
 
#poll td{
  font-size:15px;
  background:white;
  text-align:center;
  color:black;
  font-weight:bold;
}
  #poll .inputlabel,#poll td{
  font-size: 15px;
  padding:3px;
  background:;
  border-bottom:1px solid black;
  color:black;
  font-weight:bold;
  text-align: left;
}
 
#body_options_69 .oddtablerow,#poll .oddtablerow .inputlabel,#poll .oddtablerow td{
  background:#E2ECF6;
}
 
#poll a:hover{
  background:transparent;
  color:#1A8ED5;
  text-decoration: underline;
}
#poll a:hover{
  background:transparent;
  color:#1A8ED5;
  text-decoration: underline;
}
 
#body_options_207 .pagebody{
  width:100%;
}
 
#body_options_207 td.recap_preview_writeup{
  width:50%;
  padding-bottom:10px;
  background:#EDEEF0;
  box-shadow: 2px 2px 5px gray;
}
 
#body_options_207 td.recap_preview_players{
  background:whitesmoke;
  box-shadow: 2px 2px 5px gray;
}
 
 
#body_options_207 td.recap_preview_players th:last-of-type,#body_options_207 td.points,#body_options_207 th.points{
  font-size:12px;
  width:20%;
  text-align:center;
}
 
#body_options_207 .articlecaption,#body_options_207 .articlepicturetable{
  width:20%;
  padding-bottom:10px;
}
 
#body_options_207 .articlepicture{
  width:100%;
}
 
#body_options_207 .FusionCharts{
  display:none;
}
 
#message_board_summary td.topic{
  font-size:15px;
  background:#FAFAFA;
}
 
#message_board_summary td{
  border-bottom:2px solid #2B2C2D;
 
}
 
th.messageboardbar{
  background:transparent;
  box-shadow: none;
  color:black;
  border-bottom:none;
}
 
th.messageboardbar a{
  color:#2663B3;
}
 
.messageboardlink,a.messageboardlink{
  color:#2663B3;
  margin-left:5px;
  padding-left:5px;
  border-left:2px solid #DD0000;
}
 
a.messageboardlink:hover{
  color:#2663B3;
}
 
.messageboardlink:first-of-type{
  visibility: hidden;
   
}
 
.messageboardlink:first-of-type:after{
  content:'Post New Topic';
  visibility: visible;
  color:#2663B3;
}
.frontpage,.side-panel{
  margin-top:-30px;
}
 
 
#news_articles caption,#news_articles{
  background:white;
  color:black;
}
 
#news_articles{
  border:1px solid #BABBBD;
}
 
#news_articles td{
  padding-left:5px;
  padding-top:10px;
  font-size:13px;
  border-bottom:1px dotted #BABBBD;
}
 
#news_articles th,#news_articles td.timestamp{
  display:none;
}
 
#news_articles caption,#poll caption{
  display:none;
}
 
#owner_activity td.franchisename{
  width:250px; 
}
#owner_activity td.timestamp{
  white-space: nowrap;
}
 
#owner_activity .videoconferenceicon{
  display:none;
}
 
#owner_activity .eventablerow{
  background:#FAFAFA;
}
 
#owner_activity caption{
  width:97%;
  margin-left:-8px;
}
 
#message_board_summary caption{
  display:none;
}
 
table #top_performers,table #top_starters,table .stats-table,table #standings{
  border-collapse: collapse;
}
/*-------------------------------------------------*/
/* Clubhouse Tab Page                              */
/*-------------------------------------------------*/
#franchise_schedule .oddtablerow{
  background:#E2ECF6;
   
}
#franchise_schedule caption,#franchise_schedule .week,#franchise_schedule th{
  display:none;
}
 
#franchise_schedule td{
  background:;
  border-collapse: collapse;
   
}
 
.reports-content #roster caption,.reports-content #submit_lineup caption,.reports-content #my_options caption{
  display:none;
}
.franchiselogo{
  height:75%;
  width:60%;
  border-right:2px solid #3A4F75;
  padding-right:65px;
  padding-left:50px;
}
 
div#tabcontent1{
  background:white;
}
 
#brief_standings{
  background:white;
  border-collapse: collapse;
}
 
#brief_standings tr:nth-child(odd){
  background:white;
}
 
#brief_standings td{
  border-bottom:1px solid black;
}
 
#brief_standings th,#brief_standings td.pf{
  display:none;
}
 
#brief_standings caption,#my_links caption{
  width:90%;
}
 
#brief_standings td.h2hwlt{
  text-align:left;
}
/*-------------------------------------------------*/
/* Scores Tab Page                                 */
/*-------------------------------------------------*/
 
#nflschedule td,#livescoring_summary td{
  background:white;
}
 
#nflschedule caption,#livescoring_summary caption{
  display:none;
}
 
#nflschedule th,#livescoring_summary th,#twitter_feed th{
  color:#7D7F7F;
  background:#EDEEF0;
  border-bottom:2px solid #2B2C2D;
  box-shadow:none;
  padding-bottom: 5px;
  padding-top:5px;
}
 
#nflschedule td,#livescoring_summary td{
  padding-left:10px;
}
 
#nflschedule tr.eventablerow,#nflschedule tr.oddtablerow{
  font-size:16px;
  font-weight:bold;
}
 
#nflschedule td.points,#nflschedule td.points:hover{
  background:#5698DC;
  color:black;
  width:50px;
}
 
 
.report td{
  color:#2B2C2D;
}
 
#livescoring td{
  background:white;
  padding-left:10px;
  font-size:16px;
}
 
#livescoring td{
  border:2px solid #2B2C2D;
}
 
#nflschedule td:hover,#livescoring td:hover{
  background:#F2F2F2;
}
 
#livescoring_summary td.points{
  text-align:center;
  background:#5698DC;
  color:white;
}
 
#livescoring_summary td{
  font-size:15px;
  font-weight:bold;
}
 
#livescoring_summary th a:link{
 color:#7D7F7F;;
}
 
#twitter_feed caption{
  display:none;
}
 
#twitter_feed{
  background:white;
  border-collapse: collapse;
  height:800px;
}
 
#twitter_feed td{
  border:1px solid #BABBBD;  
}
 
#twitter_feed td a{
  color:#2663B3;
}
 
#twitter_feed td{
  font-weight:bold;
}
 
#twitter_feed td:last-of-type,#twitter_feed th:last-of-type{
  display:none;
}
 
#twitter_feed .oddtablerow{
  background:#E2ECF6;
}
 
#twitter_feed td{
  padding:10px;
  text-align: left;
}
/*-------------------------------------------------*/
/* Schedule Tab Page                               */
/*-------------------------------------------------*/
#next_weeks_fantasy_schedule th{
display: none;
}
 
#next_weeks_fantasy_schedule span{
  visibility: hidden;
}
 
#next_weeks_fantasy_schedule span:after{
  content:'Gameday Schedule'; 
  visibility: visible;
  float:left;
  font-size:18px;
}
 
#next_weeks_fantasy_schedule td span{
  display:none;
}
#next_weeks_fantasy_schedule caption,#fantasy_preview caption{
  width:95%;
}
 
 
#tabcontent3{
  background:white;
  margin-top:50px;
}
 
#kickoff_countdown caption{
  display:none;
}
#weekly_calendar caption,#brief_standings caption,#kickoff_countdown th,#next_weeks_fantasy_schedule th a,#next_weeks_fantasy_schedule th{
  background:white;
  color:black;
  border:none;
  box-shadow: none;
  font-weight:bold;
}
#brief_standings h3{
  display:none;
}
 
#brief_standings caption{
  height:25px;
  margin-top:20px;
  font-size:18px;
  white-space: nowrap;
}
#brief_standings h3,#next_weeks_fantasy_schedule th{
  border-bottom:2px solid #3A4F75;
}
 
#next_weeks_fantasy_schedule .oddtablerow{
  background:#E2ECF6;
  border-collapse: collapse;
}
/*-------------------------------------------------*/
/* Standings Tab Page                              */
/*-------------------------------------------------*/
.standingslogo{
  width:100%;
  height:auto;
}
 
#standings{
  border-collapse: collapse;
}
 
#standings .franchiseicon{
  padding-bottom:5px;
  height:25px;
  width:50px;
}
 
#standings a{
  padding-left:10px;
  color:#2663B3;
  white-space: nowrap;
  vertical-align: middle;
  font-weight:normal;
}
 
#standings td.ficonname{
  width:28%;
}
 
 
#tabcontent2,#tabcontent4,#tabcontent5,#tabcontent6{
  background:white;
  margin-top:25px;
  padding-bottom:20px;
}
 
#standings caption{
  display:none;
}
 
#standings th, #standings h3,#standings{
  background:transparent; 
}
 
#standings h3{
  text-align: left;
  color:black;
  padding-top:5px;
}
 
#standings th{
  font-size:14px;
  box-shadow: none;
  color:black;
  border:1px solid #A5A6A7;
}
 
 
#standings .oddtablerow td{
  background:#E2ECF6;
}
 
#standings .eventablerow td{
  border-bottom:1px solid #A5A6A7;
  border-top:1px solid #A5A6A7;
}
 
#standings td,vp,#standings th.vp,#standings th.salary,#standings td.salary,#standings td.h2hwlt,#standings .gb,#standings .pf,#standings .pa,#standings .divwlt,#standings th.h2hwlt{
  border-left:1px solid #A5A6A7;
}
 
#standings #division02 h3,#standings #division01 h3,#standings #division03 h3{
  border-top:1px solid #A5A6A7;
}
 
#standings td.vp,#standings td.salary,#standings th.salary,#standings th.h2hwlt,#standings th.strk,#standings th.h2hpct,#standings td.h2hpct,#standings th.gb,#standings td.avgpa,#standings th.avgpa,#standings td.avgpf,#standings th.avgpf,#standings th.pa,#standings td.pa,#standings th.pf,#standings td.pf,#standings th.divwlt{
  text-align: center;
}
#standings th.vp,#standings th.salary{
  color:transparent;
}
 
#standings th.vp:after{
  content:'Rank';
  visibility: visible;
  position: relative;
  color:black;
  left:40px;
}
 
#standings th.salary:after{
  content:'Funds';
  visibility: visible;
  position: relative;
  color:black;
  margin-left:-38px;
   
}
 
 
/*-------------------------------------------------*/
/* Stats Tab Page                                  */
/*-------------------------------------------------*/
 
#drop .highlight td,#add .highlight td{
  background:black;
  color:white;
}
 
#body_options_08 th, #body_top th{
  font-size:13px;
}
 
#tabcontent5 th{
  background:transparent;
  color:black;
  box-shadow: none;
  border:2px solid #A5A6A7;
}
 
#top_performers,#top_starters,#starter_points_pos,#player_search{
  background:white;
}
 
object.FusionCharts#starterPointsChart{
  padding:3px;
}
 
#top_performers caption,#top_starters caption,#starter_points_pos caption,#player_search caption{
  width:94.5%;
}
 
#player_search td{
  background:#3887D6;
  padding:5px;
}
 
#player_search input{
  width:40%;
  padding:2px;
  margin-left:10px;
}
 
#player_search th{
  display:none;
}
 
#top_performers a,#top_starters a{
  color:#2663B3;
}
#top_performers td:last-of-type,#top_starters td:last-of-type,#top_performers th:last-of-type,#top_starters th:last-of-type,#top_performers th.rank,#top_starters th.rank,#top_performers td.rank,#top_starters td.rank{
  text-align: center;
}
#top_performers td.player,#top_starters td.player{
  padding-left:10px;
  padding-top:4px;
  padding-bottom:4px;
}
 
#top_performers .oddtablerow,#top_starters .oddtablerow{
  background:#E2ECF6;
}
/*-------------------------------------------------*/
/* Teams Tab Page                                  */
/*-------------------------------------------------*/
#roster_column_middle caption,#roster_column_right caption{
  width:94%;
}
/*----------------------------------------------------*/
/* Recruiting Tab                                     */
/*----------------------------------------------------*/
 
#auction_countdown caption{
  width:96.5%; 
}
 
#curr_auctions caption{
   display:none;
}
 
#curr_auctions th{
  background:white;
  color:black;
  border-bottom:3px solid #BABBBD;
  box-shadow:none;
}
 
#curr_auctions .reportfooter:hover,#curr_auctions .reportfooter a:hover{
  color:#2663B3;
  background:#D8D8D8;
  text-decoration:initial;
}
 
#curr_auctions .reportfooter a{
  color:#2663B3;
}
/*-------------------------------------------------*/
/* Caption rules                                   */
/*-------------------------------------------------*/
.homepagecolumn .homepagemodule caption, .pagebody caption, caption,#standings caption{
 width:90%;
  color:black;
  text-align:left;
  background:#FFFFFF;
  border:1px solid #BABBBD;
  padding:10px;
  font-size:18px;
  font-weight:initial;
}
/*----------------------------------------------------*/
/* Media Rules                                        */
/*----------------------------------------------------*/
 
@media only screen and (max-width: 900px) {
   #home div#hsubmenu{font-size:9px;padding-left:130px;width:555px;}
  #hsubmenu{font-size:10px; padding-top:8px;}
    #MFLBoxContainer .MFLLiveTeam img{width:80%;}
  .franchiselogo{padding-left:35px;padding-right:45px;}
  .tabbed-reports li{white-space: nowrap;padding-right:5px;font-size:11px;}
  #standings td.ficonname{width:250px;}
  #standings a{padding-left:1px;}
  #roster_column_left .franchiseicon{width:150px;height:50%;}
  .pagebody{width:100%;}
  .two_column_layout {width:100%;float:left;padding-left:px;}
  .pagebody .two_column_layout{width:100%; margin-left:auto;margin-right:auto;}
  .myfantasyleague_menu a{font-size:10px;}
  .myfantasyleague_menu ul{position:relative;margin-left:auto,margin-right:auto;}
  #poll th{width:100%;}
   
}
 
/*----------------------------------------------------*/
/* Stats Page                                         */
/*----------------------------------------------------*/
#body_options_08,div#withmenus{
  overflow-x: scroll;
}
 
td.status{
  white-space: nowrap;
}
 
#body_options_08 td.status,#body_top td.status{
  font-size:10px;
}
 
#body_top .player,#body_options_08 .player{
  white-space: nowrap;
}
 
#body_top th a,#body_options_08 th a,#body_options_08 th,#body_top th,#body_options_08 .reportform,#body_top .reportform{
  background:white;
  color:black;
  box-shadow:none;
  border:none;
}
 
#body_top .reportform,#body_options_08 .reportform{
  width:98%;
  margin-left:12px;
  height:25px;
  padding-top:5px;
}
#body_top th:empty,#body_top .weeklypointtotals,#body_options_08 th:empty,#body_options_08 .weeklypointtotals{
  display:none;
}
 
#body_options_08 .oddtablerow,#body_top .oddtablerow{
  background:#E2ECF6;
}
 
#body_top tbody,#body_options_08 tbody{
  background:white;
}
 
#body_top td,#body_top td a,#body_options_08 td,#body_options_08 td a{
  padding-top:4px;
  padding-bottom:4px;
  font-weight:normal;
}
 
#body_top td a,#body_options_08 td a{
  padding-left:2px;
  padding-right:2px;
}
 
#body_options_08 td:nth-of-type(4),#body_top td:nth-of-type(4){
  background:#F2F2F2;
  text-align:center;
}
 
#body_top td,#body_options_08 td{
  border-bottom: 1px solid #D8D8D8;
}
 
#body_top td:last-of-type,#body_top th:last-of-type,#body_options_08 td:last-of-type,#body_options_08 th:last-of-type,#body_top td:nth-of-type(2),#body_top th:nth-of-type(2),#body_options_08 td:nth-of-type(2),#body_options_08 th:nth-of-type(2){
  display:none;
}
 
#body_options_08 td.player a{
  color:#2663B3;
  margin-left:2px;
}
 
#body_options_08 td,#body_top td{
  text-align:center;
}
 
#body_options_08 td.player,#body_top td.player{
  text-align:left;
}
/*----------------------------------------------------*/
/* Roster Pages                                       */
/*----------------------------------------------------*/
 
#body_options_07 th.contractyear,#body_options_07 td.contractyear{
  display:none;
}
 
#body_options_07 caption{width:95%;}
 
#body_options_07 th,#body_options_07 td{
  font-size:13px;
}
 
#body_options_07 td{
  border-left: 1px solid #D8D8D8;
}
 
#body_options_07 .contractstatus,#body_options_07 .points,#body_options_07 .week,#body_options_07 .salary,#body_options_07 .contractyear,#body_options_07 .contractinfo{
  text-align:center;
  font-size:12px;
}
 
#body_options_07 th.points{
  color:transparent;
  position:absolute;
  z-index: -2;
}
 
#body_options_07 th.points:after{
  content:'Points';
  color:white;
  position:relative;
  right:70px;
}
 
#body_options_07 .salary_cap_row th:first-of-type,#body_options_07 .total_salary_row th:first-of-type,#body_options_07 .cap_room_available_row th:first-of-type{
    color:transparent;
}
 
#body_options_07 .cap_room_available_row th:first-of-type:after{
  content:'Recruiting Funds Available';
  color:white;
  position:relative;
  right:98px;
}
 
#body_options_07 .total_salary_row th:first-of-type:after{
  content:'Total Recruiting Funds Used';
  color:white;
  position:relative;
  right:50px;
}
 
#body_options_07 .salary_cap_row th:first-of-type:after{
   content:'Recruiting Budget';
  color:white;
  position:relative;
  right:45px;
}
 
#roster_column_middle .contractinfo,#roster_column_right .contractinfo,#roster_column_middle .contractyear,#roster_column_right .contractyear{
  display: none;
}
 
#roster_column_left .franchiseicon{
  height:45px;
}
#roster_column_left{
  width:5%;
  margin:-10px;
}
 
#roster_column_middle,#roster_column_right{
  margin-left:-20px;
}
 
#roster_column_middle caption,#roster_column_right caption{
  width:90%;
  float:left;
  border:none;
}
 
#roster_column_middle th,#roster_column_right th{
  font-size:9px;
}
 
#roster_column_middle td,#roster_column_right td{
  font-size: 10px;
   
}
 
#roster_column_middle .checkBox{
  width:1px;
}
 
#roster_column_middle td,#roster_column_right td{
  white-space: nowrap;
  text-align: center;
}
#roster_column_middle td.player,#roster_column_right td.player{
  text-align: left;
  width:10%;
}
 
 
/*----------------------------------------------------*/
/* Team Pages                                         */
/*----------------------------------------------------*/
 
#withmenus{
  background:white;
}
 
#withmenus .franchiselogo{
  border:none;
  width:150px;
  height:120px;
}
 
#franchiselogo_0002.franchiselogo{
  width:275px;
  height:125px;
}
 
#owner_activity caption{
  display:none;
}
/*----------------------------------------------------*/
/* Custom Lineup                                      */
/*----------------------------------------------------*/
 
#benchtable,#startertable,#startertable caption,#benchtable caption{
  width:100%;
  display:inline-block;
}
 
/*******************************/
/* EDIT BELOW TO MATCH MY SITE */
/*******************************/
/* table header row */
#options_02 .report .theader{background:#f9f9f9;border-bottom:2px solid #ddd}
/* bg coloring for table rows inside each table that display Select x amount of players */
#options_02 .report .toomany{background:#fcc} /* light shaded red when player limit exceeded */
#options_02 .report .notenough{background:#ffc} /* light shaded yellow when need to add more players to that position */
#options_02 .report .rightamount{background:#f1f1f1} /* grey shade when have correct value of position player in lineup */
/* Starter and Bench tablerow background color and border color */
#options_02 #startertable tr.playerrow.eventablerow,#options_02 #benchtable tr.playerrow.eventablerow{background:#fff;}
#options_02 #startertable tr.playerrow.oddtablerow,#options_02 #benchtable tr.playerrow.oddtablerow{background:#f6f6f6;}
#options_02 tr.rightamount td,#options_02 tr.notenough td,#options_02 tr.toomany td,#options_02 tr.row_empty td,
#options_02 #startertable tr.playerrow.oddtablerow,#options_02 #benchtable tr.playerrow.oddtablerow,
#options_02 #startertable tr.playerrow.eventablerow,#options_02 #benchtable tr.playerrow.eventablerow{border-bottom:1px solid #ddd}
/* player photo */
#options_02 #startertable tr.playerrow td.pphoto,#options_02 #benchtable tr.playerrow td.pphoto{border:1px solid #ddd;background:#fff}
/* player injury */
#options_02 #benchtable td.inj b,#options_02 #startertable td.inj b{color:#fff;background:#cd2122}
/* player proj points */
#options_02 #benchtable td.proj-pts,#options_02 #startertable td.proj-pts{color:green}
/* player matchup - player on bye text color */
#options_02 #startertable tr.playerrow td.weekly-opp b,#options_02 #benchtable tr.playerrow td.weekly-opp b{color:#999;font-family: 'Roboto',sans-serif;}
/* x drop player icon */
#options_02 #startertable tr.playerrow:after{color:#cd2122}
/* lock icon color for player on bye or game started */
#options_02 #benchtable tr.playerrow.disabled-row:after,#options_02 #startertable tr.playerrow.disabled-row:after{color:#cd2122}
/* + add player icon */
#options_02 #benchtable tr.playerrow:after,#options_02 #benchtable tr.playerrow.original-starter:before,#options_02 #startertable tr.playerrow.original-starter:before{color:green}
/* show bench - show starters - submit lineup - use default submit form icon color */
#options_02 .form_buttons:before,#options_02 .form_buttons.default-btn:after,#go-back:before{color:#fff}
#options_02 .player{white-space: nowrap;}
/* Lineup Responsive Styles */
@media only screen and (max-width: 48em) {
#options_02 #startertable .row_empty td:after{color:green}
}
 
/**************************************/
/* NO NEED TO EDIT BELOW LAYOUT STYLE */
/**************************************/
/* table layout */
#options_02 .report{display:none}
#options_02 #startertable{float:left;width:49.9%}
#options_02 #benchtable{float:right;width:49.9%}
#options_02 .reportnavigation{clear:both}
#options_02 #startertable .oddtablerow th,#options_02 #startertable .eventablerow th,#options_02 #benchtable .oddtablerow th,#options_02 #benchtable .eventablerow th{display:none}
#options_02 .report .playerrow:hover,#options_02 .report .playerrow:hover{cursor:pointer}
#options_02 .report .postitle{text-transform:uppercase}
#options_02 #benchtable .sheader,#options_02 #startertable .sheader{position:relative;width:100%;display:inline-table}
#options_02 #benchtable .sheader th,#options_02 #startertable .sheader th{height:22px;line-height:22px;font-weight:400;font-size:12px}
#options_02 .report .offstartern{position:absolute;right:10px}
#options_02 #startertable tr.playerrow,#options_02 #benchtable tr.playerrow{position:relative;height:56px;background:none;border:0;box-shadow:none;display:block}
.row_empty{height:56px}
#options_02 #startertable tr.playerrow td,#options_02 #benchtable tr.playerrow td{padding:0;font-size:14px;background:none;border:0;box-shadow:none}
 
/* Hide table on submit lineup submission page when error lineup occures */
#body_submit_lineups #submit_lineups form{display:none}
 
/* table header row */
#options_02 .report .theader{height:30px;line-height:30px;position:relative;box-shadow:none;display:block}
#options_02 .report .theader td{padding:0;font-size:11px;font-weight:400}
 
/* player photo */
#options_02 #startertable tr.playerrow td.pphoto,#options_02 #benchtable tr.playerrow td.pphoto{border-radius:50%;width:52px;max-width:52px;height:52px;overflow:hidden;text-align:center;position:absolute;left:1px;top:2px}
#options_02 #startertable .headshot,#options_02 #benchtable .headshot{height: 57px;width: 42px;margin-top: -2px;}
#options_02 #startertable tr.def_row .headshot, #options_02 #benchtable tr.def_row .headshot {height:100%;margin:0;width:auto;}
/* player name */
#options_02 #startertable tr.playerrow td.player,#options_02 #benchtable tr.playerrow td.player{position:absolute;left:60px;top:2px;border:0;box-shadow:none;z-index:1}
#options_02 #benchtable tr.theader td.player,#options_02 #startertable tr.theader td.player{position:absolute;left:1px;top:0;border:0;box-shadow:none}
/* player matchup */
#options_02 #startertable tr.playerrow td.weekly-opp,#options_02 #benchtable tr.playerrow td.weekly-opp{position:absolute;left:65px;top:21px;border:0;box-shadow:none;font-size:12px}
#options_02 #startertable tr.playerrow td.weekly-opp b,#options_02 #benchtable tr.playerrow td.weekly-opp b{font-weight:400;font-style:italic;}
#options_02 #startertable tr.playerrow td.weekly-opp b:before,#options_02 #benchtable tr.playerrow td.weekly-opp b:before{content:"Player on ";}
#options_02 #startertable tr.playerrow td.weekly-opp b:after,#options_02 #benchtable tr.playerrow td.weekly-opp b:after{content:" this week !";}
/* player injury */
#options_02 #benchtable td.inj,#options_02 #startertable td.inj{position:absolute;left:40px;top:36px;border:0;box-shadow:none;}
#options_02 #benchtable td.inj b,#options_02 #startertable td.inj b{font-size:10px;font-weight:400;border-radius:50%;width:16px;height:16px;line-height:16px;display:block}
/* player proj points */
#options_02 #benchtable td.proj-pts,#options_02 #startertable td.proj-pts{position:absolute;left:70px;top:37px;border:0;box-shadow:none;text-align:center;font-size:12px!important}
#options_02 #benchtable td.proj-pts:before,#options_02 #startertable td.proj-pts:before{content:"Proj Pts: ";}
/* player bye */
#options_02 #benchtable td.bye,#options_02 #startertable td.bye{display:none;}
/* player ytd points */
#options_02 #benchtable td.ytd-pts,#options_02 #startertable td.ytd-pts{position:absolute;right:120px;top:18px;border:0;box-shadow:none;width:45px;text-align:center}
#options_02 #benchtable tr.theader td.ytd-pts,#options_02 #startertable tr.theader td.ytd-pts{position:absolute;right:120px;top:0;border:0;box-shadow:none;width:45px;text-align:center;}
#options_02 #benchtable td.ytd-pts a,#options_02 #startertable td.ytd-pts a{text-decoration:none}
/* player avg points */
#options_02 #benchtable td.avg-pts,#options_02 #startertable td.avg-pts{position:absolute;right:180px;top:18px;border:0;box-shadow:none;width:45px;text-align:center}
#options_02 #benchtable tr.theader td.avg-pts,#options_02 #startertable tr.theader td.avg-pts{position:absolute;right:180px;top:0;border:0;box-shadow:none;width:45px;text-align:center;}
/* player rush pass rank */
#options_02 #benchtable td.rush-rank,#options_02 #startertable td.rush-rank{position:absolute;right:40px;top:18px;border:0;box-shadow:none;width:20px;text-align:center}
#options_02 #benchtable td.pass-rank,#options_02 #startertable td.pass-rank{position:absolute;right:75px;top:18px;border:0;box-shadow:none;width:20px;text-align:center}
#options_02 #benchtable tr.theader td.rank,#options_02 #startertable tr.theader td.rank{position:absolute;right:40px;top:0;border:0;box-shadow:none;width:60px;text-align:center;}
#options_02 #benchtable td.pass-rank a,#options_02 #startertable td.pass-rank a,#options_02 #benchtable td.rush-rank a,#options_02 #startertable td.rush-rank a{text-decoration:none}
tr.theader .opp-rank{white-space:nowrap;display:block;position:absolute;left:0;right:0;top:-8px}
tr.theader .rush-rank{position:absolute;left:0px;top:7px}
tr.theader .pass-rank{position:absolute;right:0px;top:7px;}
/* player nfl news */
#options_02 #startertable tr.playerrow td.nfl-news,#options_02 #benchtable tr.playerrow td.nfl-news{display:none}
 
/* Disable pointer events */
#options_02 #startertable tr.playerrow,#options_02 #benchtable tr.playerrow{pointer-events:none;z-index:0}
/* Enable pointer events for player name - ytd points and font awesome icon */
#options_02 #startertable td.player a,#options_02 #benchtable td.player a,#startertable tr.playerrow:after,#benchtable tr.playerrow:after{pointer-events:all}
#options_02 #startertable td.player a:before,#options_02 #benchtable td.player a:before{content:"";position:absolute;height:100%;width:102%;z-index:-1;}
 
/* Add sillouete image to starter empty table rows */
#startertable tr.row_empty td{position:relative;}
#startertable tr.row_empty td:before {content:"";position:absolute;border-radius: 50%; width: 51px;max-width: 51px;height: 51px;overflow: hidden;text-align: center;position: absolute;left: 1px;top: 2px;background:url(//nitrografixx.com/MFL-Popups/silhouette.png)no-repeat;background-size:42px 57px;border:1px solid #ddd;border-bottom:0;background-position:50% 60%;overflow:hidden;}
 
 
/******************/
/*  FONT AWESOME  */
/******************/
/* Starter table x icon */
#options_02 #startertable tr.playerrow:after{content:"\f057";font-family:FontAwesome;position:absolute;top:13px;z-index:1;font-size:30px;right:5px}
/* Bench table + icon */
#options_02 #benchtable tr.playerrow:after{content:"\f055";font-family:FontAwesome;position:absolute;top:13px;z-index:1;font-size:30px;right:5px}
/* Starter and Bench table lock icon */
#options_02 #benchtable tr.playerrow.disabled-row:after,#options_02 #startertable tr.playerrow.disabled-row:after{content:"\f023";font-family:FontAwesome;position:absolute;top:13px;z-index:1;font-size:30px;right:7px;cursor:default}
/* Starter and Bench table checkmark icon */
#options_02 #benchtable tr.playerrow.original-starter:before,#options_02 #startertable tr.playerrow.original-starter:before{content:"\f05d";font-family:FontAwesome;position:absolute;top:1px;z-index:1;font-size:16px;left:1px;cursor:default;height:12px;width:12px;background:none}
/* Button layout to use icons */
#options_02 .form_buttons input[type="button"],#go-back.form_buttons input[type="button"]{position:relative;padding:5px 10px 5px 25px !important;font-size:16px}
/* Submit button icon */
#options_02 .form_buttons:before{font-family:'FontAwesome';position:relative;left:26px;content:"\f00c";z-index:1;font-size:16px}
/* Mobile show bench and show starters icon */
#options_02 .form_buttons.mobile-button-starter:before,#options_02 .form_buttons.mobile-button-bench:before{content:"\f0e2";left:23px}
/* Use default submission form icon */
#options_02 .form_buttons.default-btn input[type="button"]{position:relative;padding:5px 25px 5px 10px !important;font-size:16px}
#options_02 .form_buttons.default-btn:before,#options_02 h3 + p.default-btn {display:none}
#options_02 .form_buttons.default-btn:after{font-family:'FontAwesome';position:relative;right:23px;content:"\f0a9";z-index:1;font-size:16px}
/* form submission go back button */
#go-back:before {font-family: 'FontAwesome'; position: relative;left: 23px;content: "\f0e2";z-index: 1;font-size: 16px;}
#options_02 p.form_buttons,#go-back.form_buttons{margin-left:-16px;}
#options_02 p.form_buttons.default-btn{margin-left:16px;}
 
/* Lineup Responsive Styles */
@media only screen and (max-width: 63em) {
/* player avg points */
#options_02 #benchtable td.avg-pts,#options_02 #startertable td.avg-pts,
#options_02 #benchtable tr.theader td.avg-pts,#options_02 #startertable tr.theader td.avg-pts{display:none}
}
@media only screen and (max-width: 54em) {
/* player ytd points */
#options_02 #benchtable td.ytd-pts,#options_02 #startertable td.ytd-pts,
#options_02 #benchtable tr.theader td.ytd-pts,#options_02 #startertable tr.theader td.ytd-pts{display:none}
}
@media only screen and (max-width: 44em) {
.starter-hide,.bench-hide{display:none!important}
.starter-show,.bench-show{float:inherit!important;width:100%!important}
.mobile-button{display:block!important}
.mobile-link{cursor:pointer}
.mobile-table-hide{display:none!important}
.mobile-table-show{float:inherit!important;width:100%!important}
#options_02 #startertable .row_empty td{position:relative}
#options_02 #startertable .row_empty td:after{font-family:"FontAwesome";position:absolute;content:"\f055";font-size:30px;right:5px;top:13px}
/* player ytd points */
#options_02 #benchtable td.ytd-pts,#options_02 #startertable td.ytd-pts,
#options_02 #benchtable tr.theader td.ytd-pts,#options_02 #startertable tr.theader td.ytd-pts{display:block;right:150px;}
/* player avg points */
#options_02 #benchtable td.avg-pts,#options_02 #startertable td.avg-pts,
#options_02 #benchtable tr.theader td.avg-pts,#options_02 #startertable tr.theader td.avg-pts{display:block;right:250px;}
}
@media only screen and (max-width: 35em) {  
/* player ytd points */
#options_02 #benchtable td.ytd-pts,#options_02 #startertable td.ytd-pts,
#options_02 #benchtable tr.theader td.ytd-pts,#options_02 #startertable tr.theader td.ytd-pts{right:120px;}
/* player avg points */
#options_02 #benchtable td.avg-pts,#options_02 #startertable td.avg-pts,
#options_02 #benchtable tr.theader td.avg-pts,#options_02 #startertable tr.theader td.avg-pts{right:180px;}  
}
@media only screen and (max-width: 31em) {
/* player avg points */
#options_02 #benchtable td.avg-pts,#options_02 #startertable td.avg-pts,
#options_02 #benchtable tr.theader td.avg-pts,#options_02 #startertable tr.theader td.avg-pts{display:none}  
}
@media only screen and (max-width: 26em) {
/* player ytd points */
#options_02 #benchtable td.ytd-pts,#options_02 #startertable td.ytd-pts,
#options_02 #benchtable tr.theader td.ytd-pts,#options_02 #startertable tr.theader td.ytd-pts{display:none} 
}
@media only screen and (max-width: 20em) {
#options_02 #benchtable td.rush-rank,#options_02 #startertable td.rush-rank{right:38px;}
#options_02 #benchtable td.pass-rank,#options_02 #startertable td.pass-rank{right:68px;}
#options_02 #benchtable tr.theader td.rank,#options_02 #startertable tr.theader td.rank{right:36px;}
tr.theader .rush-rank{left:3px}
tr.theader .pass-rank{right:3px;}
}
@media only screen and (max-width: 19.9em) {
#options_02 #benchtable td.rush-rank,#options_02 #startertable td.rush-rank,#options_02 #benchtable td.pass-rank,#options_02 #startertable td.pass-rank{display:none}
#options_02 #benchtable tr.theader td.rank,#options_02 #startertable tr.theader td.rank{display:none}
}
 
/*----------------------------------------------------*/
/* Playoff Tab                                        */
/*----------------------------------------------------*/
 
#tabcontent8{
  background:white;
  margin-top:25px;
}
 
#playoff1{
  margin-bottom:45px;
}
 
#playoff3{
  margin-left:-40px;
}
 
#playoff3 td.topteam:nth-of-type(2){
  background:url(https://www.dropbox.com/s/j4sga19n8z8x8h7/champ-trophy.png?dl=1);
  background-size:contain;
  background-repeat: no-repeat;
  background-position: center;
  font-weight:bold;
  text-align: center;
  font-size:21px;
  padding-left:10px;
}
 
#playoff3 td.bracket.week16{
  background:url(https://www.dropbox.com/s/3g12wz8i7lpqcsa/CFP-logo.png?dl=1);
  background-size:58%;
  background-position:center;
  background-repeat: no-repeat;
  height:175px;
  color:transparent;
}
 
#playoff3 .topteam.franchise_GAME1_BRACKET1{
  padding-top:65px;
  border-bottom:5px solid #cca434;
  width:200px;
}
 
#playoff3 .bottomteam.franchise_GAME1_BRACKET2{
  padding-top:5px;
  border-bottom:5px solid #cca434;;
}
 
#playoff1 td.bracket.week15{
  background:url(https://www.dropbox.com/s/t74msb8d5e2534o/rose-bowl-logo.jpg?dl=1);
  background-color:white;
  background-size:contain;
  background-position:center;
  background-repeat:no-repeat;
  height:100px;
}
 
#playoff2 td.bracket.week15{
  background:url(https://www.dropbox.com/s/mpslgjw9wzxrkua/sugar-bowl.jpg?dl=1);
  background-color:white;
  background-size:contain;
  background-repeat: no-repeat;
  background-position: center;
  height:100px;
}
 
 
#playoff2 .topteam.franchise_SEED2,#playoff1 .topteam.franchise_SEED2{
  border-bottom:5px solid #cca434;
  padding-right:10px;
  padding-left:10px;
  height:25px;
  padding-bottom:5px;
}
 
#playoff2 td.topteam:nth-of-type(2),#playoff1 td.topteam:nth-of-type(2){
  display:none;
}
 
 
#playoff1 .bottomteam.franchise_SEED1,#playoff2 .bottomteam.franchise_SEED1{
    border-bottom:5px solid #cca434;
    border-right:5px solid #cca434;
    padding-right:10px;
    padding-left:10px;
  height:25px;
  padding-top:5px;}
 
#playoff2 .bracket.week15,#playoff1 .bracket.week15{
  border-right:5px solid #cca434;
}
 
 
#playoff1  td,#playoff2 td{
  text-align: center;
}
 
#playoff1 th,#playoff2 th.championship_week,#playoff3 th.championship_week#playoff1 th.championship_week,#playoff2 th,#playoff3 th.championship_week,#playoff1 th.week15,#playoff2 th.week15,#playoff3 th,#playoff1 caption,#playoff2 caption,#playoff3 caption{
  display:none;
}
 
 
#playoff3 .bottomteam,#playoff3 .topteam{
  text-align: center;
  padding-left:30px;
}
 
#playoff1 td,#playoff2 td,#playoff3 td{
  border:none;
}
 
#playoff7 th.championship_week,#playoff7 th.week15,#playoff7 caption,#playoff5 th.championship_week,#playoff5 th.week15,#playoff5 caption,#playoff6 th.championship_week,#playoff6 th.week15,#playoff6 caption,#playoff4 th.championship_week,#playoff4 th.week15,#playoff4 caption{
  display:none;
}
 
#playoff4 .bracket.week15{
  background:url(https://www.dropbox.com/s/8s45dmngrgkyoyn/fiesta-bowl.jpg?dl=1);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  height:100px;
}
 
#playoff7 td.topteam:nth-of-type(2),#playoff5 td.topteam:nth-of-type(2),#playoff4 td.topteam:nth-of-type(2),#playoff6 td.topteam:nth-of-type(2){
  border:none;
  padding-top:50px;
}
 
 
#playoff7 td.topteam.franchise_SEED2,#playoff7 td.bottomteam.franchise_SEED1,#playoff5 td.topteam.franchise_SEED2,#playoff5 td.bottomteam.franchise_SEED1,#playoff6 td.topteam.franchise_SEED2,#playoff6 td.bottomteam.franchise_SEED1,#playoff4 td.topteam.franchise_SEED2,#playoff4 td.bottomteam.franchise_SEED1{
  height:50px;
}
 
#playoff6 .bracket.week15{
  background:url(https://www.dropbox.com/s/9qgsz44wh395cn3/peach-bowl.png?dl=1);
  background-size: 40%;
  background-repeat: no-repeat;
  background-position: center;
  height:100px;
}
 
#playoff5 .bracket.week15{
    background:url(https://www.dropbox.com/s/dmro1u6lfh4njkl/orange-bowl.png?dl=1);
  background-size: 38%;
  background-repeat: no-repeat;
  background-position: center;
  height:100px;
}
 
#playoff7 .bracket.week15{
    background:url(https://www.dropbox.com/s/gdijsqkw0ghhtsn/outback-bowl.png?dl=1);
  background-size: 50%;
  background-repeat: no-repeat;
  background-position: center;
  height:100px;
}
/*----------------------------------------------------*/
/* League Articles                                    */
/*----------------------------------------------------*/
#body_options_73 .articlepicturetable,#body_options_73 .articlepicture{
  float:right;
  height:300px;
  width:400px;
  margin-top:34px;
}
 
#body_options_73 .articlepicture{
  border:4px solid black;
}
  
#body_options_73 p{
  margin-left:20px;
  -moz column-count: 2;
  column-count: 2;
  line-height: 1.5;
  padding-right:10px;
}
 
#body_options_73 caption{
  display:none;
}
 
#body_options_73 h1{
  background:#D8D8D8;
  border-bottom:4px solid black;
}
 
/*----------------------------------------------------*/
/* Forum Settings                                     */
/*----------------------------------------------------*/
 
.poster img.ava{
  width:100px;
  height:55px;
}
 
td.poster{
  text-align: center;
}
 
.eventablerow td.poster,.eventablerow td.message{
  background:#E2ECF6;
}
 
.oddtablerow td.message,.oddtablerow td.poster{
  border-top:3px solid black;
  border-bottom:3px solid #BDBDBD;
}
/*----------------------------------------------------*/
/* Rules for the main content frame                   */
/*----------------------------------------------------*/
 
#body_options_43 span .warning,#curr_auctions span.warning,#body_options_43 .warning{
  color: #990000;
  text-shadow: 2px 2px 4px white, 0 0 1em white, 0 0 0.2em white;
  -webkit-animation: pulsate 1.5s ease-out;
    -webkit-animation-iteration-count: infinite; 
    opacity: 0.5;
}
 
  @-webkit-keyframes pulsate {
    0% { 
        opacity: 0.5;
    }
    50% { 
        opacity: 1.0;
    }
    100% { 
        opacity: 0.5;
    }
     
}
 
#body_options_43 .eventablerow,#league_chat .oddtablerow{
  background:#E2ECF6;
}
 
#body_auction_bid th,#body_auction_bid td{
  text-align: center;
}
 
#body_options_43 table{
border-collapse:collapse;
}
 
#body_options_43 td:nth-of-type(2){
  text-align:center;
  font-weight:bold;
}
 
#body_options_43 td:nth-of-type(even) input{
  background:silver;
  color:#DD0000;
  font-weight:bold;
  border:2px groove #DD0000;
}
 
#body_options_43 td:nth-of-type(odd) input{
  border:2px groove green;
  background:#81F781;
  font-weight:bold;
  color:#0B6121;
}
 
#contentframe table {
  width:98%;
  color: white;
}
 
.homepagecolumn .homepagemodule,
.homepagecolumn #monthly_calendar,
.report,
.playoffbracket
{
  width:100%;
  border: none;
  color: white;
}
 
.homepagecolumn #bar_chart table {
   width: auto;
}
 
.homepagecolumn .homepagemodule caption {
   width: 95%
}
 
table.two_column_layout {
  width: 98%;
  background: #FBFBFB;
  opacity: .95;
}
 
td.two_column_layout {
  width:50%;
  background:#FBFBFB ;
  opacity: .95;}
}
