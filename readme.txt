DayZ Chernarus Compatible Code To Return Loot To High Rise Apartment Buildings ( Land_Tenement_Big )In Chernarus  xml Snippet Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus Local Server DAYZ Version 1.18 July 2022.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

To re-activate loot spawns in the High Rise Aprtment Buildings ( Land_Tenement_Big ) , take the following steps.

Stop your server. Download and edit or open in your webbrowser the mapgroupproto.xml file, which is found inside your servers mission folder.

After the </defaults> entry on approx line 1992, copy and paste the following xml snippet over the exisiting Land_Tenement_Big Entry: 

	<!--New High Rise Apartment Entry To Spawn Loot - Paste this over existing entry -->
		<group name="Land_Tenement_Big" lootmax="50">
					<usage name="Town" />
				<container name="lootFloor" lootmax="50">
						<!--<category name="tools" />-->
						<category name="food" />
						<!--<category name="containers" />-->
						<category name="clothes" />
						<point pos="5.215211 15.123657 9.234131" range="0.100000" height="0.250000" />
						<point pos="3.862917 -2.640669 10.493590" range="0.108582" height="0.188389" />
						<point pos="6.573243 15.137600 8.968749" range="0.134375" height="0.335938" />
						<point pos="6.546386 -5.706966 -6.059875" range="0.134375" height="0.335938" />
						<point pos="5.792849 15.128983 9.140808" range="0.134375" height="0.335938" />
						<point pos="-5.817996 -5.260164 10.468321" range="0.168750" height="0.299999" />
						<point pos="-6.394290 -5.260164 10.442260" range="0.168750" height="0.299999" />
						<point pos="3.637451 10.988808 -3.871583" range="0.169922" height="0.424805" />
						<point pos="-6.452515 1.134655 -9.014037" range="0.184937" height="0.462343" />
						<point pos="-4.328002 14.929802 -10.531922" range="0.197030" height="0.492575" />
						<point pos="3.606324 14.388580 3.606445" range="0.197998" height="0.494995" />
						<point pos="2.170410 14.239140 3.801819" range="0.201904" height="0.504760" />
						<point pos="-2.766847 -5.170860 3.249022" range="0.203125" height="0.357735" />
						<point pos="-1.725957 14.734657 8.610045" range="0.203125" height="0.507813" />
						<point pos="6.648804 -5.170860 -2.575257" range="0.203125" height="0.357811" />
						<point pos="-4.352051 -5.170561 -0.576600" range="0.203125" height="0.357744" />
						<point pos="4.361328 -5.170860 -3.900391" range="0.203125" height="0.357635" />
						<point pos="-6.092528 1.631142 -6.124145" range="0.203125" height="0.357403" />
						<point pos="-6.166992 1.134655 -10.227906" range="0.203125" height="0.507813" />
						<point pos="4.347900 -5.170860 -2.693848" range="0.203125" height="0.357399" />
						<point pos="-2.759523 -5.170860 3.787780" range="0.203125" height="0.357841" />
						<point pos="4.370971 11.829140 -3.932190" range="0.203125" height="0.357548" />
						<point pos="6.156250 11.829140 -2.591858" range="0.203125" height="0.357666" />
						<point pos="6.677490 11.829140 -2.595337" range="0.203125" height="0.357635" />
						<point pos="-4.517944 1.134655 -10.295532" range="0.219543" height="0.548858" />
						<point pos="-1.989017 7.588558 5.681335" range="0.224365" height="0.560912" />
						<point pos="-5.403566 8.291294 9.901427" range="0.225342" height="0.563355" />
						<point pos="-0.713630 14.734657 10.053589" range="0.231384" height="0.578460" />
						<point pos="3.605225 10.990486 -3.289185" range="0.232300" height="0.580750" />
						<point pos="3.562866 -6.011316 -3.913391" range="0.233704" height="0.584260" />
						<point pos="2.980225 14.390430 3.630737" range="0.235107" height="0.587767" />
						<point pos="-6.140379 1.798820 -3.140200" range="0.237500" height="0.593750" />
						<point pos="-4.423340 -5.310503 0.257567" range="0.237500" height="0.593750" />
						<point pos="5.444823 11.688793 -2.769165" range="0.237500" height="0.593750" />
						<point pos="6.300903 -1.902304 2.431213" range="0.237500" height="0.593750" />
						<point pos="5.458129 -5.311205 -2.773133" range="0.237500" height="0.593750" />
						<point pos="-6.651124 -6.160862 2.232970" range="0.239197" height="0.597992" />
						<point pos="3.507202 -2.611300 2.385559" range="0.239563" height="0.598908" />
						<point pos="-5.896118 0.639141 -2.554138" range="0.247864" height="0.619660" />
						<point pos="6.724854 14.239140 2.354797" range="0.248657" height="0.621643" />
						<point pos="-1.345218 7.590462 5.693358" range="0.250732" height="0.626830" />
						<point pos="3.575073 -6.009523 -3.307434" range="0.261353" height="0.653382" />
						<point pos="-4.346923 0.639141 -6.130738" range="0.270508" height="0.676270" />
						<point pos="1.834352 14.654881 9.942932" range="0.271240" height="0.678100" />
						<point pos="0.344116 -5.833162 -9.150085" range="0.271875" height="0.679688" />
						<point pos="4.864624 -6.160862 -2.663025" range="0.276367" height="0.690917" />
						<point pos="-2.766356 7.439140 3.973145" range="0.279175" height="0.697938" />
						<point pos="4.869507 10.839138 -2.592896" range="0.281250" height="0.703125" />
						<point pos="3.509766 -2.609621 2.952820" range="0.285767" height="0.714417" />
						<point pos="-1.645386 14.734657 9.872865" range="0.288384" height="0.720960" />
						<point pos="6.624389 10.839138 -3.102967" range="0.293701" height="0.734252" />
						<point pos="-2.087646 -6.160862 3.547424" range="0.298828" height="0.747070" />
						<point pos="7.543946 -2.760860 6.844848" range="0.301086" height="0.752715" />
						<point pos="-7.531010 7.439140 6.845456" range="0.301697" height="0.754242" />
						<point pos="-5.371216 8.148804 -1.553041" range="0.306250" height="0.765625" />
						<point pos="2.706177 10.839138 -4.009461" range="0.306763" height="0.708954" />
						<point pos="-6.656617 7.439140 2.303832" range="0.310059" height="0.775148" />
						<point pos="2.455689 -6.160862 -10.732239" range="0.317749" height="0.180153" />
						<point pos="-2.805299 -6.160862 5.683288" range="0.318115" height="0.795287" />
						<point pos="2.733154 10.839138 -2.627991" range="0.321716" height="0.804290" />
						<point pos="7.608154 -6.160862 -7.179017" range="0.322754" height="0.806885" />
						<point pos="6.647461 -2.760860 6.594847" range="0.326050" height="0.815125" />
						<point pos="6.567505 -6.160862 -10.217528" range="0.331421" height="0.828552" />
						<point pos="-7.613281 0.639141 -7.188843" range="0.332581" height="0.831453" />
						<point pos="2.800050 -2.760860 6.532530" range="0.334473" height="0.836183" />
						<point pos="-4.609497 14.928314 -2.690857" range="0.340625" height="0.851563" />
						<point pos="-3.217896 8.125748 8.864989" range="0.340625" height="0.851563" />
						<point pos="-4.419434 -6.160862 1.524720" range="0.342896" height="0.857240" />
						<point pos="-0.903442 14.239140 -4.237121" range="0.342896" height="0.857240" />
						<point pos="6.625854 -2.760860 3.163696" range="0.347656" height="0.869140" />
						<point pos="4.423462 -2.760860 3.343384" range="0.349976" height="0.874940" />
						<point pos="2.702515 -2.760860 3.649840" range="0.353882" height="0.884705" />
						<point pos="4.427369 14.239140 3.423400" range="0.353882" height="0.884705" />
						<point pos="-5.345581 7.439140 -1.727967" range="0.358765" height="0.587555" />
						<point pos="-0.012818 -2.760860 5.702271" range="0.358887" height="0.897217" />
						<point pos="-4.386110 -6.160862 10.225768" range="0.360840" height="0.902100" />
						<point pos="0.326905 -2.760860 6.555664" range="0.361938" height="0.904845" />
						<point pos="-2.862058 -6.160862 10.182313" range="0.366156" height="0.915390" />
						<point pos="6.520141 -6.160862 -6.877991" range="0.366760" height="0.916900" />
						<point pos="0.265260 -2.760860 10.365541" range="0.373596" height="0.933990" />
						<point pos="-2.867920 -6.160862 4.558532" range="0.381348" height="0.928164" />
						<point pos="-1.626098 0.639141 -10.669434" range="0.381531" height="0.953828" />
						<point pos="3.207155 14.239140 6.577085" range="0.383362" height="0.958405" />
						<point pos="5.516847 -6.160862 -9.881775" range="0.384216" height="0.960540" />
						<point pos="-6.590820 7.439140 9.017396" range="0.385742" height="0.964355" />
						<point pos="-0.087526 14.239140 5.640808" range="0.386597" height="0.966493" />
						<point pos="-0.899170 0.639141 -9.134765" range="0.386841" height="0.967103" />
						<point pos="-4.523071 14.239140 -6.903076" range="0.391846" height="0.979615" />
						<point pos="-5.704223 -6.160862 -1.811707" range="0.394531" height="0.986328" />
						<point pos="-6.456664 0.639141 -6.914490" range="0.403259" height="1.008147" />
						<point pos="5.095583 -2.760860 10.315917" range="0.407043" height="1.017608" />
						<point pos="3.927860 14.239140 10.297667" range="0.408532" height="1.021330" />
						<point pos="3.616211 -5.833162 -10.345643" range="0.409375" height="1.023438" />
						<point pos="-3.156863 -5.833162 7.009337" range="0.409375" height="1.023438" />
						<point pos="-2.897462 7.439140 8.146057" range="0.410278" height="1.025695" />
						<point pos="-6.563719 0.639141 -3.735291" range="0.412842" height="1.032105" />
						<point pos="-4.374756 7.439140 2.412353" range="0.418579" height="1.046448" />
						<point pos="-6.550171 -6.160862 -1.054626" range="0.426392" height="1.065980" />
						<point pos="-6.551270 -6.160862 6.500182" range="0.426758" height="1.066895" />
						<point pos="0.037841 10.839138 -9.791748" range="0.436035" height="1.090088" />
						<point pos="-4.615966 14.239140 -5.962892" range="0.438354" height="1.095885" />
						<point pos="-1.947875 -2.760860 6.647399" range="0.438599" height="1.096498" />
						<point pos="-3.340699 8.090145 9.983093" range="0.443750" height="1.109375" />
						<point pos="0.518433 -5.833162 -9.900756" range="0.443750" height="1.109375" />
						<point pos="-1.385132 14.561039 -9.875976" range="0.443750" height="1.109375" />
						<point pos="5.324463 14.239140 2.452941" range="0.459167" height="1.147918" />
						<point pos="2.505493 -6.160862 -3.852539" range="0.463684" height="0.862501" />
						<point pos="3.028566 -2.760860 10.258055" range="0.465027" height="1.162567" />
						<point pos="1.737061 -19.760811 1.297729" range="0.468750" height="1.171875" />
						<point pos="-6.505858 0.639141 -5.381774" range="0.470703" height="1.176758" />
						<point pos="2.876466 14.239140 10.251526" range="0.471436" height="1.178590" />
						<point pos="0.301392 14.239140 10.145141" range="0.475098" height="1.187745" />
						<point pos="-4.468874 7.439140 10.169617" range="0.483765" height="1.209413" />
						<point pos="-3.604614 0.639141 -10.471864" range="0.488037" height="1.220093" />
						<point pos="-6.161742 14.239140 -3.738160" range="0.489685" height="1.224213" />
						<point pos="6.437743 10.839138 -9.226257" range="0.517456" height="1.293640" />
						<point pos="-3.016847 -6.160862 8.615602" range="0.529663" height="1.324158" />
						<point pos="4.491212 14.239140 9.531982" range="0.542069" height="1.355173" />
						<point pos="6.431152 -6.160862 -5.392334" range="0.542358" height="1.355895" />
						<point pos="3.306763 14.239140 2.545592" range="0.551819" height="1.379548" />
						<point pos="-1.764648 0.639141 -5.844604" range="0.554382" height="1.385955" />
						<point pos="6.385621 -6.160862 -3.377320" range="0.568054" height="1.420135" />
						<point pos="3.802004 -2.760860 7.386718" range="0.570190" height="1.425475" />
						<point pos="4.390993 14.239140 6.773986" range="0.580261" height="1.450652" />
						<point pos="-1.795534 14.239140 6.965637" range="0.590942" height="1.477355" />
						<point pos="4.850098 10.839138 -10.451841" range="0.598022" height="1.495055" />
						<point pos="-0.948613 -2.760860 9.110961" range="0.637085" height="1.592713" />
						<point pos="1.479858 10.839138 -10.401550" range="0.648315" height="1.620788" />
						<point pos="-6.304201 -6.160862 9.371885" range="0.672363" height="1.680907" />
						<point pos="6.300661 -2.760860 9.153014" range="0.672852" height="1.682130" />
						<point pos="-1.406005 14.239140 -7.191163" range="0.679932" height="1.699830" />
						<point pos="2.247925 10.839138 -7.197021" range="0.685791" height="1.714478" />
						<point pos="2.587525 -6.160862 -7.337036" range="0.825806" height="2.064515" />
						<point pos="-1.546021 -6.160862 5.211243" range="0.840454" height="2.080153" />
						<point pos="-5.975829 14.239140 -5.504273" range="0.896973" height="2.080154" />
						<point pos="-5.980224 14.239140 -8.169862" range="0.948731" height="2.080154" />
				</container>
				</group>
				<!--End of new high rise apartment loot entry-->
	
Save your edited mapgroupproto.xml and re-upload if necessary.

Restart your community server and loot should start to appear in the high-rise apartments.

Please note that on local servers you may have to delelete your storage_1 folder to reset your server to see changes.

Also please note that we are adding many more potential loot placements for food and clothes, so it may be worth considering
increasing their numbers to compensate.

Thanks, Rob.