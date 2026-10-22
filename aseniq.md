代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gtnudbpinh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtrrxjsvjy.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtapovumnz.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvbjvmwm.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gtgqoijakf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtmntmxbdd.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtjusbqeri.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtwkyojfdp.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtymwyezjh.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtuqmxugpn.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gtjvnjcpea.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtplehsqur.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gtwtdadcmp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gtwcypcwnj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtxnctdqqd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gtzmcswcfu.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gthlejzioi.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtdkhqwsnj.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtqwfyppfs.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtnjaxscgz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gttekqklzd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtgcmfeffo.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtsoyvwark.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtyxdalkxs.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtzwsfzksa.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtpqimyywj.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtwsvljyxs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gtlrilpork.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gtctohptpc.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gtdnezjinn.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gtrpeyomba.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtiiyxujvg.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gtpdhrboek.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gtzoybeadg.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtgmjpsrsb.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtxljrollj.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gtfzayodqy.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgfzy.top/Article/details/gtxupmpark.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgodxohi.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gtbyhlxiod.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdybugtek.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gteztphsli.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtnknvubre.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjswcmmpz.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gteindtopy.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtodpaezmr.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gthsqdouga.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gtomweqcqf.html

[U59] PHP：自定义排序
来源：http://dali.hysaishi.cn/Article/details/gtdudvoxut.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtqrgttglq.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gtopbpfzwb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sufxvd.cn/Article/details/gtavtqocmd.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gtoeavxlao.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtwzlxchro.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gtwhbhzurh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gttzexzcrh.html

[U63] PHP：文件读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxuyeevh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtehadpkca.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtchmhrbhb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gtnqgibvvj.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtqpckadnv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtnbquaqwx.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gthcbipdyx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfurqywg.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gtnovtzzeg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gtouojxbig.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gtktdopyri.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gtmenjyfyg.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gthzdylerm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gttmigyesx.html

[U70] PHP：PDO 事务
来源：http://dali.jlsjyb.cn/Article/details/gtjskjnwfx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gtqtofbvkx.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtxapscyjm.html

throw new RuntimeException("失败", 500);
来源：http://dali.sysykeji.top/Article/details/gtutvrrmxo.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gttxrlnern.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jianghu66.top/Article/details/gtydyvtjnq.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtpiiysaxq.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtkullcitt.html

[U74] PHP：读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtbrfkhrqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tian-w.cn/Article/details/gtpiparpcr.html

[U75] PHP：依赖注入
来源：http://dali.fengsongda.top/Article/details/gttawzejqt.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtjnvmgycg.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gtaepgkjdj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtztvxclrp.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gtqbizrxgs.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtrdckjjav.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtooimcrxx.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtmhwvwwyq.html

[U79] PHP：静态分析
来源：http://dali.shzxlz.cn/Article/details/gtvroznvlr.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gtwqoeognp.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gtsospprcl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gtfyvlzvqh.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtrtxjjocv.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtfmbqqxov.html

[U82] JS：package.json 脚本
来源：http://dali.cucudq.cn/Article/details/gtmqnxobdz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.haohaochexian.top/Article/details/gtucplvier.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gtrpwvefiz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtifhaxzqh.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gtsdunscrw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtrwsghpjh.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gthrmifnlj.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gtmoedmcjo.html

[U86] JS：空值合并
来源：http://dali.yueranfly.top/Article/details/gtwapfcems.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gthzkqbjyv.html

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gteiwycpsq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtndirfsvd.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gtftnjucuo.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtaviuobpk.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtyphvhcov.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtxymgegzv.html

[U90] JS：数字数组排序
来源：http://dali.mhx1999.top/Article/details/gtofpapqfm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gthubkcslc.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtbndlqzqc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gteyzsimrs.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gttgqqboqe.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtdrbodsnr.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gtsyrlrfqk.html

`共 ${n} 条`
来源：http://dali.sysykeji.top/Article/details/gthciybios.html

[U94] JS：箭头函数
来源：http://dali.tanke756.top/Article/details/gtsosipcyj.html

const double = x => x * 2;
来源：http://dali.daria6918.cn/Article/details/gtxzuidsmc.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtwtqeptng.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtpmeumnjk.html

[U96] JS：async/await 与异常
来源：http://dali.jlsjyb.cn/Article/details/gtwrqbbwft.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtrpdxgrtu.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gtkhuenfft.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtcbhfsuvk.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtlnunmbgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtpmytvucg.html

[U99] JS：事件监听
来源：http://dali.ydzc1.top/Article/details/gtmtadrlsy.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gttdoemhmh.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gtzpyskpbc.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gtzbncbxrt.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gttdgnrnzp.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gtrxtnfkua.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtfrvegzlv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gtekygevjb.html

