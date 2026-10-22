代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gtcebvzvud.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtxmoaclzi.html

[U56] PHP：命名参数
来源：http://dali.sufxvd.cn/Article/details/gtpqcerqfm.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtswwytpje.html

[U57] PHP：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtwfvrbjkl.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gtkohuakox.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gtueyvyzoo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqkesixma.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtvstvqpyc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtexmknkbv.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gtgcwawxpz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sufxvd.cn/Article/details/gtwgxfaxlf.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gtyxkiditv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtblqnteum.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtauouvztb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gtnltspgde.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gtchpykbmb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtpdecqsrz.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtgwhoplxx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gtikcfdebq.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtpzgvxszf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtyapqnwwa.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gtykqlywwy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gtdaxypscq.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtbmswzgxu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gtxswtitzz.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gtzdoysuqa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daxiang520.top/Article/details/gtanrdfhis.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtmaaxfbtd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtyioqgjoy.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtbxacvciq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gtxzyrwvok.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtstxnnxzx.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gtvkyvtrte.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gtboopyggz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jianghu66.top/Article/details/gtjieppkat.html

[U73] PHP：读取 ini 配置
来源：http://dali.jianghu66.top/Article/details/gtpzzoytnl.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtdtzmotbf.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtpsodfcda.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yueranfly.top/Article/details/gthqhksxws.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflnmcqor.html

composer require psr/container
来源：http://dali.chenjidiqi.icu/Article/details/gtfmfzdlmv.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtcjkrvlpn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gtyzzebugj.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gtnqxzkfgk.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzwvomep.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtqotmzuki.html

composer require --dev phpunit/phpunit
来源：http://dali.hfpthk.cn/Article/details/gtxibfpgor.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gtpaxfkuyh.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gtbkcmtywn.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gttjqbyhyn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtbpwrrimk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtbvwzkmns.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtqzykkprp.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gtjddaljet.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gttczknsav.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtscwovjha.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtwafmqwuh.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtttuupmgu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxricibyw.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gtgcubfapl.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtfbknbiil.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtzbzjgkit.html

a ?? b
来源：http://dali.ppjwa.cn/Article/details/gtmlvqktfo.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gtglnqpagh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtgaighxxw.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gteksvuxto.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gtzfyysjty.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtsfxnjpii.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtqatkmaeb.html

[U90] JS：数字数组排序
来源：http://dali.redwolf501.top/Article/details/gttdtfpkfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtliiydzgd.html

[U91] JS：对象键值遍历
来源：http://dali.xinyue.icu/Article/details/gtogflkifo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shuidangran.top/Article/details/gtwihlqyem.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gtnukeqpyh.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdhhmzwz.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtyyaislkb.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gtsndowvyw.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtbldflnss.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtohrsgxrj.html

[U95] JS：Promise 包装
来源：http://dali.jianghu66.top/Article/details/gtojadphrl.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gtlyeivspn.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtuongrwuq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuclygsff.html

[U97] JS：并发请求
来源：http://dali.yonumen.top/Article/details/gtybhqxset.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtcqduonay.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtegfgpvtf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtmdwshjay.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzubcbaho.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gttbxmufzr.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gttfvqeoac.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtvjoppzir.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtkocjkusd.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtfrkfqbnh.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtaytpjnhe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgrzcjjf.html

[U103] JS：定时器
来源：http://dali.chenjidiqi.icu/Article/details/gtgppbugjh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gtajfnjdaa.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gthawbabrq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtmvbdvhcj.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtdhuiskfs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtgivzcdbf.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlktlqkfn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiylhfwro.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtxlspmugz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtlmwzxgyb.html

[U108] JS：随机整数
来源：http://dali.cdnleiting.top/Article/details/gttrdenusm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gttkzmztvi.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gtwmmjspyz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtuhatrjbi.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gtimztutyx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gtslxwdebf.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gtwpbgesvi.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtswlvmydw.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gtsyazejzr.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtgqfeemhe.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtvfadhozi.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtpmrmhgpa.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtsacsxtoh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtdxhegflo.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gtysronqpe.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtlpeucsad.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gteejqdeua.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbobmxhff.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmncergjn.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gtofuogbbz.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtihqrmoxm.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtbjcxauvv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtxylxtxxv.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtjidhfcqv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gteitstrvh.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gthwdtphuo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoeyyrxlq.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gtbbgwnxgu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlpqaetuz.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtijtnzatj.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtgbmzxiwz.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gtziqhsljz.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gtgoymuyyq.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gtcrctwrpo.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtqevnxyge.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtbgdqchvk.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtaokzmcen.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtijzohqvh.html

