<?xml version="1.0" encoding="ISO-8859-1" ?>
<!DOCTYPE tiles-definitions PUBLIC
"-//Apache Software Foundation//DTD Tiles Configuration 3.0//EN"
"http://tiles.apache.org/dtds/tiles-config_3_0.dtd">
<tiles-definitions>
	<definition name="base"
		template="/WEB-INF/views/layout/layout.jsp">
		<put-attribute name="header"
			value="/WEB-INF/views/layout/header.jsp" />
		<put-attribute name="footer"
			value="/WEB-INF/views/layout/footer.jsp" />
	</definition>

	<definition name="base2"
		template="/WEB-INF/views/layout/layout2.jsp">

		<put-attribute name="footer"
			value="/WEB-INF/views/layout/footer.jsp" />
	</definition>
	
	<definition name="base3"
		template="/WEB-INF/views/layout/layout3.jsp">

		<put-attribute name="footer"
			value="/WEB-INF/views/layout/footer.jsp" />
	</definition>
    
    <definition name="base4"
    	template="/WEB-INF/views/layout/layout4.jsp">
    	<put-attribute name="header"
			value="/WEB-INF/views/layout/header.jsp" />
    	<put-attribute name="footer"
    		value="/WEB-INF/views/layout/footer.jsp">
    	</put-attribute>
   </definition>
    

	<definition name="profile" extends="base">

		<put-attribute name="body"
			value="/WEB-INF/views/profile.jsp" />
	</definition>

	<definition name="listForReview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ListForReview.jsp" />
	</definition>


	<definition name="unitofmeasure" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/UnitOfMeasure.jsp" />
	</definition>

	<definition name="PMScheduleView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleSearch.jsp" />
	</definition>

	<definition name="masterSchedule" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/masterSchedule.jsp" />
	</definition>


	<definition name="listForAdmin" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ListForAdmin.jsp" />
	</definition>

	<definition name="scheduleEditForReview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleEditForReviewer.jsp" />
	</definition>

	<definition name="scheduleEditForAdmin" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleEditForAdmin.jsp" />
	</definition>

	<definition name="getPMSelectedEquipments" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PMScheduleSearchEquipment.jsp" />
	</definition>



	<definition name="scheduleCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleCreate.jsp" />
	</definition>

	<definition name="StandardReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/StandardReport.jsp" />
	</definition>
	
				
						
						<definition name="addReportData" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AddReportData.jsp" />
	</definition>
	<definition name="viewReportData" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ViewReportData.jsp" />
	</definition>
	<definition name="updateReportData" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/UpdateReportData.jsp" />
	</definition>

	<definition name="assetReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/StandardAssetReport.jsp" />
	</definition>

	<definition name="assetReportGeneral" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AssetReportGeneral.jsp" />
	</definition>


	<definition name="assetReportbyAge" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AssetReportByAge.jsp" />
	</definition>


	<definition name="assetReportByLifeSpan" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AssetReportByLifeSpan.jsp" />
	</definition>




	<definition name="acmvEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/acmvEdit.jsp" />
	</definition>



	<definition name="acmvSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/acmvSearch.jsp" />
	</definition>



	<definition name="acmvcreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/acmvcreate.jsp" />
	</definition>

	<definition name="electricalcreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/electricalcreate.jsp" />
	</definition>

	<definition name="CivilLevel3" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CivilLevel3.jsp" />
	</definition>


	<definition name="CivilLevel4" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CivilLevel4.jsp" />
	</definition>



	<definition name="adminDashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/Admindashboard.jsp" />
	</definition>

	<definition name="accessDashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/accessdashboard.jsp" />
	</definition>

	<definition name="editCivil" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CivilEdit.jsp" />
	</definition>


	<definition name="building" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Building.jsp" />
	</definition>


	<definition name="location" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Location.jsp" />
	</definition>

	<definition name="assettype" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AssetType.jsp" />
	</definition>


	<definition name="addUser" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-create-user.jsp" />
	</definition>

	<definition name="addGroup" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-create-group.jsp" />
	</definition>

	<definition name="viewGroup" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/editgroup.jsp" />
	</definition>

	<definition name="viewUsers" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/edituser.jsp" />
	</definition>


	<definition name="userPriviledges" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-priviledges.jsp" />
	</definition>

	<definition name="changepassword" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-change-password.jsp" />
	</definition>

	<!-- <definition name="reset" extends="base"> <put-attribute name="body" 
		value="/WEB-INF/views/ResetPassword.jsp" /> </definition> -->
	<definition name="sitePriviledges" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-site-access.jsp" />
	</definition>

	<definition name="dashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboard.jsp" />
	</definition>
	<definition name="verifyotp" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/VerifyOtp.jsp" />
	</definition>
	<definition name="dashboardlevel1" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardlevel1.jsp" />
	</definition>

	<definition name="dashboardlevelT" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardlevelT.jsp" />
	</definition>


	<definition name="overview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/overview.jsp" />
	</definition>


	<definition name="accessdashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/accessdashboard.jsp" />
	</definition>


	<definition name="useraccessdashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-control-user-management.jsp" />
	</definition>

	<definition name="groupaccessdashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-control-group-management.jsp" />
	</definition>

	<definition name="priviledgeaccessdashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/admin/access-control-access-control.jsp" />
	</definition>

	<definition name="quotation" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/QuotationCreate.jsp" />
	</definition>

	<definition name="assetSubtype" extends="base">
		<put-attribute name="body"

			value="/WEB-INF/views/AssetSubType.jsp" />
	</definition>

	<definition name="department" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Department.jsp" />
	</definition>

	<definition name="civilCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CivilCreate.jsp" />
	</definition>


	<definition name="civilSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CivilSearch.jsp" />
	</definition>
	<definition name="thrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/thrushhold_value.jsp" />
	</definition>


	<definition name="division" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Division.jsp" />
	</definition>

	<definition name="cluster" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Cluster.jsp" />
	</definition>

	<definition name="technician" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Technician.jsp" />
	</definition>
	<definition name="costCenter" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CostCenter.jsp" />
	</definition>



	<definition name="maintainancegroup" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MaintainenceGroup.jsp" />

	</definition>

	<definition name="faultCategory" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultCategory.jsp"></put-attribute>
	</definition>

	<definition name="contract" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Contract.jsp"></put-attribute>
	</definition>

	<definition name="electrical" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/electricalCreate.jsp" />
	</definition>


	<definition name="electricalSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/electricalSearch.jsp" />
	</definition>


	<definition name="electricalEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/electricalEdit.jsp" />
	</definition>



	<definition name="mechanicalCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MechanicalCreate.jsp" />
	</definition>

	<definition name="priorty" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Priorty.jsp" />
	</definition>



	<definition name="mechanicalView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MechanicalView.jsp" />
	</definition>


	<definition name="mechanicalEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MechanicalEdit.jsp" />
	</definition>


	<definition name="fireedit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/fireedit.jsp" />
	</definition>

	<definition name="fireview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/fireview.jsp" />
	</definition>

	<definition name="firecreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FireCreate.jsp" />

	</definition>

	<definition name="requestforapproval" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/requestForApprovalCreate.jsp" />
	</definition>

	<definition name="viewallrequests" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/requestForApprovalView.jsp" />
	</definition>
	<definition name="viewrfa" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/viewRfa.jsp" />
	</definition>

	<definition name="rfaApprover" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/rfaApprover.jsp" />
	</definition>
	<definition name="rfaCostCenter" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/rfaCostCenter.jsp" />
	</definition>
	<definition name="rfaPO" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/rfaPO.jsp" />
	</definition>
	<definition name="faultreportcreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportCreate.jsp" />
	</definition>
	<definition name="faultreportsearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportSearch.jsp" />
	</definition>
	<definition name="faultreportsearchsla" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportSearchSla.jsp" />
	</definition>
	<definition name="tfaultreportsearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/TFaultReportSearch.jsp" />
	</definition>
	<definition name="faultreportupdate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportUpdate.jsp" />
	</definition>
	<definition name="faultreportupdateForFmm" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportUpdateForFmm.jsp" />
	</definition>
		<definition name="faultreportupdatejfp" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportUpdateForJfp.jsp" />
	</definition>
	<definition name="faultimageupload" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/image-upload.jsp" />
	</definition>
	<definition name="faultreportequipment" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportEquipment.jsp" />
	</definition>
	<definition name="faultreportequipmentsearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportEquipmentSearch.jsp" />
	</definition>

	<definition name="frreport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportXlsDashboard.jsp" />
	</definition>
	<definition name="frexcelsearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/FaultReportExcelSearch.jsp" />
	</definition>
	<definition name="rfaAdmin" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/rfaAdmin.jsp" />
	</definition>

	<definition name="viewrfaAdmin" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/viewRfaForAdmin.jsp" />

	</definition>
	<definition name="SORCreate" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/SORCreate.jsp" />
	</definition>


	<definition name="SORSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SORSearch.jsp" />
	</definition>


	<definition name="SOREdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SOREdit.jsp" />
	</definition>

	<definition name="labourrate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateCreate.jsp" />
	</definition>

	<definition name="labourrateupdate" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateUpdate.jsp" />
	</definition>

	<definition name="labourratesearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateSearch.jsp" />
	</definition>


	<definition name="quotationlist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/listQuot.jsp" />
	</definition>

	<definition name="searchquotationrfa" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/QuotationSearch.jsp" />
	</definition>


	<!-- <definition name="addchecklist" extends="base"> <put-attribute name="body" 
		value="/WEB-INF/views/checklistcreate.jsp" /> </definition> -->
	<definition name="checklistcreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistcreate.jsp" />
	</definition>



	<definition name="Team" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Team.jsp" />
	</definition>

	<definition name="PMTaskView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/taskSearch.jsp" />
	</definition>

	<definition name="MonthlyTasks" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/monthlytasks.jsp" />
	</definition>

	<definition name="printtaskchecklist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/printTaskChecklist.jsp" />
	</definition>

	<definition name="home" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/index.jsp" />
	</definition>
	<definition name="chartdatalist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardCharData.jsp" />
	</definition>

	<definition name="starratequotation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/StarRateQuotationCreate.jsp" />
	</definition>



	<definition name="PMGetEquipment" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PredictiveEquipSearch.jsp" />
	</definition>

	<definition name="PMAddNewClass" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MonitorClass.jsp" />
	</definition>


	<definition name="starratequotationview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/starratequotationView.jsp" />
	</definition>
	<definition name="quotationview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/quotationView.jsp" />
	</definition>

	<definition name="checklistTaskUpdate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistTaskUpdate.jsp" />
	</definition>


	<definition name="SearchThrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PredictiveMainSearch.jsp" />
	</definition>

	<definition name="updateThrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ThrushHoldEdit.jsp" />
	</definition>

	<definition name="PMtaskModify" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/taskModify.jsp" />
	</definition>

	<definition name="scheduleEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleEdit.jsp" />
	</definition>


	<definition name="SOREdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SOREdit.jsp" />
	</definition>

	<definition name="labourrate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateCreate.jsp" />
	</definition>

	<definition name="labourrateupdate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateUpdate.jsp" />
	</definition>

	<definition name="labourratesearch" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/LabourRateSearch.jsp" />
	</definition>


	<definition name="quotationlist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/listQuot.jsp" />
	</definition>

	<definition name="searchquotation" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/QuotationSearch.jsp" />
	</definition>

	<definition name="addchecklist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistcreate.jsp" />
	</definition>

	<definition name="checklistequipment" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistequipment.jsp" />
	</definition>
	<definition name="checklistsearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistSearch.jsp" />
	</definition>
	<definition name="editchecklist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editchecklist.jsp" />
	</definition>
	<definition name="viewchecklist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/viewChecklist.jsp" />
	</definition>
	<definition name="adddraft" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/draftcreate.jsp" />
	</definition>
	<definition name="searchdraft" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/searchDraft.jsp" />
	</definition>
	<definition name="editdraft" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editdraft.jsp" />
	</definition>

	<definition name="Team" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Team.jsp" />
	</definition>

	<definition name="starratequotation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/StarRateQuotationCreate.jsp" />
	</definition>








	<definition name="starratequotationview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/starratequotationView.jsp" />
	</definition>
	<definition name="quotationview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/quotationView.jsp" />
	</definition>

	<definition name="assetTemplate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/assetTemplate.jsp" />
	</definition>
	<definition name="equipmentCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/EquipmentCreate.jsp" />
	</definition>

	<definition name="equipmentedit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/EquipmentEdit.jsp" />
	</definition>
	
	<definition name="equipmentAuditCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/EquipmentAuditCreate.jsp" />
	</definition>

	<definition name="equipmentAuditEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/EquipmentAuditEdit.jsp" />
	</definition>
	
	
	<definition name="equipmentSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/EquipmentSearch.jsp" />
	</definition>

	<definition name="rfaSiteApprover" extends="base4">
		<put-attribute name="body"
			value="/WEB-INF/views/rfaSiteApprover.jsp" />
	</definition>


	<definition name="PMAddNewClass" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MonitorClass.jsp" />
	</definition>

	<definition name="thrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ThrushHoldCreate.jsp" />
	</definition>

	<definition name="SearchThrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ThrushHoldSearch.jsp" />
	</definition>

	<definition name="updateThrushholdValues" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ThrushHoldEdit.jsp" />
	</definition>

	<definition name="PMGetEquipment" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ThrushHoldEquipSearch.jsp" />
	</definition>

	<definition name="partname" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartName.jsp" />
	</definition>
	<definition name="warehousecreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseCreate.jsp" />
	</definition>
	<definition name="warehousesearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseSearch.jsp" />
	</definition>
	<definition name="warehouseedit" extends="base">

		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseEdit.jsp" />
	</definition>

	<definition name="warehouseview" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseView.jsp" />
	</definition>
	<definition name="warehouseaddparts" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseAddParts.jsp" />
	</definition>
	<definition name="warehousebatch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/WarehouseBatch.jsp" />
	</definition>
	<definition name="reservepart" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReservePart.jsp" />
	</definition>
	<definition name="partissue" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartIssue.jsp" />
	</definition>
	<definition name="partrecieve" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartRecieve.jsp" />
	</definition>
	<definition name="vendor" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Vendor.jsp" />
	</definition>

	<definition name="manufacturer" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/Manufacturer.jsp" />
	</definition>

	<definition name="pmReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/pmScheduleSearch.jsp" />
	</definition>

	<definition name="reports" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/pmReports.jsp" />
	</definition>

	<definition name="pmReportSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/pmReportPdfSearch.jsp" />
	</definition>

	<definition name="createPart" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartCreate.jsp" />
	</definition>

	<definition name="adhocreport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SelfhelpReports.jsp" />
	</definition>

	<definition name="CreateSelfHelpReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/createSelfHelpReport.jsp" />
	</definition>


	<definition name="DesignSelfHelpReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/adhocDesign.jsp" />
	</definition>

	<definition name="viewSelfhelpReports" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/viewSelfhelpReports.jsp" />
	</definition>

	<definition name="editadhocreport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editAdhocReport.jsp" />
	</definition>



	<definition name="parttransfer" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartTransfer.jsp" />
	</definition>

	<definition name="parttransferissue" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartTransferIssue.jsp" />
	</definition>


	<definition name="parttransferissue" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PartTransferIssue.jsp" />
	</definition>

	<definition name="quotationupload" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/quotationUpload.jsp" />
	</definition>

	<definition name="reportinventory" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReportInventory.jsp" />
	</definition>

	<definition name="reportinventoryconsumption" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReportInventoryConsumption.jsp" />
	</definition>


	<definition name="reportinventoryparts" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReportInventoryParts.jsp" />
	</definition>

	<definition name="reportinventoryparttransaction"
		extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReportInventoryPartTransaction.jsp" />
	</definition>

	<definition name="reportinventoryparttransfer"
		extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ReportInventoryPartTransfer.jsp" />
	</definition>
	<definition name="searchquotation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SearchQuotation.jsp" />
	</definition>
	<definition name="purchaseordersearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SearchPurchaseOrder.jsp" />
	</definition>
	<definition name="purchaseorderupload" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/purchaseOrderUpload.jsp" />
	</definition>
	<definition name="printreport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/printFaultReport.jsp" />
	</definition>
	<definition name="printreportjfp" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/printfaultreportjfp.jsp" />
	</definition>
	<definition name="geolocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/GeoLocation.jsp" />
	</definition>

	<definition name="bulkDataInsert" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/bulkDataInsert.jsp" />
	</definition>

	<definition name="fmmDashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/fmmDashboard.jsp" />
	</definition>
	<definition name="generalNotification" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/GeneralNotification.jsp" />
	</definition>
	<definition name="generalGrievanceFeedback" extends="base2">
		<put-attribute name="body"
			value="/WEB-INF/views/GeneralGrievanceFeedback.jsp" />
	</definition>
	<definition name="meGrievanceFeedback" extends="base2">
		<put-attribute name="body"
			value="/WEB-INF/views/MEGrievanceFeedback.jsp" />
	</definition>
	<definition name="MESubcategory" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MESubcategory.jsp" />
	</definition>
	
	<definition name="MEServices" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MEServices.jsp" />
	</definition>
	<definition name="tQrGenerate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/tQrGenerate.jsp" />
	</definition>
	<definition name="qrImage" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/qrImage.jsp" />
	</definition>

	<definition name="qrList" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/qrList.jsp" />
	</definition>

	<definition name="fList" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/fList.jsp" />
	</definition>

	<definition name="viewTfault" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/viewTfault.jsp" />
	</definition>

	<definition name="showCharts" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/showCharts.jsp" />
	</definition>

	<definition name="Successfull" extends="base2">
		<put-attribute name="body"
			value="/WEB-INF/views/Successfull.jsp" />
	</definition>
	<definition name="SupAdminDashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SupAdminDashboard.jsp" />
	</definition>

	<definition name="TFaultReportSearchStatus" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/TFaultReportSearchStatus.jsp" />
	</definition>

	<definition name="editableView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editableView.jsp" />
	</definition>
		<definition name="anonymousFaultReport" extends="base2">
		<put-attribute name="body"
			value="/WEB-INF/views/AnonymousFaultReportCreate.jsp" />
	</definition>
	<definition name="notavailable" extends="base2">
		<put-attribute name="body"
			value="/WEB-INF/views/NotAvailable.jsp" />
	</definition>
	<definition name="fence" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/fence.jsp" />
	</definition>
	
	
