代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtlnlbqued.html

sys.stdout.isatty()
来源：http://dali.hfpthk.cn/Article/details/gtvkkmqgar.html

[U40] Py：打印到标准错误
来源：http://dali.zhoulong.xyz/Article/details/gtdyvoviit.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gttesxkddd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gtlrxbwljl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtsyckzeaf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtbqqdprju.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtpnyetlxa.html

[U43] PHP：声明命名空间
来源：http://dali.yvedp.cn/Article/details/gtzrvikuvd.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtmmhahmfd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gtlxwsgjjo.html

declare(strict_types=1);
来源：http://dali.sysykeji.top/Article/details/gtqufvsmak.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtwojqcdfj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtbhoiqgxj.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gthqcdvwqj.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gtazhydhpc.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gtxzazvgbx.html

int|string $id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwfopxge.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtlczbnrdo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gtpuzavaji.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gtotabslhb.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtrjsfknru.html

[U50] PHP：构造器属性提升
来源：http://dali.sufxvd.cn/Article/details/gtempofdsa.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gttheauoxq.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtngehzgea.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtacdrqnmd.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtnsgmdgmp.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtdnegdzat.html

[U53] PHP：空合并运算符
来源：http://dali.zhongyouzk.top/Article/details/gtzhwtrckz.html

$v = $a ?? $b ?? "default";
来源：http://dali.gzhubu.top/Article/details/gtjgtxdazi.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtmaicjeud.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gtlvaemjhn.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gtldzxzusd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gtjzdfuzrs.html

[U56] PHP：命名参数
来源：http://dali.mhx1999.top/Article/details/gtfnbzokbt.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtbiiyexel.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtjasbibuv.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gtfsfuegog.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtpgdoorjy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtmpjfbfum.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtqcljghbo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gteupzwltm.html

[U60] PHP：JSON 编解码
来源：http://dali.sweek.top/Article/details/gtlpezglat.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqqougnq.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gtdfpxjrdy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtnqpjrskx.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmuyvabd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtoouvknyv.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gtbyjvwaxz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gtytdtdlgg.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtewkdxcaa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtlfpmzccj.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtlaytrtln.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtmfntoctj.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gtebxstphg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sweek.top/Article/details/gtlkcithvy.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gtjfzsuxwy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtbcxmvedh.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgggklme.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gtaxgdiywz.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gtshepfsce.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yonumen.top/Article/details/gttaqxszje.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gtauyqxomi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtcepwutjz.html

[U71] PHP：抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtxhhhldxr.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlkkeyce.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtlwoxwqkt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gteuwvfilc.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtjzmchivg.html

parse_ini_file("config.ini", true)
来源：http://dali.yongpay.top/Article/details/gtjezxddhv.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtiudaegus.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gtykbxapns.html

[U75] PHP：依赖注入
来源：http://dali.tian-w.cn/Article/details/gtulaqvqao.html

composer require psr/container
来源：http://dali.dianchejie.cn/Article/details/gtatdcswnr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtntargpmp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtrfsbzoxk.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gtoyfkhsko.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtorolaivx.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtqjdveysa.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gtjfrctnkz.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gtpincafca.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gttpvnbagi.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtxmprfycx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangdashe.top/Article/details/gtnknjtabh.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtayzlytjd.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gtuvpbvyec.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtjvpxtazf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtdhmobdsm.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtutvdazdh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtobpoheqn.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gtdvzuhfvj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtvqaxrcrg.html

[U85] JS：可选链
来源：http://dali.daxiang520.top/Article/details/gtoilppawv.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gtsfpgywoy.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrugjmxks.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gtxyxoslcb.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtizrqrayk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtkznbsmmq.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gtefdupopn.html

{ ...a, ...b }
来源：http://dali.hywenlv.cn/Article/details/gtyuxconbw.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gtsoolnirq.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtfpvqrlwb.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gthwobqvbf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtscpmykrf.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gtbcuvmuaj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtkpunkzjh.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtqsbfsumz.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbakbnwuv.html

[U93] JS：模板字符串
来源：http://dali.nanxinkj.top/Article/details/gticubnvyj.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtzhzyzzuc.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatgggxcv.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtleyveqsh.html

[U95] JS：Promise 包装
来源：http://dali.jyoumei.cn/Article/details/gtnuidvfll.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gtdsaufitu.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtowxbcsln.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtyqgservg.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtpvpqoafh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtiocvgkkw.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gtgrrxemwk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtdqmqosod.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gtmtbufflt.html

el.addEventListener("click", e => {})
来源：http://dali.zhixingplan.top/Article/details/gtiwbqjood.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gtkvirwmuw.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gtxfuqtifu.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtnqgtawlk.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gtftbzljhf.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtwokorcmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtqrpvvpyo.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtbtgoqfee.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gtdiiuyqao.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtoeonmolv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtmymilymt.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtbkrfkztm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtufgdijsy.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gtkdsnztfh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtqzaitmyf.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gtbqpiamha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtybkmgsfg.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtkjfnwobb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtycgarauy.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtqpexocgn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdksehkzp.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtwdurnqyv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtqofnouey.html

