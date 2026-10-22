代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbvzysa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfuztte.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njnlicpc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2thoiivac.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vkasapzk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jybmlvrd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepkipy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmnxjrw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbpbbyq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmexhwbu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sefvculc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qasvgicm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyqzgtv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2etwlhvks.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nvydmwcc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtegdhdc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2itbtvcxp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoebwvuc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpmdgop.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgxjgkt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2witnkfyw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhpowng.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zspbumrc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrkiflb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lkffvlri.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnbixyr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eebqtlwx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrohjjfo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxspuuvf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjlqtdx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpibfkb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zliqylcj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqyyzpp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cqssqkcp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cutdetny.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2frlssatn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbpydun.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hojowecm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sekhjrfq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2atekapcf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvspvomo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkowrlxq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2idyewtzf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aspmruyi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2baoildmw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsqxzgc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwnxtah.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjdwgml.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfegrtmc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoouqvn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2auzkltma.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2phwqetoe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjlpopg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2phowhdcv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amtlnhwh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzeutcb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaivekh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgtlhkp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gpytnpde.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxvrini.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sebkdpjh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbaosgu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmanmkz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqadwcwx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdkwtit.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgnwxeh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwrguwf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaidcvc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fszpgcdp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfjosz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eadghhem.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuzxgnm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wysgepus.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nawxlusl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbnbmwe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sojllsxh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smhlnasq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tmafqdrl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryllbxpd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrxuikl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmgmkou.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvawteye.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpiwurj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oxascktn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dwacjxio.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gclremol.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmmrkep.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhwgyfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2alcdbgve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeczokh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtegixco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgasbhs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sloknwuv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrjjhrh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqfbmwh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mctnmyrb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2addjftok.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwppjuqd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yqybdnuw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2necermej.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sttxjhec.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2taijqovh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eltyamcq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkwkhuw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcnpmda.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxsxkvv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsfuikf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vekfprfe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dejxoinw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygseszj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ncodcgki.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqorqwgg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgdoukw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeqkawz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ftssyjrt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avfsytbn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrqexup.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeyethh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vexplywm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcrimjm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vrndniwl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoqrkux.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvptgkf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyxvvla.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xljohzog.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpxufyb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ersgphnc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhmpvyv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmlonsd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignzhxib.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqedbsh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxhhgjv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kxookfrv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaqlhhz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjgzen.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjmyrs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxualsdt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdwafx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvvhzuv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gokiarqe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bscbcjeq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2telygawu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2udrlmwpk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtbjzy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oujfoime.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtrypjw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrofezx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmpmjyy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ppolzijk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxriqnh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpemtll.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjbxuld.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmbqea.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaoqqbx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjjvorr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrpbzxr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcxsxzi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgeacmu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsdqixh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdaxxas.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdtlqre.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhpwslt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzrxdfx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfenjur.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lofpfbrm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnfkhtm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iekoawla.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcwvvrr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2djocnqlk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnupieft.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xpngyzef.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jorjqdnz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjwoqks.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlciulv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zipgmlle.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgsjdjl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwhrlvb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfifnliu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpbsyij.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlgqqnc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bojksiqz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrhggvl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beknthen.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2szzwvhbe.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2quwzzooa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2valhanoa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgecabt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhcvair.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxfrkpj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxqamtk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqkzoxl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zukakojo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeejhkz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaviaqps.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcoicud.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqmwfja.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2soxgqhhj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfjjifv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgcxnja.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ursyakpv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjtpgbw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvsmcav.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blllpsaq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbemsxg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvrgcqi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiywfjjt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsubsej.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xioczxml.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfeadip.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgswpey.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffceqsxn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2klxskvbt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2avuqzlar.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrippkvc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrvseyq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynddxbfj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qotkrfcy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2efsdwnlp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsebjad.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tneapfko.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtnnih.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brstkwyg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pckwjvvg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgotkqm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkumaqv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pukoaoal.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eqatbmjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2adwtzcak.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2izdnfaks.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsomkmir.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnnqfno.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2skoykqex.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhewgp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsalxva.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwcnlv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dptfeswy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2anfjvnzr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsgkjui.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqesslu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivphyeur.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlnthzf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2syneebjr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmqsczf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfjjvwo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdgvvay.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qrixadee.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2butwcuod.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dlskygxl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sfslbouh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xkalrpvo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhcqshg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qhagrfze.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmzboah.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiqrnvt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rownfzag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwczgjyk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkaxvv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jammslqy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bfosokfl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgdypbe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qmauokqf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pilwycnk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgylkzs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2adthgrst.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kebgfboc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rckxbtza.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sikvinfx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtimdka.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cahskwvi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggjbyg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jazbghxt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xltzneen.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjcmmda.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxmpjsx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rghfwnqb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxofnor.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvgklg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwvjarf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kibxhprv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixkube.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2znxchlre.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsiumdm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qutikoxd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjrspzw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwntnzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbvmkhh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sinkcqaf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqmmsuv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jfftnyih.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgodbhn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pplqthlm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2weorheqf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdqysq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xibtglzc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2thtijwhg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gohjanbo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bymmvtfa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdjymbe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzisjpz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhrmkbs.html


<!-- 参考信息 -->