代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drbsxkqe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbijkqo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzdgtyf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncecmok.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdkysic.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbndto.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcjxnfx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyiwtxu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkebenp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2miptcplx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooecqwcs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2megymkbj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrvkgcc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2utynebwp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mojamotg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhzkrco.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dluwzntl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtwmcpk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipezepgg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehbadzp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzigvvy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usztgego.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdbhar.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrahaln.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxbpfvg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vufnrsko.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbliqrfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2emvoprqo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacrxfq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqibkzl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sldkgbzg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjftskxk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2srfyzejj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrozpsp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iactjypn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2feroojsz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfxxofq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shyplmko.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2aacyevdf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzygxdoi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwubvza.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbzhhrm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmceuzd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgksbpgt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvchikh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieejjywm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqxogta.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lndfoxxe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aymtkpcd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqixvlf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxznguv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2csnikxax.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbfauxs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihkphxf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnjnjys.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2icikvzjb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyrzrdh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uocisobu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqpitwr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovphheit.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2juzsvwqg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwjkjkc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyvrayb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2shurztlr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2utuerrag.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2knqgikqd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yaezqlsr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnfjwta.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nuksqagv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjjymho.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ooelienm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfnjnq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2brtisylk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkminhd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmjktfr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfwswed.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsryprr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwrdjlp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlkqcps.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlzpstu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbepiiv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivesppzi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjfmigk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nppcidti.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sttekcph.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaokkns.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejabohry.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbuafvc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyrgpah.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxfcvps.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uplgscpl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuulcwi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyuqfdc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlptahq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuivbvo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqthlwj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2odkpijcb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbyifto.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrrouzw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqkjpzh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwvmkko.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxocje.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxsvmxc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlvbajb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2abzenxqn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsyztgz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaszzgi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfpndxs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvqdyoy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxslvvp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpyleka.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rldrvmjw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpnayog.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnxmcqw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnsubrt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnreidne.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pirlrejg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrqnice.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2loxezwva.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uaphkuco.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dlevcyxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaoabpv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpzgad.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbtfvyg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgcvgwh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2myppterv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ujprystw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aatxigef.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmktggf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlgiwsi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2agpsfagl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2byiqhlsm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aovlgjtv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrhxjlf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wexlxfbq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjkejqc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdsftbu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkpaeqq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2anqtdzmr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrseucjo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2edkyaqsv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2skigylam.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihycxjmr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2emtjkbvi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2plfewadf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xgimcsgu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqbsnng.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2shghepqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpimsfq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2malrnzuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsqvogj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrxkadv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjhsden.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdkvdjw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tezeoivd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xgczlmcl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2giojykcm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vklearoe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aremacho.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxcdtqu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qedviola.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zfedwfcn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvmjdol.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsuiwhi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfxgefy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2udfrcjih.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkwxmps.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzqrxjh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aetkjhnb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pypkdkhs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jwygmxqs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gfovxaos.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wwymbvgi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwcbjqq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdgujsk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kuifkbmk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhupvtu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2paaohemk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zropfgvu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyjoehc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwlgvkg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmduol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcskavkv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgxpkgy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiblpjg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdooaio.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yocegfer.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzsaydh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2oayzrnyo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rrttrgej.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2omsozcri.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fouszyef.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gsakpiug.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnzayxe.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dezaqepe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btndyjpo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdnbluv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmekcc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyuixdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbojxtia.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgnjgrc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wffflegw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnquysk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhgvvfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grwquwjf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yckqbife.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigtqux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttuimv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qotfketh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rncctzct.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2myopmvkl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2swacypxo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjzzza.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2icgduiie.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvdjzig.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcercpj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nmacltoe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2adjstahs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2coixciyc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhbtisy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqvreeo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcdfphg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwposnvy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxtcjcc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmfzcoe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qecopito.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnaoqja.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2phskwsyx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wertysoz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyxnout.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eecvppsn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eziujkud.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oculcmbf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlyohpn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nidfdhzo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjlhyg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zawqizyk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rldcsjit.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsdpfax.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzxgcvv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvwaknt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsgzrox.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdihzxyh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scecdivd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfifctlo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrpgvas.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yktufmyf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yahmjdmf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wehnezxb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dysacxrr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvsedvh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yymlonin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzotdhva.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bomfdtsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thvndwjv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmvpevy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfdsayn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqabfvf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfcjfem.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2phisygyx.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rebkcbhl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2worarzmy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjphllnm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vktltbhs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qandmvwy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hlutamwe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujznluf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvvkphj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuejeij.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngypqara.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yaidulnf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gatkngvk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2odcrxjjj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qudpwnms.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kspyjlra.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmoabrv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqrtatv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtraqrmf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvagioq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eqexepms.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnewheu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sniyjdfx.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfouvthu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqcuzws.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iherohia.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyltpan.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2elvwwrhr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwearrb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2brppswqj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgxqkde.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvnyoii.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2oemuihwi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuscmne.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwrkvdf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvipenl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqbdktj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tytzmtek.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oimckcua.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2znqukroj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiirmawe.html


<!-- 参考信息 -->