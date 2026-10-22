代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gtpchskndd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtfhmyqtou.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gtlhegvawm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gtmbckmqzw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhengqikj.top/Article/details/gtemnzxubu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cdnleiting.top/Article/details/gtyjhnemit.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtjqdgmktp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gtlcgxklin.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtifhqbycd.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtpeldwhkj.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtpengiyjm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gtjwaiipgv.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtxdbswnqp.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtaxhwairq.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtkoocnbmi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xylfe.cn/Article/details/gtupmxousz.html

[U75] PHP：依赖注入
来源：http://dali.fzhhl.top/Article/details/gtxbdwqdiv.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gttnyroubx.html

[U76] PHP：简单路由
来源：http://dali.nanxinkj.top/Article/details/gtdgzdzahk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gtiwlqmydk.html

[U77] PHP：模板渲染
来源：http://dali.hongshengwenyu.top/Article/details/gtasmeecfp.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtulummvhy.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtihmssryk.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gtsbfgxwcx.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gtsegqzkac.html

composer require --dev phpstan/phpstan
来源：http://dali.vqdsnc.cn/Article/details/gtkyhlzrdh.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtxvzxooms.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtdpsedddl.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gtmgcisiaj.html

npm init -y;  npm i express
来源：http://dali.nwbrower.top/Article/details/gtnmysupqd.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gtukujliuh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gtqkgvygic.html

[U83] JS：ES Module 导入导出
来源：http://dali.yanxiufei.cn/Article/details/gtusspdqon.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtzzfnmddn.html

[U84] JS：CommonJS 写法
来源：http://dali.yuanzhike.top/Article/details/gtlpgqbddw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gzhubu.top/Article/details/gtezguymwh.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtjbagfkfi.html

a?.b?.c
来源：http://dali.bjfxy.top/Article/details/gtuotsxedr.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gtslvxawql.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gtrwiqitbw.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gtvrzznwcv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtbvkngudp.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlefmbjgf.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gtimrbjynp.html

[U89] JS：数组去重
来源：http://dali.guannengcc.top/Article/details/gtnpmmnwsk.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtfcjfvbka.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gteffozhvq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtxyvfvsqh.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gtwfbcfnoo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xylfe.cn/Article/details/gtjjnpunpr.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gtydhcevep.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvelqtkox.html

[U93] JS：模板字符串
来源：http://dali.nwbrower.top/Article/details/gthrwxvwgm.html

`共 ${n} 条`
来源：http://dali.nwbrower.top/Article/details/gtvskjgkuj.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtpvlzdirz.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtmaqslrsw.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtcvbjjvvk.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxuanxn.top/Article/details/gtynsothjo.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gttnuacsfi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtiomzfuym.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtmgscisya.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtactnrfdg.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtuetnfrgq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guowangkeji.top/Article/details/gtvfbzxvxw.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gtmmziirvj.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtciyiywtk.html

[U100] JS：DOM 查询
来源：http://dali.shangyingyoupin.top/Article/details/gtnltgzbvz.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gtxowwxnbv.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtmkwvrgyr.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtexjnnind.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtnagxrouu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtkoufffms.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gtscnjqxhq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtkhyspzto.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtqqracazd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezmbiucz.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtfeogwyyi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtqkhijccx.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtqbjwzsmb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gtvirlipau.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gtnpdpnbne.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtccsxcaca.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gtgvckvovo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gthclcklsq.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtiqoziplt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gttubvvlmp.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gttieovaiw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gttmahgddg.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtmirbvymw.html

new Map(Object.entries(obj))
来源：http://dali.xziqi.cn/Article/details/gtxyjvdvxk.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gtdytnkspi.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtvejwyzfa.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtxvcwjfsb.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtvomqksbp.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtbeablqgy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtqhccvayq.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gteuxibtgt.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxetidsqc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtwmntzjcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtfsxcaink.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtorboxuhf.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtchxaolxo.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gtbfhnptoq.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtckubmsak.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtritiprkq.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gtovzobiod.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtmwkqtnih.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjdszyzu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkqkgdbhm.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtdnmzepzi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthxbdzkqz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gtwwplfshb.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtmfdrtasn.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtzrjzvqfo.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtstkutmgc.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gtjjncroxp.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gteydbpfze.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtezojltfo.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuycgnxdb.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtnjynvyop.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gtxzzigxau.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gtmzsjgwbj.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gtmcxbziru.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtzdvixwna.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtcuyewosr.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwifjmiuc.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtwmjqlpwt.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gtrhhcebkx.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gtcgrxuumu.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtttobipmo.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gtzagrzprb.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gtzunumshg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtzqiosgik.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtmzfcvvqw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudqwarwr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtszutquir.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtonppxyjj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtxnmcypfw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtgnoodslx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtjwstkaar.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtgojcqclp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtarbknvhi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtubhbkowv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbgxmquy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtahljtwbm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtchykvlid.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gtymqwjgad.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybnkykys.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gtgwwfwemo.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtppkcyule.html

