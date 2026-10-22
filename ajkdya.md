代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irsxlxxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gt2czfgmkuu.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gt2zxiehsio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwkcou.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gt2tijjnzgd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.kuanghao11.cn/Article/details/gt2efkudsmr.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gt2taninhgp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gt2lktutapa.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2udvfssyt.html

throw new RuntimeException("失败", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2laklaxfn.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gt2kramitrd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gt2awduxvly.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gt2liktmpok.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gt2tbqhkrap.html

[U74] PHP：读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2yuqeecmg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gt2awrcixdd.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gt2kipzelug.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gt2okxtpkpm.html

[U76] PHP：简单路由
来源：http://dali.zycfv.cn/Article/details/gt2qskrvpky.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gt2xunsdbvb.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gt2isunvzou.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gt2rcenybio.html

[U78] PHP：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2nbjvrvyb.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2iqcfqtnz.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gt2cqfpuwtc.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlajqrdm.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gt2wkxkzkyv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhixingplan.top/Article/details/gt2rromvfuk.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gt2ukmshnkd.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gt2vtmtihgi.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2hozjbovm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gt2baejflrf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gt2icolgcql.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2neejbdwn.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258888.top/Article/details/gt2dyapulfh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gt2gzbixeck.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gt2fvhenlub.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2vvmrolja.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gt2jdiuxmfy.html

a ?? b
来源：http://dali.haohaochexian.top/Article/details/gt2ovqnwjgr.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2jthtdmmf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gt2yuskbuak.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gt2txguscwu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyywpysz.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gt2qzgcqivl.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2mertwqyp.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gt2thxeflld.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2sukqkkux.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2autrdizq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2leeusrkm.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2whnkggid.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2picmztcr.html

[U93] JS：模板字符串
来源：http://dali.nwbrower.top/Article/details/gt2otklqrdk.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2ihcwmwdk.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2zzfxcykj.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gt2iwyuuiqi.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfvkxjkg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gt2edvietkd.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gt2bojeluxi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2ndaleylv.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuiypjpw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2yjcuwygx.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gt2ijxrscio.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gt2gdhtdytn.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gt2wjlicxbm.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gt2vuoqltcg.html

[U100] JS：DOM 查询
来源：http://dali.zhixingplan.top/Article/details/gt2hutlleis.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gt2irexhogk.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvsvxtax.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gt2gilqllig.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gt2eqlnouhc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gt2pzbpziao.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrhprzdm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gt2qqqkwbui.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gt2yqghnfxg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2lxqdersx.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gt2prukpnup.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gt2tmywtfyu.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2tqduonqx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gt2jjojukfh.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2mffveajl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2bsvpfifv.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gt2egotbzon.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gt2rzywckvi.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gt2enhnflkt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2xtkknxpd.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gt2otkqfnej.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gt2lcilbboo.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gt2bknrdkng.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gt2qveaogjb.html

[U112] JS：字符串补位
来源：http://dali.jinqigufen.top/Article/details/gt2pqcsxkih.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2zxlbvhbk.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gt2sxednuru.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2becfrhwy.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gt2oskrknkf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2ymlnprxc.html

[U115] JS：生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2fyjxgozj.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2pelivbvc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmoigbpj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2anxbyiij.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2jcffvtph.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gt2gpspsewa.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gt2zpuffuqj.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2gnfhtlnp.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2fzbvpoii.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gt2qojnuafs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gt2hlcouvzu.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2mtddhzel.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dzojqybx.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gt2vudeldjb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rsobwbyr.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gt2gjvzxlxb.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2fdkfsnte.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gt2fllvlwef.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tiquacjp.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gt2cbtodsdu.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szxxnmcy.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2qhaycioi.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2blzevuaa.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2satflvfy.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gt2mkcbinho.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gt2hjoxiczy.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gt2btagukmx.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gt2goetdzmx.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikjpxggu.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gt2imswgutl.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gt2vjumnvyq.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gt2wffgdkht.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gt2cthlfzjq.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2etumospj.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gt2zgfkmpra.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gt2fzlomdpw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2sxwujjlg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2yfifwpyn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2agytljws.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2csmbqhzj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gt2tyitpvoz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2fuemgflh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2cotghutc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gt2lqbfckdu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2bopvvqoc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gt2ijizswxw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2zqyvjfzf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2hgucwceg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybcuavae.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2mwvucbhg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gt2wlrbcgiq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2atljwgea.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gt2jyzfotjt.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gt2khjtsgqp.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gt2poyxyyxi.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gt2whanybwd.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gt2bjwhhgbm.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2bvtkhwqz.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gt2ozsglohw.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2znsfipxu.html

使用提醒
来源：http://dali.0kj1m.cn/Article/details/gt2natugonc.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjhxintb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shangyingyoupin.top/Article/details/gt2gefkwqnm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olegngft.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.redwolf501.top/Article/details/gt2uyogunhd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gt2ilkgtwkx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gt2skvhxtnp.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gt2vbovxfzi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vvotezco.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gt2npokmoal.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gt2bfqcnhtr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hmnqrrnn.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gt2nqzydvji.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gt2mxcfmlbb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gt2hkgjuaqe.html

SQL · Bash · C · C++
来源：http://dali.yonumen.top/Article/details/gt2uhxsuyae.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gogol.net.cn/Article/details/gt2aubpoypr.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gt2iknjfdqo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gt2dwjzacam.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shuidangran.top/Article/details/gt2eubllyqn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gt2ifihcgfy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gt2fewlimvy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gt2pkypfkzk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtfyqutv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gt2mzsjdudb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hongshengwenyu.top/Article/details/gt2szitutof.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hnqzz.top/Article/details/gt2femapsgz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gt2uptvxprc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gt2ebjnmxdm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gt2jvxtgtul.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gt2locwgjbt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gt2dlbpbcoc.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2fgdehxtd.html

目  录
来源：http://dali.sweek.top/Article/details/gt2irvknnhj.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2wjghwkbv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gt2zigzscya.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2wgcruong.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gt2rdykhvwl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2quyyetxb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2cldmdukb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gt2yrvrsxtt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2yzjxaspn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gt2xehzxzbg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2rjrzuwlc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2cdhsrfxg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2hmyvhdzs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2qkecybfw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyfjrsnz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2omtgkrwo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekrqggxk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2qaoaljul.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gt2wlwlesfw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gt2wwmisjhv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gt2pzjbqwjo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2cluhpjzu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ojkcufkm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nigifysc.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gt2szxdceud.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qmladkon.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2togxltys.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gt2pwykmbah.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gt2eqsonbur.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lewkeeql.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gt2tvvgoylq.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkiijepv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2gxcrhvrh.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxuanxn.top/Article/details/gt2fmquvwor.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gt2jgthycvf.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gt2gejxsreo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gt2gyqygpxb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gt2hgbhwwxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2vbynsepn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufvrqcmz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2cxwwiyva.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gt2mipkeyen.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cheryme.top/Article/details/gt2jcesbmzt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2isymoqmq.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gt2fiisahop.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gt2wnecbzts.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2wsfhoern.html

JS:   const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2lrtvtatl.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2hnubsclw.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2bkyldpyy.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gt2uzqrcofu.html

Ruby: PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gt2wcfkedxn.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2bntydarj.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sidavalv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ydzc1.top/Article/details/gt2fwffohsd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.9152youxi.cn/Article/details/gt2lyjlzssu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2njqvcwiq.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2jcriurgf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gt2dfouazfo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gt2ngvozsmh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gt2qdmpovgc.html

C#:   x.GetType().Name; x is int
来源：http://dali.vqdsnc.cn/Article/details/gt2uzygfezr.html

[A05] 整数除法与取模
来源：http://dali.shzxlz.cn/Article/details/gt2dauaytpo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gt2umjgvjql.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2navobowh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gt2qrcflgsv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2jhchiekw.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2zhjrmoky.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2qouxnwxq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2xplhnxcc.html

C#:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2eiybwmhk.html

[A06] 字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2xdyrllml.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygjubxqw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2hyodayci.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gt2pyfyvnea.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2xrzdyphr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2ynolkrqc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdunxkik.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xylfe.cn/Article/details/gt2cmfwypbl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2akasxxck.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqkvhsrl.html

Py:   str(42)
来源：http://dali.dianchejie.cn/Article/details/gt2zqevkccg.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gt2nyeepzfl.html

JS:   String(42); (42).toString()
来源：http://dali.guannengcc.top/Article/details/gt2qozlhpod.html

TS:   String(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewzbovcm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2scsctfkk.html

Go:   strconv.Itoa(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2ktzuccoz.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2azneufcc.html

C#:   42.ToString()
来源：http://dali.aizwys.cn/Article/details/gt2wdgttjhj.html

[A08] 取整与四舍五入
来源：http://dali.pycfn.com/Article/details/gt2oyaqtits.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2zrfrglav.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.mhx1999.top/Article/details/gt2kngsmoxx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2ppncmfjz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gt2yzunwmdl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2oypaykzy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2epjxuafz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejzhptka.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibpasmnl.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2zbzdharm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2bfbgiqrg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2rqvabuer.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2yepzmykj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2repsrahk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2crmgoekg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hysaishi.cn/Article/details/gt2cvuwpsso.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzcyezsk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2oprubnnx.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gt2rlwtjgrp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258.top/Article/details/gt2rkozkcdz.html

PHP:  random_int(1, 100);
来源：http://dali.yvedp.cn/Article/details/gt2ewqwduey.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2agarkqqr.html


<!-- 参考信息 -->