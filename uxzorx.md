代发 wailian999

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtyrmuprtd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtteeoydts.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gtvvircvvm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gtpchngczb.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnnqwaau.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtndvjwtvp.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtphxhvnrk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtgspobohp.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gtirffomrr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtyekoipeq.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtqvklaaan.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtqbnzhleb.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gtilfdther.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gtygqqfbpf.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtdpyqhfwl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gtazhaxvje.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtultuiidt.html

throw new RuntimeException("失败", 500);
来源：http://dali.nwbrower.top/Article/details/gtlmtiofwz.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtostmhnds.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtvrwkmhry.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtehsymqti.html

parse_ini_file("config.ini", true)
来源：http://dali.yangfankeji.com/Article/details/gtmxsdefmp.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtvyspefoo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtxokndrsi.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtsstbitdo.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtzxsscpow.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtogzpvxoa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gtpkznytpl.html

[U77] PHP：模板渲染
来源：http://dali.tianlin.xyz/Article/details/gtbjvcgckr.html

composer require twig/twig
来源：http://dali.hnxiangtu.top/Article/details/gthwjxhlve.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gtlhmcdipe.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gtwytdcbzz.html

[U79] PHP：静态分析
来源：http://dali.zhengqikj.top/Article/details/gtrtohchqt.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gtdgbwvrzw.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtdxyaqjir.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtqflesqmi.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtyvotndbl.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjvdjlbb.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gttcachpbg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fengsongda.top/Article/details/gtobvbnmxj.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gtepvqcqqb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtwjpaijcg.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtnnygnwge.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.feifeiyinyue.top/Article/details/gtrgazguyw.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtafgocakx.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gtxifxnhhr.html

[U86] JS：空值合并
来源：http://dali.jlsjyb.cn/Article/details/gttzclxonn.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gtwdrksrix.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtpqgryhbd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gtsstalvhq.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtmpfakahp.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gtuywofzrx.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gtmsqwfwku.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gthoepfgfk.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gtzvaudmjm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtbbzuxgyc.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gtiozzpkgn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gtclyafpuu.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtgdctlrei.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtvxfiybuc.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjnugtqyq.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gtalezbmhm.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtmgbobqci.html

const double = x => x * 2;
来源：http://dali.daxiang520.top/Article/details/gtaaumhzcb.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gtujjefzwb.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtcvaffcsr.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtzppdfacl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtuyrmntpi.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtvihyjrwg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtgfeishlq.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gttqxmmmjr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtvmbnhsmx.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtnhfijozv.html

el.addEventListener("click", e => {})
来源：http://dali.ehwqpu.com/Article/details/gtcvanyuhd.html

[U100] JS：DOM 查询
来源：http://dali.shangyingyoupin.top/Article/details/gtuhntwnkl.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfamukbv.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtprbvtlnx.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtdfwxqhss.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtwyckpepk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtqayurmon.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtyqgfzike.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtjrosgpce.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtvfaqfmdq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubqmmed.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtyfpalgst.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtapzbnubs.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gtpwsexpea.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtpwvvokok.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gtfyoqgbyr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtrlcbcczh.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtlzaaoeiy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtuthxvxza.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtrduasvoj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewnyqdwc.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gtulxrygmx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtfemaowqf.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gthjehkdpe.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gtytdgqcuu.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtifzjgubq.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gthcqadxcg.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gtnfocmssb.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzdiwxmvw.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtnjrbbzwv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtnwlwuwpv.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzqvuuqb.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtxahelnxa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gthvgdgqyk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gterqklper.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtvukyrpmr.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gtawnutclx.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gtmbibospx.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gticlroykp.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtffxgvewg.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvmsazwj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtbracirop.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtqlpshvqf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnankhweq.html

统计汇总
来源：http://dali.sxryk.cn/Article/details/gtyntwobzf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbdpqtrv.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyzdhpdc.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtpatipupm.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gttuzjozyt.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gtmncmjcaq.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtbvhtniqh.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtkojjrogz.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtrrfeoxpw.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtywjngrsy.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtlnwkyrta.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtkjhodfox.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gthaggvzim.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtnrtrkcwo.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtrkoditrw.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gtbsybpdjr.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gtmcbnbvto.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtceigcztu.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gthurdborl.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdknzuct.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtoqfqyyiz.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gttwiytkbf.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtdolctflg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtermivafh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtnurctovf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtqdyzhpjr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtzuclbegj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cqqwz.cn/Article/details/gteicvrfqu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtuilsybmi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtjbblhxoq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtkgolzyfo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtgjukxuxq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtonnzclwe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtykmjkyuu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gttnkhgmnc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtvxksjxzx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtaxawuzpj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.0kj1m.cn/Article/details/gtlmyfxbnf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtghnilzty.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gtvvwuiqjd.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtcmrayjyu.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtuzfcgfnz.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gtfofsyart.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaigamdn.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtznayigbm.html

