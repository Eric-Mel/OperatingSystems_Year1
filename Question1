#!/bin/bash

while true
do
	clear
	echo "Welcome to Bash Commands"
	echo "-----------------------"
	echo "1. List files"
	echo "2. Show free disk space"
	echo "3. Show system path"
	echo "4. Display command history"
	echo "5. Backup files"
	echo "6. Exit"
	read -p "Enter your choice: " choice
	case $choice in
		1)
			ls -al
			read -p "Press enter to continue"
			;;
		2)
			df -h
			read -p "Press enter to continue"
			;;
		3)
			echo $PATH
			read -p "Press enter to continue"
			;;
		4)
			history
			read -p "Press enter to continue"
			;;
		5)
			read -p "Enter directory to backup: " dir
			mkdir BackupFolder
			cp -r $dir BackupFolder
			ls BackupFolder
			read -p "Press enter to continue"
			;;
		6)
			echo "Exiting..."
			exit
			;;
		*)
			echo "Invalid choice, please try again"
			read -p "Press enter to continue"
			;;
	esac
done