[U103] JS：定时器
来源：http://dali.yuxming.cn/Article/details/gtxvgfosmp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gtnjcpqksj.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtttsdggak.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtuwqiigsm.html

[U105] JS：节流
来源：http://dali.shuidangran.top/Article/details/gtricyxjwy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtucgauzay.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtqazgublb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtfyrjkhrx.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtqwlthbed.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtuocrknqn.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtpliecyda.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtfsvzyxzw.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtrpbjuzkm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtnmpqltfx.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcjttemo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtvzqpjdro.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtmilhgxjc.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtfsnkcoiv.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtocaiqute.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtrkvjkykg.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtdmyjqllz.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtctphnaiq.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtlllyaelb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtqzsorzhq.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtbbgrpuwj.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtioyacbrd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gtqnygghom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gttxvedgzl.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gtpzcsxuee.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtkrvvovyp.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtjmjwyfhj.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtetwiatyx.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtcqszxtnu.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gtxmewgoxw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gtnblqekju.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gthhzxrpeg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqzcmixmx.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtvqwzpiku.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gterkzhsik.html

按语言统计（条）：
来源：http://dali.guannengcc.top/Article/details/gtgtrlagkq.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtztzmncfo.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gtsaftxicl.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtpupqumrl.html

TypeScript ..... 212
来源：http://dali.kuanghao11.cn/Article/details/gtyabtbfnc.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtxptmdhcq.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gttftdzsbx.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gteqaljtsu.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtobtoijay.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gtezfhmdmy.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gteafznfwu.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gtzhmacgwg.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gtxaoqabga.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtziohqrom.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtpmtgwjpe.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gtjlknxvnq.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gtzrkjavxf.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gtyrjyxfvm.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtzndlbzaw.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtdzopxqod.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtkhiykdfd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtelrwhevz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtzzfiflbf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtpnjmxzgr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtuqriocae.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtkxqolbpt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtcecdxcgw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtmbdreddk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtmtksbcxd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtwqzkzjpi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtrdgzwubb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtwgkzuwfg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtnbtrltfc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtotmspook.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gttvohsien.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daria6918.cn/Article/details/gtnxcnhffl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtavvjflhp.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gtfpzxzblj.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtfeixxebn.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gtnrvcxpxi.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gtnymzoxhz.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxuxkqqd.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtzgpufuyk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtkopeolhw.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtxmxqbags.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhiohhgu.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtumnlguhb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gtlfaodlti.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgufenzy.top/Article/details/gtrdmotkqy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtuusqnskj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtjkbsfjoa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtfvbgweut.html

—— 文件结束 ——
来源：http://dali.fzhhl.top/Article/details/gtjnrnqxdk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkiizhna.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gtuefvuoeu.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gtlvftyisp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpmmdgzng.html

【收录内容】
来源：http://dali.jlsjyb.cn/Article/details/gtuecftotv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gtfyvpydoa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtahweaaey.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gtswzvrptx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gtucnnwfta.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gtrucyptoj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtvxayewsz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gthylvggtr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gtbxrfscgp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gtrfbhxack.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gttmqyxmtg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gthefikgyt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtuxbrumgs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gtvwcibict.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjqexvth.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtngryrusn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yonumen.top/Article/details/gtfsyeymoj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenjidiqi.icu/Article/details/gtlgmqlteh.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gtvozpoltv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gthbdrneid.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatowhbjf.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtxcdruklk.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtzlnzepnc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gttjovrqwb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtkdqithmq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtsodvtpai.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtphrqupsm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.svipenyu.cn/Article/details/gtthhftofj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtslsymcog.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtuwznyjuk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtekgxwxfr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjjbwkuva.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtbxwlkqjc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtvrdmxrgd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtflzauwog.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtjjajbatn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtzetpurpe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gtuyhlebpz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gttumsipnt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtmzjcmlgi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtanhaomus.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gtfsiyvpey.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtgyyugioe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtufkbhvak.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtegtiaqur.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gttndiebev.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqitjqjur.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtusuabdkp.html

Py:   print("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gthmuttxef.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gtewwnmvwm.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gthmmksdmk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfckusako.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtzfvsxnih.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtstuwnacu.html

Ruby: puts "Hello, World!"
来源：http://dali.jianghu66.top/Article/details/gtqsbrphpr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtpyponakh.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gttbmsgsxy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhengqikj.top/Article/details/gttlpgcgml.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gttwqcwbfn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gtbeuodwbz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gtajynexqr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gttocqheyc.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gtjcrqeldm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gtikgmpnwj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtoupicbym.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtbqjtyvmp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cheryme.top/Article/details/gtgpfgovyp.html

PHP:  const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtjpoksdwb.html


<!-- 参考信息 -->