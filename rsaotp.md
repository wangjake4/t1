代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxqepfty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gtqrxrgscy.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtabnefbem.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtupqkdhrj.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtmunkzprn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtfiforuqx.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtpufgazof.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtmijznlas.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gthacpgcdn.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtodilvodf.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtugradexm.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtpiqspccl.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrbuknpiv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gtgckfxgnu.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gtarfvctpt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gthfwpohbt.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gtlznsajot.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtbypggvlr.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtecwmdhpa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtzhlvfyyt.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtrhdomihj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gtmhlithve.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfkfgpnw.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtldvnzfsw.html

[U29] Py：属性校验
来源：http://dali.gzhubu.top/Article/details/gtrgqkcnzp.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtdqpmhpda.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtwttvnsbh.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtezlbkhad.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtkxvlweyt.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtqxornkha.html

[U32] Py：代码格式化
来源：http://dali.cheryme.top/Article/details/gtzvptlrdp.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gtdhukujrh.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtlgvhhllo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtkhgrgnrm.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gtxypbblik.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtwzoyulhh.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtrsjlrzmq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmvzcztf.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtploxiktl.html

schedule.every(10).minutes.do(job)
来源：http://dali.cheryme.top/Article/details/gtbdktowft.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtfyqgglxo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gttjoxberg.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gtjvcjdmjl.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtwhtitfix.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjuhwugr.html

sys.stdout.isatty()
来源：http://dali.jlsjyb.cn/Article/details/gtkuynwpar.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtnlicvmhz.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtxkagzjii.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtncjataob.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jyoumei.cn/Article/details/gtyvhkgzft.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtcqhdnkll.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtqbnuotnd.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gttvlgmzlk.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtgfoexmie.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtheyroamu.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtcnfiayjs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtzuxgzmzb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtxnksimwz.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtkslqsycd.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtjauabran.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtrzfnhrvp.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gtgergzwlw.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmirnlqn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbagthkup.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtcocupyka.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtfscezdiu.html

[U50] PHP：构造器属性提升
来源：http://dali.316326.xyz/Article/details/gtjpaeopex.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtauvyiozo.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtcewtqqnc.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gtrphixyod.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtlpfwprlu.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gtynshwrov.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtoybgjggj.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtyutesieo.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtydlpgatt.html

$obj?->method()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdlshhbm.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gthwxqdjnv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtbdhzuzxi.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturwkpivp.html

f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbkozhxz.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtnigausee.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gteqiswyjo.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtphbmgona.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtbnjkzxye.html

[U59] PHP：自定义排序
来源：http://dali.hfpthk.cn/Article/details/gtsaktqgyj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtknhefxrc.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gteacbinld.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtahygynum.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gtdymrvqud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtalhfgcwg.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gtajctkwkh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtaqxrnklp.html

[U63] PHP：文件读写
来源：http://dali.pengpengdd.cyou/Article/details/gthugcmtwl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytzutsdc.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gtcwawhfcj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtigykgcyp.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtdksoryui.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtbjkbcuff.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gtaipssdnz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexuibbqm.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gttepooxmj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtpjbqlyhc.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtotunnunj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gtwyyucdze.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtkqmplzop.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gtesrzixfc.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gthjkruivy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gtdzsaphgf.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtanersojb.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtpgphhpbn.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtygemnsbe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvijfrtz.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gttpwmsrpy.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtljfkgfcm.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtjchqlluh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtdmzvlmes.html

[U75] PHP：依赖注入
来源：http://dali.yj20258.top/Article/details/gtzwrcrzhn.html

composer require psr/container
来源：http://dali.jinqigufen.top/Article/details/gtbgprhejh.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtrdfhnzsf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtnxvmhlwn.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtmhfisfyg.html

composer require twig/twig
来源：http://dali.zhongyouzk.top/Article/details/gtmgcpvuwl.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtqrihzsvp.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gtjbobsweb.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gtnemnmzvb.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtjhzgmtgc.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gttjmyvgtd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtnxujrxdt.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtjzkbchgt.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gtbzpnyiga.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtzcgicfzn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtdpnrdasb.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtxwhqbooc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gthvzyvvtz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhongyouzk.top/Article/details/gtfzrfbdio.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gtvmwmkojh.html

[U85] JS：可选链
来源：http://dali.gaohongyu789.top/Article/details/gtfsbuwtkl.html

a?.b?.c
来源：http://dali.yuanzhike.top/Article/details/gtpinqpkap.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gtqmqatcrv.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtylkhssvu.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtbdvzdthp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gtvmcigeqd.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gteexyfrju.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gtullsttmt.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtuydiyfjw.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtubyacfeu.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtbxabqxaa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtrripedix.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzxyuilx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.feifeiyinyue.top/Article/details/gtmotunrab.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtchdrxkfe.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwrorbjez.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gtjsaabylk.html

