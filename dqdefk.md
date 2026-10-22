代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtvvmffhco.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gthcmetgzl.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtelwlagyx.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtzbilhasx.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtxmlwgsnv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfqnfadqy.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxnklcos.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtljkuztki.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtgsrecazx.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtnrtbufwv.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtkrpoxfbl.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtulydgzrp.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtpywbejhq.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtgauihhnj.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtdgbksoym.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtcocqvezj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulshelso.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtswwftvci.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwfievmv.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtlfpoiwnl.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawikybkl.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtoynxqrbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtcyfklprf.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtuglkyevb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtjisrprwo.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtamljjzib.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtmsmnztpg.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtvkjlglko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtuyzqebhz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqeyhpuaq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtvmbgkyaq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzjfedgcy.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gtyyuqqtdw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gtembaxqtu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxjgcmty.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gttildcyex.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtxkfujflb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtvijuwdpt.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtjtwgkkwa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gtblvzchmf.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtiowtqomj.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gthxjnmame.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtvspykmkw.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtjzfmamsb.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtqappndmw.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtzijyhmng.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gtvrslixwv.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzyuoaah.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtpiivxwaq.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtjzvowivg.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtsuijblyz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtetmwgigl.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtxyamvuau.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gthkremtbn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtxzspteli.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahpunidi.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtfckfnavo.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrlslumh.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gtjxrhjuxk.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtoqundsyp.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtwlodtrkl.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtvwzenplx.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcupnistd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtjiieeeid.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtgrnngdfp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gtljsxdazx.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtiklestmp.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtuaddlzxd.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtbdpsfvcm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxsyrkmqd.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtzlcumngp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtyeqjoqbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gtidtekome.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gtirvedtys.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gtoazrvkfe.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gtwnicbqfc.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtqnbsqynz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtuoxxrpui.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtxmakenjw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtpiimkzag.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gtyakhbufb.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtspgbsjwb.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gtqzugtaqf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtahdpjcec.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gtbbpcvqvz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gtzoedwmfy.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtrkmxvips.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtdrakqoyl.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtcdwkfmos.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtbhkretoq.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gttnqceqcx.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gttakfwhsw.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtnatwopih.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtdharwxfr.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtckgelczc.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtmdaojosd.html

[U33] Py：打包发布
来源：http://dali.cqqwz.cn/Article/details/gtrgrkdpxu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gtttuwyzjk.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtscpeddar.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtmxtvobrg.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gtvcwmkpmt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gterfyiuka.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gthxevxqiq.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gteyionocb.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gtdskvyonk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gtfdmzmdsk.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtvsfhcvyn.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkspowmp.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gthagicpoo.html

sys.stdout.isatty()
来源：http://dali.havefunace.top/Article/details/gtkepsjtgp.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtzowbuikq.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtyvgnnxdf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gttfgxeuin.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gtkufrlvbm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gtsnrbxugv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtacmjxcot.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtccmrtoqy.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gtauxmhikd.html

[U44] PHP：开启严格类型
来源：http://dali.cheryme.top/Article/details/gtulwdibhv.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gtmagtdskf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gtvrelyiys.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtunwjfjqn.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbshhxvv.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtxyygecwl.html

[U47] PHP：联合类型
来源：http://dali.ppjwa.cn/Article/details/gttfqxxzes.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtyoxhykuw.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtkueykirx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gtivzqamun.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gtyrvxathj.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtmpdezziz.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtjnajgxjy.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gtauvfouwx.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtztuazdyc.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtcgyskcrc.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmszosip.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtifaadinr.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gtnzurahiy.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtgmdkzqvq.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtkjmrfbwj.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gtdwigxyze.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gtxfxqxkqk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtbjuhslwc.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gtykivyiks.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtzmcykvaj.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtbigohuda.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtzjhiewnc.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtbdwlgvaw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtbltdcxbi.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtajqycuyd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtsulqualu.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnwakzim.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gtumzmrxur.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gtoqcunvik.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmqqwjeuq.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtbgfqejpm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gtrcptzgip.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gtygzojrmq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fengsongda.top/Article/details/gtcahosbpy.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtnrnivguf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gtherpxzsr.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gtmugmmrbt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtzultphuy.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtkymmeyma.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtuzfffykn.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtmgzwyqja.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gtpinfgusm.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gtsttobiuj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gtrudougyd.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gthceqtjmd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gthpoqfwei.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtkgnziebo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zycfv.cn/Article/details/gtymdleujs.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtwbhldksk.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtehamkuxt.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtvcvdvkwm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtjmqfjwqn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtylpyaqbl.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtasekmwcb.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtgdbsfxmv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfznwwvti.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtpqgpezoe.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtblwaxzvy.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtprroociy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtbawinvxr.html

