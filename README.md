# configs
//WAVY'S CONFIG/AUTOEXEC
   //PART 1: BINDS
    //1.1 Buy Binds

     //1.1.1  Full buy
       bind "kp_5" "buy ak47; buy m4a1; buy vesthelm; buy defuser; buy flashbang; buy flashbang; buy hegrenade; buy smokegrenade;"

     //1.1.2 Weapons
       //1.1.2.1 Rifles
       bind "kp_leftarrow" "buy galilar; buy famas;"
       bind "kp_rightarrow" "buy awp;"
 
       //1.1.2.2 Pistols
       bind "kp_home" "buy tec9; buy fiveseven;"
       bind "kp_uparrow" "buy deagle;"
       bind "kp_pgup" "buy p250;"
 
       //1.1.2.3 SMG'S
       bind "kp_end" "buy mp7;"
       bind "kp_downarrow" "buy mac10; buy mp9;"
       bind "kp_pgdn" "buy vesthelm;"

       //1.1.3 Nades
       //1.1.3.1 Full Nade Stack
       bind "kp_ins" "buy smokegrenade; buy hegrenade; buy flashbang; buy flashbang;"
       bind "kp_del" "buy flashbang; buy flashbang; buy smokegrenade; buy molotov; buy incgrenade;"
 
       //1.1.3.2 Apart nade binds
       bind "kp_slash" "buy molotov; buy incgrenade;"
       bind "kp_multiply" "buy flashbang;"
       bind "kp_minus" "buy smokegrenade;"
       bind "kp_plus" "buy hegrenade;"
       bind "kp_enter" "buy deagle; buy vesthelm; buy flashbang; buy flashbang"
 
    //1.2 Select binds

      //1.2.1  Switch Binds (Nades)
       bind "mouse5" "use weapon_knife; use weapon_smokegrenade"
       bind "mouse4" "use weapon_knife; use weapon_flashbang"
       bind "v" "use weapon_knife; use weapon_incgrenade; use weapon_molotov"
	   bind "capslock" "use weapon_knife; use weapon_hegrenade"

      //1.2.2  Switch Binds (Q)
	   alias +knife slot3
	   alias -knife lastinv
	   bind q +knife


    //1.3 Other Binds

      //1.3.1  Jump bind
       bind "MWHEELUP" "+jump"
       bind "MWHEELDOWN" "+jump"
       bind "SPACE" "+jump"
	   
	  //1.3.2 Bomb drop
	   bind m +dropBomb
	   alias +dropBomb "use weapon_knife; use weapon_c4; drop"
	 
	  //1.3.3 Fake flash
	   bind "x" "use weapon_knife; use weapon_p250; use weapon_hkp2000; use weapon_glock; use weapon_tec9; use weapon_fiveseven; use weapon_deagle; drop"
	   
	  //1.3.4 Hand
	   bindToggle "h" "cl_righthand" 
	   
   //PART 2: VISUALS
    //1.1 Viewmodel
	   viewmodel_fov 69
	   viewmodel_presetpos 0
	   viewmodel_offset_x "2.5"
	   viewmodel_offset_y "2.5"
	   viewmodel_offset_z "-1.7"

	   cl_viewmodel_shift_left_amt "0"
	   cl_viewmodel_shift_right_amt "0"

	   cl_bobamt_lat 0.1
	   cl_bob_lower_amt "0"
	   cl_bobamt_vert 0.1
	   cl_bobcycle 2

	   cl_wpn_sway_scale 0  


    //1.2  Crosshair
       //cl_crosshairalpha "200";cl_crosshaircolor "0"; cl_crosshairdot "0";cl_crosshairgap "-1.1";cl_crosshairsize "0.9";cl_crosshairstyle "4";cl_crosshairusealpha "1";cl_crosshairthickness "0.6";cl_fixedcrosshairgap "0";cl_crosshair_outlinethickness "0.8";cl_crosshair_drawoutline "1";
	   //Or i use the default static one with cl_fixedcrosshairgap -15
	   cl_fixedcrosshairgap -8
	   
	//1.3 Others
	 r_drawtracers_firstperson "0" 
	 r_eyegloss "0" 
	 r_eyemove "0"
	 r_eyeshift_x "0"
	 r_eyeshift_y "0" 
	 r_eyeshift_z "0"
	 r_eyesize "0" 


   //PART 3: INTERNET
    //1.1 INTERPOLATION/RATE
	   rate "786432"
	   cl_updaterate "128"
	   cl_cmdrate "128" 
	   cl_interp "0"
	   cl_interp_ratio "1"
	   cl_predict "1"
	   cl_predictweapons "1"
	   cl_lagcompensation "1"
	   

   //PART 4: OTHER COMMANDS
    //1.1 HUD
	   cl_alwaysshowinventory
	   cl_showloadout 1
	
	//1.2 FPS
	   fps_max 0
	   fps_max_menu 0
	
	//1.3 SOUND
	   snd_headphone_pan_exponent 2
	   
	//1.4 OTHERS
	   cl_disablefreezecam 1
	   clanid 29312184
	   bind "n" "+spray_menu"
	   exec slam
	 
host_writeconfig
