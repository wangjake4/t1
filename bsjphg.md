代发 wailian999

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gt2jykyglwy.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2zfrckltu.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gt2gczywtwa.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gt2qosblccx.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gt2mhwinklw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gt2kboorruw.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gt2efmfneew.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gt2vgyedexb.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gt2eqgniksq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyuqdtko.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2vhshuila.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gt2lcddipqn.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gt2avkpnboa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gt2fgbgglrj.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gt2kfidqpmu.html

Path(__file__).resolve().parent
来源：http://dali.yonumen.top/Article/details/gt2auetemdm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gt2uhjjrcmx.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gt2bnyozoba.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gt2mqjzmttx.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2hqtffoxn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gt2bhxdjyof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gt2bsxgdzoz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2hqtnnwml.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gt2eoduawox.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2yhwtmnvg.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gt2rgkomyzn.html

[U44] PHP：开启严格类型
来源：http://dali.guannengcc.top/Article/details/gt2nvgoboto.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gt2tqulptrk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gt2yycogmng.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2woduybqa.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gt2ynbqjiii.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gt2zbsznuem.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gt2ycnsxjev.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gt2pqkdnkwc.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gt2fbfrqbii.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krrueaio.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2crgfdjcf.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gt2dqqkmxnc.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gt2foudyern.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gt2gcxfzptn.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gt2lvxwvrri.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gt2fiwgcvku.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gt2djrpdxim.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gt2vnzjyfqs.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gt2bzvlixjk.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gt2xzuxsspw.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2jkdsxjwm.html

$obj?->method()
来源：http://dali.fzhhl.top/Article/details/gt2icsntvec.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2burmdvpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2aqihmrno.html

[U56] PHP：命名参数
来源：http://dali.xylfe.cn/Article/details/gt2uaqytcxq.html

f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2tnrvceui.html

[U57] PHP：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2wuozelsn.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gt2vuclmxeh.html

[U58] PHP：数组三件套
来源：http://dali.yvedp.cn/Article/details/gt2okvzkpue.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2soguanww.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gt2swivhsgy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gt2werhemhz.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gt2ubqbzwgw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gt2gtoyghrp.html

[U61] PHP：正则
来源：http://dali.yj202588.top/Article/details/gt2ldzfvyis.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2zwuokgxj.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gt2looqjlbb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gt2obaxkyqp.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gt2deostzcr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gt2nsuuorta.html

[U64] PHP：目录遍历
来源：http://dali.0kj1m.cn/Article/details/gt2jydvfmpf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2meycfoim.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gt2aaqsllqr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2gyitpcsy.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2izbxbrug.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtlqgpwh.html

[U67] PHP：处理文件上传
来源：http://dali.xylfe.cn/Article/details/gt2kwfizcvg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gt2kquhuhcb.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gt2tbrdsrhq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2hueuzxtv.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gt2emflysax.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daxiang520.top/Article/details/gt2qvhwstvq.html

[U70] PHP：PDO 事务
来源：http://dali.ybcxt.top/Article/details/gt2aflpjarx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gt2tqutpcbu.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gt2ptssxbeb.html

throw new RuntimeException("失败", 500);
来源：http://dali.pycfn.com/Article/details/gt2aftarojk.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htknpnev.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gt2ueguljem.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gt2wjutihmf.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gt2fuquland.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2kegjdeii.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gt2ucmggtwa.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvxqxadc.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gt2noztcbdz.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gt2qtgolqsb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gt2iacrrmzc.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gt2nasinryr.html

composer require twig/twig
来源：http://dali.xziqi.cn/Article/details/gt2timtagrl.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gt2ficdcvux.html

composer require --dev phpunit/phpunit
来源：http://dali.mhx1999.top/Article/details/gt2bxhukogr.html

[U79] PHP：静态分析
来源：http://dali.gogol.net.cn/Article/details/gt2rxmsyjnn.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gt2nsrvvzvx.html

[U80] PHP：代码规范修复
来源：http://dali.ehwqpu.com/Article/details/gt2swcbzqmx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gt2bcaanlqo.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gt2bydnfeli.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gt2bmoxtyaj.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gt2wgbhjlyy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gt2iiejzbfk.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gt2fotbquxp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2jnquybqa.html

[U84] JS：CommonJS 写法
来源：http://dali.cheryme.top/Article/details/gt2saldjijh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xziqi.cn/Article/details/gt2fgwnektl.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gt2nznnmdxf.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gt2ksgniosg.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrlamcyc.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gt2ffxeopzn.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gt2jwlzwhmb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ydzc1.top/Article/details/gt2vygbodbn.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gt2olkwccqi.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gt2vqrrxynb.html

[U89] JS：数组去重
来源：http://dali.cqqwz.cn/Article/details/gt2znzuxbwl.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2topotubk.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gt2drttelrv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2uqicdsqx.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gt2gkaczuth.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gt2hqwhpnkf.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2rsteggbv.html

structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ghnqdkst.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2wjryllje.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gt2xoquniwk.html

