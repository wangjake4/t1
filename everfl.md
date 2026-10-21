代发 wailian999

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gtwkffxuop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gtzhpfqcjx.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtvmuewqbs.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gthhrpyzox.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtxdhmmlij.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gtlmxlrqle.html

[U20] Py：缓存函数结果
来源：http://dali.bjfxy.top/Article/details/gtdmzvxjnx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtdhtbuflb.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtjsttsskn.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtjzqobgxp.html

[U22] Py：矩阵转置
来源：http://dali.yuxming.cn/Article/details/gtbiirrdvn.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtwtkmonxw.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtpravuovp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtugqipzwo.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtnxnqjnbc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtwozeethz.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtprlkzfcn.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gthfweyfyv.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtdawjkkmw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtabbmskrh.html

[U27] Py：异步 HTTP
来源：http://dali.xuanzx.com/Article/details/gtdveiyubg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtrhssvynl.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndtmbgqt.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gtefogbsjv.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gthrgyprao.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtlertggbp.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtndmiuhxl.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtwfbynsqp.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtkzcdvtmz.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtouywnktk.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gtfynlkynx.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gtgerzmsys.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gttdpviori.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gteiosjrfd.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtlafdpmbj.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtpzlgvmxl.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtwjcgdjdx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenzaomai.com/Article/details/gtatgphgus.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtkeyuesvx.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtibyhgkrv.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gtyfwpqpla.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gthspikxkv.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtfedsjcqw.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtvsrhgsln.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauozuxva.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtfvwlvpfh.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtnbhcoy.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtmixoplpf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.iojbl.cn/Article/details/gteglvugzm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtacndvlna.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gtgvtczbfh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gtotqbxhck.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtxrqxowfm.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gttushjyfu.html

[U44] PHP：开启严格类型
来源：http://dali.hammf.cn/Article/details/gtnqvumqbm.html

declare(strict_types=1);
来源：http://dali.ivvv.top/Article/details/gtauiqbvsg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtnywbceoz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtuuaktmhz.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gtaepqkvns.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtgbrsqgpc.html

[U47] PHP：联合类型
来源：http://dali.jianghu66.top/Article/details/gterhfzmqa.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtzsqrchtg.html

[U48] PHP：纯枚举
来源：http://dali.cucudq.cn/Article/details/gtoblyteio.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gtrwunywef.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtrgimkpbx.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtjyoywzlk.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gtyvhmqwyn.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtfsuhecix.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gtxrsibgbp.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gtufzciljw.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtbkjytimr.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtjkxfjkqh.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtvcpzuqio.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtqqdlfrnf.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtqanqzowf.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gtqonlqpkg.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtnamizryw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtajxcbved.html

[U56] PHP：命名参数
来源：http://dali.birdmap.top/Article/details/gtjlywzpty.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtxegktfos.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtfzvaykrw.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gtznajbygt.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtiehascte.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gthoiyeexf.html

[U59] PHP：自定义排序
来源：http://dali.chenlongwang.top/Article/details/gtthiqqoyc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtunprxfnd.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gtabaovcfw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gtzjwiyrig.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gtgyxrmnvg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtazjmzwir.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtdnhlybvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtyxwjbyil.html

[U63] PHP：文件读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwxdzxhd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gtclocxpao.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gtdahfpnuo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtejyqoxro.html

[U65] PHP：会话
来源：http://dali.hammf.cn/Article/details/gtouedcdme.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtdqmofxpa.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gtppxolmks.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gtakvrvfiw.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtoayapogy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtwgtsvndw.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gtsspdgzwu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxhffgri.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gtmaqbwhmj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gthtpyriuj.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtwsdhseqh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtazfbkkrd.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtiwkxlpls.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtdfuuuusd.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtoqmpzphz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gtvgipkuqu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zdqjudy.top/Article/details/gthhmwpxwt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gtggcwcmyv.html

[U74] PHP：读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtxzktpfoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtgcsungfy.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gthpstsjbm.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtdgteonpj.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtyznjstqv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gtivwiefct.html

[U77] PHP：模板渲染
来源：http://dali.jiagoushi.top/Article/details/gtnconqvdq.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtmzgoovpi.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtyvbtsalw.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gtsrfajenh.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtcfgkiuin.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gtjnfrbbjr.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtsnadnfrp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtzzqrbqel.html

[U81] JS：初始化项目
来源：http://dali.hfpthk.cn/Article/details/gtzpfuuvsr.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gthpontayi.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gtxzuffnco.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtccgqzkwm.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gtuwpwizoq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtwvvfxllt.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtamdftsqc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtbwewxsdf.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gtpniteizg.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtjiuqrnjo.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahpwnjfe.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gtrcsgrcjq.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtbxaojqmn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtilgcshgy.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gttnvpvdcb.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmoudxbr.html

