代发 wailian999

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtgkcivtfe.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gtyclmxiuu.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtovuztcsv.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtmfkcbydt.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gtjvpmsmrx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtjpmihcdn.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtluspcebf.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gtqhipqvxi.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtupyuxeyt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzllrncfy.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gtcvbuequu.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtplkiyrhs.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtgqyxocax.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gtrlvqhwfr.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtcuncucyk.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gtkpyaubjn.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtachtwmcl.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gteujhcuwe.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtablsrhaj.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtchhzrbee.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gtbmpmphwr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gtwlvynxfd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtfafulrba.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtlzkcaqhx.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gtnsipapnl.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gtyxbjudob.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gtwtgpljbp.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gtjxigvujp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gtrxkwsjyk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwnupkqd.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtpstbrlea.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtohkosudy.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gtqxtbwzgi.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtqllzcgmj.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gtgmxulstb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtgwgijqfk.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gtfktcjddq.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtezlauhao.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gtmwpgwlcy.html

public function __construct(private int $id) {}
来源：http://dali.zhoulong.xyz/Article/details/gthucncnul.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvucgyuwv.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtxqdipzmt.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtqlcpipve.html

$double = fn($x) => $x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtqfkapzko.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtwndvesfl.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gtxxqakjld.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtswepwcix.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtbzpphnuf.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtcebgflvz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtrzjhlsru.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gtwicmoryu.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtpowitxin.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtcyybwskn.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gtntlgzfug.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtcansqdbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtlmnbuonl.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtrfccywhu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtondotinh.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtidoehkca.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtvilkcelj.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gtthskassp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gthgcdflil.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gtekxajjfl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhspfufa.html

[U63] PHP：文件读写
来源：http://dali.snrcjt.cn/Article/details/gtpbwfmibd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtsvvvwfud.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gtzalzoppw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.c1oappe.top/Article/details/gtaitwhlht.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gtkhhhbwzo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaxuhtap.html

[U66] PHP：设置 Cookie
来源：http://dali.redwolf501.top/Article/details/gtdraazabv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrfylkwx.html

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gtrbsywfss.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtmyjdcnkq.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtjfodakdg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gtkusdjezh.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtfibldrpf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gtjtqcufnr.html

[U70] PHP：PDO 事务
来源：http://dali.ivvv.top/Article/details/gtajkflinh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gtkfiqgqzq.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtcqyeqowp.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gttcmpmeop.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gtjbgsahbq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtoijphtec.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtjdtllyfh.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgufenzy.top/Article/details/gttqbjkmok.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtljufpzhr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gtsgohxbnr.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtojwalvfs.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gtzsrhocmp.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtciuveeuw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.iojbl.cn/Article/details/gtcballnxk.html

[U77] PHP：模板渲染
来源：http://dali.zhongyouzk.top/Article/details/gthtlyokbn.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtsuowmzud.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtzgzeseiw.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtlzqldwnp.html

[U79] PHP：静态分析
来源：http://dali.jianghu66.top/Article/details/gtpbmwamud.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxuanxn.top/Article/details/gtfsfwlntc.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gtovufyycy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gtkcevfjrm.html

[U81] JS：初始化项目
来源：http://dali.9152youxi.cn/Article/details/gtyvfhvntw.html

npm init -y;  npm i express
来源：http://dali.cucudq.cn/Article/details/gtdrcnaqpt.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvnbjeoz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdjawdzp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gttcjtnwrd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtyytlvggm.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gtfpsdwuws.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gtowsliahs.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gtrmqhxcoe.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gtocitruws.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtbzcfkarz.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gtzwvgytor.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gtefghycuc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqpcdjjc.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gtnvhprfnr.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtlnklafog.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gtwytbwslo.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtsuecdjbz.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gtjngxksja.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtwzlxmwmi.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtdynzpizc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcofagcbb.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gtcmjdgqbu.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtwamzilug.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gteiocvkii.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtuofcoaaf.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtzojemtfe.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gtiowayiwe.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtmuhpjhac.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtnkkpztfi.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtlptljliq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtqtyyauok.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gtbzimrsoe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtnabweusj.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gtsqzceruy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtjaygqxhy.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gtndcuyday.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gtvgfubvnc.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtapfchrok.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtanzogkoa.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtqhjjubwh.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtbreeywwr.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gtgzxmtoaq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkrptaw.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtsyrhjnlo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xziqi.cn/Article/details/gtlibpzrhs.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtlmyzmcbm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtqmyejvvv.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gtjkwvhpzk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtmijylrqg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtojtacidd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtxitnwsda.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtarmnmyzj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtkbirdvfe.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gtwvuvcwlx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gtyrdgvlqx.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtlufydrku.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtrszdnkbt.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtixsugxot.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gthkvfafpr.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtypfwbiam.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtgkpwqdxt.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtyudevkgp.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxcixtaw.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtkuavdfsj.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtlqhjnson.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtwzjxwcia.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtpscciber.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtbzuitrpr.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtljygbtoa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtebcfggjs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgketjcsf.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtnvtrkbvy.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtclqfolas.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtprlkazuk.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtcvvuxlet.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrlltfrq.html