<definition name="serviceIndicator" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ServiceIndicator.jsp" />
	</definition>
	
<definition name="meterDashboard" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MeterDashboard.jsp" />
	</definition>
	
		<definition name="meter" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AddMeter.jsp" />
	</definition>
	
	<definition name="utility" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/viewMeterUtility.jsp" />
	</definition>
	
	<definition name="utilityReading" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/utilityReadingsearch.jsp" />
	</definition>
	
	<definition name="addMissingUtility" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/MissingReading.jsp" />
	</definition>
	
	<definition name="searchMeter" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/SearchMeterByCategory.jsp" />
	</definition>
	
	
	<definition name="anonymousFaultReportForm" extends="base3">
		<put-attribute name="body"
			value="/WEB-INF/views/AnonymousFaultReportCreateForm.jsp" />
	</definition>
	
	<definition name="editutility" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/UpdateUtility.jsp" />
	</definition>
	
	  <definition name="managementGrievanceFeedback" extends="base3">
    <put-attribute name="body"
      value="/WEB-INF/views/ManagementGrievanceFeedbackForm.jsp" />
  </definition>
	<definition name="JFP_Dashboard" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/dashboard_JFP.jsp" />
  </definition>
  
  <definition name="editutility" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/UpdateUtility.jsp" />
	</definition>
	
	<definition name="cleaningSearch" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/cleaningLocationSearch.jsp" />
  </definition>
  

      
  <definition name="jfpCleaningLocation" extends="base">
      <put-attribute name="body"
        value="/WEB-INF/views/jfpCleaningLocation.jsp" />
    </definition>
  
  <definition name="printCleaning" extends="base">
      <put-attribute name="body"
        value="/WEB-INF/views/printcleaningreport.jsp" />
    </definition>
    
    <definition name="viewEnforcementNotice" extends="base">
      <put-attribute name="body"
        value="/WEB-INF/views/ViewEnforcementNotice.jsp" />
    </definition>
       <definition name="downloadReport" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/DownloadReport.jsp" />
  </definition>
  
  <definition name="carParkingUpload" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CarParkingUpload.jsp" />
	</definition> 
	
	 <definition name="carParkingDownload" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/CarParkingDownload.jsp" />
	</definition>
	
	<definition name="carParkingCollectionPreview" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/CarParkingCollectionPreview.jsp" /> 
 </definition>
 <definition name="attendanceDownload" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/AttendanceDownload.jsp" /> 
 </definition>
    
      <definition name="shiftDownload" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/ShiftDownload.jsp" /> 
 </definition>
 <definition name="attendancedashboard" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/admin/attendancedashboard.jsp" />
  </definition>
