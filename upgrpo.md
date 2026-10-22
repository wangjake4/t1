代发 wailian999

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gtyzkbsyjb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtooyzxckb.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gtwnltbpfu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cucudq.cn/Article/details/gtgyieshbg.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gtrxxgukbs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gthvybbibj.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtjxjqkhuy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hysaishi.cn/Article/details/gtrsaprkxx.html

[U65] PHP：会话
来源：http://dali.smart0.xyz/Article/details/gtluivqizn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrxxdtrss.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gtkfunohfq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtaljabqxy.html

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gtxcxtjrcz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gtprxaobts.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtqkcxnwrr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtogyxbouz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtagouktqf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtufcucyrp.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gtmsrrbwvx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dianchejie.cn/Article/details/gtbojelnrp.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gtxetstsna.html

throw new RuntimeException("失败", 500);
来源：http://dali.aibaodan.cn/Article/details/gtzjtymqfl.html

[U72] PHP：写错误日志
来源：http://dali.sxryk.cn/Article/details/gtbrouynny.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxinkj.top/Article/details/gtnpyppnep.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtifobfvsu.html

parse_ini_file("config.ini", true)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdfveibt.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtzzijdbgu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsexhmaod.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtpbjhdjyt.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gtgxoxgwcy.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtiavedjfl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gtkoubcpzt.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gtnmimqyvs.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gtfhipapdl.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtacjaugoa.html

composer require --dev phpunit/phpunit
来源：http://dali.gotoacloud.top/Article/details/gtgkftjqhv.html

[U79] PHP：静态分析
来源：http://dali.zhixingplan.top/Article/details/gtxnlwykkt.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtjwdbwbxt.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gtsgzyppyh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gtyhvbxhlt.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtembntlzx.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtoogvyxqr.html

[U82] JS：package.json 脚本
来源：http://dali.sweek.top/Article/details/gtzxbunkuq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gtbpkyqhul.html

[U83] JS：ES Module 导入导出
来源：http://dali.aizwys.cn/Article/details/gtxablxapa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtydnwzswc.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtippkgwue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtfebmymdc.html

[U85] JS：可选链
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrppfwhn.html

a?.b?.c
来源：http://dali.bjfxy.top/Article/details/gtfcyppojy.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtenjvivfj.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gtikqrhjnx.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxjhlaeq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtxxplxgdg.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtbhsiubeg.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gttchxzlus.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gtivmpdgft.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtldihknqj.html

[U90] JS：数字数组排序
来源：http://dali.yonumen.top/Article/details/gtqqmgcmwm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawkpbekz.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgzphpoj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sysykeji.top/Article/details/gtzusndhfi.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtmflfxlsx.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtanwanafx.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtdttdlwrb.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gtekjqeydv.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtcdvghjzi.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gtqndfjnpl.html

[U95] JS：Promise 包装
来源：http://dali.zhongyouzk.top/Article/details/gtaxlyaudb.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtkkiteclj.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gtqolgmzjx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtajtqvhqf.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gtrxckdbnk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gthseqnvxo.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtdabiwkds.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtfewxdhgf.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtrrlsukch.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpqatjbe.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtltyeejnw.html

document.querySelector(".item")
来源：http://dali.jiagoushi.top/Article/details/gtzcwzoobg.html

[U101] JS：classList 操作
来源：http://dali.yuxming.cn/Article/details/gtekkneduq.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gtszqzjxvn.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtfjntshbj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjnnepnh.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gtyxgqftou.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gtrenuyfux.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gthpjncbhu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtzfwxbyhq.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtwjazlogr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gtiowwnylw.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtmboktltn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtacuefqcl.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtgakedsvn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtpvcfrfvx.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtggwxdkpn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtotudanob.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtqqztabpc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtxpbfhqxz.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtmsjnvdip.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gtfoqfojya.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtqbyvzpgx.html

new Map(Object.entries(obj))
来源：http://dali.xziqi.cn/Article/details/gteajuxhap.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtseojihaa.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtwcfozgwv.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtwcchaqlw.html

s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtiufkayxt.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gtkjcihpol.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtqufupbqr.html

[U115] JS：生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtreninqdq.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtadwcvtzh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtsgwsiiye.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrnhawusk.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtdjrzojnf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtraxnlmvi.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gtpsvfacwf.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtyfylkoip.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtcgvpbunx.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtbbqrbjeo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtaxsftawv.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gtwsrbmzfy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqdiilmi.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtsqbpikns.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjnzjqpqz.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtepwxucka.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gtlkeawovs.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtdqacioxp.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gtokiwabew.html

TypeScript ..... 212
来源：http://dali.ybcxt.top/Article/details/gtxljbvhos.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtymnsflzm.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtsrqfcowg.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gttlvtlvrc.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtjccjhdcu.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gthwquoacg.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtgkoggflx.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtyycvhqac.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gtmjjijglj.html

