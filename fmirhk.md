代发 wailian999

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtfzgmkkxw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gtjippzuer.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gteqfxkhxh.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtwvtpucfy.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtwaujlfdv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gthsphvabj.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gtrakmkknf.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtcwbxcjkd.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gtsxrkbukn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtbosvtete.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtvakwpwem.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gtbnjxmzew.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gtpupeosdh.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjcprugm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gtxuldqnmc.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtqvecydmk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenlongwang.top/Article/details/gtrkylmzjc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtblgnjyac.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtyipstyxr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gtxlnjrbtt.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeemvibm.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gttkxkdoup.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtmljhkiov.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gtvofhohyz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtumbhnnto.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtscrxinte.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gtzrqcleir.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtvgustges.html

[U47] PHP：联合类型
来源：http://dali.chenlongwang.top/Article/details/gtcgnpgxsm.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gtrjmdgixn.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtkryuzmty.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtycjlmakh.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gttancpocc.html

public readonly string $name
来源：http://dali.xuetiantiany.cn/Article/details/gtqnvkvrva.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtutkynabn.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnurgfqvd.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtsyuhktiq.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtsgkgsecc.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gttrhthkuy.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtcplkaahk.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtyhdmjslx.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtpfpyegiz.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtxnbjrhuf.html

$obj?->method()
来源：http://dali.zhiwuduotai.top/Article/details/gtiwgqhsnb.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtucouykdb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcpanesm.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtyoekxeqh.html

f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtuegynzeh.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtjdakchsk.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gthwsblegt.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtrhodswlc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtpnepoalq.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtxcadhcrj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtqcyyjmbu.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtylabheoi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gtglrlgfvq.html

[U61] PHP：正则
来源：http://dali.nwbrower.top/Article/details/gtfbtxldae.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvskrzlyo.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtsrhqlnzf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtxnmrjgch.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtdjdlxgxs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtwezkbhlc.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnqxapfn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmvptrka.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqsayxtp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtohkcafob.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gtjxlpeujq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtvfehqmyh.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtzhkjvbrm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gtirblwmee.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gtqbedfvlq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgktiuklp.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtebtniqsf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtyzamopjs.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtifnbkpcq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gtntmwbwaj.html

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtturslftb.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gtmdnvvfga.html

[U72] PHP：写错误日志
来源：http://dali.smart0.xyz/Article/details/gtrinrites.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guowangkeji.top/Article/details/gtxbtuodky.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtsvvodmrm.html

parse_ini_file("config.ini", true)
来源：http://dali.0kj1m.cn/Article/details/gtdkmzrobq.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtcqlxjcwt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtmfaytxet.html

[U75] PHP：依赖注入
来源：http://dali.gzhubu.top/Article/details/gtbpvizmak.html

composer require psr/container
来源：http://dali.yj20258.top/Article/details/gtfmwwyrtv.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gtcsczvnzc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtwpacmndu.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtnepgipxw.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtspmymxug.html

[U78] PHP：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtyygejnmv.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gtmqjwjpax.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtnyysmirf.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtbisfagld.html

[U80] PHP：代码规范修复
来源：http://dali.dianchejie.cn/Article/details/gtcdwgcfcj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gtetfjvwrc.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gtyoolgpau.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gtfquwblmr.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtgghibfaq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtxykpvxjh.html

[U83] JS：ES Module 导入导出
来源：http://dali.9152youxi.cn/Article/details/gtgkjondif.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtpzcmyekb.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gtgkqycudd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtmsscsbea.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gtatzjrsod.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gtkgatqyyn.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gttihdzitq.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gtztrwfuyz.html

[U87] JS：解构默认值
来源：http://dali.guowangkeji.top/Article/details/gttunxyjfs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtxxbkisrf.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtivxekydp.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gthzqkfkws.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtlnoqgrwu.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtrrcdbsfo.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdutkpgxh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbongkafc.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtjeilafdw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtgyktidxz.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtvbrqjkkq.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtysvwfhsl.html

[U93] JS：模板字符串
来源：http://dali.yuxming.cn/Article/details/gtqseuvgax.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gtxfuohhlj.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtnllaotmg.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgkxztrl.html

[U95] JS：Promise 包装
来源：http://dali.sysykeji.top/Article/details/gtdlbvztjo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtgbhfkfrn.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gtiygvtqgz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtxcukigrg.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtflxnlikc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtblxugbyi.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtsjdipxgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gzhubu.top/Article/details/gtityyqxlp.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgmlvnfp.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gtvsymjluc.html

[U100] JS：DOM 查询
来源：http://dali.sufxvd.cn/Article/details/gtxuswpxto.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gtwjvbqvzn.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtlnajfmgp.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gtsydfsndk.html

