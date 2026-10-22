代发 wailian999

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gt2xvmnfsdp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2irtqebkr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gt2mlgmhqbh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gt2vevgujkr.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gt2xvrujobv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gt2kkjehdtd.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gt2vvlnnyud.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gt2djxepabg.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gt2ldozksbo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcpsmokf.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gt2bvprhoev.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangdashe.top/Article/details/gt2dwsptqwo.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2jlrappju.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2impbqued.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2brlyukoq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2wvyskbfy.html

[U73] PHP：读取 ini 配置
来源：http://dali.cqqwz.cn/Article/details/gt2lcclrefe.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gt2shlonilg.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2dtegebln.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gt2sielcyad.html

[U75] PHP：依赖注入
来源：http://dali.chenzaomai.com/Article/details/gt2frvfpkhu.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdtcjqxg.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gt2rjijrlcj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gt2zvnbubvr.html

[U77] PHP：模板渲染
来源：http://dali.pycfn.com/Article/details/gt2tnqiqmwi.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gt2qhfooxlo.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gt2bzcrnxaw.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gt2xcoytzbu.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gt2srqbraql.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gt2eatxkatg.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gt2lockbjwt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gt2elxtuswv.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gt2ecpxftfi.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gt2rvwjiodn.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gt2qtqjdrme.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gt2xhsplzuu.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gt2wjwduvhn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwkddccy.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gt2oywiunqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuanzhike.top/Article/details/gt2dgsqugrg.html

[U85] JS：可选链
来源：http://dali.yanxiufei.cn/Article/details/gt2telelatl.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gt2kabfadnj.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gt2ufecqftc.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gt2fjqetrrl.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gt2sufhicqu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gt2dwwcbqhv.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gt2hrrqtseo.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gt2elbfhiyw.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gt2javektnd.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2vbhlmmfr.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gt2ohfyizzb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2whcwmzgi.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gt2vyfxqmjz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yonumen.top/Article/details/gt2mjqdlisv.html

[U92] JS：深拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2zobyrryz.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2foogtlpe.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gt2xkihkmmj.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgzobdxi.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2ofjrehuj.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2hgizvkzu.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gt2dmflpwgw.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gt2ybkxnilg.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gt2cinknutl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpcmyudc.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gt2zyagacer.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2mwpqijsy.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gt2kzeeypjl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrjurdsr.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gt2ovqeyumn.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajraklvq.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gt2zvrqkttk.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gt2tpxtxjzq.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gt2ulseokbe.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gt2mmfeswop.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gt2ikadeyrm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gt2iqkhanqp.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2gwxzgzuy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gt2iinrmruo.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gt2bfkufvjd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2srstmtjl.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gt2rlobfmqe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2qbbvadih.html

[U106] JS：日期格式化
来源：http://dali.havefunace.top/Article/details/gt2lmdovigg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gt2lrxozjel.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2gloylcyv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2dehgecqz.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gt2flofdmfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gt2ghrcvgca.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gt2efgkzlkx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbvwqcms.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gt2hjtyoyqh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gt2pnffojbm.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2qstuzvbw.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2bktvvxdq.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gt2ajvpkjmz.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2xumlcdyp.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2dayrzwmt.html

s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2dgwossso.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gt2mlpdolnn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pudrgcib.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2jhiopnnu.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2ostiurwo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gt2scohrfut.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwdbsjfz.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2jaejukvu.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gt2uoiiyklr.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gt2vxipcisz.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gt2adqnapwh.html

[U119] JS：生产构建
来源：http://dali.yonumen.top/Article/details/gt2hzjggbey.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwcaefms.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gt2vagmciku.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gt2zudwwzeu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ihcwkbmh.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gt2aaemxqik.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ejhttzuu.html

按语言统计（条）：
来源：http://dali.shuidangran.top/Article/details/gt2dhlffsom.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dagfxjub.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gt2ajgkaqei.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2gxdxmaub.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gt2bfgwvymz.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2ebqynwdq.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2iuimviva.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2otnuywuy.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2kmklgbbo.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gt2ojczbkby.html

C++ ............ 30
来源：http://dali.svipenyu.cn/Article/details/gt2osocqfqn.html

SQL ............ 90
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxcxjkvv.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2ftcrxuwh.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gt2nbtdzuhq.html

