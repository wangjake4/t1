代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjzkpai.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emuqxrjr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uktanllt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmspwwkk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wxydmcck.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrmhgxr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wstjbhde.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfuqmlw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeoagrc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqknpxpk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zojzjahb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvciwoz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmegnfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobotthw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfucpsm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umaxrkff.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lezwdpmb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dignpzkc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cietngna.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkawiamv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nblvrwop.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfqtgqv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzdqftf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwhxnji.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ahovoqgt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzcunpq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2odhavapw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqthpvno.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfsuzec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdrellv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upwgicpk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqmstyj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxqkbbl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmcwgug.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwanvvn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2unblujni.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pevnbybu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoxmsdr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxnabmu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvophx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uuznyztg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnixnhni.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxphdjde.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoylndr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wopcjvej.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrqtdla.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnghatrp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvabmuep.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qazhvcxk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2prcgxnzl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfajrxxb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fumhvcnb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbfodmi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbofdar.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wksppuuv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koohuqwu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbggxcr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtvyucc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvylkem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yahjfdza.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hnddyrsz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvmxkgn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vswbnudx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bufkholj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnfvxtt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhziepl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euhponot.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2quifzaqw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxnhiuq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsnaslk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjrdxqn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxkspyl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nulwguvl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjmnrzw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktnszy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2muxxcmez.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqyril.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkpwztr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgjbzrt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tracakwo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjuvdlx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qkanxeoi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbwksoe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kobqbvti.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxzkbtf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcovsfj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyetween.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfremoi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrpoetz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meuaypmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqglvxwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tidkzevf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbllrbs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cggneppm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mzutlgbk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqozqxc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrxrcwv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcmlzdx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2atudyitn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hntntmnn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ialsvpkl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpjgopk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2byixwxgr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2piifzseo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2enujenss.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2scwuuhgh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlhefiu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmrpra.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsaiojf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyqdxse.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuamzff.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkufcpcf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtrkgof.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmlykyo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htlfsxrj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhthusl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrnuzcg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrojhjj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbgduow.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqopajw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2okqlfbie.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2codxiiwm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhddyvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cddbjfwd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2etdnwvey.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2amlfivus.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwcpnqa.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbldyhtw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bjftirfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzqkkwt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2frexdelw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvpwxzi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lodlecgz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaeepmi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yabpwxxc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcrjao.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adhwugyg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2chrricgv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2shfcpkwh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmsndcf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnmauba.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpypyev.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yztybgyv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlswwzry.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yrharjsr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tpefiktg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwnvizu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbunilk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pnexrgnl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoujxgq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzazhgq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqhcsa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrenxsk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2whclfuuf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtngywc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2npakcnea.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqgwiyc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvoivxm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tlajchrd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uunjjqdg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2flmqgpqq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2afsemilw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbspcnyi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuedzyj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkalhtj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcgyraf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2efvqcfkw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdcxxpa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2utibahpl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpgnhtw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbmjgwc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwknhhog.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmsqzgg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzwxwms.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2afnxogvg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrlixoe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwedtmoy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsamyyly.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gcperzxh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnvcjpn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2boyocvqu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaapdfw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrqvktg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sodabknv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bezalntt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbjuytb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozulcopq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeqvgjz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwqgvcv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhehzenp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yagajjzq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlxhygh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhajikzu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2htcqcqnb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjccrk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwolgsin.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkgmcnm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvledmoz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aonnwtfr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2edjrjxjc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmenyhz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2imfyrjje.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gixidzmt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtncgbu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2psfwisxj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkepajwo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpqaepk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szwjfizy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqvddnh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2msbhzkfg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wonmpzua.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxsmku.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjvxefj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2amisxiki.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqnypz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hejutata.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hlocplnw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ablamtal.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mozdcint.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnkvwkz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxgbxxs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myubcwge.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvojzui.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhubdza.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2drxoiqrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcamsnew.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2keywovkm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdonqqd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2axbejaee.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkqxqn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rylsfhes.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bltdqjqt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqopflf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbehgolb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfykkuc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jublfdwb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpcssny.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvveyio.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmxpxda.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2esddjwaw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcgixxa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuubolh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2byglxkyg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2aabxjdcf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jecoykqn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qybxhmmv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvwdjxl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2trsyyyuo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmbbrwe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2koviwzuh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vysuwdze.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lavlixua.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2afahqnrf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfycgg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2khchbszp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aektamwg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qblxvzpg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2egxppjmi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqmnjud.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2euwldqlr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpikibp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2znbbuwdz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbfyeow.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbzqrwn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrwrsuh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeovkhg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kutfssbe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zozxzrcb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2grrzqupp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjdctsl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stjnyeli.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvrewav.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhyjkif.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2opdiwobj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwiruso.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqxwngn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eeajfsma.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yozzhany.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yccjavem.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xltkegij.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaxkhnn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqiiyfk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqeducv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwohvhm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dannoffx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiaxrzp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwovbpq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfccpfum.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyscbyp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hamfkqug.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjmdchf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynipoprb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fauumfny.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rczmwduh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdxdlvu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rscmijex.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagybup.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyxrldk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvphouv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucppps.html


<!-- 参考信息 -->