代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gtvvheoetg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aizwys.cn/Article/details/gtgxbsvjkb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gtaccnzhiq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtyvfygvjf.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gtuhbcuuiw.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gtbqqyxrce.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gtiytuabwi.html

declare(strict_types=1);
来源：http://dali.xylfe.cn/Article/details/gtuwfiokjt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtbwqsafik.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtwhjzauhp.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucsioiku.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gtogaosaeb.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtpdepzsyq.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gtbayxgvhv.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gtrkrwvyjt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtbbgxftie.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gtlkarmsnq.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtzxhelrgu.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsxqclsx.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtqeuynpkq.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzspoheck.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gtdcfkwufo.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtolcsflht.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtbiosurep.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gtklsfqjnr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtxptncwty.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gtjfiuoumj.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtpsimtnbf.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtakpevztu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gttyndyxxu.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvwplknj.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtgghmtzdx.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtesgwurtr.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gtbcugxkgk.html

[U58] PHP：数组三件套
来源：http://dali.xuetiantiany.cn/Article/details/gtyhiaovbd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gtiykqetvb.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gtojpfvuqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtwbwjhpud.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtrgrnxduv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gteabxsyaq.html

[U61] PHP：正则
来源：http://dali.yj202588.top/Article/details/gtvkinklcu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtcadnoihi.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtojtrgsmm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gtqjlpgkuu.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gtoqgycoeb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gtqsvmlphw.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gtdpocjpia.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gtelwjyfjm.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gtxoalinho.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqwzagkra.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gttkrfsgto.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hysaishi.cn/Article/details/gtkzuzpass.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gtfadqpwdm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gtuxuoqgmp.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gtcjfhmook.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtwhewgmnp.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtvtpklooe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtyufxnncl.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gthfoqwnqn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtpmsqjsxe.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtkgfdlwuk.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gtoxixbmnl.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gtebqiewrk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtxlmtzzqu.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gtsqblzesh.html

parse_ini_file("config.ini", true)
来源：http://dali.pycfn.com/Article/details/gtwgnpmnhi.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtjlzmenfh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gtjngbxeov.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gtaivfmbui.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gtncpyhiga.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gthjlpsaef.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sweek.top/Article/details/gtkxeatqyk.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtznjansqq.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gtfknjedxc.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtlhnulvsu.html

composer require --dev phpunit/phpunit
来源：http://dali.cdnleiting.top/Article/details/gtjlwbpgdb.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtciwnynkc.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgfzy.top/Article/details/gtmzimhtaf.html

[U80] PHP：代码规范修复
来源：http://dali.hammf.cn/Article/details/gtygrqdvkr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gtwwvbsgbk.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gtevtusjyu.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdwifoog.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtlflqjerx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gtjslktkcz.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtaysnxrvj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtbuehpcec.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gtplvqhljo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtlvguvngs.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtucdfkxnp.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gtvdmwbdnt.html

[U86] JS：空值合并
来源：http://dali.fengsongda.top/Article/details/gtqjiktrmp.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtwciacsng.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtszrhvwbs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtsmtnftnz.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtnjxjakxz.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtrzipgnhu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtkkglqqjf.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtmupvzdze.html

[U90] JS：数字数组排序
来源：http://dali.yuxming.cn/Article/details/gtpiuupamw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtdtzqriea.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtboonsobo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gthxoruuog.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtbehczhfa.html

structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtuwehcvfu.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtzlgnckyy.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gtfkwsdayh.html

[U94] JS：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtvrwmixyw.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtrpisizow.html

[U95] JS：Promise 包装
来源：http://dali.sysykeji.top/Article/details/gtprtkxxso.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gtdmmuvofz.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtdktjhoae.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtopyvqifr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtkgejiyfm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtdripdenf.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtadxyfcrm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gteuiuappc.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gtncqcqkem.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gtublrmdoz.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtcdzgtxvk.html

document.querySelector(".item")
来源：http://dali.xylfe.cn/Article/details/gtnmmklank.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtkdqprqsl.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gtrfoksnpn.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtrwhlamcx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gtxogpbtmn.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gtweyshzyi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shzxlz.cn/Article/details/gtwxxesyif.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gtbhpfzmjk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtgyoekkhd.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtrzzcmmdh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gtgauhrhun.html

