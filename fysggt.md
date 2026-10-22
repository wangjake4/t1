代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnolhvfa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxijgfof.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emglucbs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaykrot.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfexewl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglqpcva.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdbkbt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2klllvyhq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqpdjkx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhckqfce.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fjritezm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbihixfl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkkvbwz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgzvryo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkuvldq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjpjwxl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qbocbelb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sduttfsy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbabfen.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bueuwryv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kqehzvsf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsgxlqx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dlorxrip.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplcrdfa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeoxjyd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyiaglr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ludixkqb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieycovyt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrddctv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrufxsz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yypjfwlc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjnkex.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sddfshvg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmxahtg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwjutym.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2muiuetzb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqgdyv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyucyhng.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msyyytwz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nphqwwbp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcjpgar.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdremehc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilglmyiy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2doalzpvw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxornlm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2homgetsm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2egmgahvn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjhxspo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdpmhat.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcqrlmp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zopiwzip.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbafaik.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgguvltu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwkdzns.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqddjglm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhyqkie.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdsfsck.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kezvckmz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrijcnv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdinikt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdjixak.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqehbxx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvyxtqc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjhcke.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpjkkis.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbgelmq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdymandc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedwwnha.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mypaabeb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avntisek.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2breagxia.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsmbmqv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzinwnrs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzdlwig.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmnoywo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2msewzhhb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qllhrjnm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gekelgse.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhtcyhf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlsrcoh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvisydup.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyqmiin.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzozippl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzekhiqx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nicywglm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpkbewb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfvzkkc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhtnret.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceioqojl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mssywrof.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqaxewy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haoreffl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2utuvphqq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlbasqt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2srznvxqi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shyxvmff.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmcpix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqmziin.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kexnghml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxgwnyb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbhnagr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuldvsg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tbadunxg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2twdxdwkm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpuxjmj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnncmadz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwptunt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsllwzu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyqahfy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qabrnmkd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqugrxwh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmddqjl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuatdoqx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyrrwvo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxuwwaw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhagqtvl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mysoopau.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuyjqfk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2skkkhmab.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ensgzdfc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vycuuygn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yebosrjx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhjnyfy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuoxcwd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2inateafx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefkbiye.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpqbqod.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhigmovm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgtoovs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epdyotbq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kusyuuht.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgijujj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmessgn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvnbger.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbqryoc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmtmsfu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpeyicj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhzvzin.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jovdycrx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjsqdt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wqstztze.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdelnoxt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oiecwouo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsvighg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2agnqxtaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdocgzu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kskgznym.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fxarsyvn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2obwgqupt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvzgatt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyhgfiv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufikluy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cagntwvj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgukccq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kapkyyne.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzllzxi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gurhmdla.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyzpndc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaithmf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcnhojv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfciqpmh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyitfwx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrptuslg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2slknfhzf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oosaldja.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrbtayj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxstgd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrytkfh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2swcictsz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2klqfgudy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwlomnq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuqylhx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2twcldtch.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlaruil.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oefqpebb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuiwwgr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2byzfymmc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ombvyjau.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfdgpaz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqthxbt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtufbrgw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uccfqpfp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkkfwub.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmgblnk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrhewwr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gjttaqtj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbgdexu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nypzltqn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzznmsh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgspcmjj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkxpxen.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hduqusby.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dveruehk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlczoiy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwflqb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkmwvwt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzdpysg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtmryui.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlfgkyj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yunyajrs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuzjved.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkksly.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdpihib.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucioxio.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2juwtvfcd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2csejszoy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2epbzodmo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgpqysc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxpywod.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2folbcpvc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2whhuboxm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2knuyrgwo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvpocj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzugscn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdhgdo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzlvayb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyvqwkk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpdiqgr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmdvjfy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kshcxkqd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nyppmabj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepdpwmh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2luexqvva.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2joxeztds.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfxiahw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxlvjoo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyejfhd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pymyojxo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shcckhbn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoxivyp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtkxqad.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpxpkoi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxrnjkx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeybhoz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2omaaeaay.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dehhmlgz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdmecoh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzssgxhi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spliwefj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2veohaldj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vtewwtxb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqgjrrn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmlfel.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tivudrox.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eojdvjei.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpljcvz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ykauvwki.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sktwtrwj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oolmpkbs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmrswvg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpbemqk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2znxluxev.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfegskc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rparrhtr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuwwcka.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggebrhn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxnbqzk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yttjraid.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2giyoupwj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wslvjbmd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqiiqsz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tjspomel.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhfwxxp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sucizfux.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqzzhbb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlumcmw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgnejhg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2faylbfdp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiouinh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcmupf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqnszjs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqttixjk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igcjhgsd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxvkqql.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwjeblg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvszfvhw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drthmcoi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmmwijz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzsqcwq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjigriv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzizjyd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpxdwlc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vryfzmzn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbftqigw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpisrok.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgydjdv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ucacztmq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvjbqvl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2oynneupy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2owmtexgr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2arjdfqba.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhcqmiq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgymgijc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cehvltjy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2trmwadwr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfrwppe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqdgmil.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkubvyng.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ejydqfsy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2btmobflx.html


<!-- 参考信息 -->