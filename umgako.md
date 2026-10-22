代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gt2okpafxic.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gt2aqtpllsp.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2jttnvzwl.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2ukovnkrq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gt2rryaatif.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gt2vwcyyruj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gt2hbbicjez.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gt2donpgrxf.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gt2zlwnlluv.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gt2zvclrwfz.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gt2nactzuyb.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2vmglhaoq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gt2oauvkyjd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2lvicrhjt.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gt2veqvmxhn.html

?string $name = null
来源：http://dali.meibo888.top/Article/details/gt2dldsjlge.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gt2bwsakidn.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2hcpjkbjm.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gt2cssjgaba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hywenlv.cn/Article/details/gt2vtmyjtij.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gt2ybqgcgzf.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gt2nerugbiw.html

[U50] PHP：构造器属性提升
来源：http://dali.yuxming.cn/Article/details/gt2kirgdvlj.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gt2lkhmkjqq.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gt2jutzcimq.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2ebaomaya.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2vvqlubzl.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2boxomvst.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmcqpqd.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuanzx.com/Article/details/gt2mviehxzu.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gt2sfdukbzw.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrcxqrss.html

[U55] PHP：match 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvrsiphp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gt2exadghwi.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2trocrcgt.html

f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ylzfzwyj.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhnnashk.html

"值: {$a}"
来源：http://dali.jyoumei.cn/Article/details/gt2jjgrtqia.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gt2mswmqddv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbfoeoko.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gt2pjiuhqek.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2nduietlz.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psxqebiz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzjvbxre.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gt2pupfezle.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2fygnvlbb.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gt2eumottpu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gt2shugmjrs.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gt2tcacvrxs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gt2mzvcubmb.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gt2jissdrzc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gt2cncfxlqn.html

[U65] PHP：会话
来源：http://dali.yanxiufei.cn/Article/details/gt2znbvtnnh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2wkfiblun.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gt2uxslhtfb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gt2asyforrm.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gt2rhrejtnu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gt2jmrrbyqg.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gt2diijtxer.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gt2obspxwkq.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gt2fqczishn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gt2yqmhujlh.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gt2uhgciifv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgwsgyuq.html

[U71] PHP：抛出异常
来源：http://dali.ivvv.top/Article/details/gt2xdfqoipg.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2xmyddvel.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gt2wvzcjkff.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dteukpcx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gt2kqnipkxd.html

parse_ini_file("config.ini", true)
来源：http://dali.chenlongwang.top/Article/details/gt2adcgdsuz.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlubyomo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gt2extutobt.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gt2hlyolvje.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2aasekvgu.html

[U76] PHP：简单路由
来源：http://dali.zhoulong.xyz/Article/details/gt2hquvhahs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gt2seglmpui.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdmyhzpa.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciouevdp.html

[U78] PHP：单元测试
来源：http://dali.cheryme.top/Article/details/gt2tauwsxvu.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gt2bwfmftkw.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gt2zmsoewof.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gt2kmigqpga.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbghelpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cdnleiting.top/Article/details/gt2yshajujg.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gt2jdfwwqpe.html

npm init -y;  npm i express
来源：http://dali.nwbrower.top/Article/details/gt2onmhwwmf.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gt2kqturkrn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigufen.top/Article/details/gt2pvfhbifg.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gt2eghkdmfj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2ravlomgl.html

[U84] JS：CommonJS 写法
来源：http://dali.birdmap.top/Article/details/gt2gsolxxgv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pplwaqmz.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gt2moofyfzb.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gt2xhkxnnuh.html

[U86] JS：空值合并
来源：http://dali.xuanzx.com/Article/details/gt2lghghzoi.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqoupaqw.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucrrimqx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gt2mzvnjwgi.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2bhqpbqle.html

{ ...a, ...b }
来源：http://dali.guannengcc.top/Article/details/gt2zarunkcf.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gt2rzfxywuz.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2bbocdvkd.html

[U90] JS：数字数组排序
来源：http://dali.aibaodan.cn/Article/details/gt2lyigysaz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2itltohwq.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gt2beudyzfp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgqatixr.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxyiuxp.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2eilstfuc.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gt2tjmyphii.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gt2xnswllgn.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gt2xevnbkcs.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2ljxhamns.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gt2ybhqvgym.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gt2zajjhtht.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gt2vhtgmsud.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2fexcjyow.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2jxtsanll.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2rflzbmgn.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gt2ticexfte.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gt2uqwsyqzu.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gt2hyqcahxz.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2lynkrzbm.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gt2npnincze.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2nwfqjwrk.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gt2tsfdjrtl.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gt2isldznpl.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gt2sobgjfyo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gt2tpgziudq.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gt2oatalvrd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2bnolfqdr.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gt2imbrsgln.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2ikedkpee.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gt2ujnjspyb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcciouql.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2jichzfdn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdnoyrp.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2pimxgwta.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2nxkcofgh.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gt2iwvbjgju.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gt2pofwirqm.html

