代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtirthsxjr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtcwravdbc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtywgahpbn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtjohdpref.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gttwswciuh.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtlzltxtru.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gtwbhfzupe.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtzkfqmohh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gthpfogkvl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtsvsasvoa.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gtbmhaotgu.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gthlgxbhfr.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtqnwhuati.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gtfuhdekrn.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtgyjcdlor.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtvmjhbxhx.html

[U49] PHP：只读属性
来源：http://dali.wangshuangyany.cn/Article/details/gtmmwdagjh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtdystncrd.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtqysbmxwz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gtppkyrinc.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtbnkcbtwr.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtsxooncix.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtnwaxjwuq.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtetnvpwdf.html

[U53] PHP：空合并运算符
来源：http://dali.xinyue.icu/Article/details/gtwsactiog.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfnykced.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gtyynmvjvg.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtnffhogqz.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejdwamiy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gturddqqxf.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtrfhexeau.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvrsfgxz.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gthqgrnjtz.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gtslflevzd.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gtcskxdqht.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtpeucpjqp.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtlnvfzdvc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtoftzqvql.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtnqngtukr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtbixerdab.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gtsnvnfjik.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvnpvfvft.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtnqtgngzm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtxyyululr.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gttokacnsu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gtbsttyypx.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnpilfbai.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.smart0.xyz/Article/details/gtcjikothr.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtaegrngml.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gttztzcuyj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzwqelmn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gtjbqhxbyn.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtuqejbfua.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxfmxfqk.html

[U68] PHP：PDO 连接
来源：http://dali.vqdsnc.cn/Article/details/gtopxsucld.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtdnfbbvmj.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gtaboorchj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtmgjgkjgy.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gtgueemmwy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtlkteqqjt.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxkgndpe.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gtrhtfjlfk.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtsctgjfmk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtblwctath.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gtvvnroltx.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtfpknmnkq.html

[U74] PHP：读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtsbuuxodn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gtkjrcrkot.html

[U75] PHP：依赖注入
来源：http://dali.jianghu66.top/Article/details/gtolhmduea.html

composer require psr/container
来源：http://dali.jinqigufen.top/Article/details/gtyhxqkslo.html

[U76] PHP：简单路由
来源：http://dali.xuetiantiany.cn/Article/details/gtrmgutvbv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtumgxiykd.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gtpjjldkay.html

composer require twig/twig
来源：http://dali.ivvv.top/Article/details/gtdfxlvzuh.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtyusegbka.html

composer require --dev phpunit/phpunit
来源：http://dali.tanke756.top/Article/details/gtlrfootfk.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gtipkghtxc.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtnhkouqjp.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gtbxdjigtg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnqzz.top/Article/details/gtymxuhfon.html

[U81] JS：初始化项目
来源：http://dali.zhongyouzk.top/Article/details/gtqehfdkhn.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gttgdmgsvl.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkkztain.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtwdkzftku.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtgetzlrlm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gthgohwxtz.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtqcdzgfzp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.meibo888.top/Article/details/gthxduoewd.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gtttjffjmq.html

a?.b?.c
来源：http://dali.xziqi.cn/Article/details/gtvjyyjlxy.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gtotoucjes.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtqtkcmapj.html

[U87] JS：解构默认值
来源：http://dali.chenlongwang.top/Article/details/gtwgylbquo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlmoxbax.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtpxavboyp.html

{ ...a, ...b }
来源：http://dali.sufxvd.cn/Article/details/gtxvozjtfo.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtqufcqenq.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtszewezum.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gtoegsxduf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtgvcismsx.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtnuyebaoo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtejigwilj.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gtqsqtirww.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtaraoizgc.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtmjemjblf.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gtibqusypy.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtpbikaznl.html

const double = x => x * 2;
来源：http://dali.sweek.top/Article/details/gtnetpmypn.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtljmuyzpj.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gtwcisrsyj.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gthekobtov.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtnpzhikps.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gttxyzpxjr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gthyhzfilc.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtvfzmdeqt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gtzxmcwcph.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtbwpljyym.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtvgvsvbfn.html

[U100] JS：DOM 查询
来源：http://dali.gaohongyu789.top/Article/details/gtdiyvjjkm.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gtzitffiuy.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtywmcnehj.html

el.classList.toggle("active")
来源：http://dali.aibaodan.cn/Article/details/gtbkvzvmzc.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gttcadgzub.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtorlhbvyd.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gtrpdqxklg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtuplquhlx.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gtjxhfrdqm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtxwegcsys.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtlsmyxcso.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gtyhnkgiye.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtpedbxynn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfezapvxd.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtifkltggr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtshlhaabm.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gtvnyuryvn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sweek.top/Article/details/gtekfqpwzy.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtbkqikgxg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtjfsxzyto.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtasigeoco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtlokdhdmh.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtaqmahtpr.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtapdmnswb.html