<definition name="carparkingDashboard" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/admin/carparkingDashboard.jsp" />
  </definition>
  <definition name="printEnforcement" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/printEnforcement.jsp" />
  </definition>
  
    <definition name="attendanceUploadFile" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AttendanceUploadFile.jsp" />
	</definition>
<definition name="attendanceSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AttendanceSearch.jsp" />
	</definition>
  
  <definition name="masterScheduleReport" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/masterScheduleReport.jsp" />
  </definition>
  
  <definition name="addAttendance" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/addAttendance.jsp" /> 
 </definition>
 
          <definition name="kpiDownload" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/KpiDownload.jsp" /> 
 </definition>
  <definition name="license" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/License.jsp" /> 
 </definition>
    <definition name="licenseSearch" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/LicenseSearch.jsp" /> 
 </definition>
 
 <definition name="LocationPMScheduleView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LocationScheduleSearch.jsp" />
	</definition>
	<definition name="locationScheduleEdit" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/LocationScheduleEdit.jsp" />
	</definition>
<definition name="LocationPMTaskView" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationtaskSearch.jsp" />
	</definition>
	
	<definition name="locationpmReportSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationpmReportPdfSearch.jsp" />
	</definition>
	
	<definition name="locationpmReport" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationpmScheduleSearch.jsp" />
	</definition>
	
	<definition name="getPMSelectedLocations" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PMScheduleSearchLocation.jsp" />
	</definition>
	
	<definition name="LocationPMtaskModify" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationtaskModify.jsp" />
	</definition>
	
	<definition name="locationchecklistTaskUpdate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationchecklistTaskUpdate.jsp" />
	</definition>
	
	<definition name="printlocationtaskchecklist" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/printlocationTaskChecklist.jsp" />
	</definition>
	
	<definition name="LocationMonthlyTasks" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationmonthlytasks.jsp" />
	</definition>
	
	<definition name="locationscheduleCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationScheduleCreate.jsp" />
	</definition>
	
	<definition name="listForReviewLocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ListForReviewLocation.jsp" />
	</definition>
	
	<definition name="listForAdminLocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ListForAdminLocation.jsp" />
	</definition>
	
	<definition name="scheduleEditForReviewLocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleEditForReviewerLocation.jsp" />
	</definition>
	
	<definition name="scheduleEditForAdminLocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/ScheduleEditForAdminLocation.jsp" />
	</definition>
	
	<definition name="locationchecklistcreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationchecklistcreate.jsp" />
	</definition>
	
	
	<definition name="adddraftlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/locationdraftcreate.jsp" />
	</definition>
	
	
	<definition name="searchdraftlocation" extends="base">
		<put-attribute name="body" 
			 value="/WEB-INF/views/searchDraftLocation.jsp" />
	</definition>
	
		<definition name="checklistsearchlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistSearchLocation.jsp" />
	</definition>
	
		<definition name="editchecklistlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editchecklistlocation.jsp" />
	</definition>
	
		<definition name="editdraftlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editdraftlocation.jsp" />
	</definition>
	
	<definition name="editchecklistlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editchecklistlocation.jsp" />
	</definition>
	
	<definition name="editdraftlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editdraftlocation.jsp" />
	</definition>
	
	<definition name="checklistlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistlocation.jsp" />
	</definition>
		<definition name="editchecklistlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/editchecklistlocation.jsp" />
	</definition>
	
		<definition name="searchdraftlocation" extends="base">
		<put-attribute name="body" 
			 value="/WEB-INF/views/searchDraftLocation.jsp" />
	</definition>
	
	<definition name="checklistsearchlocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/checklistSearchLocation.jsp" />
	</definition>
	
	<definition name="getPMSelectedLocations" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/PMScheduleSearchLocation.jsp" />
	</definition>
	
	<definition name="masterScheduleLocation" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/masterScheduleLocation.jsp" />
	</definition>
	
	<definition name="homecl" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardcleaning.jsp" />
	</definition>
	<definition name="homepest" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardpest.jsp" />
	</definition>
	<definition name="homelandscape" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardlandscape.jsp" />
	</definition>
	
	<definition name="homewastage" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/dashboardwastage.jsp" />
	</definition>
	
	<definition name="addCarParkUser" extends="base"> 
  <put-attribute name="body" 
   value="/WEB-INF/views/CarParkUser.jsp" /> 
 </definition>
 
 <definition name="addKpi" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/addKpi.jsp" />
  </definition>

