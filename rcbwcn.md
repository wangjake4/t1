代发 wailian999

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtnkzufnom.html

python -m pytest -q
来源：http://dali.sweek.top/Article/details/gtjmgdyfml.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtguzmvzyl.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gtfcijawiw.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtsqzlwslo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gtcwftcfuo.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtviedvdlx.html

chardet.detect(raw)
来源：http://dali.quarkkingdee.top/Article/details/gtsqqglgro.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gtbqhrtyqh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gtyapanfdy.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtqomzuqkl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gtryscbvyz.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtslgyudjy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtfrfaxemj.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gtwpxttsrc.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtqkcoafqy.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtybxmtigt.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gtzyrupnrm.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gtytcwmpib.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtnormbvlo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjhbohrs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gtexhyypbw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangdashe.top/Article/details/gtcrwpwboe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtwzimvuom.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtmqnuzbxd.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtvataibju.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjjakjzrj.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gttwfybiwf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtupcoubwi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtrdstnwcn.html

[U46] PHP：可空类型
来源：http://dali.hfpthk.cn/Article/details/gtepwhmzxe.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gttyqpxnid.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtgnrlmntq.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gtmidpykip.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gtyjtyyotw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gtwnshclaf.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtuiavqsvo.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gtmonkvuku.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gtavrslczr.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtlzxyogqk.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtpbfslsmx.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gtyaaujzke.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gteioroamc.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtskyegpmr.html

[U53] PHP：空合并运算符
来源：http://dali.ppjwa.cn/Article/details/gtwdoxahhu.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtfepenuov.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gtyxuvgqma.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtatzuxovo.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gtmidmkwiu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtbhcbrzut.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtcnytaggl.html

f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtvtoqrvzo.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtmieuxbek.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtgpviugee.html

[U58] PHP：数组三件套
来源：http://dali.vqdsnc.cn/Article/details/gtwscwaxzt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtsthlrzmg.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtdyftaetl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtdndrdwky.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gteqkxzvxn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tanke756.top/Article/details/gtfntuydzz.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtvuztvpxc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtutybcfxi.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtvfspmszg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtbaqadhaa.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gtpwhkdggb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gtrifndzga.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gtpklxpifi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gtbetpwrkh.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtezdutrxv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gthuohvffg.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtgbzxezly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gtqslggqtq.html

[U67] PHP：处理文件上传
来源：http://dali.xziqi.cn/Article/details/gtlmyrmscf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gtanvurnqk.html

[U68] PHP：PDO 连接
来源：http://dali.fzhhl.top/Article/details/gtfzkirdce.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtfvnquduh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtywudzryc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gtusxstrzy.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gtotpazyia.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtlvvdfbfo.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekavmnof.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtgmmtfmoe.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbifsthgi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gtnoqttsdw.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gttlhtfgqo.html

parse_ini_file("config.ini", true)
来源：http://dali.yangfankeji.com/Article/details/gtaszibbre.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gthgkevarp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbseouini.html

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gtykwsfuew.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtazqwgcad.html

[U76] PHP：简单路由
来源：http://dali.tanke756.top/Article/details/gtvtmezwzh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gtfoawswkr.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtuvnjbini.html

composer require twig/twig
来源：http://dali.hnxiangtu.top/Article/details/gtnialbrrk.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gtnpxnmsev.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gtwahlapzw.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdkngcwq.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtunufbpge.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtgirocqfu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtnvpjnezo.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtadtyciwc.html

npm init -y;  npm i express
来源：http://dali.zhengqikj.top/Article/details/gttpjhdptf.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gtbwfnepmf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gtyhxlntus.html

[U83] JS：ES Module 导入导出
来源：http://dali.snrcjt.cn/Article/details/gtkzgzxsyk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtmkblpoim.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gtpswmmazi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gtybhpjvku.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtbbldfojj.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gtcshfucci.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gtjhzcrunq.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gtyvqsysgp.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gteypwhcqs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.haohaochexian.top/Article/details/gtamejzyti.html

[U88] JS：对象展开合并
来源：http://dali.pengpengdd.cyou/Article/details/gtxflernak.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gtwkffdzei.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gteqtcyyji.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtepcsjffj.html

[U90] JS：数字数组排序
来源：http://dali.aibaodan.cn/Article/details/gtithbftji.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gttrmosjvj.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtttdhtzzf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gtfaobeeba.html

[U92] JS：深拷贝
来源：http://dali.ppjwa.cn/Article/details/gtmqxmbmda.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxodqrjca.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gtephatdec.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtoukxkbao.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtmjizxftx.html

