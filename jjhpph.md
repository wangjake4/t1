代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtcmfxbwez.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtsskothrx.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtdclnbgfa.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtlgonutgj.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtangdgzxf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtswmozhjj.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtzstzsrzu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gtwookpxwx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtzwjwoyeg.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtllsvcvtp.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtxzukxpqa.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtsglgftaw.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtgjiqimwy.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gttplqxbwt.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gteovzfqzl.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtnmdmemfb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gthsblherg.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtfyzzpepd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtsoshjupe.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtybhjoumz.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtdscyynag.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtppgiptnn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtznlwinak.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gtazglfpqz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtrjazbwnn.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeladaic.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtyddtqvnn.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtzqogdmie.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtexdhmcjp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtiubfasdg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjyvysbr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvhpwlcok.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtxinfwsnb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtzthcjbqa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gthwfguidb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtdyoqfnol.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtmpqnfhzl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtwctulpyn.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gthlfazznt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gtrjflpfix.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gthaetqokh.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtxqypavrv.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtwnhxsras.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gthcumlltt.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtvzikxzjr.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gtaeovplgt.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gtgdmkoanj.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtjvkbybou.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtnyjxywwg.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gteuuhruwr.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtcwauflrr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gtbehaepav.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gthvtwbeve.html

(x * 2 for x in arr)
来源：http://dali.shuidangran.top/Article/details/gtkpfyexje.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.haohaochexian.top/Article/details/gtafxedigr.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gtlsrncepz.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtqctcnmub.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gtyxktglgl.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtivjpfchv.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtvzfxgfre.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtyjrvfxhv.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnthkiyri.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtvqbypmvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtupqhggmw.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gtflgpngdy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gtzurjgsbo.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gtnfhnkszj.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmijhlwp.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtjqhhiyxd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtlyseidrk.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gthhaccbrn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtzawkofeu.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gttcdbsmdi.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtcvlgzzhx.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtbyjtucoz.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtilrwayqp.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtgycogbjx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtrrckzhcx.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gtciqqlsiw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtehvlkfgh.html

[U25] Py：CSV 按字典读
来源：http://dali.nwbrower.top/Article/details/gtyxyechnz.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtiqmwvszg.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtscdvprys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtqabrwhkz.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtmbmopxfh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdirdtlee.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtyafjzwyf.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gtrfltwcok.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtocgzmtcm.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gtmyxekcwa.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtpetksiqo.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gtmavgvrnm.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gtgulfaqfh.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtsepjxatk.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gtpcbptbhs.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtixacephh.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtwtjaesev.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtnazxzrkv.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gttarlypvq.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gtmizdxnvg.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtggxnxcex.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gtgoigcgeb.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtwwjxyelx.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gtoztsjjsk.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtkiosjqwp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsocjhum.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtkhxkzcdj.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gtnzxppema.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoyvcrtn.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtzsdqzilc.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gtekzqseoi.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtvmlwerjf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomouiiac.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtfsilzwje.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gthcvkiblc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtzyvkjmlq.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gtzlmlqmxg.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gtjxjglpgq.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtovvlogjy.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtizdbsxpu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dianchejie.cn/Article/details/gtjuipqwbb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtugsqwddw.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtavvtbvql.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gtfiojwgii.html

[U47] PHP：联合类型
来源：http://dali.bjfxy.top/Article/details/gtsrfxvimx.html

int|string $id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohhunvra.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtuayefles.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gteozjwlql.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtonixfoyz.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgslriepr.html

[U50] PHP：构造器属性提升
来源：http://dali.dianchejie.cn/Article/details/gtfkwhwjee.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gtswbixwyt.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gtgjdnqmnb.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtnhjcpesk.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtxdcnnyzv.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gtyuqychno.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gtfcqhbtzv.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gtlddhlmaj.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gtwaxjjdpw.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gttjbtdbol.html

[U55] PHP：match 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtpdmfvjoz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtlrraifhb.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gtawoejmzi.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtnwnoscke.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtzgffbmfh.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtroovdiae.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtwtehbgof.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gteegresni.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtxgsfnove.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtalzgqyuo.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtjkyzfvcj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtqoguykom.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtzgiojmkx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtauzonhvc.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtqpphbmty.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwknwvpgl.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtvxootkfm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtbozolaoe.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gtwcvfrwwc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtgmwtxutt.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtwxgmzjix.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtgjfvfmng.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gtblqpdvil.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gtgckmcsol.html

