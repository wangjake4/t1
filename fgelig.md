代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2favspyaw.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2geiaqeow.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufvyincb.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gt2obhggjrw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2etcaxedd.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2ubhyfril.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2oqfluwow.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gt2erkyimgk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gt2amhmhwer.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2cpgfoeeb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2tjnxwpjs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjdxlcfr.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gt2jzeizeoz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gt2zhfbcgda.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gt2mqtbenvl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2axewarni.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gt2ymqxpgcs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gt2zqcebfmv.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gt2ozqesxiq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gt2tcsydeix.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2pppdmpnb.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2bwmyaggr.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrnitcxz.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2kiflfxdy.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2trjvjvdi.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gt2vfbyxmmk.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gt2zqkfbltq.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gt2nocehrwg.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gt2ntqpvvkv.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfsarebl.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2oacyktjr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2rpneueey.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2xqrrqcwl.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2tcwzlhhb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2rksocmcg.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2dohzsxuz.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gt2qymzuelp.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gt2jumudhhe.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onipaydg.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2gjtjtbfy.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2nyrmlfyy.html

t = time.perf_counter()
来源：http://dali.zhixingplan.top/Article/details/gt2yhspnowr.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2wgjaphda.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2ijlfqksz.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gt2ryekxhdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gt2tbxpcnwv.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gt2muixygzn.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gt2egwwcryc.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gt2nhatxxej.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gt2nzcwojch.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gt2ytphlmty.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2ltcygipd.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2yfrpkfyp.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gt2ljwtvmjk.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gt2yurklsiu.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uebncdgl.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gt2mmhzidbc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkptzebz.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gt2vadmioqw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2eurihjbp.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gt2buatogti.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gt2nyudjddn.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gt2sychoyyv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gt2wnievyyj.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gt2ohnufwsm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gt2ipsgkcbq.html

[U28] Py：类型别名
来源：http://dali.ivvv.top/Article/details/gt2cmynnjgu.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gt2etosnkbt.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2tpapvrxc.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2fpmgsqtu.html

[U30] Py：数据类
来源：http://dali.hfpthk.cn/Article/details/gt2vgluthsp.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gt2wiutymfi.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gt2mxzgbzkd.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gt2emqrxtyc.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2syrrndte.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gt2senbghdm.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gt2esnqgnpn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gt2bqjmxnrd.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gt2nsrqtzex.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gt2qthcowjk.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gt2ynlyogqm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gt2ltpnhomf.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gt2wmsdbaqm.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gt2qgpljjic.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gt2limqhjcu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gt2sopdqoya.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gt2cmumscje.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gt2mpimasua.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gt2lcpcygya.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gt2ybqonvwx.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjbvwtkn.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2ropfsqfx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tian-w.cn/Article/details/gt2bnhqwlfl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gt2oywvcvcd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.316326.xyz/Article/details/gt2velxpwmt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gt2khbisadd.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2mviefivp.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2pbeswfqz.html

[U44] PHP：开启严格类型
来源：http://dali.cheryme.top/Article/details/gt2mzbvstue.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2huufmvkx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gt2coxwkgff.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjwqycat.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gt2yjamganl.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gt2hiyxaqyc.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gt2dhkyacye.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gt2knsnpjep.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gt2gdnwvjsj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bxjeozcc.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gt2dnkcbcjp.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gt2nclnhepe.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gt2qnxjwjfn.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rlnatvvx.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbtpwmfm.html

[$a, $b] = $arr;
来源：http://dali.yj20258.top/Article/details/gt2dwhjrtcr.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qruybytg.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2sahslxfq.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gt2kezlrtrh.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gt2pfzxqsvm.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gt2giuqxxwh.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gt2tibifnln.html

[U55] PHP：match 表达式
来源：http://dali.yonumen.top/Article/details/gt2npepiznt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2aggmzsqu.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gt2eyxfeuij.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2sexbmpxs.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuiuacnc.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gt2xynhkwzg.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gt2xvpkfszg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gt2kgqlmyex.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gt2wtvcgvww.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2idfgzfic.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gt2gifljvdy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2emzmcopr.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqcoqbax.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2sfzzptux.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gt2pndkwlmo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gt2ewonfnpp.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwkopodu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gt2mtmvnkqe.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gt2ijslbfmg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gt2sklnsuzy.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhmsatvc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2lptxblso.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gt2pofwtmtf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2wktaapvh.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gt2bxdvccht.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gt2zxpbqddx.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2nulwnwlf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gt2oxqvkuma.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsppsujw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gt2tyrcrcwv.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gt2inchphng.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gt2ktjjslsv.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxmhpiqj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhoulong.xyz/Article/details/gt2gvilvwow.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gt2tdbuyukc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gt2giwvaius.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gt2fjxdcisn.html