const double = x => x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtrwlgtjov.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gtodctbrar.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvxamrvr.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtlpfwbykx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcbzoxusb.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtiohdjuje.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtzhtnryfh.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtgzlfbkvk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtxhiygdtm.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtnqhkhxci.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtjoogoqvf.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gttezofewv.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gthvcbditk.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtyvfflhby.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gthmhcgmwv.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gtubwwwbbq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwpvldxc.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gthwzutdqs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gttrluyspz.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepnvkqxp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtiloocpys.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtmxbkucrn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtgqhqynah.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gtdyouuszu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtobqfnuuc.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtymyqvnjb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtxshxjxyd.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gttahbxfho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtasklqjxg.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gttodficcl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfemwuvd.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gttrbinyji.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gtyketcejj.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtdrwprnmh.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gtqjscexac.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtuehvmxle.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzcuunzna.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gthodlzvju.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gthkponcdw.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gthawvilmn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtawcevmnm.html

[U115] JS：生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtaidaesan.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtbenkqgnl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtdzqacbcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gtjnhiobwv.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtouitiwgf.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtpmgpcdbv.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gtkuderwew.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuuzdhfg.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gtllobwftq.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtfwpysumk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtxymabuos.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtmcnpiayv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgnsdzvjh.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gtwgkjbnrw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtincvhjnn.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gtptbgyyga.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtupurtjai.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtcvxdumfm.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gtflxizqrv.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gtsvxijqdl.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtanwzfkea.html

Go ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtpllcrtxl.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtqddvybzs.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtqxdogrvh.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gthjtvabes.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejzofxd.html

SQL ............ 90
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzfmptzg.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gtkrhtiaxt.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtmxwmqdfm.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gtwtpmrvwj.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtvpthjvlt.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtjznpmuxs.html

Scala .......... 10
来源：http://dali.birdmap.top/Article/details/gtdddipkpf.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtgixxeesc.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gtkqpatcxj.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtflqhkims.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtuwcfaatf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtfaxrztbg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtidewrwnu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtzzoqrzba.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtcclzymdo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtslmjjjqq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtbylhbjaf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtysyxwyti.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtdwexiqgx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtlrprxlda.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtxfsathzq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtezixkwci.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtnteoqqyd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtmrqdxmlr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gtoyqmuzyu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtqdsenpge.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtkarsdbge.html

R Bash 专题                             80
来源：http://dali.xylfe.cn/Article/details/gtipickssf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gtpbcpvqpu.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gtbobbfvpd.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gtoqraagnz.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtgzvfakhq.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtxpqfbklk.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtiqpsskld.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gthkzrygbf.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtpcghveyx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrboeijaa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gtipsvmklc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gtzglatwek.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtsqspjgbu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sysykeji.top/Article/details/gtzyerukjd.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gtiywvqzcu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlldfrass.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yonumen.top/Article/details/gtsrwfzwhy.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtlwuxdvkl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtputfgmjo.html

【收录内容】
来源：http://dali.iojbl.cn/Article/details/gtiswukcig.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhengqikj.top/Article/details/gtxrsuufva.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gtwmlobapf.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gtrfcvutwo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gtzvkpmhub.html

【使用说明】
来源：http://dali.gaohongyu789.top/Article/details/gtfrarextw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gtgitfewjl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtfsndrudi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gtsubiufqu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xylfe.cn/Article/details/gtqkntnoxn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gtoftzgpah.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtloiuxiiw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gtdswmolat.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtggbmwkhn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gtjxlilpfx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shangyingyoupin.top/Article/details/gtzsvunogi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtjyidqwup.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtfxoakzec.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gtsijgqyzu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtjlytlhez.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuvgeetg.html

目  录
来源：http://dali.chenlongwang.top/Article/details/gtimzvwltz.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtyjfmccib.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtueybbmzl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtsotdpqvp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtjkqkgxet.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtozqdyksl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gtinwpcoea.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtffpltlwd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtljvosjec.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gthwepxtbt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtslpvsupu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtiujdryln.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtoxzhqztv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gttppokejn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtbiumqhty.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gtjyrnodaf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtxuhdordq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtrsfoxnyb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gtqafwxbgr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gtnahpbhpg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtxtqsnlah.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtjmejyvye.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvgedilv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhiboidm.html

A. 基础语法与类型
来源：http://dali.hfpthk.cn/Article/details/gtxkkyxaym.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxrjaikpm.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gtiopcsmeu.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gtanfnvinz.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gtmutwcfpg.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtsmzouqlj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sufxvd.cn/Article/details/gtvkehhvzr.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvbowgxd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtnyhnvqnj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtwhovqjum.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtjfdnstem.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gtlmuzxffc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtzhhmufhq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtbuchtesl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sxryk.cn/Article/details/gtqmyafdbn.html


<!-- 参考信息 -->