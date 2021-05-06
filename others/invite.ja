const { MessageEmbed } = require("discord.js");

module.exports = {
  name: "invite",
  aliases: ["inv"],
  description: "Invite the bot to your server.",
  execute(message) {

    let inviteEmbed = new MessageEmbed()
      .setTitle("Add us to your server!")
      .setDescription("Thank you! Consider adding it to your server!")
      .setColor("#F0EAD6")
      .setAuthor('Haha yes')
      .setThumbnail(message.guild.iconURL())
      .addField(`Use the following link to add The bot to your discord server`, 'https://discord.com/api/oauth2/authorize?client_id839524199617790003=&permissions=49572160&scope=bot', true)

    inviteEmbed.setTimestamp();

    return message.channel.send(inviteEmbed).catch(console.error);
  }
};
