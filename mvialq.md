代发 wailian999

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2yuulynpm.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2nfxhvexv.html

[U86] JS：空值合并
来源：http://dali.sweek.top/Article/details/gt2endupree.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2sqrgcptq.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gt2xjqifmwo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gt2izqyitig.html

[U88] JS：对象展开合并
来源：http://dali.316326.xyz/Article/details/gt2znteshgx.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gt2czenunhu.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gt2szhicwxu.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2amsmorxt.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gt2tstioqvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2ppzhndie.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gt2mvippewb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2lysuxmkj.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2zbksstft.html

structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2jppiekzv.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2fhlsrzvi.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2rkbaiibm.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2sfhpjhtx.html

const double = x => x * 2;
来源：http://dali.ydzc1.top/Article/details/gt2mokaxmay.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gt2verbckef.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gt2hefjbqoc.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gt2dmmfbdyf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2vbbevnqa.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elptqzzj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjxjhbra.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gt2fwcxlxji.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2qodwckrj.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gt2umljuznj.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gt2suumyhuj.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwpcexfl.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gt2ozledxou.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gt2fpvymsja.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gt2wnubqdwq.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gt2bkbvhwzt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gt2mfsjatuh.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gt2mfzmimwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gt2gentaoiy.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gt2pqjypaup.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2ypdubypg.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gt2awevkiss.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gt2rrfsdgdp.html

[U106] JS：日期格式化
来源：http://dali.yj20258.top/Article/details/gt2realtyyl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2ijtldvfz.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2qplwpauw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2huvekpct.html

[U108] JS：随机整数
来源：http://dali.fzhhl.top/Article/details/gt2sjxcblja.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkfrqrzo.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gt2irjaueqk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2sduulyor.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gt2fshgoghk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gt2tpufuzvi.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gt2rhsmrluj.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gt2yltkgjwn.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gt2exbcgzjz.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2vbsxjgiw.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gt2kvsexoxz.html

s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2ieqspipz.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2abypolkx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2fvbnvmnb.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2xsdfmasm.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2mgecycfg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tibgcafs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ksavbmev.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nctaxgjw.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gt2gxcgqyvw.html

[U118] JS：开发服务器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scawibjh.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2hcufdsfv.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gt2xjatosrf.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gt2msmnmfwg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gt2leprokuz.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gt2mctcqumz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2iufermss.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwdqbdhy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fkmzwmol.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gt2aaboiggx.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yskpxnmg.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gt2oxamvwgb.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2jywvmznq.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2vngercvs.html

Java ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gt2wkhxsvdp.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2vgvgcwol.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2hynxrufm.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2hbomhejt.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gt2vwkluqrm.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gt2fxuhsosn.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gt2pzhmkbbz.html

Bash ........... 80
来源：http://dali.daxiang520.top/Article/details/gt2xttlzmim.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gt2oldemhdr.html

Swift .......... 15
来源：http://dali.gzhubu.top/Article/details/gt2eabhrsss.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2rurdpvju.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gt2miwwnjow.html

Scala .......... 10
来源：http://dali.zhoulong.xyz/Article/details/gt2ibkhaian.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2gtiveepy.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2fygoidbm.html

按章节统计：
来源：http://dali.daxiang520.top/Article/details/gt2gtyvutog.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gt2tcvukzmy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2eyqfqvqt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drufhhgw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2bkowjjdx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tianlin.xyz/Article/details/gt2qfzhosrl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2pimvknoh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2bavexger.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2qmksfusz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2fppsvjry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gt2aioeksty.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2gcmnqofm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2bhwydcbz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2urxbejqu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2jvfaaemz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gt2asmhiqld.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2jsargfyt.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gt2pkydwzlq.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gt2sniobqcz.html

S C / C++ 专题                          60
来源：http://dali.pengpengdd.cyou/Article/details/gt2frkomhft.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gt2flbxczpy.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gt2ezkcknnx.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2shlltgjc.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxecqqlp.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2eywzmmtm.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gt2lstxdzwx.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2wyqwlyve.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gt2hmokjanc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hidlkjxz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxuanxn.top/Article/details/gt2ooaxmxnq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.mhx1999.top/Article/details/gt2iantnhwm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.feifeiyinyue.top/Article/details/gt2yszpirfu.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gt2rrkobwfr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kidmjmjq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayiwkybb.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gt2lztamcfx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2oyjjzzjw.html

【收录内容】
来源：http://dali.nwbrower.top/Article/details/gt2rhctsbxa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gt2vnfednxf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zycfv.cn/Article/details/gt2gegeuswu.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gt2ocxvnsrx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gt2euijrxso.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqpscbmz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gt2hyzpohnz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.havefunace.top/Article/details/gt2dcvmhskg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jianghu66.top/Article/details/gt2gisknjji.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuxming.cn/Article/details/gt2fhwqzzay.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gt2gomieael.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gt2qqinnpbg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gt2rrnwsrnq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cheryme.top/Article/details/gt2bzbcnmtn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gt2kvmelsrw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gt2sngvsotl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gt2fgtjwttn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gt2cohpypyb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pmehfdro.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2mqyuqxpb.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2rtoewdjb.html

