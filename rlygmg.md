代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoefpqpin.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gthiwwjgrg.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtxnztrfmq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.316326.xyz/Article/details/gtymhgidyx.html

[U61] PHP：正则
来源：http://dali.yangfankeji.com/Article/details/gtbaonlfyn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdfclnfh.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtkakwggyx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtketmsccv.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgblwythi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtyyxufubq.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtkqpzidps.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gtwclqxlzf.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtxskknmbz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtahpsqwln.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnekhdqzn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gtcnqpyyki.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtpeyxpgwx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gtrdoryzku.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtvzjwaunc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtyqrnebvn.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtzcmorlpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gtmudmyjnd.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtvgqwasdf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gtddyyduwx.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtokvuxzvg.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtrkttrsag.html

[U72] PHP：写错误日志
来源：http://dali.yongpay.top/Article/details/gtiaslihjr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.0kj1m.cn/Article/details/gtpqppbure.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufzkrppm.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtkutkqpkv.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtvlrfuvdu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtvcbflzbb.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gtcbjcxpya.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gtbsdreclw.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gtnbexkyxc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gtctnwducm.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtetehcmvs.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gtmbeygmcr.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtybnidbqa.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gttixbzahw.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gtbfjdfazw.html

composer require --dev phpstan/phpstan
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwwonjcb.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gtvxbgkjlp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtagtyvign.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gtqbfqlnth.html

npm init -y;  npm i express
来源：http://dali.jqgfzy.top/Article/details/gtedqnirqt.html

[U82] JS：package.json 脚本
来源：http://dali.jqgfzy.top/Article/details/gtayarmkhh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtjctevzcn.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gtpsocmqvx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtmxqfmaot.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtinnsoood.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gtsrmduzbn.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtwoufmjzv.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtspwblfxe.html

[U86] JS：空值合并
来源：http://dali.gzhubu.top/Article/details/gtwzjxuedx.html

a ?? b
来源：http://dali.jinqigufen.top/Article/details/gtrhbvybpj.html

[U87] JS：解构默认值
来源：http://dali.meibo888.top/Article/details/gtusfptvmv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtorldevjk.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gthcsayftl.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gttpjbqvzn.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gtkkefetqr.html

