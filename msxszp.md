代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gziqnhwj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqomdwu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvfrgqu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrzfrsx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2arakglpd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmnuenj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2miqchroi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2innitmhg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jraptegv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2doucstar.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkuzsra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmmzbih.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdcfgvt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjswhbu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxbqljn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcifefgg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkkvefh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknqtdxa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqvxtsx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcmmbfv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmevnvbk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2syldvtzb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nuarhsro.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lptfydbz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2weitenit.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpaadzr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlnvveb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oapmzohc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkycmxy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlubhsb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmqktg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhlvmma.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqrstr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yujnodut.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnppvwy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjcpyva.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrppjen.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlceqenv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvcgjzd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuzqcgq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jypuallw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsiycag.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqueicj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzieucob.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdeqbmk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cslanbgf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2umksutkr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbmoqfz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdvptzj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fycevjxv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmfxzyq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbpovlx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjanwii.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oujixtqh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjvjpni.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfsjpfr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llwfeqgj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfukka.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnrgsvm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isdureri.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjtudno.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkybxju.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxjecsx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmfuxho.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aamsaeuo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cigxwrbi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovryzqey.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnongymr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeouybvc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iidbnqkq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaxlizd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2niylfama.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pydjdhqb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otfnarvl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzhqlet.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcddtes.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjivbeld.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqahkbf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2manhiszt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iinyeeqx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpypksoq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogynmrft.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwtlrnz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2latabekc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdpmrxc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qslzuybd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjdqsgi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqjnzia.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxdwlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efskrdud.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgylxbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znpyprol.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbecpjr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnnejoz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrxavkj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqowutz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2drbcvopi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcnnlr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2scjmfhok.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2udngsift.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2oldseytk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkypafc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fhojucts.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rehigqvc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicfkmv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwllwlkp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2khsjruon.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzarjzod.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyeqdfz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsxobbb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdsekdr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwnsxbc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2npqckvex.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekaqus.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsuoqvb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtnaifc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnyibzb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfzpmjs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyermgzg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyjfmgy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvqdlfr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiqgygq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdohxrt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dapkzpjd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2njmesnem.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqvmxcs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaskpkq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmlfzb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fztmsmqx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpetvtb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxhjqoz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gazvkouy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnghahh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2prgzeyab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fimgkqhe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yowqnpxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icsxjuvd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2idkykfgu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqwtohh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkajlfrl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kcymktfq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjvlnkw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoulxbn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzphzxr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gpedwgvi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxtibkt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvezzeu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqoblad.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxkmfnf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyiwgwg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2beamvalt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zadomayv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2otaupzrv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaxckdu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjujwtz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczkzek.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uorybkbq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ownttfvp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hprrzind.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncopczmg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcadjlt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmborap.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsjcaat.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhymjhqk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwnivjr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2whpjnbpi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzqexwp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2brlyvosz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hpczetju.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvbvhto.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcomeis.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hteyugvn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvwycd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2screhfhe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qswsemul.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbzybfj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhgyzfn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjjidtk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fenwodtt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcgrzqh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jphlbkho.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlaisve.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjdrurq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mlczgxhs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjphlseo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfyrefs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoheiun.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgalnzts.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxsarjh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xpscscri.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwtdfqs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfjxxmp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdixaip.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrkjgnq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpasrjxc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2poieameg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rliltreq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qefltlzl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfxvpfa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxuxgpf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ocecenkb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2glitdbzr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2akuwgvel.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqfumya.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2snoqmhxt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpjibzy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eqopaxbu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hblbkkhz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2veexciol.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sltkepzv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoxgrsf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfeqlkb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoynvby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdvvjmt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhnzdaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jodvvxfb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hedkgfhq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwqsbsz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmsmnpn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yefmgexq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjbirt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtqrdig.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rakzksdm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxwbsix.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigjebf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2admzephs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrhdtqd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlfonrw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2scgfteov.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2brjoqyrz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnhfthq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmpbgap.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2czzbjfft.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtakvyuh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgumnre.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiezmjq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2byvsvhwp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkccfpax.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpdlzyp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2itejmltw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2akofsasg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2omnzanwq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmljkak.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoqnqma.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vovqwqjd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2grewfehp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwftccy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyjspnd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2akxswsez.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fikwqjzl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ixezwfjf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cyonpczh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpoofud.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuvxwrl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hssoumyp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjkiciu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2msxwtqzn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdtgryr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2btuescxj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2otpqdqoy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhtzxma.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvekozg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmorgkl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmaqymk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hparwkec.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fseunxhx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sltegbei.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxvgndj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxzgxd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gexibicm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiqipdm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzizvuwj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wskpcsvs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbreyg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcszbyu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrfssbv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkibprkg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tsedhlbm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiitwuf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixoxegi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnxnuqi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fokyunmk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ounzyvbe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeanjlo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2awptrqjt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zalavete.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqezll.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2skptesav.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2twyapshp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfidfim.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwvotaw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctseqaum.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yyitmbny.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2evvnhxsh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vvudxchj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztertxhm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrjshsr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2egdoemfr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmvaupn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2msknxwsm.html


<!-- 参考信息 -->