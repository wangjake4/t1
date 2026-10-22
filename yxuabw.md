代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtywhkqpoe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gttjheihje.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtsreakyaj.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gtvngcwyjm.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gttkxggfsc.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtecqqqgcb.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gtugvwefox.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gtcprwwnut.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gtvuuvfdao.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtsiyjioog.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtorjaxutj.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtybcfapao.html

[U51] PHP：数组解构
来源：http://dali.haohaochexian.top/Article/details/gtaonrfvyh.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtnbhtvpxv.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtxccnmhlk.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtfwwjfjcd.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkgyheph.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtmuhmeldv.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gtpopaujgq.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gtjjuevugx.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gtzlazlegq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtqrrczgbl.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtubuolzke.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtcpptsxda.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtuihbvswz.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtdxevmvjc.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtcqnjikyl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqjpifoyf.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gtwshgcfvj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveoonbby.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtdgjjcasn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gtktqozmoy.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohnflndi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgdaitnwi.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gttfwmkidb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqzfsjnk.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtmrgrwpwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcskowb.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gtcwrnnvwy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtxupzjhfv.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gtcibomlqi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtdginwydn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggzyzspa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gtrcmhmxqv.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtjbugofar.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gtuicrwenl.html

[U68] PHP：PDO 连接
来源：http://dali.ivvv.top/Article/details/gthbvohgat.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gtdnldizus.html

[U69] PHP：PDO 预处理
来源：http://dali.xylfe.cn/Article/details/gtylonrvcd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gtqwvebkrp.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gtfcccuihm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtsrcxnaor.html

[U71] PHP：抛出异常
来源：http://dali.xylfe.cn/Article/details/gtjygmcgwi.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtwzznsdma.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gtrldnvnmr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hammf.cn/Article/details/gtgielcrlb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjusexktc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gtsxfbyzzt.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtlxyzeohs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtzpvryl.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gteacbzmcl.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtkxflreso.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gtahbspkpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gtsddokzqd.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtdeowpfdw.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtyzbrsggp.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gtekklzwuj.html

composer require --dev phpunit/phpunit
来源：http://dali.shangyingyoupin.top/Article/details/gtabrhtxsl.html

[U79] PHP：静态分析
来源：http://dali.daria6918.cn/Article/details/gtwuorfxlh.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gtcpigpgyu.html

[U80] PHP：代码规范修复
来源：http://dali.pengpengdd.cyou/Article/details/gtblrvudui.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aizwys.cn/Article/details/gtoxuihwfi.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gtxfasiphj.html

npm init -y;  npm i express
来源：http://dali.zhongyouzk.top/Article/details/gtcnsbiwuw.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtnstrqnde.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gtbtbxqxyi.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenlongwang.top/Article/details/gtjfjmgiuq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtjytomsyr.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtkfugnfhc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gthpvsvvoc.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gtrvckueur.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtvkbzfaiq.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gturtuqozn.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gtqtfkqhxn.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gtmppqhswl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tianlin.xyz/Article/details/gtxvnzqpim.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtmflxqrkc.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtphqrehyk.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gtndgyyyiy.html