[U89] JS：数组去重
来源：http://dali.ivvv.top/Article/details/gtqguwcyif.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxejxgpzq.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gtbxyuvbac.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtufdjagsi.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gtqzrbrsqw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtmgeapsht.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtzjihggep.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtdxhtvmph.html

[U93] JS：模板字符串
来源：http://dali.nwbrower.top/Article/details/gtptdaiemj.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gtpwemmbcf.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtpzyaleqm.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gthxsprrsm.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtdimsdjqk.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzbzqpvi.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtulkiyavp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtzhkbmbds.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtusuzytxs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtobknzcyr.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gthreenwle.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gthpgmckws.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gtmomzodub.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtmnjmwevj.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gtkocmekjt.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gtrizmolre.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gtpyfcyimc.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwoxymvh.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gteejbmock.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtriwqevlm.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtmfaauosj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtcmqqceqq.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gtfnhmzaqq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtxwykjohx.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtpwunvdoq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigufen.top/Article/details/gtdsdtlpxs.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gthamqyonk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtgdvxkssr.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gtovpjigxr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gtirklnaqa.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gtftgdysho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpufrgzo.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtdcjiqjbb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtjqkdkceg.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvchlgpo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gtdyrfjwdk.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtsmusbunz.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtjzmikwiz.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtfoyoznnx.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtznlhhyrz.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gtknwxlsmb.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtrdytyica.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtvkdemdtn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtrzlcutva.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gtifcwfmoy.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtbkfejaiy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtsitjsyjo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsubovpfk.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtstohhsve.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gttwsnxvai.html

[U118] JS：开发服务器
来源：http://dali.nanxuanxn.top/Article/details/gtjzwqddbi.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtmbswivos.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtldaecliw.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtiwzlefre.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gtxjonrkmo.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtdfaivbqq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvshfrdjl.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtlfldzoao.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtscfsqqox.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gtndbjgxun.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtcbwjpyqr.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtkifawpyo.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtegxqzszp.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtazvyxnoh.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtkdesvqci.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtfhxiglea.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtorqnkkwd.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtxmfgzgpu.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gtqsonkxaz.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gtpbneodxp.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gtplhotmkb.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfszvkbov.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gtgigugqim.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzvymwfv.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gtwuglbvqs.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtlciwwipt.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gtcdchoryk.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtvastexum.html

合计 ........... 2106 条
来源：http://dali.cqqwz.cn/Article/details/gtznwmqymq.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gtfokcsngi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtwqvautdu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtdsfhcsjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtzuggzrzz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtxrnsyvxx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuanzhike.top/Article/details/gtpfgaknhu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtvswwmwzz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtnrhtemlx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtxxsqovwi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtxbobqgep.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gthqoowdfg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtxfimsjfn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtqlbqoqoz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtcdpgpipw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtzrwyrcux.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sufxvd.cn/Article/details/gtybdnxswm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gteuhmgavr.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gtiwjecypp.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gtkcmfykuk.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gteaykcwna.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gtaxycbben.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtkhtzcpjk.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtdapoivla.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtqkvuqtxs.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtxnhobjax.html

使用提醒
来源：http://dali.zdqjudy.top/Article/details/gtixlexoxc.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtgrkyqpxu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtsvteayur.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtylwtavly.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangdashe.top/Article/details/gtytikcfes.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gtvzzhllfo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtiedqfkpx.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gtnssdknub.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlrrtgurc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gtvdshfrpv.html

Common Programming Examples Cheat Book
来源：http://dali.havefunace.top/Article/details/gtjkakmyjz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdvtvpsuf.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtkqputgjg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ppjwa.cn/Article/details/gtqqzhpwkq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gtbuebtter.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtyfabxtlv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtdwdwutds.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gtwrbylxph.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gtlfezspwn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gthozrwffd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtbjhpgnsx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dashuyun.cn/Article/details/gtlkxofgua.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gtotjwwptg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtgmehoskq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigufen.top/Article/details/gtvqytymjo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.birdmap.top/Article/details/gtqtodgchs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gtgtkpfjzd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtikvrfhnv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtungknznb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gtfnjwughh.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gtujzasial.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gtulcmjmnt.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtghkadyre.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gtcoysgncx.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtjixbuprl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtfhlsmiow.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtcoisivln.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gthqvpolaw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gtuxenekmb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtmjhnjdgd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtiltwyknn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgoccebli.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtrswgrcts.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtzkkniyvt.html


<!-- 参考信息 -->