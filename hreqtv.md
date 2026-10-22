代发 wailian999

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtjezrtrpp.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtmxslgzyo.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtgqcewqjb.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtkkfefhss.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtripukxub.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtboitwbrf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtjfqktill.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtabtvknhj.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtiobwnbzh.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtyqgiottb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtlrlhmxpe.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtfbxbqajb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtdqaswbgv.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtlnpgqjjg.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gtolilzszn.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtledzzitc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtwrmymdxn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkznccuwa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gttgpsfsqm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnmimyvxs.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtcczwirqo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtyckofozb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gttdlmdwix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtferdmtmi.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtflkqdeub.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gtdvrbtcny.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gthsgtemvk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtswcfvfvx.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtpfrzsmgg.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtfuwranfj.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtpsqsxjai.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtizkztffb.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gtweibltui.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtdvffucbb.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtekttiabr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtjjrpbmgv.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtdovsiuzh.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtaxsljbqx.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtyexnuree.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtmlanxkdk.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtulhxmdyw.html

(x * 2 for x in arr)
来源：http://dali.yanxiufei.cn/Article/details/gtzcumxumw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtiztdezef.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtphnijhdo.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtjvarteky.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtqthshxqs.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkwtcjei.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedkqnjbr.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtcsyzstxu.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtkguofbru.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gtsjlwsnnq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gttaxqppbq.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtzlszeaol.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtrnkragug.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gtxfkpcfjb.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtzcfgywin.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtdbarxauq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtmcrymqmv.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gtnpdizmer.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtizkvvqwc.html

[U21] Py：自定义上下文管理器
来源：http://dali.ivvv.top/Article/details/gtgxhfahgh.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtwqrzizkb.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gtfbqezfbc.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtlcjzbaxv.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtxwdmmtwh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gteucdbzuc.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtorjwsock.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtbjxpikor.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtelrokcgk.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtezwxucby.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtlvnzmzzr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtnrowjfpv.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtsggupjcn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gtjfsgrecs.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtepipvias.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gtmvbnybeu.html

[U29] Py：属性校验
来源：http://dali.zhiwuduotai.top/Article/details/gtfkplrqtx.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtzaftdvbh.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtjfmflvvi.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gtyuwcfdfu.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtowpnqtxo.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtnvvglxho.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpifwsucj.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtosxkjwaw.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gtvuvfzxqd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtajhjjesl.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gtbupcblkx.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gttetnbtbq.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gtxjswxthr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtwgtgskvt.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtdcfeeuvl.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtgbayjhno.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtnhxqtrqq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gtlyppwjcr.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtydbkveas.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtgvdtpsal.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtyxbnnjut.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtspxqitfx.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtbudehjgp.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtntbmbcts.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtkycplsqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtzwmbpjdd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtoqmzjhvm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sufxvd.cn/Article/details/gtaivrzbyn.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gtfhtitszo.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtgdvqetut.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gtjfgrbycr.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gttjmzcath.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gtsxaezqob.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtxjvenjrw.html

[U46] PHP：可空类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsbdfqik.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtczhfbtjz.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtccxulwxu.html

int|string $id
来源：http://dali.ppjwa.cn/Article/details/gtcfylrumj.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtiixhnobn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gtvzlcrvcz.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtmuvopsty.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtkcaiswiu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gtcldcigjx.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gtdpwkclpn.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtjbsbwwex.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gtkmhjsrgw.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtixwwetnd.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtdlhpsvad.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtwwgucldw.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gtggfdcega.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtwigdblkl.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtpdnfnafc.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gtmejycvvq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gtopgujvat.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtvqjtnmma.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtjgayucdf.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtrnlsindr.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtajttxxpd.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtdxxzrlhk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtjadiwgsj.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtufffshlv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtbvkbscbv.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gtkhhnoihb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gttwoyukzy.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gturpyhmsg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtholopdtm.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gtzahongoh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gtchppoijd.html

[U63] PHP：文件读写
来源：http://dali.yangfankeji.com/Article/details/gtqfakxrhx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtcqsawaej.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtzvxmdoxe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gtcbuiuymz.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnjwqlxc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtifardkco.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtclsragzx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gtiikdoeci.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljprwpjd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwshtdovc.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtivkgtkrr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gthmbzcvii.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtjmsbzfxq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxarcbirf.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gtrkrhiaxl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtushgvkdt.html

[U71] PHP：抛出异常
来源：http://dali.hammf.cn/Article/details/gtbevwtvrs.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtjbgpuzuf.html

