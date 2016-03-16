# Created by: Choe, Cheng-Dae <whitekid@gmail.com>
# $FreeBSD$

PORTNAME=	wordpress-themes
PORTVERSION=	20160316
CATEGORIES=	www
MASTER_SITES=	https://downloads.wordpress.org/theme/
DIST_SUBDIR=	wordpress

MAINTAINER=	whitekid@gmail.com
COMMENT=	Wordpress themes

USES=		zip

RUN_DEPENDS=	wordpress>=0:${PORTSDIR}/www/wordpress

NO_BUILD=	yes
WRKSRC?=	${WRKDIR}
PLIST=		${WRKDIR}/pkg-plist

DISTFILES= \
	adventure-journal.1.7.2.zip \
	annotum-base.2.0.zip \
	arclite.2.02.zip \
	arjuna-x.1.7.1.zip \
	atahualpa.3.7.24.zip \
	chocotheme.0.10.zip \
	comment-central.1.2.5.zip \
	constructor.1.6.5.zip \
	coraline.1.5.2.zip \
	cordobo-green-park-2.0.9.502.zip \
	dark-wood.1.9.zip \
	edegree.1.1.zip \
	elegant-grunge.1.0.3.zip \
	eos.1.3.11.zip \
	holistic-teahouse.1.3.zip \
	hybrid.1.2.zip \
	idream.1.0.2.zip \
	ifeature.5.5.6.zip \
	inanis-glass.1.3.6.zip \
	inove.1.4.6.zip \
	intrepidity.1.5.1.zip \
	journalist.1.9.zip \
	jq.3.4.zip \
	lightword.2.0.0.6.zip \
	liquorice.2.3.zip \
	magazine-basic.3.0.7.zip \
	monochrome.3.0.4.zip \
	motion.1.1.6.zip \
	multi-color.4.3.zip \
	mystique.2.5.7.zip \
	news.0.3.zip \
	notepad-theme.1.3.zip \
	orbit.1.2.1.zip \
	organic-theme.1.9.4.zip \
	p2.1.5.8.zip \
	piano-black.2.2.zip \
	pixel.2.0.2.zip \
	platform.1.4.4.zip \
	responsiveboat.1.1.3.zip \
	retromania.1.5.zip \
	skinbu.1.5.0.zip \
	sliding-door.3.2.4.zip \
	smooth.1.0.4.1.zip \
	suffusion.4.4.9.zip \
	the-erudite.3.2.zip \
	thematic.1.0.4.zip \
	titan.2.3.1.zip \
	twentyeleven.2.3.zip \
	twentyten.2.1.zip \
	twentythirteen.1.7.zip \
	twentytwelve.1.9.zip \
	under-the-influence.1.03.zip \
	vermillon.1.0.2.1.zip \
	white.1.1.zip \
	whitehouse.2.0.0.zip \
	wp-andreas01.2.0.zip \
	zbench.1.4.2.zip

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
