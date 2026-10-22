代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvlzgpu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttipcld.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2evdeycdi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwxrzad.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxtmjic.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnflebe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2azrtvnxx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwwdqkx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mwulvpxg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbysbqt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqffdwse.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnytobf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcvkqmu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuykmwmm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hssoddgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qerdgemr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urtcdsix.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmpxjps.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmummqi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwtrlz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pysekhox.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2unjvbkef.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaxfujo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvztjesb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyzvjbz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxschlf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfivrtzu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqalfubh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2coqkjgcf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lojrwbua.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqgwmqr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnukvmk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vivninbt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsyiecu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jledoldg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvwafep.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoxepml.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdljwimn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdavftxh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hntlrart.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrpnoop.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuogmwqo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oprajaxp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2augoanwa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztldvbue.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdevynre.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxvjxaq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdxkynh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxnccwr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgdyifg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmsgqtg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2npzbmncn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuszmox.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqssuju.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwugjdf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkxlfwu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrtpmv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgawnby.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2khhqcuaq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqiwohv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiggjhd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzftmmxl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdekrxe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2irfumeha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zapbfuvw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xfteddem.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckwtcqd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzjpoyu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuycidb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfdxko.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazeuklu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpihtiiy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2matoikkw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiwqipx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibtgxsl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcyriln.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxygzht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deeogzqx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnwylys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jelxrtcp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hybizckf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbkhogf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlathfd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gykhojuc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnujrat.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdhdyza.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnakabi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjzxvrk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhkusl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmfgrbm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnylrtr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2flhwkdom.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dutpvolm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2raxdrkca.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rouuiemz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuzkxqr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2slnibrpy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfzfcoq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxieya.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjeofep.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xhslqkvr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnozhx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xdajphmj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgpwqhm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkizwtbk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijdcdsk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qycozqhw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2igjroewn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyaqrco.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhxcvxe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2syzmigbx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zygxkqak.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgrazow.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxzmadl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ceozwfnc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoqkamp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlfwoiq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbitsago.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2talnzcas.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsccbaei.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2waaqvkpc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwozjld.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqojtwjw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxiarvy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glzjpqip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vczbrbju.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnexlrg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2byasvuhi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvolwgr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvnsdxh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pdadvcxx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrzmend.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdlgssr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zgicphzn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaoqfkz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2scocamyv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnjjolc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yifyywbe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uehjbdit.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcwvuhh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxdvyqq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgyepjl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dewmhsae.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnyvwx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2klwekgbu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2moeuteuw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkdcowa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgekwzx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvkyzam.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aurjmcqt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2laqblubh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzcarix.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsstyxp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuwbdey.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfulurk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzyibhz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuklqbh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwjfvqo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdcspdk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hynmqzjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkyrxba.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmmbhmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hegygrgb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkwfmaq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vabvejph.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hljiaehu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjkfmfx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxqcfzn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqtvig.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nodwlroi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvmwhiw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpxwocc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiaxalc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2akvxuhmk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nalavgrt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enrmdmsp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdmfyax.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uguqbddb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmibnez.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fujxgcia.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgfcxtf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyqfnqi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrzrcty.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjkemnj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uipeotvv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgoyxdm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzclimyk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2adxkjadj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrggcen.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhocccc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2guvduofi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlbpufe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjgpdpi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlhtgzj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kvofvdmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2novcitmv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwiiuul.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2obsboeid.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeokibg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitzdvq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zpksmhat.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2inqlcnmx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2etfcvcna.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdhlrpn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzngdwt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aboqobdl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfgluif.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjffwj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uorvcbyu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obrrgqcs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyvepte.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcrzotq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoblxdv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfakiibd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2onqsvihv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdzxzpp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kziuhawm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbdjrwy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdprngv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqtznus.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvjaqda.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvveskym.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nruipaaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyurbur.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrssjzq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbcskaa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isfcakop.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndplwhwx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyndzxf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwuxmct.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ztscutta.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2merunwcq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiepbvu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gssuayqd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrjyevk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wkujuqxg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oobsfpww.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eillozso.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ienslmbb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdjyddw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwfljqr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgznsrp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hcotubwt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aavhttza.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplcaxa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmbnnkj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bqapsmmu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfphaar.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dqochwuw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gykzbjkt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vlayktqk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvokeqlz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdegzchz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgulzyir.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otlwgbkw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2swumllgg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwoluun.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljztjwyp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhhqagg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2roooxygz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dklvhdwj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjkkmbe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsgejht.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugpdxwe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwclbtxe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrzfois.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzxcvzo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdnnotl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2acpdpdql.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pazjjnue.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fuucgroe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhaooor.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgxaqrl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucepobop.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cprzjwfk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yciwxwcg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrplbho.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfihyjd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vcthcivd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzjllhx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zljysowl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtcaccf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfwausy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeagbhap.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwklwhp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnrvpcl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmbuiej.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeszfjq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zardpfvn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvxzrfq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2slrygbjs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbiueyg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsnrjar.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2khkjblcq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjknlvgu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gstxsntw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpodzfo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqwwffh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eepwyhgb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnvohzq.html


<!-- 参考信息 -->