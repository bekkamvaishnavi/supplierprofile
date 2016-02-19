# supplierprofile
supplierprofile
/*
-----------------------------------
YOUR STYLES GO HERE
-----------------------------------
*/
/* ********************************************* */
/* LAYOUT */
input.ng-invalid {
    border: 1px solid red;
}
/* GLOBAL */
.navbar-static-top {
    margin-bottom: 0;
}
img.tenantLogo {
    height: 75px;
    max-width: auto;
}
.user-name {
    margin-right: 40px;
    font-size: 12px;
}
.left10 {
    margin-left: 10px;
}
/* EDIT-IN-PLACE */
.editInPlace .value {
    padding: 3px 5px;
    color: #999c9f;
    border: 1px solid #bfc2c5;
}
.editInPlace .value.date {
    color: #13161a;
    border-width: 0;
}
.editInPlace .value:hover {
    cursor: pointer;
    background-color: yellow;
}
.editInPlace .units {
    font-size: 0.8em;
    margin-left: 5px;
}
.checkbox-label {
    color: #bfc2c5;
    /*margin-left: 5px;*/
}
/* DATEPICKER */
/* hide the buttons */
.ng-valid-date > li:nth-child(2),
.ng-valid-date > li:nth-child(3) {
    display: none;
}
/* DETAILS */
.detail h1,
.detail h2,
.detail h3,
.detail h4 {
    font-family: "ge-inspira", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.breadcrumbs {
    font-family: "ge-inspira", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 1.3em;
    padding: 10px;
}
.summary {
    padding: 0 10px;
}
.summary .thumb {
    padding: 0 20px;
}
.summary label {
    margin-bottom: 0px;
}
.newvalveoptions {
    margin-top: 10px;
}
.valveheader {
    float: left;
    margin-right: 150px;
}
.editBar {
    background-color: #3f4145;
    padding: 3px 0;
}
.editBar h3 {
    font-family: "ge-inspira", "Helvetica Neue", Helvetica, Arial, sans-serif;
    display: inline;
    color: #ffffff;
}
.editBar .actions {
    display: inline;
    margin-left: 20px;
}
.editBar.hasEdit {
    background-color: #e1e2e5;
}
.editBar.hasEdit h3 {
    color: #313337;
}
.subnav {
    padding: 10px;
}
.subnav .item {
    margin: 5px 0;
    cursor: pointer;
}
.subnav .item .status {
    padding: 3px;
    color: #ffffff;
    background-color: #bfc2c5;
}
.subnav .item .status.completed {
    background-color: green;
}
.detail {
    padding: 10px;
    border-left: 1px solid #bfc2c5;
}
.detail .control-label {
    color: #bfc2c5;
    text-align: left;
    padding-top: 0;
    width: 150px;
}
.detail .form-horizontal .controls {
    margin-left: 150px;
}
.detail h4 {
    margin: 10px 0;
}
.detailsBar {
    background-color: #3f4145;
    color: #e1e2e5;
    padding: 0 0 0 10px;
}
.detailsBar .btn {
    background-color: #3f4145;
    border-color: #3f4145;
    color: #e1e2e5;
}
.detailsBar div[class*="span"] {
    margin-bottom: 0;
    min-height: 25px;
}
.detailsBar .actions .btn.default {
    background-color: #f7f8fa;
    border-color: #e1e2e5;
    color: #313337;
}
.even {
    background-color: #edeeef;
}
/* GLOBAL NG GRID STYLES OVERWRITE */
.ngTopPanel {
    background-color: #999c9f;
}
.ngHeaderText {
    color: #ffffff;
}
.valverepairgrid {
    margin-right: -50px;
}
.ngHeaderContainer {
    font-weight: normal;
}
.ngAggregate {
    background-color: #e1e2e5;
    border-width: 3px 0 0 0;
    border-color: #ffffff;
    border-style: solid;
    border-bottom: 0 solid #ffffff;
}
.ngAggArrowExpanded {
    border-color: inherit;
    border-width: 0;
}
.ngAggregateText {
    font-weight: bold;
}
/* CUSTOMER/PLANTS */
.customerDetails.module.fullwidth {
    padding: 0 0 40px;
}
.customerDetails.module.fullwidth .plantBar {
    min-height: 25px;
}
.customerDetails.module.fullwidth .plant {
    margin: 20px 1px;
}
.customerDetails.module.fullwidth .plant .columnButton button {
    background-color: #999c9f;
    border-color: #999c9f;
}
.customerDetails.module.fullwidth .plant .gridHeaderText {
    padding-top: 1px;
}
.customerDetails.module.fullwidth .plant .plantDetails {
    padding-left: 10px;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable {
    width: 500px;
    margin: 20px;
    overflow: auto;
    height: 200px;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable tr {
    width: 100%;
    min-height: 200px;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable tr th {
    background-color: #e1e2e5;
    color: #313337;
    text-align: left;
    padding: 0 10px;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable tr th .btn {
    background-color: #e1e2e5;
    border-color: #e1e2e5;
    color: #313337;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable tr th.mainCol {
    width: 100%;
}
.customerDetails.module.fullwidth .plant table.plantDetailsTable tr td {
    padding: 0 10px;
}
.customerDetails.module.fullwidth .plant .detailsBar {
    background-color: #e1e2e5;
    color: #313337;
    padding: 0;
}
.customerDetails.module.fullwidth .plant .detailsBar .btn {
    background-color: #e1e2e5;
    border-color: #e1e2e5;
    color: #313337;
}
.customerDetails.module.fullwidth .plant .activeSelection {
    color: #3b73b9;
}
.customerDetails.module.fullwidth .plant .inActive {
    color: #313337;
}
.customerDetails.module.fullwidth .plant .plantText {
    color: #bfc2c5;
}
.customerDetails.module.fullwidth .plant .customerplantgrids {
    height: 175px;
    margin-left: 0px;
    background-color: #ffffff;
    width: 100%;
}
.row-fluid .span12.plantNotes,
.row-fluid div.span10.plantNotesBody {
    margin-left: 0;
}
.activemenuselection {
    padding: 3px;
    color: #ffffff;
    background-color: green;
}
/* GRIDS */
.grid .span12 {
    margin-bottom: 3px;
}
.gridStyle {
    height: 500px;
    margin-left: 0px;
    background-color: #ffffff;
    border-bottom: 5px solid #999c9f;
}
.customersGrid {
    height: 5000px;
    width: 100%;
    margin-left: 20px;
    background-color: #ffffff;
    padding: 20px 20px 20px 0;
}
.gridSearchBar {
    overflow: hidden;
    zoom: 1;
    padding: 5px 26px;
}
.gridSearchinput {
    background-color: #e1e2e5;
    border: 2px solid #e1e2e5;
    width: 290px;
}
.gridSearchinput .form-horizontal {
    margin-bottom: 0;
}
.gridSearchinput .form-horizontal .control-label {
    width: 50px;
    margin-bottom: 0;
    padding-top: 3px;
    text-align: left;
    padding-left: 10px;
}
.gridSearchinput .form-horizontal .controls {
    margin-left: 10px;
}
.gridSearchinput .form-horizontal .controls .btn-icon {
    background-color: #5c5f63;
}
.gridSearchinput .form-horizontal .controls .icon-search {
    color: #ffffff;
}
.form-horizontal .header-label {
    padding-top: 0px;
    margin-right: 10px;
    font-weight: bold;
}
.detail-grid label {
    margin-bottom: 0px;
}
.grid .gridStyle .ngTopPanel {
    background-color: #999c9f;
}
.grid .gridStyle .gridHeaderText {
    font-weight: normal;
    text-align: left;
    color: #ffffff;
    padding: 4px 0;
}
.grid .gridStyle .gridIcon {
    color: #5c5f63;
    padding-right: 15px;
    display: inline-block;
}
.userAdmin {
    font-weight: bold;
}
#userdetails {
    height: 35px;
    padding: 10px 40px;
    text-align: center;
}
#userdetails .alert {
    margin-bottom: 0;
}
.addnewusermodal {
    padding: 10px 20px;
    background-color: #e1e2e5;
    width: 580px;
    height: 600px;
    overflow: scroll;
    max-height: 800px;
    margin: 40px 0 0 30px;
}
.addnewusermodal .fields {
    background-color: #ffffff;
    overflow-y: auto;
    padding: 5px 10px;
    max-height: 500px;
}
.addnewusermodal button {
    float: right;
}
.module.fullwidth {
    padding: 0;
}
.pastdue i.icon-warning-sign {
    color: #ed8000;
}
.pastdue i.icon-ok-sign {
    color: #446b00;
}
i.icon-muted {
    color: #e1e2e5;
}
.errormsg {
    min-height: 50px;
    background-color: rgba(100, 100, 100, 0.26);
    padding: 10px 20px;
    width: auto;
    left: 45%;
    color: #ee3324;
}
.errormsg button {
    margin-top: 25px;
    float: right;
}
.createFilterModal {
    min-height: 275px;
    background-color: #e1e2e5;
    padding: 20px 20px 20px 30px;
    width: 720px;
    left: 45%;
}
.createFilterModal .filterProperties {
    min-height: 150px;
}
.createFilterModal .filterProperties .filterRow {
    margin: 20px 5px 20px 0;
}
.createFilterModal .nameSearch {
    overflow: hidden;
    zoom: 1;
}
.savedFilterTxt {
    margin-right: 6px;
}
.filterBar {
    background-color: #313337;
    padding: 5px 0 0 5px;
    overflow: hidden;
    zoom: 1;
}
.secondrow {
    background-color: #ffffff;
    height: 38px;
    padding: 9px 40px 0 40px;
}
.filterTxt {
    color: #ffffff;
}
/* GRID FOOTER */
.grid .gridfooter {
    background-color: #999c9f;
    height: 25px;
    padding: 0 10px;
    margin: 0 15px;
}
.grid .gridfooter .prntbtn,
.grid .gridfooter .exportbtn {
    color: #ffffff;
}
.grid .gridfooter .columnButton {
    zoom: 1;
    overflow: hidden;
    background-color: #999c9f;
}
.grid .gridfooter .columnButton button {
    background-color: #999c9f;
    border: none;
}
.exportbtn:before {
    content: "export";
}
.prntbtn:after {
    content: "print";
}
/* MODALS */
.addPlantTask,
.addPlantGeneric,
.contactmodal,
.importform,
.addPlantNote {
    background-color: #e1e2e5;
    width: 400px;
    min-height: 200px;
    padding: 20px;
}
.contactmodal {
    width: 460px;
}
.importform {
    width: 300px;
    min-height: 100px;
}
.addPlantGeneric .addAttachment {
    min-height: 100px;
    padding-top: 20px;
}
.selectFieldsModal {
    padding: 10px 20px;
    background-color: #e1e2e5;
    width: 280px;
    max-height: 600px;
    overflow: hidden;
    margin: 140px 0 0 230px;
}
.selectFieldsModal .fields {
    background-color: #ffffff;
    overflow-y: auto;
    padding: 5px 10px;
    max-height: 500px;
}
.exportsModal {
    width: 60px;
    margin: 0;
}
.selectFieldsModal .titlebar,
.modalTitleBar {
    zoom: 1;
    overflow: hidden;
}
.createFilterModal .deleteFilter .btn,
.createFilterModal .filterRow .btn {
    background-color: transparent;
    margin-bottom: 10px;
}
.createFilterModal .deleteFilter .btn i,
.createFilterModal .filterRow .btn i {
    font-size: 16px;
}
.partsbyRepairModal {
    margin-top: 150px;
    border: 1px solid #313337;
    width: 510px;
    height: 300px;
    overflow: auto;
    top: 40%;
    left: 80%;
    font-size: 11px;
}
.tasksbyRepairModal {
    margin-top: 150px;
    border: 1px solid #313337;
    width: 510px;
    height: 400px;
    overflow: auto;
    top: 40%;
    left: 80%;
    font-size: 11px;
}
.modalTitleBar {
    background-color: #e1e2e5;
}
.modalTitleBar .btn {
    background-color: #e1e2e5;
}
.modalTitleBar h4 {
    padding: 5px 0 0 10px;
}
.modal.fade {
    -webkit-transition: none;
    -moz-transition: none;
    -ms-transition: none;
    -o-transition: none;
    transition: none;
}
.lookupFieldsModal {
    max-height: 500px;
    overflow: hidden;
    width: 425px;
}
.lookupFieldsModal .fields {
    overflow: auto;
    max-height: 400px;
    width: 100%;
}
.lookupFieldsModal .fields .table .odd {
    background-color: #edeeef;
}
.lookupFieldsModal .fields .table .tableheader {
    background-color: #e1e2e5;
}
.lookupFieldsModal .fields .table .actionfield {
    width: 10px;
}
.lookupFieldsModal .fields .table .valuefield {
    width: 270px;
}
.lookupFieldsModal .fields .table .fieldactionicon {
    padding: 5px 0;
    width: 75px;
}
.lookupFieldsModal .fields .table .fieldactionicon .btn {
    background-color: transparent;
    border-width: 0;
    padding: 2px;
    color: #13161a;
}
.lookupFieldsModal .fields .table .fieldactionicon .btn i {
    font-size: 12px;
}
.moveFieldModal {
    width: 600px;
}
.moveFieldModal .modal-header {
    height: 10px;
}
.moveFieldModal .modal-header h3 {
    width: 500px;
}
/* MASTHEAD */
@media (min-width: 1200px) {
    .navbar-static-top .container {
        width: 100%;
    }
    .navbar-inner {
        padding: 0 40px;
    }
    .navbar .nav {
        padding: 0 40px;
    }
    .primary-navbar .btn-group {
        padding: 0 40px;
    }
}
@media (min-width: 980px) and (max-width: 1199px) {
    .navbar-static-top .container {
        width: 100%;
    }
    .navbar-inner {
        padding: 0 40px;
    }
    .navbar .nav {
        padding: 0 40px;
    }
    .primary-navbar .btn-group {
        padding: 0 40px;
    }
}
@media (min-width: 768px) and (max-width: 979px) {
    .navbar-static-top .container {
        width: 100%;
        padding: 0px;
    }
    .navbar-inner {
        padding: 0 40px;
    }
    .navbar .nav {
        padding: 0 40px;
    }
    .primary-navbar .btn-group {
        padding: 0 40px;
    }
}
@media (max-width: 767px) {
    .navbar-static-top .container {
        width: 100%;
    }
    .navbar-inner {
        padding: 0 40px;
    }
    .navbar .nav {
        padding: 0 40px;
    }
    .primary-navbar .btn-group {
        padding: 0 40px;
    }
}
.green {
    color: #76B900;
}
/* PADDING */
.mleft10 {
    margin-left: 10px;
}
.popupCell {
    border: 0px;
}
/* MARGINS */
.mtop20 {
    margin-top: 20px;
}
.popupAdd {
    padding: 5px;
    font-size: 12px;
}
.popupAdd label {
    font-size: 10px;
}
.adduser {
    float: right;
    padding-top: 10px;
    border: 1px solid;
}
/* For image slider */
.slider {
    width: 500px;
    height: 300px;
    overflow: hidden;
    position: relative;
    background: #fff;
    border: 20px solid #FFF;
    margin-top: 20px;
}
.slide {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
}
.arrow {
    position: absolute;
    z-index: 1002;
    display: block;
    top: 50%;
    margin-top: -35px;
    width: 36px;
    height: 71px;
    outline: none;
    cursor: pointer;
    background: url(../img/blank.gif) no-repeat;
}
.arrow.prev {
    opacity: 0.2;
    left: 20px;
    background-image: url(../img/arrow_prev.png);
    transition: 0.2s linear all;
}
.arrow.next {
    opacity: 0.2;
    right: 20px;
    background-image: url(../img/arrow_next.png);
    transition: 0.2s linear all;
}
.arrow.prev:hover {
    opacity: 1;
    background-image: url(../img/arrow_prev.png);
}
.arrow.next:hover {
    opacity: 1;
    background-image: url(../img/arrow_next.png);
}
/*---------------------------------------------------------
NAV
---------------------------------------------------------*/
.imgNav {
    text-align: center;
    display: block;
    position: absolute;
    z-index: 1002;
    left: 0;
    bottom: -4px;
    right: 0;
    height: 48px;
}
.nonDraggableImage {
    -webkit-user-drag: none;
}
.imgNav .wrapper {
    margin: 0 auto;
    width: 100%;
    padding: 1em 0 .8em;
}
.imgNav ul {
    margin: 0;
    width: 100%;
}
.imgNav .dot,
.imgNav .dot a {
    display: inline-block;
    zoom: 1;
}
.dots .dot {
    position: relative;
    margin: 0 8px;
    width: 12px;
    height: 12px;
}
.dots .dot a {
    position: absolute;
    top: 2px;
    left: 2px;
    width: 6px;
    height: 6px;
    text-indent: 100%;
    white-space: nowrap;
    overflow: hidden;
    background: #DDD;
    border: 1px solid transparent;
    outline: none;
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%;
    -webkit-transition: background-color 0.25s, border-color 0.25s;
    -moz-transition: background-color 0.25s, border-color 0.25s;
    transition: background-color 0.25s, border-color 0.25s;
}
.dots .dot a.active {
    border-color: #000;
    background-color: transparent;
}
.imageSize {
    height: auto;
    width: auto;
    max-width: 300px;
    max-height: 300px;
}
.iconRight {
    float: right;
    padding-right: 20px;
}
/*---------------------------------------------------------

ANALYTICS - GRAPHS
---------------------------------------------------------*/
.analytics table {
    margin-top: 10px;
}
.analytics td {
    padding: 2px;
    text-align: center;
}
.analytics td .tooltip-inner {
    text-align: left;
}
.analytics .outlook tr,
.analytics .outlook td {
    border: 2px solid #ffffff;
}
.analytics .outlook td {
    background-color: #ed8000;
}
.analytics .outlook td + td {
    background-color: #ff9921;
}
.analytics .outlook td + td + td {
    background-color: #ffb054;
}
.analytics .outlook td + td + td + td {
    background-color: #ffc887;
}
.analytics .orangeSingleBar tr,
.analytics .orangeSingleBar td {
    border: 2px solid #ffffff;
}
.analytics .orangeSingleBar td {
    background-color: #ed8000;
}
.analytics .orangeSingleBar td + td {
    background-color: #ff9921;
}
.analytics .orangeSingleBar td + td + td {
    background-color: #ffa53b;
}
.analytics .orangeSingleBar td + td + td + td {
    background-color: #ffb054;
}
.analytics .orangeSingleBar td + td + td + td + td {
    background-color: #ffbc6e;
}
.analytics .orangeSingleBar td + td + td + td + td + td {
    background-color: #ffc887;
}
.analytics .orangeSingleBar td + td + td + td + td + td + td {
    background-color: #ffd4a1;
}
.analytics .orangeSingleBar td + td + td + td + td + td + td + td {
    background-color: #ffdfba;
}
.analytics .orangeSingleBar td + td + td + td + td + td + td + td + td {
    background-color: #ffebd4;
}
.analytics .orangeSingleBar td + td + td + td + td + td + td + td {
    background-color: #fff7ed;
}
.analytics .twoValuesBar tr,
.analytics .twoValuesBar td {
    border: 2px solid #ffffff;
}
.analytics .twoValuesBar td {
    background-color: #3b73b9;
}
.analytics .twoValuesBar td + td {
    background-color: #999c9f;
}
.analytics .blueSingleBar tr,
.analytics .blueSingleBar td {
    border: 2px solid #ffffff;
}
.analytics .blueSingleBar td {
    background-color: #3b73b9;
}
.analytics .blueSingleBar td + td {
    background-color: #5c8dcb;
}
.analytics .blueSingleBar td + td + td {
    background-color: #6f9bd1;
}
.analytics .blueSingleBar td + td + td + td {
    background-color: #83a8d7;
}
.analytics .blueSingleBar td + td + td + td + td {
    background-color: #96b6de;
}
.analytics .blueSingleBar td + td + td + td + td + td {
    background-color: #a9c3e4;
}
.analytics .blueSingleBar td + td + td + td + td + td + td {
    background-color: #bdd1ea;
}
.analytics .blueSingleBar td + td + td + td + td + td + td + td {
    background-color: #d0def0;
}
.analytics .blueSingleBar td + td + td + td + td + td + td + td + td {
    background-color: #e3ecf6;
}
.analytics .blueSingleBar td + td + td + td + td + td + td + td {
    background-color: #f7f9fc;
}
.analytics .status td {
    width: 16%;
}
.analytics .status tr.totals,
.analytics .status .totals td {
    border: 2px solid #3b73b9;
}
.analytics .status tr.totals td {
    background-color: #d0def0;
}
.analytics .status tr.totals td + td {
    background-color: #a9c3e4;
}
.analytics .status tr.totals td + td + td {
    background-color: #83a8d7;
}
.analytics .status tr.totals td + td + td + td {
    background-color: #5c8dcb;
}
.analytics .status tr.totals td + td + td + td + td {
    background-color: #3b73b9;
}
.analytics .status tr.totals td + td + td + td + td + td {
    background-color: #bdd1ea;
}
.analytics.tabularData table {
    width: 100px;
}
/*---------------------------------------------------------
SETTINGS
---------------------------------------------------------*/
div.settings .settings-title {
    color: #3b73b9;
    font-size: 16.8px;
}
div.settings .settings-chevron {
    font-size: 10.5px;
}
div.settings .settings-groups {
    padding: 10px;
}
div.settings .nav-pills a {
    background-color: #edeeef;
}
div.settings .nav-pills .active a {
    background-color: #3b73b9;
}
div.settings .form-settings .btn {
    border-width: 0;
    padding: 2px;
    color: #13161a;
}
div.settings .form-settings .btn i {
    font-size: 12px;
}
div.settings .form-settings .btn.addfield {
    border-width: 1px;
    padding: 2px 10px;
    color: #5c5f63;
}
div.settings .form-settings table.table tbody + tbody {
    border-color: #ffffff;
}
div.settings .form-settings table.table td {
    border-color: #ffffff;
}
div.settings .form-settings table.table td.labels {
    width: 40%;
}
div.settings .form-settings table.table .reorderfield {
    width: 15px;
}
div.settings .form-settings table.table .settings-section {
    background-color: #e1e2e5;
    border-color: #ffffff;
}
div.settings .form-settings .settingsTab {
    font-size: 16px;
}
.configuration-settings {
    margin-top: 20px;
}
.configuration-settings .odd {
    background-color: #edeeef;
}
.configuration-settings .buttonaction {
    width: 100px;
}
.configuration-settings .fieldactionicon {
    padding: 5px 0;
    width: 75px;
    text-align: center;
}
.configuration-settings .fieldactionicon .btn {
    background-color: transparent;
    border-width: 0;
    padding: 2px;
    color: #13161a;
}
.configuration-settings .fieldactionicon .btn i {
    font-size: 12px;
}
.configuration-settings .qccheck .hasEdit th {
    background-color: #bfc2c5;
    color: #13161a;
}
#partForm .input-small,
#weldsForm .input-small {
    width: 95px;
}
.iconsmargin a {
    margin: 3px;
}
.importExternalAppDataPopup {
    width: 900px;
    left: 40%;
}
.importExternalAppDataGridStyle {
    height: 200px;
    margin-left: 3px;
}
.packagesGrid {
    height: 650px;
    width: 98%;
    margin: 40px 0 0 30px;
    border: 1px lightGray solid;
}
.managePackageModal {
    width: 1025px;
    height: 610px;
    overflow: auto;
}
.managePackageModal button {
    float: right;
}
.packageItemsGrid {
    height: 100px;
    width: 465px;
    border: 1px lightGray solid;
}
/* LAYOUT */
.footer {
    text-align: center;
    margin: 0;
    height: 20px;
    color: #5c5f63;
    font-size: 0.7em;
    background-color: #bfc2c5;
}
.footer .copyright {
    text-align: center;
}
.footer .licensed {
    text-align: right;
}
.btn-info {
    color: #ffffff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
    background-color: #49afcd;
    background-image: -moz-linear-gradient(top, #5bc0de, #2f96b4);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#5bc0de), to(#2f96b4));
    background-image: -webkit-linear-gradient(top, #5bc0de, #2f96b4);
    background-image: -o-linear-gradient(top, #5bc0de, #2f96b4);
    background-image: linear-gradient(to bottom, #5bc0de, #2f96b4);
    background-repeat: repeat-x;
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de', endColorstr='#ff2f96b4', GradientType=0);
    border-color: #2f96b4 #2f96b4 #1f6377;
    border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
    *background-color: #2f96b4;
    filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}
.btn-info:hover,
.btn-info:focus,
.btn-info:active,
.btn-info.active,
.btn-info.disabled,
.btn-info[disabled] {
    color: #ffffff;
    background-color: #2f96b4;
    *background-color: #2a85a0;
}
.btn-info:active,
.btn-info.active {
    background-color: #24748c \9;
}
.field-settings .scrolling .bodyScroll {
    height: 400px;
    overflow-x: hidden;
    overflow-y: auto;
    display: block;
}
.field-settings .scrolling .headScroll {
    position: relative;
    display: block;
}
.field-settings .scrolling .headScroll .fieldname.string {
    width: 160px;
}
.field-settings .scrolling .check {
    width: 75px;
}
.field-settings .scrolling .string {
    width: 100px;
}
/*
.gridfooter .prntbtn,
.gridfooter .exportbtn {
  color: #ffffff;
}
.gridfooter .columnButton {
  zoom: 1;
  overflow: hidden;
  background-color: #999c9f;
}
.gridfooter .columnButton button {
  background-color: #999c9f;
  border: none;
}
*/