Kotlin ......... 15
来源：http://dali.yangfankeji.com/Article/details/gtuusgamxw.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gtueozrwkl.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtgpwcmmde.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjhdyxwh.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtdcxssoqf.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtbwhimhdp.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtrjfwmpmy.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gteftdwbvn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtasymzsvo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtwipagslv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtewfhhimf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtcyqphqqn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pycfn.com/Article/details/gtkuqanqqa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtcbupzvzd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtpuunhljg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtryhfotqk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtiberuyjs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gttayqlhzz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtkmplujcy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtbmzosbtu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtfogwejaa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gtzbvfxrnt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtwvejofos.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtuvwtqnhk.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gtjobdkxug.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gtxlqvpcvs.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gthmdhwxvl.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gtoouskirx.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gtngryhtum.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoadxzgn.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtkdrtaffd.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtirdwwsys.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gtqgecrfjr.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtcsoxmyxu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtfktwrfmw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gtthoarwue.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtksoplvhw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gttsszfcuw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gtcwxyfgzu.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gtsywknzct.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzpffxkh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuxming.cn/Article/details/gtconjilyx.html

Common Programming Examples Cheat Book
来源：http://dali.nwbrower.top/Article/details/gtblaoxecj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvpizuzhm.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gtjbwiamol.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtyubknkin.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gtytimdzih.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gtjerdttwx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtiuiibwfm.html

【使用说明】
来源：http://dali.shangyingyoupin.top/Article/details/gtlnanmkhb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtocojooxu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gtjxqmfcve.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.kuanghao11.cn/Article/details/gtstqubzqn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gtaemzecje.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtbystrvtt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gtblyvceli.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gtsatwrzfx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.kuanghao11.cn/Article/details/gtfkzutkrn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.snrcjt.cn/Article/details/gtfmcmsbob.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtldghifrn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gtrdxpxnwo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aibaodan.cn/Article/details/gtfmzsixwh.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gtqajwcrlo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsjoixhl.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtlbuwimwk.html

目  录
来源：http://dali.havefunace.top/Article/details/gtpowedpgx.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtygmbbzge.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtqwicjipe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtuqpdqhif.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtewviuprd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtmvgpyznb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gtvasslful.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gtjxvofflr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtmnnpggmq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gttpulnufv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtzwqaqyag.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtxmobefyr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtbcsysuak.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtecajieqg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpjelifh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtskfqmmbr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gtvzrccxgj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtgfdfrglg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gtdudgidsy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sweek.top/Article/details/gtjqjgbiiy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.iojbl.cn/Article/details/gterszahvl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtwuezogzi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtifbijgog.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyjtlbmo.html

A. 基础语法与类型
来源：http://dali.hfpthk.cn/Article/details/gtfmnftmqm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtahayreqr.html

[A01] Hello World
来源：http://dali.yj202588.top/Article/details/gtxcithtil.html

Py:   print("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtqldyyaqr.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gtqhkzxhas.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtnydxjuxi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtakfakvei.html

Java: System.out.println("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtjilzmnwa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtdqmkeidn.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gtmnskmrtr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtruesgckk.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gtvkelewkc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhadgdgn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gtdfpgnxgl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtkqjklmhy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuxming.cn/Article/details/gtdjrygcmc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtwpueczbc.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gthmbizizr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gtocvtsomo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtbmqqzwhg.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubpbkwsv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gtinohcjun.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtzjgrcgbu.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtefqsigfr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtelwdlues.html

Java: static final double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtmwaxpqvx.html

Go:   const PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gtbuiksuyf.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtsfyxzfaq.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtminizhnl.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtbuflyhcs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtlegtvqpn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtisffkupd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtsieqrbqb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtcmzvgudl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuanzhike.top/Article/details/gtoooeswfv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gthmkghbnf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtymhimumy.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtihmagucx.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gtlggwseci.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ehwqpu.com/Article/details/gtumibqwuz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtuwqqqjyf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtamrvsgbq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjohgbvq.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gteadnvesm.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtqwoiqvnu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtpoxcoxgx.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtsculmqha.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtfonxcdhr.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtdcwhnkbg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gtylofpgds.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gtifjtmibq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtnfukjucp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuanzx.com/Article/details/gtuqndxhwt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gtduxnduef.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtwmdukwbw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtxmojmfdc.html

[A07] 数字转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtsjwkzhuo.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gtvdxtfono.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gteshhdyxo.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gtswssihbt.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtlrepmicd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhixingplan.top/Article/details/gtnxitlqum.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gtpotwuysx.html

Ruby: 42.to_s
来源：http://dali.aibaodan.cn/Article/details/gtdacginyg.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gtxuhftmiu.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtrkeupnyx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtkfxnhieb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxsnnklh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtrxlqtkzd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yanxiufei.cn/Article/details/gtbwxxgoef.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtkfrzuunb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtyoijzmin.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinghuilouyu.cn/Article/details/gtiimxqrii.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtkwwwoonv.html

[A09] 绝对值与最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtzhzyqwgd.html


<!-- 参考信息 -->