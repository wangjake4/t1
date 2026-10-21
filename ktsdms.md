代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtgcisvrpl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtscswcxqp.html

[U28] Py：类型别名
来源：http://dali.yuxming.cn/Article/details/gtoqayzlxc.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtsttqivbo.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtvnpesrsb.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gthzefqwdg.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtlahoyezh.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtkvwlxnwt.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtbcczmsyh.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtdztgzssh.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gtezvsgytk.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gtpbiulqpl.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gtxualnpci.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtxorfdcig.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtpgyvelqu.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtrasmemfq.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gtumifxdiq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gtxfkuwyzl.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtulnklcgn.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtejzvptcr.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gtmniakwdb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gtgzmeutyi.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtafmjfgug.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtbayxaxav.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraoykjry.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gtyexwpzlr.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtfojjqsyo.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtunslxblb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gttgmufyjn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtbupnhirk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gttwcxclhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtiksmdfar.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtvqvhdtvk.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtfqsvmhin.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtpixxrdjo.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqabbkbe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gtvhlyokgv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtyihfojjp.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gtfkqxoisf.html

?string $name = null
来源：http://dali.gotoacloud.top/Article/details/gtfxomkhts.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtyvbjilvl.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtqcmjildf.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtdwskxlud.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgtlwmms.html

[U49] PHP：只读属性
来源：http://dali.dashuyun.cn/Article/details/gtfcwttxuy.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtiadlngfg.html

[U50] PHP：构造器属性提升
来源：http://dali.yongpay.top/Article/details/gtvtrjldwc.html

public function __construct(private int $id) {}
来源：http://dali.ydzc1.top/Article/details/gtfhoxsswt.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gtpydbqziu.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtcjylibke.html

[U52] PHP：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtjtsefcgo.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gtyaqicsik.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtlwjqdosv.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtcoecnvjr.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gtmztooawn.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtllnxwcpk.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtgxwqlkqn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtosxbxvon.html

[U56] PHP：命名参数
来源：http://dali.vqdsnc.cn/Article/details/gttvodgirv.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqouawttn.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtqxmtdggv.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtrnzemeit.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtsebiefyu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sysykeji.top/Article/details/gtvipspkpo.html

[U59] PHP：自定义排序
来源：http://dali.yvedp.cn/Article/details/gtijwgwvxl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtexmnkrze.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gtyipybpcp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtgxynymut.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtjrqpvvya.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtxbrgufih.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtcggsnnxz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsnnnghl.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gtrvqnehyg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gtcsqehlwt.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtwkgrqjyc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtmsmigmnf.html

[U65] PHP：会话
来源：http://dali.shuidangran.top/Article/details/gtytkylvpn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtaarmplcc.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gtnfoehrcb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sxryk.cn/Article/details/gtfnrdtnih.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gtgdvyndaa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gtmawljwlq.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtoguqpesz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtmnjvezco.html

[U69] PHP：PDO 预处理
来源：http://dali.zhongyouzk.top/Article/details/gtjasfxsml.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gtcysszgwd.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtbcktemnn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtjsczlarj.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtjwkxrcku.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtfuilplwf.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewoyvwrk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gtjnrloavp.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtsmxyspwg.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhbozmyu.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtiyvsqhfu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqyvcbun.html

[U75] PHP：依赖注入
来源：http://dali.yuxming.cn/Article/details/gtfkiynelp.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtugenewuy.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gthgmuvqmr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.c1oappe.top/Article/details/gtnsjfenoy.html

[U77] PHP：模板渲染
来源：http://dali.ivvv.top/Article/details/gtksyfutdv.html

composer require twig/twig
来源：http://dali.daria6918.cn/Article/details/gtrqimbobb.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtogkrmkji.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtqgioczyu.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmutxnpa.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtokpjevbf.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gteunizznd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daxiang520.top/Article/details/gtlusbdfqt.html

[U81] JS：初始化项目
来源：http://dali.gotoacloud.top/Article/details/gtdwvnwzba.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcobiiohl.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gtiscnhkrz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwgzzyuu.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtwknnfvel.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtcassefnd.html

[U84] JS：CommonJS 写法
来源：http://dali.jyoumei.cn/Article/details/gtlucbufgx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gttsmxfsze.html

[U85] JS：可选链
来源：http://dali.cdnleiting.top/Article/details/gtcleeihqy.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtmgrqmwvd.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtcozbiunu.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtqyoseuav.html

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtnxbkwbie.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtfqubzqgk.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtfkdqebvn.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtdnnymadt.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtkwcqjbsu.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtosivfmci.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtzycltvqr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtinmamggf.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gteennnxiq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gtenywztvs.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtrcmstvim.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtiygyvkim.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtlrsuwkhf.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gtqqosctvq.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtvpazwjsu.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzsdupje.html

