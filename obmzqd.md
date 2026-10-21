代发 wailian999

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gtkfaafsfm.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtykvmpjot.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gtarnpckqi.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtjjlheobn.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtwgcpviwh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtdhynhhol.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtgmupcryu.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gtbfeyxtps.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtaqikufou.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtysnryauc.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjwkkntq.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtxwswfugl.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtprtegyds.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtcrclyjkl.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gtskccbijg.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtvilymiya.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gtnzhfrycd.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtpsbwuqys.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtkicemkni.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtcxqrtcmj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gtvxphvjbh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtkhejzxos.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gtabuhbbzo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtzdhqlgdt.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtcsmsbrpw.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtwszehrcm.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gteamerulz.html

declare(strict_types=1);
来源：http://dali.haohaochexian.top/Article/details/gtzhcnaqdy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gthlvqddqz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtqjtqyxgi.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtvtltcpzl.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gtnheuedly.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtlryuwcju.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtpldecyqo.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gtxplwuutd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gtbjtaxpbm.html

[U49] PHP：只读属性
来源：http://dali.zhixingplan.top/Article/details/gtqkrbrdaa.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gtzcmxhadm.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtfglnlfod.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxgkhxxmx.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gtyybmnjqq.html

[$a, $b] = $arr;
来源：http://dali.jyoumei.cn/Article/details/gtftxoizsp.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtupnzvfhp.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtgvomotrm.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtyvvbcefh.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkbqqnhi.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtkikycljz.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gtaszddene.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtjeacxbri.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtyrbbgyjz.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gtvvencogg.html

f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtwjuaulrw.html

[U57] PHP：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtnwohmfjv.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gtbwgqmvjm.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gthwaqnrpy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtprvwqygn.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gtuilztyfy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtycrdvcnu.html

[U60] PHP：JSON 编解码
来源：http://dali.hnxiangtu.top/Article/details/gtqlyyckeo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gtsupjdngf.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gtlncksher.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtjdegsbvy.html

[U62] PHP：日期对象
来源：http://dali.chenzaomai.com/Article/details/gtnqvtgkaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtibydvoye.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gtolktwefe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gtknjqcukk.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gtfxqkkqdq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsxdxfkm.html

[U65] PHP：会话
来源：http://dali.ehwqpu.com/Article/details/gtxsdsthkj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtomnjaiij.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gttgnfhdvu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gtikjbzpdy.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gtnjstaxqe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtvvtchcje.html

[U68] PHP：PDO 连接
来源：http://dali.ehwqpu.com/Article/details/gtxwuiirke.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gtmjvjxfsx.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gtwlcrixit.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gtdxtxauhs.html

[U70] PHP：PDO 事务
来源：http://dali.jyoumei.cn/Article/details/gtdixpqrik.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gtgvmoeqkh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtzzfzoryv.html

throw new RuntimeException("失败", 500);
来源：http://dali.c1oappe.top/Article/details/gthpbrdfmy.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtnllihhaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gttmrufajc.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgufenzy.top/Article/details/gtypiqlzsc.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtcqomghyh.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtpokcqlas.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeahvssf.html

[U75] PHP：依赖注入
来源：http://dali.fengsongda.top/Article/details/gtmrbsojes.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gtvzvaerwn.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtpgezloyp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtuzofysxp.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gtsydjmyvc.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gtkydxadrc.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtltzrkldu.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gtucpknplq.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gtjsbhvhwn.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgfzy.top/Article/details/gtdappjgad.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtradhuvjc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtdzcbvehi.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gthtzknoos.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtgtuxxwdy.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gthrhsrlag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gtseptyjxa.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gtapadblnx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtdjosyrts.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtsfbnofnp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gtzpvspygu.html

[U85] JS：可选链
来源：http://dali.ivvv.top/Article/details/gtwcpviddj.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gtbyivhvrf.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtqebhistm.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gtwnujtcua.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gtpvtnoupy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtssgaikst.html

[U88] JS：对象展开合并
来源：http://dali.cheryme.top/Article/details/gtwndsqgaw.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtytbigwrc.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gtshmjteso.html

