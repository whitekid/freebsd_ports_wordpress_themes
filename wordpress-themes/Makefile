# New ports collection makefile for:	wordpress-themes
# Date created:		2010-02-18
# Whom:			whitekid@gmail.com
#
# $FreeBSD$
#

PORTNAME=	wordpress-themes
PORTVERSION=	20130320
CATEGORIES=	www
MASTER_SITES=	http://wordpress.org/extend/themes/download/
DIST_SUBDIR=	wordpress

MAINTAINER=	whitekid@gmail.com
COMMENT=	Wordpress themes

RUN_DEPENDS=	wordpress>=0:${PORTSDIR}/www/wordpress

OPTIONS_DEFINE=	VERMILLON \
		ATAHUALPA \
		PIANO_BLACK \
		JQ \
		CHOCO \
		CONSTRUCTOR \
		ARJUNA_X \
		SMOOTH \
		PIXEL \
		MOTION \
		LIGHTWORD \
		COMMENT_CENTRAL \
		MONOCHROME \
		MULTI_COLOR \
		MYSTIQUE \
		NOTEPAD_THEME \
		HOLISTIC_TEAHOUSE \
		WHITEHOUSE \
		ARCLITE \
		DARK_WOOD \
		ELEGANT_GRUNGE \
		EOS \
		HYBRID \
		INANIS_GLASS \
		INOVE \
		ORGANIC_THEME \
		SKINBU \
		SLIDINGDOOR \
		SUFFUSION \
		THEMATIC \
		P2 \
		CORDOBO_GREEN_PARK_2 \
		TITAN \
		ZBENCH \
		INTREPIDITY \
		EDEGREE \
		IDREAM \
		UNDER_INFLUENCE \
		RETROMANIA \
		THE_ERUDITE \
		MAGAZINE_BASIC \
		JOURNALIST \
		WP_ANDREAS01 \
		ADVENTURE_JOURNAL \
		TOOLBOX \
		EASEL \
		LIQUORICE \
		CORALINE \
		NEWS \
		TWENTY_TEN \
		TWENTY_ELEVEN \
		IFEATURE \
		PLATFORM \
		ANNOTUM_BASE

VERMILLON	= Enable Vermillon theme
ATAHUALPA	= Enable Atahualpa theme
PIANO_BLACK	= Enable Piano Black theme
JQ	= Enable jQ theme
CHOCO	= Enable Choco theme
CONSTRUCTOR	= Enable Constructor theme
ARJUNA_X	= Enable Arjuna X theme
SMOOTH	= Enable Smooth theme
PIXEL	= Enable Pixel theme
MOTION	= Enable Motion theme
LIGHTWORD	= Enable LightWord theme
COMMENT_CENTRAL	= Enable Comment Central theme
MONOCHROME	= Enable Monochrome theme
MULTI_COLOR	= Enable Multi-Color theme
MYSTIQUE	= Enable Mystique theme
NOTEPAD_THEME	= Enable Notepad theme
HOLISTIC_TEAHOUSE	= Enable Holistic Teahouse theme
WHITEHOUSE	= Enable WhiteHouse theme
ARCLITE	= Enable Arclite theme
DARK_WOOD	= Enable Dark Wood theme
ELEGANT_GRUNGE	= Enable Elegant Grunge theme
EOS	= Enable Eos theme
HYBRID	= Enable Hybrid theme
INANIS_GLASS	= Enable Inanis Glass theme
INOVE	= Enable iNove Glass theme
ORGANIC_THEME	= Enable Organic theme
SKINBU	= Enable Skinbu theme
SLIDINGDOOR	= Enable Sliding Door theme
SUFFUSION	= Enable Suffusion theme
THEMATIC	= Enable Thematic theme
P2	= Enable P2 theme
CORDOBO_GREEN_PARK_2	= Enable Cordobo Green Park 2 theme
TITAN	= Enable Titan theme
ZBENCH	= Enable zBench theme
INTREPIDITY	= Enable intrepidity theme
EDEGREE	= Enable eDegree theme
IDREAM	= Enable iDream theme
UNDER_INFLUENCE	= Enable Under the Influence theme
RETROMANIA	= Enable Retromania theme
THE_ERUDITE	= Enable The Erudite theme
MAGAZINE_BASIC	= Enable Magazine Basic theme
JOURNALIST	= Enable Journalist theme
WP_ANDREAS01	= Enable WP-Andreas01 theme
ADVENTURE_JOURNAL	= Enable Adventure Journal theme
TOOLBOX	= Enable Toolbox theme
EASEL	= Enable Easel theme
LIQUORICE	= Enable Liquorice theme
CORALINE	= Enable Coraline theme
NEWS	= Enable News theme
TWENTY_TEN	= Enable Twenty Ten theme
TWENTY_ELEVEN	= Enable Twenty Eleven theme
IFEATURE	= Enable iFeature theme
PLATFORM	= Enable Platform theme
ANNOTUM_BASE	= Enable Annotum Base theme

