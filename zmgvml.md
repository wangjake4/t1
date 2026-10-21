代发 wailian999

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gtrzryjdfa.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtfgumdxob.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtdpjuzmer.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtchwgedyl.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtheznydvn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gthzryjogc.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtjryqxhce.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtzrxpgsfi.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtmikwvcii.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaepvvyci.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtdugmeqrj.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gtryflqowe.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtoprntjfw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gtrcboamqn.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtfzmnohsi.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gtylxxubwu.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gtxrvwbemx.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gtfaobtdcn.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gtikktdroj.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlfduyhy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gtqcqkvnnh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdtgiapp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gtwrnjzjpe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrdoryjd.html

[U43] PHP：声明命名空间
来源：http://dali.svipenyu.cn/Article/details/gtxwxhbtno.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gttrlzhebe.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtqztoqdyk.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtkyykgoyt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtytidtcka.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtupffimcp.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gtryondkoj.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtzyefmpny.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtcdfqehuq.html

int|string $id
来源：http://dali.hywenlv.cn/Article/details/gtkigtlfrz.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtdrwjhzmy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtfubuxsqr.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gtwshgkokl.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtsgulzmqw.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtioxdcsvx.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvhaxjum.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gtfuiqlfxn.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnfxmhdj.html

[U52] PHP：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtpqbsxqtb.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtpsxsgmds.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtrxdrsmnv.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtuvecfmel.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtktcgdfns.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtimixsjcr.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gtaaulfaqi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtrwpnoiet.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtssjqgwfg.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtyzqusifz.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gttnaitbmd.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gtqmdemkor.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gtpwrmzvdz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gttkdhiimy.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gtvwuzlxob.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gthxhvafnz.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtiqkqiihs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gtrxepimoa.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtxqbjmyxd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtahdmrepk.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gttpzsuupq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gtmbksvnju.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gtolnxhvsy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtfaxxjutt.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gtkfowlzlq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtypwhazgp.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gtwceajeal.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtpcljczdr.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtaduwuuwr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gtmybkllyy.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258.top/Article/details/gtfpadprru.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gtuimhgnzi.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gtbrghxzvn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gtaurjgsjt.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtldvcmdyy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtpwygfxek.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gtvmgkbuec.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtxndombka.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gthybgqnoc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtgqkfuuve.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gtoahjammx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtbksqduhu.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtkhvbznbc.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcptpkzpo.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gttorikdbg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtuvuljpll.html

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtvexgtbme.html

composer require psr/container
来源：http://dali.gotoacloud.top/Article/details/gtafsqqyzh.html

[U76] PHP：简单路由
来源：http://dali.tian-w.cn/Article/details/gtvsnvlclm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gtezdeerzn.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gtjljakxit.html

composer require twig/twig
来源：http://dali.quarkkingdee.top/Article/details/gtjfafqieb.html

[U78] PHP：单元测试
来源：http://dali.cheryme.top/Article/details/gtrjcmgxwx.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrpfqrtj.html

[U79] PHP：静态分析
来源：http://dali.zhixingplan.top/Article/details/gtbuwbrqbn.html

composer require --dev phpstan/phpstan
来源：http://dali.cucudq.cn/Article/details/gteulhplaw.html

[U80] PHP：代码规范修复
来源：http://dali.hnxiangtu.top/Article/details/gtpxirizwb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gtwrnbzouc.html

[U81] JS：初始化项目
来源：http://dali.feifeiyinyue.top/Article/details/gtckbgaceg.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gtsgpquohv.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gtqsyjheaj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtswkxoauq.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtfgltwuiq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtkvwuhzzy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojxogvjs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gtlgwemwjp.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtfabdfcll.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gtwyhkftpq.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtbgpmyvxi.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gtnklknlrs.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gtxgotvdol.html

const { a = 1, b = 2 } = obj;
来源：http://dali.feifeiyinyue.top/Article/details/gtpsiytmra.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtxqlytryy.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtlxuclwpt.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gtjbymgamh.html

