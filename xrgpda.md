代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwopeexg.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmvzmtpq.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2xuaacwjz.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2ndnalgnm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gt2jcmkxcgv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2cvatrrtd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gt2zexpmjwo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gt2jvccvrte.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2ziffpexe.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2mzdivfmk.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gt2zdciyrab.html

declare(strict_types=1);
来源：http://dali.nanxinkj.top/Article/details/gt2cnetimgz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gt2eugtlnpp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2ocvmoujq.html

[U46] PHP：可空类型
来源：http://dali.xziqi.cn/Article/details/gt2wsendflf.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gt2dazxyzhv.html

[U47] PHP：联合类型
来源：http://dali.yonumen.top/Article/details/gt2fujtvxtx.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gt2veqdkzuv.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdjwewch.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gt2czyozebx.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gt2utgxorxz.html

public readonly string $name
来源：http://dali.guannengcc.top/Article/details/gt2aeogrnvf.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gt2ezbnafhr.html

public function __construct(private int $id) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uliivjuk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hhywhoed.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2wguutoob.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gt2arxbaiou.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gt2wcinhfhy.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2gcqrqqxi.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gt2pfqqncow.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gt2dlwcizqg.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gt2ufagtsba.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2vljqlmom.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2hvjhckmw.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2dbanndzn.html

f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ebdcwwqy.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2aetqdzvn.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkhympbh.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gt2ubzagnew.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gt2iounwclb.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gt2wkpdywul.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyafbuns.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqcepiju.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gt2qbfqmgee.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gt2sipifbbd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2zbsydetw.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gt2ibimndte.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyystccq.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gt2pqhbgnhe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gt2datsrskm.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2bdqwbdef.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gt2ofeoxqbz.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gt2qzufvptd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2utkootyq.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gt2vystvyuj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.andypj.xyz/Article/details/gt2piuhagda.html

[U67] PHP：处理文件上传
来源：http://dali.hysaishi.cn/Article/details/gt2uineewyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2eiuhpbcn.html

[U68] PHP：PDO 连接
来源：http://dali.ppjwa.cn/Article/details/gt2pltpyigf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gt2dbtebvxt.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gt2brvuhxaw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2zavxlhbc.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpztenbr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gt2fijsouih.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2gbbvnzkb.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gt2lbvsqhdd.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gt2jxgrvyps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guannengcc.top/Article/details/gt2vugmiydu.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkriwvzj.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2tncniajv.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2bnlxqdzw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjwpdrdu.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gt2mksqzmtl.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gt2ayusraec.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gt2wapdwdcw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smwjetwn.html

[U77] PHP：模板渲染
来源：http://dali.jyoumei.cn/Article/details/gt2pndqyfmd.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gt2rtswaxtg.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gt2stwkfghb.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gt2wmglacsf.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gt2yreikqzi.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gt2hifkqtcn.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gt2pbpnnlbj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gt2rmolkhmv.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gt2swjghspo.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gt2vxhrswbg.html

[U82] JS：package.json 脚本
来源：http://dali.zhiwuduotai.top/Article/details/gt2urcozclk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gexqgbpg.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djhnxufu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gt2djhfiwfp.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gt2cygtnntf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gt2zfidszie.html

[U85] JS：可选链
来源：http://dali.gzhubu.top/Article/details/gt2xcxtxpvz.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gt2aqhuaghj.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gt2pnhhvtdl.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gt2vzsixtpz.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlwlsjou.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gt2blbdosgf.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gt2bvfgjiaq.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gt2oumqwzlf.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttiwmvmy.html

