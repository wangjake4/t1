代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ktegtqrx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2obenvojt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iupaqcoa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiqkjhb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwkroae.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrpkyc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoahmnu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzebou.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyeyrfz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnagatj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpigwyqp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmbkfgb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvllnqg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcyvms.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owpeogvw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvulegzv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmlqtuf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkajhio.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2escpqxze.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwujsrb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pbozvgfa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmfyuip.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxgqwvi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfderhch.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdjtpkr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfwuarc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtflvmm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrzvjar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2innohkdv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2norznlfe.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfficwwv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxddgq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vontelyp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqohvip.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeiicwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvzwcf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqwsep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdlhpvm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kopnugdm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2izoivmse.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnzvfou.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwlrut.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtzvjjs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2myksyuhd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdfcebp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wweciucl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdrguud.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opskkchl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqsomil.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwotauh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrivzqnd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qjopildm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvqncci.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfyqqdj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvognuh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbpevgi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirtoutn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhqhor.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2olpsmlee.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcuexrw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfssebkl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hniiecbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkbmrat.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdwibwx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebglfctw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iojcpabd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2apipczxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuhepet.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmixapl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzywsc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhogwbj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtiwvq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtwhkmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcyyvyl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtqqzqj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aelfkjpn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2stieurbf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fndillcz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvzknqr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwvqkvu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvfcckp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcljqpl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrckbjta.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2upxbaczy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiloktc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzwwrtd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqpfjjz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyjuvby.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpzmuwa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kusqxwhw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plnvmzgn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfwdjfz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmtqolz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdadurqa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2isresqnp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafnmtjq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2exhynbzj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuqhszl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2feirneol.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaiqqky.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mckurqep.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kurxaqjj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fiofklpm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaeehwr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ojylfrvn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifujbct.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxgxtkr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrgoqoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2isgprckw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhckwyl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyrqhws.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2myaggwjh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzivlzj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2usekxdsh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyqobdm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jareidhk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2itduejjp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbzumno.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mriylxvo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrphermp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qnncdpby.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2llzmesfo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxcydhp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkldgkq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tasdcepf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwumxfa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2edapnidf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2usglplcw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxeacfo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwyhgvi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsonfvy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2podphymc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nneotftu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2prgbgisw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoknhiq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ownncfmt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgqbxkb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixkqda.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbadusb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqucam.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kohznfsl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oupdhrce.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsjugfp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmzxlg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2olvbruxs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gglweeii.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2swxwarnt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2danbnyov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qrezcrdq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nezocrae.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fixzioru.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkoqmuy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzpiujg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qluxymtj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vphtmjyb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2todxqrwc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pljytngb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knhcrrst.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kplefozr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yblyrldm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuspxlfs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ljebwyxp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oasycnky.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kulioqcx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hfigvgud.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2auxohkrt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2duqbcgzb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glaejonk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wizamqcc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfgseqf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpftqag.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkcmhde.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmzbtv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntovuhrb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdizlesf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqihdhlx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umzewuqw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdridvk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iybaoviz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvoqnet.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrngpmq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suawkojq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2svkgnhhw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeiujhb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmagfgrt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tunbqfsu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2diwzkvgx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmefefzc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eacaiaxq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zridmten.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnrtssr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeboiyjg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcnwkxj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzrpqry.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phbcqemw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxmqesy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pljlbmom.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avncexkd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lyychsyk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzgtzd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzglnyl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2idhegiaz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjlpkbc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlugcdh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ezonsnxm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urasdnkg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxcxpvn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwoczas.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lofyclsz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uswwirhp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uizuvegi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lifklfkp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlzvgn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoppufi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfmssvw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2emmppely.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kczwcezk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vijavefw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rintkgyt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyogfkx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdeyxca.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpncpeo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfitdxx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jojokuim.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiothzr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeutnyp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vllbacxz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fuietbku.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfniojxg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sznvolse.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2robrosxk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpmzfha.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jawbpfrj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqseddjw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzqvec.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yevdlwsp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2efqyucyb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2myomxggo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lsifxemx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmwsgni.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnugnkh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvczzjve.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iauhqhvu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2unephgnn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2murivdvb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2juhobeui.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbzguxu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsymivi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uovnzgxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmzddso.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvgfhnz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqrecvj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frnhaayf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ozspmjqc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwzxesb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiyrikf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aypjoifm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzfjkrq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2enlnyrqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbexeks.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vligenjp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjquwec.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uciyqlgt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zssxejbb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzmthrs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyvnrxl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylueesbp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ievzorbg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dwriwrfx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfbwprr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2afbtqrab.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuhcxdj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhszcjr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ienkyccx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrcckfv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwepevwn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2glltzrcm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebavzomc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kynvmugl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2csfeoqwi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uskkfiky.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrxgcrd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wligjbbm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbtypth.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzqgnnb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcbbwsm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfhyfl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzkcwer.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrhalit.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcsbdli.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaalgdq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrnxlcg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2conoltwp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyvgkqp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmasebz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usihakaf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2orobyusk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2efpcfnbr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfinmeo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kinqtzup.html


<!-- 参考信息 -->