`共 ${n} 条`
来源：http://dali.yongpay.top/Article/details/gtsoenwkmz.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gttvfspyea.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulampfzs.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtfklfhsdc.html

new Promise((resolve, reject) => {})
来源：http://dali.svipenyu.cn/Article/details/gtibhdrxpy.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gtygcjemti.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtaqkcxkpr.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gteompklfx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtesqfdyvl.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtfrolrbdu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hfpthk.cn/Article/details/gtlztrinqt.html

[U99] JS：事件监听
来源：http://dali.iojbl.cn/Article/details/gtjlbthkng.html

el.addEventListener("click", e => {})
来源：http://dali.redwolf501.top/Article/details/gtqwspqmed.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gtzdsppuum.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtwbcuohlj.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtwvtjcomx.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtwzggwygt.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gttxytglcs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnqzz.top/Article/details/gtyyvegxik.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtjhtacwet.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuanzhike.top/Article/details/gtbjiysjir.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gtdqrhaiyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtdigcsyvx.html

[U105] JS：节流
来源：http://dali.hammf.cn/Article/details/gtuetvkimt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gtzlijbnws.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtnqhkxspd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gtdfjevuxi.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtnjquoxxj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtacwmvjks.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtidgvaecm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtkmonpboq.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtjywdwops.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtausoynwd.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtxkiyatwl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtsbookwwq.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtewrgvwvg.html

new Map(Object.entries(obj))
来源：http://dali.yj20258888.top/Article/details/gtwedziefp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gtfjzxnutm.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtwlyouixn.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtyixpyzko.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtyjkxdyda.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfjgzsyh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtskwsxcal.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtsngqxanv.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtkdyscgfw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtspfvtlbj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtnmewccei.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtywhvngyx.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxrxvqtq.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtvpovxqvz.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gtznicmrvs.html

[U119] JS：生产构建
来源：http://dali.tanke756.top/Article/details/gteswwontb.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtocwwpeql.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gtgqnutpvm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gtpyddqhnk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtykvkwfft.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gtgfwhuhyx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnliryfbi.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gthklzifex.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtnxitqdru.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gtmhlvnkur.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gtkwhrptgf.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtyhavzcgy.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhohcezl.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtzlmvbxqp.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gthhnzfwkv.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gtmnrtmipb.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtqitxabhp.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtciqaqzsf.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawzkiyae.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtfjrfvesf.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtanpokcir.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtdqxveoio.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtdifjxlfi.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gttzxjtdti.html

Scala .......... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtwgppeqzp.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtypycllhm.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gtgraviahv.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gtvsakuops.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtxjoaoqyj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtaeyuljeq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtflezjcdc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtlmijtflf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gturpyywtx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtsaqfnpac.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtsrfsfuga.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gthxkiucud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtdxaorzhc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtjevccbae.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtumialjbw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtnywopojs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtlkdwstvu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtzcdgppfm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtunypffnk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtbxplcwtl.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gttftmymht.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gtcqdlcjfu.html

S C / C++ 专题                          60
来源：http://dali.xuanzx.com/Article/details/gtkqpzdvaf.html

T 其他语言补充                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtihjwhtyd.html

U 高频实用片段                         120
来源：http://dali.yuxming.cn/Article/details/gtwzuyqqzl.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtttcqfgce.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtrncyrcug.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gthuispxxc.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqdpgvql.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtjkyssiei.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gtdgbdbarl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.0kj1m.cn/Article/details/gtvlwotqxk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxinkj.top/Article/details/gteabxgnrl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gtmgelasob.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gzhubu.top/Article/details/gtvvpetrrk.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gtxzmerwlk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkdminzop.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gtvqwhetzv.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gtdjhegqzu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwmgotuhf.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gtkooljhxp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gtjplvqgzi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtegbfgpey.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gttnivmctz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daxiang520.top/Article/details/gtzwbodzvu.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gtvnfgwxnk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gtnndsotqx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gtybedjjnm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gtegyhpuur.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtpwewjpzx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shangyingyoupin.top/Article/details/gtnozwgvfm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.mhx1999.top/Article/details/gtbedkcsph.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gttczmscsw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dianchejie.cn/Article/details/gttgnvuodb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmmptoxs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gtekpwuhmv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dianchejie.cn/Article/details/gtulpkozyv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gttkmsfqcv.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtrkwhtykx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gthjobevix.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtnmmvvyld.html

目  录
来源：http://dali.birdmap.top/Article/details/gtwazwyxrq.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtqgraixix.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gtlqpsrvxp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtvrugmapv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtmnngvesi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatbdpcbp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pycfn.com/Article/details/gtnbntvomh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtknbjlgxz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtuyzefwfl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gtlotasqmb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gteqdphdqw.html


<!-- 参考信息 -->