<definition name="addShift" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/addShift.jsp" /> 
 </definition>  
   
     <definition name="carParkBooth" extends="base"> 
  <put-attribute name="body" 
   value="/WEB-INF/views/CarParkBooth.jsp" /> 
 </definition>
  
 <definition name="maOffice" extends="base"> 
  <put-attribute name="body" 
   value="/WEB-INF/views/MaOffice.jsp" /> 
 </definition>    
 
 <definition name="createCarParkCollection" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/CreateCarParkCollection.jsp" /> 
 </definition> 
 
   <definition name="pendingPMScheduleReport" extends="base">
      <put-attribute name="body"
        value="/WEB-INF/views/PendingPMScheduleReport.jsp" />
  </definition> 
  
  <definition name="reportsdashboard" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/dashboardreportsnew.jsp" /> 
 </definition>
 
 <definition name="sopCreate" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/sopCreate.jsp" />
	</definition>
	
	
	<definition name="sopSearch" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/sopView.jsp" />
	</definition>
	
	<definition name="anonymousESGFaultReportForm" extends="base3">
    <put-attribute name="body"
      value="/WEB-INF/views/AnonymousESGFaultReportCreate.jsp" />
  </definition>
  
  <definition name="anonymousRafflesFaultReportForm" extends="base3">
    <put-attribute name="body"
      value="/WEB-INF/views/AnonymousRafflesFaultReportCreate.jsp" />
  </definition>
  
   <definition name="CleaningSearch" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/CleaningSearch.jsp" />
  </definition>
  
  <definition name="editKpi" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/EditKpi.jsp" />
  </definition>
  <definition name="viewRecipt" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewRecipt.jsp" />
  </definition>

  <definition name="allRecipts" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/AllRecipts.jsp" />
  </definition>