[U67] PHP：处理文件上传
来源：http://dali.xziqi.cn/Article/details/gtbybeqhdz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigfzy.top/Article/details/gtumtsconm.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtsglfnnqh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtfvlrfkec.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtcxkbrzuw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gtadgsarnf.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtnzhuyprv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtzbbwuqec.html

[U71] PHP：抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcpoxnxv.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrspwmxux.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gttwbpnsmf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtqjkprvnw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtumkfhcer.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtbbmezdos.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gtbamxxxik.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtbsnsfhjf.html

[U75] PHP：依赖注入
来源：http://dali.fengsongda.top/Article/details/gtqzbcwqqw.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gthguwzxaf.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtqmqosudu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtybwvhtxo.html

[U77] PHP：模板渲染
来源：http://dali.c1oappe.top/Article/details/gtetrfbola.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gtdohdbfxs.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gtjcdtyepp.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gtlxfxtcxy.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtyqidqfsq.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkebpobu.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtnmoljhji.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gtjdadtsrs.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gtymunpypj.html

npm init -y;  npm i express
来源：http://dali.nanxinkj.top/Article/details/gtnsezyrjr.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gtcyxksejr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtnituankf.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtkenapymp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtquwgqsgv.html

[U84] JS：CommonJS 写法
来源：http://dali.wangdashe.top/Article/details/gtcremjgcy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ppjwa.cn/Article/details/gtokyvkgfj.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtmwagcdko.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtqkvfrtol.html

[U86] JS：空值合并
来源：http://dali.chenjidiqi.icu/Article/details/gtstjavhjr.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gttjoqiznk.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gtmfitdknk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gthtpjaesl.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtdykkcdbv.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtyhkiodpq.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtrkbdjjpz.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gttmzfcuzo.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gtphbdkqvz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtnukpqque.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtqtppqofv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gtzxqnkbsl.html

[U92] JS：深拷贝
来源：http://dali.yangfankeji.com/Article/details/gtmxvmmunp.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtkhprhnbg.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gtaojqfesu.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtisubmeuy.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtrqocmalu.html

const double = x => x * 2;
来源：http://dali.daxiang520.top/Article/details/gtpqpgivbq.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtyhnxgoit.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtcfkayrtl.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtefcixyxu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtjecxikpo.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtewvkkfsw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gttnmamegd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtltwyoulf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gtdkehsiev.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gtlcxivftn.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gtduclspos.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gtugobcyjn.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gtscsrcpkc.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtkylbkdsq.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtbvjaecqm.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtqyqqvabc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtkcrqiqcy.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gtsicpwjzm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gthlsdoarw.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtenojffhs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedoijtbf.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtmyfcjapn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtjanrykuc.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtllqrixwv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtolzgdxgk.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtrewskluo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfpznvkj.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtkvwtopab.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gtjfipouxe.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gtuppuwzrv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtzfwpabtb.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtcwpwjmxp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfufbmlvp.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtkirwecbl.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtbwepuxii.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtiluzbasj.html

"7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtuswwxgrs.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gtejkgshqo.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtplnqepmn.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtzvjhgpck.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtgtnudaow.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gtombqzxgk.html

crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtqbiycvwu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gtrahsqzyh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtagyhnbeo.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gtynbvmgel.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gtntgygznz.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtfzmqytet.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxjeyjdx.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtypmutmzu.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtndoersdg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gtexxijbmz.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtwynmbzdg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgpcfqahq.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gtodgurrxx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvwredmud.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluxmlbbp.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gtqvbjzeco.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gtvoivgdbi.html

JavaScript ..... 252
来源：http://dali.yonumen.top/Article/details/gtdrbzuvls.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gttxbczvyo.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtzfsdvcbf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gttomzzgil.html

Ruby ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfipcui.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtyjdtcrwz.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtoxmxmjnq.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrrbhwvx.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gtduvttlid.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gtwjrnlner.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtquwhwayv.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gttvgvipgb.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtusjlpklc.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtjuhrdxro.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtcmzsgdil.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtdjdxnypo.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gtlxewcuyg.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtexsbnujp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtisbjzzkf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtkssxbprp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtrgradhop.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtppifyfoq.html


<!-- 参考信息 -->