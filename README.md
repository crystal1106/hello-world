<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<templates>
	<template autoinsert="false" context="gettercomment_context"
		deleted="false" description="Comment for getter method" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.gettercomment" name="gettercomment">
/**
 * get ${bare_field_name}
 * @return the ${bare_field_name}
 */
	</template>
	<template autoinsert="false" context="settercomment_context"
		deleted="false" description="Comment for setter method" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.settercomment" name="settercomment">
/**
 * set ${bare_field_name}
 * @param ${param} the ${bare_field_name} to set
 */
	</template>
	<template autoinsert="false" context="constructorcomment_context"
		deleted="false" description="Comment for created constructors"
		enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.constructorcomment"
		name="constructorcomment">
/**
 * <p>Description:</p>
 * ${tags}
 */
	</template>
	<template autoinsert="false" context="filecomment_context"
		deleted="false" description="Comment for created Java files" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.filecomment" name="filecomment">
/**
 * @Title:${file_name}
 * @Package:${package_name}
 * @Description:${todo}
 * @author:chenrong
 * @date:${date}
 */
	</template>
	<template autoinsert="false" context="typecomment_context"
		deleted="false" description="Comment for created types" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.typecomment" name="typecomment">
/**
 **************************************************
 * ClassName:${type_name}
 * @Description:${todo}
 * @author:chenrong
 * @date:${date}
 **************************************************
 */
	</template>
	<template autoinsert="false" context="fieldcomment_context"
		deleted="false" description="Comment for fields" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.fieldcomment" name="fieldcomment">
/**
 * @Fields ${field}:${todo}
 */
	</template>
	<template autoinsert="false" context="methodcomment_context"
		deleted="false" description="Comment for non-overriding methods"
		enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.methodcomment"
		name="methodcomment">
/** @Description:${todo}
 * @param:${tags}
 * @return:${return_type}
 * @throws
 * @author:chenrong
 * @date:${date} 
 */
	</template>
	<template autoinsert="false" context="overridecomment_context"
		deleted="false" description="Comment for overriding methods" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.overridecomment" name="overridecomment" />
	<template autoinsert="true" context="delegatecomment_context"
		deleted="false" description="Comment for delegate methods" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.delegatecomment" name="delegatecomment">
/**
 * ${tags}
 * ${see_to_target}
 */
	</template>
	<template autoinsert="true" context="newtype_context" deleted="false"
		description="Newly created files" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.newtype" name="newtype">
		${filecomment}
		${package_declaration}
		${typecomment}
		${type_declaration}
	</template>
	<template autoinsert="true" context="classbody_context"
		deleted="false" description="Code in new class type bodies" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.classbody" name="classbody">
	</template>
	<template autoinsert="true" context="interfacebody_context"
		deleted="false" description="Code in new interface type bodies"
		enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.interfacebody"
		name="interfacebody">
	</template>
	<template autoinsert="true" context="enumbody_context"
		deleted="false" description="Code in new enum type bodies" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.enumbody" name="enumbody">
	</template>
	<template autoinsert="true" context="annotationbody_context"
		deleted="false" description="Code in new annotation type bodies"
		enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.annotationbody"
		name="annotationbody">
	</template>
	<template autoinsert="true" context="catchblock_context"
		deleted="false" description="Code in new catch blocks" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.catchblock" name="catchblock">
		// ${todo} Auto-generated catch block
		${exception_var}.printStackTrace();
	</template>
	<template autoinsert="true" context="methodbody_context"
		deleted="false" description="Code in created method stubs" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.methodbody" name="methodbody">
		// ${todo} Auto-generated method stub
		${body_statement}
	</template>
	<template autoinsert="true" context="constructorbody_context"
		deleted="false" description="Code in created constructor stubs"
		enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.constructorbody"
		name="constructorbody">
		${body_statement}
		// ${todo} Auto-generated constructor stub
	</template>
	<template autoinsert="true" context="getterbody_context"
		deleted="false" description="Code in created getters" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.getterbody" name="getterbody">
		return ${field};</template>
	<template autoinsert="true" context="setterbody_context"
		deleted="false" description="Code in created setters" enabled="true"
		id="org.eclipse.jdt.ui.text.codetemplates.setterbody" name="setterbody">
		${field} =	${param};</template>
</templates>
