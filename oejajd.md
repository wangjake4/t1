代发 wailian999

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtteyqehxg.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtfhdvyzkp.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtchrvcdtm.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtpcpatdbc.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtcfoagpcc.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevrjlbyy.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtufdlewjz.html

$obj?->method()
来源：http://dali.yj20258888.top/Article/details/gtuasziqby.html

[U55] PHP：match 表达式
来源：http://dali.aizwys.cn/Article/details/gtavxmsylp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtzliulukk.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkilixum.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtezruvizs.html

[U57] PHP：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gthhpbsoap.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtzkoeuuro.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtnfizntmm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuanzx.com/Article/details/gtdzyfosvw.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtuqnqreaj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtsmhpwvux.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gtmvrbfmcy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.meibo888.top/Article/details/gtinupuysz.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtwuqqaasz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtzrivvrni.html

[U62] PHP：日期对象
来源：http://dali.shzxlz.cn/Article/details/gtovplqupd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.kuanghao11.cn/Article/details/gtauflksci.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtryemnxkb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtkuqhqair.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gtcihiagds.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdddvwgw.html

[U65] PHP：会话
来源：http://dali.zhixingplan.top/Article/details/gtkayalccx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpgrjfysf.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmhzpabs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtarzwexfm.html

[U67] PHP：处理文件上传
来源：http://dali.jiagoushi.top/Article/details/gtoamzsnas.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gtcichtrap.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gtqfjnbdxd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtsjecrbym.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtokhhzhko.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtydcvykfg.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtksxngymm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shuidangran.top/Article/details/gtarewyswz.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtxlhmdcyp.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gtppwvokou.html

[U72] PHP：写错误日志
来源：http://dali.iojbl.cn/Article/details/gtqisuxzln.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtpxczyqpy.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunzuqxbt.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gtwuqccxws.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtufrwbfsl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtnkvoghov.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtvtfcabff.html

composer require psr/container
来源：http://dali.jianghu66.top/Article/details/gtdazwzqtc.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gthpodvzcp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtcivlyape.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gtuchtesjs.html

composer require twig/twig
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfdxuqnn.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtndbmijzh.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gtviksvwgd.html

[U79] PHP：静态分析
来源：http://dali.fzhhl.top/Article/details/gtmgammdax.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtzwekhchy.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtbwnqvnwk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtzrqseybl.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gtqciiphms.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gtrxiuvufu.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtupzakwas.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtmjlebest.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtmyqyltjn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtgcbpirlg.html

[U84] JS：CommonJS 写法
来源：http://dali.ydzc1.top/Article/details/gtctobyxff.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtsqucawyu.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gtreohiqmi.html

a?.b?.c
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcwpcbgx.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gtejbyfnxu.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtsgoogpew.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gthlmjelfs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gtenjyyclg.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gtkshybbkz.html

{ ...a, ...b }
来源：http://dali.ehwqpu.com/Article/details/gtxxpxfdnr.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctruemgd.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtcmeijyor.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gtdwauotcb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtsvztbzeb.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gtpdqlbjfx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gtdkseasgw.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtprwsxkmu.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdviacwle.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtlszkmoiy.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtsrwjlnqc.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtlwdpmcpr.html

const double = x => x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtklvsjgmt.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gtobkknsbk.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtvfwupein.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gtqaizgdvn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gturxgjrqm.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtdxqbqjfv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtwhkfxqff.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyfhyiar.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ivvv.top/Article/details/gtjnlkfgam.html

[U99] JS：事件监听
来源：http://dali.jinqigfzy.top/Article/details/gttodvuzyd.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcudbcoq.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtssadocbi.html

document.querySelector(".item")
来源：http://dali.jinqigufen.top/Article/details/gtkprrlpzi.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtbkozqlwr.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtegfkbkcs.html

[U102] JS：本地存储
来源：http://dali.guowangkeji.top/Article/details/gtdslxsnyn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gtpjqzychx.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gtbnyutxiv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gtgmwkqwsf.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtlzajnyhs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtdcbvpqrb.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gthhxwbajo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gtnteccjtg.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtcjggwiav.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtvfvpxhpp.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gtqhpefuja.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtjsjrlgmi.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtwssaqzxy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gtkkegwuqs.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtxchewkil.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtfnffnosd.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtfysnlzsy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gttqimsobd.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gthwhbmvkj.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gttwlgrcoc.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gtrrmscazk.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtbupmzbnj.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gtvochycyk.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtecagcytk.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtapjronip.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gthxqxghll.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljjkwoxz.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gthtonryqu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gtkghbxaud.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtuakfjimx.html