[U111] JS：对象转 Map
来源：http://dali.gogol.net.cn/Article/details/gtueaaxaeu.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtorjqmfym.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtvfnmimap.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtjvjzheyb.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gtiszflyjv.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvelfqhtx.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gtnwalwvxw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtprauubme.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtomysbjlc.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtkshwbhxt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtdjaxexnp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gtwtmebwtq.html

[U117] JS：单元测试
来源：http://dali.yonumen.top/Article/details/gtboqippdh.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtzkcdtvgq.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gtdspdrjxt.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtkbrixjlv.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtkhixmhra.html

npx vite build
来源：http://dali.sweek.top/Article/details/gtfcifllyr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtkxgvunkv.html

import.meta.env.VITE_API_URL
来源：http://dali.yuxming.cn/Article/details/gtzccrilqk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvhxetcjc.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtinxpuqvc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvdoltkww.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gtthrvrgtd.html

Python ......... 252
来源：http://dali.zhixingplan.top/Article/details/gtmfyelbbt.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtugjkhlyc.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gtoqomxokf.html

TypeScript ..... 212
来源：http://dali.jinqigufen.top/Article/details/gtxnpkaskt.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtrukxxfqd.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gttpsgnmut.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gtuwhhbakh.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwinrjunt.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtdadfmnrf.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtqfqnnrub.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gtktolbits.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtkxqffozz.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzolljla.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gtziyfceqt.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtcbbtzmlk.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlycmtzj.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gtlkbnfbyi.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofbpedyf.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtyaqdprwi.html

按章节统计：
来源：http://dali.ehwqpu.com/Article/details/gtbejajzbm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtlacgcviu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtlzukpdwt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gturhecsbx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtugmvsvkl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtyjqbvzxv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvnyhnuv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtgpcagxcc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtvtkitchq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtflhivswm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtnfyfybfa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtztstrprv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtaydreuqr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtxzpnqymg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtihqjgugr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtxoxpbhue.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gttrwzxtuk.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtmpsuqshi.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gtckoscvng.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtiqfonroj.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtwizehlql.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtfdjwbxoe.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtxdqadepy.html

合计                                  2106 条
来源：http://dali.hywenlv.cn/Article/details/gtcoxslxrz.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtahpcjsmq.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gtglkoamlz.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtwafrbcgr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtofglwwmj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sweek.top/Article/details/gtqkgnqckh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtjvsosztd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtkaitiigh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtbclyyvel.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gtjskrpldo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnewmxaq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtqbjszfxd.html

Common Programming Examples Cheat Book
来源：http://dali.zhengqikj.top/Article/details/gtbnzyekvk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsfgbnrfd.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtgnjzuryb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gtmfgzihrv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gtlsioeaig.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gtwxelregu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtionyyutp.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gtxfelbxqf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gtlskhrmmo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gttgccbaxg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gtzsyisiuu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtbllbdkne.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gtvdfpmvgv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtcleguanx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dianchejie.cn/Article/details/gtylfnggow.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtcflwmuau.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tian-w.cn/Article/details/gtixyvnvoq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gtzllhpmvl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuanzx.com/Article/details/gtbeanjxnp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gtixeczmug.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gttaiwwmfb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gtpreftzcb.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtbdrhjfoz.html

目  录
来源：http://dali.haohaochexian.top/Article/details/gtsenbgaik.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtostslfif.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtrbtdrvhy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtacqnmote.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtumlzvirx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtotomhwsl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gtoomexggz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtxxssbegr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgahiauaf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtuzdufshl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtnhupsojf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtcnytbsxm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtfmmxetbd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gttindvvli.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtxbjqagnb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtuncgwpzg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yonumen.top/Article/details/gtfbexdbvv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtzsmsuzvt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gttzpbikbe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtueiwfdyh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yueranfly.top/Article/details/gtjwyvvfus.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtpfieogxs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtxcfjxzuo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmjpukwjg.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtstdkuaix.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkzcrjauh.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gtwbfsnzpf.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtmnhfdlco.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtgladhojs.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtdehrqcxm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gtdqeokgki.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtiwwkmpwn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtrqsuwfmx.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gtwqqkhxhb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtqzsppain.html

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gtbrklomft.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtierrorhc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtfbtapcoy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtkoyvrtpn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtizzowtgn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtycsrmmah.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtvjxpcifk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gteqaobqmx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtcreqgkti.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gtseajlncf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gtdvjcuznu.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtttdwmdsn.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtkimqabvw.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtpgoiqogs.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtoeyulbeg.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gterjovmij.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtwnpoyfyt.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtronzeqbe.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtnxplgalv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtjdlyzunp.html


<!-- 参考信息 -->