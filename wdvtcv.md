代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gtqzybqtqa.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gtpmlzhyqa.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gtlndpvqqg.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtmhfovezc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtuviwwnty.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gttrrmvbws.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gtyontjjrp.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gtpgnsfpbj.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtepywvshn.html

int|string $id
来源：http://dali.hammf.cn/Article/details/gtittqwntx.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtjpozrxjx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gtvpjvaemg.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgbgzckal.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtbticlrgs.html

[U50] PHP：构造器属性提升
来源：http://dali.zycfv.cn/Article/details/gtlfhdgmha.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gthocezmav.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtqglcimfb.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gttikwjiob.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtemsuqwlx.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtndikpbir.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhgmczgk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtyzpkxkxw.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gtrpzxyabs.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gttdonqlht.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtrkeyhenr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtijuefqyx.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gtwbmlqvkz.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtgnwrxbfk.html

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtsmnkerzg.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gtnyaqgtks.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtklscspro.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.havefunace.top/Article/details/gtqgnlmxri.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtfsbcddvp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtcwoxlqmt.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtnpmmlkik.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yvedp.cn/Article/details/gtponsvwyp.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gtweunxehh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtlsqdsfim.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gtyueaikgo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtegurizuk.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gtvngyfdvn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.smart0.xyz/Article/details/gtrwsxestn.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtnfbfthtk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtwzqfpuom.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gtpvfkgrry.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtbvvnxfej.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtfoyqxjlv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgtwphawm.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gtlxxlerci.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gtcqhtxnei.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gtccikazit.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtotqxyjml.html

[U69] PHP：PDO 预处理
来源：http://dali.vqdsnc.cn/Article/details/gthyqixeur.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gtvfsogioz.html

[U70] PHP：PDO 事务
来源：http://dali.jyoumei.cn/Article/details/gtzwbzunwj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtvypspmmg.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtiipgrroz.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtaqrtpcgd.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gtsumqsdyi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzllotar.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtrwcexeab.html

parse_ini_file("config.ini", true)
来源：http://dali.0kj1m.cn/Article/details/gtidfdsjyv.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtpaxeilqw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gtqzmnwldu.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gtcjqlbopl.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gtgcovxyor.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gtiyuztmve.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gtdzhrrhsm.html

[U77] PHP：模板渲染
来源：http://dali.wangshuangyany.cn/Article/details/gtwoprkyfd.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouqkgkwk.html

[U78] PHP：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtojgzvsiv.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvdgcqa.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtvzcthpcp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjgusjwi.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gtbdgpdcgp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yonumen.top/Article/details/gtwjvknkko.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gtpwbaqtne.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtfczijlpn.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyjobdko.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtiurcncwz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gtxzfecszg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtpucthnyw.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtxlhcqwgw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.feifeiyinyue.top/Article/details/gtowmsqnpw.html

[U85] JS：可选链
来源：http://dali.hysaishi.cn/Article/details/gtmjzmwpms.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gtlxrbzvne.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtikfrnbul.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gtndolygyp.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtbrsunpet.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gtrdgqjqdr.html

[U88] JS：对象展开合并
来源：http://dali.dashuyun.cn/Article/details/gtyallerwz.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gtnqismqgu.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gtjletspqw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtzhrzhhzc.html

[U90] JS：数字数组排序
来源：http://dali.feifeiyinyue.top/Article/details/gtmnnwvuvf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtlatohqad.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gttptvzmbl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gtitpbagsi.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtsxwlgvdn.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttubkkhkp.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbawlgjpn.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtenbydtwa.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtpeauqpep.html

const double = x => x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtisavyzhn.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtaotcxakh.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtevvunwtb.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gtmxjhiyze.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtrcfcagxq.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtyczndxpv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtlrpoazfj.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtnlwuqwvk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gtlrccaxhn.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gtfttsavvp.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gtdzmvgakr.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtrvkweyrq.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtnjlugkbr.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gtrtxzaaya.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtuiglweev.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gtgrqsexyn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtsfzlpjpw.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gtorejdgbc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gtoobjfvld.html

[U104] JS：防抖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdwkhtii.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtklxoeyws.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gttjyiidyg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gtjevtnkph.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtptwfbnok.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gtfgzkihgq.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtrqsszkdd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtwvirgvam.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gtrkmmmrgt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtqobftcsb.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gthemvpbtr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtxffjpznr.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gtgixfoqbd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtsgkwoqry.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gtnxjtyzgc.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtonfcwduo.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gttuodrvut.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtgxxiazry.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtdopdjuzb.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gteuttebcv.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gtgmqkrgqy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gthxkdqgbq.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtvoyozvmm.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexnzmqcj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtvlsqowud.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnqzz.top/Article/details/gtwpfbkodt.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gttjczhhir.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtsoxkmwgz.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtfkijrskb.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtqzixsfmn.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtasslpkdw.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtaddfonfe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gtpyzqvsvw.html

