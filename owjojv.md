代发 wailian999

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gthldoskda.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtdgzxskxh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtcaddopgy.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtxxxdiqcr.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtehnyibmf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfdvqlak.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtqrytzdtd.html

chardet.detect(raw)
来源：http://dali.jqgfzy.top/Article/details/gtgolecsma.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gtwpvrmtbo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtghnmblkl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gteatioprq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtyjuvadar.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gtdmolczof.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gtkgpgpsnt.html

[U38] Py：获取脚本所在目录
来源：http://dali.daria6918.cn/Article/details/gtxgtncnen.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtqjzjwifu.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gttdmkglwn.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gttysiikjj.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtasvvtchc.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtuiynysli.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gttspkixij.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gtgnnzsxzb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcamywrxd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.feifeiyinyue.top/Article/details/gttvozjudx.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtlusccizy.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtzzyxbumc.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gthopumxfp.html

declare(strict_types=1);
来源：http://dali.9152youxi.cn/Article/details/gthqgylppo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gtixtzmyhz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gthunyzzmx.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtzcelcvjf.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtctvtdpiy.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gtvlxvysac.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtqbigisll.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopktojeq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtcsecoepc.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtepcwxuwg.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtzdpskilu.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigufen.top/Article/details/gtgtzhtpsi.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfatmiav.html

[U51] PHP：数组解构
来源：http://dali.cheryme.top/Article/details/gtdgawcgbf.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gtkdwqonul.html

[U52] PHP：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbsxtuzs.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtxgwyjsrs.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtfmpahhdf.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtqwjmufaq.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtseuoemoh.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtzaqlocnp.html

[U55] PHP：match 表达式
来源：http://dali.chenzaomai.com/Article/details/gtcidhoohw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtrcczikzk.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtjtyhpybk.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtmvinyqww.html

[U57] PHP：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtsrtdsbvv.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gtoeqmugmb.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gtqqoatoup.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gtqclgxeez.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtcenvmmot.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtsympatpc.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtqqdsntyb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gtecwaojdo.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtsdbjdhox.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtqovoulwg.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gteyqpabdb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gtenydardw.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtveolovkx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gtrmdfmcpr.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gtgtgypyzc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gtywtktrnl.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmhzdjbp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtkxqvrtse.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtijkgedmr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtmtvacqmq.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gtsifhbuvx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gthuuwsslz.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gtcgrsfgzv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtxluxxrcg.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtydryrlgj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtbgnweeje.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyjhqwrl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gthcsdvewa.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtmyhatysj.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gtojdijkts.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gtsgvxekzf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sufxvd.cn/Article/details/gttmiuomru.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtfdmcpugh.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gtmkzughgt.html

[U74] PHP：读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtctbkzgmr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtrvrxaazc.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gtfdmxhcig.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gtbupooqpg.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiedrppoy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gtuebigffr.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtibwkypkk.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gtlyjoxvuj.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gtuqujblim.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtrixhllex.html

[U79] PHP：静态分析
来源：http://dali.c1oappe.top/Article/details/gtjtkfsbkn.html

composer require --dev phpstan/phpstan
来源：http://dali.yangfankeji.com/Article/details/gtpbmabwbc.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gthslsxdox.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gtdmebznoa.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gtvzhocspb.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gtyxoikysi.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gtgbzrcxxs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hammf.cn/Article/details/gtqdtoikdm.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtphainfhe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtfaqgutyu.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtpgzovyxg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtrfynvmlc.html

[U85] JS：可选链
来源：http://dali.andypj.xyz/Article/details/gttzptvwch.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gtwkrvdlez.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtmnvuahsk.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gtsvdqkwkj.html

[U87] JS：解构默认值
来源：http://dali.iojbl.cn/Article/details/gtmqvtxxox.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gttybuenub.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gtcjmzxaxf.html

{ ...a, ...b }
来源：http://dali.zhiwuduotai.top/Article/details/gtkruaoniq.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gtcdbjazrl.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtklpuvrfw.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gtjonlpfcz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtcutiylru.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehyyyvky.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtmeepsswv.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gtckvqczan.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqilujbt.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyaadxak.html

`共 ${n} 条`
来源：http://dali.jinqigfzy.top/Article/details/gtrsykpdkr.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtsauvaqzy.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gtdjwpuptw.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtwnqgfphj.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtsxyrndxr.html

[U96] JS：async/await 与异常
来源：http://dali.jqgufenzy.top/Article/details/gtrahqlckg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtkoaqwkyg.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtujfoqivg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtynixkpkb.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gtsltpqgkc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtdavelaop.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtyslurroq.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gtmnbjoivw.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gtyvjbjmhe.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gttqvzqppw.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gtosrxqsmn.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gticbcffum.html