C .............. 30
来源：http://dali.feifeiyinyue.top/Article/details/gtqekodqrb.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtnxsiseel.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtxpplwxna.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtctjezfas.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtanxfwwae.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtjxhtxskq.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtskcgkd.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtpwetlyrx.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gtfzlszyrg.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gticvaskms.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtdnolrz.html

按章节统计：
来源：http://dali.andypj.xyz/Article/details/gththvcdjs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtyboysmif.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtfbacrdxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnzmieef.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtjjgudfjx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtozrvmsri.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunqhzsns.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtjwxjssxk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtewoshulw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtavlrkdmw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtofjpjell.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtxxplzjpo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtkzvfxwft.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gthcvmtiev.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtweijpvjp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtrdutlftj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoflxiwc.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gtbhrjcyto.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gtkxizipbk.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtjavqpmet.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gtitzpbnzu.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnzvacmy.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtnmgauxvc.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtcaqijhyf.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtytaejzdu.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjuobolk.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtejdurilf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtxnvuudxb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gtrihofygz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtntnbkqcz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gtrnkkxndh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gtrfbsthat.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtqplbexdp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmpslddet.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtgpoeisks.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gtjxhptzbt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfaimmvzh.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gtgwmcweea.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258888.top/Article/details/gtcxrvtobl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gtqxxtmlyi.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtjmtzkfve.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtqcwxhvyi.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gtfycdcrcn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gtfrkqazia.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtpyqvixae.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gtyrzritez.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtshzduizo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtidijtuza.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gteizionon.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yanxiufei.cn/Article/details/gtlvjvikxp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtwehcmmxw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fengsongda.top/Article/details/gtrxztkbpg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtvmhhauvd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gtxrsfhnej.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xylfe.cn/Article/details/gtdhigixjy.html

【文件统计】
来源：http://dali.zhixingplan.top/Article/details/gtvujcpgsy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gtyfxinvfb.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtfkqoqxds.html

目  录
来源：http://dali.yj202588.top/Article/details/gtjlefjgav.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtpthkesgy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gtbdyrdebs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvbqtyzqc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gttjolbodo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtonywgfbv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.birdmap.top/Article/details/gtcijumcvp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtzyovyjnm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtnrlxhsct.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtgrfkjkhg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtmkpdkfnu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nwbrower.top/Article/details/gtqmwgsyzm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtzgzseiau.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gttvpxtpss.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlngbxmsd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbjlysll.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guowangkeji.top/Article/details/gtcdsgzyiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtkekedqia.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuanzx.com/Article/details/gtmnfxbcnl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtymyofkwt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gtwxjfampa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtjraharaw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtlxasnclt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtywfgfrdl.html

A. 基础语法与类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdebelfz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtigbwfhza.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhsbxmsz.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gtqwybrwjj.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gtjiwbvxzn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtfivkjdrr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gtfsxeloex.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtryycewth.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtlhhxtdhy.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gtvosklrce.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtimatjcds.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gtrfpoxxui.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gtszkvkgmw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gtyxmnjoiq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtdfanqxvj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gtvmkerlwe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtpnpnscrm.html

Go:   name := "Alex"; age := 20
来源：http://dali.xylfe.cn/Article/details/gtqkqxwlju.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gtjnjprkcf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtbxgzfyfv.html

[A03] 常量定义
来源：http://dali.aizwys.cn/Article/details/gtsecxrfwi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tianlin.xyz/Article/details/gtxhgmqeuj.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtjrjxccnk.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbnkbbwal.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtqpdvdeby.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtkgqjhxpk.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtsbtsvbai.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtjtnvlhdn.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gteoxdzkbf.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtyzmxwgdm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenlongwang.top/Article/details/gtrmmwmtgm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtnqxlengx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gtqgztbkcd.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtbhsyersp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjsyxxtk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gtmdudxjkb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shzxlz.cn/Article/details/gtepgafena.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gtfketcexp.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtgvxogwoy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtzaqvanmi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtjsykhhpy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtzfwxigvr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtrmmrvolw.html

Java: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtfyuriarj.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtljoprejb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtmmrkwnpq.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtxvtxtekq.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtxpgziikz.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gtipcurwno.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gtjbgzqell.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gttvchmzcu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtmegrvymo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtyvdholpi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gtbjpsfcsy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hfpthk.cn/Article/details/gtzkivykee.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtqzespusz.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gtswhavkfd.html

Py:   str(42)
来源：http://dali.gaohongyu789.top/Article/details/gtntfrvzdd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmvwrhi.html

JS:   String(42); (42).toString()
来源：http://dali.ivvv.top/Article/details/gthlgbsbqt.html

TS:   String(42)
来源：http://dali.redwolf501.top/Article/details/gtlucucgan.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtlbayjxhq.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gtquyiuqer.html


<!-- 参考信息 -->