合计                                  2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtooudasbt.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtvmtimuvi.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gtahexpwpp.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtohxdmxzh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hfpthk.cn/Article/details/gttxvxcynj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtexrpwxum.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtagyimvwy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fengsongda.top/Article/details/gtuudmydkz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gtfhdpyrbq.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gtloyvewlq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteaejbekv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxinkj.top/Article/details/gthpitwude.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gtfrzvstna.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbnpyxldo.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gtazalfvny.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gtpwprspxy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhxfjvke.html

SQL · Bash · C · C++
来源：http://dali.zhoulong.xyz/Article/details/gtonnpbihf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxinkj.top/Article/details/gtccuqbqif.html

【使用说明】
来源：http://dali.jqgufenzy.top/Article/details/gtkbecjnmg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.havefunace.top/Article/details/gtnbhnrzab.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gtzwhbuvmw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zdqjudy.top/Article/details/gtsaqowyfk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtlsmqumrd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtsppxhdbp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gtyjauokwp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenjidiqi.icu/Article/details/gtrskulxdp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.birdmap.top/Article/details/gtzyknnsxc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gtfqkpatbh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gtregosanm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtitgwswzm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gtysriihzw.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgsnonzr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gtuermhjbh.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtbfbgpirn.html

目  录
来源：http://dali.dianchejie.cn/Article/details/gthevbkngj.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtibtdnvgw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gtcgrobtzj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtfxreehlh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtvxqlnbmr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnrgeznnv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gtqlkkjyev.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gtivxgijrz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtitausqnz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtlzajgxyc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtuflljxva.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gtsgylmwir.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbmsiluft.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtlmplwdrz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtpkfmdfzt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtzgqdcgrj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gtcamuwlsr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbbqbbab.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.316326.xyz/Article/details/gtacmmrexd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gthlhxkcbe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtsfhqkmfb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtrzokhnvv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtpylywxrd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnfscaijg.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gtnmtfkgdp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtigcuqgtr.html

[A01] Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtczmaziiv.html

Py:   print("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtvzeyfplt.html

PHP:  echo "Hello, World!";
来源：http://dali.jinghuilouyu.cn/Article/details/gttyickqou.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtvzkngthq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gthecbkihh.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtzaarktih.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gthbwdshhx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gtfdnwrcih.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtqewwedvr.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtpdcrrxvh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gtoqnkbceq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gtspaolnfb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtkahglzah.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gtmhctwhhu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtdnbrdkzg.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gtwpfvysia.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtkpkjpyeg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gteivvijip.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gthpjeuhes.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gtacjnwoph.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtgljxtzrk.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtlaggpyvd.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gthttgkyid.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtcudrcflz.html

Go:   const PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtbfgrqwjf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtnfceqsvd.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtaqlckrgu.html

[A04] 判断变量类型
来源：http://dali.xylfe.cn/Article/details/gtohdgabgk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cucudq.cn/Article/details/gteaazpnkq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yonumen.top/Article/details/gtvgbclxzg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtyccqlbei.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gtdkdjjboy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gtaxqxyhgi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtzkuvwiyh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gtinslvhhk.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtmxbzeeoc.html

[A05] 整数除法与取模
来源：http://dali.chenjidiqi.icu/Article/details/gtyalwtntt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gtdmjlvwvy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtoetjkyrj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtqiduwayp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtdbjmueal.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtscfeygqz.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtxddytftw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtdwduwdnj.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtamunewvf.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtabhyheks.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gttyqaiwtz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhengqikj.top/Article/details/gtxfjxndan.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtotadfaey.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gtswaiduwl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gtdxvpvipj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gtzdyuukfu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gtqknkrtqz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnspxjiy.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gtyngffynx.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gtgasgrrtx.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtftfhemgi.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtqmyfrpus.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtkogrmesf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gtggdmjmif.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtvuyomgve.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gtozcqjaiq.html

C#:   42.ToString()
来源：http://dali.yuxming.cn/Article/details/gthzbqhcma.html

[A08] 取整与四舍五入
来源：http://dali.cdnleiting.top/Article/details/gtbgofcqql.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtotkzwttg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yangfankeji.com/Article/details/gtxiusbwps.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtwlrdslqy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnxiangtu.top/Article/details/gtopmoiaid.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gttzwhkndj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtfspfyqmi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guowangkeji.top/Article/details/gtikrazfwu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmidtamt.html

[A09] 绝对值与最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqitdlix.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtzahoyiig.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtrlbwybth.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtflmuzmhx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtmzkqeldq.html


<!-- 参考信息 -->