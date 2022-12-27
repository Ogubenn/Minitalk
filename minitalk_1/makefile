# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ogdurkan <ogdurkan@student.42kocaeli.co    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/12/11 14:33:37 by ogdurkan          #+#    #+#              #
#    Updated: 2022/12/24 18:09:00 by ogdurkan         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
LIBFT = Libft

all: $(NAME)
		gcc server.c $(NAME) -o server
		gcc client.c $(NAME) -o client
$(NAME): $(LIBFT)
		make -C $(LIBFT)
		cp Libft/libft.a .
clean:
		make clean -C $(LIBFT)
fclean: clean
		make fclean -C $(LIBFT)
		rm -rf $(NAME)
		rm -rf server client

.PHONY: clean