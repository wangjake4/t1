代发 wailian999

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2qyuiipyw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dzdowran.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2xvdouwfu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gt2dwojqbgg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2ljqnahqv.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gt2tsqycnxe.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2kcwbdubz.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gt2qtflplxo.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2jcjuhxdj.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2tpnsvkgn.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaokhjpx.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2ehkwqixo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2eezpymtz.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2ldjfgzml.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gt2wbjdymmj.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gt2xkhqizme.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2djljemfv.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2chvfndzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yufcythl.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gt2vgxcmstf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gt2sedidllb.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2qbmdoooj.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2eafggpbu.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gt2mfhrexyp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gt2lznugyze.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lkhbpvih.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2plsjdzwt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ierhepwh.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zadttarf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2bywssgtm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oirngmoo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buxxrlzv.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gt2ezdqrxnm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gt2lmshcouh.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2elosicvy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gt2bywbebjc.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gt2enesyhak.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbkegqkl.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gt2vrefwkoi.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gt2pcdopovu.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gt2msltoubb.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gt2osspevby.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gt2ziveyshb.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gt2txpygeir.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khvttlul.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gt2wvstbaaz.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebxdjvij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2rgyrikax.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2ellsmaug.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2qrqeerno.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2hykxsvli.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaarsyxj.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gt2szppxdsc.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gt2ojryszwm.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gt2kbakvptf.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2vfjysgfq.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gt2ykmipjai.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gt2zgqwkzxh.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gt2gtttgyoo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gt2uxdymhvk.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gt2opwgqwsk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gt2wxujffda.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gt2mfsvmtkk.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2gdgozvqv.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gt2aqqsagdw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gt2ncmalpjl.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gt2gcfwvljd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gt2vwhkkpda.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gt2gdzdapac.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gt2etmripxh.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gt2mmyprmar.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2uytiswbz.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gt2jkhgtjiy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gt2jzshpncc.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gt2fzuwlyde.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2yhumeqrm.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2celpplce.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gt2yfdugxpr.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gt2hetqkcrs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gt2yeyziofn.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gt2azknzoeg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigfzy.top/Article/details/gt2lwevqsgy.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2vnhebycr.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2zzyyaqwk.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gt2ncvvotlq.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gt2alftwwrf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bmenolfp.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2wqhqrotn.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hytcwdon.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gt2pvddgxhp.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gt2ytxeqyda.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gt2ojwtrdgb.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gt2ylxzcerh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gt2gnbxiiwm.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2kemvnbfo.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gt2ritivijo.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gt2gmmzitrv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gt2ercqlgxx.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2abdgmkoz.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gt2xqijpnqy.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gt2mcawnkgb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gt2hesjixhz.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gt2jkdquvgw.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gt2dqiqcalt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2bbptktzi.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lalclhto.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2mzkbgylz.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2uonbfarq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gt2vjoobnfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gt2svixlaca.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oddssudh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gt2dufbfxpu.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gt2ushqilzq.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gt2sacpmyrk.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gt2wrxcocea.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gt2ayjkytzv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ozjdjpwo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2rwgwjhyr.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gt2nblwewyd.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gt2qwggqanr.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gt2nmucvhro.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gt2nluvmttg.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gt2clhdxliq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gt2flkeetwk.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gt2apzwoqqi.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfdeaaua.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gt2vzuawtks.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eukuushp.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gt2gyjzewvv.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdpqbnhu.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2txracwdn.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2tdgfjpgl.html

[U53] PHP：空合并运算符
来源：http://dali.hfpthk.cn/Article/details/gt2uaaqnvcd.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gt2usslfnda.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2fuvqxrky.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wncgiheh.html

[U55] PHP：match 表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2ghvmvrzc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gt2emetubfy.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gt2vwsqscup.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ddqrqwzy.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2vocyvwqo.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gt2nngyriyu.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gt2zehsecrk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gt2gjvuqjna.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gt2fgvknmvo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2dqvfrxur.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gt2dnebyazj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gt2qqscofru.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gt2ylwrfjqr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2xujfxwdg.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2cyboxbde.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gt2ppnpcpzq.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gt2dpxtjirv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gt2prwcuzru.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gt2qzoclena.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gt2ocglbmzs.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gt2vhkbjgxo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcvhxtk.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gt2vrlpdlqv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pycfn.com/Article/details/gt2emzvragp.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gt2penbgvlf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gt2klselenc.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2iegpelxp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.birdmap.top/Article/details/gt2slcldvof.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gt2neziinsv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gt2renlkkye.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gt2syxoktxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxywxrwz.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2kyxxgvcm.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azlmojgr.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gt2lxlupfvm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gt2nyfxfcbo.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwgglojv.html