[...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2fcbtpxez.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gt2yodnsefw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2gxzwsvyq.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gt2bohnfdvh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gt2bxzpjocy.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2awrvffmd.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2zgxuhasd.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gt2knplwjau.html

`共 ${n} 条`
来源：http://dali.pycfn.com/Article/details/gt2xrikjpcb.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gt2ifglgart.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2apwkdjht.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyvupivr.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gt2nyidyydb.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gt2zcypcrdo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2kphmjves.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouzupobl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2cjbyzbds.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gt2inflyzzh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bouxyxsm.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gt2twbmxvqc.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrznjhpt.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gt2kjidbjiq.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmysqnfx.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gt2itbyityp.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gt2dqewibig.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gt2xycckvuu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gt2sfbyuril.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2awkmtrun.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yangfankeji.com/Article/details/gt2ljatlceg.html

[U104] JS：防抖
来源：http://dali.zhoulong.xyz/Article/details/gt2bmebyess.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2olykqeky.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwxzctmj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tanke756.top/Article/details/gt2nozocnzd.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2qpdnegvv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gt2sbycnvni.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2ryxufnlq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2dfiqizng.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gt2xossjhyp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgqzmgdm.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gt2jnhlvclz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2nrnptccw.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqxpbzpa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gt2njixzyjx.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gt2nbjukfqu.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2vaddhcai.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gt2ngeqazoa.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2rqvgrpdv.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzxptqos.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2rquimydj.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gt2dtptrsac.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsdgnqif.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2kinehvzt.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2izykcndr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.vqdsnc.cn/Article/details/gt2muxnhzsk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2bgbsjtuc.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2vsidwngr.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gt2vrvjwklb.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2oyiexxwu.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmxxwaxc.html

[U119] JS：生产构建
来源：http://dali.guannengcc.top/Article/details/gt2ygkkecmk.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2wkueinuj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gt2xdobwgdl.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gt2dobynnqs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdxqjcog.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gt2xsazdmvd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wosyrhjx.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gt2nczevgsl.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gt2lfbtagbu.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkslefgr.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gt2omtwahyc.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2rplnvwpn.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gt2klcnygxt.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2mltaghai.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2zpxzjlug.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gt2povycway.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gt2icacidwc.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gt2czivenve.html

SQL ............ 90
来源：http://dali.haohaochexian.top/Article/details/gt2xodunvez.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2qmtouqax.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibqrzxrx.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwyavzje.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gt2xspgrrtm.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gt2ewdbqell.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gt2mkjforsk.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2pnimnsdb.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2zqyehhxf.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gt2sbxogoyb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2jwmcqihb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2ekprurjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwywuspe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gt2njlrukfu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gt2yfgsfpti.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzxnwogj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2snnilroq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gt2ticmpdfp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2lilnavvb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2qttcekva.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gt2oqeokxcd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2yfexotgd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2uulqffoa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2spagyunx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gt2laeigfsf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2umudmajq.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npqziade.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gt2jacnvzax.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gt2akpxejtk.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gt2xgyjonmi.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gt2bepireel.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2ajmliltd.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsnpcikf.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2flxujrra.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gt2wlgjaoxl.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2vlnuezpg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gt2spfojsho.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gt2pyfdgvul.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gt2fjdkqtqm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.snrcjt.cn/Article/details/gt2wiwaahel.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daria6918.cn/Article/details/gt2gvqngxgg.html

—— 文件结束 ——
来源：http://dali.nwbrower.top/Article/details/gt2hmavmhpu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fypezdnt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gotoacloud.top/Article/details/gt2lzqradnj.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gt2jxmbnybu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jezqmwtc.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gt2ijdjiebk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gt2ekjsspnh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gt2xlfbqqzr.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gt2vyofqstx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gt2melcwfrc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmqhvgd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qndmpske.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aizwys.cn/Article/details/gt2cjfgxggg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigufen.top/Article/details/gt2fhjcrcml.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzwluryz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tianlin.xyz/Article/details/gt2boltgdtm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmlxwtbi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gt2shwuyjtw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gt2xqtllhwm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypvqoaph.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2gxconqyq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gt2vloocctg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gt2dycacbbp.html

【文件统计】
来源：http://dali.jlsjyb.cn/Article/details/gt2aqkeziih.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gt2oxdertga.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2xqfkcrki.html

目  录
来源：http://dali.ivvv.top/Article/details/gt2bdxeseiy.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2bezdbhcn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gt2ntvwohpg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2ldtfpywt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gt2lymlliwr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2jbrtljik.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2ewluvuow.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2ziukpmls.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2mtfczldi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2zjwlycjv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2hijhshrs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2acrxhnjr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2lruiwcqg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnitwhqd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2xhwvhddy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2phdgxogb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gt2yqcsyoko.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2khzuzdkw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2jdjiovle.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gt2iggiwpjy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gt2jpwegshu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2dnewglmj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2oywazmda.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucaqvhit.html

A. 基础语法与类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zejrlnfu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2spbmzner.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2bmovabyz.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gt2anfjnhww.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gt2etowrdfb.html

JS:   console.log("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2fzpkpcof.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gotoacloud.top/Article/details/gt2rckjocjt.html

Java: System.out.println("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gt2kkygzwen.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2vvraxwrd.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gt2tbvkkzmf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2uxemzzpq.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gt2jspzymkk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gt2clxxqjve.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2xgtkczbq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2kbbodakt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pycfn.com/Article/details/gt2aibpycob.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieefnost.html

Go:   name := "Alex"; age := 20
来源：http://dali.redwolf501.top/Article/details/gt2pitrtzaw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yknizkvk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iciwoxkc.html

[A03] 常量定义
来源：http://dali.smart0.xyz/Article/details/gt2xtrizazv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gt2ofgmepzd.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2fjqlxyga.html

JS:   const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2cickxrii.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2hgydymnv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcfjortw.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gt2wfmflmcd.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2huartypt.html

C#:   const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2oelipadq.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2ljkwuiem.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gt2crscwkff.html


<!-- 参考信息 -->