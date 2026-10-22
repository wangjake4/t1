代发 wailian999

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtgqnhdbns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.vqdsnc.cn/Article/details/gtcbjfyakg.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtbhglvdjq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtfnklrwkb.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtortdwswf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gteegvfnwd.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvbinfqj.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtufflmgcj.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gtdcoqlpus.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtwtmzombm.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gtcppwaqsy.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtyeltvhta.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtevgfhhvi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtcsnraumy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtjgcirgkz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttvukhige.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gthwtgyxln.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtmndmjtfh.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtjazslpzx.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gtihasprfj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gtqlvkievw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrbvmclw.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtjuoifqpr.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyqktlzf.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gtnkznvmjz.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gtljwmyedu.html

[U48] PHP：纯枚举
来源：http://dali.hnxiangtu.top/Article/details/gtuwkdiekg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtokyhdbcg.html

[U49] PHP：只读属性
来源：http://dali.fzhhl.top/Article/details/gtnsndqzko.html

public readonly string $name
来源：http://dali.dianchejie.cn/Article/details/gtzekcoeju.html

[U50] PHP：构造器属性提升
来源：http://dali.fengsongda.top/Article/details/gtugkoqdxs.html

public function __construct(private int $id) {}
来源：http://dali.smart0.xyz/Article/details/gtdvkqofyc.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtknceuzvt.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtoeindnuj.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtwssuxkpd.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtljktktzd.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gtedxkjtci.html

$v = $a ?? $b ?? "default";
来源：http://dali.c1oappe.top/Article/details/gtysehhrps.html

[U54] PHP：空安全调用
来源：http://dali.0kj1m.cn/Article/details/gtqnlwwqbe.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtumgpmhvl.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gtdhazwtqm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtvednpgai.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gtubekqwmh.html

f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtrucfbngh.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtgpwyotog.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gthtmecset.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtoazudzre.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtmjhbutzt.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtqevdvybg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpxhwlhok.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtfngjwuvq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtjbpuuadl.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtysvhtbtc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gttmebhzoy.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtqyniwgrt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xinyue.icu/Article/details/gtjxfenrti.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtxikdgoyq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtmgbnxacf.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtfkxoodbv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gttzyyuiti.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gtfnfndigd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtvilmznvm.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gtupoqqqri.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gtjhknkkwu.html

[U67] PHP：处理文件上传
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonhfdlvx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gttxtejdog.html

[U68] PHP：PDO 连接
来源：http://dali.sweek.top/Article/details/gtinznwjqv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gtejayphox.html

[U69] PHP：PDO 预处理
来源：http://dali.shuidangran.top/Article/details/gtbryupyyn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdaeytnn.html

[U70] PHP：PDO 事务
来源：http://dali.ehwqpu.com/Article/details/gtdjpjzbig.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtnoagctwb.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtrwqytwjy.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangdashe.top/Article/details/gtavbdfskn.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtwzehvgzx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsczaobd.html

[U73] PHP：读取 ini 配置
来源：http://dali.gotoacloud.top/Article/details/gtaiqcdvlx.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gtjbsfbxou.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtxlregocu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtivewvuwa.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjgoexnb.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gtaljiqiyo.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtzpabihtd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aizwys.cn/Article/details/gtecxyjuaf.html

[U77] PHP：模板渲染
来源：http://dali.316326.xyz/Article/details/gtajzauikn.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gtjxzlftlo.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gtkgkghbqu.html

composer require --dev phpunit/phpunit
来源：http://dali.sufxvd.cn/Article/details/gtgjdcknkl.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gttqjajkwb.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gteucvwsxp.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gtvnyqoejc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtfrvdniws.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtbmsobtcu.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtjncddnyg.html

[U82] JS：package.json 脚本
来源：http://dali.shzxlz.cn/Article/details/gtetujfbgf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtxehqtter.html

[U83] JS：ES Module 导入导出
来源：http://dali.yvedp.cn/Article/details/gtdqmmrwlp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtsldgxfch.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gtsmjhxuqd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gtyilabmio.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtgnxyaqle.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtiedwlvqr.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gtbovluool.html

a ?? b
来源：http://dali.zycfv.cn/Article/details/gtpeglyrts.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtmwwqemkl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtmgddrwwl.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtxognvxcr.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtagudfiyi.html

[U89] JS：数组去重
来源：http://dali.gogol.net.cn/Article/details/gtmctpwqjj.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtdcrzpbcu.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtnnahrzbm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gteuymszrr.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gthgrxxijg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtpwcvhzyb.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gtbknjfxjb.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtqxuqqoby.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtrrxhzruw.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gtlgztkcsf.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtisqyjawe.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gteamwamsc.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gtljgmunob.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gtkahbvnus.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gtpuyfocgs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtozlsimhy.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtyhhxynfa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtmwooybjt.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtfwoeudtx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtcpxmnedq.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gttqhxbbtw.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gteekgzzqy.html

