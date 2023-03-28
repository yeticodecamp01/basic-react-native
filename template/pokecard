import React from 'react';
import { View, Text, Image, StyleSheet } from 'react-native';
import Icon from 'react-native-vector-icons/FontAwesome';

const PokemonCard = ({ name, image, type }) => {
  return (
    <View style={styles.card}>
      <Image  source={require('./assets/char.png')} style={styles.image} />
      <View style={styles.details}>
        <Text style={styles.name}> <Icon name="info" size={30} color="#900" /> Name :Charmander </Text>
        <Text style={styles.type}> <Icon name="question" size={30} color="#900" /> Type : Fire </Text>
        <View style={styles.line} />
        <Text style={styles.details}>It has a preference for hot things. {'\n'} When it rains, steam is said to spout from the tip of its tail.</Text>
      </View>
     

    </View>
  );
};

const styles = StyleSheet.create({
  card: {
    flex: 1,
    backgroundColor: '#fff',
    borderRadius: 20,
    shadowColor: '#000',
    shadowOffset: {
      width: 0,
      height: 2,
    },
    shadowOpacity: 0.25,
    shadowRadius: 3.84,
    elevation: 20,
    margin: 10,
  },
  image: {
    width: 150,
    height: 150,
    resizeMode: 'contain',
    alignSelf: 'center',
    marginVertical: 10,
    marginTop:100
  },
  details: {
    padding: 10,
  },
  name: {
    fontSize: 20,
    fontWeight: 'bold',
    textAlign: 'center',
    marginBottom: 5,
    textAlign: 'left',
  },
  type: {
    fontSize: 16,
    textAlign: 'center',
    fontWeight: 'bold',
    textAlign: 'left',
    backgroundColor: '#f09124',
    padding: 10,
  },
  line: {
    borderBottomWidth: 5,
    borderBottomColor: 'gray',
    marginVertical: 10,
  },
});

export default PokemonCard;
