代发 wailian999

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtysnbepyz.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtbfuzgami.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtqobqqhon.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqargepf.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtsmjenbek.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtxivkovcj.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtontxspvt.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtlnleviaj.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gttjpmhued.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gtzaqgdpdc.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtosvgoaaa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtayyjwxqe.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshjwzsrq.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gtopqagvqd.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtjhrjvacf.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gtaybrohxn.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtjuzultud.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtwpqcdzic.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtpbbtjstq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtrnkmlzqt.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtxfsverbh.html

csv.DictReader(f)
来源：http://dali.xinyue.icu/Article/details/gtlbzdzdkv.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gtwwafkrhm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtkfimskig.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiuwmwbf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gtaijttmjm.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gtwvhppkuq.html

UserId = int
来源：http://dali.shuidangran.top/Article/details/gtofnjwxkg.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtibghzluj.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtzofhfxsn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtsphgcrxh.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtytxfzagl.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtmytqxnmn.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtzkvtrlig.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gtgdftibhz.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtkgvqydgf.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtywollphd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtxfhsrbzm.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtkvqcchso.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gttgarjrpd.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtpllfskll.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.316326.xyz/Article/details/gtuibcdrwi.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtywupnyup.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehszcppb.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtiqiqncbm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtzegncasp.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirxxgyrt.html

Path(__file__).resolve().parent
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhrbpgq.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtwtxxfqll.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gtybxgrcir.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtyvtevscl.html

print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtbnmzkkry.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtulokyjyi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtaqniszkj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtqqmmnkrj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtgezgopvu.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtiacrejjx.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtrkrmrmqc.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtamnmzfdo.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtjmmwpbtu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpbloisj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtcaqpspwr.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtsghrohtf.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtjqylrlwr.html

[U47] PHP：联合类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwnwchda.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gtabczlonj.html

[U48] PHP：纯枚举
来源：http://dali.bjfxy.top/Article/details/gtllzrqkak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.bjfxy.top/Article/details/gtrdqqioxu.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtylygmyhi.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtuppwhwqa.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gtntyunoec.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbegdekdq.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gtajukwvoq.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtofwdudnj.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtdcikdhgz.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtujchyhki.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtxdbfqcil.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtkhypnivp.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gtpszzeozx.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtdhetdrja.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gtaxbtvwih.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gtrppkxivz.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gtphpicpgk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmahntkru.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtxsmghnim.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gtouzdijmv.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gtocobueib.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtabjqxocp.html

[U59] PHP：自定义排序
来源：http://dali.daria6918.cn/Article/details/gtcggxgwsy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtyypamlxt.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gttywakxcz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cheryme.top/Article/details/gtbijmtfjf.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gtpworemsc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtcdbfgpoz.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gtcekurxtr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gtgwmxyeom.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtiyblxkay.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtmwlesfek.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtgalfycmu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtnwylkupw.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtvbjdxidb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtotmsvudh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gtetymavmf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gteymcyvoa.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtlyftyecm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gtweudctma.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtkjsdivmj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gtnzjtvwwg.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gtdlcmvfhf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tian-w.cn/Article/details/gtyociiieh.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtghuniwrk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gtolbttwkr.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtqjwdthtj.html

throw new RuntimeException("失败", 500);
来源：http://dali.sysykeji.top/Article/details/gtrmdqacnv.html

[U72] PHP：写错误日志
来源：http://dali.fengsongda.top/Article/details/gtdnupuxhl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtsiofwupm.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gtbuidcvql.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gttvdhjeiq.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtkrmavbaw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gthyegghij.html

[U75] PHP：依赖注入
来源：http://dali.chenzaomai.com/Article/details/gtabavqugf.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtlqyhfkct.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtwojnsxmj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ivvv.top/Article/details/gtfbiqntlx.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtxpivboxz.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtilwpwrwn.html

[U78] PHP：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtvmqqgkvb.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtkkhkzjom.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gtxdinfppc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtalfsbjjf.html

[U80] PHP：代码规范修复
来源：http://dali.ppjwa.cn/Article/details/gtklqdjqfc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gtviyqdjnv.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gttqcelbik.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtkoftoncu.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangtech.top/Article/details/gtziaommsg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgfzy.top/Article/details/gtlodyzxwi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gtafmggnuj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtmgvekkal.html

