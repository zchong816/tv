home.json
block_grid 				相同的 		图片下面有标题		电视剧热搜榜   
 ui_type: {
            unitary: true, 
            ratio: 0.6667, 
            name: "block_grid", 
            columns: 6
          }

block_grid_button 		可以不同的      只有图片          unitary: true 同步跟播大剧     |    unitary: false 7月这些剧最火   

 ui_type: {
            unitary: true|false, 
            ratio: 1.4667, 
            name: "block_grid_button", 
            columns: 3
          }






图片 item外观可以不一样  上层uitype=block_grid_button   unitary: true 同步跟播大剧     |    unitary: false 7月这些剧最火
{
          stat: {
            id: 179665, 
            tp: "album"
          }, 
          target: {
            url: "/tv/lean/v?id=179665", 
            entity: "v:album", 
            params: {
              android_intent: "intent:#Intent;action=android.intent.action.MITV_VIDEO_DETAILS;S.id=179665;end"
            }, 
            schema: "yktv"
          }, 
          ui_type: {
            style: "movie", 
            name: "display_item", 
            pos: {
              y: 0, 
              x: 4, 
              w: 2, 
              h: 1
            }
          }, 
          images: {
            poster: {
              url: "http://image.cdn.pandora.xiaomi.com/mitv/10007/1/5dbdccc6dbdd55c63409ef5e2116b09c.jpg", 
              md5: "5dbdccc6dbdd55c63409ef5e2116b09c"
            }, 
            fore: {
              url: "http://image.cdn.pandora.xiaomi.com/mitv/10007/2/7e2fca82b238f686c21f24348c92817a.png", 
              align: "mid", 
              md5: "7e2fca82b238f686c21f24348c92817a"
            }
          }, 
          ns: "video", 
          id: "V/179665", 
          ad: {
            enable: false
          }
        }


带标题 item外观一样 上层uitype=block_grid  unitary: true, 
{
              stat: {
                id: 207131, 
                tp: "album"
              }, 
              target: {
                schema: "yktv", 
                params: {
                  android_intent: "tenvideo2://?action=1&cover_id=xfxd9mej2luhfoz&pull_from=101503#Intent;action=com.tencent.qqlivetv.open;launchFlags=0x10000000;package=com.ktcp.tvvideo;end", 
                  android_component: "com.ktcp.tvvideo", 
                  android_version_code: 1240
                }, 
                entity: "v:album"
              }, 
              title: "芈月传", 
              ui_type: {
                style: "movie", 
                name: "display_item", 
                pos: {
                  y: 1, 
                  x: 5, 
                  w: 1, 
                  h: 1
                }
              }, 
              images: {
                poster: {
                  url: "http://image.box.xiaomi.com/mfsv2/download/s010/p01ia89x23Cy/S6sDi8mOg5nBPI.jpg", 
                  md5: "5e8d06fe2bff065d5fc2d5830a908649"
                }
              }, 
              ns: "video", 
              id: "V/207131", 
              ad: {
                enable: false
              }
            }



