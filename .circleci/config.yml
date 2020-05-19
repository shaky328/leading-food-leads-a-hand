import React, { Component } from 'react';
import { AppRegistry, Text, View, StyleSheet, Image, TextInput, ImageBackground, TouchableHighlight, Alert, Dimensions, ScrollView } from 'react-native';
import Constants from 'expo-constants';
let deviceHeight = Dimensions.get('window').height;
let deviceWidth = Dimensions.get('window').width;
export default class App extends Component {
 state={
     email:'email:',
     password:'password:',
   signin: '',
     companyname:'Company Name:',
     address:'Address:',
     owner:'Owner Name: ',
     time:'Resturant  times: ',
     pickup:'Avaible time for pick up:',
     food: 'Types of food that will be provided: ',
     pop:'How many people do you hold:',
     drop:'Aviable time for drop off:',
     clock:'Shelters times',
     p1PageDisplay:'block',
     p2PageDisplay:'none',
      p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'none',
          p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
         
         
 }
handleP1PagePress=()=> this.setState(state=>({
p1PageDisplay:'block',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
 p7PageDisplay:'none',
  p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP2PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'block',
p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
 p7PageDisplay:'none', 
 p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP3PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'block',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
 p7PageDisplay:'none',
  p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP4PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'block',
        p5PageDisplay:'none',
         p6PageDisplay:'none', 
          p7PageDisplay:'none', 
          p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP5PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'block',
         p6PageDisplay:'none',
         p7PageDisplay:'none',
          p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP6PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'block',
         p7PageDisplay:'none',
          p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP7PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'block', 
         p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP8PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'none', 
         p8PageDisplay:'block',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP9PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'none', 
         p8PageDisplay:'none',
          p9PageDisplay:'block',
          p10PageDisplay:'none',
           p11PageDisplay:'none',
}))
handleP10PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'none', 
         p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'block',
           p11PageDisplay:'none',
}))
handleP11PagePress=()=> this.setState(state=>({
p1PageDisplay:'none',
p2PageDisplay:'none',
 p3PageDisplay:'none',
       p4PageDisplay:'none',
        p5PageDisplay:'none',
         p6PageDisplay:'none',
         p7PageDisplay:'none', 
         p8PageDisplay:'none',
          p9PageDisplay:'none',
          p10PageDisplay:'none',
           p11PageDisplay:'block',
}))
render() {
     return (
        <View style={styles.container}>
      <View style ={{display:this.state.p1PageDisplay}}>
        <View style={styles.contentContainer}>
        <Image source={{uri:'https://editor.freelogodesign.org/?lang=en&logo=dd872f49-0ec5-491e-a415-2aa8dbb16334'}}
        style={{height:100, width:200}}>
           </Image>
       <View style={styles.box}>
        <Text style={styles.paragraph}>
       Welcome to
        </Text>
    
        <Text style={styles.paragraph}>
        Leading Food Leads A Hand
        </Text>
        </View>
  
     
        <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Start
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP2PagePress}>
           <Text style={styles.boxText}>
      Start
        </Text>
        </TouchableHighlight>
        </View>
        </View>
<View style ={{display:this.state.p2PageDisplay}}>
        <View style={styles.contentContainer}>
       <View style={styles.box}>
        <Text style={styles.paragraph}>
        LOGIN
        </Text>
    
        <Text style={styles.paragraph}>
        Enter your info:
        </Text>
        </View>
        <TextInput style={styles.textBar}
        onChangeText={(email)=>this.setState({email})}
        value={this.state.email}/>
     
     
        <TextInput style={styles.textBar}
         onChangeText={(password)=>this.setState({password})}
        value={this.state.password}/>
    
        </View>
        <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Or Sign in
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP3PagePress}>
           <Text style={styles.boxText}>
      Or Sign in
        </Text>
     
        </TouchableHighlight>
    
            <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Continue
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP4PagePress}>
           <Text style={styles.boxText}>
     Continue
        </Text>
     
        </TouchableHighlight>
        </View>