Swift .......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcfhhhsu.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gt2hrwpshwv.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gt2cxvnuniu.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gt2hkwdsomx.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2peaufcnm.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gt2reiadjyt.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gt2wvnrlpwx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gt2gvxcotbc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eppdixvf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gt2vbgadjgo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2xbqkrxbv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gt2qjfqordr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gt2pdlrkulc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2rvkicksw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2muknyqnb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2riouueci.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkkmmqyi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2bzdrtswl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2qgylltkx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2vyjuapqw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gt2dlchykas.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gt2rcyoesfq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2xusxaoqx.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gt2ngegybqt.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gt2maaszccr.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gt2zaqwowts.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2foqecihl.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gt2suwlewbk.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2mwmmydes.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdiwdlza.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2pwqtquap.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gt2wrutxsug.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2zggcyjbb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.svipenyu.cn/Article/details/gt2nznajdlf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.snrcjt.cn/Article/details/gt2oxbzumid.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gt2ovqeckkk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zulkuqfv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hysaishi.cn/Article/details/gt2wtlhzive.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gt2wnmflaci.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qpquhzvg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuxming.cn/Article/details/gt2rgtmddfj.html

Common Programming Examples Cheat Book
来源：http://dali.dianchejie.cn/Article/details/gt2umnciyvt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2oeluzoxg.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gt2bljrlhxf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gt2parprlis.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gt2mlumsztj.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gt2ikfilfmy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gt2kflhwsne.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gt2kjtfsjra.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gt2hbkhcwcd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gt2iwvetbyv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gt2pcwhulgk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guowangkeji.top/Article/details/gt2cujpifmc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkwmwllf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gt2zwkwyqav.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gt2felvocph.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gt2bzcwobly.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daxiang520.top/Article/details/gt2mmntucbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2zeqtvjqu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj202588.top/Article/details/gt2jefbepos.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2thiuydak.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gt2vhubcbfn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixvqoqcp.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2ikuaayis.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gt2hbnpaann.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2ubipbazo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gt2qjswthhk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2dkizmxws.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gt2cnatflux.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2hffqkbil.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gt2eymdpzrk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2fmbafbwu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gt2gpmamsxz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gt2evxrfzex.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2loxocoox.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2ujejvejc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2oervvpmp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gt2jomqirwr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2qrzwxqgq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2lborzqmb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gt2bicvondi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ugarakjo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gt2wgrhqwep.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gt2heefwsor.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2pgtecheg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2kyxrjooa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gt2zklutkxh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zpsixnuv.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gt2xbvahtdy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mpbjlrly.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gt2hepcvivy.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2tigodhsa.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gt2phrscnoa.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2ojexhxbk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gt2brgwmsbz.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bijoitar.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2ljhzmzmy.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgkjejpx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gt2bjdfgqlk.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gt2poixutzb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2fraouyhe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gt2ecnviujd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gt2ibmkrryt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2dphnchjf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2zzutuxrv.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gt2gizcpvia.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gt2kfhokgdd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2vtjmsiif.html

[A03] 常量定义
来源：http://dali.shuidangran.top/Article/details/gt2iqmnjawa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gt2xirwjwrj.html

PHP:  const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2nydjhzvn.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuaguuqy.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvbxqfsn.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2oqrdgobf.html

Go:   const PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2ottbnewo.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2odcqdwqj.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojelwjyp.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzpdcngw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gt2htgkdpgd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gt2vmhxgloz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gt2ccldofzw.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2fylifstl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gt2evovcwjz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.snrcjt.cn/Article/details/gt2dxftqgxb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gt2cpbxrpco.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gt2sskixeqh.html

[A05] 整数除法与取模
来源：http://dali.kuanghao11.cn/Article/details/gt2esptggmy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nwbrower.top/Article/details/gt2vzzbbuus.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2tqojunat.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2fwbjqlxn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2uungtimv.html

Java: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2iygdszbo.html

Go:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2vprmmfmm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2hgrhrkvj.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2lyvmfjyd.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2cxsdvtfg.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gt2ssqwrxbn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gt2ivzihoce.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2zxipafsh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2gvhaiunj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2glfrmrjw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gt2mxkzkayp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gt2ncnclbvd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sabuegui.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gt2ssbmrdrn.html

Py:   str(42)
来源：http://dali.cucudq.cn/Article/details/gt2feivuyij.html

PHP:  (string) 42; strval(42)
来源：http://dali.ehwqpu.com/Article/details/gt2luixcrcf.html

JS:   String(42); (42).toString()
来源：http://dali.yueranfly.top/Article/details/gt2wpzgdxul.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gt2muwtqern.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gt2jgbnhoee.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gt2nhrqfian.html

Ruby: 42.to_s
来源：http://dali.gaohongyu789.top/Article/details/gt2ewfxibxw.html

C#:   42.ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2gquwobzh.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gt2eltwqafe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2ykqmtvwt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gbtmoxjt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2bxwncuds.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhixingplan.top/Article/details/gt2yxzpikrh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2rjggnunm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2jnqywkto.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gaohongyu789.top/Article/details/gt2ffoexnyl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2mzoavhrg.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gt2sxjfahhf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2avpunxzb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2uskmekfs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2tcilpzbz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2eoznkfjv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2wpazbdps.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258.top/Article/details/gt2ubxunddh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuanzhike.top/Article/details/gt2acfdhqtw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2hqltxwzu.html


<!-- 参考信息 -->