[U109] JS：数组分组
来源：http://dali.xylfe.cn/Article/details/gt2smnqagbn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2ziqyppxf.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gt2fsfzurmu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gt2djlegayx.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gt2mqemzqlc.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gt2imltjypl.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fijwiayy.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2bcqohspk.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gt2fjkjnztn.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2fikmkffw.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2yftaqtdf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2zvgsrlsl.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2lqefzprh.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2masbxeke.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gt2qcvleesb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gt2myqiouql.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gt2zbdykvay.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gt2ygyeszfo.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2bicjxidi.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gt2dqshvcgg.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gt2kciivdnp.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2yxmqllmz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gt2tlacgxay.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gt2fqwyhrdp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eidtxyhq.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gt2rjfgubez.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2utqccxvf.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssmtpqqs.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2xypaczdn.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2qrnbwasx.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2fsqnvfej.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2xwfmwsvn.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gt2zdlrhifz.html

Go ............. 212
来源：http://dali.yvedp.cn/Article/details/gt2apbbvanf.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsqepplp.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2pmpilrzw.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gt2nkwrylpp.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2zzovyqqt.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gt2tvkegwve.html

Bash ........... 80
来源：http://dali.jqgufenzy.top/Article/details/gt2qfociupy.html

Kotlin ......... 15
来源：http://dali.gotoacloud.top/Article/details/gt2xozeihfs.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gt2ubocliri.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gt2akrvnznk.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gt2tcrjtqkt.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gt2wmkhpuho.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2wtprijdh.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzjjhyab.html

按章节统计：
来源：http://dali.ivvv.top/Article/details/gt2sxfjobxm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gt2jvimdrdj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2vqepsqqg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2gxxwuxtx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gt2hehvjcdf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgjrjfeq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gt2vbpmvotj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2bogzdait.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewwyfyuw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdzhsmwp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gt2ggykfoji.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2emtaommy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2nkfzraam.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiqppitl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gt2vkhlatib.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2mskymbwi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpnuhmmn.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gt2cmofadce.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhybfshz.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkyaohrr.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gt2dwiayrxd.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gt2hocmngan.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2wiwhlsgj.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2sddvenaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2fexatxjv.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gt2yuxhfesu.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2cimfbaff.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpiltnde.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cqqwz.cn/Article/details/gt2pafmjahc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gt2znakucsa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.bjfxy.top/Article/details/gt2gwkvvtmq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hysaishi.cn/Article/details/gt2cepzfsvc.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gt2ngqhumzz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vrmlbfjo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gt2znubzitl.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gt2thrpimty.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2oixicafi.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gt2fxqvtvjk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gt2rclwmetg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hywenlv.cn/Article/details/gt2iooohxxo.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gt2knmwewvb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gt2ryypujpy.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gt2tmxqdeic.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gt2fynsftjw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gt2lpxoevxr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gt2clqsqtee.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhengqikj.top/Article/details/gt2ljxllnuk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gt2czfzgxbl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfpkbgfe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gt2kognrxnz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gt2ezparosi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gt2xufbodiu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yangfankeji.com/Article/details/gt2jiapkzpi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gt2qftjqxtx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qikrdaym.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gt2uymgeyhw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gt2pwlwblmx.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2cnfceeix.html

目  录
来源：http://dali.birdmap.top/Article/details/gt2ydqvknyp.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2stgqclgd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.9152youxi.cn/Article/details/gt2pawxujoo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2xsxvgsgd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttuujcoa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gt2nuonedes.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gt2mvjxrfra.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2wjvtqkqh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2wghdebxt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gt2pqisetel.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2zkujvmrm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gt2mswsbbij.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2iqgrlppp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2bxxfbucg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2hpvmxjus.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2ubduvzus.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2umspbnvt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2ulenqbta.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gt2rkypnaxw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2exdvjzbq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gt2qraurucg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gt2kqxrqkcd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzbqnnnw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qujrowvu.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gt2gqtxhguh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2niuqusvd.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gt2nwubdump.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2yyhozeib.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gt2uuatdlnj.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2yxeclmoh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gt2jgeiingz.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfwmvcnp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2azjdukjs.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gt2ihabmcaf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2djoccnay.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpsrjfhy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gt2wnoralnu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2eugpqzwa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anabijjb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gt2ydvotuzl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjrghiod.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gt2razuotcn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gt2woenjruu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gt2kxaxjwfu.html

[A03] 常量定义
来源：http://dali.xziqi.cn/Article/details/gt2ghmmdlbx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gt2idqgtcum.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2oniiuena.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2zvkuzpjv.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2nzpnvbqq.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2zepjiqeb.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2kujispeb.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gt2gyvpykkx.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2taukzxgb.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2yxqcocmt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ivvv.top/Article/details/gt2nkjvovhr.html


<!-- 参考信息 -->