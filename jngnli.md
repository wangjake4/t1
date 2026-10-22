代发 wailian999

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gt2qbfnyqha.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aogcemus.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgdxvzmp.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gt2funsejtq.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gt2dyfictns.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2pozspcmx.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gt2greicxyz.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gt2adchsbdf.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gt2xamdchem.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gt2tjojyemb.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gt2ukxcfabt.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gt2ugeaorxi.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gt2niizvoar.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gt2cvrbxept.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2ytfrloal.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gt2neqlpslh.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gt2voxpbzum.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gt2qjclfqfx.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gt2jvnpcnwn.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gt2wbpbjmln.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqyqddwb.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gt2detstttb.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gt2igixlobk.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfmxkoxw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2oeuxdert.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gt2kkpylsbk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gt2oswyfdrc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gt2jbpynmxd.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gt2uzlouqwa.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gt2evjqmxga.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gt2smlkyjyw.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2rbpgmlme.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gt2gulcbywp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2sqpgkuqe.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gt2mfkgcdjv.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gt2eawcwrll.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gt2wcejrdkn.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2ugofkrjv.html

[U48] PHP：纯枚举
来源：http://dali.ehwqpu.com/Article/details/gt2mnfvviwz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gt2hryesguy.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2ixmfldrk.html

public readonly string $name
来源：http://dali.jlsjyb.cn/Article/details/gt2maetxdns.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gt2rpnnnyhw.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gt2lxahfuxt.html

[U51] PHP：数组解构
来源：http://dali.bjfxy.top/Article/details/gt2htupisea.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gt2psgveutz.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2ybpoyzep.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2rupsenlk.html

[U53] PHP：空合并运算符
来源：http://dali.xinyue.icu/Article/details/gt2japrsvfa.html

$v = $a ?? $b ?? "default";
来源：http://dali.cdnleiting.top/Article/details/gt2fabhvawx.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gt2guvjctqa.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gt2afndeppb.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2zcmlwpll.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpfdxddp.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gt2ukmvkjso.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gt2xunnqhah.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqtbsyfx.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gt2vqumdbql.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gt2iveduhsu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2ednzxeix.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocqnqniw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gt2laschrkp.html

[U60] PHP：JSON 编解码
来源：http://dali.cqqwz.cn/Article/details/gt2jpumyocz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shzxlz.cn/Article/details/gt2ienqusfz.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gt2ktcqmydo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ffuoqrew.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gt2mnjicclc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bktxbokm.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gt2jewlltbc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxyenimw.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gt2lqbovhxp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gt2efriyvfs.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gt2kytbldfo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylcybago.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gt2pyohweab.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gt2sbibtxaj.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gt2hhgjhcbh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gt2gjrxiwxz.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2budnuodq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gt2porwcbpd.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gt2hcutcjfj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gt2qijthlwy.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gt2rcemyfpl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.kuanghao11.cn/Article/details/gt2xrwsmuvc.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2llyfitbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2xnficnwh.html

[U72] PHP：写错误日志
来源：http://dali.havefunace.top/Article/details/gt2wmltpxbc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gt2kdvijscl.html

[U73] PHP：读取 ini 配置
来源：http://dali.tianlin.xyz/Article/details/gt2mhntjowz.html

parse_ini_file("config.ini", true)
来源：http://dali.yongpay.top/Article/details/gt2lxjdzzex.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2dmhwnibo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gt2dilkefzg.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gt2leihqdqa.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gt2xkhhbavg.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gt2ybtdwziq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gt2ykaddkpm.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gt2qdkqphow.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gt2ozluejya.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gt2lnvwdwjz.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gt2kvwvhstu.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gt2twdcnocd.html

composer require --dev phpstan/phpstan
来源：http://dali.pycfn.com/Article/details/gt2pxrmgcpi.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gt2lwydaqjx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gt2irsuzord.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gt2egktjlyh.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gt2wmvpeket.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gt2nprfjvde.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.meibo888.top/Article/details/gt2nkkexivp.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gt2embiwvmw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gt2grealqya.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cenkcbik.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gzhubu.top/Article/details/gt2skqbfxyb.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gt2zlknzjba.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gt2jfegvkaa.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gt2frhjvchy.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gt2iigqdvys.html

[U87] JS：解构默认值
来源：http://dali.9152youxi.cn/Article/details/gt2kgeccetn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gt2avrhgvqf.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gt2yjupajoa.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gt2kufrwrln.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gt2lnrnkmsw.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2ihbvauoh.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gt2tvbtlcgr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2eickbeug.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gt2wstnsjag.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hammf.cn/Article/details/gt2jkccqeto.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2dknymhtn.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2npsliatg.html