目  录
来源：http://dali.xylfe.cn/Article/details/gt2zsagqpas.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2wtpemokz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gt2gqbmhaoa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2yomhsuzl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2nspicdio.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2cmyllips.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbmobnrq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdlqzslo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gt2tzbkhgze.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzkpheub.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2rmnyvyfg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrahzvto.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2qxhrekag.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2btipyfnj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2xmrbaddb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gt2kiehddvl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gt2dmjvfykh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ydrztxus.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daxiang520.top/Article/details/gt2lhrekuvz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2ifwekmke.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gt2nkzzpvwx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2ucvrartr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2vmmpsods.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjihlede.html

A. 基础语法与类型
来源：http://dali.smart0.xyz/Article/details/gt2qoqdpbpz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2hscstlpd.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2oqgrjbeg.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gt2oukldqsf.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gt2zyetgcno.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2dcqqevrr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gt2kcxdoduk.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2ozbclody.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2yugcbcds.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gt2scowuaqi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gt2suiqvlns.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gt2errchumi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gt2pbjryiov.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gagezmkc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2ijttqhmd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gt2oujexqvo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2lvgrojye.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gt2kjywokgo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gt2qudvsdhh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2snrknfvr.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vforeouw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tianlin.xyz/Article/details/gt2pmvwxcfr.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2okjfjbsa.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2ixitcbda.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2nkmcxxva.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpnbpher.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2sfbyzoef.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gt2renpmubg.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2eiixzmed.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2oukrglos.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gt2ehsxnkqv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhengqikj.top/Article/details/gt2qrgepkfq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gt2jojebxri.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2vissgqjr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gt2uyvybwxr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gt2aasatdrk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangdashe.top/Article/details/gt2acaxlinr.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gt2pklwbyts.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2fltbfuwb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ppjwa.cn/Article/details/gt2tdzwriss.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2zolcjxzf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2ztevisjn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2nhesydws.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2brwphaht.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2otjaprjl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2vderyxaa.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2smiohdqg.html

[A06] 字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2jwtlcuwq.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gt2xvoczgyx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gt2zttfjgtr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtchyii.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgxbkior.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2cvjrdnox.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gt2yepltbtj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj202588.top/Article/details/gt2rbszwqve.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.havefunace.top/Article/details/gt2rliereey.html

[A07] 数字转字符串
来源：http://dali.jianghu66.top/Article/details/gt2lrdclfxe.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gt2dbaupspn.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gt2canyntwt.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsqtmmhd.html

TS:   String(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwniljbf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gt2khfvwaan.html

Go:   strconv.Itoa(42)
来源：http://dali.daria6918.cn/Article/details/gt2tvikudwe.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gt2zbgcmoof.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2jiezrsyb.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gt2tntpsemt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2twztmvgg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gt2vfylcgtw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2mlnisiew.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cqqwz.cn/Article/details/gt2fqkacwtb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2wcyydihb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gt2defrncdj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gt2kwzgamml.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2rqrmnnhd.html

[A09] 绝对值与最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psqfkhbu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2ifowehbh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ljamdzbs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbeavwsn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2ixzqjhia.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgkmlqrb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ivvv.top/Article/details/gt2albzfzzx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gt2skwiulhx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2ksgqsoxm.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gt2hlegkaxx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfsnnsqv.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gt2hkxrumcd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gt2inauesdn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2xxhoklfj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aibaodan.cn/Article/details/gt2txoeyjeq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yongpay.top/Article/details/gt2taeqtegl.html

Ruby: rand(1..100)
来源：http://dali.hfpthk.cn/Article/details/gt2ygqkndes.html

C#:   new Random().Next(1, 101)
来源：http://dali.quarkkingdee.top/Article/details/gt2uwjxomid.html

[A11] 条件表达式（三元）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opunywxa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gt2xqvrbrhp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2hzpjrpml.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gt2hpikvsms.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2bjgibawk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2ebvaarnj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gaohongyu789.top/Article/details/gt2uyirdwau.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2ryjmushe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2fidbskeg.html

[A12] 字符串插值 / 格式化
来源：http://dali.sysykeji.top/Article/details/gt2uyskihsj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fzhhl.top/Article/details/gt2bqgnguyq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fzhhl.top/Article/details/gt2pkwoygcu.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gt2bugisfos.html

TS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqqfnooe.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangdashe.top/Article/details/gt2uojqwxni.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sxryk.cn/Article/details/gt2ygtisauq.html

Ruby: "Hello, #{name}!"
来源：http://dali.dianchejie.cn/Article/details/gt2dkdrclfa.html

C#:   $"Hello, {name}!"
来源：http://dali.aizwys.cn/Article/details/gt2ynizdlyg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpejjzot.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2kkeeiucq.html

PHP:  "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2nrlonlxm.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2eidcfqil.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2bmlbajtz.html

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2yqepuyge.html

Go:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2dcvfvotz.html

Ruby: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2fqxqbcws.html

C#:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqlgjjaq.html

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gt2gqygcrun.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlnqplrj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gt2pxrkgwun.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gt2qpcboozh.html


<!-- 参考信息 -->