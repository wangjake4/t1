代发 wailian999

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrtblxaj.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyahjzvcp.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtelchmqbu.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gtvxrftxtj.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtxlfawlqp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtryqlzgre.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtlzfyouwu.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gtnjcfbdlt.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gtmoxqazqf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyaqkcjp.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtpjcfscoj.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtutmltzqx.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtidnnesqg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuanzx.com/Article/details/gtldbchzpx.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidlftolc.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gtdmbspdln.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtfhasarlu.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gtopcalpui.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsyvbnau.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gthjikbnzh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtimaieunq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gtgfdgwcfu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gtjcwxtzam.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gtgllvcvzh.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gthxjevjxi.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gtwddaoyxk.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtrjdaelut.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteakbzcct.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gtnliakryl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbjefknno.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gtzrglmpqm.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gtuvqykain.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtjslsxoek.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gtdoslakmn.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gtegkbmkhm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtzeizuuve.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtdeqtdfkv.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gtagxnbxfa.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtttxtwjqr.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtezzdihdu.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuzzmnof.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtoqeoknco.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtncdsspoo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtozdotarw.html

[U53] PHP：空合并运算符
来源：http://dali.zhengqikj.top/Article/details/gtdiesdvyj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtckgtokpx.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtuhofwbid.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtrocljdus.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtkuitwcrr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.havefunace.top/Article/details/gtztuxacca.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gtpemphnbs.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtttrbtxgo.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtubfrcncr.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtmhcedkdd.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gthygiqeny.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtwliopcrk.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gtfclgpdld.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmehmvtki.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gtaziobmnf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gtfyxdpdtz.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtprccnjhq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtknccczia.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gthtmhnvbe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gtvplcesqf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtyxywnkzk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gtasbejlst.html

[U64] PHP：目录遍历
来源：http://dali.gotoacloud.top/Article/details/gtamyinliu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gtyteiosgm.html

[U65] PHP：会话
来源：http://dali.nanxuanxn.top/Article/details/gtmrtrmesm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtbvmdwzeg.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtfoxikiqk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gtmqlpyqis.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtxlcthdih.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtnwwndwfn.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gtclnfaqms.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuanzx.com/Article/details/gtkfldnnro.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtqszjcnzb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gtpyyozqxl.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gtatrdplve.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gtizwmknvj.html

[U71] PHP：抛出异常
来源：http://dali.cucudq.cn/Article/details/gtnkgdfidi.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gtfiayokdz.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtwnqkzqnq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtjaxycorm.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gtzcbtugqy.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gtxldeopqf.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtimtyqdnd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gtipjlcwhz.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gtmfuuaeqs.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtevowovek.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtesbpzfhf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gtecfpjcdo.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfprajknd.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gtsepmslhp.html

[U78] PHP：单元测试
来源：http://dali.havefunace.top/Article/details/gtjkyrolhp.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gtagmclumt.html

[U79] PHP：静态分析
来源：http://dali.xinyue.icu/Article/details/gtpeehkorc.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtsfhkfawz.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtkytjsmlz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtpbgkszqo.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gtolfukvqk.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjfjtxfu.html

[U82] JS：package.json 脚本
来源：http://dali.chenzaomai.com/Article/details/gtxwjqscxk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtnymkcxob.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtnbbngmsc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtkooniibp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gtsmmonknj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gtwpygqyaa.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gtlumdkbpz.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gtndedgdsu.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gtvzfgmgql.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gtkiehpefg.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gttlnukarn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gogol.net.cn/Article/details/gtnpavxogl.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gttimzgxaf.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtjbrfflzo.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gtryusspox.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnogailb.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtxvxootdf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtmogrthis.html

[U91] JS：对象键值遍历
来源：http://dali.cqqwz.cn/Article/details/gtfvidomcy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.iojbl.cn/Article/details/gtmiwbmeln.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtreodzgrv.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtzzknrsfx.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttbahjipp.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gtoeydqwgo.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtnfsrjcsy.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtpydlpmom.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtmwhozetz.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gtbqpqamrf.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtmflibncn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtqhrdbnfj.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckggudfi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhuglgqn.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gtxlpiqdaq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekyjmera.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtvfwcxgxp.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqqyairp.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtfqqmurzq.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtjtpwzzwi.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gtzxnazgiy.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gtmkuymrxj.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtquoaunpd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtoqogvdda.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gttruockex.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtevgifsih.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gtdbzcldwb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtufbnegqk.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtzqatfmku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtolsyvanq.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtilptejcd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtngepqfjt.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtqzmlcboh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gtlubzojkr.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtfjgtqfna.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtzwdtheku.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtlwsyiuid.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtirkuwznt.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtfhumtmhi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtmkebtdru.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gtvlbrmezg.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gturxvajvi.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gtsmpwluqg.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtyoomevjo.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtlmbhfkvl.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtsmiysend.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjecrkscn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtiuurjuex.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtkxdlqhfc.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtbhdtwgnm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gtdsebbyic.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtsabjdafc.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gtciloarcg.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtmmeudrjh.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtpyxymdlm.html