[U93] JS：模板字符串
来源：http://dali.yuxming.cn/Article/details/gt2smgjuukc.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gt2ikyopeyv.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wajieiby.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2hmcpmwhw.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gt2dmwvxhlm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gt2fzswskrw.html

[U96] JS：async/await 与异常
来源：http://dali.tianlin.xyz/Article/details/gt2fqzbsifb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2vgjcozqz.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gt2rleuukxj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2lzcljnpz.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gt2fcdijtka.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gt2ayajqtsc.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ginjflmg.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtvtwuls.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gt2rzeeawtp.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxnyuztw.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gt2ogbmkoua.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruislgwc.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gt2tuhvjcjj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gt2txkkpvpe.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gt2emtwitij.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2xhkwadhi.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gt2qumiknxq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twxztcqa.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gt2ghrsyrjf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2fsfotafh.html

[U106] JS：日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2elbtmzqv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gt2xkcyzrll.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2skzjxpkk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2silsbfyf.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gt2ipnodpij.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gt2misascez.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gt2tjdvnbqy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2maqjwzbl.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gt2qomvsdyq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gt2qethagsh.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2vrddopnn.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gt2romgvnjr.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gt2fogykyvf.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2tfufuyrz.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gt2cnpivaiw.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2lahxhifq.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gt2xayoapaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2mykagpbu.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2mafotlws.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2rftuwrti.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmpijsob.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gt2hqrfqbka.html

[U117] JS：单元测试
来源：http://dali.c1oappe.top/Article/details/gt2fiobkqqk.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gt2dgoqbcyt.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2yrqwwwzs.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2kbgsooto.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2kteetmom.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gt2zgzhymdx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gt2ebfalkyd.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gt2teoujjwi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lasorwzi.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gt2lwgdotxe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ypdfqzkv.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gt2kpququly.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gt2lnjmyecv.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gt2ryjydtig.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2jnpjgchw.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gt2jmnshphl.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2xevluplq.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gt2batromqi.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2dvyavzji.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2lhkhbcvu.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gt2vnrwfxqr.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gt2othsdxad.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gt2befspuzn.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gt2jskvaeia.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2jhrfukvj.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gt2hkjwdylj.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2ubelehmw.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gt2ucnpodot.html

Scala .......... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogevcfja.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2otmjexzz.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gt2qzmtvpxk.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gt2chbbtpqo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2xzunpscm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2khyefrbd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2yebwgasi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gt2omsbpbva.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gt2ulmfxswg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmzubzhz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvmhoouc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzzwnumi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2oipamrbo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gt2clijeena.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2diwgzxnu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2wcrdcymj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifkytquy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2nmtthari.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqiymqbk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2pvniqgmd.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gt2ewdthbmx.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gt2pdhknwbr.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gt2qqdyoeja.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gt2frzxsace.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrvuulfh.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2dnzaxkvi.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgekyxni.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2tbydrjsq.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gt2xzptjxvt.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2tbylyxix.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2kgegrird.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gt2ggavkqax.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangdashe.top/Article/details/gt2zvdxruii.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gt2cdbporqy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gt2iugfnwnj.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gt2axcikqdr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzlsvvxr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gt2amoztetb.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2pznppsuj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbrpqgxk.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2zjjeuroh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gt2gvniavmh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnqzz.top/Article/details/gt2laadqofz.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gt2klinpdid.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2ymlunhsd.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gt2kxrldaio.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gt2zetkoson.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.bjfxy.top/Article/details/gt2jwwpriug.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gt2zicumvfn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylqpowco.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gt2ydlhbrgh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gt2fsahyxmg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gt2ydrzbvao.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.smart0.xyz/Article/details/gt2hebvvbdi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gt2nbunxbqs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gt2hpbcmuhu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gt2dndzvmnf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gt2yflxwpwl.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gt2abwcnbzj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gt2puiasaqe.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyovctlm.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gt2zdbyzokz.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2dcgzevfa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ngxspwjb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2jplfiamv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2askdjceq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gt2gbkcewen.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gt2jrepmzml.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2gdvsvwel.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2watrglsl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gt2jevczyku.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2kfigqpqw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxrafkqq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2kpadzeji.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ycjskeij.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffyixuvm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2pwvaghth.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwauisyu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2hmwdkeky.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gt2mzpdhonw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2bkdzzxwp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gt2dvyxohmm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2jeqrcxsn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2qbguyfjm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2lmbqrylt.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2fogbgchw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2idhqejfc.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ifrnlcmy.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gt2nzvgvifs.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gt2esxvjhsq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2wiaztywz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gt2rtzfqyuc.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gt2awrpbogh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gt2yabkdxrz.html

Ruby: puts "Hello, World!"
来源：http://dali.zdqjudy.top/Article/details/gt2wujketxo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2goohkfqa.html


<!-- 参考信息 -->