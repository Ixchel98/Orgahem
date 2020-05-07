# Orgahem
Organic Chemistry 
Hi  guys, I would like to bring knowledge of organic chemistry to anyone.                    
yarn android- ( react-native run-android) 
$ npm install -g create-react-native-app
$ create-react-native-app my-app
$ cd my-app/
$ npm start
import React, { Component } from 'react';
import {  StyleSheet,  Text,  View,  TouchableHighlight,  Image,              ActivityIndicator,  StatusBar} from 'react-native';
export default class home extends Component {
  constructor(){}
  //métodos, funciones, estados, logica
  render(){
   return{
    //vistas del proyecto en JSX  
   }
  }
  const styles = StyleSheet.create({
    //Estilos css del proyecto
  )}
  constructor() {
  super();
  let source = null;
  this.state = {   
     tags:'No has subido ninguna imagen',  
     contenido: null,   
  };   
  this.onPressButtonGET = this.onPressButtonGET.bind(this);   
}
