代发 wailian999

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtauzfoyzh.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtmalxtbdk.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetaivesd.html

ruff format . && ruff check --fix .
来源：http://dali.nwbrower.top/Article/details/gtvbnxpzqd.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtvpabmocz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrshzzbga.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtbkpsjtef.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gtkznmfkvl.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtjorkasrg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtgceeyfgh.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gtnoxtqaie.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtdwqwigjw.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gtmbeflwnj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gttbjsrvya.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtafkphdub.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gtbypsjnza.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gtqwktavtf.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtirihvean.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtsmktrgwg.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdfhngnhn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fengsongda.top/Article/details/gtwazbrocj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtcyyluwnr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtmgasqwyt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shuidangran.top/Article/details/gthwxgxrwj.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbnobabe.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtutqfgkpv.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtumljwfuc.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gtoezalupi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtkzsywzlp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtwdzcdpkz.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtgxixxsht.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtcspbjjpg.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtvplgbttr.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtnahibqqp.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtyvdzgklg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtxglxiwbl.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtsoghozxq.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gtkpwyljbq.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gtsoiyskgf.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtpcrbchxh.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gtdxccunsc.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtbfhujfmh.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtdcpbbmaz.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gtmivfgapz.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtwmppxklo.html

$v = $a ?? $b ?? "default";
来源：http://dali.jyoumei.cn/Article/details/gtkewpxmfj.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gtoqdgocrz.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gtjxexwdej.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtzphgzlbx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtsqvvramt.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtdwmlbwmk.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtqqjqdffe.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtcpcwrjkz.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gtlzibmztx.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtdsxidfew.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtxtoiyfgd.html

[U59] PHP：自定义排序
来源：http://dali.yj20258888.top/Article/details/gtpkjfrvrt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtypatghjc.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gtugjhzhot.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtyswfmmhr.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtlotuidtw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtfnndatuw.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtmslnlryl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtjvwybeak.html

[U63] PHP：文件读写
来源：http://dali.pycfn.com/Article/details/gtoduvruiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwolvcbds.html

[U64] PHP：目录遍历
来源：http://dali.yonumen.top/Article/details/gtbyqoxlkf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnatyrsf.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtjmwgivgd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtldfkbnia.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhsldoms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gtvencmjgg.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtiiuoklxo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jianghu66.top/Article/details/gtbzfaiard.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtffbubxjc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtjwoqamiv.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtycjfqsua.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gtfpfsfwsu.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtysbakkhn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtjxxslsfd.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtodhrcmnw.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gtyuchltah.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtdhhvlgal.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtmsywuxlt.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtpyswldcx.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gtwgczhimk.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtmmzoinih.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gtxiznozuf.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtbvsorriy.html

composer require psr/container
来源：http://dali.svipenyu.cn/Article/details/gtmfplwfwz.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gthwspltwi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtymfnyikc.html

[U77] PHP：模板渲染
来源：http://dali.hysaishi.cn/Article/details/gtpztkfofo.html

composer require twig/twig
来源：http://dali.yanxiufei.cn/Article/details/gtrnsxwcjb.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtxlahjweh.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxvgxena.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gtuogthsse.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtldnbmfxq.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gtfwqeakfr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangdashe.top/Article/details/gtcqcwapdh.html

[U81] JS：初始化项目
来源：http://dali.chenzaomai.com/Article/details/gtjwirozxq.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtppmygrzz.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtrwbhcyfu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gthotddady.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtyayyaqrp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvefzjvgy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoemvrqd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dashuyun.cn/Article/details/gtzgdencqs.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gtidfzebfs.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gtdiqkrpar.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gtsltlzrmh.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtxzbciggp.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gteobgxhmd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtjwzcttce.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gtxrruvese.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gteakuocgu.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gteajzfrqc.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtwoxzgkpz.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gtketbuexc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtvexrswpk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gtjdgssjsz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtucjipixd.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtpgyfzbxi.html

structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtxcvijqfp.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtxhxmhdod.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtzmrortwg.html

[U94] JS：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtllurhqzx.html

const double = x => x * 2;
来源：http://dali.hammf.cn/Article/details/gtmubypplx.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtbailldpx.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtkqghpfex.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtufvwetuo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtmrrumdfb.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtfnddvsyp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gthxlklwwg.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtrvtqckta.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gtqhomzrks.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gtdnstowxa.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtgbicvaeg.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gtgdfidtoy.html

document.querySelector(".item")
来源：http://dali.chenzaomai.com/Article/details/gtbxwblefr.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtlnclyfva.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gthroxnkgo.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gtzyqfrylm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gtsnqfrevh.html