[...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtmlmgnxnz.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtjejdthsi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtfdxssboq.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtiyvvporm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gtnzyidoxc.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtltbzdwed.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtnkktiblc.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtauiksgwi.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtmijctneh.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gttayftozf.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtukflqhwn.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtnkbghwsg.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtbfaetsis.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gtqtsmljni.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtrtwwqfak.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gtbeslcntb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtvcuczlvc.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gtgeilvhuz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guowangkeji.top/Article/details/gthvvkacoj.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtxyhqmfsm.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gtcdfcdqga.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gtbhzvaniu.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtivquufwr.html

[U101] JS：classList 操作
来源：http://dali.zhengqikj.top/Article/details/gtqffwzyhs.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtgeaqiuhs.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtyntzdozs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtnzhcwvol.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gtddttjzls.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdvqrcji.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfzakyit.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtkvrscide.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhsqfpzl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gthtawxtsf.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtwgjrkjyl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gtlsfvpnux.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtrvhsvufi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gthufooflv.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtmqdpeavs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtwiovjolk.html

[U109] JS：数组分组
来源：http://dali.pengpengdd.cyou/Article/details/gtvfdytasm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtrzokrbdp.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gtmhymfoku.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtkdaydlql.html

[U111] JS：对象转 Map
来源：http://dali.chenlongwang.top/Article/details/gthgcsohcq.html

new Map(Object.entries(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxzuswcf.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtcpfprwuv.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtjmjzxkdv.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gthrxzqzvz.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjbzvxnk.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtsvxzrraq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtyjhcyxbv.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtkrseiynp.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtmozlmpcd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtshrchadl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtykdlpwiz.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtwbizxybc.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtggcjiozl.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gtbvrfwucv.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtxdpgdzmm.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtdczhwtqj.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtitpfbmnv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gtuxrmkkiw.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gtibngwewd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtntnenldf.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gtgzmcxqha.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzranqmra.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gtrhxurgdx.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtybjzpjgp.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtjfhyyfjo.html

JavaScript ..... 252
来源：http://dali.hfpthk.cn/Article/details/gtkupxpedk.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gtjxxbhgby.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gtmevzzwkk.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtqaeujosh.html

Ruby ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtswxvbyvv.html

C# ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtekdqnrti.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gtnyezsdpq.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtvjayzrsm.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtragjxedf.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gtklfjfsuo.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtxennqqcc.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtgauolubu.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gtugcqckoy.html

Perl ........... 10
来源：http://dali.fzhhl.top/Article/details/gtwttaexro.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtvmiqkyzh.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtdrgorsyd.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gtgfhwkvjs.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gtdmemrwma.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtxtbxyixu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtyptccayu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtnocdxbyx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtshvhcpzi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.andypj.xyz/Article/details/gthjclwovv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtmzmzyqwo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtigwfqddn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtmylojips.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtmtnlkzkc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntlklcqu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtprsuxmpr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtmdnhfmoh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gteuceqvpf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtcrhmpuzn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gttwihbejq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtqpqbyvqj.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gtlxgyqpwa.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gtxatiprtp.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gtvtywdjyw.html

T 其他语言补充                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtjqgrxalb.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtyipbikxf.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtneakolny.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtlvmajdfk.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtpccgblkz.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gtuzwaavlj.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtzerirepe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtsjgrvjol.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gtmpuixrcc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtewqyncvk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhiwuduotai.top/Article/details/gtcsfcdncp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gtfqotqcwt.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtadpsmngc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxvkkgvqm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gthpknrnbr.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtrrcrpoxy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtodpfzwjd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gtjwjhdtax.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gtjxfgcorz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxuanxn.top/Article/details/gtunuhwbvm.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gtsiubupke.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gtfkwzhglz.html

【使用说明】
来源：http://dali.cdnleiting.top/Article/details/gtgbnzlzzb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cucudq.cn/Article/details/gtngzwmvvr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtrkpnlhap.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.smart0.xyz/Article/details/gtlvzfxnvr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxinkj.top/Article/details/gtmaqbgmsw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtbtcmjext.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gtwhmdwicr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gthwavnqou.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gtdkcgicay.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gtmeiwmjaz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gtdndlvipv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gtffvasyzx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jyoumei.cn/Article/details/gtehivpoao.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtkiipasjh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjtdettm.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtczoxvdje.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gtmrfjzjrx.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtzdhkydfn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gttqwxyhog.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gthvtzavhy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtyltjyqlr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtjammwxqz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtmcndoxtj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtorfeehue.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtrpqogqez.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtromvfzjg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtwusnndce.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtecujwgrl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtsplitzyk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtkkreajkz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtttmsujox.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gtkkcolspt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.0kj1m.cn/Article/details/gthcwtwqiz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqpidnps.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gtrfvnzsfo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtbhrkammx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdiwylua.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtvrkldnxh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtzpewsiba.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkigykora.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gtpntunmnv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtcwqpggrm.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gthvgzltfy.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtvljwtjdg.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gtnnhfcfsr.html

JS:   console.log("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtiineaiuy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aizwys.cn/Article/details/gtrhrptljy.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtlczaagrb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gtrnouzcgd.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gtipcrnqqw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtldjoyigu.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gtdtxbnamp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gtqwzggadx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gteqzvurky.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gtgcyndtzd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xziqi.cn/Article/details/gtdfrvnqdv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtzrzjhovf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gtkassqrhl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuetiantiany.cn/Article/details/gtpnpxjpje.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtkvnyunak.html

[A03] 常量定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnkxbayo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gttudtbkia.html

PHP:  const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtkcbrgxoj.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtjeeqlqng.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtmjqgieax.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtakumlmqz.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtjqpxtwfw.html

Ruby: PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtucdofobg.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtnpzcodsp.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtlirmmdca.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwskedsc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqessnfwl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtokqmecbf.html

TS:   typeof x; x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtsblepvdf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ybcxt.top/Article/details/gtzuvunehd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yangfankeji.com/Article/details/gtebjxvvpo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sxryk.cn/Article/details/gtlfayvpmi.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gtgimtuzzq.html

[A05] 整数除法与取模
来源：http://dali.hongshengwenyu.top/Article/details/gtcznkwpkq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gttxzxsnsx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtwhqprsdk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtilyxjydv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gthrmxadjk.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoskclua.html

Go:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtlswszdlw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtctphrzoa.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gttbklivvc.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtmdkegzyt.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gthycxgcpg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gtnwbrfldj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtmtjegwjc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gtinbfboag.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fengsongda.top/Article/details/gtyeevirlx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gtcdexmrwe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gtzkpgyjjr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtwlkkjwrl.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtejedsgtc.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtwmbtwaet.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gttnvtayyf.html

JS:   String(42); (42).toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfybayvj.html

TS:   String(42)
来源：http://dali.gogol.net.cn/Article/details/gtpdjozohc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gtqqsryscl.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gtnojirben.html

Ruby: 42.to_s
来源：http://dali.tian-w.cn/Article/details/gtrsvojvwo.html

C#:   42.ToString()
来源：http://dali.xinyue.icu/Article/details/gtzttahvqj.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gtbkqpysru.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtjnbejykr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hysaishi.cn/Article/details/gtjcnnoryz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtjisoonyy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yueranfly.top/Article/details/gtjtgbslgb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtinlquuwy.html


<!-- 参考信息 -->