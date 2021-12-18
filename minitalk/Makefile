# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: nlenoch <nlenoch@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/12/17 00:03:58 by nlenoch           #+#    #+#              #
#    Updated: 2021/12/17 22:54:41 by nlenoch          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME_SERVER = server
NAME_CLIENT = client
CC = gcc
CFLAGS = -Werror -Wextra -Wall
SRC_SERVER = server.c
SRC_CLIENT = client.c
RM = rm -f

all: $(NAME_SERVER) $(NAME_CLIENT)

$(NAME): all
	$(CC) -g $(CFLAGS) $(SRC_SERVER) -o $(NAME_SERVER)
	$(CC) -g $(CFLAGS) $(SRC_CLIENT) -o $(NAME_CLIENT)
	
clean:
		$(RM) $(NAME_CLIENT) $(NAME_SERVER)
		
fclean: clean

re: fclean all