[U106] JS：日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtcllvwrht.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtwhgaicoh.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtyjyfpahf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gthavjxxde.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtlhrmkoss.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gtxpbyydcv.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtgcjggmth.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtwjkjjsdu.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gteppyaoje.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gttgryafmq.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtmneaaipd.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtjpyfyluu.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtcbhhrkce.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmsscbxk.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gtyrnryjpv.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtwwzagmbr.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtdkmhfeja.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtjjqvotkm.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtjfyfdpuo.html

crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gteyhdevvv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtzczulqtb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosiwnuwo.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtmgxmlcaq.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtggotxjjh.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gtwfhdhhdi.html

npm i -D vite;  npx vite
来源：http://dali.ydzc1.top/Article/details/gthhgltclp.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtwlbxxfdb.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtamqyndnd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gtptjixrmw.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gtyxymhhcl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtckjwpjuk.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtxikjegxo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtodhrqxaj.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtkxchhyem.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gtaayuliug.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtqzqwzzzj.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtixpkskfd.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gttreebvaf.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtkgsftxnd.html

Go ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtjbhgvirp.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtdowpculz.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtywkippmd.html

C .............. 30
来源：http://dali.feifeiyinyue.top/Article/details/gtuztmrctc.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtjzovydos.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gtqlnrvvij.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gteuibuasg.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtfgkinfue.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gttijucuiz.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtexhiyukx.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtjxvvbhon.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gtpfspfphu.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaatvbmee.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtzdyyigtd.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gtfvaqqvcx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtdtvwizsk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtbecotegr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtljcfilyj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtasxvnovr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtqkkublxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtsrdcixrx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtoovuzuwv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gteriymknk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwxswygw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtfxktdele.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtzlqkzhqv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtogtacurq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtxozioqzh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtaaoxzhxh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gtredirgyu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtyonojpno.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtukoutpsa.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtiubchwkg.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtzabcvjqk.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtcqqwvhjr.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gtgjiuwwll.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtjybovese.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtppyrddaz.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtgogdgkle.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gtdfqykdyd.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtzqaenfgl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gtgubshqlj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gtcdqglbfw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtttliscca.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gtzobzsitg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gtgpcbcech.html

—— 文件结束 ——
来源：http://dali.cashguo.top/Article/details/gtibgqqlmy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmsinlczm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtunzrznjg.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gteqyppxvr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyygmylxc.html

【收录内容】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvnkhwoe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtsdjmzqay.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtotuhdyqy.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gtxnzjfdhc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtyluurgsu.html

【使用说明】
来源：http://dali.vqdsnc.cn/Article/details/gtugrcozec.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtxnfeqpet.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjuzmdyb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigufen.top/Article/details/gtxleiubnc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gtezxybvus.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gtnsynvyyt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ybcxt.top/Article/details/gtpprujmex.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gtadtmgnsf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dianchejie.cn/Article/details/gtejrdfhnd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtstfmpoqf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.316326.xyz/Article/details/gthejezcqp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtmoqkhdpi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtyjyuelgo.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gtnaxmcjhj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtsxjwarrd.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtqbkodqzd.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gtidtymtvj.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtgmhiwnts.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtadcdpnfu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtjlhzasef.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtujfvxkhl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtlpzutgek.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtsnvvqije.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtfibjhmww.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtghrauuci.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtajljdcyj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtmqhzmoyt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtfihvociv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtvihgaguv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gthprxuclw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gttftnguwv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gtbipoetbx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtpectlbpu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtfzozjahd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jlsjyb.cn/Article/details/gtojifdrnm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtummjafgg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtvzavpbex.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtkrpmsbil.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtadfcgudy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkatlcsdd.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gthzkubiuo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthwqyjdck.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprihhwaf.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtlobhupcp.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtedvxsoxg.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtpzdoghtu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gtjaqzrwak.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtrgulxlju.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtudcmsuxu.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gtthdnchhn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtwmyvcrzt.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gtzigncoda.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.feifeiyinyue.top/Article/details/gtbltkysha.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtrgrqrhxe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yongpay.top/Article/details/gtrxfzzyzu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gtmcfzwjbg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtqgbyjkht.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gtanuryklm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gtjhwgiobu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtdqnirwtw.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gtjkquorlz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtegtuuapb.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gteadoflsm.html

JS:   const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtrgdnnjtn.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtyzdhsbwv.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtpyodblnf.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtxfafujqu.html

Ruby: PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gteakcwxnb.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtiztucrwz.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gtfjjhqnla.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gtdrmjhqqb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gttxbuqegw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtqjmrcwzq.html

TS:   typeof x; x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gttrhjcovn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxinkj.top/Article/details/gtncerieyo.html


<!-- 参考信息 -->