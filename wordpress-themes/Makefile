# New ports collection makefile for:	wordpress-themes
# Date created:		2010-02-18
# Whom:			whitekid@gmail.com
#
# $FreeBSD$
#

PORTNAME=	wordpress-themes
PORTVERSION=	2011084
CATEGORIES=	www
MASTER_SITES=	http://wordpress.org/extend/themes/download/
DIST_SUBDIR=	wordpress

MAINTAINER=	whitekid@gmail.com
COMMENT=	Wordpress themes

RUN_DEPENDS=	wordpress>=0:${PORTSDIR}/www/wordpress

OPTIONS=	VERMILLON "Enable Vermillon theme" on \
		ATAHUALPA "Enable Atahualpa theme" on \
		PIANO_BLACK "Enable Piano Black theme" on \
		JQ "Enable jQ theme" on \
		CHOCO "Enable Choco theme" on \
		CONSTRUCTOR "Enable Constructor theme" on \
		ARJUNA_X "Enable Arjuna X theme" on \
		SMOOTH "Enable Smooth theme" on \
		PIXEL "Enable Pixel theme" on \
		MOTION "Enable Motion theme" on \
		LIGHTWORD "Enable LightWord theme" on \
		COMMENT_CENTRAL "Enable Comment Central theme" on \
		MONOCHROME "Enable Monochrome theme" on \
		MULTI_COLOR "Enable Multi-Color theme" on \
		MYSTIQUE "Enable Mystique theme" on \
		NOTEPAD_THEME "Enable Notepad theme" on \
		HOLISTIC_TEAHOUSE "Enable Holistic Teahouse theme" on \
		WHITEHOUSE "Enable WhiteHouse theme" on \
		ARCLITE "Enable Arclite theme" on \
		DARK_WOOD "Enable Dark Wood theme" on \
		ELEGANT_GRUNGE "Enable Elegant Grunge theme" on \
		EOS "Enable Eos theme" on \
		HYBRID "Enable Hybrid theme" on \
		INANIS_GLASS "Enable Inanis Glass theme" on \
		INOVE "Enable iNove Glass theme" on \
		ORGANIC_THEME "Enable Organic theme" on \
		SKINBU "Enable Skinbu theme" on \
		SLIDINGDOOR "Enable Sliding Door theme" on \
		SUFFUSION "Enable Suffusion theme" on \
		THEMATIC "Enable Thematic theme" on \
		P2 "Enable P2 theme" on \
		CORDOBO_GREEN_PARK_2 "Enable Cordobo Green Park 2 theme" on \
		TITAN "Enable Titan theme" on \
		ZBENCH "Enable zBench theme" on \
		INTREPIDITY "Enable intrepidity theme" on \
		EDEGREE "Enable eDegree theme" on \
		IDREAM "Enable iDream theme" on \
		UNDER_INFLUENCE "Enable Under the Influence theme" on \
		RETROMANIA "Enable Retromania theme" on \
		THE_ERUDITE "Enable The Erudite theme" on \
		MAGAZINE_BASIC "Enable Magazine Basic theme" on \
		JOURNALIST "Enable Journalist theme" on \
		WP_ANDREAS01 "Enable WP-Andreas01 theme" on \
		ADVENTURE_JOURNAL "Enable Adventure Journal theme" on \
		TOOLBOX "Enable Toolbox theme" on \
		EASEL "Enable Easel theme" on \
		LIQUORICE "Enable Liquorice theme" on \
		CORALINE "Enable Coraline theme" on \
		NEWS "Enable News theme" on \
		TWENTY_TEN "Enable Twenty Ten theme" on \
		IFEATURE "Enable iFeature theme" on \
		PLATFORM "Enable Platform theme" on

NO_BUILD?=	yes
WRKSRC?=	${WRKDIR}
PLIST=		${WRKDIR}/plist

WORDPRESS=	www/wordpress

.include <bsd.port.pre.mk>

.if defined(WITH_VERMILLON)
DISTFILES+=	vermillon.1.0.2.1.zip
.endif

.if defined(WITH_ATAHUALPA)
DISTFILES+=	atahualpa.3.6.7.zip
.endif

.if defined(WITH_PIANO_BLACK)
DISTFILES+=	piano-black.2.2.zip
.endif

.if defined(WITH_JQ)
DISTFILES+=	jq.3.4.zip
.endif

.if defined(WITH_CHOCO)
DISTFILES+=	chocotheme.0.10.zip
.endif

.if defined(WITH_CONSTRUCTOR)
DISTFILES+=	constructor.1.6.4.zip
.endif

.if defined(WITH_ARJUNA_X)
DISTFILES+=	arjuna-x.1.7.1.zip
.endif

.if defined(WITH_SMOOTH)
DISTFILES+=	smooth.1.0.4.1.zip
.endif

.if defined(WITH_PIXEL)
DISTFILES+=	pixel.2.0.2.zip
.endif

.if defined(WITH_MOTION)
DISTFILES+=	motion.1.1.6.zip
.endif

.if defined(WITH_LIGHTWORD)
DISTFILES+=	lightword.2.0.0.6.zip
.endif

.if defined(WITH_COMMENT_CENTRAL)
DISTFILES+=	comment-central.1.2.5.zip
.endif

.if defined(WITH_MONOCHROME)
DISTFILES+=	monochrome.3.0.4.zip
.endif

.if defined(WITH_MULTI_COLOR)
DISTFILES+=	multi-color.1.7.zip
.endif

