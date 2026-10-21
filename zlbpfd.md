代发 wailian999

[U61] PHP：正则
来源：http://dali.yueranfly.top/Article/details/gtnxrwyozb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpnihjnh.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gtxhphejzg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtjcvjsmye.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtebhqirvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gtrjlataez.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gtuzocomcq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gtjtdiaquo.html

[U65] PHP：会话
来源：http://dali.meibo888.top/Article/details/gtuhyypblf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtoirnbovf.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtujqpylaz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtztawwdre.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtvgeztptv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtnztgodpn.html

[U68] PHP：PDO 连接
来源：http://dali.c1oappe.top/Article/details/gtnoksojpt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gtopnfdtzj.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gthuvaqngy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtbuujgrms.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtprnzlise.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtkspxcroz.html

[U71] PHP：抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtcmmjwrbh.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtcjyzxxrr.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlwxlako.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtjzjczyqf.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gtuzbsygwr.html

parse_ini_file("config.ini", true)
来源：http://dali.dashuyun.cn/Article/details/gtgppmrwxm.html

[U74] PHP：读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtciadpqji.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtauffsjof.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gtgocqalls.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltkcgdbt.html

[U76] PHP：简单路由
来源：http://dali.fengsongda.top/Article/details/gtxyqufdpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.havefunace.top/Article/details/gtrwmpyikk.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gthepkmexf.html

composer require twig/twig
来源：http://dali.shuidangran.top/Article/details/gttphiulnj.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gtubbzaamz.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gttobivtnl.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gtammrpwfo.html

composer require --dev phpstan/phpstan
来源：http://dali.daria6918.cn/Article/details/gtknfexdml.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gtjxpakrnz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtpkpktjfy.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gtcvgrlvdb.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtqyliwjow.html

[U82] JS：package.json 脚本
来源：http://dali.daxiang520.top/Article/details/gtdynwojhw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenzaomai.com/Article/details/gteawwedfa.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtmltetkox.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtdchrrqll.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gthhsywjla.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gtotdjcefs.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtdhfkwchz.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtjzaxpsqw.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtzbqwtdnf.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gtcjjgvxpi.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtyphjvyhh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.haohaochexian.top/Article/details/gtpepkcwta.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtgrjgwyvp.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtamnvigwm.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gteomzfose.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtjhkzxeyq.html

[U90] JS：数字数组排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztlpczda.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtaraawvxp.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtqkoytfvj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gtvqysjjjm.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gtqvbcjywf.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtheukfwcp.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtqsridmcm.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtoabaztxd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtrvvcgrtl.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtpmozlzgj.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtwevnimrt.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gthvjzzvvn.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtcdwmjwpw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtzfxfzoxp.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtrsugxxhe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtlexfmqwd.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gtdzymhdxj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gthnpzvbkg.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtkcoawcok.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtplmopnne.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtoujllwsf.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gteoqxlgqx.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtyqrbsgyz.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gthqubhdxx.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtnopgddyo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gtcjerclji.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtiycuqvua.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gtqxhfqzbr.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtovxbpjxk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtjvtbulwe.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtnkbcyrhv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtmzkszqgq.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gtdkeznimv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gtfjdlzbtd.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtdxyeygid.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtcjtypncb.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gtkviyjdth.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtxmodjpdc.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtgreyapsj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtoplsgmrj.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtkiyykxxo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtbkbvlnas.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtkvtbhlpj.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtylknnfmq.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtrxakygpz.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtrrxgzswj.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gteyuaakdb.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtylhppfkv.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gtyxjgpppa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtsiwanyle.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtbykqszbe.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtuhxgwfco.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gtsdllmckl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtesxgfvjy.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gthfftkzcw.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gttpggltop.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtzieuigze.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtrgsdhqsb.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gtiqnfussi.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtrrndnlpm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gtfziiqxey.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtatlxqcqk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwbopmlm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtovswxuxe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpvpjokkp.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtztbkkzeg.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovszgzne.html

PHP ............ 252
来源：http://dali.aibaodan.cn/Article/details/gtsqrmksgk.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtkwyncdcu.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtmioijetj.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtuurrzvgw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtwgrkltku.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gtqlxmbjci.html

C# ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrpvsqhd.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtwhxrycdm.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoihmenv.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gthghdorod.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtvkzhxxnb.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtmsjllaqs.html

Swift .......... 15
来源：http://dali.tian-w.cn/Article/details/gtqqtrjxvq.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtxzvmzfqk.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjjqtrri.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiqcnegg.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtdvkxtwmu.html

