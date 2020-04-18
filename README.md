# ONTOLOGIA-PROYECTO-CHATBOT
ONTOLOGIA DEL PROYECTO REALIZADA EN PROTEGE
<?xml version="1.0"?>
<rdf:RDF xmlns="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#"
     xml:base="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl."
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
     xmlns:Ontología-IDC-OntologíasTecnológico="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#">
    <owl:Ontology rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl."/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Contiene_Un -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Contiene_Un">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Para_Una"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Aplicada_En -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Aplicada_En">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Necesita_Una"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Asignado_A -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Asignado_A">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tomada_Por"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Cursada_Por -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Cursada_Por">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A_Una"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Impartida_Por -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Impartida_Por">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Imparte"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Para_Hacer -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Para_Hacer">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Utiliza_El"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Para_Una -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Para_Una">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tomada_Por -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tomada_Por">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tramitado_Por -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tramitado_Por">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Realiza"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tratado_Con -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Tratado_Con">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Utiliazada_Para"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Utiliazada_Para -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es_Utiliazada_Para">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Imparte -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Imparte">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Necesita_Una -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Necesita_Una">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tienen_Su"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A_Un -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A_Un">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Un"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A_Una -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Pertenece_A_Una">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Realiza -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Realiza">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Aplica_A_Una -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Aplica_A_Una">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Su"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Compone_De -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Compone_De">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Usa_En"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Realizan_Los -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Realizan_Los">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Son_Realizados_En"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Usa_En -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Usa_En">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Utiliza_El -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Se_Utiliza_El">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Son_Realizaas_En -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Son_Realizaas_En">
        <owl:inverseOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es:Utilizado_Para_Impartir"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Son_Realizados_En -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Son_Realizados_En">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Su -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Su">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Un -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tiene_Un">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tienen_Su -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tienen_Su">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
    </owl:ObjectProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es:Utilizado_Para_Impartir -->

    <owl:ObjectProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Es:Utilizado_Para_Impartir">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas"/>
        <rdfs:range rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias"/>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Adeudo -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Adeudo">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Apellido_Materno -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Apellido_Materno">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Apellido_Paterno -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Apellido_Paterno">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Calle -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Calle">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Causas_Deserción -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Causas_Deserción">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Clave_de_Asignatura -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Clave_de_Asignatura">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Codigo_de_Carrera -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Codigo_de_Carrera">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Correo -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Correo">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Descripción -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Descripción">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Beca_Alimentos_y_Transporte"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documento_Oficial"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Inscripción"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Residencia_Profesional"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Servicio_Social"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documentos -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documentos">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Duración_de_Carrera -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Duración_de_Carrera">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Día -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Día">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#E-mail -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#E-mail">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Hora -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Hora">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Lugar -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Lugar">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Nombre -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Nombre">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Npumero_de_Créditos -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Npumero_de_Créditos">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Complementarias"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Especialidad"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Estructura_Generica"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia_Profesional"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio_Social"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Actividades -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Actividades">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Aisgnaturas -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Aisgnaturas">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Especialidad"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Estructura_Generica"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Control -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Control">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Beca_Alimentos_y_Transporte"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documento_Oficial"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Inscripción"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Residencia_Profesional"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Servicio_Social"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#long"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Horas -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de_Horas">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de__materias_reprobadas -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Número_de__materias_reprobadas">
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_de_Estudios -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_de_Estudios">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Proyecto -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Proyecto">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Región -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Región">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Reticula -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Reticula">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Semestre -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Semestre">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Situación -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Situación">
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Telefono -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Telefono">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#long"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tipo_de_Actividad -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tipo_de_Actividad">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tipo_de_Asignatura -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tipo_de_Asignatura">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Total_de_Créditos -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Total_de_Créditos">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite -->

    <owl:DatatypeProperty rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite">
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Beca_Alimentos_y_Transporte"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documento_Oficial"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Inscripción"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Residencia_Profesional"/>
        <rdfs:domain rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Servicio_Social"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Complementarias -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Complementarias">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividades_Extraescolares">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#AsignaturaM">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Beca_Alimentos_y_Transporte -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Beca_Alimentos_y_Transporte">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Complementarias">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Director">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#División_de_estudios">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documento_Oficial -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Documento_Oficial">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Especialidad -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Especialidad">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Estructura_Generica -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Estructura_Generica">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Financieros">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Inscripción -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Inscripción">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Nombre -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Nombre">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia_Profesional -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Residencia_Profesional">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio_Social -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicio_Social">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Servicios_Escolares">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Residencia_Profesional -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Residencia_Profesional">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Servicio_Social -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#T_Servicio_Social">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
    </owl:Class>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites -->

    <owl:Class rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites">
        <rdfs:subClassOf rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tecnológico"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se lleva a cabo en el aula de vinculación</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Miercoles y vienres de 2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Taller de Ajedrez</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">1</Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Complen