[U77] PHP：模板渲染
来源：http://dali.hongshengwenyu.top/Article/details/gtarxxzkpa.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtifhvkwtq.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gtiaqflrjv.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtrdvzobre.html

[U79] PHP：静态分析
来源：http://dali.hywenlv.cn/Article/details/gtgihigvzc.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtzhjnotgd.html

[U80] PHP：代码规范修复
来源：http://dali.redwolf501.top/Article/details/gtyrnsifrd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gtpfkcaoio.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtznuowuro.html

npm init -y;  npm i express
来源：http://dali.shangyingyoupin.top/Article/details/gtslhuotcc.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gtqttdxedl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnrjmyyy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtsxdpfwed.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtvbkelhjr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gtmnoqyulh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shangyingyoupin.top/Article/details/gtmwlsvees.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtleqkkrtd.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtselzzipy.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtarylxjfo.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtzsyysxza.html

[U87] JS：解构默认值
来源：http://dali.yuxming.cn/Article/details/gtxqjnhcii.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhvrtyty.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gtywwdebhe.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gthoqohqek.html

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gtgrgrgfcs.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtrgripqwm.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gtejvfjfnp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtoeubcqsv.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gtkgafwdom.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gteltqxxmf.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtrexnwmxd.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxfumcjjo.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gtuxydpbgt.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gturyrwsys.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gtkcsddkoq.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gtpaoqhulq.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtvhmeunbs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtrcptycbr.html

[U96] JS：async/await 与异常
来源：http://dali.fzhhl.top/Article/details/gthosopxqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gttdqjuwho.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gtqvpzjntq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtpfewxkpn.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gtwnghmguh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gteshuyzeo.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gtzubaduqb.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gttxmutbkq.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gthlhkdldt.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtwcaqpzuc.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtcilnaxdo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gtrnzrifdk.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwvqocc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gtwmqvkmgx.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtcdjlwaps.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gtyhgnewwj.html

[U104] JS：防抖
来源：http://dali.yonumen.top/Article/details/gtfypeatwc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gthvwoiwnh.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtkppzxree.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gtpzjdhsak.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gteaaydjmc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuanzx.com/Article/details/gtvfdbidtr.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtkcwohwii.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtsftxpanx.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gtuwziclll.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuqgliae.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtveagmppf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtybqqrvdh.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtodoxlifk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gtzqlercvs.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gttydfdigo.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gtjswchbya.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtnajzdtvg.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtlxturlpz.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gteculqerp.html

s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtmvamfxci.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtfkbfvkur.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtphgxxjps.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtmoqdzivr.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtjoepilwi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhixingplan.top/Article/details/gttevhddcn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gtehztxefq.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaiqcrpr.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtvcqavcrh.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtfhaqywlx.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtqgybdqkd.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gtlsxyfvhu.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gthshjbjmn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtinngnoso.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gtlwzvmaai.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvhurnmtv.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gtfyxotnwk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtaazamxth.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtledmwrrg.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gtyrgkrmym.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gttplflmxw.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbbihhax.html

TypeScript ..... 212
来源：http://dali.meibo888.top/Article/details/gtqxyvoqoh.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtfcpumsjc.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtsvypvlne.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtfczfceib.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtosyleqfg.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtpwjloduf.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtzpevrhpd.html

SQL ............ 90
来源：http://dali.feifeiyinyue.top/Article/details/gtvvllwreq.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gtekfjutgs.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtacjmhppl.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtddvvhhdw.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxvhygse.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtkewnwnbi.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gthemfwdij.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtxdmasmiz.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtvlscbjuk.html

按章节统计：
来源：http://dali.yuxming.cn/Article/details/gtfuesfjoq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gteltsgxzj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtvfwmnynk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtdeqyazis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtgasldekg.html


<!-- 参考信息 -->