.if defined(WITH_MYSTIQUE)
DISTFILES+=	mystique.2.5.1.zip
.endif

.if defined(WITH_NOTEPAD_THEME)
DISTFILES+=	notepad-theme.1.3.zip
.endif

.if defined(WITH_HOLISTIC_TEAHOUSE)
DISTFILES+=	holistic-teahouse.1.3.zip
.endif

.if defined(WITH_WHITEHOUSE)
DISTFILES+=	whitehouse.2.0.0.zip
.endif

.if defined(WITH_ARCLITE)
DISTFILES+=	arclite.2.02.zip
.endif

.if defined(WITH_DARK_WOOD)
DISTFILES+=	dark-wood.1.9.zip
.endif

.if defined(WITH_ELEGANT_GRUNGE)
DISTFILES+=	elegant-grunge.1.0.3.zip
.endif

.if defined(WITH_EOS)
DISTFILES+=	eos.1.3.11.zip
.endif

.if defined(WITH_HYBRID)
DISTFILES+=	hybrid.0.9.zip
.endif

.if defined(WITH_INANIS_GLASS)
DISTFILES+=	inanis-glass.1.3.6.zip
.endif

.if defined(WITH_INOVE)
DISTFILES+=	inove.1.4.6.zip
.endif

.if defined(WITH_ORGANIC_THEME)
DISTFILES+=	organic-theme.1.9.4.zip
.endif

.if defined(WITH_SKINBU)
DISTFILES+=	skinbu.1.5.0.zip
.endif

.if defined(WITH_SLIDINGDOOR)
DISTFILES+=	sliding-door.2.6.1.zip
.endif

.if defined(WITH_SUFFUSION)
DISTFILES+=	suffusion.3.8.2.zip
.endif

.if defined(WITH_THEMATIC)
DISTFILES+=	thematic.0.9.7.7.zip
.endif

.if defined(WITH_P2)
DISTFILES+=	p2.1.3.2.zip
.endif

.if defined(WITH_CORDOBO_GREEN_PARK_2)
DISTFILES+=	cordobo-green-park-2.0.9.502.zip
.endif

.if defined(WITH_TITAN)
DISTFILES+=	titan.1.25.zip
.endif

.if defined(WITH_ZBENCH)
DISTFILES+=	zbench.1.2.7.zip
.endif

.if defined(WITH_INTREPIDITY)
DISTFILES+=	intrepidity.1.5.1.zip
.endif

.if defined(WITH_EDEGREE)
DISTFILES+=	edegree.1.1.zip
.endif

.if defined(WITH_IDREAM)
DISTFILES+=	idream.1.0.2.zip
.endif

.if defined(WITH_UNDER_INFLUENCE)
DISTFILES+=	under-the-influence.1.03.zip
.endif

.if defined(WITH_RETROMANIA)
DISTFILES+=	retromania.1.5.zip
.endif

.if defined(WITH_THE_ERUDITE)
DISTFILES+=	the-erudite.2.7.8.zip
.endif

.if defined(WITH_MAGAZINE_BASIC)
DISTFILES+=	magazine-basic.2.7.3.zip
.endif

.if defined(WITH_JOURNALIST)
DISTFILES+=	journalist.1.9.zip
.endif

.if defined(WITH_WP_ANDREAS01)
DISTFILES+=	wp-andreas01.2.0.zip
.endif

.if defined(WITH_ADVENTURE_JOURNAL)
DISTFILES+=	adventure-journal.1.7.1.zip
.endif

.if defined(WITH_TOOLBOX)
DISTFILES+=	toolbox.1.2.zip
.endif

.if defined(WITH_EASEL)
DISTFILES+=	easel.2.0.7.zip
.endif

.if defined(WITH_CORALINE)
DISTFILES+=	coraline.1.0.2.zip
.endif

.if defined(WITH_NEWS)
DISTFILES+=	news.0.1.zip
.endif

.if defined(WITH_LIQUORICE)
DISTFILES+=	liquorice.2.0.0.zip
.endif

.if defined(WITH_TWENTY_TEN)
DISTFILES+=	twentyten.1.1.zip
.endif

.if defined(WITH_IFEATURE)
DISTFILES+=	ifeature.2.0.3.zip
.endif

.if defined(WITH_PLATFORM)
DISTFILES+=	platform.1.3.2.zip
.endif

WORDPRESS_THEME?=	${WORDPRESS}/wp-content/themes
THEME_DIRS=	${DISTFILES:C|\.[\.0-9]+\.zip||}

pre-install:
	@${RM} -rf ${PLIST}
	@${TOUCH} ${PLIST}

.for f in ${THEME_DIRS}
	@cd ${WRKSRC} && \
	${FIND} -s ${f} -type f | ${SED} -e 's|^|${WORDPRESS_THEME}/|' >> ${PLIST} && \
	${FIND} -d ${f} -type d | ${SED} -e 's|^|@dirrm ${WORDPRESS_THEME}/|' >> ${PLIST}
.endfor

do-install:
.for f in ${THEME_DIRS}
	@cd ${WRKSRC} && \
	${FIND} ${f} -type d -exec ${MKDIR} ${PREFIX}/${WORDPRESS_THEME}/{} \; && \
	${FIND} ${f} -type f -exec ${CP} {} ${PREFIX}/${WORDPRESS_THEME}/{} \;
.endfor

.include <bsd.port.post.mk>
