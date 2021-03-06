---
title: "SoftLayer_Survey_Response"
description: "The SoftLayer_Survey_Response data type contains general information relating to a single SoftLayer survey response."
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Survey"
classes:
    - "SoftLayer_Survey_Response"
---

# SoftLayer_Survey_Response
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
        <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Survey_Response' >Datatype</a></li>
    </ul>
</div>

## Description 
The SoftLayer_Survey_Response data type contains general information relating to a single SoftLayer survey response. 





<!-- Service Filer BEGIN -->
<div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Method Filter" onkeyup="titleSearch(inputId='prop-input', divId='properties', elementClass='prop-row')" 
                    type="text" id="prop-input" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
</div>
<!-- Service Filer END -->

<div id="properties" class="content">
    <div id="localProperties" class="prop-content" >
        <h2>Local</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#otherAnswer" name=otherAnswer>otherAnswer</a>
            </span>
            <div class='views-field-body'>The user typed response for the [[SoftLayer_Survey_Answer|Survey Answer]] that a response is associated with. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#surveyAnswerId" name=surveyAnswerId>surveyAnswerId</a>
            </span>
            <div class='views-field-body'>The Id of the [[SoftLayer_Survey_Answer|Survey Answer]] that a response was made for. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
            </div>
        <div id="relationalProperties"  class="prop-content" >
        <h2>Relational</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#surveyAnswer" name=surveyAnswer>surveyAnswer</a>
            </span>
            <div class='views-field-body'>The survey answer that this response was to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Survey_Answer'>SoftLayer_Survey_Answer </a></p>
            </div>
        </div>
                <h2>Count</h2>
            </div>
</div>


