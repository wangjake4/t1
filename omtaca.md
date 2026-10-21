代发 wailian999

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtzkpgfjwr.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gtdpzzsyll.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtlndmjsnc.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtqfzdqxht.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gthhilxaxq.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gtpggnztmh.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gtbyoqppku.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtoyquaoxk.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtkmkxbwbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtpthuxjzy.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtqrrrgjbh.html

chardet.detect(raw)
来源：http://dali.fengsongda.top/Article/details/gtewsktqhl.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gtljtqhgro.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtkjfkbjig.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtedapnmfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtxpfwnzbb.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gthgqaeccb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gtjqufbzzh.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gtvfscawga.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtttbffkpp.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gtteglfoeh.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gtexcaqhnj.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gttfflyoph.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtahtopyhe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gtjsazldvy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gtzgfkmdqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtdcoaysck.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtgnqdzqml.html

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gthueulzgd.html

namespace App\Http;
来源：http://dali.jyoumei.cn/Article/details/gtbofnsdkh.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtwrohqxlo.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtbuxgcyye.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtoqolnqbp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtqtaigekf.html

[U46] PHP：可空类型
来源：http://dali.yongpay.top/Article/details/gtlzffastm.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gtobrifmeg.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnavfcah.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtswiceznb.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtlxoyjyyj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gtwvzmflry.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtfqmlbdrc.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiiesxcf.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gtptpyyitx.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gtuopikubm.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gtaazilqlh.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gtkvvlbwsk.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwbmxtya.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtomtrbius.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gtvtmncgrh.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gtwzovyctc.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gtuocuhmnt.html

$obj?->method()
来源：http://dali.ybcxt.top/Article/details/gtclpybklp.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtndlkiama.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtwoygnmas.html

[U56] PHP：命名参数
来源：http://dali.snrcjt.cn/Article/details/gtqatgllth.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtikklmwby.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsntzwye.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtcunipefu.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfuxpjhn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gthshnvvol.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtdeszrpcd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtdduadqcw.html

[U60] PHP：JSON 编解码
来源：http://dali.vqdsnc.cn/Article/details/gtrwpqqrcd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.birdmap.top/Article/details/gtsypfrjbt.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtuwgimnie.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtfvymaxmi.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gtjdslxuwm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtmgsbkxqz.html

[U63] PHP：文件读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcsiqrrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gtbnwjeqcb.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtvqeyiavc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gthnvseabw.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtwqcyibaq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtrbgkrhst.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsfwthwy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtvctbufmj.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gtgvlehayt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jianghu66.top/Article/details/gtoqoxxwxz.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtptmovler.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtqhsqihbn.html

[U69] PHP：PDO 预处理
来源：http://dali.0kj1m.cn/Article/details/gtfjevolna.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtioybfzoh.html

[U70] PHP：PDO 事务
来源：http://dali.ehwqpu.com/Article/details/gtguxanbvj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gtgvxcclrt.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuikewuxv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gtdvkahobc.html

[U72] PHP：写错误日志
来源：http://dali.guowangkeji.top/Article/details/gttxnpypip.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gtnikfiauw.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gtrczeyujf.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtdfzjhpwd.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtuxdtrwpg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gtfkgbuvpx.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gtsrdtqtpe.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gtasfrvdrx.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtbsxruutq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtjeplvnbg.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtaugaqlxv.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtvgonorvg.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtcbhssxph.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gtqldtbjlh.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtonvracao.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gttcznrndc.html

[U80] PHP：代码规范修复
来源：http://dali.zdqjudy.top/Article/details/gtlxyirloz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtcfgxrfid.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksffhrux.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtckoptmps.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gtuvbtzabo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtjrbkpcyb.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtdxisrpiy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gthgjbcszi.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gtmnchrifk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gtypaadhap.html

[U85] JS：可选链
来源：http://dali.svipenyu.cn/Article/details/gtijenmrvy.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtwkgekypw.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gtpmtgfmaz.html

a ?? b
来源：http://dali.daxiang520.top/Article/details/gtqsdnmlxu.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtixolzqvc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.havefunace.top/Article/details/gtzohttaxo.html

[U88] JS：对象展开合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoptvyfjc.html

{ ...a, ...b }
来源：http://dali.316326.xyz/Article/details/gtcvzfbrkc.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gttzvoloje.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtclkounoc.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gtflzptsxe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtpsipyhea.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gtxcgfzcdg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtiwpdumkt.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gtcfzbwdmu.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtcrfuzcpl.html

[U93] JS：模板字符串
来源：http://dali.cdnleiting.top/Article/details/gtzmheoudk.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gtvlotqkdw.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtetsyhucl.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gtszhwpzzy.html

[U95] JS：Promise 包装
来源：http://dali.zhongyouzk.top/Article/details/gthjhdyjtz.html

