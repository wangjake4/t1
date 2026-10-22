代发 wailian999

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gt2msyvqsvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gt2emnubovx.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2lusaxvja.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gt2lwnsyxhd.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gt2siovfdgi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2jyxhmwpj.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gt2nlxgitxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gt2yguxukvi.html

[U67] PHP：处理文件上传
来源：http://dali.ivvv.top/Article/details/gt2rukkdmit.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigfzy.top/Article/details/gt2iwyzthwu.html

[U68] PHP：PDO 连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liildfya.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gt2qikxvkqz.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gt2davrdsup.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2ywosmxbk.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2srgzatns.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.smart0.xyz/Article/details/gt2nxiktipz.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gt2zjhpmgce.html

throw new RuntimeException("失败", 500);
来源：http://dali.316326.xyz/Article/details/gt2zhyggfac.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gt2ssbpknef.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gt2okymswbn.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gt2otqownem.html

parse_ini_file("config.ini", true)
来源：http://dali.gotoacloud.top/Article/details/gt2joeyxdwc.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2utmwsqxm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gt2tehzvxlq.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gt2gclcxdzh.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gt2zpdgpptu.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gt2iheyuhov.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gt2mtdivvau.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2irtkdrgw.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2azpvmrzq.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gt2eqfvpujp.html

composer require --dev phpunit/phpunit
来源：http://dali.gotoacloud.top/Article/details/gt2jnxgygmf.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gt2qsgzcrrp.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gt2purgweps.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gt2zgyxpgds.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2dcnrfosu.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gt2chhbalwe.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gt2tfcuywdf.html

[U82] JS：package.json 脚本
来源：http://dali.fzhhl.top/Article/details/gt2cpdrwcmd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gt2zxvjqgxi.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gt2qysztsxn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gt2duaznhtp.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gt2oyckpsxn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.quarkkingdee.top/Article/details/gt2nmugllko.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gt2pxjifpee.html

a?.b?.c
来源：http://dali.zhengqikj.top/Article/details/gt2nzwrobxc.html

[U86] JS：空值合并
来源：http://dali.smart0.xyz/Article/details/gt2rpdjnftd.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gt2rztqzacv.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gt2vbqqylre.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmaodrqu.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gt2pwljcwpk.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gt2yidzunlc.html

[U89] JS：数组去重
来源：http://dali.smart0.xyz/Article/details/gt2ztjvzrep.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2juhkceda.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gt2jukhtvgq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2pjllhjir.html

[U91] JS：对象键值遍历
来源：http://dali.andypj.xyz/Article/details/gt2pgosroza.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gt2tqclbgiw.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgcaextv.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2bjsiqmxj.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gt2ekldylzd.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2vjoazsdj.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gt2hociflol.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gt2nogliuyv.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2brdrqtih.html