Complementaria - Deportiva</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se imparte en centro de información</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Taller de photoshop</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">1</Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Compelemntaria - Cultural</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se imparte en sala de vinculación y se hacen manualidades</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Taller de artes manuales</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">1</Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Complementaria - Cultural</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_4 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_4">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Danza foljlorica Xali Nayare Kore, bailes tipicos mexicanos</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Danza</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int"></Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Complementaria . Cultural</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_5 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_5">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Banda de guerra del tec del sur, asiste a eventos</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Banda de guerra</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int"></Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Complementaria/Horas servicio - Cultural</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_6 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_6">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Rondalla corazón romantico, conformada por alumnos del tec del sur</Descripción>
        <Horario rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M a 3 P.M</Horario>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Rondalla</Nombre>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int"></Npumero_de_Créditos>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Complementaria - Cultural</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_7 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_7">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se presta servicio a una institución publica o privada de los 
        conocimientos adquiridos durantes los semestres</Descripción>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se necesita solicitar el servicio social en división de estudios profesionales</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Servicio Social</Nombre>
        <Número_de_Horas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">480</Número_de_Horas>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Servicio Social</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_8 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_8">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#ActividadesAcadémicas"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se realiza una simulación de trabajo durante un periodo de 6 meses en una empresa</Descripción>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">El asesor es el encargado de la documentación que le va brindando el asesorado</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Residencia Profesional</Nombre>
        <Número_de_Horas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">1</Número_de_Horas>
        <Tipo_de_Actividad rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Residencia Profesional</Tipo_de_Actividad>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_2"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_3"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_5"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_6"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_7"/>
        <Pertenece_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Inscripción"/>
        <Tiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_1"/>
        <Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Carrera>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Es un alumno del sexto semestre de la carrera de ITIC</Descripción>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Josue García Gonzalez</Nombre>
        <Número_de_Control rdf:datatype="http://www.w3.org/2001/XMLSchema#long">1711140004</Número_de_Control>
        <Proyecto rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ninguno</Proyecto>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
        <Situación rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Con leve retraso reticular</Situación>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_2"/>
        <Pertenece_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Inscripción"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social"/>
        <Tiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_2"/>
        <Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Carrera>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Alumno de la carrera de ITIC</Descripción>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Hector Daniel Talamantes</Nombre>
        <Número_de_Control rdf:datatype="http://www.w3.org/2001/XMLSchema#long">171140002</Número_de_Control>
        <Proyecto rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ninguno</Proyecto>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
        <Situación rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Avance reticular normal</Situación>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4"/>
        <Pertenece_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte"/>
        <Tiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_3"/>
        <Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Carrera>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Alumno de la carrera de ITIC</Descripción>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Erik Gomez Delgadillo</Nombre>
        <Número_de_Control rdf:datatype="http://www.w3.org/2001/XMLSchema#long">171140023</Número_de_Control>
        <Proyecto rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ninguno</Proyecto>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
        <Situación rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Avance reticular normal</Situación>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_3"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_5"/>
        <Pertenece_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social"/>
        <Tiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_4"/>
        <Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Carrera>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Alumno de la carrera de ITIC</Descripción>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Alfonso Villegas Robles</Nombre>
        <Número_de_Control rdf:datatype="http://www.w3.org/2001/XMLSchema#long">171140012</Número_de_Control>
        <Proyecto rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ninguno</Proyecto>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
        <Situación rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Avance reticular normal</Situación>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carpeta_Alumno"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1"/>
        <Es_Asignado_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_1"/>
        <Pertenece_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Realiza rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Tiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_5"/>
        <Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Carrera>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Alumno de la carrera de ITIC</Descripción>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Jennifer Valdez Bernal</Nombre>
        <Número_de_Control rdf:datatype="http://www.w3.org/2001/XMLSchema#long">171140027</Número_de_Control>
        <Proyecto rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ninguno</Proyecto>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
        <Situación rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Avance reticular normal</Situación>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_2"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1"/>
        <Necesita_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_1"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ingeniería del Conocimiento</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_4"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Taller de Ingeniería de Software</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_5"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Necesita_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_2"/>
        <Necesita_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_3"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Negocios Eletrónicos I</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_3"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Desarrollo de Emprendedores</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_5 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_5">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_6"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Sistemas Operativos I</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_6 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_6">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Impartida_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_7"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Taller de Investigación II</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_7 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_7">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura"/>
        <Es_Tomada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5"/>
        <Clave_de_Asignatura rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ACA – 0910</Clave_de_Asignatura>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Redes de Computadoras</Nombre>
        <Plan_de_Estudios rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ITIC</Plan_de_Estudios>
        <Semestre rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Semestre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1"/>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">54</Npumero_de_Créditos>
        <Número_de_Aisgnaturas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">19</Número_de_Aisgnaturas>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">25</Npumero_de_Créditos>
        <Número_de_Aisgnaturas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">6</Número_de_Aisgnaturas>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">52</Npumero_de_Créditos>
        <Número_de_Aisgnaturas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">13</Número_de_Aisgnaturas>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_4 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_4">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">85</Npumero_de_Créditos>
        <Número_de_Aisgnaturas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">21</Número_de_Aisgnaturas>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_5 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular_5">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Avance_Reticular"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5"/>
        <Npumero_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">140</Npumero_de_Créditos>
        <Número_de_Aisgnaturas rdf:datatype="http://www.w3.org/2001/XMLSchema#int">30</Número_de_Aisgnaturas>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <Contiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Gestión_Empresarial"/>
        <Codigo_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">IGEM-2009-201</Codigo_de_Carrera>
        <Duración_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a 12 Meses</Duración_de_Carrera>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ingeniería en Gestión Empresarial</Nombre>
        <Total_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">260</Total_de_Créditos>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <Contiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Industrias_Alimentarias"/>
        <Codigo_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">IIAL-2010-219</Codigo_de_Carrera>
        <Duración_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a 12 Meses</Duración_de_Carrera>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ingeniería en Industrias Alimentarias</Nombre>
        <Total_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">260</Total_de_Créditos>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera"/>
        <Contiene_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_TICS"/>
        <Es_Cursada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1"/>
        <Es_Cursada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Es_Cursada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Es_Cursada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Es_Cursada_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5"/>
        <Codigo_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">TIF-1003</Codigo_de_Carrera>
        <Duración_de_Carrera rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a 12 Meses</Duración_de_Carrera>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ingeniería en Tecnológias de la Información y Comunicaciones</Nombre>
        <Total_de_Créditos rdf:datatype="http://www.w3.org/2001/XMLSchema#int">260</Total_de_Créditos>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección_Tecnológico -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección_Tecnológico">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Dirección"/>
        <Lugar rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Carretera Crucero Jala-Ahuacatlan</Lugar>
        <Región rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Zona sur de Nayarit</Región>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Actividades_Extraescolares -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Actividades_Extraescolares">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <Tiene_Su rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Actividades_Extraescolares"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Hector Eli Sida</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Director -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Director">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <Tiene_Su rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Director"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Mario Soto</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_División_De_Estudios -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_División_De_Estudios">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <Es_Para_Hacer rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Residencia_Profesional"/>
        <Es_Para_Hacer rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social"/>
        <Tiene_Su rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_División_Estudios_Profesionales"/>
        <E-mail rdf:datatype="http://www.w3.org/2001/XMLSchema#string">dep_surnayarit@tecnm.mx</E-mail>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Cinthia Anahi Mata Bravo</Nombre>
        <Telefono rdf:datatype="http://www.w3.org/2001/XMLSchema#long">3119105919</Telefono>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Financieros -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Financieros">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <Es_Para_Hacer rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Tiene_Su rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Financieros"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Sinhue Ibarra</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Servicios_Escolares -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Servicios_Escolares">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#EncargadosDepartamento"/>
        <Es_Para_Hacer rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte"/>
        <Es_Para_Hacer rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Tiene_Su rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Servicios_Escolares"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Juan Antonio Rodriguez Ramirez</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Act_Complementarias">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Actividades_Académicas"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_1"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_2"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_3"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_4"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Actividad_Académica_5"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2 P.M. a 3 P.M.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Actividades_Extraescolares -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Actividades_Extraescolares">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Actividades_Extraescolares"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a.m. a 4 p.m.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Director -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Director">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Director"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a.m. a 4 p.m.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_División_Estudios_Profesionales -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_División_Estudios_Profesionales">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_División_De_Estudios"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Residencia_Profesional"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a.m. a 4 p.m.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Financieros -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Financieros">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Financieros"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Inscripción"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a.m. a 4 p.m.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Servicios_Escolares -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Servicios_Escolares">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Atención"/>
        <Pertenece_A_Un rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Servicios_Escolares"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte"/>
        <Se_Realizan_Los rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial"/>
        <Día rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lunes a Viernes</Día>
        <Hora rdf:datatype="http://www.w3.org/2001/XMLSchema#string">9 a.m. a 4 p.m.</Hora>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_7"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Juan Antonio Rodriguez Ramirez</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_1"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Cinthia Anahi Mata Bravo</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_4"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Salvador Portugal Luna</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_4 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_4">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_2"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Erik Renato Acosta</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_5 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_5">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_3"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Eduardo Topete</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_6 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_6">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_5"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Carlos Rivera</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_7 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro_7">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Maestro"/>
        <Imparte rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Asignatura_6"/>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Lizeth Casillas Meza</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_Gestión_Empresarial -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_Gestión_Empresarial">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial"/>
        <Se_Aplica_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Formar profesionales que 
        contribuyan a la gestión de empresas e innovación de procesos; así como al diseño, implementación y desarrollo de sistemas 
        estratégicos de negocios, optimizando recursos en un entorno global, con ética y responsabilidad social.</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_Industrias_Alimentarias -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_Industrias_Alimentarias">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias"/>
        <Se_Aplica_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Formar profesionistas con sólidas bases científicas y tecnológicas, alto
        compromiso social, elevados valores éticos, actitudes y aptitudes que le permitan
        constituirse como agentes de cambio, capaces de integrar, desarrollar y consolidar
        redes de valor en los sistemas productivos de su entorno, mediante la
        industrialización de los alimentos.</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_TICS -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General_Ingeniería_En_TICS">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Objetivo_General"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Se_Aplica_A_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Ingeniería en Tecnologías de la Información y Comunicaciones
      Objetivo General:
         Formar profesionistas capaces de desarrollar, integrar y administrar tecnologías de la información y comunicaciones que contribuyan 
          a la productividad y al logro de los objetivos estratégicos de las organizaciones en un entorno globalizado; caracterizándose por ser 
          líderes, críticos, competentes, éticos y con visión emprendedora, comprometidos con el desarrollo sustentable.</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Gestión_Empresarial -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Gestión_Empresarial">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
        <Es_Para_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Gestión_Empresarial"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Industrias_Alimentarias -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_Industrias_Alimentarias">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
        <Es_Para_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_Industrias_Alimentarias"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_TICS -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudios_Ingeniería_En_TICS">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Plan_De_Estudio"/>
        <Es_Para_Una rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Pertenece_A rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Carrera_TICS"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
        <Es_Tratado_Con rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_1"/>
        <Causas_Deserción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">No tiene los recursos suficientes para continuar 
         con sus estudios</Causas_Deserción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
        <Es_Tratado_Con rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_2"/>
        <Causas_Deserción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Resago escolar</Causas_Deserción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#RiesgoDeserción"/>
        <Es_Tratado_Con rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_3"/>
        <Causas_Deserción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Se va a cambiar de domicilio</Causas_Deserción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_1 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_1">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <Es_Aplicada_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_1"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Solicitar una beca alimenticia y de transpor,  benito juarez</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_2 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_2">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <Es_Aplicada_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_2"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Hacer el analisis necesario para tomar materias que se 
        consideran de más importancia</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_3 -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución_Riesgo_Deserción_3">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Solución"/>
        <Es_Aplicada_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Es_Utiliazada_Para rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Riesgo_De_Deserción_3"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Tratar de quedarse en su localidad</Descripción>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Beca_Alimentos_y_Transporte">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_3"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Se_Utiliza_El rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Servicios_Escolares"/>
        <Son_Realizaas_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Servicios_Escolares"/>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Acudir a servicios escolares</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Beca de alimentos y transporte</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Doc_Oficial">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_5"/>
        <Se_Utiliza_El rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Financieros"/>
        <Se_Utiliza_El rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_Servicios_Escolares"/>
        <Son_Realizados_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Financieros"/>
        <Son_Realizados_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_Servicios_Escolares"/>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Acudir a servicios escolares</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Documento Oficial</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Inscripción -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Inscripción">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_1"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Acudir a servicios escolares</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Inscripción</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Residencia_Profesional -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Residencia_Profesional">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <Se_Utiliza_El rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_División_De_Estudios"/>
        <Son_Realizados_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_División_Estudios_Profesionales"/>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Acudir a división de estudios</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Residencia Profesional</Nombre>
    </owl:NamedIndividual>
    


    <!-- urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social -->

    <owl:NamedIndividual rdf:about="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramite_Servicio_Social">
        <rdf:type rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Tramites"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_2"/>
        <Es_Tramitado_Por rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Alumno_4"/>
        <Se_Utiliza_El rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Encargado_Dep_División_De_Estudios"/>
        <Son_Realizados_En rdf:resource="urn:absolute:Ontología-IDC-OntologíasTecnológico.owl.#Horario_Dep_División_Estudios_Profesionales"/>
        <Documentos rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Acudir a división de estudios</Documentos>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Servicio Social</Nombre>
    </owl:NamedIndividual>
     </rdf:RDF>



<!-- Generated by the OWL API (version 4.5.9.2019-02-01T07:24:44Z) https://github.com/owlcs/owlapi -->