parse_ini_file("config.ini", true)
来源：http://dali.iojbl.cn/Article/details/gt2foyxrrkl.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2hvvxnrhq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gt2arbfqjaz.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gt2xzjkktyy.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gt2ifavzkyb.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gt2drlghmxn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gt2ftlietgf.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gt2typtinjo.html

composer require twig/twig
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgebdxvb.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gt2jkkghnex.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gt2nrwvaaok.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gt2xulxqrsv.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gt2xepradgi.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigufen.top/Article/details/gt2ootyebin.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gt2afexvzso.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gt2mnbnvfva.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdjhtifs.html

[U82] JS：package.json 脚本
来源：http://dali.fzhhl.top/Article/details/gt2banzzoqa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigfzy.top/Article/details/gt2hfacdihh.html

[U83] JS：ES Module 导入导出
来源：http://dali.nwbrower.top/Article/details/gt2xapxvjom.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2ygpkglct.html

[U84] JS：CommonJS 写法
来源：http://dali.yongpay.top/Article/details/gt2hllznrlu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pycfn.com/Article/details/gt2xpsxoisg.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gt2mkqakxug.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gt2estikoxp.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifgeluog.html

a ?? b
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgssatqh.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gt2pzzhtplp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dashuyun.cn/Article/details/gt2rpnjnxnb.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gt2zmfagnjy.html

{ ...a, ...b }
来源：http://dali.quarkkingdee.top/Article/details/gt2hwwrfjve.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqmbcuub.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2nbqyyraz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cbukvoxb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2fkzbuvbb.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gt2meadsmsr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gt2dnsjvogu.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcznjqtj.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2rmokoryf.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gt2hukbwlae.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gt2drwnouod.html

[U94] JS：箭头函数
来源：http://dali.yj20258.top/Article/details/gt2romrzzmc.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2hrqnjwwm.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gt2xfjqxrce.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxlzswil.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gt2walomwmh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqvndtao.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gt2vcgvcgni.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2esnbnade.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2mnprzftn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.iojbl.cn/Article/details/gt2xxhtjgof.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gt2kviknxox.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gt2jjifwcsu.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gt2dtrfovpi.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzadqzdy.html

[U101] JS：classList 操作
来源：http://dali.fengsongda.top/Article/details/gt2hovmhycn.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gt2shnojwkh.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gt2pwvadvvl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gt2kvogafka.html

[U103] JS：定时器
来源：http://dali.shangyingyoupin.top/Article/details/gt2duduelqg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2enltgkbs.html

[U104] JS：防抖
来源：http://dali.ehwqpu.com/Article/details/gt2vxwmzmxx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2znjdlzek.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gt2rziyfefn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icwsnied.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2nmycwjsa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gt2ilsbjdbd.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2bvvsybzd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2bzvcrzwk.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gt2bovfpotp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gt2abfyxicp.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gt2altexczj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2rhepblwo.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gt2sehjqlne.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2eklpcqgn.html

[U111] JS：对象转 Map
来源：http://dali.sxryk.cn/Article/details/gt2xhobtytf.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gt2moqcixqy.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gt2hduxigub.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2srjwatde.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gt2byawjtvk.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufhpwaus.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2pigmqmzb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2urxuwoat.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2bpmaurzz.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2hkgcfxvh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2rbnmlaqp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2bexcdoee.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2xgdsmpyf.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrcelczz.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gt2putknbas.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljhdojkk.html

[U119] JS：生产构建
来源：http://dali.sufxvd.cn/Article/details/gt2ygkxtfdu.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2sxzrahek.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ybcxt.top/Article/details/gt2qttqfsau.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2matgijxq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2imqhhazj.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdpjtkjl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2uacebfqw.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gt2rylouigt.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gt2qztdrzix.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gt2wlszrjay.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gt2opecqqtb.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2pyfwkvrd.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2wbmnfnqa.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwvqnkge.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gt2rcwfkwlk.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gt2abscyopk.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gt2zbprfiak.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gt2wdienqsp.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gt2rhvprrie.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gt2xnyjhsgg.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctasndqz.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2qgqbhcyw.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2oqnbryxn.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gt2xxfnocwa.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gt2zwkppupn.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtgzqzkn.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gt2dbbsimus.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gt2yjxklgpr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2pfdgdohu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxpzhnrl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2loyeotwo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gt2pdwkbket.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2hjbipraw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2czssjcqd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dunihuoa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gt2blobxshs.html


<!-- 参考信息 -->