<definition name="scanQrCode" extends="base2">
      <put-attribute name="body" value="/WEB-INF/views/scanQrCode.jsp"/>
  </definition>
  <definition name="printCart" extends="base2">
      <put-attribute name="body" value="/WEB-INF/views/printCart.jsp"/>
  </definition>
   <definition name="recieptPrint" extends="base2">
      <put-attribute name="body" value="/WEB-INF/views/recieptPrint.jsp"/>
  </definition>
  <definition name="ViewSales" extends="base2">
    <put-attribute name="body"
     value="/WEB-INF/views/ViewSales.jsp" />
 </definition>
   <definition name="TransferMainItem" extends="base2">
      <put-attribute name="body" value="/WEB-INF/views/transferItems.jsp"/>
  </definition>
  <definition name="ViewTransferMainItems" extends="base2">
      <put-attribute name="body" value="/WEB-INF/views/ViewTransferMainItems.jsp"/>
  </definition>
<definition name="parkingRate" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/AddParkingRate.jsp" />
  </definition>
  <definition name="recipt" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/Recipt.jsp" />
  </definition>
  <definition name="updateReceiverReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/UpdateReceiverReserveItem.jsp" />
  </definition>
  
  <definition name="scheduleDelete" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/scheduleDelete.jsp" /> 
 </definition>
 
 <definition name="searchSecurity" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/SearchSecurity.jsp" />
  </definition>
    <definition name="securityAttendance" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/SecurityAttendance.jsp" />
  </definition>   
   <definition name="checkGeolocation" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/CheckGeolocation.jsp" />
  </definition>
  <definition name="cleaningImages" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/UploadCleaningImages.jsp" />
  </definition>
   <definition name="whatsappnotification" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/whatsappnotification.jsp" />
  </definition>
  <definition name="addPartsToFault" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/AddPartsToFault.jsp" />
	</definition>
  <definition name="viewPartsInFault" extends="base">
		<put-attribute name="body"
			value="/WEB-INF/views/viewPartsInFault.jsp" />
	</definition>
	<definition name="partInUseReport" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/partInUseReport.jsp" /> 
 </definition>
 <definition name="rfaVerifier" extends="base4">
  <put-attribute name="body"
   value="/WEB-INF/views/rfaVerifier.jsp" />
 </definition>
 <definition name="searchTopLocationFaults" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/FaultReportTopLocationSearch.jsp" /> 
 </definition>
	<definition name="FaultReportingFormByStaff" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/FaultReportingFormByStaff.jsp" />
  </definition>
 
 
 <definition name="esguserdetails" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/esguserdetails.jsp" />
  </definition>
  
  <definition name="addutilityreading" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/addutilityreading.jsp" />
  </definition>
  
  
  <definition name="maintype" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/maintype.jsp" />
  </definition>
 
  <definition name="mainlocation" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/mainlocation.jsp" />
  </definition>
  
  <definition name="MainCategory" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/MainCategory.jsp" />
  </definition>
  
   <definition name="CreateMainInventory" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/CreateMainInventory.jsp" />
  </definition>
  
  <definition name="mainItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/MainItem.jsp" />
  </definition>
  
   <definition name="viewMainInventories" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewMainInventories.jsp" />
  </definition>
  
   <definition name="updateMainInventory" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/UpdateMainInventory.jsp" />
  </definition>
  
    <definition name="mainsupplier" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/MainSupplier.jsp" />
  </definition>
  
  
   <definition name="CreatePurchaseOrder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/CreatePurchaseOrder.jsp" />
  </definition>
  
