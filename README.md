# TitleManager
A repository for Minecraft developers to use with the Spigot API to send Title and Actionbars to players. Uses NMS so you will need to update this everytime Minecraft updates. To do this, change these imports:

import net.minecraft.server.v1_11_R1.IChatBaseComponent;

import net.minecraft.server.v1_11_R1.Packet;

import net.minecraft.server.v1_11_R1.PacketPlayOutChat;

import net.minecraft.server.v1_11_R1.PacketPlayOutTitle;

import org.bukkit.craftbukkit.v1_11_R1.entity.CraftPlayer;
