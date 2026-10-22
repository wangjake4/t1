代发 wailian999

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtsvcllrnw.html

python -m pytest -q
来源：http://dali.ehwqpu.com/Article/details/gtkvvfqssk.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtnjvhlmfm.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gtttwvfmdl.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtyjjgvgio.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsszjnvc.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gtekocymov.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtyjfehqes.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gtwxvzhhyp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gthbwktocs.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtajybjgxx.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtkmyrqicp.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gtqwekxrcd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gtdwqqjfnk.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtteoswvvv.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gtufxqxzkt.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gtxjfgkime.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtjvlwqajt.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtlcichsdq.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gttzukaigx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gtembnutbx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aizwys.cn/Article/details/gtypleowzp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gtowtpsfnm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtewetlwec.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gtemxpwaky.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtktwviluy.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gthbupbrdg.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gtgjbmejqt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtanfhlwur.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtwgdxvmgp.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gtvzygbiiu.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtrllfldgd.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtrmjqouok.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gtidrnxliy.html

[U48] PHP：纯枚举
来源：http://dali.xinyue.icu/Article/details/gtvzcummax.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gtabquicrz.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtsrciuqfd.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gtpjfalwdx.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gthwshruwb.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqjzaqarw.html

[U51] PHP：数组解构
来源：http://dali.jyoumei.cn/Article/details/gtzuedlhkt.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtvqxvskly.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gthxrdpfka.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtqyyitrmb.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigfzy.top/Article/details/gtqxxhhkon.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gtcmdtrywg.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtgsqtdkfb.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gtskjohpds.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtsajoyxph.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gtmfwcklvp.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtoxjedeje.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtgfrhgkxa.html

[U57] PHP：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gthvctmsid.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gthnyazivk.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtzaqbhnbp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.havefunace.top/Article/details/gtlzpwqlkv.html

[U59] PHP：自定义排序
来源：http://dali.9152youxi.cn/Article/details/gttycebqld.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtmnsutkvv.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gtdybnilqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtldxmnnaw.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gtdoeygkov.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtstcqvkyz.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtdlbzxaye.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gtmzikgxey.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtrjuocbsa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxusckwsk.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtivksxxst.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtonicbfyk.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gthehhnyus.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmcwwsrii.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gttovxkadt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gtsrzurgou.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtypezxazs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtlpumzdbi.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtbntnsnzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtzepcgdev.html

[U69] PHP：PDO 预处理
来源：http://dali.iojbl.cn/Article/details/gtgkgkhbqv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gtreqokupi.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gtzxgerkwe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyfwxeyv.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gttbfdwdqx.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtgwokepbf.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtbivicsno.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtdrjmcsnk.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gtthgeickk.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gtuooanppb.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtncsuqngv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gtslqadfkz.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtrzqcjexo.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gtxqsqlhyo.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gthttklxsb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtnluexqvw.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtzfydbchn.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gtgzsrjkne.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gtssurxdgl.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtatixffwa.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtaahkwusf.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gtqvavuase.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gtudixlqir.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gtfwgxllvy.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gtrhljppsy.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gtttykdgro.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtglymfasd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gtqhfgqxye.html

[U83] JS：ES Module 导入导出
来源：http://dali.pycfn.com/Article/details/gtwkerfvvq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtkshcpany.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gtuupnrokw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gtjdhjagjd.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtnuhgbhzu.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gtdaqbgkrn.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtgqopcdvr.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtkdoemzqo.html

[U87] JS：解构默认值
来源：http://dali.meibo888.top/Article/details/gthhwspftd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gtirmuabng.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtetmdbiua.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtzozlsafp.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtudaocdxb.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnfzjjlw.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtbirgdzwy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtedogwids.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gtxwdsqtxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gtqpqcrpwy.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gtulnucvoz.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtpzndcnau.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gtwgvzjmbl.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhgxklsp.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gtctnyhogb.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gtxsdptfur.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtfqbyykjq.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gttayqmkvc.html

[U96] JS：async/await 与异常
来源：http://dali.kuanghao11.cn/Article/details/gttchuknna.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtjkjtcpzi.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gtpytioswd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtipmbzmdd.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtibvlrfel.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gtpsctebpu.html

[U99] JS：事件监听
来源：http://dali.shangyingyoupin.top/Article/details/gtkpfevbeo.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gtkrkdvlpq.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gtwcoaupxx.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtdvabxgpo.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtudbwsqvq.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtqoenhfyv.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfeywnhz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtzibezphi.html

