代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gt2ispmbucp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2kqhaypdi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gt2troimyvz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gt2xtwefcgf.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gt2naljouqw.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcbzpcnv.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2sqskqesk.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2zssiqqqn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gt2tooklymo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2dywhcfuz.html

[U46] PHP：可空类型
来源：http://dali.c1oappe.top/Article/details/gt2fgsoyuud.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2jjuytjgu.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gt2ptkqlwhw.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gt2nnmrluel.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gt2snmsxzig.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gt2eoxkonnz.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gt2krvmohdq.html

public readonly string $name
来源：http://dali.yuxming.cn/Article/details/gt2ybkonwwk.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gt2yjvumklp.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gt2lpvuqeft.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gt2xiewgcjt.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gt2thlwkffn.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2bwiqbnzj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqeribb.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2varytkpx.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gt2blebpjka.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gt2xcjesoob.html

$obj?->method()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xupyajri.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2awsbqqnq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gt2bakzguug.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlauziow.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2bvkjkswj.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2brztqxwr.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2iwdkmdhe.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gt2qxaplaoj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2hhuimcme.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuwbouua.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2zwtorviu.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2yueavfkc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gt2shjreoxo.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gt2bhpmyrhq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2ykbztodh.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gt2fiwgrpri.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gt2unywakqd.html

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dftfnyax.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.0kj1m.cn/Article/details/gt2cavifpcp.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gt2flpwcmra.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.mhx1999.top/Article/details/gt2tjolsohi.html

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gt2yxystktf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2abhutqvu.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gt2lxqqonrj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gt2kmiijeuz.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkbhpdbp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gt2hcynfbdb.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gt2vobjlvde.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gt2krzopciq.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gt2fimkmran.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gt2hsculvqy.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gt2nkxztxcr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flafljbg.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2jphcuuwp.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gt2oreziibj.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gt2kghwreln.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gt2gpbcaspb.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gt2qryylxgk.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gt2usuedvxi.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwgezcri.html

getenv("APP_ENV") ?: "production"
来源：http://dali.bjfxy.top/Article/details/gt2ofypoljs.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gt2lseyotmh.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gt2iuqewpmd.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2erdopigv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gt2dkxmlwdz.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gt2ncbezcrk.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2peaaaihb.html

[U78] PHP：单元测试
来源：http://dali.cheryme.top/Article/details/gt2pdabwspr.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipbydrdj.html

[U79] PHP：静态分析
来源：http://dali.zdqjudy.top/Article/details/gt2egfinmcx.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icdcmgcd.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gt2hkvvgqed.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gt2devyfwmu.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gt2ysfzaxso.html

npm init -y;  npm i express
来源：http://dali.zhiwuduotai.top/Article/details/gt2vltwrmnh.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gt2uhcpxmay.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbkrclqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2ecoonvyq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gt2ovupdklm.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gt2qmioepao.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gt2cgonpjup.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gt2mhsvzpip.html

a?.b?.c
来源：http://dali.jlsjyb.cn/Article/details/gt2qtpgivnx.html

[U86] JS：空值合并
来源：http://dali.hfpthk.cn/Article/details/gt2rmskeuiq.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gt2myiqwibp.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gt2ubaoakar.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gt2eysmmwrr.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gt2dbvcwnps.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gt2qqtdrisa.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gt2eyhanyke.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2wphmrwsh.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkhhgtet.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkcjnybc.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gt2tqqghvof.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gt2mltvteyx.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnrushwi.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2wvktubnu.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2aumkrfpv.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxujdesv.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gt2alwbrndt.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gt2xvproiui.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqvczxuc.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gt2skhhfory.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gt2njcpqhvz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyfmajvg.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gt2yfrjomec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2syqqksfc.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2wyccyzlt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gt2qbbnpyjg.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gt2lamtbtlt.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gt2emtdnnlw.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gt2qdyuwfuc.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gt2ooxqehip.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2fjtiizsf.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gt2bieodqpu.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gt2cagsltyt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gt2bwiqpure.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2jpeovqgk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gt2arkyywut.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gt2hmpfbsmz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2bjdavbld.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksbafjqx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gt2zgxdnszr.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2nemcnbwq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.bjfxy.top/Article/details/gt2wuuucphd.html

[U107] JS：数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kczsgyos.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2getzfsri.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gt2epfkahtq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gt2oajekarm.html

[U109] JS：数组分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnayndns.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2fneigowb.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gt2edboxidy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2czxqooar.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gt2ljkgtujb.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gt2mjowytvp.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2uofzcidk.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2xscqzvid.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gt2osouxeep.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2bljsdamp.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gt2weqzpvpp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2uvftzyur.html

