Issues pour Github

calculateTotal()

ok pb - vuejs chrome extension install |ok refresh fonctionne

pb - <p class="center" v-if="!Object.key(cart).lengh">
pb - <button @click="remove"

not consireded as a function


digit 1 decimal total price 

pb - verif processus
1- ds le template | Button Event onclick <button @click="remove" (ne peut pas directement convoquer la func).
2- ds la custom balise bliding :remvove="removeItem" | proxy = "call function"
3- ds le componoent props (propriete partagé) | Liste les proxy | props: ["toggle", "cart", "inventory", "remove"],


pb 4- function
removeItem(name) {
delete this.cart[name];
},