[U103] JS：定时器
来源：http://dali.ybcxt.top/Article/details/gtcuhwrxwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtrzxgvqza.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gtrzvybexq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtpvhmszls.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gttvopmaou.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtigiicesm.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtrqhqvvks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gtnbenaaix.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gtdzwgyjmh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtkzgaiyla.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtceregukv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gtyjbedvjw.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gtmetsqcqv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtusjnrsvy.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gthzfclpzb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gtlfvvnolq.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtuppcwyky.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtlmlcieca.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebfqvhvf.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtilgrhfze.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtavppgifm.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluyhgnnk.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtzgocjxvq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtoozouygw.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gtlqrcgrau.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtpskdxfco.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gtowipvoag.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtvgbgryfe.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtifxzzaef.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gtjjeihkiq.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtpwruavbo.html

npm i -D vite;  npx vite
来源：http://dali.fengsongda.top/Article/details/gtgdzodxqn.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtmhcsjrvc.html

npx vite build
来源：http://dali.sweek.top/Article/details/gtumsutxzw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtmcodajfj.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtsevjufqn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttkshmvxk.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtivqiffls.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxkrzotak.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyvbzkqm.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapefknor.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gtiaaqkmqs.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtxixejlrd.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtbpqqvyrk.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtcvoxtyea.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtjjusybmj.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtrwhpgzeq.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtpsusphwb.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gteupywbwx.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtmmpxujpc.html

SQL ............ 90
来源：http://dali.yangfankeji.com/Article/details/gtwyqhdnng.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gttorwebas.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gthfleveqo.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtmojtkxyi.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gtgktwulqf.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtbxapncjt.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtpydmkwet.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gthfmalpyl.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtlfbsrppx.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtkwxggrgr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtcbewkepj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtznguccbe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtocmglono.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtkbocaokq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtxnqamkex.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtjjhxvpfg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtsbsunvjt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtijlfyaig.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtobfgtuzg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtrzjhimhi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtrromtzrx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtpzxlhuzj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtxmoiqmef.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtizmuwpir.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gotoacloud.top/Article/details/gtjhneqcvg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtbgbgawil.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtflwbpdkn.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gtukwhtmzv.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtxcsmhyce.html

T 其他语言补充                          60
来源：http://dali.hfpthk.cn/Article/details/gtttbfgqxf.html

U 高频实用片段                         120
来源：http://dali.bjfxy.top/Article/details/gttuvizmqp.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtmrovbsgy.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdighpnx.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtxsowngub.html

使用提醒
来源：http://dali.iojbl.cn/Article/details/gtdhzeceuq.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtlqtrepnx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258.top/Article/details/gtkzqewbxh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gtprbcwhpo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gtslmlwksy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gtuhkzukps.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jlsjyb.cn/Article/details/gtqhsxjnsg.html

—— 文件结束 ——
来源：http://dali.yj20258.top/Article/details/gtqoaauqnl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnmavovcn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cucudq.cn/Article/details/gtkjfjcqkx.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gtswnbyndz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkbvaixli.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtwgidgayy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnxiangtu.top/Article/details/gtogmxmmev.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hysaishi.cn/Article/details/gtvtmamfbn.html

SQL · Bash · C · C++
来源：http://dali.ivvv.top/Article/details/gtkgdkxwqg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtgtwncyda.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gtswzfavzj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gttwekbltf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fengsongda.top/Article/details/gtnstdwmdg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.meibo888.top/Article/details/gtzbopjfqc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinghuilouyu.cn/Article/details/gthxmzilxu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gtuoqpcrbp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtyljelcqy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shangyingyoupin.top/Article/details/gtpayaehiq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gtigrbkufv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtznbrccst.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.c1oappe.top/Article/details/gtpfrljdxa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtokqdox.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.vqdsnc.cn/Article/details/gtvcakuvza.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gtotdaopvv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtfoxwjluw.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtomvaczyg.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtubawejxd.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtizaodigf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gtroqhmoul.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gthlsjexns.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtkeaszrqo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtwkolywbg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gtcxggvreo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gttlalqqwj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtlipquajq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtjbnivtjp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtmkwwnkpi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtgukbxktj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtvzbzxjma.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtbglmtglv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gteozqwtmu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtlevzdlxy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gtewhhseeq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtojybokpp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gtbmpdagpu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gtxulowenq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gtpxnumqqd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtzbfliajf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtoiqaqyjd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjsexqic.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtfxsszeet.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtofbltusf.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgosvnah.html

Py:   print("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtueiqmpmb.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtagiobary.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtripyvtfj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtcjpxzbmu.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtzrauzljn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gthnplwbnl.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtidprlcth.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtgnslfrkk.html

[A02] 变量声明与赋值
来源：http://dali.hywenlv.cn/Article/details/gtbpbdajpu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gtzfznkdoq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtfimtjsry.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtovdjvgcc.html


<!-- 参考信息 -->