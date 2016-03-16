# New ports collection makefile for:	wordpress-themes
# Date created:		2010-02-18
# Whom:			whitekid@gmail.com
#
# $FreeBSD$
#

PORTNAME=	wordpress-themes
PORTVERSION=	20160316
CATEGORIES=	www
MASTER_SITES=	https://downloads.wordpress.org/theme/
DIST_SUBDIR=	wordpress

MAINTAINER=	whitekid@gmail.com
COMMENT=	Wordpress themes

USES=		zip

RUN_DEPENDS=	wordpress>=0:${PORTSDIR}/www/wordpress

OPTIONS_DEFINE= \
		ADVENTURE_JOURNAL \
		ANNOTUM_BASE \
		ARCLITE \
		ARJUNA_X \
		ATAHUALPA \
		CHOCO \
		COMMENT_CENTRAL \
		CONSTRUCTOR \
		CORALINE \
		CORDOBO_GREEN_PARK_2 \
		DARK_WOOD \
		EDEGREE \
		ELEGANT_GRUNGE \
		EOS \
		HOLISTIC_TEAHOUSE \
		HYBRID \
		IDREAM \
		IFEATURE \
		INANIS_GLASS \
		INOVE \
		INTREPIDITY \
		JOURNALIST \
		JQ \
		LIGHTWORD \
		LIQUORICE \
		MAGAZINE_BASIC \
		MONOCHROME \
		MOTION \
		MULTI_COLOR \
		MYSTIQUE \
		NEWS \
		NOTEPAD \
		ORBIT \
		ORGANIC \
		P2 \
		PIANO_BLACK \
		PIXEL \
		PLATFORM \
		RETROMANIA \
		SKINBU \
		SLIDINGDOOR \
		SMOOTH \
		SUFFUSION \
		THEMATIC \
		THE_ERUDITE \
		TITAN \
		TWENTY_ELEVEN \
		TWENTY_TEN \
		TWENTY_THIRTEEN \
		TWENTY_TWELVE \
		UNDER_INFLUENCE \
		VERMILLON \
		WHITEHOUSE \
		WP_ANDREAS01 \
		ZBENCH

OPTIONS_DEFAULT=	${OPTIONS_DEFINE}

ADVENTURE_JOURNAL_DESC	= Enable Adventure Journal theme
ANNOTUM_BASE_DESC	= Enable Annotum Base theme
ARCLITE_DESC	= Enable Arclite theme
ARJUNA_X_DESC	= Enable Arjuna X theme
ATAHUALPA_DESC	= Enable Atahualpa theme
CHOCO_DESC	= Enable Choco theme
COMMENT_CENTRAL_DESC	= Enable Comment Central theme
CONSTRUCTOR_DESC	= Enable Constructor theme
CORALINE_DESC	= Enable Coraline theme
CORDOBO_GREEN_PARK_2_DESC	= Enable Cordobo Green Park 2 theme
DARK_WOOD_DESC	= Enable Dark Wood theme
EDEGREE_DESC	= Enable eDegree theme
ELEGANT_GRUNGE_DESC	= Enable Elegant Grunge theme
EOS_DESC	= Enable Eos theme
HOLISTIC_TEAHOUSE_DESC	= Enable Holistic Teahouse theme
HYBRID_DESC	= Enable Hybrid theme
IDREAM_DESC	= Enable iDream theme
IFEATURE_DESC	= Enable iFeature theme
INANIS_GLASS_DESC	= Enable Inanis Glass theme
INOVE_DESC	= Enable iNove Glass theme
INTREPIDITY_DESC	= Enable intrepidity theme
JOURNALIST_DESC	= Enable Journalist theme
JQ_DESC	= Enable jQ theme
LIGHTWORD_DESC	= Enable LightWord theme
LIQUORICE_DESC	= Enable Liquorice theme
MAGAZINE_BASIC_DESC	= Enable Magazine Basic theme
MONOCHROME_DESC	= Enable Monochrome theme
MOTION_DESC	= Enable Motion theme
MULTI_COLOR_DESC	= Enable Multi-Color theme
MYSTIQUE_DESC	= Enable Mystique theme
NEWS_DESC	= Enable News theme
NOTEPAD_DESC	= Enable Notepad theme
ORBIT_DESC	= Enable Orbit theme
ORGANIC_DESC	= Enable Organic theme
P2_DESC		= Enable P2 theme
PIANO_BLACK_DESC	= Enable Piano Black theme
PIXEL_DESC	= Enable Pixel theme
PLATFORM_DESC	= Enable Platform theme
RETROMANIA_DESC	= Enable Retromania theme
SKINBU_DESC	= Enable Skinbu theme
SLIDINGDOOR_DESC	= Enable Sliding Door theme
SMOOTH_DESC	= Enable Smooth theme
SUFFUSION_DESC	= Enable Suffusion theme
THEMATIC_DESC	= Enable Thematic theme
THE_ERUDITE_DESC	= Enable The Erudite theme
TITAN_DESC	= Enable Titan theme
TWENTY_ELEVEN_DESC	= Enable Twenty Eleven theme
TWENTY_TEN_DESC	= Enable Twenty Ten theme
TWENTY_THIRTEEN_DESC	= Enable Twenty Thirteen theme
TWENTY_TWELVE_DESC	= Enable Twenty Twelve theme
UNDER_INFLUENCE_DESC	= Enable Under the Influence theme
VERMILLON_DESC	= Enable Vermillon theme
WHITEHOUSE_DESC	= Enable WhiteHouse theme
WP_ANDREAS01_DESC	= Enable WP-Andreas01 theme
ZBENCH_DESC	= Enable zBench theme

