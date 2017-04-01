# TitleManager
A repository for Minecraft developers to use with the Spigot API to send Title and Actionbars to players. Uses NMS so you will need to update this everytime Minecraft updates. To do this, change these imports:

import net.minecraft.server.v1_11_R1.IChatBaseComponent;

import net.minecraft.server.v1_11_R1.Packet;

import net.minecraft.server.v1_11_R1.PacketPlayOutChat;

import net.minecraft.server.v1_11_R1.PacketPlayOutTitle;

import org.bukkit.craftbukkit.v1_11_R1.entity.CraftPlayer;

For example, if you wanted to update to Minecraft 1.12 you would change 'v1_11_R1' to 'v1_12_R1'.
For 1.13: 'v1_13_R1' 

Remember to change 'R1' to the corresponding Spigot version. There is a Spigot R2 so if you use that you change it to R2.
