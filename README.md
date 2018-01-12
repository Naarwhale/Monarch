# Monarch
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" dir="ltr" style="overflow: auto;" class="gr__monarch_aop_com" lang="en"><head>
		<meta http-equiv="X-UA-Compatible" content="IE=Edge">
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
		<title>Monarch |  Daniel  Ramjitsingh</title>
		
		<link rel="shortcut icon" href="/img/favicon.ico" type="image/x-icon">

		<link rel="stylesheet" href="/css/gl-presentation.css?v=6.0.0" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/css/gl-presentation-ext.css?v=6.0.0" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="//code.jquery.com/ui/1.10.2/themes/smoothness/jquery-ui.min.css" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/js/gl-audio-manager/css/audio-manager.css" type="text/css">
		<link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css">
		<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Oswald:400,700,300|Lato:300,400,700" type="text/css">
		<link rel="stylesheet" href="//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css">
		<link rel="stylesheet" href="//releases.flowplayer.org/5.5.2/skin/minimalist.css">
		<link rel="stylesheet" href="/js/jquery-ui/base/ui.all.css?v=6.0.0" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/css/themes/base.css?v=6.0.0">
		<link rel="stylesheet" href="/css/themes/aop-desktop/style.css" id="theme">
		<link rel="stylesheet" href="/css/app/calendar.min.css">
		<link rel="stylesheet" href="/css/games.css?v=6.0.0" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/css/dla_fixes_local.css?v=6.0.0" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/css/app/helpers.css?v=6.0.0" type="text/css">

		<script async="" src="//www.google-analytics.com/analytics.js"></script><script type="text/javascript" src="//code.jquery.com/jquery-1.10.2.min.js"></script>
		<script type="text/javascript" src="/js/jquery/jquery.media.monarch.js"></script>
		<script type="text/javascript" src="//code.jquery.com/ui/1.10.2/jquery-ui.min.js"></script>
		<script type="text/javascript" src="/js/jquery/jstorage.min.js"></script>
		<script type="text/javascript" src="/js/jquery/jquery.PrintArea.js"></script>
		<script type="text/javascript" src="/js/jquery/jquery.layout.min.js"></script>
		<script type="text/javascript" src="//cdn.datatables.net/1.9.4/js/jquery.dataTables.js"></script>
		<script>
			// Gets around an annoying JS compatibility issue with Firefox Javascript : Must precede FLOWPLAYER...
			if (/firefox/i.test(navigator.userAgent)){
				window.oldGetComputedStyle = window.getComputedStyle;
				window.getComputedStyle = function (element, pseudoElt) {
					var t = window.oldGetComputedStyle(element, pseudoElt);
					if (t === null) return { getPropertyValue : function(){ return '' } };
					return t;
				};
			}
		</script>
		<script type="text/javascript" src="/js/flowplayer/flowplayer.min.js"></script>
		<script type="text/javascript" src="/media/globmedia/lib/requirejs/js/require.js"></script>
		<script type="text/javascript" src="/media/globmedia/html5/animationmanager/js/animationmanager.js"></script>

		<!-- Google Analytics -->
		<script type="text/javascript">userId = "202959";</script>
		<script type="text/javascript" src="/js/analytics.js"></script>

		<!-- Monarch JS - Loaded after all dependencies -->
		<script type="text/javascript" src="/js/global.js?v=6.0.0"></script>

		<!-- Vocab Arcade -->
		<script src="/js/app/arcade.js?v=6.0.0" type="text/javascript"></script>
		<!-- Script -->
		<script src="//cdnjs.cloudflare.com/ajax/libs/json2/20110223/json2.js"></script>
		<script src="//netdna.bootstrapcdn.com/bootstrap/3.0.3/js/bootstrap.min.js"></script>
		<script type="text/javascript" language="javascript" src="/js/app/dataTables.bootstrap.js"></script>
		<!-- Calendar -->
		<script type="text/javascript" src="/js/app/jstz.min.js"></script>
		<script type="text/javascript" src="/js/app/underscore-min.js"></script>
		<script type="text/javascript" src="/js/app/calendar.js"></script>
		<!-- CKEditor for HTML Editor -->
		<script src="/js/ckeditor_4.5.7/ckeditor.js"></script><style>.cke{visibility:hidden;}</style>
		<!-- Validator -->
		<script type="text/javascript" src="/js/app/jquery.validate.min.js"></script>
		<!-- Application -->
		<script src="/js/global.js?v=6.0.0"></script><script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="audiomanager" src="/media/globmedia/html5/modules/audiomanager/js/audiomanager.js"></script>
		<script type="text/javascript" src="/js/student_password.js"></script>
		

	<style type="text/css">
		.dropdown-header {
			cursor:default;padding-left:5px;
			border-bottom:#eee 1px dotted;
		}
		.schoolwork-toolbar {
			display:none;
			position:absolute;
			z-index:100;
			right:27px;
			top:300px;
			background:#F8F8F8;
			border:#E6E6E6 1px solid;
			overflow:hidden;

			-webkit-touch-callout: none;
			-webkit-user-select: none; /* Webkit */
			-moz-user-select: none;	/* Firefox */
			-ms-user-select: none;	 /* IE 10  *//
			-o-user-select: none;
			user-select: none;  
		}
		.st-link {
			padding:5px;
		}
		.schoolwork-table td {
			vertical-align:top;
			text-align:center;
		}
		#theMessage {
			color:#fff;
			display:none;
			background:red;
		}
		#theVoices {
			display:none;
			background:#EBEBEB;
		}
		.st-voices {
			padding:5px;
		}
		.st-voice {
			cursor:pointer;
			padding:3px;
			text-align:left;
			display: block;
			border: none;
			background-color:transparent;
		}
		.st-voice:hover {
			background:#F1F1F1;
		}
		#theTools {
			border-left:#E6E6E6 3px solid;
		}
		.st-link {
			color:#5B5B5B;
			cursor:pointer;
			display:block;
			border: none;
			background-color: transparent;
		}
		.st-link:hover {
			color:#909192;
		}

		.ui-dialog { background-color: white; border:1px solid gray; border-radius: 3px; padding: 3px;}
		.ui-dialog-titlebar-close { content: "x"; float: right;}
		.ui-dialog-title { background-color: #DDDDDD; text-align: left;}


		#scoreframe {
			display: block;
			position: absolute;
			width: 100%;
			left:0px;
			top:200px;
			text-align:center;
			background-color: transparent;
		}
		#scorebox {
			display: inline-block;
			width: 640px;
			background-color: white;
			border: 3px solid #CCCCAA;
			border-radius: 5px;
		}
		#scorebox .starbox {
			width: 375px;
			height: 75px;
			margin: 20px 112px;
		}
		#scorebox .star {
			width: 75px;
			height: 75px;
			margin: 0px;
			padding: 0px;
			float: left;
			line-height: 70px;
			font-size: 70px;
			text-align: center;
			vertical-align: middle;
		}
		#scorebox .gradetext, #scorebox .notetext, #scorebox .scorebuttons {
			text-align: center;
			width: 100%;
			font-size: 14pt;
			color: black;
			padding: 10px 10px 30px;
		}
		#scorebox .notetext {
			color: gray;
			font-size: 12pt;

		}

		/* The grading stars animation code */
		@keyframes goldstar {
			from {color: white; transform: rotate(360deg); font-size:10%; text-shadow: -1px -1px 0 #FFFFFF, 1px -1px 0 #FFFFFF, -1px 1px 0 #FFFFFF, 1px 1px 0 #FFFFFF; }
			to {color: yellow; transform: rotate(180deg); font-size:50%; text-shadow: -1px -1px 0 #BBBBBB, 1px -1px 0 #BBBBBB, -1px 1px 0 #BBBBBB, 1px 1px 0 #BBBBBB; }
			to {color: #FFCC00; transform: rotate(0deg); font-size:100%; text-shadow: -1px -1px 0 #777777, 1px -1px 0 #777777, -1px 1px 0 #777777, 1px 1px 0 #777777; }
		}

		@keyframes graystar {
			from {color: white; }
			to {color: #333333; }
			to {color: #CCCCCC; }
		}
		#scorebox .fa-star {
			animation-name: goldstar;
			animation-duration: 3s;
			animation-fill-mode: forwards;
			vertical-align: middle;
            color: #FFCC00;
		}
		#scorebox .fa-star-o {
			animation-name: graystar;
			animation-duration: 3s;
			animation-fill-mode: forwards;
			vertical-align: middle;
            color: #CCCCCC;
		}

		/* Offset causes default state to be shown, default state can't be hidden because of IE/Safari
		   ...until I figure  this out I'm turning off the delay offset...
		#scorebox .star1 .fa { animation-delay: 0s; }
		#scorebox .star2 .fa { animation-delay: .5s; }
		#scorebox .star3 .fa { animation-delay: .75s; }
		#scorebox .star4 .fa { animation-delay: 1s; }
		#scorebox .star5 .fa { animation-delay: 1.25s; }
		*/

	</style>

	<script>
		function findFrame(){
			//Find which frame is currently displayed
			if( $( '#doQuestions').hasClass('active') ){
				return $('#questionFrame')[0];
			} else {
				return $('#presentationFrame')[0];
			}
		}

		function sectionLoaded(){
			hideLoading();
			update_header();
		}
	</script>
	<script src="/js/monarch_texthelp_helpers.js"></script>
	<script>
		var _learner_id = '202959';
		var _upcoming_ids = ['126747151','126747580','126747917','126748137','126748346','128334357'];
		
		function show_questions(){
			$('#doQuestions').click();
		}
	</script>

<script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="assetloader" src="/media/globmedia/html5/animationmanager/js/assetloader.js"></script><script type="text/javascript" src="https://monarch.aop.com/js/ckeditor_4.5.7/config.js?t=G14E"></script><link rel="stylesheet" type="text/css" href="https://monarch.aop.com/js/ckeditor_4.5.7/skins/moono/editor_gecko.css?t=G14E"><script type="text/javascript" src="https://monarch.aop.com/js/ckeditor_4.5.7/lang/en.js?t=G14E"></script><script type="text/javascript" src="https://monarch.aop.com/js/ckeditor_4.5.7/styles.js?t=G14E"></script><script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="jquery-private" src="/media/globmedia/html5/animationmanager/js/jquery-private.js"></script><script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="jquery" src="/media/globmedia/lib/jquery/js/jquery-1.9.1.js"></script><script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="fetch" src="/media/globmedia/html5/animationmanager/js/fetch.js"></script></head>
<body data-gr-c-s-loaded="true" style="overflow: auto; margin-bottom: 0px;">

	<div id="gl-correct-answer" style="border:red 1px solid; background:yellow;position:absolute;z-index:100;left:0;top:0"></div>

	<!-- THE Modal Password-->
	<div class="modal" id="password" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
					<h4 class="modal-title" id="myModalLabel">Change Password</h4>
				</div>
				<div class="modal-body" style="padding:5px;">
						
					<table style="width:100%" border="0"><tbody><tr><td style="width:40%">
					<div class="">
						<div class="">
							<p>Make sure that your password contains:</p>
							<ul>
								<li>At least 6 characters.</li> 
								<li>At least 1 upper case letter.</li>
								<li>At least 1 lower case letter.</li> 
								<li>At least 1 number.</li> 
								<li>No spaces.</li>
							</ul>
						</div>
					</div>
					</td><td style="padding-left:18px; width:60%">
						
					<div class="mon-inline-form" id="monif-changepassword">
						<div class="monif-group">
							<div class="monif-label">Current Password</div>
							<div class="monif-input"><input id="current_password" type="password"></div><div class="monif-errors"></div>
						</div>
						<div class="monif-group">
							<div class="monif-label">New Password</div>
							<div class="monif-input"><input id="new_password" type="password"></div><div class="monif-errors"></div>
						</div>
						<div class="monif-group">
							<div class="monif-label">Verify New Password</div>
							<div class="monif-input"><input id="new_password_verification" type="password"></div><div class="monif-errors"></div>
						</div>
					</div>	
					</td></tr></tbody></table>
					
				</div>
				<div class="modal-footer">
				
					
				
					<button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
					<button type="button" id="submitPassword" class="btn btn-success" onclick="do_validate_all()">Change Password</button>
					
				</div>
			</div>
		</div>
	</div>




	<!-- THE Modal -->
	<div class="modal" id="theModal" tabindex="-1" role="dialog" aria-labelledby="theModalTitle" aria-hidden="true">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
					<h4 class="modal-title" id="theModalTitle">Modal title</h4>
				</div>
				<div class="modal-body">
					...
				</div>
				<div class="modal-footer">
					<button type="button" class="btn btn-warning" data-dismiss="modal">Cancel</button>
					<button type="button" id="markAsCompleteGo" class="btn btn-success" onclick="complete_lesson_go()">Mark Lesson as Complete</button>
				</div>
			</div>
		</div>
	</div>
	<div class="modal" id="iframeModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
					<h4 class="modal-title" id="iframeModalLabel"></h4>
				</div>
				<div class="modal-body clearfix">
					...
				</div>
				<!-- <div class="modal-footer"></div> -->
			</div>
		</div>
	</div>



	<!-- Navigation -->
	<div class="mcl-mode" style="display: none;"></div>
	<div class="all-navigation">
		<nav class="navbar" role="navigation">
			<div class="container">
				<div class="navbar-header">
					<a class="navbar-brand" href="/student#schoolwork">
						<img class="small-logo" src="/img/monarch-m.png">
					</a>
				</div>
				<ul class="nav navbar-nav navbar-right">
					<li data-state="home" class="section-nav active"><a><span class="glyphicon glyphicon-home"></span><br>Home</a></li>
					<li data-state="learn" class="section-nav"><a><span class="glyphicon glyphicon-book"></span><br>Learn</a></li>
					<li data-state="message" class="section-nav"><a><span class="glyphicon glyphicon-comment"></span><br>Message</a></li>
					<li data-state="help" class="section-nav"><a><span class="glyphicon glyphicon-question-sign"></span><br>Help</a></li>
					<li class="dropdown">
						<a class="dropdown-toggle" data-toggle="dropdown"><span class="glyphicon glyphicon-user"></span>
						<br>Daniel<b class="caret"></b>
						</a>
						<ul class="dropdown-menu">
							<li>
								<div class="dropdown-header">Themes</div>
								<div class="swap-themes">
								
									<div>
										<div class="swap-theme" data-theme="default">
											<div class="swap-theme-color color-blue"></div>
										</div>
										<div class="swap-theme" data-theme="default-purple">
											<div class="swap-theme-color color-purple"></div>
										</div>
										<div class="swap-theme" data-theme="default-green">
											<div class="swap-theme-color color-green"></div>
										</div>
										<div class="swap-theme" data-theme="default-orange">
											<div class="swap-theme-color color-orange"></div>
										</div>
										<div class="swap-theme" data-theme="default-red">
											<div class="swap-theme-color color-red"></div>
										</div>
									</div>
									
									
									
									<div class="swap-theme" data-theme="aop-chess"><img src="/css/themes/aop-chess/img/thumbnail.png"></div>
									<div class="swap-theme" data-theme="aop-sea"><img src="/css/themes/aop-sea/img/thumbnail.png"></div>
									<div class="swap-theme active-theme" data-theme="aop-desktop"><img src="/css/themes/aop-desktop/img/thumbnail.png"></div>
									<div class="swap-theme" data-theme="aop-west"><img src="/css/themes/aop-west/img/thumbnail.png"></div>
									<div class="swap-theme" data-theme="aop-field"><img src="/css/themes/aop-field/img/thumbnail.png"></div>
									<div class="swap-theme" data-theme="aop-birds"><img src="/css/themes/aop-birds/img/thumbnail.png"></div>
								</div>
							</li>
							<!-- 
							<li>
								<div class="dropdown-header">Style</div>
								<div class="swap-themes">
									<div class="swap-theme" data-theme="default">Blue</div>
									<div class="swap-theme" data-theme="mon-hummingbirds">Birds</div>
									<div class="swap-theme" data-theme="mon-balloon">Balloon</div>
									<div class="swap-theme" data-theme="mon-sports">Sports</div>
									<div class="swap-theme" data-theme="mon-desktop">Desktop</div>
									<div class="swap-theme" data-theme="mon-undersea">Sea</div>
									<div class="swap-theme" data-theme="mon-noah">Ark</div>
								</div>
							</li>
							 -->
							<li class="dropdown-header">Settings</li>
							<li><a role="menuitem" data-toggle="modal" tabindex="-1" href="#password">Change Password</a></li>
							<li data-state="exit"><a href="javascript:sign_out();">Sign Out</a></li>
						</ul>
					</li>
				</ul>
			</div>
		</nav>
		<div class="monarch-submenus">
			<div class="container">
				<div id="home-submenu" class="monarch-submenu active" style="display: block;">
					<div class="ms active" data-state="schoolwork">Schoolwork</div>
					<div class="ms" data-state="calendar">Calendar</div>
				</div>
				<div id="learn-submenu" class="monarch-submenu active" style="display: none;">
					<div class="ms" data-state="assignments">Assignments</div>
					<div id="readAction" class="ms" data-state="courses">Courses</div>
					<div id="readStatus" class="ms-read">
						<div class="mcl-assignment" data-problem-count="7">Skills of Oral Reading</div>
						<div class="mcl-course">English II</div>
					</div>					
					<div id="doQuestions" class="ms ms-right" data-state="question" style="display: block;">Questions</div>
					<div id="doRead" class="ms ms-right active" data-state="read" style="display: block;">Read</div>
				</div>
				<div id="message-submenu" class="monarch-submenu" style="display: none;">
					<div id="messages_compose" class="ms ms-right" data-state="messages_compose">Compose</div>
					<div class="ms active" data-state="messages_inbox">Inbox</div>
					<!-- <div class="ms" data-state="messages_archive">Archived</div>  -->
					<div class="ms" data-state="messages_sent">Sent</div>
					<div id="messages_refresh" class="ms ms-blocked"><span class="fa fa-refresh"></span></div>
				</div>
				<div id="help-submenu" class="monarch-submenu" style="display: none;">
					<div class="ms ms-right ms-blocked"><!-- 1-800-622-3070 --></div>
					<div class="ms active" data-state="help">Contact</div>
					<!--   <div class="ms" data-state="help_news">What's New</div> -->
				</div>
			</div>
		</div>
	</div>
	
	<!-- Read/Problems Toolbar -->

	<div class="schoolwork-toolbar" style="display: none;">
		<table class="schoolwork-table">
			<tbody><tr>
				<td id="theVoices">
					<div class="st-voices">

						<button class="st-voice" onclick="readLessonAs('allison');">Allison</button>
						<button class="st-voice" onclick="readLessonAs('ava');">Ava</button>
						<button class="st-voice" onclick="readLessonAs('samantha');">Samantha</button>
						<button class="st-voice" onclick="readLessonAs('serena');">Serena</button>
						<button class="st-voice" onclick="readLessonAs('daniel');">Daniel</button>
						<button class="st-voice" onclick="readLessonAs('tom');">Tom</button>
					</div>
				</td>
				<td id="theTools">
			
					<button class="st-link" id="printCurrent" title="Print"><span class="fa fa-print"></span></button>
					<button class="st-link" id="speakSelected" title="Speak as.." onclick="$('#theVoices').toggle();">
						<span class="fa fa-volume-up"></span>
					</button>

					<button class="st-link" id="startSpeech" title="Start Speaking.." onclick="readLesson();">
						<span class="fa fa-play"></span>
					</button>
					<button class="st-link" id="pauseSpeech" title="Pause Speaking.." onclick="event_pause();">
						<span class="fa fa-pause"></span>
					</button>
					<button class="st-link" id="stopSelected" title="Stop Speaking.." onclick="stopSpeech();">
						<span class="fa fa-stop"></span>
					</button>

					
				</td>
			</tr>
		</tbody></table>
	</div>

	<!-- View -->
	<div id="main-content">
	
		<div class="monarch-loading" style="display: none;"><img src="/img/app/loader.gif"></div>

		<!-- In Progress -->
		<div id="schoolwork" class="ms-view" data-state="schoolwork" style="display: block;"><div class="container">
	<div class="row">
		<div class="col-xs-12 col-sm-6 col-md-8">
			<div>
				<div class="area-header">Assignments</div>
				<div><div><div class="schoolwork-link" data-id="126747151" data-course-id="127690"><div class="sl-1"><span class="fa fa-file" style="color:#ccc; margin-right:5px; display:none;"></span>Division of the Land (Part II)</div><div class="sl-2">Old Testament Survey - ISRAEL IN CANAAN</div><div class="sl-3">Due January 17th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747580" data-course-id="127869"><div class="sl-1"><span class="fa fa-file" style="color:#ccc; margin-right:5px; display:none;"></span>Absolutism in France</div><div class="sl-2">World History - GROWTH OF WORLD EMPIRES</div><div class="sl-3">Due January 15th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747917" data-course-id="128068"><div class="sl-1"><span class="fa fa-file" style="color:#ccc; margin-right:5px; display:none;"></span>Skills of Oral Reading</div><div class="sl-2">English II - WRITING AND READING SKILLS</div><div class="sl-3">Due January 12th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126748137" data-course-id="128562"><div class="sl-1"><span class="fa fa-check-circle-o" style="color:#ccc; margin-right:5px; display:none;"></span>Quiz 1</div><div class="sl-2">Biology - CELLS</div><div class="sl-3">Due January 15th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126748346" data-course-id="130470"><div class="sl-1"><span class="fa fa-check-circle-o" style="color:#ccc; margin-right:5px; display:none;"></span>Quiz 4: Reduction Formulas</div><div class="sl-2">Pre-calculus - TRIGONOMETRIC FUNCTIONS</div><div class="sl-3">Due January 12th, 2018</div></div></div><div><div class="schoolwork-link is-behind" data-id="128334357" data-course-id="134190"><div class="sl-1"><span class="fa fa-file" style="color:#ccc; margin-right:5px; display:none;"></span>¿En qué se diferencia mi vida de la vida en México?</div><div class="sl-2">Spanish I - AMIGOS EN MÉXICO</div><div class="sl-3">Due January 11th, 2018</div></div></div></div>
			</div>
						<div class="area-header">Projects</div>
			<div> <div><div class="schoolwork-link is-behind" data-id="128334323"><div class="sl-1">Proyecto: ¡Vamos a viajar!</div><div class="sl-4">Spanish I - AMIGOS EN EL MUNDO</div><div class="sl-3">Due January 4th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747889"><div class="sl-1">Essay: Effective Writing</div><div class="sl-4">English II - WRITING EFFECTIVE SENTENCES</div><div class="sl-3">Due January 15th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747898"><div class="sl-1">Essay: Using Connectives</div><div class="sl-4">English II - WRITING AND READING SKILLS</div><div class="sl-3">Due January 18th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126748100"><div class="sl-1">Project: Research</div><div class="sl-4">Biology - TAXONOMY: KEY TO ORGANIZATION</div><div class="sl-3">Due January 15th, 2018</div></div></div><div><div class="schoolwork-link is-behind" data-id="128334349"><div class="sl-1">Proyecto: ¿Cómo es mi familia?</div><div class="sl-4">Spanish I - AMIGOS EN EE.UU.</div><div class="sl-3">Due January 9th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747142"><div class="sl-1">Report: Report of the Spies</div><div class="sl-4">Old Testament Survey - ISRAEL IN CANAAN</div><div class="sl-3">Due January 24th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747907"><div class="sl-1">Essay: Biography</div><div class="sl-4">English II - WRITING AND READING SKILLS</div><div class="sl-3">Due January 18th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747913"><div class="sl-1">Essay: Logic</div><div class="sl-4">English II - WRITING AND READING SKILLS</div><div class="sl-3">Due January 18th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747914"><div class="sl-1">Essay: Expository Essay</div><div class="sl-4">English II - WRITING AND READING SKILLS</div><div class="sl-3">Due January 18th, 2018</div></div></div><div><div class="schoolwork-link" data-id="126747149"><div class="sl-1">Report: Israel in Canaan</div><div class="sl-4">Old Testament Survey - ISRAEL IN CANAAN</div><div class="sl-3">Due January 24th, 2018</div></div></div></div>
					</div>
		<div class="col-xs-12 col-sm-6 col-md-4">
			<div class="area-header">Messages</div>
			<div class="area-message-container">
				
				<div class="mon-messages"><div class="mm-title-empty"><span class="fa fa-comment"></span> You have no unread messages.</div>				</div>
				
				<!-- Adding inbox and new message button -->
				<div class="mon-message-actions">
  			<div class="btn-group btn-group-sm" style="padding:0px 0px 0px 0px; float:right">
					<button type="button" class="btn btn-default" onclick="window.location.href='#messages_inbox'"><span class="fa fa-inbox"></span> Inbox</button>
					<button type="button" class="btn btn-default" onclick="window.location.href='#messages_compose'"><span class="fa fa-pencil-square"></span> New Message</button>
					
			</div>
				</div>
			<!-- // Adding inbox and new message button -->				
			</div>
			
						
			
			<div class="area-header">Resources</div>
			<div class="mon-settings">				
					<div class="mon-setting">
						<div class="sl-1"><a href="#help">Student Guide</a></div>
						<div class="sl-2">How to use Monarch.</div>
					</div>
					<div id="math_operantics" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('Operantics');">Operantics</a></div>
						<div class="sl-2">Practice math facts in a fun new way.</div>
					</div>
					<div id="math_fact_quest" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('FactQuest');">Fact Quest</a></div>
						<div class="sl-2">Learn how to find multiples of a random number.</div>
					</div>
					<div id="math_times_tables" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('TimesTables');">Times Tables</a></div>
						<div class="sl-2">Practice your times tables with interactive flashcards.</div>
					</div>
					<div id="geography_state_capitals" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('StateCapitals');">State Capitals</a></div>
						<div class="sl-2">Memorize the state capitals using tried and true flash cards.</div>
					</div>
					<div id="geography_world_capitals" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('WorldCapitals');">World Capitals</a></div>
						<div class="sl-2">Wouldn't it be nice to know all of the world capitals?</div>
					</div>
					<div id="history_timeline" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('Timeline');">Timeline</a></div>
						<div class="sl-2">Browse through the history of the world.</div>
					</div>
					<div id="periodic_table" class="mon-setting ">
						<div class="sl-1"><a href="javascript:void(0);" onclick="doPlay('PeriodicTable');">Periodic Table of Elements</a></div>
						<div class="sl-2">Learn about the elements that make up this world.</div>
					</div>				
			</div>
		</div>
		
		
	</div>
</div></div>
		<div class="ms-view" data-state="calendar" style="display: none;"><div class="container">
	<div class="page-header">
		<div class="pull-right form-inline">
			<div class="btn-group">
				<button class="btn btn-default" data-calendar-nav="prev">&lt;&lt; Prev</button>
				<button class="btn" data-calendar-nav="today">Today</button>
				<button class="btn btn-default" data-calendar-nav="next">Next &gt;&gt;</button>
			</div>
			<div class="btn-group">
				<button class="btn btn-default" data-calendar-view="month">Month</button>
				<button class="btn btn-default active" data-calendar-view="week">Week</button>
				<!-- <button class="btn" data-calendar-view="day">Day</button>  -->
			</div>
		</div>
		<h3>January 2018</h3>
	</div>
	<div id="calendar" style="width: 100%;" class="cal-context"><div class="cal-week-box">
	<div class="cal-offset1 cal-column"></div>
	<div class="cal-offset2 cal-column"></div>
	<div class="cal-offset3 cal-column"></div>
	<div class="cal-offset4 cal-column"></div>
	<div class="cal-offset5 cal-column"></div>
	<div class="cal-offset6 cal-column"></div>
	<div class="cal-row-fluid cal-row-head">
		
			<div class="cal-cell1 cal-day-weekend" data-toggle="tooltip" title="" data-original-title="">Sunday<br>
				<small><span data-cal-date="2018-01-07" data-cal-view="day">7 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 " data-toggle="tooltip" title="" data-original-title="">Monday<br>
				<small><span data-cal-date="2018-01-08" data-cal-view="day">8 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 " data-toggle="tooltip" title="" data-original-title="">Tuesday<br>
				<small><span data-cal-date="2018-01-09" data-cal-view="day">9 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 " data-toggle="tooltip" title="" data-original-title="">Wednesday<br>
				<small><span data-cal-date="2018-01-10" data-cal-view="day">10 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 " data-toggle="tooltip" title="" data-original-title="">Thursday<br>
				<small><span data-cal-date="2018-01-11" data-cal-view="day">11 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 cal-day-today" data-toggle="tooltip" title="" data-original-title="">Friday<br>
				<small><span data-cal-date="2018-01-12" data-cal-view="day">12 Jan</span></small>
			</div>
			
		
			<div class="cal-cell1 cal-day-weekend" data-toggle="tooltip" title="" data-original-title="">Saturday<br>
				<small><span data-cal-date="2018-01-13" data-cal-view="day">13 Jan</span></small>
			</div>
			
		
	</div>
	
	
<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747142" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="" data-status="can_work " class="cal-event-week event126747142">
			Report: Report of the Spies
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126747573" data-course="World History" data-subject="historyandgeography" data-unit="RENAISSANCE AND REFORMATION" data-course-id="127869" data-completed="2018-01-08 07:39:00" data-status="node_completed can_work " class="cal-event-week event126747573">
			Quiz 2: The Reformation
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747889" data-course="English II" data-subject="languagearts" data-unit="WRITING EFFECTIVE SENTENCES" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747889">
			Essay: Effective Writing
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747898" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747898">
			Essay: Using Connectives
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747907" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747907">
			Essay: Biography
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126748100" data-course="Biology" data-subject="science" data-unit="TAXONOMY: KEY TO ORGANIZATION" data-course-id="128562" data-completed="" data-status="can_work " class="cal-event-week event126748100">
			Project: Research
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-test" data-event-class="test">
		<a href="javascript:void(0)" data-event-id="126748129" data-course="Biology" data-subject="science" data-unit="CHEMISTRY OF LIFE" data-course-id="128562" data-completed="2018-01-08 11:38:01" data-status="node_completed can_work " class="cal-event-week event126748129">
			Test
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126748342" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="2018-01-08 08:25:15" data-status="node_completed can_work " class="cal-event-week event126748342">
			Quiz 2: Evaluation of Functions
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="128334349" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN EE.UU." data-course-id="134190" data-completed="" data-status="past_due can_work " class="cal-event-week event128334349">
			Proyecto: ¿Cómo es mi familia?
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset1 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="128334351" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN EE.UU." data-course-id="134190" data-completed="2018-01-09 06:02:32" data-status="node_completed can_work " class="cal-event-week event128334351">
			Repaso
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747142" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="" data-status="can_work " class="cal-event-week event126747142">
			Report: Report of the Spies
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747144" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="2018-01-09 06:47:36" data-status="node_completed can_work " class="cal-event-week event126747144">
			Conquest of the Land
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-test" data-event-class="test">
		<a href="javascript:void(0)" data-event-id="126747575" data-course="World History" data-subject="historyandgeography" data-unit="RENAISSANCE AND REFORMATION" data-course-id="127869" data-completed="2018-01-09 11:53:44" data-status="node_completed can_work " class="cal-event-week event126747575">
			Test: Renaissance and Reformation
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747889" data-course="English II" data-subject="languagearts" data-unit="WRITING EFFECTIVE SENTENCES" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747889">
			Essay: Effective Writing
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747898" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747898">
			Essay: Using Connectives
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747907" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747907">
			Essay: Biography
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747913" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747913">
			Essay: Logic
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126748100" data-course="Biology" data-subject="science" data-unit="TAXONOMY: KEY TO ORGANIZATION" data-course-id="128562" data-completed="" data-status="can_work " class="cal-event-week event126748100">
			Project: Research
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126748132" data-course="Biology" data-subject="science" data-unit="CELLS" data-course-id="128562" data-completed="2018-01-09 08:51:00" data-status="node_completed can_work " class="cal-event-week event126748132">
			The Cell–An Introduction
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126748343" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="2018-01-09 18:33:42" data-status="node_completed can_work " class="cal-event-week event126748343">
			Angle Location
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="128334349" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN EE.UU." data-course-id="134190" data-completed="" data-status="past_due can_work " class="cal-event-week event128334349">
			Proyecto: ¿Cómo es mi familia?
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset2 day-highlight dh-test" data-event-class="test">
		<a href="javascript:void(0)" data-event-id="128334352" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN EE.UU." data-course-id="134190" data-completed="2018-01-10 13:18:50" data-status="node_completed can_work " class="cal-event-week event128334352">
			Examen
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747142" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="" data-status="can_work " class="cal-event-week event126747142">
			Report: Report of the Spies
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747578" data-course="World History" data-subject="historyandgeography" data-unit="GROWTH OF WORLD EMPIRES" data-course-id="127869" data-completed="2018-01-10 08:06:57" data-status="node_completed can_work " class="cal-event-week event126747578">
			Absolutism in England: 16-17th Centuries
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747889" data-course="English II" data-subject="languagearts" data-unit="WRITING EFFECTIVE SENTENCES" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747889">
			Essay: Effective Writing
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747898" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747898">
			Essay: Using Connectives
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747907" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747907">
			Essay: Biography
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747913" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747913">
			Essay: Logic
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747914" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747914">
			Essay: Expository Essay
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126748100" data-course="Biology" data-subject="science" data-unit="TAXONOMY: KEY TO ORGANIZATION" data-course-id="128562" data-completed="" data-status="can_work " class="cal-event-week event126748100">
			Project: Research
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126748133" data-course="Biology" data-subject="science" data-unit="CELLS" data-course-id="128562" data-completed="2018-01-10 11:41:51" data-status="node_completed can_work " class="cal-event-week event126748133">
			The Microscope
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126748344" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="2018-01-10 19:46:15" data-status="node_completed can_work " class="cal-event-week event126748344">
			Quiz 3: Angle Location
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset3 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="128334356" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN MÉXICO" data-course-id="134190" data-completed="2018-01-10 18:14:06" data-status="node_completed can_work " class="cal-event-week event128334356">
			¡Ay Chihuahua! ¡Hay tantas culturas en México!
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747142" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="" data-status="can_work " class="cal-event-week event126747142">
			Report: Report of the Spies
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126747146" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="2018-01-11 07:10:36" data-status="node_completed can_work " class="cal-event-week event126747146">
			Quiz 1: Conquest of the Land
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747889" data-course="English II" data-subject="languagearts" data-unit="WRITING EFFECTIVE SENTENCES" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747889">
			Essay: Effective Writing
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747898" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747898">
			Essay: Using Connectives
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747907" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747907">
			Essay: Biography
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747913" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747913">
			Essay: Logic
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747914" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747914">
			Essay: Expository Essay
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126747915" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="2018-01-11 08:19:52" data-status="node_completed can_work " class="cal-event-week event126747915">
			Quiz 3: Reading Skills
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747916" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="2018-01-11 10:43:05" data-status="node_completed can_work " class="cal-event-week event126747916">
			Value, Nature, and Role of Oral Reading
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126748100" data-course="Biology" data-subject="science" data-unit="TAXONOMY: KEY TO ORGANIZATION" data-course-id="128562" data-completed="" data-status="can_work " class="cal-event-week event126748100">
			Project: Research
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126748345" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="2018-01-11 13:04:51" data-status="node_completed can_work " class="cal-event-week event126748345">
			Reduction Formulas
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset4 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="128334357" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN MÉXICO" data-course-id="134190" data-completed="" data-status="past_due can_work " class="cal-event-week event128334357">
			¿En qué se diferencia mi vida de la vida en México?
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747142" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="" data-status="can_work " class="cal-event-week event126747142">
			Report: Report of the Spies
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747147" data-course="Old Testament Survey" data-subject="bible" data-unit="ISRAEL IN CANAAN" data-course-id="127690" data-completed="2018-01-12 07:47:35" data-status="node_completed can_work " class="cal-event-week event126747147">
			Division of the Land (Part I)
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747579" data-course="World History" data-subject="historyandgeography" data-unit="GROWTH OF WORLD EMPIRES" data-course-id="127869" data-completed="2018-01-12 07:28:28" data-status="node_completed can_work " class="cal-event-week event126747579">
			Absolutism in England: 17th Century
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747889" data-course="English II" data-subject="languagearts" data-unit="WRITING EFFECTIVE SENTENCES" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747889">
			Essay: Effective Writing
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747898" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747898">
			Essay: Using Connectives
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747907" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747907">
			Essay: Biography
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747913" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747913">
			Essay: Logic
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126747914" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747914">
			Essay: Expository Essay
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126747917" data-course="English II" data-subject="languagearts" data-unit="WRITING AND READING SKILLS" data-course-id="128068" data-completed="" data-status="can_work " class="cal-event-week event126747917">
			Skills of Oral Reading
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-project" data-event-class="project">
		<a href="javascript:void(0)" data-event-id="126748100" data-course="Biology" data-subject="science" data-unit="TAXONOMY: KEY TO ORGANIZATION" data-course-id="128562" data-completed="" data-status="can_work " class="cal-event-week event126748100">
			Project: Research
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-quiz" data-event-class="quiz">
		<a href="javascript:void(0)" data-event-id="126748346" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="" data-status="can_work " class="cal-event-week event126748346">
			Quiz 4: Reduction Formulas
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="126748347" data-course="Pre-calculus" data-subject="mathematics" data-unit="TRIGONOMETRIC FUNCTIONS" data-course-id="130470" data-completed="" data-status="cant_work " class="cal-event-week event126748347">
			Quadrantal Angles
		</a>
	</div>
</div>

<div class="cal-row-fluid monarch-weekday" style="display:none;">
	<div class="monarch-event cal-cell1 cal-offset5 day-highlight dh-lesson" data-event-class="lesson">
		<a href="javascript:void(0)" data-event-id="128334358" data-course="Spanish I" data-subject="electives" data-unit="AMIGOS EN MÉXICO" data-course-id="134190" data-completed="" data-status="cant_work " class="cal-event-week event128334358">
			¡Vamos a la playa!
		</a>
	</div>
</div>

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
	
</div>
<div class="monarch-days">
	<div id="day1" class="monarch-day">&nbsp;<div class="mon-no-schoolwork">No Schoolwork<br>Assigned Today</div></div>
	<div id="day2" class="monarch-day">&nbsp;<div class="monarch-day-event can_work  monarch-bible" data-id="126747142" data-course-id="127690" data-completed=""><div class="mde-lesson">
			Report: Report of the Spies
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-historyandgeography" data-id="126747573" data-course-id="127869" data-completed="2018-01-08 07:39:00"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Quiz 2: The Reformation
		</div><div class="mde-unit">RENAISSANCE AND REFORMATION</div><span class="label mde-course">World History</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747889" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Effective Writing
		</div><div class="mde-unit">WRITING EFFECTIVE SENTENCES</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747898" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Using Connectives
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747907" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Biography
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-science" data-id="126748100" data-course-id="128562" data-completed=""><div class="mde-lesson">
			Project: Research
		</div><div class="mde-unit">TAXONOMY: KEY TO ORGANIZATION</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-science" data-id="126748129" data-course-id="128562" data-completed="2018-01-08 11:38:01"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Test
		</div><div class="mde-unit">CHEMISTRY OF LIFE</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-mathematics" data-id="126748342" data-course-id="130470" data-completed="2018-01-08 08:25:15"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Quiz 2: Evaluation of Functions
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event past_due can_work  monarch-electives" data-id="128334349" data-course-id="134190" data-completed=""><div class="mde-lesson">
			Proyecto: ¿Cómo es mi familia?
		</div><div class="mde-unit">AMIGOS EN EE.UU.</div><span class="label mde-course">Spanish I</span></div><div class="monarch-day-event node_completed can_work  monarch-electives" data-id="128334351" data-course-id="134190" data-completed="2018-01-09 06:02:32"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Repaso
		</div><div class="mde-unit">AMIGOS EN EE.UU.</div><span class="label mde-course">Spanish I</span></div></div>
	<div id="day3" class="monarch-day">&nbsp;<div class="monarch-day-event can_work  monarch-bible" data-id="126747142" data-course-id="127690" data-completed=""><div class="mde-lesson">
			Report: Report of the Spies
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-bible" data-id="126747144" data-course-id="127690" data-completed="2018-01-09 06:47:36"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Conquest of the Land
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-historyandgeography" data-id="126747575" data-course-id="127869" data-completed="2018-01-09 11:53:44"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Test: Renaissance and Reformation
		</div><div class="mde-unit">RENAISSANCE AND REFORMATION</div><span class="label mde-course">World History</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747889" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Effective Writing
		</div><div class="mde-unit">WRITING EFFECTIVE SENTENCES</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747898" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Using Connectives
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747907" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Biography
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747913" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Logic
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-science" data-id="126748100" data-course-id="128562" data-completed=""><div class="mde-lesson">
			Project: Research
		</div><div class="mde-unit">TAXONOMY: KEY TO ORGANIZATION</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-science" data-id="126748132" data-course-id="128562" data-completed="2018-01-09 08:51:00"><div class="mde-lesson"><i class="fa fa-check"></i> 
			The Cell–An Introduction
		</div><div class="mde-unit">CELLS</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-mathematics" data-id="126748343" data-course-id="130470" data-completed="2018-01-09 18:33:42"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Angle Location
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event past_due can_work  monarch-electives" data-id="128334349" data-course-id="134190" data-completed=""><div class="mde-lesson">
			Proyecto: ¿Cómo es mi familia?
		</div><div class="mde-unit">AMIGOS EN EE.UU.</div><span class="label mde-course">Spanish I</span></div><div class="monarch-day-event node_completed can_work  monarch-electives" data-id="128334352" data-course-id="134190" data-completed="2018-01-10 13:18:50"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Examen
		</div><div class="mde-unit">AMIGOS EN EE.UU.</div><span class="label mde-course">Spanish I</span></div></div>
	<div id="day4" class="monarch-day">&nbsp;<div class="monarch-day-event can_work  monarch-bible" data-id="126747142" data-course-id="127690" data-completed=""><div class="mde-lesson">
			Report: Report of the Spies
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-historyandgeography" data-id="126747578" data-course-id="127869" data-completed="2018-01-10 08:06:57"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Absolutism in England: 16-17th Centuries
		</div><div class="mde-unit">GROWTH OF WORLD EMPIRES</div><span class="label mde-course">World History</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747889" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Effective Writing
		</div><div class="mde-unit">WRITING EFFECTIVE SENTENCES</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747898" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Using Connectives
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747907" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Biography
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747913" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Logic
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747914" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Expository Essay
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-science" data-id="126748100" data-course-id="128562" data-completed=""><div class="mde-lesson">
			Project: Research
		</div><div class="mde-unit">TAXONOMY: KEY TO ORGANIZATION</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-science" data-id="126748133" data-course-id="128562" data-completed="2018-01-10 11:41:51"><div class="mde-lesson"><i class="fa fa-check"></i> 
			The Microscope
		</div><div class="mde-unit">CELLS</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-mathematics" data-id="126748344" data-course-id="130470" data-completed="2018-01-10 19:46:15"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Quiz 3: Angle Location
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event node_completed can_work  monarch-electives" data-id="128334356" data-course-id="134190" data-completed="2018-01-10 18:14:06"><div class="mde-lesson"><i class="fa fa-check"></i> 
			¡Ay Chihuahua! ¡Hay tantas culturas en México!
		</div><div class="mde-unit">AMIGOS EN MÉXICO</div><span class="label mde-course">Spanish I</span></div></div>
	<div id="day5" class="monarch-day">&nbsp;<div class="monarch-day-event can_work  monarch-bible" data-id="126747142" data-course-id="127690" data-completed=""><div class="mde-lesson">
			Report: Report of the Spies
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-bible" data-id="126747146" data-course-id="127690" data-completed="2018-01-11 07:10:36"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Quiz 1: Conquest of the Land
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747889" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Effective Writing
		</div><div class="mde-unit">WRITING EFFECTIVE SENTENCES</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747898" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Using Connectives
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747907" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Biography
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747913" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Logic
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747914" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Expository Essay
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event node_completed can_work  monarch-languagearts" data-id="126747915" data-course-id="128068" data-completed="2018-01-11 08:19:52"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Quiz 3: Reading Skills
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event node_completed can_work  monarch-languagearts" data-id="126747916" data-course-id="128068" data-completed="2018-01-11 10:43:05"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Value, Nature, and Role of Oral Reading
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-science" data-id="126748100" data-course-id="128562" data-completed=""><div class="mde-lesson">
			Project: Research
		</div><div class="mde-unit">TAXONOMY: KEY TO ORGANIZATION</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event node_completed can_work  monarch-mathematics" data-id="126748345" data-course-id="130470" data-completed="2018-01-11 13:04:51"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Reduction Formulas
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event past_due can_work  monarch-electives" data-id="128334357" data-course-id="134190" data-completed=""><div class="mde-lesson">
			¿En qué se diferencia mi vida de la vida en México?
		</div><div class="mde-unit">AMIGOS EN MÉXICO</div><span class="label mde-course">Spanish I</span></div></div>
	<div id="day6" class="monarch-day">&nbsp;<div class="monarch-day-event can_work  monarch-bible" data-id="126747142" data-course-id="127690" data-completed=""><div class="mde-lesson">
			Report: Report of the Spies
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-bible" data-id="126747147" data-course-id="127690" data-completed="2018-01-12 07:47:35"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Division of the Land (Part I)
		</div><div class="mde-unit">ISRAEL IN CANAAN</div><span class="label mde-course">Old Testament Survey</span></div><div class="monarch-day-event node_completed can_work  monarch-historyandgeography" data-id="126747579" data-course-id="127869" data-completed="2018-01-12 07:28:28"><div class="mde-lesson"><i class="fa fa-check"></i> 
			Absolutism in England: 17th Century
		</div><div class="mde-unit">GROWTH OF WORLD EMPIRES</div><span class="label mde-course">World History</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747889" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Effective Writing
		</div><div class="mde-unit">WRITING EFFECTIVE SENTENCES</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747898" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Using Connectives
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747907" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Biography
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747913" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Logic
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747914" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Essay: Expository Essay
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-languagearts" data-id="126747917" data-course-id="128068" data-completed=""><div class="mde-lesson">
			Skills of Oral Reading
		</div><div class="mde-unit">WRITING AND READING SKILLS</div><span class="label mde-course">English II</span></div><div class="monarch-day-event can_work  monarch-science" data-id="126748100" data-course-id="128562" data-completed=""><div class="mde-lesson">
			Project: Research
		</div><div class="mde-unit">TAXONOMY: KEY TO ORGANIZATION</div><span class="label mde-course">Biology</span></div><div class="monarch-day-event can_work  monarch-mathematics" data-id="126748346" data-course-id="130470" data-completed=""><div class="mde-lesson">
			Quiz 4: Reduction Formulas
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event cant_work  monarch-mathematics" data-id="126748347" data-course-id="130470" data-completed=""><div class="mde-lesson">
			Quadrantal Angles
		</div><div class="mde-unit">TRIGONOMETRIC FUNCTIONS</div><span class="label mde-course">Pre-calculus</span></div><div class="monarch-day-event cant_work  monarch-electives" data-id="128334358" data-course-id="134190" data-completed=""><div class="mde-lesson">
			¡Vamos a la playa!
		</div><div class="mde-unit">AMIGOS EN MÉXICO</div><span class="label mde-course">Spanish I</span></div></div>
	<div id="day7" class="monarch-day">&nbsp;<div class="mon-no-schoolwork">No Schoolwork<br>Assigned Today</div></div>
</div></div>

	<div class="mon-keys">
		<div class="mon-key">
			<div class="mon-example">
				<div class="me-t me-assigned">Assigned</div>
				<div class="me-d">Assignment is scheduled to be done and can be worked on now.</div>
			</div>
		</div>
		<div class="mon-key">
			<div class="mon-example">
				<div class="me-t me-pending">Pending</div>
				<div class="me-d">Assignment can not be opened until a previous assignment is completed.</div>
			</div>
		</div>
		<div class="mon-key">
			<div class="mon-example">
				<div class="me-t me-pastdue">Past Due</div>
				<div class="me-d">Incomplete assignment scheduled to be completed already.</div>
			</div>
		</div>
		<div class="mon-key">
			<div class="mon-example">
				<div class="me-t me-blocked"><i class="fa fa-times-circle"></i> Blocked</div>
				<div class="me-d">Student may not proceed until the block on the assignment is removed.</div>
			</div>
		</div>
		<div class="mon-key">
			<div class="mon-example">
				<div class="me-t me-completed"><i class="fa fa-check"></i> Completed</div>
				<div class="me-d">Assignment has been turned in.</div>
			</div>
		</div>
	</div>
</div></div>
		<div class="ms-view" data-state="assignments" style="display: none;"><div class="container">
	<div class="assignment-container">
	<table class="table">
		<thead>
	          <tr>
	            <th>Due</th>
	            <th>Unit</th>
	            <th>Title</th>
	            <th></th>
	          </tr>
	        </thead>
	        <tbody>
			<tr class="assignment-header"><td colspan="4"> Spanish I </td></tr>
		          <tr class="upcoming-work" data-id="128334357">
		            <td style="width:10%">01/11/18</td>
		            <td style="width:25%">AMIGOS EN MÉXICO</td>
		            <td>¿En qué se diferencia mi vida de la vida en México?</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	
			          <tr class="upcoming-work" data-id="128334323">
			            <td style="width:10%">01/04/18</td>
			            <td style="width:25%">AMIGOS EN EL MUNDO</td>
			            <td><span class="label label-success" style="font-size:1em;">Proyecto: ¡Vamos a viajar!</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="128334349">
			            <td style="width:10%">01/09/18</td>
			            <td style="width:25%">AMIGOS EN EE.UU.</td>
			            <td><span class="label label-success" style="font-size:1em;">Proyecto: ¿Cómo es mi familia?</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	<tr class="assignment-header"><td colspan="4"> Pre-calculus </td></tr>
		          <tr class="upcoming-work" data-id="126748346">
		            <td style="width:10%">01/12/18</td>
		            <td style="width:25%">TRIGONOMETRIC FUNCTIONS</td>
		            <td>Quiz 4: Reduction Formulas</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	<tr class="assignment-header"><td colspan="4"> Biology </td></tr>
		          <tr class="upcoming-work" data-id="126748137">
		            <td style="width:10%">01/15/18</td>
		            <td style="width:25%">CELLS</td>
		            <td>Quiz 1</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	
			          <tr class="upcoming-work" data-id="126748100">
			            <td style="width:10%">01/15/18</td>
			            <td style="width:25%">TAXONOMY: KEY TO ORGANIZATION</td>
			            <td><span class="label label-success" style="font-size:1em;">Project: Research</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	<tr class="assignment-header"><td colspan="4"> English II </td></tr>
		          <tr class="upcoming-work" data-id="126747917">
		            <td style="width:10%">01/12/18</td>
		            <td style="width:25%">WRITING AND READING SKILLS</td>
		            <td>Skills of Oral Reading</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	
			          <tr class="upcoming-work" data-id="126747889">
			            <td style="width:10%">01/15/18</td>
			            <td style="width:25%">WRITING EFFECTIVE SENTENCES</td>
			            <td><span class="label label-success" style="font-size:1em;">Essay: Effective Writing</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="126747898">
			            <td style="width:10%">01/18/18</td>
			            <td style="width:25%">WRITING AND READING SKILLS</td>
			            <td><span class="label label-success" style="font-size:1em;">Essay: Using Connectives</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="126747907">
			            <td style="width:10%">01/18/18</td>
			            <td style="width:25%">WRITING AND READING SKILLS</td>
			            <td><span class="label label-success" style="font-size:1em;">Essay: Biography</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="126747913">
			            <td style="width:10%">01/18/18</td>
			            <td style="width:25%">WRITING AND READING SKILLS</td>
			            <td><span class="label label-success" style="font-size:1em;">Essay: Logic</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="126747914">
			            <td style="width:10%">01/18/18</td>
			            <td style="width:25%">WRITING AND READING SKILLS</td>
			            <td><span class="label label-success" style="font-size:1em;">Essay: Expository Essay</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	<tr class="assignment-header"><td colspan="4"> World History </td></tr>
		          <tr class="upcoming-work" data-id="126747580">
		            <td style="width:10%">01/15/18</td>
		            <td style="width:25%">GROWTH OF WORLD EMPIRES</td>
		            <td>Absolutism in France</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	<tr class="assignment-header"><td colspan="4"> Old Testament Survey </td></tr>
		          <tr class="upcoming-work" data-id="126747151">
		            <td style="width:10%">01/17/18</td>
		            <td style="width:25%">ISRAEL IN CANAAN</td>
		            <td>Division of the Land (Part II)</td>
		            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
		          </tr>
		        	
			          <tr class="upcoming-work" data-id="126747142">
			            <td style="width:10%">01/24/18</td>
			            <td style="width:25%">ISRAEL IN CANAAN</td>
			            <td><span class="label label-success" style="font-size:1em;">Report: Report of the Spies</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        	
			          <tr class="upcoming-work" data-id="126747149">
			            <td style="width:10%">01/24/18</td>
			            <td style="width:25%">ISRAEL IN CANAAN</td>
			            <td><span class="label label-success" style="font-size:1em;">Report: Israel in Canaan</span></td>
			            <td class="assignment-actions"><!-- <a class="glyphicon glyphicon-info-sign"></a> --><span class="glyphicon glyphicon-circle-arrow-right"></span></td>
			          </tr>
			        					</tbody>
			</table>
			</div>
</div>
</div>
		<div class="ms-view" data-state="courses" style="display: none;"><div class="course-browser">
	<div class="container">
		<div id="course-carousel" class="carousel slide">
			<div class="carousel-inner">
				<div class="item active">
					<div class="carousel-header courses-header">Courses</div>
					
					<div class="panel-header-row">
						<div class="row row-fluid row-header">
							<div class="col-xs-5">Title</div>
							<div class="col-xs-1">Year</div>
							<div class="col-xs-4">Progress</div>
						</div>
					</div>
					
					<div class="m-courses">
										
						<div class="m-course m-percent0 " data-id="705842" data-id-updated="1515697335">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">Spanish I</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 22%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">22%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										
						<div class="m-course m-percent0 " data-id="697774" data-id-updated="1515701087">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">Pre-calculus</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 22%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">22%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										
						<div class="m-course m-percent0 " data-id="697773" data-id-updated="1515609703">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">Biology</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 21%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">21%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										
						<div class="m-course m-percent0 " data-id="697772" data-id-updated="1515692582">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">English II</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 27%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">27%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										
						<div class="m-course m-percent0 " data-id="697770" data-id-updated="1515767303">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">World History</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 38%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">38%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										
						<div class="m-course m-percent0 " data-id="697769" data-id-updated="1515768452">
							<div class="row row-fluid">
								<div class="col-xs-5 course-title" data-placement="bottom" data-toggle="tooltip" data-original-title="" title="">
									<div class="course-title-text">Old Testament Survey</div>
																	</div>
								<div class="col-xs-1">
									2017								</div>
								<div class="col-xs-4">
									<div class="progress">
										<div class="bar" style="width: 33%;"></div>
									</div>
								</div>
								<div class="col-xs-1 progessPercent">33%</div>
								<div class="col-xs-1">
									<span class="glyphicon glyphicon-chevron-right"></span>
								</div>
							</div>
						</div>
										</div>
				</div>
				<div class="item">
					<span class="glyphicon glyphicon-chevron-left go-back"></span>
					<div class="carousel-header units-header">Unit Title</div>
					
					<div class="panel-header-row">
						<div class="row row-fluid row-header">
							<div class="col-xs-6">Title</div>
							<div class="col-xs-3">Progress</div>
							<div class="col-xs-3">Start Date</div>
						</div>
					</div>
					
					<div class="m-units"></div>
				</div>
				<div class="item">
				
					<span class="glyphicon glyphicon-chevron-left go-back"></span>
					<div class="carousel-header assignments-header">Assignments Title</div>
					
					<div class="m-unit-grades"></div>
					
					
					
					<div class="panel-header-row">
						<div class="row row-fluid row-header">
							<div class="col-xs-1"></div>
							<div class="col-xs-5">Assignment Title</div>
							<div class="col-xs-1"><div class="hidden-sm hidden-xs">Due</div></div>
							<div class="col-xs-2">Score</div>
							<div class="col-xs-1"><div class="hidden-sm hidden-xs">Completed</div></div>
							<div class="col-xs-1">Graded</div>
							<div class="col-xs-1"></div>
						</div>
					</div>
					
					
					
					<div class="m-assignments">Loading...</div>
					
				</div>
				
				<div class="item">
				
					<span class="glyphicon glyphicon-chevron-left go-back"></span>
					<div class="carousel-header problems-header">Assignment Title</div>
					<div class="m-problems-heading"></div>
					<div class="m-problems"></div>
					
				</div>
			</div>
		</div>
	</div>
</div></div>

		<div class="ms-view" data-state="read" style="display: none;">
			<div class="m-presentation" style="height: 736px; position: relative; top: auto; left: auto;"><iframe id="presentationFrame" data-qtactive="false" class="student_presentation" src="/curriculum/section/126747917" style="" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen="true"></iframe></div>
		</div>
		<div class="m-print" style="display: none;"></div>
		<div class="ms-view" data-state="question" style="display: none;">
			<div class="m-questions" style="height: 736px; position: relative; top: auto; left: auto;"><iframe id="questionFrame" src="/curriculum/question/126747917" style=""></iframe></div>
		</div>

		<!-- Not Started -->
		<div class="ms-view" data-state="messages_compose" style="display: none;">
			<div class="ms-placeholder">
				<div class="container">
	<div class="compose-container">
		<form id="messageComposeForm" novalidate="novalidate">
			<div class="form-group">
				<label for="tosend">To : </label> <select class="form-control" tabindex="1" name="message_recipient" id="message_recipient">
																	<option value="202884">Ramjitsingh, patricia</option>
																</select>
			</div>

			<div class="form-group">
				<label for="message_subject" class="control-label">Subject : </label> <input class="form-control required" id="message_subject" name="message_subject" placeholder="Enter Subject" aria-required="true" type="text">
			
			</div>

			<div class="form-group">
				<label for="message_body" class="control-label">Message : </label>
				<textarea name="message_body" id="message_body" rows="50" class="form-control required" style="visibility: hidden; display: none;" aria-required="true">               
            </textarea><div id="cke_message_body" class="cke_1 cke cke_reset cke_chrome cke_editor_message_body cke_ltr cke_browser_gecko" dir="ltr" role="application" aria-labelledby="cke_message_body_arialbl" lang="en"><span id="cke_message_body_arialbl" class="cke_voice_label">Rich Text Editor, message_body</span><div class="cke_inner cke_reset" role="presentation"><span id="cke_1_top" class="cke_top cke_reset_all" role="presentation" style="height: auto; -moz-user-select: none;"><span id="cke_9" class="cke_voice_label">Editor toolbars</span><span id="cke_1_toolbox" class="cke_toolbox" role="group" aria-labelledby="cke_9" onmousedown="return false;"><span id="cke_14" class="cke_toolbar" aria-labelledby="cke_14_label" role="toolbar"><span id="cke_14_label" class="cke_voice_label">Basic Styles</span><span class="cke_toolbar_start"></span><span class="cke_toolgroup" role="presentation"><a id="cke_15" class="cke_button cke_button__bold cke_button_off" title="Bold" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_15_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(1,event);" onfocus="return CKEDITOR.tools.callFunction(2,event);" onclick="CKEDITOR.tools.callFunction(3,this);return false;"><span class="cke_button_icon cke_button__bold_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -24px;background-size:auto;">&nbsp;</span><span id="cke_15_label" class="cke_button_label cke_button__bold_label" aria-hidden="false">Bold</span></a><a id="cke_16" class="cke_button cke_button__italic cke_button_off" title="Italic" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_16_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(4,event);" onfocus="return CKEDITOR.tools.callFunction(5,event);" onclick="CKEDITOR.tools.callFunction(6,this);return false;"><span class="cke_button_icon cke_button__italic_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -48px;background-size:auto;">&nbsp;</span><span id="cke_16_label" class="cke_button_label cke_button__italic_label" aria-hidden="false">Italic</span></a><a id="cke_17" class="cke_button cke_button__underline cke_button_off" title="Underline" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_17_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(7,event);" onfocus="return CKEDITOR.tools.callFunction(8,event);" onclick="CKEDITOR.tools.callFunction(9,this);return false;"><span class="cke_button_icon cke_button__underline_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -144px;background-size:auto;">&nbsp;</span><span id="cke_17_label" class="cke_button_label cke_button__underline_label" aria-hidden="false">Underline</span></a><a id="cke_18" class="cke_button cke_button__strike cke_button_off" title="Strikethrough" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_18_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(10,event);" onfocus="return CKEDITOR.tools.callFunction(11,event);" onclick="CKEDITOR.tools.callFunction(12,this);return false;"><span class="cke_button_icon cke_button__strike_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -72px;background-size:auto;">&nbsp;</span><span id="cke_18_label" class="cke_button_label cke_button__strike_label" aria-hidden="false">Strikethrough</span></a><span class="cke_toolbar_separator" role="separator"></span><a id="cke_19" class="cke_button cke_button__removeformat cke_button_off" title="Remove Format" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_19_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(13,event);" onfocus="return CKEDITOR.tools.callFunction(14,event);" onclick="CKEDITOR.tools.callFunction(15,this);return false;"><span class="cke_button_icon cke_button__removeformat_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1680px;background-size:auto;">&nbsp;</span><span id="cke_19_label" class="cke_button_label cke_button__removeformat_label" aria-hidden="false">Remove Format</span></a></span><span class="cke_toolbar_end"></span></span><span id="cke_20" class="cke_toolbar" aria-labelledby="cke_20_label" role="toolbar"><span id="cke_20_label" class="cke_voice_label">Paragraph</span><span class="cke_toolbar_start"></span><span class="cke_toolgroup" role="presentation"><a id="cke_21" class="cke_button cke_button__numberedlist cke_button_off" title="Insert/Remove Numbered List" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_21_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(16,event);" onfocus="return CKEDITOR.tools.callFunction(17,event);" onclick="CKEDITOR.tools.callFunction(18,this);return false;"><span class="cke_button_icon cke_button__numberedlist_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1368px;background-size:auto;">&nbsp;</span><span id="cke_21_label" class="cke_button_label cke_button__numberedlist_label" aria-hidden="false">Insert/Remove Numbered List</span></a><a id="cke_22" class="cke_button cke_button__bulletedlist cke_button_off" title="Insert/Remove Bulleted List" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_22_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(19,event);" onfocus="return CKEDITOR.tools.callFunction(20,event);" onclick="CKEDITOR.tools.callFunction(21,this);return false;"><span class="cke_button_icon cke_button__bulletedlist_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1320px;background-size:auto;">&nbsp;</span><span id="cke_22_label" class="cke_button_label cke_button__bulletedlist_label" aria-hidden="false">Insert/Remove Bulleted List</span></a><span class="cke_toolbar_separator" role="separator"></span><a id="cke_23" class="cke_button cke_button__outdent cke_button_disabled " title="Decrease Indent" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_23_label" aria-haspopup="false" aria-disabled="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(22,event);" onfocus="return CKEDITOR.tools.callFunction(23,event);" onclick="CKEDITOR.tools.callFunction(24,this);return false;"><span class="cke_button_icon cke_button__outdent_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1032px;background-size:auto;">&nbsp;</span><span id="cke_23_label" class="cke_button_label cke_button__outdent_label" aria-hidden="false">Decrease Indent</span></a><a id="cke_24" class="cke_button cke_button__indent cke_button_off" title="Increase Indent" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_24_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(25,event);" onfocus="return CKEDITOR.tools.callFunction(26,event);" onclick="CKEDITOR.tools.callFunction(27,this);return false;"><span class="cke_button_icon cke_button__indent_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -984px;background-size:auto;">&nbsp;</span><span id="cke_24_label" class="cke_button_label cke_button__indent_label" aria-hidden="false">Increase Indent</span></a><span class="cke_toolbar_separator" role="separator"></span><a id="cke_25" class="cke_button cke_button__blockquote cke_button_off" title="Block Quote" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_25_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(28,event);" onfocus="return CKEDITOR.tools.callFunction(29,event);" onclick="CKEDITOR.tools.callFunction(30,this);return false;"><span class="cke_button_icon cke_button__blockquote_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -216px;background-size:auto;">&nbsp;</span><span id="cke_25_label" class="cke_button_label cke_button__blockquote_label" aria-hidden="false">Block Quote</span></a><span class="cke_toolbar_separator" role="separator"></span><a id="cke_26" class="cke_button cke_button__justifyleft cke_button_off" title="Align Left" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_26_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(31,event);" onfocus="return CKEDITOR.tools.callFunction(32,event);" onclick="CKEDITOR.tools.callFunction(33,this);return false;"><span class="cke_button_icon cke_button__justifyleft_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1128px;background-size:auto;">&nbsp;</span><span id="cke_26_label" class="cke_button_label cke_button__justifyleft_label" aria-hidden="false">Align Left</span></a><a id="cke_27" class="cke_button cke_button__justifycenter cke_button_off" title="Center" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_27_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(34,event);" onfocus="return CKEDITOR.tools.callFunction(35,event);" onclick="CKEDITOR.tools.callFunction(36,this);return false;"><span class="cke_button_icon cke_button__justifycenter_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1104px;background-size:auto;">&nbsp;</span><span id="cke_27_label" class="cke_button_label cke_button__justifycenter_label" aria-hidden="false">Center</span></a><a id="cke_28" class="cke_button cke_button__justifyright cke_button_off" title="Align Right" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_28_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(37,event);" onfocus="return CKEDITOR.tools.callFunction(38,event);" onclick="CKEDITOR.tools.callFunction(39,this);return false;"><span class="cke_button_icon cke_button__justifyright_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1152px;background-size:auto;">&nbsp;</span><span id="cke_28_label" class="cke_button_label cke_button__justifyright_label" aria-hidden="false">Align Right</span></a><a id="cke_29" class="cke_button cke_button__justifyblock cke_button_off" title="Justify" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_29_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(40,event);" onfocus="return CKEDITOR.tools.callFunction(41,event);" onclick="CKEDITOR.tools.callFunction(42,this);return false;"><span class="cke_button_icon cke_button__justifyblock_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1080px;background-size:auto;">&nbsp;</span><span id="cke_29_label" class="cke_button_label cke_button__justifyblock_label" aria-hidden="false">Justify</span></a></span><span class="cke_toolbar_end"></span></span><span id="cke_30" class="cke_toolbar" aria-labelledby="cke_30_label" role="toolbar"><span id="cke_30_label" class="cke_voice_label">Links</span><span class="cke_toolbar_start"></span><span class="cke_toolgroup" role="presentation"><a id="cke_31" class="cke_button cke_button__link cke_button_off" title="Link" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_31_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(43,event);" onfocus="return CKEDITOR.tools.callFunction(44,event);" onclick="CKEDITOR.tools.callFunction(45,this);return false;"><span class="cke_button_icon cke_button__link_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1248px;background-size:auto;">&nbsp;</span><span id="cke_31_label" class="cke_button_label cke_button__link_label" aria-hidden="false">Link</span></a><a id="cke_32" class="cke_button cke_button__unlink cke_button_disabled " title="Unlink" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_32_label" aria-haspopup="false" aria-disabled="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(46,event);" onfocus="return CKEDITOR.tools.callFunction(47,event);" onclick="CKEDITOR.tools.callFunction(48,this);return false;"><span class="cke_button_icon cke_button__unlink_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1272px;background-size:auto;">&nbsp;</span><span id="cke_32_label" class="cke_button_label cke_button__unlink_label" aria-hidden="false">Unlink</span></a></span><span class="cke_toolbar_end"></span></span><span id="cke_33" class="cke_toolbar" aria-labelledby="cke_33_label" role="toolbar"><span id="cke_33_label" class="cke_voice_label">Insert</span><span class="cke_toolbar_start"></span><span class="cke_toolgroup" role="presentation"><a id="cke_34" class="cke_button cke_button__horizontalrule cke_button_off" title="Insert Horizontal Line" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_34_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(49,event);" onfocus="return CKEDITOR.tools.callFunction(50,event);" onclick="CKEDITOR.tools.callFunction(51,this);return false;"><span class="cke_button_icon cke_button__horizontalrule_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -888px;background-size:auto;">&nbsp;</span><span id="cke_34_label" class="cke_button_label cke_button__horizontalrule_label" aria-hidden="false">Insert Horizontal Line</span></a><a id="cke_35" class="cke_button cke_button__smiley cke_button_off" title="Smiley" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_35_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(52,event);" onfocus="return CKEDITOR.tools.callFunction(53,event);" onclick="CKEDITOR.tools.callFunction(54,this);return false;"><span class="cke_button_icon cke_button__smiley_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1056px;background-size:auto;">&nbsp;</span><span id="cke_35_label" class="cke_button_label cke_button__smiley_label" aria-hidden="false">Smiley</span></a><a id="cke_36" class="cke_button cke_button__specialchar cke_button_off" title="Insert Special Character" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_36_label" aria-haspopup="false" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(55,event);" onfocus="return CKEDITOR.tools.callFunction(56,event);" onclick="CKEDITOR.tools.callFunction(57,this);return false;"><span class="cke_button_icon cke_button__specialchar_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -1848px;background-size:auto;">&nbsp;</span><span id="cke_36_label" class="cke_button_label cke_button__specialchar_label" aria-hidden="false">Insert Special Character</span></a></span><span class="cke_toolbar_end"></span></span><span class="cke_toolbar_break"></span><span id="cke_37" class="cke_toolbar" aria-labelledby="cke_37_label" role="toolbar"><span id="cke_37_label" class="cke_voice_label">Styles</span><span class="cke_toolbar_start"></span><span id="cke_10" class="cke_combo cke_combo__styles cke_combo_off" role="presentation"><span id="cke_10_label" class="cke_combo_label">Styles</span><a class="cke_combo_button" title="Formatting Styles" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_10_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(59,event,this);" onfocus="return CKEDITOR.tools.callFunction(60,event);" onclick="CKEDITOR.tools.callFunction(58,this);return false;"><span id="cke_10_text" class="cke_combo_text cke_combo_inlinelabel">Styles</span><span class="cke_combo_open"><span class="cke_combo_arrow"></span></span></a></span><span id="cke_11" class="cke_combo cke_combo__format cke_combo_off" role="presentation"><span id="cke_11_label" class="cke_combo_label">Format</span><a class="cke_combo_button" title="Paragraph Format" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_11_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(62,event,this);" onfocus="return CKEDITOR.tools.callFunction(63,event);" onclick="CKEDITOR.tools.callFunction(61,this);return false;"><span id="cke_11_text" class="cke_combo_text cke_combo_inlinelabel">Format</span><span class="cke_combo_open"><span class="cke_combo_arrow"></span></span></a></span><span id="cke_12" class="cke_combo cke_combo__font cke_combo_off" role="presentation"><span id="cke_12_label" class="cke_combo_label">Font</span><a class="cke_combo_button" title="Font Name" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_12_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(65,event,this);" onfocus="return CKEDITOR.tools.callFunction(66,event);" onclick="CKEDITOR.tools.callFunction(64,this);return false;"><span id="cke_12_text" class="cke_combo_text cke_combo_inlinelabel">Font</span><span class="cke_combo_open"><span class="cke_combo_arrow"></span></span></a></span><span id="cke_13" class="cke_combo cke_combo__fontsize cke_combo_off" role="presentation"><span id="cke_13_label" class="cke_combo_label">Size</span><a class="cke_combo_button" title="Font Size" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_13_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(68,event,this);" onfocus="return CKEDITOR.tools.callFunction(69,event);" onclick="CKEDITOR.tools.callFunction(67,this);return false;"><span id="cke_13_text" class="cke_combo_text cke_combo_inlinelabel">Size</span><span class="cke_combo_open"><span class="cke_combo_arrow"></span></span></a></span><span class="cke_toolbar_end"></span></span><span id="cke_38" class="cke_toolbar" aria-labelledby="cke_38_label" role="toolbar"><span id="cke_38_label" class="cke_voice_label">Colors</span><span class="cke_toolbar_start"></span><span class="cke_toolgroup" role="presentation"><a id="cke_39" class="cke_button cke_button__textcolor cke_button_off" title="Text Color" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_39_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(70,event);" onfocus="return CKEDITOR.tools.callFunction(71,event);" onclick="CKEDITOR.tools.callFunction(72,this);return false;"><span class="cke_button_icon cke_button__textcolor_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -408px;background-size:auto;">&nbsp;</span><span id="cke_39_label" class="cke_button_label cke_button__textcolor_label" aria-hidden="false">Text Color</span><span class="cke_button_arrow"></span></a><a id="cke_40" class="cke_button cke_button__bgcolor cke_button_off" title="Background Color" tabindex="-1" hidefocus="true" role="button" aria-labelledby="cke_40_label" aria-haspopup="true" onblur="this.style.cssText = this.style.cssText;" onkeydown="return CKEDITOR.tools.callFunction(73,event);" onfocus="return CKEDITOR.tools.callFunction(74,event);" onclick="CKEDITOR.tools.callFunction(75,this);return false;"><span class="cke_button_icon cke_button__bgcolor_icon" style="background-image:url('https://monarch.aop.com/js/ckeditor_4.5.7/plugins/icons.png?t=G14E');background-position:0 -384px;background-size:auto;">&nbsp;</span><span id="cke_40_label" class="cke_button_label cke_button__bgcolor_label" aria-hidden="false">Background Color</span><span class="cke_button_arrow"></span></a></span><span class="cke_toolbar_end"></span></span></span></span><div id="cke_1_contents" class="cke_contents cke_reset" role="presentation" style="height: 320px;"><span id="cke_45" class="cke_voice_label">Press ALT 0 for help</span><iframe src="" style="width: 100%; height: 100%;" class="cke_wysiwyg_frame cke_reset" title="Rich Text Editor, message_body" aria-describedby="cke_45" tabindex="0" allowtransparency="true" frameborder="0"></iframe></div></div></div>				
			</div>

			<div class="row">
				<div class="col-md-6">
					<button id="message_send" type="button" class="btn btn-default btn-lg">
						<span class="glyphicon glyphicon-envelope"></span> Send
					</button>
				</div>
			</div>



		</form>

	</div>
</div>

				<!--   <img src="/img/student-ui/examples/messages_compose.png" /> -->
			</div>
		</div>
		<div class="ms-view" data-state="messages_inbox" style="display: none;">
		
		<div class="container">
<div class="assignment-container">
	<div class="row">
		<div class="col-xs-12 col-sm-6 col-md-4">
			<div class="mon-message-list">
		
				<div id="messageinbox_wrapper" class="dataTables_wrapper form-inline" role="grid"><div class="row"><div class="col-sm-12"><div class="pull-right"><div class="dataTables_filter" id="messageinbox_filter"><label><input aria-controls="messageinbox" type="text"></label></div></div><div class="pull-left"><div id="messageinbox_length" class="dataTables_length"><label>Show <select size="1" name="messageinbox_length" aria-controls="messageinbox"><option value="10" selected="selected">10</option><option value="25">25</option><option value="50">50</option><option value="100">100</option></select></label></div></div><div class="clearfix"></div></div></div><table class="table table-striped table-bordered table-hover dataTable" id="messageinbox" aria-describedby="messageinbox_info" cellspacing="0" cellpadding="0" border="0">
						<thead style="display:none;">
						<tr role="row"><th class="sorting_disabled" role="columnheader" rowspan="1" colspan="1" style="width: 0px;">
							<!-- 
								<button type="button" class="btn btn-default btn-xs">Mark as Read</button>
								<button type="button" class="btn btn-default btn-xs">Mark as Unread</button>
								 -->
							</th></tr>
					</thead>
				
					
				<tbody role="alert" aria-live="polite" aria-relevant="all"><tr class="odd active"><td colspan="1" class="dataTables_empty" valign="top">You don't have any messages.</td></tr></tbody></table><div class="row"><div class="col-sm-12"><div class="pull-left"><div class="dataTables_info" id="messageinbox_info"></div></div><div class="pull-right"><div class="dataTables_paginate paging_bs_two_button" id="messageinbox_paginate"><ul class="pagination"><li class="prev disabled"><a href="javascript:void(0)" class="paginate_disabled_previous" tabindex="0" role="button" id="messageinbox_previous" aria-controls="messageinbox"><span class="glyphicon glyphicon-chevron-left"></span>&nbsp;Previous</a></li><li class="next disabled"><a href="javascript:void(0)" class="paginate_disabled_next" tabindex="0" role="button" id="messageinbox_next" aria-controls="messageinbox">Next&nbsp;<span class="glyphicon glyphicon-chevron-right"></span></a></li></ul></div></div><div class="clearfix"></div></div></div></div>
			</div>

		</div>
		<div class="col-xs-12 col-sm-6 col-md-8">
				<div id="messagepreview"><div class="mon-nomessage">You don't have any messages.</div>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         </div>
		</div>
	</div>
</div>
</div>

		
		<!--  
			<div class="ms-placeholder">
				<img src="/img/student-ui/examples/messages.png" />
			</div>

			-->


		</div>
		 <!-- <div class="ms-view" data-state="messages_archive">Archived</div>  -->
		<div class="ms-view" data-state="messages_sent" style="display: none;">
			<div class="container">
<div class="assignment-container">
	<div class="row">
		<div class="col-xs-12 col-sm-6 col-md-4">
			<div class="mon-message-list">
			<div id="messagesent_wrapper" class="dataTables_wrapper form-inline" role="grid"><div class="row"><div class="col-sm-12"><div class="pull-right"><div class="dataTables_filter" id="messagesent_filter"><label><input aria-controls="messagesent" type="text"></label></div></div><div class="pull-left"><div id="messagesent_length" class="dataTables_length"><label>Show <select size="1" name="messagesent_length" aria-controls="messagesent"><option value="10" selected="selected">10</option><option value="25">25</option><option value="50">50</option><option value="100">100</option></select></label></div></div><div class="clearfix"></div></div></div><table class="table table-striped table-bordered table-hover dataTable" id="messagesent" aria-describedby="messagesent_info" cellspacing="0" cellpadding="0" border="0">
				
			<thead style="display:none;">
					<tr role="row"><th class="sorting_disabled" role="columnheader" rowspan="1" colspan="1" style="width: 0px;">
						<!-- 
							<button type="button" class="btn btn-default btn-xs">Mark as Read</button>
							<button type="button" class="btn btn-default btn-xs">Mark as Unread</button>
							 -->
						</th></tr>
				</thead>
			
				
			<tbody role="alert" aria-live="polite" aria-relevant="all"><tr id="481542" class="gradeX odd active"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481542_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">I'm done...</div><div class="mm-body">I typed this with my eyes...</div></td></tr><tr id="481540" class="gradeX even"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481540_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">I think I'm gonna skip th...</div><div class="mm-body">Okay!...</div></td></tr><tr id="481538" class="odd gradeX"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481538_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">Why dont you read my mess...</div><div class="mm-body">Please?...</div></td></tr><tr id="481535" class="odd gradeX even"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481535_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">I don't like math very mu...</div><div class="mm-body">Dear Mother,I have reache...</div></td></tr><tr id="481526" class="odd gradeX"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481526_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">HI!...</div><div class="mm-body">What's Poppin'?&nbsp;...</div></td></tr><tr id="481524" class="odd gradeX even"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="481524_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/26/2017</div><div class="mm-title">Hello?...</div><div class="mm-body">Hello?HELLO?&nbsp;...</div></td></tr><tr id="455413" class="odd gradeX"><td class="messagecol2 "><div class="col-xs-12 col-md-8 nopadding"><div id="455413_read"> <i class="fa fa-envelope-o fa-2"></i> Daniel Ramjitsingh</div></div><div class="col-xs-6 col-md-4">09/07/2017</div><div class="mm-title">Daniel posted a new probl...</div><div class="mm-body">A new note was posted by ...</div></td></tr></tbody></table><div class="row"><div class="col-sm-12"><div class="pull-left"><div class="dataTables_info" id="messagesent_info">1 to 7 of 7</div></div><div class="pull-right"><div class="dataTables_paginate paging_bs_two_button" id="messagesent_paginate"><ul class="pagination"><li class="prev disabled"><a href="javascript:void(0)" class="paginate_disabled_previous" tabindex="0" role="button" id="messagesent_previous" aria-controls="messagesent"><span class="glyphicon glyphicon-chevron-left"></span>&nbsp;Previous</a></li><li class="next disabled"><a href="javascript:void(0)" class="paginate_disabled_next" tabindex="0" role="button" id="messagesent_next" aria-controls="messagesent">Next&nbsp;<span class="glyphicon glyphicon-chevron-right"></span></a></li></ul></div></div><div class="clearfix"></div></div></div></div>
			</div>
		</div>
		<div class="col-xs-12 col-sm-6 col-md-8">
				<div id="messagesentpreview"><div class="panel panel-default">
		<div class="panel-heading"><div class="row"><div class="col-xs-12 col-md-8"><h3>Daniel Ramjitsingh</h3></div><div class="col-xs-6 col-md-4" align="right"><h3>09/26/2017</h3></div></div><div class="row"><div class="col-xs-16 col-md-12 hyphenate"><h4>I'm done</h4></div></div></div><div class="panel-body"><div class="row"><div class="col-xs-16 col-md-12 hyphenate"><p class="text-justify" style="max-width:100%;">I typed this with my eyes closed:<br>I really like the book Charlie nad the choclatefactory alot;;/ Goodbye now</p></div></div></div><div class="panel-footer">
				<button id="sentboxreplymessage" type="button" class="btn btn-default btn-lg">
  <span class="glyphicon glyphicon-share-alt"></span> REPLY
</button>
				<button id="sentboxdeletemessage" type="button" class="btn btn-default btn-lg">
  <span class="glyphicon glyphicon-remove"></span> DELETE
</button>
				</div></div>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         </div>
		</div>
	</div>
</div>
</div>

		</div>
		<div class="ms-view" data-state="help" style="display: none;">
			<div class="ms-placeholder">			
			<style type="text/css">

	.monarch-guide-root {
	margin-bottom:10px;
	overflow:hidden;
	}
		.monarch-guide-cover {
		}
			.monarch-guide-cover img {
			border:0px;
			}
		.monarch-guide-link {
		padding-top:20px;
		}
			.monarch-guide-link a {
			font-size:1.2em;
			}
	.monarch-training-contact {
	padding:10px;
	overflow:hidden;
	margin-bottom:15px;
	}
		.link-shell {
		background:#fff;
		float:left;
		padding:5px;
		}
	p {
	margin:15px 0px;
	max-width:380px;
	}
	.monarch-footnote {
	font-size:.9em;
	}

</style>



<div class="container">
	<div class="assignment-container">

<div class="monarch-view-callout">

	<table><tbody><tr><td style="width:50%">

	
	<div class="monarch-guide-root">
		<div class="monarch-guide-cover">
			<a href="//d1vbs4wtgpocou.cloudfront.net/docs/monarch-help/6.0/mon_student_guide.pdf" target="_blank"><img src="//d1vbs4wtgpocou.cloudfront.net/img/mon_student_guide_2.png"></a>
		</div>
		<div class="monarch-guide-link">
			<a href="//d1vbs4wtgpocou.cloudfront.net/docs/monarch-help/6.0/mon_student_guide.pdf" target="_blank">Student Guide (pdf)</a>
			<p>An introduction to Monarch for Students.</p>
		</div>
	</div>
	<div class="monarch-footnote">To view a PDF file, you need a reader.<br>You can use <a href="http://get.adobe.com/reader/" target="_blank">this link</a> to install a PDF reader from Adobe.</div>

	</td>
	<td>
	<!--
	<div>
				<div>
		<p>Did you know that we offer free training seminars just for you?</p>
		</div>

		<div class="monarch-training-contact">
		<div class="link-shell">
		<a href="https://www.aop.com/customer/webinar/monarchwebinarfront" target="_blank">Sign Up for a <b>Monarch Training Webinar</b> Now</a>
		</div>
		</div>
				 <p>
		 	<b>Phone Numbers:</b><br/>
			Customer Service Inquiries: 1-800-622-3070<br/>
			Monarch Technical Support: 1-888-881-4958 <br/>
			Business hours are Monday through Friday from 7 a.m. to 5 p.m. (CT).<br/>
			<br/>
			<b>Technical Support E-Mail:</b>
						<a href="mailto:techsup@aop.com">techsup@aop.com</a>
			<br /><br />
		 	<b>Mailing Address:</b><br />
			Alpha Omega Publications<br/>
804 N. 2nd Avenue East<br/>
Rock Rapids, Iowa 51246<br/>
<br />
					</p>
	</div>
		-->
	</td></tr></tbody></table>

</div>

			</div>
</div>
			<!-- 
				<img src="/img/student-ui/examples/0.00_faq.png" />
				 -->
			</div>
		</div>
		<div class="ms-view" data-state="help_news" style="display: none;">
			<div class="ms-placeholder">
				<img src="/img/student-ui/examples/0.1_whats_new.png">
			</div>
		</div>
	</div>
	
	<div id="footer" style="display: block;">
	  <div class="container">
		<span class="text-muted">©2018 Glynlyon, Inc. All Rights Reserved.</span>
		<span class="text-muted" style="float:right"><a href="/authorize/eula/view" target="_blank">Terms of Use</a></span>
	  </div>
	</div>


	<div id="scoreframe" class="hidden">
		<div id="scorebox" class="">
			<div class="starbox">
				<div class="star star1"><i class="fa fa-star"></i></div>
				<div class="star star2"><i class="fa fa-star"></i></div>
				<div class="star star3"><i class="fa fa-star"></i></div>
				<div class="star star4"><i class="fa fa-star-o"></i></div>
				<div class="star star5"><i class="fa fa-star-o"></i></div>
			</div>
			<div class="gradetext">
				You've completed this assignment and your current grade is <span id="scoregrade"></span><span id="scorescore"></span>.  
			</div>
			<div class="notetext">
				Your final grade is calculated when your teacher completes problem grading.
			</div>
			<div class="scorebuttons">
				<!-- <button>Keep Going</button> There is no logic for this function yet... so I'm skipping it -->
				<button onclick="location.reload();">Return to Assignments</button>
			</div>
		</div>
	</div>
	<!-- Loading Student View Application -->
		<script src="/js/app/student.js?v=6.0.0"></script>



</body><span class="gr__tooltip"><span class="gr__tooltip-content"></span><i class="gr__tooltip-logo"></i><span class="gr__triangle"></span></span></html>