[U100] JS：DOM 查询
来源：http://dali.vqdsnc.cn/Article/details/gtasgqiuxt.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtgujgbxpm.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtarqfajup.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtvwcmrgyf.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gtyiltwcfj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtfcxlwpws.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gtibstwkwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gtwtnyjlxb.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gttihuwpyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtkxtaatlb.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gthvrvxahw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gtyjduimjw.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gthjdlftmy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gtmmiwqkuw.html

[U107] JS：数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtxuyiphmw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtesofiudg.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gtxbkctjyp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcpneckc.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtuedkpqwi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtmakkewbr.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtfsldbkmz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtgpkramdf.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtswoogfvh.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtsucgtxyo.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbwwagms.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtiyfdbnyb.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gtmhznnood.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkolydfg.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gttiqefwla.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfnxiusp.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gttuilrcpr.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtlptnqzov.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllpymccp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtfsqwqxla.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtgfupxroo.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gtjjfobmil.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtdbeviucp.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gtlpxmvlqz.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtkovkxevd.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtvmdjzppc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gtpajxqafc.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjhrprbk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gteflfrolk.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtezczzubt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsbpzkwsa.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gtmcupffmo.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtqkmmxfhq.html

PHP ............ 252
来源：http://dali.zhengqikj.top/Article/details/gtmgbqpqvn.html

JavaScript ..... 252
来源：http://dali.pycfn.com/Article/details/gtekgudtwl.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gttywncvmf.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtvqtlkcwy.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtzigredne.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtsstxxvcx.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtzahymuhl.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtezycplvr.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtfhywewlq.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtpfwcbpts.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtyfsmzouu.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtqjugwqmd.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtmphleuax.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtyfnogumm.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gtiaunjtlz.html

Scala .......... 10
来源：http://dali.shuidangran.top/Article/details/gturzbxjsd.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gthntpjwtr.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtacvglvbe.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtsagxumcs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gttkyeiwfu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtnljmhxcn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtxiwxwywz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtsfrsevfc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gtlfqcnexh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtufgvnvxf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtmzwlssmv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtlukbtbdl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtikwlxvym.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtujtdufxa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtioljvlhm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtivtycphd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtbqrejbql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtdrzatxsi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gttgqiszkm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtecjpgcfq.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gtnesykoab.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gtiqakirlh.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gtkmfvwamr.html

T 其他语言补充                          60
来源：http://dali.haohaochexian.top/Article/details/gtabzpypkz.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtsxfemzfd.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtpyaoexir.html

合计                                  2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtwjfyxutl.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtdobokggb.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtdlvrumfr.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtzaqlwdvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.haohaochexian.top/Article/details/gtbjehzqwv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtkuhaygyb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gtxwjksnrx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sufxvd.cn/Article/details/gtnqqebqdn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtjhugrqax.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gtaiolwugn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiqausugy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtvmfaizas.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gthzwvygwa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesclrymy.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtumjewfly.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtlktdxsyo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gtxfdjxeec.html

SQL · Bash · C · C++
来源：http://dali.tian-w.cn/Article/details/gtvuejwnxb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtwicrryff.html

【使用说明】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynnmgryv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gtbseoxcrl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gtzfeivbcj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.c1oappe.top/Article/details/gtnhibyjqi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.redwolf501.top/Article/details/gtrewjvxii.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtjhgnrkux.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.smart0.xyz/Article/details/gtlawcjbby.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gtegofmner.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmalooye.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gthpkbtrps.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.0kj1m.cn/Article/details/gtvqccmzxz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gtpjdznlwq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtszalmwdo.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtxbfggyrm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.9152youxi.cn/Article/details/gtulqfqnzc.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtfdtbxchh.html

目  录
来源：http://dali.cashguo.top/Article/details/gtlopkrvdx.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtbxttiyar.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtwmomuqyu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsletsty.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtgfidddpz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtexcqvyse.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtjqgjpbbg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtivqxzrde.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtopyuwkuu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtlgnftsyx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtviibhaiz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtfisxauub.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtgiruglxp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtiabafdra.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gthpzglavg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gtfwlcdczh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtnxxnbprs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtgvwpbeze.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gtrzulsimc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gtxbxnmdgw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtljkktuii.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtvknthhkg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtxyeikbbb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtawfbxxde.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtftmjoysi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkllbbrxz.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gtmugcshow.html

Py:   print("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gtqnszsgmt.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gtivdewmkm.html

JS:   console.log("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtqvfkoeys.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gtuyshscqe.html

Java: System.out.println("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtlupqxgns.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtbdzmnoar.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzemdfmom.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtmcclutlu.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gtcjdopiwf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtprwbwfqo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtcmdrblpp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtqalybbou.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gttgexhwuu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtxuvclobw.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenzaomai.com/Article/details/gtqveupxtw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gtodwdoxfe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtujikideh.html

[A03] 常量定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiunxpcrx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gtlanngadx.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gthxmworcx.html


<!-- 参考信息 -->