代发 wailian999

[U61] PHP：正则
来源：http://dali.birdmap.top/Article/details/gtepyukmgq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtsxvdgofn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtxzzudgrv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gtsbhciwaq.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtgptpvoeb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gticfieaav.html

[U64] PHP：目录遍历
来源：http://dali.aizwys.cn/Article/details/gtnhxxunsl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gtwzrnizxq.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtaluntxwi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtzsdjdzqv.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gthynbxyyh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtorkonjnp.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gtiycpfiey.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gthunxlhve.html

[U68] PHP：PDO 连接
来源：http://dali.shuidangran.top/Article/details/gtnqzwtuyb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtgxcsnqdb.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gtmydkfblo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtkjppicrg.html

[U70] PHP：PDO 事务
来源：http://dali.gogol.net.cn/Article/details/gtlalhdohy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gtnptamrrd.html

[U71] PHP：抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtbzrdbqhj.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtrsvndjhg.html

[U72] PHP：写错误日志
来源：http://dali.jqgufenzy.top/Article/details/gtdhojutxh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.snrcjt.cn/Article/details/gtfhfbcufu.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtrxemqzwv.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtckmovory.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtwgaelmbx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtlnbcdjxa.html

[U75] PHP：依赖注入
来源：http://dali.yvedp.cn/Article/details/gtfyrzraah.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtswrvlqlt.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gtfeymricp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtzxqpqhsz.html

[U77] PHP：模板渲染
来源：http://dali.yj20258.top/Article/details/gtuwxmzxax.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtyypuwkdv.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqpzznba.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtsgearway.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtxcadvwok.html

composer require --dev phpstan/phpstan
来源：http://dali.xuanzx.com/Article/details/gtzleushqk.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtxqrosdmx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gtwoisywez.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtvmicpxtn.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtuavwbeia.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtrvhhlgba.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtlcfcyhxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gtwjsljpsm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtdoivhrmj.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrivllmlx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtmytfumok.html

[U85] JS：可选链
来源：http://dali.sufxvd.cn/Article/details/gtasdaencw.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtcurqwiex.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gtealibxlt.html

a ?? b
来源：http://dali.sweek.top/Article/details/gtsotbjnrb.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gtevmtxdge.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dianchejie.cn/Article/details/gtisfuvzzi.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtlsqytpxw.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtslvkqjgz.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gtznjlwxmr.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtlqtgxohu.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtymlfvocu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtjhxfdchd.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtanzkvwna.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtpeqdfisd.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtuwnlwsun.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkrzwspf.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtvqnkptve.html

`共 ${n} 条`
来源：http://dali.zhixingplan.top/Article/details/gtbwdieaxg.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtsktptoxs.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtiecrkihu.html

[U95] JS：Promise 包装
来源：http://dali.sweek.top/Article/details/gtapgbamab.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtofpvfgjc.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gtqscszmks.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtfnovglzu.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtpkvgxlwb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtubpeyaax.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtnexhxhpm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtmzebyphx.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtwiowotpj.html

el.addEventListener("click", e => {})
来源：http://dali.ehwqpu.com/Article/details/gtbtdlotdf.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gtdsokbeqr.html

document.querySelector(".item")
来源：http://dali.0kj1m.cn/Article/details/gtdgvlgjco.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtzeerldoj.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtlbjtnfsj.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gtawuyehuu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtfnkygcki.html

[U103] JS：定时器
来源：http://dali.shanyushiyangtech.top/Article/details/gteggjfikw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gthmijtnsi.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtilzrztzo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtlmvvoayx.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gtgfhldtyx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtvbpdljid.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtmapgnpsh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtpiofuzjl.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtobzinwaq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtfpbmiliq.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtbqnehect.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guowangkeji.top/Article/details/gtucbxhpgr.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtdqipeyyh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtfalkscob.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gtnxlowqlc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gtdzgkicys.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtktrmpvda.html

new Map(Object.entries(obj))
来源：http://dali.havefunace.top/Article/details/gtpsztqdaq.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtqruamnww.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtcpwsljbo.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtwoivipkq.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtnvpeodub.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gtrtalqpas.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtwqqcbqfa.html

[U115] JS：生成 UUID
来源：http://dali.tanke756.top/Article/details/gtfajbaomo.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtxtbbgamh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gtcveadsfg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtwimlhqeq.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtlyezmgzv.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gtoyhovymo.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gthywawwkp.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gtwtnvshps.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtfjprmpum.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtzsfrkynv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gtaupdmzgo.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtdfcyvvma.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiacmudnd.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gtpdxfqfcz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkhoytzix.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlmcemgd.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtktryjbee.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtasdfdkau.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtqclhhqlb.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtevrlyska.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gterekaavy.html

Go ............. 212
来源：http://dali.redwolf501.top/Article/details/gtreghvyiq.html

Ruby ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtkkujdnfn.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtflrbogca.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtxncyotun.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gtwbffglzr.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtstgkvlnz.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gtoajyfngv.html