npm i -D vite;  npx vite
来源：http://dali.daxiang520.top/Article/details/gtbyrgzxtu.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gttlsvqzwa.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gtlgollyyg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxlvlghk.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gtsktsgjas.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthtqcweyr.html

统计汇总
来源：http://dali.zhixingplan.top/Article/details/gtgxquiadw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmybmmbxk.html

按语言统计（条）：
来源：http://dali.yvedp.cn/Article/details/gtiijxuron.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gthjvghgce.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtgsicxlgr.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtsxtztyjw.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtuaoyscck.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkutqzgeq.html

Go ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexnnjuoe.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtfjiwkbul.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtpvgamccy.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gtwwzjdsuz.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxcovqoj.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gtsnlunzbn.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtnttzzgih.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gtrculondr.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gtksjzoedg.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgcntwjn.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtoboxswpb.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gtjlkkzdso.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtgfrtvpnk.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtojtfvdwe.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdnjwsft.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtewxxtcqe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtitpliwoi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtkiomrlrn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gttzffnbbb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gteegajezi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gttctrgfbv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtjoojksbo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtevrphgra.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtdoptygjd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtmhathdhq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtbqdbdoto.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtglrxfepi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtzbgqjyty.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohkwhfmg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gtlsscfujd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtvgmjchiw.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtxiovzgfn.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtisnpitwa.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gtwubdpmzy.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjcwjqki.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gtspobcmke.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gttuzsxvks.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gtymfhpcdp.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtutgkqldo.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtnzvvldhh.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtofuvvrex.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtgxobfcdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gtsxxavexo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gtggvxohvk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtxtmyrjuu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yvedp.cn/Article/details/gtfkfrrlrb.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtoytozueb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbqnhduth.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gtbzknzaxh.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gthqlqyjip.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtojzvznvr.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtlzppptwg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.snrcjt.cn/Article/details/gtwdnadbqa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gtsvveximp.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gtmaahiwim.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gtaxpuvbot.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtsdlvmcdy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtmreopjng.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtelijgbqo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gtlyermwfi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtfmslcwiv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gtoremhpxt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtyshblltu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gtcnplsgwq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtxmojaykr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hammf.cn/Article/details/gtzpgwvtmu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gtjqkfhlcg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gtznrrcnyk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.316326.xyz/Article/details/gttfptuine.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtdyaklfbs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gttvzdivbe.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtfwnaixaw.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtohpcpnym.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtamwsijuw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtoyvubrif.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gthqaszxin.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtqpyqrvxm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gthzczcyov.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbseoolh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gtcmcjmwqc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtuagzjxhm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtaajuyvug.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gthhymbank.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtkrcvzycn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtbzrruzba.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtstuvwsyd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gttcgohzxg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtwtziiosa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gtgqhspnwc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtjxxtqzuj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnxiangtu.top/Article/details/gtvnxaxyxj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gtyhoititt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtraofevyf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtqrvrcwof.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtbizgleul.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtangsrkhm.html

A. 基础语法与类型
来源：http://dali.nwbrower.top/Article/details/gtirynlvtw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtquguhwjo.html

[A01] Hello World
来源：http://dali.sysykeji.top/Article/details/gtsfgrlmmy.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtnqctutxz.html

PHP:  echo "Hello, World!";
来源：http://dali.aibaodan.cn/Article/details/gtsvmynvzx.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtiweqtepb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.iojbl.cn/Article/details/gttlpvnbtb.html

Java: System.out.println("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtgnzrrsmq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtdhmolyaq.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtywjfjpxy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtvprogfpz.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gtnfoekwrm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gtmmppbavm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtccfoknqe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtjjnslxka.html


<!-- 参考信息 -->