NO_BUILD=	yes
WRKSRC?=	${WRKDIR}
PLIST=		${WRKDIR}/pkg-plist

.include <bsd.port.options.mk>

.if ${PORT_OPTIONS:MADVENTURE_JOURNAL}
DISTFILES+=	adventure-journal.1.7.2.zip
.endif

.if ${PORT_OPTIONS:MANNOTUM_BASE}
DISTFILES+=	annotum-base.2.0.zip
.endif

.if ${PORT_OPTIONS:MARCLITE}
DISTFILES+=	arclite.2.02.zip
.endif

.if ${PORT_OPTIONS:MARJUNA_X}
DISTFILES+=	arjuna-x.1.7.1.zip
.endif

.if ${PORT_OPTIONS:MATAHUALPA}
DISTFILES+=	atahualpa.3.7.24.zip
.endif

.if ${PORT_OPTIONS:MCHOCO}
DISTFILES+=	chocotheme.0.10.zip
.endif

.if ${PORT_OPTIONS:MCOMMENT_CENTRAL}
DISTFILES+=	comment-central.1.2.5.zip
.endif

.if ${PORT_OPTIONS:MCONSTRUCTOR}
DISTFILES+=	constructor.1.6.5.zip
.endif

.if ${PORT_OPTIONS:MCORALINE}
DISTFILES+=	coraline.1.5.2.zip
.endif

.if ${PORT_OPTIONS:MCORDOBO_GREEN_PARK_2}
DISTFILES+=	cordobo-green-park-2.0.9.502.zip
.endif

.if ${PORT_OPTIONS:MDARK_WOOD}
DISTFILES+=	dark-wood.1.9.zip
.endif

.if ${PORT_OPTIONS:MEDEGREE}
DISTFILES+=	edegree.1.1.zip
.endif

.if ${PORT_OPTIONS:MELEGANT_GRUNGE}
DISTFILES+=	elegant-grunge.1.0.3.zip
.endif

.if ${PORT_OPTIONS:MEOS}
DISTFILES+=	eos.1.3.11.zip
.endif

.if ${PORT_OPTIONS:MHOLISTIC_TEAHOUSE}
DISTFILES+=	holistic-teahouse.1.3.zip
.endif

.if ${PORT_OPTIONS:MHYBRID}
DISTFILES+=	hybrid.1.2.zip
.endif

.if ${PORT_OPTIONS:MIDREAM}
DISTFILES+=	idream.1.0.2.zip
.endif

.if ${PORT_OPTIONS:MIFEATURE}
DISTFILES+=	ifeature.5.5.6.zip
.endif

.if ${PORT_OPTIONS:MINANIS_GLASS}
DISTFILES+=	inanis-glass.1.3.6.zip
.endif

.if ${PORT_OPTIONS:MINOVE}
DISTFILES+=	inove.1.4.6.zip
.endif

.if ${PORT_OPTIONS:MINTREPIDITY}
DISTFILES+=	intrepidity.1.5.1.zip
.endif

.if ${PORT_OPTIONS:MJOURNALIST}
DISTFILES+=	journalist.1.9.zip
.endif

.if ${PORT_OPTIONS:MJQ}
DISTFILES+=	jq.3.4.zip
.endif

.if ${PORT_OPTIONS:MLIGHTWORD}
DISTFILES+=	lightword.2.0.0.6.zip
.endif

.if ${PORT_OPTIONS:MLIQUORICE}
DISTFILES+=	liquorice.2.3.zip
.endif

.if ${PORT_OPTIONS:MMAGAZINE_BASIC}
DISTFILES+=	magazine-basic.3.0.7.zip
.endif