NO_BUILD?=	yes
WRKSRC?=	${WRKDIR}
PLIST=		${WRKDIR}/plist

WORDPRESS=	www/wordpress

.include <bsd.port.options.mk>

.if ${PORT_OPTIONS:MVERMILLON}
DISTFILES+=	vermillon.1.0.2.1.zip
.endif

.if ${PORT_OPTIONS:MATAHUALPA}
DISTFILES+=	atahualpa.3.7.12.zip
.endif

.if ${PORT_OPTIONS:MPIANO_BLACK}
DISTFILES+=	piano-black.2.2.zip
.endif

.if ${PORT_OPTIONS:MJQ}
DISTFILES+=	jq.3.4.zip
.endif

.if ${PORT_OPTIONS:MCHOCO}
DISTFILES+=	chocotheme.0.10.zip
.endif

.if ${PORT_OPTIONS:MCONSTRUCTOR}
DISTFILES+=	constructor.1.6.5.zip
.endif

.if ${PORT_OPTIONS:MARJUNA_X}
DISTFILES+=	arjuna-x.1.7.1.zip
.endif

.if ${PORT_OPTIONS:MSMOOTH}
DISTFILES+=	smooth.1.0.4.1.zip
.endif

.if ${PORT_OPTIONS:MPIXEL}
DISTFILES+=	pixel.2.0.2.zip
.endif

.if ${PORT_OPTIONS:MMOTION}
DISTFILES+=	motion.1.1.6.zip
.endif

.if ${PORT_OPTIONS:MLIGHTWORD}
DISTFILES+=	lightword.2.0.0.6.zip
.endif

.if ${PORT_OPTIONS:MCOMMENT_CENTRAL}
DISTFILES+=	comment-central.1.2.5.zip
.endif

.if ${PORT_OPTIONS:MMONOCHROME}
DISTFILES+=	monochrome.3.0.4.zip
.endif

.if ${PORT_OPTIONS:MMULTI_COLOR}
DISTFILES+=	multi-color.4.3.zip
.endif

.if ${PORT_OPTIONS:MMYSTIQUE}
DISTFILES+=	mystique.2.5.7.zip
.endif

.if ${PORT_OPTIONS:MNOTEPAD_THEME}
DISTFILES+=	notepad-theme.1.3.zip
.endif

.if ${PORT_OPTIONS:MHOLISTIC_TEAHOUSE}
DISTFILES+=	holistic-teahouse.1.3.zip
.endif

.if ${PORT_OPTIONS:MWHITEHOUSE}
DISTFILES+=	whitehouse.2.0.0.zip
.endif

.if ${PORT_OPTIONS:MARCLITE}
DISTFILES+=	arclite.2.02.zip
.endif

.if ${PORT_OPTIONS:MDARK_WOOD}
DISTFILES+=	dark-wood.1.9.zip
.endif

.if ${PORT_OPTIONS:MELEGANT_GRUNGE}
DISTFILES+=	elegant-grunge.1.0.3.zip
.endif

.if ${PORT_OPTIONS:MEOS}
DISTFILES+=	eos.1.3.11.zip
.endif