Kotlin ......... 15
来源：http://dali.svipenyu.cn/Article/details/gtjngdcadm.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gttsxiodzn.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gtbnmciaec.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtmjqveqwx.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtrwolarjs.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtnijyxrsh.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtxhhmtxti.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gtymoaldfv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtyrckkvlx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtndjgcsdr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtoyxzqans.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtzqdypqyy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuanzhike.top/Article/details/gtffbhmyzb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtmaqduszp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gthqccgvbh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtqftthqud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtjpmlioee.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtjcpucchn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gttuffchlw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtkpmubyta.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gthmpzineo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtezcrzkvv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gttgumjfrt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtnlzpxjwx.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gtpeuscsze.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gtacvbocam.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtsukwcnph.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtwfrickod.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtyspyclru.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtpqjxrnkp.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtpbovjzjx.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtqxjvvdfb.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoveheijd.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtsxcidfxn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ybcxt.top/Article/details/gthgctlrjx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gtjftxitqw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtmcnuncxc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gtifworxsz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtlsakqper.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtzeyqvblc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrmtdkqwb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtusxrlpss.html

Common Programming Examples Cheat Book
来源：http://dali.tianlin.xyz/Article/details/gtdgpqxynq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtufdomanh.html

【收录内容】
来源：http://dali.svipenyu.cn/Article/details/gtayzoewmv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gthevemran.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigufen.top/Article/details/gtriqpjjni.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gtyovgypsx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gtykvpckee.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gtavhjkleg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtafndmlsd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gteijgaywk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyoclrqw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gtbyajvjjt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zycfv.cn/Article/details/gtdismaisk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgkyzqxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenzaomai.com/Article/details/gtmtqlubhi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsatmqkq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gtmmihmblp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gtwwqfqdim.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gtkdmifrwo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gtsjhjjsip.html

【文件统计】
来源：http://dali.svipenyu.cn/Article/details/gtigdyrmeo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gtodsnqaar.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtzpmupccp.html

目  录
来源：http://dali.guannengcc.top/Article/details/gtuaajvbtc.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtsbdexqfs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtshetzpxd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtygkzrgok.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugrzimfb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtzsxdokqt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.0kj1m.cn/Article/details/gtpupwiggi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtxuvifjxz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtyggwpcbd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtfajekfwd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtjwdmwnvg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtjbztcdhr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtgturkjpz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtkytjvvbk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtynutznnr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gtinohxpto.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gtdrejtmio.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtaeiokuij.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gtaqlpuuai.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtwampuhbc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gtukyhyuhc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtcfvxrnxu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtjieiktoi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuyapusjo.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gtpocetzay.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtumemyomr.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gtrtuqwckx.html

Py:   print("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtdvvaseet.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtminirlvc.html

JS:   console.log("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtkzqcfceg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.mhx1999.top/Article/details/gtwnbvgjjq.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtuxwgmpjd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gtcpuicepg.html

Ruby: puts "Hello, World!"
来源：http://dali.redwolf501.top/Article/details/gtfzxstgfw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtehxsglpw.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gtnadvtgqi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtjrvygdan.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sweek.top/Article/details/gtcpnrsztk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvyqftnx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtpxpcmdyn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtkirqgbkx.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gtsbbtakws.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gtebfqnngv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtpyjgejbn.html

[A03] 常量定义
来源：http://dali.yuanzhike.top/Article/details/gtmxjxoqxy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gtldpstuyx.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtrzzatszr.html

JS:   const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gthgqctpgf.html

TS:   const PI: number = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtgxvfgacw.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtadvflght.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtnvyuahjt.html

Ruby: PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtdtsdqtqe.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtvzcxxndy.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gttoqqkbxc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtufvxnxym.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtrnxegyng.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtvvmqizli.html

TS:   typeof x; x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gturgrfmha.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtfmqrbagd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangdashe.top/Article/details/gtkwhaiigz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.9152youxi.cn/Article/details/gttvwkjlyx.html

C#:   x.GetType().Name; x is int
来源：http://dali.yongpay.top/Article/details/gttuufqbus.html

[A05] 整数除法与取模
来源：http://dali.yuanzhike.top/Article/details/gtfspethdf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtiyjnihsa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gttoswcfpo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtjilyibgt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtelgbygpw.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyrvctdo.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtofdjesqu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtgkewfhfr.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtaadhjyjf.html

[A06] 字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtcpcbiyyc.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gtecdvqprm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gaohongyu789.top/Article/details/gtxgtzhvro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtxkwotmuj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtweydvmtl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtzjqkftsr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hfpthk.cn/Article/details/gtyhgyhfli.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtezztwnsi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gtyijkqihg.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtudgydmfy.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gtgcxqabfn.html

PHP:  (string) 42; strval(42)
来源：http://dali.ehwqpu.com/Article/details/gtugesedgw.html

JS:   String(42); (42).toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjetjlver.html

TS:   String(42)
来源：http://dali.quarkkingdee.top/Article/details/gtiuoebkkz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gtczhuvljj.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gtuaeabeao.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gtptxnnbxu.html

C#:   42.ToString()
来源：http://dali.hysaishi.cn/Article/details/gtxzcqufsx.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtkvjilrmz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtnmcelpks.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.kuanghao11.cn/Article/details/gtlwozdunw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtoxcfuprm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtayvuqtpo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhyznbfq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gthjqvkmav.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqljmolvg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtofioiesq.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gtlnkawsej.html


<!-- 参考信息 -->