[...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gthfcwvofw.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gtgilqqsaq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtphtnicxg.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gtaruhwspi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gtnwxxsidh.html

[U92] JS：深拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtpijkcjjl.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtzlzkddbd.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtwjhlmfiq.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtugzibzjh.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtsjlxubwa.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtkmngbomc.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gthnaemyfr.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gtafnolnpm.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtwfbsopoz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtluqjgknx.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtqjdocfmb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtjqrewylv.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtwwmdepmu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gtwvtktpel.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gtjvyhedbu.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtitoxnlvq.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gtouodwdgv.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gtmykuxewh.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gttjypunub.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtslyhwtlt.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gtbaiwauwb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.andypj.xyz/Article/details/gtrcqzioyv.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtzoeyvzlg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtsxbewcdb.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gtyrsxgsmf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtudxmxsma.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtbxftagvs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gtixxddsij.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtlaixiuja.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.iojbl.cn/Article/details/gtjigixxne.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtdawdhciq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtkiihayqe.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gtjgdyrnpn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gtsnhfznog.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gtfnqqzhgr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtildtzwck.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gtmqnywbsw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gtywqxzowr.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtxynxampy.html

new Map(Object.entries(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykfsvmyf.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gtsongxgad.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtyycflasp.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtmjhuckkg.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwmeedkzy.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gtysdjjwfx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtjafhqvfi.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtfhblewqy.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtbxocvvms.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gturyovesb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtabzioqcb.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtxzthfieu.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtummgntzs.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtbnaujsnv.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gtdvktifbb.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlcfedsn.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqdhhnum.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigufen.top/Article/details/gteuyuaykn.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtqfsacher.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuvquiumd.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtjdcvfgjy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkgodlpsh.html

按语言统计（条）：
来源：http://dali.yj202588.top/Article/details/gtxlccrygy.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtbtfkjjma.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gtlqxyvgjx.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gtmmtkbqfx.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gtlckwcbez.html

Java ........... 212
来源：http://dali.guannengcc.top/Article/details/gtjclrjofj.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtzzefestx.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtoykdczbd.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtrykbvwvd.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtwaffbsbk.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gtrapayrjz.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtgqtnakjl.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtxuktwsey.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtvfsruimr.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtwlaoppsy.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gtfuwlztnz.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtdodyatsk.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gtlhckbxxn.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtjlhbwhzv.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gtswpvtxca.html

按章节统计：
来源：http://dali.yueranfly.top/Article/details/gtomeqhjwf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtldnhnquh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtpcryfkvv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtvowxpyka.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtpugdifbu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtxtpthofi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtgovfrxph.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtfohpnwvp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtwjzitxit.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtxrjwisxd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtpbtznlok.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgqnxliv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtikbfpmnc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtldvtbvgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtvayqbvpw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gtwaguzjgp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtchxolpqy.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtetfuoquc.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gtsaafxtwz.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gthgnvjpsa.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtfngltmbp.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gtszgjcldi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtgkbomcdj.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gtmvamjpca.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtkmapbevx.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtywahsdxj.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtkjazbitn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gtfifcmgoz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gtcynmhnog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gtedrmqrfl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtcqukbecc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gtsjfhibeq.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gttppgdqeh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmvnietxq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gtaxdxfyqw.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjldxeeq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvksddztc.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gtllvevobc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gthbldnskh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.birdmap.top/Article/details/gtsthybmii.html

SQL · Bash · C · C++
来源：http://dali.ivvv.top/Article/details/gttffxivvr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gthetgiecd.html

【使用说明】
来源：http://dali.hywenlv.cn/Article/details/gtwwcwetmf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gtphudbesl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gtjxwefvaq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hammf.cn/Article/details/gtxtcisoid.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xuetiantiany.cn/Article/details/gtrplzsmsg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtsdbivego.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gtkwxmdgfo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtjijclwdh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ydzc1.top/Article/details/gtxrxpbxhn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fengsongda.top/Article/details/gtjveddgsp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivbomrn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtywwmahqh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aizwys.cn/Article/details/gtmjxoolrx.html

【文件统计】
来源：http://dali.zhiwuduotai.top/Article/details/gthteyykth.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nwbrower.top/Article/details/gtjabhutjw.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtjtkyoyql.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gtjupyofki.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtosqmrnmg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtbiwubyyc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtsjjzwuha.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtqgeohdtl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gtedkethem.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gtfqdcxuuq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtrlhrotxj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtazppis.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtnwasnbfa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtkphnywkz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtqyqmedbc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtbngbqvle.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gthdiifboi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtgxzxijzm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtxwbmhlpl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlezietl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gthfjvfyee.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gtkgjvslsx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ybcxt.top/Article/details/gtahoihsja.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtzrmzmugf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtbmgdhynp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtuvpnfbmw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnxvarpqk.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gtnifrneyq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcourlpif.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtlkxfzzfu.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtorimghoi.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtiyccqrek.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gthktabdnz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ehwqpu.com/Article/details/gtyjmceeem.html

Java: System.out.println("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtakgddulb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gtkwolexcp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtngjkpzpg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtohcvxfth.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtvvvhmyob.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhengqikj.top/Article/details/gtowpozorv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gtiwrnptup.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.birdmap.top/Article/details/gtwkveuapf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yongpay.top/Article/details/gtvrjyouka.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtcwtawhsl.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gtxbtzwwwt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gtjwsmbwpx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gttstnbjal.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtlqwoechr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtbejrtblk.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjipouiom.html

JS:   const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtkkbjarei.html

TS:   const PI: number = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtwjgnfejy.html

Java: static final double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthmdxpdoy.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtwpzhnntg.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtmqtostkb.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtumztamcq.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gtcjotxugb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnqzz.top/Article/details/gtmzuhncje.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhongyouzk.top/Article/details/gtvhuvipwe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gtbcmbmwnj.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtcunfjnas.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.9152youxi.cn/Article/details/gtueucigzy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gthwjncttz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hfpthk.cn/Article/details/gtmhknpikp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtdconluev.html

[A05] 整数除法与取模
来源：http://dali.dianchejie.cn/Article/details/gtrwljdqvf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shuidangran.top/Article/details/gtoukwwfyh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtgrfgyljj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtbnuwcult.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gteesqepny.html


<!-- 参考信息 -->