.if ${PORT_OPTIONS:MMONOCHROME}
DISTFILES+=	monochrome.3.0.4.zip
.endif

.if ${PORT_OPTIONS:MMOTION}
DISTFILES+=	motion.1.1.6.zip
.endif

.if ${PORT_OPTIONS:MMULTI_COLOR}
DISTFILES+=	multi-color.4.3.zip
.endif

.if ${PORT_OPTIONS:MMYSTIQUE}
DISTFILES+=	mystique.2.5.7.zip
.endif

.if ${PORT_OPTIONS:MNEWS}
DISTFILES+=	news.0.3.zip
.endif

.if ${PORT_OPTIONS:MNOTEPAD}
DISTFILES+=	notepad-theme.1.3.zip
.endif

.if ${PORT_OPTIONS:MORBIT}
DISTFILES+=	orbit.1.2.1.zip
.endif

.if ${PORT_OPTIONS:MORGANIC}
DISTFILES+=	organic-theme.1.9.4.zip
.endif

.if ${PORT_OPTIONS:MP2}
DISTFILES+=	p2.1.5.8.zip
.endif

.if ${PORT_OPTIONS:MPIANO_BLACK}
DISTFILES+=	piano-black.2.2.zip
.endif

.if ${PORT_OPTIONS:MPIXEL}
DISTFILES+=	pixel.2.0.2.zip
.endif

.if ${PORT_OPTIONS:MPLATFORM}
DISTFILES+=	platform.1.4.4.zip
.endif

.if ${PORT_OPTIONS:MRETROMANIA}
DISTFILES+=	retromania.1.5.zip
.endif

.if ${PORT_OPTIONS:MSKINBU}
DISTFILES+=	skinbu.1.5.0.zip
.endif

.if ${PORT_OPTIONS:MSLIDINGDOOR}
DISTFILES+=	sliding-door.3.2.4.zip
.endif

.if ${PORT_OPTIONS:MSMOOTH}
DISTFILES+=	smooth.1.0.4.1.zip
.endif

.if ${PORT_OPTIONS:MSUFFUSION}
DISTFILES+=	suffusion.4.4.9.zip
.endif

.if ${PORT_OPTIONS:MTHEMATIC}
DISTFILES+=	thematic.1.0.4.zip
.endif

.if ${PORT_OPTIONS:MTHE_ERUDITE}
DISTFILES+=	the-erudite.3.2.zip
.endif

.if ${PORT_OPTIONS:MTITAN}
DISTFILES+=	titan.2.3.1.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_ELEVEN}
DISTFILES+=	twentyeleven.2.3.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_TEN}
DISTFILES+=	twentyten.2.1.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_THIRTEEN}
DISTFILES+=	twentythirteen.1.7.zip
.endif

.if ${PORT_OPTIONS:MTWENTY_TWELVE}
DISTFILES+=	twentytwelve.1.9.zip
.endif

.if ${PORT_OPTIONS:MUNDER_INFLUENCE}
DISTFILES+=	under-the-influence.1.03.zip
.endif

.if ${PORT_OPTIONS:MVERMILLON}
DISTFILES+=	vermillon.1.0.2.1.zip
.endif

.if ${PORT_OPTIONS:MWHITEHOUSE}
DISTFILES+=	whitehouse.2.0.0.zip
.endif

.if ${PORT_OPTIONS:MWP_ANDREAS01}
DISTFILES+=	wp-andreas01.2.0.zip
.endif

.if ${PORT_OPTIONS:MZBENCH}
DISTFILES+=	zbench.1.4.2.zip
.endif

THEME_DIR=	${PREFIX}/www/wordpress/wp-content/themes
THEME_DIRS=	${DISTFILES:C|\.[\.0-9]+\.zip||}

post-patch:
	@${RM} -f ${PLIST}

.for f in ${THEME_DIRS}
	@cd ${WRKSRC} && \
	${FIND} -s ${f} -type f | ${SED} -e 's|^|${THEME_DIR}/|' >> ${PLIST} && \
	${FIND} -d ${f} -type d | ${SED} -e 's|^|@dirrm ${THEME_DIR}/|' >> ${PLIST}
.endfor

do-install:
.for f in ${THEME_DIRS}
	@cd ${WRKSRC} && \
	${FIND} ${f} -type d -exec ${MKDIR} ${STAGEDIR}${THEME_DIR}/{} \; && \
	${FIND} ${f} -type f -exec ${CP} {} ${STAGEDIR}${THEME_DIR}/{} \;
.endfor

.include <bsd.port.mk>