[U115] JS：生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2utzpcbch.html

crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2hdvrnwpn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gt2blmhkqal.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2wqqppcno.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2neksybiy.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gt2kdlqlhks.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gt2kgzggili.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gt2vtysabdm.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2hqnmnhsf.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqfpaqdp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gt2egctfbix.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2chwkqbkv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xlougmjo.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gt2ptnngovy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rbjyfcqq.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gt2spaqnvse.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gt2hwlgraes.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gt2xrpmurqx.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gt2xhlnpfcc.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gt2tmydynib.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gt2agdooqhb.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2qxsvonrm.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gt2beivacjc.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2mgekcjsx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhembpmq.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gt2vgkbnbeb.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gt2soudejxe.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrawgmhg.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gt2jhurcjhx.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gt2oyprdbcw.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gt2kcuqlcbf.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gt2qklzgorh.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gt2tompinfq.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2srxeijra.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gt2nixvmffl.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2hinpxbyc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2pysvjesy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2fgzadibi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2yhdyubsh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gt2bjnokfki.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gt2kbqsrifi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2afbgwipa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2sqvcdquu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gt2nrexlkmf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2yeywsitl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2giewciof.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2axfnyfam.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2pyqrknvg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2hxuhwjga.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2xmghtkbe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj202588.top/Article/details/gt2nqjpupjn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2veefnucm.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2mmxnlikl.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gt2pktroneh.html

S C / C++ 专题                          60
来源：http://dali.zycfv.cn/Article/details/gt2liwpedte.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewkslokf.html

U 高频实用片段                         120
来源：http://dali.0kj1m.cn/Article/details/gt2llizqdbr.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2yzfldlnj.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gt2nvdoyqob.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2zvhupkdc.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gt2vjrjkeit.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2uqmwvfgb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guannengcc.top/Article/details/gt2ocwekeoz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gt2mzuykfuf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gt2itorqfxh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnqzz.top/Article/details/gt2qmouisms.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gt2xxfaapdt.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gt2rspiczph.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wzkjugjh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gt2akotsmey.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gt2klqvvnri.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xkiocwvy.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gt2mmcttnds.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2oibzdjuf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gt2cbyzhtrm.html

SQL · Bash · C · C++
来源：http://dali.zhengqikj.top/Article/details/gt2bvqrpuvl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gt2qjyhlboi.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gt2dkgeqtse.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gt2vciyvxsa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2kddyalzs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gt2izauefwv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dormxuwr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gt2jkinjtyw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gt2fvlpvgft.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.0kj1m.cn/Article/details/gt2ngzdvodj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cdnleiting.top/Article/details/gt2dkkvelcy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hnqzz.top/Article/details/gt2vxgkvkqr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2lhcdlzdk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmnxrkbx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxinkj.top/Article/details/gt2obdpkzbt.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gt2iwwfgnfx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gt2pdpkftvw.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2ktsjpbma.html

目  录
来源：http://dali.xylfe.cn/Article/details/gt2ywhggbba.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2fiooddtr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hionubnl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gt2oraxypfi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2heblwvzf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ydiqldsg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aazpnpne.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2nciywiut.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2gvjqtoue.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gt2uwbdtkjv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2uuvmmxox.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gt2zizbwgya.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vylcbxpc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2ncrmvpcx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2ujpopnec.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gt2aznlyric.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ivvv.top/Article/details/gt2ocofulhn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2gbvzvapa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gt2swmklser.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2njevtugb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zycfv.cn/Article/details/gt2ulwjgfdk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gt2hkxstpgq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2pftthqrg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rjfzepyg.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gt2kepfrmok.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kcuivhhn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpprdiqw.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gt2eoufggxp.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gt2jegzvotc.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gt2hxyzslph.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nwbrower.top/Article/details/gt2qezsmvjf.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieycwpoy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gt2mwknomsd.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2rjgawwhk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2rneactpg.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gt2tytpjhdv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gt2hngtfgrx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2msakweuf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xditfgvr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpmvpaic.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2mpsopjui.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gt2aixwrslf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guowangkeji.top/Article/details/gt2fuhmcsfz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2arauvrhs.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2isdjnchz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ivvv.top/Article/details/gt2sbpgvyeh.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2nexqpxhz.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2qomnfxau.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2uwnegqdr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvkavjeo.html

Go:   const PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gt2zdmizlxs.html

Ruby: PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2rdofspxm.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2frtqdcfe.html

[A04] 判断变量类型
来源：http://dali.smart0.xyz/Article/details/gt2dstolpzc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gt2rcwylmrm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gt2wjhqkvfg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2pmfhntxp.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2poqmhrji.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gt2kzttngio.html


<!-- 参考信息 -->