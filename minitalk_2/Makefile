# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ogdurkan <ogdurkan@student.42kocaeli.co    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/12/27 15:17:31 by ogdurkan          #+#    #+#              #
#    Updated: 2022/12/27 15:17:32 by ogdurkan         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #


CC = gcc
CFLAGS = -Wall -Werror -Wextra
CLIENT = $(CC) $(CFLAGS) client.c -o client
SERVER = $(CC) $(CFLAGS) server.c -o server
NAME_CL = client
NAME_SV = server
all: $(NAME_CL) $(NAME_SV)
$(NAME_CL):
	$(CLIENT)
$(NAME_SV):
	$(SERVER)
clean:
	rm -rf client server
fclean: clean
re: clean all