<definition name="mainItemEdit" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/MainItemEdit.jsp" />
  </definition>
  
   <definition name="viewMainItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/viewMainItem.jsp" />
  </definition>
 
  
   <definition name="viewPurchaseOrder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewPurchaseOrder.jsp" />
  </definition>
  
  
   <definition name="brand" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/Brand.jsp" />
  </definition>
  
   
   <definition name="ReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ReserveItem.jsp" />
  </definition>
  
     <definition name="ViewReserveItems" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewReserveItems.jsp" />
  </definition>
  
     <definition name="updateReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/UpdateReserveItem.jsp" />
  </definition>
  
       <definition name="ViewWorkspaceReserveItems" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewWorkspaceReserveItems.jsp" />
  </definition>
  
    <definition name="updateWorkspaceReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/UpdateWorkspaceReserveItem.jsp" />
  </definition>
  
  <definition name="MainUnit" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/MainUnit.jsp" />
  </definition>
 
  <definition name="addinventorystock" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/addinventorystock.jsp" />
  </definition>
  
   <definition name="ThresholdInventories" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ThresholdInventories.jsp" />
  </definition>
  
  
   <definition name="AlarmInventories" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/AlarmInventories.jsp" />
  </definition>
  
  <definition name="ReceiveReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ReceiveReserveItem.jsp" />
  </definition>
  
    <definition name="TransportReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/TransportReserveItem.jsp" />
  </definition>
  <definition name="workspaceInventoryEdit" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/WorkspaceInventoryEdit.jsp" />
  </definition>
  
   <definition name="viewWorkspaceInventory" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewWorkspaceInventory.jsp" />
  </definition>