new Promise((resolve, reject) => {})
来源：http://dali.chenlongwang.top/Article/details/gtvfcyewkm.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtzfulvucm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtvhxlntvh.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gtytwhudxm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtahztngsp.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtjanidjmd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gtdocyqjpx.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gtirdtknuv.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gtcwwtobkx.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gtbypaajwk.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtvlxllskt.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtakxxoynx.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gtmepimbws.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gtufmtrqbz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhongyouzk.top/Article/details/gthybyfhni.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gtheyumyso.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gtxaxrctzv.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtmwjktggm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gthpblvosu.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtczrjlejq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gtwgerlgti.html

[U106] JS：日期格式化
来源：http://dali.shuidangran.top/Article/details/gtfebroszg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gtwtqpufoc.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtlnqetqzk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtroxyfhzl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtcgqujftt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gtounndjpl.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gteqesrwyy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtgtmriadg.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtideohnyp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtnmpadkiw.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtljigsitb.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtjrfeqsfp.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtshbtpyji.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtdbytoyye.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gtgvqrwmet.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtlzdnehuu.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtzukjxsop.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtpfzsabml.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtxsvusijc.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtbvaqimuf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtdemrtqew.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtwtrzqkvx.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtedczhwje.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gtfwzewndu.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtbyjrkmzs.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gtlexdbfar.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtavawtrlx.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gtacwkdvuc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gtaiyhclyp.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgpudcbz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtigwxlmbm.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gtpdepkvgc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxjmzsyx.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gteoxrxkjg.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtuwsxoxag.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtkbddpjug.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtujeudhjj.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gtlwcestju.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gthmkvlyfy.html

Go ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtxvxirkps.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gtblacbfab.html

C# ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojjdjahd.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtdbsrqody.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gtjuzhuffx.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gtagzpadsz.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtzkixxyat.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gtjfopnydj.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gthcrkdnoz.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtjbtkaomk.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gttchlylia.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gtgspzowfo.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtaedlrgau.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtcaubxvpi.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdchdaglr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtkmfmrmnt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtlvbmyhcl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtegwwokio.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtibucmjva.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gtebkkqnuw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtoccyzpvx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtlxxiqjow.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtcksyunim.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtvjvjysij.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtxbpspvks.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtxquqhnae.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtsahdjple.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gthajrymql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtvovvuvvx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtwybakaed.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaayxcob.html

Q SQL 专题                              90
来源：http://dali.daxiang520.top/Article/details/gtwqisaypj.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtakvbpkrz.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtcpkjiwuc.html

T 其他语言补充                          60
来源：http://dali.gaohongyu789.top/Article/details/gtbjbvdkfo.html

U 高频实用片段                         120
来源：http://dali.zhixingplan.top/Article/details/gtjduwlbvp.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtzsdriaua.html

合计                                  2106 条
来源：http://dali.jiagoushi.top/Article/details/gtbmxipzql.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtfvzafitn.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtaehkzyem.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gteugkbkas.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtgxewzfdk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gtatpmmsws.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtammtimng.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yanxiufei.cn/Article/details/gtowbypgat.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gtxtgwnbmf.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gtunhlvwhs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxfpiqbzu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jyoumei.cn/Article/details/gtixvhhxme.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gtwjkicyqh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpvrtlwfs.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gtcfiuohef.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gtuciisxqa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtncoxdzde.html

SQL · Bash · C · C++
来源：http://dali.tian-w.cn/Article/details/gtcajoxpsk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gtztkzbkgc.html

【使用说明】
来源：http://dali.vqdsnc.cn/Article/details/gtkjfdytlp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gtfalxncpm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gthsbvzcas.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gtfevkecke.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtsouyaojf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gtebfvgeoh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtotnlqgvp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gtdjurjbxw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtnamfdqqv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gtrcjlhhjx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gtejxyvfye.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gttiexeowp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sweek.top/Article/details/gtbasopuie.html

【文件统计】
来源：http://dali.dashuyun.cn/Article/details/gtglwsnjtb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gtvppehmim.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtxwqppnkv.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtjcndipkl.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtttgczulf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtikmzhizs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtthedjwmu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgebdtclh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtfweebsop.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tanke756.top/Article/details/gtnxsxsmlf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtmviifxkt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtdtdgjgbb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtarjbgfvk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtqtiovinh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrdqxemsx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtgknnnaas.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtvipuhrqf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqeihvrm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtjqdsuhum.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gtesotgsin.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtwwqlkrft.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dashuyun.cn/Article/details/gtehydzfdf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.iojbl.cn/Article/details/gtzarvdwuw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sufxvd.cn/Article/details/gtpfwywbjq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtwntreotd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtvxcolysx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdpeyfycv.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gtsuyxcuhq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlxrfakjy.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtgtqvmmxr.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtcxnmdbgr.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gtciapomvb.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxxfyygw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dashuyun.cn/Article/details/gtgnwijbdz.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtlovnphbo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gtayiezcna.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gtkmldefjr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gtobkldjxp.html


<!-- 参考信息 -->