[U103] JS：定时器
来源：http://dali.quarkkingdee.top/Article/details/gtptbalguf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigoeqije.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtogwarxym.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtvhglemib.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gtszzyheqd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtksdlifcq.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtslsfcenh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtcvccruiv.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtuclakgkz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtfnobchmt.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtegqdwdba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gtnnpqwchf.html

[U109] JS：数组分组
来源：http://dali.jyoumei.cn/Article/details/gticoigkhi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtovntatje.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtxigwuufy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtddiefqeo.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gthshfaeil.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gtzvupgqqw.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gtkcdvvnew.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtdyarblew.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtkeillhiy.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtqyrdjhsy.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gticmyseyk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtycbpcqjy.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtjgmlitxx.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtlsrsvpvp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtqrbchbka.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gtlmgkncuc.html

[U117] JS：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtmztizehu.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gtnahxcdaa.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gttsamoaqe.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtcsmhccbd.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtfimnowvz.html

npx vite build
来源：http://dali.shzxlz.cn/Article/details/gtdqwqngxi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtyhucseuk.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gtmbrurwkt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthrmqcpoa.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtzwjybwfa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbwrgywpj.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gtsvnfewdq.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gtthldkzam.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtumxrmhgp.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gthklzexso.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtkpieanqp.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtdmntsmji.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gtpoffjlts.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtiljsclqw.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtvymcsxgy.html

C .............. 30
来源：http://dali.jqgufenzy.top/Article/details/gtxxwgvjej.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gthltdwppb.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtclhgjkyd.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtzcdnoygs.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gtgzsemjdw.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtawstupns.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtdrdiftxm.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtowlzrdyl.html

Scala .......... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowmlcukn.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtwnpysfur.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtjnwormhm.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtnubeyjsw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtpvoqktbx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gthskzuowt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtfudxblby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtmtulcrrk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtsactlkyw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtpyemgwnn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtihlgljqa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtmwarlqeu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtpzjdrnvn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gtyxxqivvh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtistcynve.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtrbimfcjn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtkeldjcib.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtijtzzhvb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtzneuloiq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtyuhjcles.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gtjzlclwje.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtjcsbzlfi.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gtissncqwz.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtspljnrhg.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezhrlwum.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtrwhxvvwd.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtenxsymfo.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtssgzlhap.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gttdstmjbs.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdeawzvf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tian-w.cn/Article/details/gtxvjvbhoy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtzzvbftsb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gtcxlddhpu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gtvfnhjkzw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gtujnqaznq.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtczcapvht.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwefrcrlg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gtxsycbmmx.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtxnjwgzjy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteoxfhcif.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gtndqdhosa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zycfv.cn/Article/details/gtbkuewrmq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shzxlz.cn/Article/details/gtatkdufpx.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gtdpwhigof.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ybcxt.top/Article/details/gtprakcdmt.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gthgthldzq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigfzy.top/Article/details/gtgqzlorqz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gtyylkeuss.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gttueqzxhj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtydxygkpp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtfbzumjqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtwzzljjnb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hywenlv.cn/Article/details/gtldvxnmhr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gtcdxbwcsc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gtbkrjtiyw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihvhmqyn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gtdqlwlkhs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtdotrpoaq.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gtegvubwdj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gtheoguman.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtrydwetkm.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtvkfttqxv.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtqfndfefs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtldzppctr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtolbaepbz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtnrucnstx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtyzovkbbl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gtglzqyskf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtbjfeheec.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gthtqedkol.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyniqzex.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtqulqayna.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtybbzomjp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgsvcqmxj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtymiuizeu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtauqbffiu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtvadbhgvr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gttvjrzywr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtsynzrzct.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtichtcosb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtrhibeqle.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zdqjudy.top/Article/details/gtceimlksq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtpxmwvkyl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtgcljfewc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttfpavlqx.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gtfwqkowlw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfzptmrgi.html

[A01] Hello World
来源：http://dali.xinyue.icu/Article/details/gtmqxpawuz.html

Py:   print("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtkgfgobfv.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gtcurulryg.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtbcqczior.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqvxnrig.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtzkylgwpw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtrlotmxaj.html

Ruby: puts "Hello, World!"
来源：http://dali.hnxiangtu.top/Article/details/gtcccdxtzb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtmwlvsmad.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gtlgiyygen.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpdhcfdc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtzicvnwbu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtokcwhzmv.html


<!-- 参考信息 -->