[U102] JS：本地存储
来源：http://dali.yuxming.cn/Article/details/gtmnoperov.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtqsfjosdx.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtvszqddqq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gtapvyvbcl.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtbjplobve.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtpevwnkjw.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gtfwdnezgr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gtbdqyiure.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtdjtcwelm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gtunkezfec.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtjljtlper.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtkpbyizpi.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtuqyydpbp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtmlunsyyc.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtgmlqcixv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtvqikibvg.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gtwwtxnqbt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gtshubytnj.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtizfvsczh.html

new Map(Object.entries(obj))
来源：http://dali.tianlin.xyz/Article/details/gtxqadlast.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gtntomfpjw.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gttwdknasa.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gtkxfvbtdy.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtmwsbkgut.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gtdefjeszo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtccccithx.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtulyqdjvh.html

crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtwynzrbby.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtvrilxfdx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtbsauujtp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtepsdgmjt.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtzolgkkdg.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gtazvowkaq.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gtoznliobi.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gtvmqktlog.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gthljvtyoo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtxmdlyefh.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtzsvjzbme.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbjcfvppc.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gtnleraurv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfmrayhwe.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtfadnkmsq.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gtjuidqyyc.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gtkbhiiast.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gtbifmeizw.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtceuaygoh.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtuhvvhndy.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtkijpmngk.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtzkxglzjk.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtpgiefbkl.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gthbumgicm.html

C++ ............ 30
来源：http://dali.zdqjudy.top/Article/details/gtyefpbdjr.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtoznymqdh.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtzoreljpi.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtbsaewtla.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtjllrlirh.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gtmlugmrwd.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gtfwyvltqg.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gthiqkgnzm.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtuhtsuqyz.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gthnljwlms.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gtldfdnodr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtlfxctiym.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtvfisasna.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgwamgjw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtzkpdbidj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gtwahkcfwz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gthtcvdoqc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtbpryjqpo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtcprghvgi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtzhfakxnm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtvyulvblc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtrrbkurio.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtchymirlo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtocuejzia.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtpwutylrq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtitmjlhhs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gthwsdgizv.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtbrzqedge.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtiakwslqs.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtwjxjanuv.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtjgmvvyiu.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtztwabdva.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtffjpeswt.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gttfdqdscx.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtkdownktp.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gtzrelppiz.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtkhdqywvj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gttcktifpt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gthhkbtcuc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtehghkcya.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenjidiqi.icu/Article/details/gtvzutflby.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtryvtnmjh.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtvgrdknmb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzpmkqeym.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtfehyzjwp.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtmwcbhehx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgcqcenr.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gtwhguhdex.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gtvzuohfgj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtoyfroujq.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gtimfcrcqu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gtfhrsjnox.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gtlyzzacsl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gtimopqvmv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pycfn.com/Article/details/gtrfxehree.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sxryk.cn/Article/details/gticzhkcfo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnxiangtu.top/Article/details/gtrzyjegif.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gtrpdztznw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gtntfzfzya.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jyoumei.cn/Article/details/gtmmbulpmo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxuanxn.top/Article/details/gtcxanhpyf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswgjiaeu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jlsjyb.cn/Article/details/gtfmuptclu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guannengcc.top/Article/details/gtohnvidpr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnojfoowz.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdndizsty.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtvhxevxoa.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtvavxdkpm.html

目  录
来源：http://dali.sysykeji.top/Article/details/gtevokloih.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gthzdxmkvo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtorsrqrjd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtjvelacvu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtrmhfpvhp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtjnpypkil.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtbgbvjblx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtsptcgvci.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtnebljana.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gtqveqijuh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtlyprwuld.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtnppuqypg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtqmwmwtpv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtfgjjzcyq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtpwjuxbgd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtpzmbxvct.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gthuapsfue.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtiinipzxf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtlacrdqzi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtegztlpan.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtefzpvntv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtuylvyuqc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjhlhnewp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmswrcnab.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcltkcvks.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmfnokupp.html

[A01] Hello World
来源：http://dali.0kj1m.cn/Article/details/gtooizejlc.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtkrbaglso.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglwzcyep.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtajpmwwzk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gtydsuetfg.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtfyyoscbf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtdjjxzzjl.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtemwukbne.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gttmujbavm.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtzfsptokg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwysmlilm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daria6918.cn/Article/details/gtsdkddeoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gtnqrauclb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.c1oappe.top/Article/details/gtqpqspfrn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtragfrygx.html

Go:   name := "Alex"; age := 20
来源：http://dali.iojbl.cn/Article/details/gtsqqszzlg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gtmbhppzcg.html


<!-- 参考信息 -->