<View style ={{display:this.state.p3PageDisplay}}>
           <View style={styles.contentContainer}>
       <View style={styles.box}>
        <Text style={styles.paragraph}>
        SIGN IN
        </Text>
    
        <Text style={styles.paragraph}>
        Enter your info:
        </Text>
        </View>
        <TextInput style={styles.textBar}
        onChangeText={(companyname)=>this.setState({companyname})}
        value={this.state.companyname}/>
        <TextInput style={styles.textBar}
        onChangeText={(email)=>this.setState({email})}
        value={this.state.email}/>
    
        <TextInput style={styles.textBar}
         onChangeText={(password)=>this.setState({password})}
        value={this.state.password}/>
    
        </View>
        <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Or back to Login In
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP2PagePress}>
           <Text style={styles.boxText}>
      Or back to Login In
        </Text>
     
        </TouchableHighlight>
        </View>
         <View style ={{display:this.state.p4PageDisplay}}>
          <View style={styles.contentContainer}>
       <View style={styles.box}>
        <Text style={styles.paragraph}>
        Leading Food Leads A Hand
        </Text>
    
        <Text style={styles.paragraph}>
        Are you a:
        </Text>
        </View>
  
    
        </View>
        <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Restaurant
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP5PagePress}>
           <Text style={styles.boxText}>
      Restaurant
        </Text>
        </TouchableHighlight>
     
         <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
       Shelter
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP7PagePress}>
           <Text style={styles.boxText}>
      Shelter
        </Text>
        </TouchableHighlight>
        </View>
         <View style ={{display:this.state.p5PageDisplay}}>
         <View style={styles.contentContainer}>
         <View style={styles.box}>
        <Text style={styles.paragraph}>
        Fill in info for your Restaurant:
 
        </Text>
      <TextInput style={styles.textBar}
         onChangeText={(companyname)=>this.setState({companyname})}
        value={this.state.companyname}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(address)=>this.setState({address})}
        value={this.state.address}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(owner)=>this.setState({owner})}
        value={this.state.owner}/>
        </View>
         <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Next
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP6PagePress}>
           <Text style={styles.boxText}>
        Next
        </Text>
        </TouchableHighlight>
        </View>
        </View>
<View style ={{display:this.state.p6PageDisplay}}>
         <View style={styles.contentContainer}>
         <View style={styles.box}>
        <Text style={styles.paragraph}>
         Restaurant Times:
 
        </Text>
      <TextInput style={styles.textBar}
         onChangeText={(time)=>this.setState({time})}
        value={this.state.time}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(pickup)=>this.setState({pickup})}
        value={this.state.pickup}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(food)=>this.setState({food})}
        value={this.state.food}/>
        </View>
         <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Next
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP9PagePress}>
           <Text style={styles.boxText}>
        Next
        </Text>
        </TouchableHighlight>
        </View>
        </View>
 <View style ={{display:this.state.p7PageDisplay}}>
         <View style={styles.contentContainer}>
         <View style={styles.box}>
        <Text style={styles.paragraph}>
        Fill in info for your Shelter:
 
        </Text>
      <TextInput style={styles.textBar}
         onChangeText={(companyname)=>this.setState({companyname})}
        value={this.state.companyname}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(address)=>this.setState({address})}
        value={this.state.address}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(owner)=>this.setState({owner})}
        value={this.state.owner}/>
        </View>
         <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Next
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP8PagePress}>
           <Text style={styles.boxText}>
        Next
        </Text>
        </TouchableHighlight>
        </View>
        </View>
<View style ={{display:this.state.p8PageDisplay}}>
         <View style={styles.contentContainer}>
         <View style={styles.box}>
        <Text style={styles.paragraph}>
        Shelter Times:
 
        </Text>
      <TextInput style={styles.textBar}
         onChangeText={(clock)=>this.setState(clock)}
        value={this.state.clock}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(drop)=>this.setState({drop})}
        value={this.state.drop}/>
 
        <TextInput style={styles.textBar}
         onChangeText={(pop)=>this.setState({pop})}
        value={this.state.pop}/>
        </View>
         <View style={styles.blueBox}>
        <Text style={styles.buttonText}>
        Next
        </Text>
        </View>
        <TouchableHighlight style={styles.button}
        onPress={this.handleP9PagePress}>
           <Text style={styles.boxText}>
        Next
        </Text>
        </TouchableHighlight>
        </View>
        </View>
        <View style ={{display:this.state.p9PageDisplay}}>
         <View style={styles.contentContainer}>
         <View style={styles.box}>
        <Text style={styles.paragraph}>
        App info:
    
        </Text>
        </View>
       <View style={styles.box}>
        <Text style={styles.paragraph}>
      APP website: leadinghands.com
        </Text>
        </View>
          <View style={styles.box}>
        <Text style={styles.paragraph}>

        App Assiastance Number: 908-267-4083
        </Text>
        </View>
        </View>

    
        </View>
        </View>

   
    
     
    
        );
 }
}
const styles = StyleSheet.create({
container: {
     height: deviceHeight,
     width: deviceWidth,
 },
 contentContainer:{
     alignItems:'center',
     justifyContent:'center',
 },
 textBar:{
     height:30,
     width:200,
     fontsize:20,
     borderColor:'black',
     borderRadius:20,
     margin:10,
     borderWidth:2,
 },
  buttonText:{
     fontFamily:'futura',
     color:'white',
     fontSize:14,
 },
  boxText:{
    fontSize:20,
      fontWeight:'bold',
      textAlign:'center',
      alignItems:'center',
      margin:10,
      justifyContent:'center',
     borderRadius:20,
      backgroundColor:'teal',
     height:30,
     width:250,
  color:'white',
  flexDirection:'row',
 
 },
 box:{
 textAlign:'center',
 alignItems:'center',
 },
});
 
 

