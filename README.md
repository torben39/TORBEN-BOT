const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`BOT SUNUCULARA GİRİŞ YAPTI ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'sa') {
    msg.reply('ALEYKÜM SELAM HOŞGELDİN');
  }
});

client.login('NDg2NjMzODkyMDc0MjI1Njc0.Dv1hrA.O-BSLhyJY2v2vXCVtEI-g8r8PKs');