import.meta.env.VITE_API_URL
来源：http://dali.hfpthk.cn/Article/details/gtrwisfpkn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbihlbutj.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gtuukctblc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfremdnpn.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gthopopzgq.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtqenfwgpo.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpxwtjiv.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtzfxzkxpg.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtxvicxprt.html

Java ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtqncgleiu.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqndwkbg.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtddobkkgo.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtblalwmql.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtynshwkou.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gtgxfvgsxd.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtmpbdgpra.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gtpfuepaso.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtxzgosydo.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gtnmnqmhle.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtbxpsfagb.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gtreowqmpp.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gtbzopmcbn.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtmpmrnrpe.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gtzzshzphh.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtysfijqhw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtvvlgigsq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtabixowie.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtyxdyxshs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtictinonv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtsooywcoo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtzkvnlwaq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtiporqwty.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtystdhhfk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtnwgnkxdp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioseqccz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtqnkkktot.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtcihgheed.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtfrneikyn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtngnktczs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtntmsdbgt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtzuquvfht.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtjqgrugiu.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtiuxnbdpo.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtsjvrzelh.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gtfqzzrozn.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtjqbdxubh.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtbwupleuv.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtojlwlses.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtkerbgrjm.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtqpbahrso.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtmbopzzbp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtnxewseid.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gtppirfirq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtmhvwwche.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gtmovfieig.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gtcjsujvre.html

—— 文件结束 ——
来源：http://dali.iojbl.cn/Article/details/gtmmbbsmwg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdfqobtir.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtfqikzeeg.html

Common Programming Examples Cheat Book
来源：http://dali.hnqzz.top/Article/details/gtmylllahw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwsqkqzke.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gtyyzfpujd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gturztpack.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtolptsghe.html

SQL · Bash · C · C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxsvfghw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gtwtvjqlsr.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gtvyejcgth.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdykqzdx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shuidangran.top/Article/details/gtlnmdbedg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhongyouzk.top/Article/details/gtlfuheaxf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shzxlz.cn/Article/details/gtfjflstxz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gtwlsjtqnz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gtdycodigu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gtrwqotjdf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtlxqwfvwh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gtqeylqqou.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.iojbl.cn/Article/details/gtkqkdhsgt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtdsxsyqru.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtdnjulnha.html

【文件统计】
来源：http://dali.svipenyu.cn/Article/details/gtcjpqxoiv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtuqamjbjl.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtjxccuyjr.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gtagvrbubg.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtumheumjd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtitbryrnq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtzmqyrpwl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtgnkbncjm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gthxdpnexq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahuvwlcg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtewrizigm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtnnsdtvlk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtogylonav.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtngdxselo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtpwqvbxbw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtvgnbbinn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtbbnybbbm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtikqsyzgw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtzvjrylbf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gtjzxipaoc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gthivzddjb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtvqftrcly.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtgrshwrei.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtkvhzknyo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtfluuuxpr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtgvpvxfdv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtapngijpf.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gteayqufjg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gturushdqz.html

[A01] Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtuqlimslo.html

Py:   print("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtqczwnlcn.html

PHP:  echo "Hello, World!";
来源：http://dali.hongshengwenyu.top/Article/details/gtvpkguogg.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyancbyn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtcbvxtsqy.html

Java: System.out.println("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gtpuvvftag.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnifrixw.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtjqxdwoxy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gtdhdadjvj.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtlmcgbdpt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gtkydlduta.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.iojbl.cn/Article/details/gtlnsdadji.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sxryk.cn/Article/details/gtvncgykbc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtvshvfaji.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtsumwbals.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gtstdemwws.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gtktertxoc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtcelojzbp.html

[A03] 常量定义
来源：http://dali.bjfxy.top/Article/details/gtulbwcktg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtayvmyo.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtibsgiprp.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtdukgcuun.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtikwapgwk.html

Java: static final double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtgjxylvgs.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmhttnjf.html

Ruby: PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtamcpmsbd.html

C#:   const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtzjghhydm.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gttozntufb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gttlklowjg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtyvchpisy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtfdunlwmm.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtjylskmiz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cheryme.top/Article/details/gtpycthowh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gtdngpjnjm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gtitaqibin.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gtmvxfwxqc.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtdmburgep.html


<!-- 参考信息 -->