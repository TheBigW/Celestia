noinst_LIBRARIES = libcelengine.a
noinst_HEADERS = $(wildcard *.h)

AM_CPPFLAGS = -I$(top_srcdir)/src \
	      -I$(top_srcdir)/thirdparty/Eigen \
	      -I$(top_srcdir)/thirdparty/curveplot/include \
	      -I$(top_srcdir)/thirdparty/glew/include

libcelengine_a_CXXFLAGS = $(LUA_CFLAGS) $(SPICE_CFLAGS) $(GLEW_CFLAGS)

AM_LDFLAGS = $(LUA_LDFLAGS) $(GLEW_LDFLAGS)

libcelengine_a_SOURCES = \
	asterism.cpp \
	astro.cpp \
	axisarrow.cpp \
	body.cpp \
	boundaries.cpp \
	catalogxref.cpp \
	cmdparser.cpp \
	command.cpp \
	console.cpp \
	constellation.cpp \
	dds.cpp \
	deepskyobj.cpp \
	dispmap.cpp \
	dsodb.cpp \
	dsoname.cpp \
	dsooctree.cpp \
	execution.cpp \
	fragmentprog.cpp \
	frame.cpp \
	frametree.cpp \
	galaxy.cpp \
	glcontext.cpp \
	globular.cpp \
	glshader.cpp \
	image.cpp \
	location.cpp \
	lodspheremesh.cpp \
	marker.cpp \
	meshmanager.cpp \
	modelgeometry.cpp \
	multitexture.cpp \
	nebula.cpp \
	observer.cpp \
	opencluster.cpp \
	overlay.cpp \
	parseobject.cpp \
	parser.cpp \
	planetgrid.cpp \
	regcombine.cpp \
	rendcontext.cpp \
	render.cpp \
	renderglsl.cpp \
	rotationmanager.cpp \
	selection.cpp \
	shadermanager.cpp \
	simulation.cpp \
	skygrid.cpp \
	solarsys.cpp \
	spheremesh.cpp \
	star.cpp \
	starbrowser.cpp \
	starcolors.cpp \
	stardb.cpp \
	starname.cpp \
	staroctree.cpp \
	stellarclass.cpp \
	texmanager.cpp \
	texture.cpp \
	timeline.cpp \
	timelinephase.cpp \
	tokenizer.cpp \
	trajmanager.cpp \
	univcoord.cpp \
	universe.cpp \
	vertexprog.cpp \
	virtualtex.cpp \
	visibleregion.cpp \
	../../thirdparty/glew/src/glew.c \
	../../thirdparty/curveplot/src/curveplot.cpp