[...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtjuumybek.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gteahkcdzz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywabynul.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gtkccypati.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtzzliqcfc.html

[U92] JS：深拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzbdbrpr.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtaxafqohk.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtndedrhbh.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gtletwfajt.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtanekkrat.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gteubljjxj.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gtekbbmqdx.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gtuaeuzjia.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtqohfjdzx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtwctwsjla.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtybdfmdti.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gteplbcmad.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtxalklckq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtrmeypves.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtlzyhfshd.html

el.addEventListener("click", e => {})
来源：http://dali.jianghu66.top/Article/details/gtpjrlpqbv.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gtwgjeniac.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtloljbcpc.html

[U101] JS：classList 操作
来源：http://dali.fengsongda.top/Article/details/gtipdsdpjz.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjjotsrb.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtcjpfrzzk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtzpqlqctl.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtycmhmxwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtodxrjipg.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtsihvwuol.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtwgsqgbia.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gttooimzcy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpmklobz.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtdtcvutyo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtufggneti.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtelfqykub.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtxbviqgxw.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gtjllgdbcx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtmycsrplm.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtnyyfxszj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtumtqchvf.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtghnvjkib.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gtwniyatri.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtvisqmfor.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtpqatwzjm.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtdlimpvto.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtauwkdyul.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtsohuvhsz.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtaekteckk.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gtwtgguslr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtpgpcnvhu.html

[U115] JS：生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtzfxllnoe.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtednlkuxa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtkgepirnz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gtxxvzlcfs.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtnndoqlbo.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gthcnhauhx.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gtqdvfmrvy.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtrwuhbqug.html

[U119] JS：生产构建
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjehxdfeu.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gtjwaqisot.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gtpyhppnac.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtyhoanyme.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtskngqwif.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gtgpzaskko.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvyevddrh.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gthkcmmdqf.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtfjanaupc.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtxzphjbos.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtbrmarqwi.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gtwozfnlar.html

Java ........... 212
来源：http://dali.birdmap.top/Article/details/gtviazgtkx.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtukvelsvj.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gteebdbpac.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtedofnpbg.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gtafjcqvmn.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtvwkziwtt.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gtqnlptetj.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gtfkqsrovy.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtyuusikqe.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gturkvwjwz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtrcoznesj.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtwcenavud.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gthzdbiouv.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtamribwgz.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gtwpjuoenz.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gtplaszsoi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtecsmuhzy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtcxlefhdw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtizyxprws.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjqdebzf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtmqccguku.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtnpppwkmz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtmynxdxmm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gthbcjspxn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtdlsdbezp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtfqdxldsx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbekamued.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtxcmksbfh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtuhspuhmq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtmdfuxzrc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtifvlwpwo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtuolzorjh.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtzxfnwwkp.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtsoivobma.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gtdnduoqxq.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gthrgntxop.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtdmgaqwhc.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtcoqdtbln.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtgjpvcnzc.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtxkixwmle.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtyoqmxmzx.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbjcscmm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtiseheqes.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxuanxn.top/Article/details/gtawijqsjp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gtlfuqzeko.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtxhwbfbjh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtmprlhswb.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtnpfhfxgr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzkobvlij.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtwjadsati.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtmkfcencp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwvzopesg.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gtngqlwqcm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtsttyjxpu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gtxheqscdn.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtokvexlqh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gtmbkhtbjq.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gtdgzoublz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gtmtnhzvfo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gtslmczdej.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gtbthjxpmv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gtprlthvrc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gtoyoxcecg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gtfwbajhwq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gtycgsvqbx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtvroptmin.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zycfv.cn/Article/details/gtyftddlnb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gtfbefxllz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gthqouybkr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwckxevni.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gtayvnuvfg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gticnfjzig.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtvpggtyjq.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtiiwgmjzs.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaydtmlw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gtzwkfgplr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtiulohzzh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtzqtwodad.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtpwqwnmwa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtgbqaehdb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtordygmky.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gthrsaujeh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtgpfkwizm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtpmpknxrh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtemphwkba.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtbqgfdtsf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtulzhwnds.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtguguksay.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtwlmehcsw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gtlfhcfrpb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqssfpza.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtljnzpids.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gtszxlyssr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gtbqhpzqdt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtyecwsqet.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtbtkyrycc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwllplis.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gtdoqundsm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtiubsjvfd.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtewfxudnu.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtubrhkjdp.html

PHP:  echo "Hello, World!";
来源：http://dali.daria6918.cn/Article/details/gtgljdkbcc.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gttsiymlra.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gtjdoeezyf.html

Java: System.out.println("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtpxdnwokn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtfiaihhsd.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gthpgqozlk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtjhgsagcc.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gtmwwxzhbn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtmmqbufma.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gtbscwmzys.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtjsvtnjiv.html


<!-- 参考信息 -->