# linux-cpw-engine
Didactic chess engine for chessprogramming wiki. Version for GNU/Linux, forked from nescitus/cpw-engine.

Still no Makefile. For now build with

g++ -o cpw attacks.cpp board.cpp book.cpp chronos.cpp com.cpp console_ui.cpp CPW.cpp eval.cpp eval_init.cpp move.cpp 
movegen.cpp Quiescence.cpp recognizer.cpp search.cpp see.cpp stdafx.cpp transposition.cpp util.cpp

Juan Carlos