<definition name="workspaceInventory" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/WorkspaceInventory.jsp" />
      
  </definition>
  <definition name="ReceivePurchaseOrder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ReceivePurchaseOrder.jsp" />
  </definition>
  <definition name="TransportReserveItem" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/TransportReserveItem.jsp" />
  </definition>
  
  <definition name="rfadashboard" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/RfaDashboard.jsp" />
  </definition>
  
  <definition name="RFAReportSearch" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/RFAReportSearch.jsp" />
  </definition>
  
  <definition name="printpurchaseorder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/PrintPurchaseOrder.jsp" />
  </definition>
  
  <definition name="CreateSupplyPurchaseOrder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/CreateSupplyPurchaseOrder.jsp" />
  </definition>
  
      <definition name="ReceiveSupplyPurchaseOrder" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ReceiveSupplyPurchaseOrder.jsp" />
  </definition>
  
  <definition name="parkingRate" extends="base">
    <put-attribute name="body"
      value="/WEB-INF/views/AddParkingRate.jsp" />
  </definition>
  
  <definition name="viewRecipt" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/ViewRecipt.jsp" />
  </definition>

  <definition name="allRecipts" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/AllRecipts.jsp" />
  </definition>

  <definition name="recipt" extends="base2">
    <put-attribute name="body"
      value="/WEB-INF/views/Recipt.jsp" />
  </definition>
  
   <definition name="receiptdashboard" extends="base"> 
    <put-attribute name="body" 
     value="/WEB-INF/views/receiptDashboard.jsp" /> 
 </definition>
  
  
  
</tiles-definitions>
