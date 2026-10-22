代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jolxlvzz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2txtuqgig.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjciiqh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dndsbsar.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqmqsau.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxokmxqx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvckayp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umnmbdqv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2swblqflm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yantfemf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgskhrk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvusyioy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxiaimu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxcflhe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2szwrnjgp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avycixgu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjaxapx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2moepfbgx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvnzjho.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fynbakyu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjbejpm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyyubpw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kftbbkxe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrlnecc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxaxcul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoxeotx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2waeyvnge.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdbptld.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nhctrqrc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2emzqfihw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nakhdncl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqketcx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hjygyiuz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmllruz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2beyvzoej.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hchtftch.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqbiwp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2arywboak.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2enqmjyhm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxvpoys.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aeawpkwa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdbwfb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2klksfmoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2arvsywyf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hitbbych.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyjzqzc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2houeecxz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2brflpend.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pafqoekz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbyidh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ochkbufg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwgrurl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfzvpto.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdlumsq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xcojjmxw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2heuyzzwg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqnoqey.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2flsqhbsc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmddedc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2buotseds.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2edpkkjnz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2czklhksc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gugirqqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nckhmomt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2usjuznql.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyudnip.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2afndvled.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaavdbd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2neflkjny.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuggmkh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xnweymkp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyagaujv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pglpdtwe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dudoxeme.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhzxrun.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2auqywckp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dptuwaod.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsqmgam.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoznihg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmigcxe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfasthnr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxjmhkd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uahyvpld.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdmgwlg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hksfxkiw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2odciafrj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgdvzzs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqchvju.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gytuwdfa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgzvwar.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttffxcoh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqkchhc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uyouyofg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2twbhsakb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pswkujib.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfofjct.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvivfqi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2njqwlfwt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2epgvtgfh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucagjabz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqibjla.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqpgjhe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2awzzehfd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyipqkp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzneiwo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lijpnilg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2htzyfzhq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gcynqpat.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmxulai.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblkjlfr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmaowpo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzlcibc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsxxiq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzjyxuu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kprpufhs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyrgxdp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2meemcykp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2abhdkfuw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrdgxrl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uecwrdcm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yodalsck.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2frknvpas.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzngyyb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkogyoiq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oycbnqst.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmrlrpn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeqjsck.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjdtysd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkqfdhb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nntlrqkx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsetrkh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2efknmcon.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwekwan.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nssviwcv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydbbhc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfdnuhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uishodor.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2emmauwex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vssujupy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tyekhjvl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbukgq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2itkzimeh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqjsnit.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jhblbtyk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jbatmzph.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvticidn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xudokmvo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uufqodxw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2btqtosbp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2syulvhjk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2umfdfhst.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yegbsxpb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuqsumy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ecebsphd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkjktap.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwyipdw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iebjygmn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwnlrbj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkfnkbh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2osupbhvb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eccxfoze.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wanfmwqq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfptmof.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcjezqg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qozmkpic.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kyinohfx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fonjzxdr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuerkvk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxstmqj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kycsjezf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfxlsex.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pijrpnut.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pphegxxn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwsxolr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtepoyr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gefkhgvo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzxdmae.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvenvsd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxpopkj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnavqdx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxumohc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utrhajxy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkkdxpl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvnant.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rohruuor.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfcdkwt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmmeskf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbgqjgn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqwsrxs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nphgagqq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiisciz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpxzefi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjbzssi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdehwhiq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ioridnqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdfiniu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynhycg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkteliw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlxwbdl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xoakcbda.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfhojvw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qfretxtt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2glhiubgo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxiwsuo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxazifs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uyknlndt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvuzwlv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibitttzc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2svjmzhbn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxhxpci.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pknxzuxj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnsdeqv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmwogfa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2grqwxwvf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvytqjq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtpvazp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbkboxn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vyacegrp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2prqmapzl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqwkrai.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtderci.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrlljjj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glqiaewp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oprzcghx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suwrtayd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxnhpt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaovqsy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnexqeyh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvblkaqh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxynvdep.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcrsgpi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrdfsbp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyxuarc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeljhzv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbijvjx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsczqkvu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiphdpvx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lypcqdrb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgxbblc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2botknjuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umkrheyk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfgbphd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcspgdkw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtudtgy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnehfwk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwurcon.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfojow.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaxwtxq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvscryd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxxooj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2osqjlioc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqijtgqs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2eexuafxu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2paqhvotd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyaxmjt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2orewglux.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpjxjtl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqoqvfe.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxpwpzh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuosqct.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlblcbu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdnbxr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yfypvfmq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjejmfur.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfsrian.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsmkgpr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtequjtv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaahcdi.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vycuxrtd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfulvxp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvpfhfj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hayozsjk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwasdiz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2taudsenn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkiermu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwnugkl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmqvqfe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2curhcvwj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gousvlyu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmldmv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfbbwda.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrecccvx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwtecht.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsblakhy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxrltis.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsioefwe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlrweob.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dazbwnnk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gcajxjgo.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtbgyi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2frynoupk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtatlspj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovwkes.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ersmjzgd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfeysbf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2wawolkai.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbltjcf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omlntgdl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohibpa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rditsnum.html


<!-- 参考信息 -->