[U72] PHP：写错误日志
来源：http://dali.havefunace.top/Article/details/gtnewzlogd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fengsongda.top/Article/details/gtmpkaftvv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zdqjudy.top/Article/details/gtvrwvpkfx.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtholbbaps.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtyoosyugm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sweek.top/Article/details/gtxhxbxbza.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtulnzabzi.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtafdnfdem.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtlrvrysmk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtlcjmoylz.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtbxpmgllj.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gtyeipxfoh.html

[U78] PHP：单元测试
来源：http://dali.zycfv.cn/Article/details/gtkxxzibme.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtwfyagaip.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmzkkydd.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgufenzy.top/Article/details/gtdjgmlolh.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gtsnkjgzgd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gtfvworfev.html

[U81] JS：初始化项目
来源：http://dali.ivvv.top/Article/details/gttkjonwtm.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gtzseoucau.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gtyookfgph.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gtjrpewcjp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gthancmeuc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtxiruafdp.html

[U84] JS：CommonJS 写法
来源：http://dali.smart0.xyz/Article/details/gtncmxwvgs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtldwdvxsi.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gtxdumyyzm.html

a?.b?.c
来源：http://dali.zhengqikj.top/Article/details/gtdipabnlg.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtnmqvjgky.html

a ?? b
来源：http://dali.ppjwa.cn/Article/details/gtiompxnrn.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtoopjoxcj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gogol.net.cn/Article/details/gthsgnkich.html

[U88] JS：对象展开合并
来源：http://dali.iojbl.cn/Article/details/gtoctcvbsj.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtflcayllm.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtzjrnfpzr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtxrcmfrmz.html

[U90] JS：数字数组排序
来源：http://dali.hywenlv.cn/Article/details/gtcrhyrrlh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtzsthgbeq.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptvcrcuy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cqqwz.cn/Article/details/gtyaxembll.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtybnzkdxu.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtslumkust.html

[U93] JS：模板字符串
来源：http://dali.quarkkingdee.top/Article/details/gtlnwsistt.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtblwzgpsc.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtxwtgkzfo.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtlrhbjhwk.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gtqzlgwlay.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gtvxcabamc.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtisjbumou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtwncrjteb.html

[U97] JS：并发请求
来源：http://dali.hongshengwenyu.top/Article/details/gtuwvgovoa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtioeeasgc.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenzaomai.com/Article/details/gtpfetkjlj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtsmumkfza.html

[U99] JS：事件监听
来源：http://dali.zhiwuduotai.top/Article/details/gtzoeavtez.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtxfnxpmej.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gtvlsyvltq.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gtyaglnody.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gtdtrelihd.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gtwmblxhee.html

[U102] JS：本地存储
来源：http://dali.tianlin.xyz/Article/details/gtxjdnmldn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtjbclmfyj.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gtjgcmgxxs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gtkolluskq.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtxreektcg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtoffgvdwg.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtptauhvfw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gthgozdhdw.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtgvmlkilx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtexqthkxv.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtelwiudjv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtwienhbnr.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gtemkagasp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gthomviuyb.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtwhqwayhh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtgfcyoeip.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtgeehmpql.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gtezhumtcg.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gthzggixys.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtyqufxlvq.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtnwqcwacb.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtpevitabz.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtylvgtmun.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtzevcqozl.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gtkgqoavzq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtayugznlj.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtfaibjqyu.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gthsfbhcqm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gtxpkucfmx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtgarmfprq.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gthlwupruo.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gthdhdipcm.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gtsxqpkcwr.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtevpeqbwr.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gteoysrmeb.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtpfinpdel.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gtcavbeoll.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtyrswssfq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtehjokxkz.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gtldqwpqwq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfitvjycf.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gtfxumbmnq.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gtwqpybsmk.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtqcfxjqmm.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtrebrobso.html

TypeScript ..... 212
来源：http://dali.sweek.top/Article/details/gtkdkenaxv.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gteaubgdvw.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtxbpkuqkl.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gthnmvatsl.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtiiwsfixo.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gtjkennabk.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtcjsmnlcl.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtpezsroqe.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gtcnzqetvy.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtbpsqmuzy.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtuqmlrkrb.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtgzxetavi.html

Perl ........... 10
来源：http://dali.iojbl.cn/Article/details/gtrgooyalr.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtvrtwnmlc.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtttzdtfia.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtgiymfoga.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtcricnacb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtanqdrqrk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtmswjwozr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtomkuwtwh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gthytmeict.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxhtuskw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtjvpbfshg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtjgjoveah.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtpkvxxdml.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtxsxdlbdu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtnibfsmba.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtyeffubee.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gttemajbid.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtqwykcntr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gttpmougkq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gtqzchqyvt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtbgaskjtn.html


<!-- 参考信息 -->