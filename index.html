<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>jQuery UI Sortable - Portlets</title>
		<link rel="stylesheet" href="css/themes/base/jquery.ui.all.css">
		<link rel="stylesheet" href="css/themes/base/demos.css">
		<script src="js/jquery-1.9.1.js"></script>
		<script src="js/ui/jquery.ui.core.js"></script>
		<script src="js/ui/jquery.ui.widget.js"></script>
		<script src="js/ui/jquery.ui.mouse.js"></script>
		<script src="js/ui/jquery.ui.sortable.js"></script>
		<style>
			body {
				min-width: 520px;
			}
			.column {
				width: 170px;
				float: left;
				padding-bottom: 100px;
			}
			.portlet {
				margin: 0 1em 1em 0;
			}
			.portlet-header {
				margin: 0.3em;
				padding-bottom: 4px;
				padding-left: 0.2em;
			}
			.portlet-header .ui-icon {
				float: right;
			}
			.portlet-content {
				padding: 0.4em;
			}
			.ui-sortable-placeholder {
				border: 1px dotted black;
				visibility: visible !important;
				height: 50px !important;
			}
			.ui-sortable-placeholder * {
				visibility: hidden;
			}
		</style>
		<script>
			var byColumns = "";
			$(function() {
				/////////////////////////////////////////////////////////////////////////////////////////////////
				$(".column").sortable({
					connectWith : ".column"
				});

				$(".portlet-header .ui-icon").click(function() {
					$(this).toggleClass("ui-icon-minusthick").toggleClass("ui-icon-plusthick");
					$(this).parents(".portlet:first").find(".portlet-content").toggle();
					var sign = $(this).hasClass("ui-icon-plusthick")?"plus":"minus";						
					var portlet_id = $(this).parent().parent().attr('id');
					$('#info_cols').html('?sendSigns=yes&portlet_id='+portlet_id+'&sign='+sign);
					
 					$.get("ajax.php"+'?sendSigns=yes&portlet_id='+portlet_id+'&sign='+sign, function(data){ $('#so').text(data);} );					
				});

				$(".column").disableSelection();

				$(".column").on("sortstop", function(event, ui) {

					var i = 0;
					$("#left > div").each(function() {
						byColumns += '&left[' + i + ']=' + $(this).attr('id');
						i++;
					});

					var i = 0;
					$("#middle > div").each(function() {
						byColumns += '&middle[' + i + ']=' + $(this).attr('id');
						i++;
					});

					var i = 0;
					$("#right > div").each(function() {
						byColumns += '&right[' + i + ']=' + $(this).attr('id');
						i++;
					});

					byColumns = '?sendColumns=yes' + byColumns;

 					$.get("ajax.php"+byColumns, function(data){ $('#so').text(data);} );

					$('#info_cols').html(byColumns);

					byColumns = "";
				});

				//////////////////////////////////////////////////////////////////////////////////
			});
		</script>
	</head>
	<body>
		
		
<div style="position:absolute;left:575px;border:double;">
		<div id="info_cols" style="padding:5px;font-size:small;">
			&nbsp;
		</div>	
		<pre id='so' style="padding:5px;font-size:medium;">&nbsp;</pre>	
		
</div>				
		
		
			
		<div class="column" id="left">
			<div class="portlet ui-widget ui-widget-content ui-helper-clearfix ui-corner-all" id="item_1">
				<div class="portlet-header ui-widget-header ui-corner-all">
					Feeds 1<span class="ui-icon ui-icon-minusthick"></span>
				</div>

				<div class="portlet-content">
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit
				</div>
			</div>
			<div class="portlet ui-widget ui-widget-content ui-helper-clearfix ui-corner-all" id="item_2">
				<div class="portlet-header ui-widget-header ui-corner-all">
					News 2<span class="ui-icon ui-icon-minusthick"></span>
				</div>

				<div class="portlet-content">
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit
				</div>
			</div>
		</div>

		<div class="column" id="middle">
			<div class="portlet ui-widget ui-widget-content ui-helper-clearfix ui-corner-all" id="item_3">
				<div class="portlet-header ui-widget-header ui-corner-all">
					Shopping 3<span class="ui-icon ui-icon-minusthick"></span>
				</div>

				<div class="portlet-content">
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit
				</div>
			</div>
		</div>

		<div class="column" id="right">
			<div class="portlet ui-widget ui-widget-content ui-helper-clearfix ui-corner-all" id="item_4">
				<div class="portlet-header ui-widget-header ui-corner-all">
					Links 4<span class="ui-icon ui-icon-minusthick"></span>
				</div>

				<div class="portlet-content">
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit
				</div>
			</div>
			<div class="portlet ui-widget ui-widget-content ui-helper-clearfix ui-corner-all" id="item_5">
				<div class="portlet-header ui-widget-header ui-corner-all">
					Images 5<span class="ui-icon ui-icon-minusthick"></span>
				</div>

				<div class="portlet-content">
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit
				</div>
			</div>
		</div>

	</body>
</html>