[...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtlsuwhmke.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gtxefxakdo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtapepbeyk.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtsfhbmsyc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtthmmotxr.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtoyeboxqz.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gttenywgam.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gthczgszhl.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtwlngcvte.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtqopeqvis.html

const double = x => x * 2;
来源：http://dali.hammf.cn/Article/details/gtybzhydsu.html

[U95] JS：Promise 包装
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgjmkgdm.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gtptxqpthu.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gtyswyvwsg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtpuareyrf.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gtqfbonwmd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtzfvlobor.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gticsneylw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gtmhyivsiv.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gtsfibtnmx.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtbamnmnix.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gttqnnzgsa.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtyilefqia.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtpeakdbtv.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtpsqakjuo.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtappfdane.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gtrrqvnwlo.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtgvezxrwx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtgaokespn.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gtsovfqkpb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtlraevlzm.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gtkmoedcbc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gtruepbtqq.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtqmqsruwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtgwnbbczu.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gtorwftqfa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtpktygqyr.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gtjokabntv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtlqkmghge.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gthflvjmxa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtcvfcigjx.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gtmjuwmdjg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.vqdsnc.cn/Article/details/gtpfaavsxw.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtndccvpsr.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gteldxrkcq.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbuhyhzu.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhpnwbeo.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gtnarslfpj.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtdpkldprr.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gtdvblyomx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtlbedmvtb.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gteavrkzkq.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gteofltbng.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gttabihymi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtxzesgapy.html

[U117] JS：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtpjyopyvl.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gtkawikrmg.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gtalqqnjpr.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtmiwgchuo.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtryegptkd.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gtnssjzifo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtuemgihab.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtqezysvxk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfvwlpjis.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gteujnjviu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtupjhumxp.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gtnzczfuwb.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gtaixnwvye.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gtweyzdmnn.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gtjvbtpwli.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gtijsvnlcp.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtdhbumvhb.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtjncmpojz.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtxfqivdnq.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtmoeffltn.html

C .............. 30
来源：http://dali.jinghuilouyu.cn/Article/details/gtzujlvnuz.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtosekbrhg.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtirxsuumj.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtclnzcrmk.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtnwokhnnt.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtrwwetvcs.html

Lua ............ 10
来源：http://dali.zhoulong.xyz/Article/details/gtsyehtzwy.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtnlwxnohp.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gteuaspxfj.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtiiqhnmak.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gttelwejbb.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gtkiqgvlti.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtacdgocrd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtkgliupfv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtpjcmjjst.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkngbnaw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gtbduvbupe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gteyvyftbx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gthihvvkbq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtkgdysuth.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtathnancf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplqxxjac.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtddejgumn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gttnrgqzuz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtabapeefg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtthuoukoj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gtrzuucywl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtwepcgawe.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gtpybycrgq.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtbhgortxt.html

S C / C++ 专题                          60
来源：http://dali.iojbl.cn/Article/details/gtsjsdmmlq.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gtsmrudmgi.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gtxgtepune.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtlhyobvfv.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gthtcmfkcm.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtxtedxupv.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgjtsrcs.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtnslleepy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhongyouzk.top/Article/details/gtmkgzpusj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtgyhbzymn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.meibo888.top/Article/details/gtrkdtbvss.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqglzlqp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gtyfnhdoxa.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gtqwskgvcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzyjhwleo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtjibfemzh.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtxyhthamh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtidmugjie.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gtyczgbrwx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gtcvzkuuwx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtnbxwetrr.html

SQL · Bash · C · C++
来源：http://dali.hongshengwenyu.top/Article/details/gtetllvxeg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gtcwxaaodt.html

【使用说明】
来源：http://dali.guowangkeji.top/Article/details/gtweqhmttv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gtligoocsi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtmstaatcf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gtfwspbuqo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gtpyfojfcb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtchfwgwat.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gtpacauppk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuanzx.com/Article/details/gtmbafoxdp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gtjvxcavxo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gtesnrlsvz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gtvwfjgtvn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtohoelbnp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenjidiqi.icu/Article/details/gtqmrymuvv.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gtuatmlwzm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gthrfkgyla.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtjdpjiaaz.html

目  录
来源：http://dali.yonumen.top/Article/details/gtlxvrscgo.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtjycbrqxx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnixxjkrm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtkmireatb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtvnruteov.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gtspmyjfrt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gotoacloud.top/Article/details/gtoeerewkg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrxdcuoil.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gttooigvsv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtkrsyvwdq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtiehtpues.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtewzioenn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtwfeocykd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtwtokgqwg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtrnsdnvne.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtpjgconyd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gtifxxznlr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtucajkgig.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gtlyonnazm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtvnqakifw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjbdcbbq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtfmkeoskw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtoncnyfiy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgvgvwqrp.html

A. 基础语法与类型
来源：http://dali.ivvv.top/Article/details/gteejhlyxu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtikrnowlb.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtgkvzhlci.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtlfyrkqas.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gtnvhckejf.html

JS:   console.log("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gttvikkskp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtxboyubza.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtgrjnatgw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtjeyxfnke.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtwdcjuegu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtryblamin.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gtafwdvaot.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.andypj.xyz/Article/details/gtdgeiybkt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtmabrshee.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gtyfmwmwlo.html


<!-- 参考信息 -->