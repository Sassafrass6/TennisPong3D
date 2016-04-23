noinst_HEADERS = Application.h MultiPlatformHelper.h OISManager.h StadiumFlashes.h SceneHelper.h CoreConfig.h SoundManager.h ScoreManager.h GameManager.h GameObject.h Simulator.h BulletContactCallback.h CollisionContext.h OgreMotionState.h Ball.h Paddle.h Wall.h NetManager.h GameState.h

bin_PROGRAMS = TennisPong3D
TennisPong3D_CPPFLAGS = -I$(top_srcdir) -std=c++11 -Wunused-variable
TennisPong3D_SOURCES = Application.cpp main.cpp OISManager.cpp StadiumFlashes.cpp SoundManager.cpp ScoreManager.cpp GameManager.cpp Simulator.cpp GameObject.cpp OgreMotionState.cpp CollisionContext.cpp BulletContactCallback.cpp Ball.cpp Paddle.cpp Wall.cpp NetManager.cpp
TennisPong3D_CXXFLAGS = $(OGRE_CFLAGS) $(OIS_CFLAGS) $(bullet_CFLAGS) $(CEGUI_CFLAGS)
TennisPong3D_LDADD = $(OGRE_LIBS) $(OIS_LIBS) $(bullet_LIBS) $(CEGUI_LIBS) $(CEGUI_OGRE_LIBS)
TennisPong3D_LDFLAGS = -lOgreOverlay -lboost_system -lSDL -lSDL_mixer -lSDL_net

EXTRA_DIST = buildit makeit
AUTOMAKE_OPTIONS = foreign
