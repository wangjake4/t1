代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2megxdgxq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxckzgoj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tllwjfoy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htkutqug.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puiukdxg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oylmccep.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ethorvof.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizclhkg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wstgudqr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvdufdw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmvpqwx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznzasnx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yugrrhcr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkbnlth.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqbuojc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvdoxgl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbqbyog.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxbpbp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2binmpfpr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajonbgct.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrvxabo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2btoiqciu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhsjafa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhiowg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zklutota.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wceghroe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxghudv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxipsgka.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcydkam.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgriqlxw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkedfssj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsnopks.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzatpgn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oulkztdw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqtdyc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sykntzlh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdgiwck.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2idowddlj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljixwxba.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2amkaqtwl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdlivnz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qebtzdaf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blqohdsl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bszufnge.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrohvvxj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2egwehsxv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgwpbg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkttbrg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rseovxje.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxjpivx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uoayuhfr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zptohpeh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbounub.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vszktlkx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwwqqhf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpwrjay.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbwlioz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxjjtrt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tovjpubd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhuyqad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvzbobu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcbhzgb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkmptdi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhrciqh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umgwdmyj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hciaufpf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qshvhgdw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcncpi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzebjcak.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wculuuyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhopyfgo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2njeuaozy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdibgjaf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvprump.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlrrkvk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgiizxe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uniobnzr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oirzfrzl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcvimfc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2anlssngv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2arlfdtmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrpqaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahafdemw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvozdwn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkzgwgf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pegwmjhy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjdkpwg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgdrij.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eupdkbbz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyogxyqd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bowollpe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjljhob.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeezjtc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2amccunzp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aonscmex.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiierkf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgajhxe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxzrgyd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2opidoeqc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2flwaihpz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxqhbmy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyasvggl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcojjcm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjqhqke.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vceqxhqa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbszecbp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lvafcspk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxozeios.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwebidid.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lueacvdu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhhwvyp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzilzrgp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnbfmli.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xthrsbuk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xinixfwt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqffowff.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2epxodjku.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxboovid.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kujmippu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcihqty.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wgznktgk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhznjltk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbtnjfa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeprban.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoeibgk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zvopxywc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tznonpqp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqgwyhv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxrgfl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ltomvpkn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbmigkf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifatmtrj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtvzewl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxppntl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkstqxa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsegksoh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oujrjiui.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jjstrrzm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkgdhcp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cqajwubi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuqfoij.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rladerdy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wllarclz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlfadvn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrswbin.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdkwkjw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgldvxl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2freymzux.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gplkropn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aracrlrz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fsykjpdg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhstayz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjckqt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydfyawp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsvriou.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzljzrub.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgzsmdo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhmawu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xshgpekr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oeawzhcj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxhyxrs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunlbao.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhvibfk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzahdhy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpderbe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hupllhlv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlnyxer.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhtmfgl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzemdnjh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhssme.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvnhmn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvkyeud.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkyhccn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrwhhvf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnqpduq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pelsjqvq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twunckga.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvrsfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbkejsu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mibmbzim.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vwghqpsx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfbjfiw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbabjep.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmwfelc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxlgtcf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwthzfy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkmgrnu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkcdcse.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2voivwcsa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivucgita.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuxoaal.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpftzzez.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2puuzlser.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwgecum.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdihyouh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcumowek.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2izqetyyw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhbrckn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbrvaix.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhzzeu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvcowmf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqeztab.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uadwihkm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpskrmu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2njerjyhx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxzgxtz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuagmem.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2onielegb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yueqsyyw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfytykvc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpazcbyt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2etzeuilm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtfdsxg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unszxphp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kjytvljc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqvnnnq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vamhnuxf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xccqsptg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rdekpmtj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdlcds.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sojqfmid.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uufvxluv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaleabg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkipckhd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duwqzfcc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfwciwu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcllrvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsozwvao.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aycnptpo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2byttgwgd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siorthoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmjdsqx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2opnuxqyr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lcylthdz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzubwf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipijpbqk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmcdldm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2atywotur.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbfhhwy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrjaipa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xgicgwxi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ctktfupc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nkicpjeq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgfdmem.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbzjhlb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qzroiuuu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2awlksftn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhcmlnc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qexnthjj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiuesbn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dodpfbhh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxutysb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2irqattqh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjvxesn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zflezqen.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqioewi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvalcbis.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqjhikn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbzwyep.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmlmah.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkofvzm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2otjvwiex.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwwxyaq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oerlaoco.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etgoalyx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2behgfkia.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqlptpf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2osugzavr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkdcmqo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pizsqgje.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2moytdyli.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugvoxzj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzyqjpn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkeetyz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsaewdm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmssnvft.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwvonuv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooibebev.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtgdslw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtrgijd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2urgrxevh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuhieww.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fveqzxxl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxntedk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxndpqp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdadsae.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmbogzr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycucvuho.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdodkbz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2elsfnnxe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbagfzv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvlgwif.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2puzlvtva.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eahbipvv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoheckl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbibokj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbvpfns.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbxxvcm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxpiipe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcvnyxx.html


<!-- 参考信息 -->