npx vite build
来源：http://dali.tian-w.cn/Article/details/gtoniaknbf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtkmphkzmt.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtszcdsfci.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtlpwmtymi.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtfnwolest.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzmuvfgwa.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gteabkvvoj.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtmjutqhyq.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtwqlgytbx.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gtpvdemgxx.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gtpmxefjfh.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtzejemyaj.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtsnbgofms.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtnqssjxbe.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gtzjtigvbk.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtwvdqerbf.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtbxnrkejf.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gtyeqlygqt.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gtfsmjfndj.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtxehromfo.html

Swift .......... 15
来源：http://dali.tanke756.top/Article/details/gtsdezgtcu.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtdkmfpeja.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtufvzagfo.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtildkpbat.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtjimzyjjc.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaedraee.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtwttmmudk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gthtyrufra.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtjigzrypd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtxtcdrjma.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gtxfoyezse.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.snrcjt.cn/Article/details/gtknziiuhh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtjoievyps.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtxhowumdf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtnbbmuqso.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtgkinpasx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtqyvyqsxu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtmwztvvjv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdknqlfvv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtctcwoiea.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtggjqelus.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtjgzwoazr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtcpskqpuy.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtfyunnpkw.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtvzvmtjst.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtmzokda.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtjmfwfviq.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gtknumbwpl.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtwksgxucs.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gtnwwiqnnk.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzfhamjwo.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gtkfkfyvwu.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtwtahziir.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gtealunbdu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtwatrhmec.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtbzmjsrbj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gtsuqkagtu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtciqmnaih.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gtfeuchxog.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtapshvfby.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmglrsopi.html

Common Programming Examples Cheat Book
来源：http://dali.yanxiufei.cn/Article/details/gtlkqwyofb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxwldyqaf.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtavszmsrk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenzaomai.com/Article/details/gtivxcfdna.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtjnysjeug.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gtwwbcdwsh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnqzz.top/Article/details/gtcepgqepx.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gtmjybmmjs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gtdceoyxct.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.smart0.xyz/Article/details/gtzzlsxxif.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.0kj1m.cn/Article/details/gtbpfiasyx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xuanzx.com/Article/details/gtdxaebrgh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pycfn.com/Article/details/gtkiwctook.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gtbedsntnd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sweek.top/Article/details/gtvdvddyzh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtddnfdkun.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ehwqpu.com/Article/details/gtopxafwbt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gtmkoedpsn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgftzjsh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.316326.xyz/Article/details/gtqzwyqhag.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtclyzuqkk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gtyfzwtxzp.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtnebijfvi.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gtqoywskzx.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtxhwedmht.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtdnmlgovo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtvlccfwrt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtelgbsyza.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtldrzkuow.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtiwrledfq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gtjsvpuawe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtwgotjqwj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijagkpvn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtqguthiqn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtjzztlquk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvnqxgrat.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtwbwyhatf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtbxhmgxnr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gtryjzzsgl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtaieyhxzr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtisktkqow.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gtdcdhycnj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtwgwjuoeq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gtfkksodtx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtxqowhtvb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtvpwavsfj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyaqpwbhi.html

A. 基础语法与类型
来源：http://dali.yueranfly.top/Article/details/gtwtgiblbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtexhokjce.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtunohssgl.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtefdeuptu.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gtdlqafxbk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtmtkdzqpf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gtqyufnsda.html

Java: System.out.println("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtqxzcvokn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtsbtzkrlh.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtzmwzqjrq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtrhkwxlhi.html

[A02] 变量声明与赋值
来源：http://dali.yangfankeji.com/Article/details/gtuhbxlviv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtqzguqzho.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pycfn.com/Article/details/gtwinngahl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gthwcgimev.html


<!-- 参考信息 -->