[U95] JS：Promise 包装
来源：http://dali.c1oappe.top/Article/details/gtllqnoykf.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtjscgfxql.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtramqjble.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gttqgucsof.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gtoxkmdmsg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtweveapqi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtmmfcfkjq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gtmicdehpw.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtwzewwwbt.html

el.addEventListener("click", e => {})
来源：http://dali.0kj1m.cn/Article/details/gtukmtgwkj.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gtxnujkdyn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gtdeesnyij.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtuggvqfon.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gtpmvjelnq.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtvwjzksbj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gtxoyfxfxs.html

[U103] JS：定时器
来源：http://dali.kuanghao11.cn/Article/details/gtewyinlxd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtyzutyrub.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gtbeptnxcn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtvdxaegtl.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gtjkltfxtx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtwxvfssaj.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtttubeenv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gtykybduxc.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtdivunujm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtusxucpqy.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gtphplgwsg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtkbsitiak.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gtsmwavmdh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gttbdopgto.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gtmachcxjz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtgswguubd.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtnucrevuk.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtnbuvdlle.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddwtagir.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtouixipfc.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gtahxcoqwt.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gttzlrflcz.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gtvffznvoa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtllvfkehe.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gttikrvmji.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyehpacq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtftvlxiph.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfzxasrhs.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtvueuhxja.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gtbitamjkv.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtmfvelnhn.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gtilxaarrp.html

[U119] JS：生产构建
来源：http://dali.jinqigufen.top/Article/details/gtwnhmxhoo.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtleenhmkm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtesjwqrhy.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gtnyeqjmap.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyaohrudw.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gtcqxrhaeh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkjgjyjno.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtpgepiowt.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtlscvwnjd.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtnfwhdxqr.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtvooopqbn.html

TypeScript ..... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtcvfircat.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtobgfutfp.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtgpyukhgb.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtukyqiytl.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtgnnjohuv.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtvfjgpeow.html

C++ ............ 30
来源：http://dali.guannengcc.top/Article/details/gtgnapcydq.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gtfmbdplce.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtzosuruid.html

Kotlin ......... 15
来源：http://dali.meibo888.top/Article/details/gtvaviowcb.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtlwbhslaa.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqpuyjws.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gtfpdenrvo.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkdxlaqi.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtqlottfph.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gtxtbrldss.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gthebksazr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gteliqqshp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtncyxkuom.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtcevuuxeu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtnphkqtax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gtrgdcheel.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gthxudrhvr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtwrktogts.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtbabzctdf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtrpqwilbn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtpzplzisj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gttbzrhopt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtgymkyahw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtfopgkouh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtiasgaxpu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtmytlgpzv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtlkivkhvs.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gtmkiclsnd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtvokshhhu.html

S C / C++ 专题                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaheyibd.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtglhfcaqc.html

U 高频实用片段                         120
来源：http://dali.wangdashe.top/Article/details/gtyghgajup.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtrxryevts.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmjisqty.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtmckogofa.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gtgfxwmnzz.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqbhetin.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gtqgnrgqoh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuxming.cn/Article/details/gtwnxdgwrs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gtozagtruo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gtzivwacgu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gtoccypdwp.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtozyqpjxr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvucdfmvg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgufenzy.top/Article/details/gtcgsrquvl.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtuqmixbrl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsvspqwpz.html

【收录内容】
来源：http://dali.yuxming.cn/Article/details/gtjdyoqjaq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgufenzy.top/Article/details/gtucuiispo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gtwkegycem.html

SQL · Bash · C · C++
来源：http://dali.zhongyouzk.top/Article/details/gtftiunwnz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtxeuxvaxt.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtvinhnaht.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gttgvtvbdp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gtlqwqkxji.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigufen.top/Article/details/gthppbjgxp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtccvxmlql.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtjljdvkim.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gtcwugjwvg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtcoxohvbr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gtbesysksf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtrgvcfwmh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gtmgihdjdr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtbxdfqsrp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gthiktbgah.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gtxdpkgdii.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gtjxzmtdcl.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtaeekfumt.html

目  录
来源：http://dali.yuxming.cn/Article/details/gtgovejlud.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtwkzzivty.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gtffmcdlro.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtdatfjinl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtyvzcbotd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtvtkdfgsg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sufxvd.cn/Article/details/gtdxwdauff.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtuwwvomwo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtblmfwerl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtaqitgjgv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtfujvlcee.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtnzvlvpsz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gttyfysvgn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtkthwanpf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtbmylxswu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtzjjjyhfp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gtynlwzbox.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtfmxfmhpy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gtdxnwswoj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gtkxhzggrr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258888.top/Article/details/gttyhuarjs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtondoplqe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtmlymkokc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzxvtimfm.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gtqkydrkjy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvowsuwll.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtujoqpyxq.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtpvtakqsb.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtxppmoohp.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtejzinsmw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtghwylwtf.html


<!-- 参考信息 -->