[U112] JS：字符串补位
来源：http://dali.sufxvd.cn/Article/details/gtdwruutcz.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtszwtorhp.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gtvnrlvgac.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtpsfygmci.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gtgkezqhrz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtrvzsgmaj.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gthbuxcmtg.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtvuxogncd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtksqdwbfz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuiabcpik.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtkxzprued.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gtxcztuifw.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtwfxllnne.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtpsxcooyh.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtnwjjiqhe.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtvobjwwzp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gtjqjxgsff.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtawtxghip.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthlezqxna.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtvueusrsz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtudvfswpp.html

按语言统计（条）：
来源：http://dali.ybcxt.top/Article/details/gtbebjohqk.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvyqmvkl.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gticycofvi.html

JavaScript ..... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtcwzgagyh.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gtagtqkxcs.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtmufkoxql.html

Go ............. 212
来源：http://dali.shuidangran.top/Article/details/gtfagpaiao.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gttvoeorhf.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtmeaxqjsl.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gtohwaephu.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtvvqlouuk.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gtftjnqrei.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gtswasmtwy.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtjmwmmbyr.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gthhymbpdz.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gtswcfjjki.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtvqaxklxc.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtzsbbwzme.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtlgpwdcqg.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtzijpnglj.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtokkaqpzn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gteohhmbet.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtzwstlbkd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtcofmbmje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtswwllvlx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgphjptgx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtcmrlxwsd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtemowsvzy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gthfuucjvx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gthkckbipt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtcrzfeiiw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gticjjruyu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtjtdbttqv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtytvmfolg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlwpkqjj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gtulvsjcnc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtdiuubdlt.html

Q SQL 专题                              90
来源：http://dali.yanxiufei.cn/Article/details/gtvxaxgfck.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gtukbxrvow.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtgbfzpfdn.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gthgqpmdhs.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtyiognajx.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtzqijbyhq.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gtzuwnikrq.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtfhnkjylz.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gtehyylejg.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtxlahuous.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtfdyxlfjc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtzrvcxnda.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gtwvwlvlbp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhiwuduotai.top/Article/details/gtvufkjmjr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gtayppbcpn.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtemfwfqpj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdjztmopu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtvhhglhxi.html

Common Programming Examples Cheat Book
来源：http://dali.tianlin.xyz/Article/details/gtrfuhgwvo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtompmyzhk.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gtqjnxvuoe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gtxsyuptjn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfuogjll.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gtqhdacelq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gtcmpgroyw.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtvwihycqe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtkmzdvfjj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtgrtymehr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gtwucbvqry.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gtupxmnihw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtiyjhcras.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtcennqqow.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtwhisftrs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gtzgmhjzjw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnzworgd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hfpthk.cn/Article/details/gtjdvdpolj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuanzhike.top/Article/details/gtnywatbet.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtfzewxyqu.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gtnhednyii.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gtrevxjrcn.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtglamclkt.html

目  录
来源：http://dali.meibo888.top/Article/details/gthsceoefa.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gterhgfphw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtmwwpujll.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gtyadtwxjx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtqleffwbu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtjkuxaxqx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gtkuxpxspb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtfmtolots.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoizjgwtc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gttosanzni.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrabsbzba.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gthvpxxywt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtlgqshnhm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtpjvvhqyw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtylvmrwqk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtqglphmey.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtlsdovcix.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gthirqdibv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtzizjmxnc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtzgxdegpa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gtzeqsonpz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtmsvopbbh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gtvggffnrg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvzwwvfnc.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gtapmsbxdr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtefsyufri.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gtprqjinhz.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtmbnnssaj.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gthnhfulym.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gteqwnihqc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtmumtrwrd.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtjyfssjpr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtvykyvpqk.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtpeirccog.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtypygrwla.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwipxtnwp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hywenlv.cn/Article/details/gttlcmtvyf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtafwlkupf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtdzokzrfr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gtszssnzef.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtahyfmkre.html

Go:   name := "Alex"; age := 20
来源：http://dali.ivvv.top/Article/details/gtjshzvyvu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shzxlz.cn/Article/details/gtuxungksf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtitbypzmm.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtqdvluzeg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gtggjdwcef.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtgdhhrqoe.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtwoozvvck.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtqnsyvzld.html

Java: static final double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtdhlpjwpt.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtyjffkoso.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtciiqpadm.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaklxxrf.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtmassqwrl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gtohrmlxxf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhengqikj.top/Article/details/gtpbupwohj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtzwgwnrmh.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtxyggfwyx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtflgozhhf.html


<!-- 参考信息 -->