.if ${PORT_OPTIONS:MHYBRID}
DISTFILES+=	hybrid.1.2.zip
.endif

.if ${PORT_OPTIONS:MINANIS_GLASS}
DISTFILES+=	inanis-glass.1.3.6.zip
.endif

.if ${PORT_OPTIONS:MINOVE}
DISTFILES+=	inove.1.4.6.zip
.endif

.if ${PORT_OPTIONS:MORGANIC_THEME}
DISTFILES+=	organic-theme.1.9.4.zip
.endif

.if ${PORT_OPTIONS:MSKINBU}
DISTFILES+=	skinbu.1.5.0.zip
.endif

.if ${PORT_OPTIONS:MSLIDINGDOOR}
DISTFILES+=	sliding-door.3.0.9.zip
.endif

.if ${PORT_OPTIONS:MSUFFUSION}
DISTFILES+=	suffusion.4.4.7.zip
.endif

.if ${PORT_OPTIONS:MTHEMATIC}
DISTFILES+=	thematic.1.0.4.zip
.endif

.if ${PORT_OPTIONS:MP2}
DISTFILES+=	p2.1.5.1.zip
.endif

.if ${PORT_OPTIONS:MCORDOBO_GREEN_PARK_2}
DISTFILES+=	cordobo-green-park-2.0.9.502.zip
.endif

.if ${PORT_OPTIONS:MTITAN}
DISTFILES+=	titan.2.3.1.zip
.endif

.if ${PORT_OPTIONS:MZBENCH}
DISTFILES+=	zbench.1.3.7.zip
.endif

.if ${PORT_OPTIONS:MINTREPIDITY}
DISTFILES+=	intrepidity.1.5.1.zip
.endif

.if ${PORT_OPTIONS:MEDEGREE}
DISTFILES+=	edegree.1.1.zip
.endif

.if ${PORT_OPTIONS:MIDREAM}
DISTFILES+=	idream.1.0.2.zip
.endif

.if ${PORT_OPTIONS:MUNDER_INFLUENCE}
DISTFILES+=	under-the-influence.1.03.zip
.endif

.if ${PORT_OPTIONS:MRETROMANIA}
DISTFILES+=	retromania.1.5.zip
.endif

.if ${PORT_OPTIONS:MTHE_ERUDITE}
DISTFILES+=	the-erudite.3.2.zip
.endif

.if ${PORT_OPTIONS:MMAGAZINE_BASIC}
DISTFILES+=	magazine-basic.3.0.3.zip
.endif

.if ${PORT_OPTIONS:MJOURNALIST}
DISTFILES+=	journalist.1.9.zip
.endif

.if ${PORT_OPTIONS:MWP_ANDREAS01}
DISTFILES+=	wp-andreas01.2.0.zip
.endif

.if ${PORT_OPTIONS:MADVENTURE_JOURNAL}
DISTFILES+=	adventure-journal.1.7.2.zip
.endif

.if ${PORT_OPTIONS:MTOOLBOX}
DISTFILES+=	toolbox.1.4.zip
.endif

.if ${PORT_OPTIONS:MEASEL}
DISTFILES+=	easel.3.3.3.zip
.endif

.if ${PORT_OPTIONS:MCORALINE}
DISTFILES+=	coraline.1.4.1.zip
.endif

.if ${PORT_OPTIONS:MNEWS}
DISTFILES+=	news.0.3.zip
.endif

.if ${PORT_OPTIONS:MLIQUORICE}
DISTFILES+=	liquorice.2.3.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_TEN}
DISTFILES+=	twentyten.1.6.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_ELEVEN}
DISTFILES+=	twentyeleven.1.5.zip
.endif

.if ${PORT_OPTIONS:MIFEATURE}
DISTFILES+=	ifeature.5.1.30.zip
.endif

.if ${PORT_OPTIONS:MPLATFORM}
DISTFILES+=	platform.1.4.3.zip
.endif

.if ${PORT_OPTIONS:MANNOTUM_BASE}
DISTFILES+=	annotum-base.1.1.1.zip
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

.include <bsd.port.mk>