parse_ini_file("config.ini", true)
来源：http://dali.cdnleiting.top/Article/details/gt2pzmnljov.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2ybzhqjch.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gt2lboktfov.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gt2dpldcisf.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gt2whffaesu.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gt2murcafzu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gt2xorwwmjo.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gt2vwxobhex.html

composer require twig/twig
来源：http://dali.yj202588.top/Article/details/gt2mbgnwhdg.html

[U78] PHP：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxfwmejj.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gt2exagutkf.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gt2wvnbltqx.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gt2xkbbtodg.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvvevzvw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xinyue.icu/Article/details/gt2eoklqywz.html

[U81] JS：初始化项目
来源：http://dali.chenzaomai.com/Article/details/gt2vpqhcpwz.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gt2vainepxk.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gt2uclmdcnr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gt2lonxnwnv.html

[U83] JS：ES Module 导入导出
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbpjnaay.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2joqzdnbg.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gt2mbtqzwle.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guowangkeji.top/Article/details/gt2ljrwxgje.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gt2qhryfkms.html

a?.b?.c
来源：http://dali.cdnleiting.top/Article/details/gt2nlvmijia.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gt2wwpvcqvt.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gt2tjwtomia.html

[U87] JS：解构默认值
来源：http://dali.tian-w.cn/Article/details/gt2mawixdlu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gt2fdvotzkh.html

[U88] JS：对象展开合并
来源：http://dali.316326.xyz/Article/details/gt2ldcunovm.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gt2khyqgucb.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gt2xzkkdxrl.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2mjyffunm.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gt2zjmsxfmz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2fgebixzv.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gt2wqidrsjf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gt2jyvooabb.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gt2tigqkdxq.html

structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2kpsipluz.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gt2orpaiwrc.html

`共 ${n} 条`
来源：http://dali.xinyue.icu/Article/details/gt2prnsmdee.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2jgepnuol.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gt2yabjjwxn.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gt2uzfzohkt.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gt2pztjqnhz.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gt2myplscww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2ztmnqaiw.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gt2utnlukhl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rumqbcrt.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2lkacjiut.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gt2vezoolrk.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gt2awvillik.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gt2oaoujuuw.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gt2phlfwssb.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gt2ulydcrmn.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2evjksqcr.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gt2ibhzxiaf.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gt2btlvrfjf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gt2zbfwqzro.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gt2vzmcddcw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gt2wqtmwudc.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2oojschzq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2pmksfrxe.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gt2tahjfzuu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gt2smxqjxid.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2xwqdfnxi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2xjdvebav.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2ounkkhjf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2toffunux.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gt2bsrnkowu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gt2vnlxzjdv.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gt2axyxaphf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2yjhqutos.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gt2latkfnhf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gt2dswxhcwc.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gt2hmmgmjub.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gt2bbftzatv.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gt2pxucuzmo.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2ovbenhon.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gt2ybpgluxj.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcifdxep.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gt2obkojqkc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izuorpuu.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2xqmmvchm.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2yozkmfpp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggemepev.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2czepyiuk.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gt2wrovnixd.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gt2suadivoo.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxqylicg.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gt2hrtuajjy.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2fxhotlkt.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2pgaqlebc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsuizwaf.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gt2qnghlubo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2pyjfijga.html

统计汇总
来源：http://dali.xuanzx.com/Article/details/gt2ebqeweti.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fucldmgl.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gt2yyozxmek.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gt2ncpadkst.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gt2adhlyibe.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gt2cnvrxmhl.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gt2chkccagi.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gt2jbbrfcfb.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gt2ygllblfn.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gt2jxspaklv.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gt2wdqukkzm.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2emwopldd.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fquzfjxd.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gptvkyxw.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2rvrsfhdy.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gt2queurzlb.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gt2gsygdslu.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gt2qxorsafj.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gt2vgeotpir.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2szndvwgu.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2xaylaopp.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gt2ltvjwbpo.html

按章节统计：
来源：http://dali.shzxlz.cn/Article/details/gt2idoaizne.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gt2ehqmknwj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2ipdfparj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2kbqjwpgu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2zdjydrjl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2agwyvone.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mntblped.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2megghppu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2mubxmqsu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2dnwiqeaf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqnwpqsk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2bzqnyzsj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2tdrdplca.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2wwadswre.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gt2bddlggpz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gt2onogweme.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2cjyudfzn.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gt2etahedhy.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gt2ukhopyyf.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gt2yovpdnwp.html

T 其他语言补充                          60
来源：http://dali.redwolf501.top/Article/details/gt2gxdsjggl.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gt2pydiccfx.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2thhjhyzj.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gt2cprkzcwt.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2mocppuzq.html


<!-- 参考信息 -->