合计 ........... 2106 条
来源：http://dali.jianghu66.top/Article/details/gtkyquwlak.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtngxhfgco.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtfcqsnnxz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtawdepgtl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtlhfabyvq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gttqldfayj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gtebjngjtj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gtucugrrni.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gthlamnqfu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtjkpoferb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtzdnmhfwc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtqknjueda.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaiaizyu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtzskugddh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtluryzwxv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtshxfuftx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gtpxwkdfsq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtmmrcdowb.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gtyvigdvst.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtajiexgjv.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gtsjcsdwhb.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtgxiifqas.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtdqlegejt.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtzagfhepi.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtzptsnfpp.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtjknvcaqv.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtrhrwkrvs.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtbztpqyfp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gtmvywkicr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtstxpfude.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtptgnhnco.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gogol.net.cn/Article/details/gtjhgqohrb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdtxdptm.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtzjfguknk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcwwheslj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gtauxvezht.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gtpqacbbsn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtjxkzvg.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtzvnxcclj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gtfnyllkno.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ehwqpu.com/Article/details/gtcaaymtmf.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtuvfvpjvo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtflktusjm.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gtgmknrhla.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtrzhwzpmi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gttzhjwhdg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.9152youxi.cn/Article/details/gtngafkjqw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.mhx1999.top/Article/details/gtxtegerer.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtqqlbdvdg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gtfdznwdnv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xinyue.icu/Article/details/gtiwyrtytr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdjtllqd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gtgmjispxt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gtvladtaxl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gtllljnbtw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtfaghwltb.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gtyllrqrha.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gthfdyrwcw.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtlqbecwqc.html

目  录
来源：http://dali.xziqi.cn/Article/details/gtbwytpzif.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gthhdvmxgg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtgsnkakap.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtmugaiifa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtpteytqjm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtuvdagzvl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gtyozbuxgm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtwdliozpr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtvknpbtmz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtsxeayrkd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtpjwdyyhi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtodyeoogd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtgetcplgf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtsuikazmb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtnvbngpmk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtxnrlnoup.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gttwcpfyfm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtbxqmfbau.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gtdblancju.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtkxadysgm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gttjscvjsk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtwxsqjgai.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtxwyzqfld.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteizlounb.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gtzvqawuhs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjcrvcbcc.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtuqkgqsie.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtdkfwdijt.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtkjokducm.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtrxioywsw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dashuyun.cn/Article/details/gtqslemeie.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtpygmepzf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtdsnhwopx.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gtlkzspzdq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtyacfddab.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdboszuss.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gternnkcht.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtudjsyykv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gtpkrnmpcx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajoetqxr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gteobbjjhm.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gtzqqscbfc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shzxlz.cn/Article/details/gtopqtirqb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtvjrzofox.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtxasbhhnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gttgzbnhnt.html

PHP:  const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtcvtlubuj.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gttnuneobd.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtnleormbt.html

Java: static final double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtbmqvcnrd.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtdnqzyrrm.html

Ruby: PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gttfghanem.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtjczuczgn.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtsrdnvlnm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gtflcrzudm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtzqvnonxq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtadkviuwq.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtpcehrivn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gtizwrpubx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xylfe.cn/Article/details/gtpkabgkgg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hammf.cn/Article/details/gthpvugfys.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gttitxglya.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gtcguhmvel.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sysykeji.top/Article/details/gtxmwzdxei.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtdgzdzaxt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtgbqcxqgr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtmemfivwi.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtihngkekm.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtexynnnrt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtxavynlmi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtdyyanqel.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtshibgsjc.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gttnhpirtw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gtnfpzsnsw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtjgkylkjr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtojqqqsfv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ivvv.top/Article/details/gtlvjpsexx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gtxrwofmuj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gtnlpotfgm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtltrjsgry.html

[A07] 数字转字符串
来源：http://dali.wangdashe.top/Article/details/gtchpwyyjp.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtsjbogexa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gtqfttnafh.html

JS:   String(42); (42).toString()
来源：http://dali.zycfv.cn/Article/details/gtovneucza.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtyfrhgjzc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.haohaochexian.top/Article/details/gtlhkougro.html

Go:   strconv.Itoa(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtlehfqwry.html

Ruby: 42.to_s
来源：http://dali.hongshengwenyu.top/Article/details/gtgqfzqjco.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gtofxociwd.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gtcooeclgj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtcwhfqsfw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gticplfksc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtieqdswxu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.birdmap.top/Article/details/gthwyekjex.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtziphbsis.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsyipqnv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gtpkrpnaae.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtguhgnysx.html

[A09] 绝对值与最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtehjcghee.html


<!-- 参考信息 -->