S C / C++ 专题                          60
来源：http://dali.guowangkeji.top/Article/details/gtfzkruaeh.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gtwiiyektm.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gtpgfuztro.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gthdiexysm.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gthdbuvnqi.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtbrykxoqj.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtrgxfjafa.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtqfnimpxv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gtmtdokfnt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gtsgsluogd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gtfklrwnnz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gtleugfrza.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gthmpqzfpz.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtdbucyiyy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxkivkqwp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtgodhizbs.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gttwwtrwwk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkfeqhavu.html

【收录内容】
来源：http://dali.daria6918.cn/Article/details/gtoquensgl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gttbsiuelq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtxhgrdvai.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gtsuknnroc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gtzgwisqea.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gttqnhqtoi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtclvbxqyv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gtvqujducq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtzcvtmqfo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gtfvgserfq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhongyouzk.top/Article/details/gtqbufqjmv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gtztcohpfm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gtwkcyehqx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtinfojczt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtjctflegr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.haohaochexian.top/Article/details/gtfpxcbviv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxuanxn.top/Article/details/gtrbaerlro.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtcjdckmkw.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gtmzmeocst.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcztsupf.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtsjcjwoqz.html

目  录
来源：http://dali.chenjidiqi.icu/Article/details/gtzrytpjpr.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtxkofzaxj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtuxydnudi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtsodqekyy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtcmpfkcyo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtevpejovp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shzxlz.cn/Article/details/gtjsvwxzxa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gtzxgkinwj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtiukxajhi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtnpwcmcct.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtcwfpclsm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtpioqqvcc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtwzgmxkwj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtbpijoiut.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtgslagxkq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtvutjkyxf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtkvyivzdo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtubtsxmhe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtuvajakxl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtddzlurac.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcynfnobt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtjbicdosz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gtcbixtbrp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpuidrecf.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gtetsrsrej.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthtvvjjja.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gtkknfbswc.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtzxkjkdah.html

PHP:  echo "Hello, World!";
来源：http://dali.aibaodan.cn/Article/details/gtjukzyuyb.html

JS:   console.log("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtpnuwsewm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yanxiufei.cn/Article/details/gtwdizkkht.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtapziejev.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtbxxrqkxs.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gteazywysh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtjnvjcmwt.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtlxrvgelk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtnnsdjcqm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guannengcc.top/Article/details/gttqazomxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gtsjpbvzcg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj202588.top/Article/details/gtakrummrw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtzfyavajz.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gtenoxlhlc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuetiantiany.cn/Article/details/gtiymyemuv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfxtjtvs.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gtdhgjqcfc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gtiuusrzwp.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtlojjbpoq.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtwywxgshb.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtqpiwuums.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtgbdklrul.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtejqcjtml.html

Ruby: PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtbmwhdwpj.html

C#:   const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtkvtrbcay.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gtddaciziz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gtjwkiczsi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gtcjdmjfnc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtuxmlcohr.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtamjqxpjp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gthbxjojuy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtsevvvhqo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxinkj.top/Article/details/gtmzvvdegx.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gthlffwlts.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gtgscxeqpw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtfxxfjocv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtlnahfpuu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtvjdkamhc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtavxyqbfz.html

Java: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtzjnfxfoj.html

Go:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtkqhjrtau.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtolgfcxvh.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtynljkejg.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtabqzotmq.html

Py:   int("42"); float("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtcqmvnfdw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gtyunemksh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sweek.top/Article/details/gtedbqhcxt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtibljorrz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtqdupjxgm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.c1oappe.top/Article/details/gtraxlduzd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtmwmsdutv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrtrtkqy.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtjbxtzquw.html

Py:   str(42)
来源：http://dali.andypj.xyz/Article/details/gtgltldtct.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gtuloxeqlu.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gteqtjxkre.html

TS:   String(42)
来源：http://dali.aizwys.cn/Article/details/gthfftncrf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gtfgluwswk.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gtgeiosbos.html

Ruby: 42.to_s
来源：http://dali.pengpengdd.cyou/Article/details/gtxcidcily.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtrixmhbxl.html

[A08] 取整与四舍五入
来源：http://dali.chenlongwang.top/Article/details/gtzsalbfqr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtwhvkmecy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hammf.cn/Article/details/gtfcgohldi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtuizptdjb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtdbexqvus.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpashsko.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtmnonyisn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gtaqdhpmmg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglclvdoc.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gtfynwuave.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvdtdzxr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtcwnnovut.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtqleavfvr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtudehnpjx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtsrtvxmhk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gtuwegodff.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj202588.top/Article/details/gttzecblfs.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtczskzonl.html

[A10] 生成随机数
来源：http://dali.pycfn.com/Article/details/gtrxcvupas.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gtqrbunace.html

PHP:  random_int(1, 100);
来源：http://dali.aizwys.cn/Article/details/gtpjlrxssi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtggcvrkvy.html


<!-- 参考信息 -->