new Promise((resolve, reject) => {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhtdxmcd.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gt2bdxstqry.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcownjyi.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gt2mmuxmsfp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2ixrbndvs.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gt2nwdykfju.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gt2mjjhiwyb.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gt2rjxpykgi.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gt2ehqnbrmb.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gt2tnrsqgth.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gt2odhettgc.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gt2quxhxayu.html

el.classList.toggle("active")
来源：http://dali.guowangkeji.top/Article/details/gt2mrodeaoe.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gt2cgncfwje.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gt2lfreyvlf.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxnowafo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gt2fdazflxw.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gt2vzbduwzv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2prcnepza.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gt2whcwonxs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gt2rfacgfdl.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2hhxhawjt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gorfwiqj.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2rmhyqust.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2otmjxamc.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gt2rzxbixui.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gt2pjcufurz.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2dqbkhcri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2ccwtwdri.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gt2fjaxujbs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqnxcvlt.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gt2ekqbkdyg.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2usztpfea.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gt2hnoiaefb.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2xuqjskns.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gt2pmqvipjw.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2bfycdvwc.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gt2uxznuxux.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2sbnmliym.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2ffkbnthe.html

crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2lrlgoopy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gt2nszgseaw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tzvcvlgq.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2nftrplfe.html

npm i -D vitest;  npx vitest
来源：http://dali.xinyue.icu/Article/details/gt2rmhroixc.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gt2lnhmcisq.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owgmvyvq.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gt2nkndkspl.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gt2pquaqixl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2djabfsvz.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2mbhtnevn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2tigdgakr.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gt2doqaeuer.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wyaehdee.html

按语言统计（条）：
来源：http://dali.xylfe.cn/Article/details/gt2jnpoyvrq.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2swzdjbvm.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gt2ulbpalxo.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2tiytueyx.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjicjxiq.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gt2yytjovnt.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gt2dqylqxys.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2ijtqeyue.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2dptejrvw.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gt2coatyymd.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gt2miumaksb.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gt2mqtfsnjf.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2joducpqz.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2hwaghrft.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gt2ualvexol.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gt2lurubhcj.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2kdxvbcgd.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gt2wizdtqso.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2fbwthemg.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2ppxglcet.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gt2lneeszpe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gt2sgzxbveg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2oybagmok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2kjvtecpg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqengcbh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gt2fjgrbdyd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gt2rahvvclb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2lcedtnge.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2mqbrwuvu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2vhnhxkbk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gt2sbhltcvt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2qfgkwxdp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2lgskyaeh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljheeukr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gt2kzvajizu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tianlin.xyz/Article/details/gt2sdcyckxv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2gvsxwqbk.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gt2gsqmfeyt.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gt2dtifhcbl.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxligfrr.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gt2gynmmcur.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gt2omypibmv.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2abwfpvxz.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2xwwbcufv.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2rwblepej.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gt2wwlfaeli.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wodmgoyq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sysykeji.top/Article/details/gt2uixucwci.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gt2uoeqgjdp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.0kj1m.cn/Article/details/gt2wjeldpqo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gt2ssdcuvhc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gt2whrazbjn.html

—— 文件结束 ——
来源：http://dali.ybcxt.top/Article/details/gt2sfpbtnrs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ldptstmn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gt2alybrjxi.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gt2tkiyazov.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2crpjhvix.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gt2sarfffrt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gt2opxnqspx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj202588.top/Article/details/gt2gthbqpgb.html

SQL · Bash · C · C++
来源：http://dali.tianlin.xyz/Article/details/gt2cmjynyum.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgufenzy.top/Article/details/gt2rbaftksm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkkjgqg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jiagoushi.top/Article/details/gt2fezruvhx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gt2luwsmiyy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuxming.cn/Article/details/gt2mshfgqmn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.kuanghao11.cn/Article/details/gt2disnwpou.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gt2ubzivpky.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gt2qygmzgse.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gt2ybggdcga.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gt2zpmijaar.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gt2blkfydnz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dianchejie.cn/Article/details/gt2jgjlawlh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gt2ukgssnph.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gt2edowqdyn.html

【文件统计】
来源：http://dali.cucudq.cn/Article/details/gt2vbfkraxw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.316326.xyz/Article/details/gt2agtwdhri.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2iztawadx.html

目  录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmxlpqqa.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2bfbjqwsu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gt2rtbmqyqp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gt2lejxkxme.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2uighypcw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gt2trzlxpmx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yangfankeji.com/Article/details/gt2olnvidix.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gt2dkcoabwj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2fuushhre.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2eizgmilu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2kxmftcls.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2vmtcsazf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2ejhswrdt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2mgmprawc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2plgjcdws.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iequsdkr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gt2fplmpefy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2jkzyavip.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gt2nlqjesox.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2bmxscxiq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sufxvd.cn/Article/details/gt2drzmsayq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gt2iqpzvrvt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2pzcnsbyv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2psmnvunu.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2tblvelpn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2himcirwg.html

[A01] Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2xhnkhfww.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gt2xfajzoov.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gt2wizotawm.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2vexhdgzb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gt2rlddgkjx.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iczprioi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gt2xyvfemsa.html

Ruby: puts "Hello, World!"
来源：http://dali.guowangkeji.top/Article/details/gt2rwhbxjkt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2hwmupuvc.html

[A02] 变量声明与赋值
来源：http://dali.hnxiangtu.top/Article/details/gt2alxgkvqb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yanxiufei.cn/Article/details/gt2egtjmlaz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2sbpditds.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.havefunace.top/Article/details/gt2rgjjtvbu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2yroslvbt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2wzhikukz.html

Go:   name := "Alex"; age := 20
来源：http://dali.hfpthk.cn/Article/details/gt2wcmwyljd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gt2hsyzcpef.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2jgzwospl.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2mhqldjrb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2rhlnbhvs.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2ieqqxjln.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2rodhmjoe.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2uzbgafww.html

Java: static final double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2dbwuktti.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gt2qioroeoy.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gt2lomokfvt.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2buypoleo.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gt2acqrqcyj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbdnlzwt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpcqygpe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gt2ajxdjpow.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2infoeqmc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2utcyruqs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gt2dzdvgegf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gt2owurqttk.html

C#:   x.GetType().Name; x is int
来源：http://dali.xinyue.icu/Article/details/gt2ixnkjqmo.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gt2yogwmqau.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2ydydbrbh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2wlelkpca.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2nwgjbrtc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2mgdsmdxf.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2snxoicky.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2hsyuglzu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2strxklpz.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2jndccxrp.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gt2cyudqagb.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zplfxilg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gt2tgkjieel.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2pxpmbjth.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yueranfly.top/Article/details/gt2bdoofixs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2emfzcdup.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gt2lntmoigi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cheryme.top/Article/details/gt2uwgmwpnk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2voinojbe.html

[A07] 数字转字符串
来源：http://dali.fengsongda.top/Article/details/gt2siplgazq.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gt2pzlxagaa.html

PHP:  (string) 42; strval(42)
来源：http://dali.xinyue.icu/Article/details/gt2puscaguw.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gt2avlzkqyf.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gt2vpkqdcnw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gt2ghbhbbqh.html

Go:   strconv.Itoa(42)
来源：http://dali.hnqzz.top/Article/details/gt2cqfisrby.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gt2hiozjyhc.html

C#:   42.ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiqpefro.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gt2pvmeksua.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2fjgazmkq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gt2lakhvnsm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nczzwite.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gt2vbbvbffo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gt2okjougei.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2mjrjsgen.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gt2ffxtrhsl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2nioxsmno.html

[A09] 绝对值与最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luoxhren.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2wctjgnzg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2mtdxfwof.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2ckfpadgj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2ibmlijdj.html


<!-- 参考信息 -->