[U94] JS：箭头函数
来源：http://dali.redwolf501.top/Article/details/gt2wgxzlzmq.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2pujcdzfs.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gt2kptnghlq.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gt2cdntvqnd.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gt2qxgtcxfc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2urqzbkpa.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gt2yaivrkdu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2jjdqdfbh.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2rvrixcry.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gt2kubozsan.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2usupxqic.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gt2dzmzvubv.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gt2vtvhxdyh.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gt2vjpucrcu.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlpuvwuc.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gt2yoxprajb.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2duwvyrvj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gt2btpsumlx.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gt2fllcnlio.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gt2gkgaybos.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gt2niyzesbj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2mweqclzv.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2aimhxrum.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gt2ntiqnzlr.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmuxcvic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gt2srtmsgnm.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2ktnvkqsi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2ulijtith.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gt2whragkxx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkxjldkj.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gt2jukgpbhv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmslxnix.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gt2hoslbpiv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gt2bezwrfda.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gt2xrkjtryb.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gt2lmhdwota.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gt2rbxccjda.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2luoywahe.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gt2vmlvindv.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2alvlmrbc.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inuttpto.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2xhekyyxy.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2iqggnokd.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2fjxynoys.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yonumen.top/Article/details/gt2fcwaghwd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnfpnamn.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2ieutomaj.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gt2uiimhtuv.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxmrrqmz.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gt2ucizvjxo.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2zhvwtpvj.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thxhrqck.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gt2bdlttagn.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gt2vggxyibt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2owatlzoh.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gt2qzayoano.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qglynguo.html

按语言统计（条）：
来源：http://dali.kuanghao11.cn/Article/details/gt2kvspbcga.html

Python ......... 252
来源：http://dali.jiagoushi.top/Article/details/gt2dpiuqmcw.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2xmdjzwpa.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtyrcawg.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gt2fhlmtyta.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2qedfuvkc.html

Go ............. 212
来源：http://dali.yvedp.cn/Article/details/gt2yliwnlgr.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilmnpnfi.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2lsrpazqc.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gt2jowitonz.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2gaddlqqm.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvcpynzl.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gt2ufykfwuu.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gt2zuqxcjqa.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gt2duiaesky.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gt2myaoncdn.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyhdxnje.html

Scala .......... 10
来源：http://dali.shuidangran.top/Article/details/gt2voelekhz.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2zgliyduu.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gt2wtflqgrd.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gt2eobrjnti.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2yawwkgbd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2powkzzos.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvyfsbzf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gt2cmvicjly.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdldzsoc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jymocfhy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2objgnkto.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gt2lzrddifz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2canstitx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2bxvyxoup.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2btbxrviu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2daugnhtv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehmtjggw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gt2xdefyzst.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gt2iedvjjeh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2ispghmat.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gt2ulibknls.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gt2njhqgdqi.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gt2laoyasnl.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gt2dboiiron.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gt2jdoaturt.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2uapkwvfi.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gt2kpvpyqjw.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2jotsragv.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2lufqlfxy.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2cvoqqjzu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbzfcerw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gt2hjadcrte.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gt2lffrcfpo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gt2pwlabwsz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gt2xkujldsf.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gt2jbbalthf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tqawzzbb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuanzhike.top/Article/details/gt2xuydszzf.html

Common Programming Examples Cheat Book
来源：http://dali.cheryme.top/Article/details/gt2ynhrdwbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csfuelza.html

【收录内容】
来源：http://dali.nanxinkj.top/Article/details/gt2gtwxqeyr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqtxcfoe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuanzx.com/Article/details/gt2olbtukbg.html

SQL · Bash · C · C++
来源：http://dali.birdmap.top/Article/details/gt2ftaxjizf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gt2efzgqvup.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gt2dkgikrfl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gt2emnctmth.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gt2qylmbxgr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gt2igbdcrnb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gt2sxakqizw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shuidangran.top/Article/details/gt2tibdzmdy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gt2nziwblud.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gt2htsqimzb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gt2kghvbnyx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daxiang520.top/Article/details/gt2hmuzjddy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tian-w.cn/Article/details/gt2hhqbbzwv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gt2jfaeoxwt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xziqi.cn/Article/details/gt2odgbsonm.html

【文件统计】
来源：http://dali.cashguo.top/Article/details/gt2rvbptuar.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2kimgyizc.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2dexsdflh.html

目  录
来源：http://dali.gzhubu.top/Article/details/gt2bdqaeihm.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2vdvnqlzh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gt2qqdexzvg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2kxvjfykm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2gozkyzwu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2ouhvypwf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cashguo.top/Article/details/gt2qdmvwedv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2yblsjugn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2gcpxecfp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2vtyriuoq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2oqiwnemc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gt2nifwifwn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2cqghtckq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2kfnmfgnt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2qnryrboe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gt2svctqjbo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gt2vfixauna.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ewdrtfdg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gt2odsxjikk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2hvdsbiwa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gt2vbuodacb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2cfdfugux.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bexstosl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2mkugwlas.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gt2kgolwmad.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nizgbfrt.html

[A01] Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2tisjkjaq.html

Py:   print("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gt2niroxjgo.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gt2bwgpunbd.html

JS:   console.log("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2eghyvloq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.bjfxy.top/Article/details/gt2iwfalwof.html

Java: System.out.println("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2mntglugf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gt2ekljijdl.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gt2lgllpmch.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2klrfoiuz.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcfgpckm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gt2cepioglm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2dkodnnzp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2tixqicns.html


<!-- 参考信息 -->