[U117] JS：单元测试
来源：http://dali.havefunace.top/Article/details/gtkkondfak.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtfpjxfilt.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gturmzxwdf.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtnxmbupxi.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gturoprpah.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gtuyjcpocf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhnbvrpd.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtsboifaum.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfbkqoayh.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtqwafujgo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmtrhscbr.html

按语言统计（条）：
来源：http://dali.yj202588.top/Article/details/gtabgthgua.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtfygxdfky.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gthcflyvbr.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtjobgwuyv.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gtvywoaoze.html

Java ........... 212
来源：http://dali.dashuyun.cn/Article/details/gthzbyxrmn.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gtuicxalmn.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gteuzmcyyp.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtnwnnrudj.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtydpbquak.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gtqqvbhdzg.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtteepekcw.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtyazqszmd.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtalglyxto.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtrhhxqqoa.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfahmxewf.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtbnnjpqnd.html

Scala .......... 10
来源：http://dali.daxiang520.top/Article/details/gtjpdcnncn.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtfdidbwcb.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtekioykfs.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gttcgevftp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwouwcbr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtjjryxhwl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtjjhkgeiv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtzfoovrfb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtbtrvlxvx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtiyxifnsl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtisbxcvec.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtgiegnhmx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtqldknklc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtewdnirzf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtfnejltxf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtcwedicgh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtllrqcayd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqwjzdif.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sufxvd.cn/Article/details/gttekbboes.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtixsvhsxv.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtgbtoqsjg.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtscooevfn.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtuibwixhf.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gtaakvmqct.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gtampimdmc.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtqpbtnrhv.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtnffpashg.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtldyfznmi.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtartybozt.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtugktklsc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gtuwsjbktr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gthsufyiow.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtgakpdgve.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwezfoofh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtsrheqzvo.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtbitbalro.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gticrpvyzf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gtiypvtnwn.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gtnbgcucjv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxteesmjt.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gtoxpotbmc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtgmjihluv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtmvginich.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gtlojawqlk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxciqkrk.html

【使用说明】
来源：http://dali.gzhubu.top/Article/details/gtjeomofpz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtjktundsl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pycfn.com/Article/details/gtzmunkbwp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtozhkotyt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtyaijqbww.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtitaareqx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtmilmwdov.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gtahbrimeb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtuqhofsug.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gtuewazcpg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtwxkbjdrv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtdjgnywul.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gtzportswu.html

【文件统计】
来源：http://dali.hnqzz.top/Article/details/gthlycvsnf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtwukdkjli.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtbifgtqgy.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtjwftfhzy.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gteyltmasv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtauccvgip.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtncxayzpu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gturytholy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gthquobrkw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtswjpgynr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtkursceee.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtmogfsrdd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtfwrzyvzx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtfbefgebb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtdnzzkmkl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtlzhepgqv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtwiwiwleh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtjjkqmqqr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrfpfhci.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbtirilf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtkwfwhqrh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtnvncrkyr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtukuddoqo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gtrdvphuot.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gthlmuiyhr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtyerdkkuu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbhvqjdmz.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtradkjtyt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwnqmvvfo.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gtkksaceoj.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gthxjkrpwe.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gtwtdjgxmw.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtnvovosci.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tanke756.top/Article/details/gtogncvqhs.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtxincqeyr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtjxwgpgti.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gtlwjljsnu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvjakqvs.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gtcwxuqdjr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnqzz.top/Article/details/gtwxwqjkhg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jianghu66.top/Article/details/gtfltsyzpw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.andypj.xyz/Article/details/gtosymwcff.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhengqikj.top/Article/details/gtuqihhzvm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtbdjobjzp.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gtygcntbnt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gtixewwloi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtpzjvrtkp.html

[A03] 常量定义
来源：http://dali.xinyue.icu/Article/details/gtfpopzene.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtwsmtollx.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gttrmjvqcn.html

JS:   const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfshezsn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtljaxxyrh.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtwrtffaze.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtliuehplk.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtpsbtgqyb.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqfxnppt.html

[A04] 判断变量类型
来源：http://dali.yuxming.cn/Article/details/gttmnuncxo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gtndaiqooj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gtrzeamare.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtttzmgmhh.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtzquqnttn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtusccwuxe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gtdofgjnmz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tanke756.top/Article/details/gthlrqjsqe.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtjtlqcqsw.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnjziqxq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cashguo.top/Article/details/gtihgimhah.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzadgzgi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtdunmmtah.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtuslqpwdo.html

Java: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtfvcqffub.html

Go:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtblonbsvr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtlptintgg.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtmxkpzdbz.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gtfvxbawcm.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gthbuibciw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gtfdzketac.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtbstjstzm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtfdtbtpsk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fengsongda.top/Article/details/gtbwofuggi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.havefunace.top/Article/details/gtghkuvpvq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gtmgptdyts.html


<!-- 参考信息 -->