[U102] JS：本地存储
来源：http://dali.mhx1999.top/Article/details/gtplmlhxyl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtapzzpteo.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtilmkvzii.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtqicgfwkc.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtwfrtpefx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtrnktmdyf.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtnlpzbmya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkvigrm.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gticbjtbys.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gzhubu.top/Article/details/gtnvmyivyh.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gtzgdrteyt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtjreaalbf.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggewicro.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gtglehdszd.html

[U109] JS：数组分组
来源：http://dali.pengpengdd.cyou/Article/details/gtawkodkfp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtspvclavn.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpsmtjdh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtvqloiwqf.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkvagyya.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtbcqygyog.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtwdjcqrrl.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtatinkgxd.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gtnwjydfct.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtkbpqdmpv.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtajzatgxg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtvopsgbkl.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtuwcabtzd.html

crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtnpyvhmbl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtxzbwuwrr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzovujjyh.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtjmrsozed.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gteprrtfpm.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtamzjcuvu.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtyubqngzf.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtcbrbyhzo.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtppabdrbe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gthybaluyd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gtkxwfpwrj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtplhyygid.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gteqvhxrfj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfnuhlmzh.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtosaxbgzh.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtziqkxrjq.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gtsrgybzul.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtckxhegxh.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtpmlakdgc.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gtjuprhroj.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtzxqrfeie.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtvfdpxisv.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtrgejreap.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gtjpouzfdi.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gtzbkqlcdt.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gtemaebhbm.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gthydcqivb.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gtfabydphq.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtktcxamju.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gtokrdnfjc.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtqlcoywtl.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gtuskxligz.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtxeenqznv.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gtpprzkahe.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gtyqpzmzlk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjkbqypr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyocrdggu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtjplzecet.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtefvfjkkt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gtxizylqay.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtrdhcfluo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtjrzzmtfr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtqkvovkqo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtsknwhjrt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtxpomfaac.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtczxxfzgv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtdsnuhhbb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgbpexkxm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtzfdeulfj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtrfghgiag.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkujsumw.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtuuhxycal.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gteyfivqcr.html

S C / C++ 专题                          60
来源：http://dali.jqgufenzy.top/Article/details/gtrnefvfdz.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gtrbnkhdfu.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtywvnoqvr.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gttkepgrni.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtrujxyfzu.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtbbdpgklp.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gtbhdbbtep.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunduzuxg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtwafkfswb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzjucuvz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gtxaphunbv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtebuvrriv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtdvqwwnli.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gticdvsdua.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtneedfyci.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gtxpslfvlb.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtxikycgon.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtveadisay.html

【收录内容】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvxcbmgq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gtjqwcsncz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gtgpiyauws.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gtqxwvlgix.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gteufxqjym.html

【使用说明】
来源：http://dali.andypj.xyz/Article/details/gtnwyudiqg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlceckmge.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gtebswhgrf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gtdmsrbkjw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tianlin.xyz/Article/details/gttuibsryx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tianlin.xyz/Article/details/gtyiprdbrq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxokctnbd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gtynkouaxs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dianchejie.cn/Article/details/gtlvhwtpzo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gthvtenaos.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtxjocbvcz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xinyue.icu/Article/details/gtujgzppip.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gtwdtaizez.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gtnaqeodeo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gtarmqdigw.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtfduktvqv.html

目  录
来源：http://dali.pycfn.com/Article/details/gttwpmoqbp.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtckzxzjho.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtnmlboxqp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtgeautadx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtmyrvazlr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtyzkjfvom.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegsyjyce.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gthaamcgzf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtvctovqab.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtmwnfupdx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtelohpolq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtlfvmenul.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gthbughhnn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtyyywgwbv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtyjxcpsfr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtyeiaqflb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.0kj1m.cn/Article/details/gticdphryb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtqtyiqupb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gtdxpxahjg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sysykeji.top/Article/details/gttobzpzwq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnqwzpxjc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtoenobnoy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtwrwqmpvb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlahpypvd.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gtgezzikvv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtguvkmhap.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtbcykomfn.html

Py:   print("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtkyzwasze.html

PHP:  echo "Hello, World!";
来源：http://dali.shangyingyoupin.top/Article/details/gtumhbvidd.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtuwbizzfk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hfpthk.cn/Article/details/gtyifpogfv.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtwtbkvwfb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtzyapgxse.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gtfzchvoyu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gtfpbxiicr.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gtyadvbbbt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tianlin.xyz/Article/details/gtcjlxzrey.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtqjayygbn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtjqnhphqh.html


<!-- 参考信息 -->