[U84] JS：CommonJS 写法
来源：http://dali.cheryme.top/Article/details/gtdvlozwws.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sxryk.cn/Article/details/gtcgcecxqk.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gtgdhslabw.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtvjcikewv.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gtaoevrsws.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gtixvyqtps.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gtffjjssvp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gttoxzfxdr.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtnipoyqpp.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtymfrgnsk.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtqfcxghgo.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtbdvmlckh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtnidexpqf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtzvsbtsat.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtpxwltofa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gturqvlkkp.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtzuzpqdlq.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmyemynyl.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtbnxnnzae.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gtbzqxdexl.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtpylgwcvq.html

const double = x => x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtxasrwltz.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtuaqgnlqt.html

new Promise((resolve, reject) => {})
来源：http://dali.svipenyu.cn/Article/details/gtcwcfmwmd.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtmyqoakeh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtcvgqeexb.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtoouzudub.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtuvjwxvri.html

[U98] JS：fetch 带 JSON
来源：http://dali.hammf.cn/Article/details/gthaphjjaa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gtygqxolfl.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtqjftulbn.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gthochsmww.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gtcgjkygid.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcszozcmm.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtiojlvqbz.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gteresjfzh.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtzzmknhkr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtbarbspro.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtuhuomqhd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtjpzifjyg.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskhzydtv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtutulxxfr.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gtzythyami.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhongyouzk.top/Article/details/gtpyiostyq.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtcykgryqs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjghwses.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtdfpsqvlo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtxpmsqpjn.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtzsntamef.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gtlvybztlq.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gtohfvnhnd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtwaoaqvdr.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gtefqbpmxa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlabsgsth.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gtcqasvxfa.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gtexefwege.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtmwajfgrg.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtgpuczgwh.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gthhzevsiu.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtrlppzvdf.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtsioayvxg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtsdafnyks.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtpppsorhx.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtulbotfzb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtthufulca.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtrysisfpy.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gtgtzcinpi.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gtvjajhzmz.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtfhbwexdv.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gthorvhlia.html

[U119] JS：生产构建
来源：http://dali.shangyingyoupin.top/Article/details/gtqbrvyeih.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gtgtdzmfdi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtitbwflyw.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gthkbpjojq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtajecfagw.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtwaoipvao.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuyoqcbdw.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtgjdgmwgr.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtneydinbu.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gtzneytays.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtruocjikj.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtiubffzcg.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtbzcykega.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtrdxrsvop.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtolomlmax.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtejkfrlgp.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gtnzzjvygg.html

C++ ............ 30
来源：http://dali.xziqi.cn/Article/details/gtvxpmnxzf.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gtifgqsfdb.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gtyrpcdsbt.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gtpgkhbzjj.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtxqmefwey.html

Lua ............ 10
来源：http://dali.feifeiyinyue.top/Article/details/gttxxwsqrt.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtpzbusxhw.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtrvyikdkf.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtzqwsozfs.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gtqloehmgl.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtnsqkkubv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtezvuoxsk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtsogovunv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtqixneknd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gttcrrvbok.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtfithkhvi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gttuwkqgfv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjrqttyi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtvqvwwjbz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtexwdhmtq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gthallmuso.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtzktkvwjf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtbcuaujcv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtenmntrjo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtffygcmrm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gtgtapurqz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gttssyjjly.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtwznvnufa.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gttiqlqdyf.html

S C / C++ 专题                          60
来源：http://dali.aibaodan.cn/Article/details/gtxtymgzzb.html

T 其他语言补充                          60
来源：http://dali.gotoacloud.top/Article/details/gthpemylri.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtcvlyokvg.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtwvvykakq.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtolmmwkdd.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtdutwykfw.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtfoeguzcd.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtwpqvnigu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtfzktnbxl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtjjnisawj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gtivycskpk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shangyingyoupin.top/Article/details/gtnrlvzgcg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtoecbrhqv.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtmhzycdjl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfmmvcsti.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gtallgkmfi.html

Common Programming Examples Cheat Book
来源：http://dali.yanxiufei.cn/Article/details/gtcmaxdire.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwzwhlfkb.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gtlwiwmnyu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gtuvskltcz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gtjbhaaybr.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtkmowyldl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtzlrdpekn.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gtjcylbqdg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dashuyun.cn/Article/details/gtamlxhneo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gthscnjpho.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258888.top/Article/details/gtxdzbisoh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xuetiantiany.cn/Article/details/gtiulugeqm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gtdwuwoegg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdlxaqps.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gtzddhjwxm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtplkwvkko.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gtffdiynkp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gtmhtanglj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gtosyhludt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gtwatusfuo.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gtylfclyzp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gtrpoeezux.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtmctbnpim.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gtrzlescnp.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtjhnxyoki.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gtkaibzlpj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtlplkjcdw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtbzqdnjax.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtkxjgkgpt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtnrxmsjmw.html


<!-- 参考信息 -->