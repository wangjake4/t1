代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aumuszwg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxyccvr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2etjxxumw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcivrfuz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrtoqkj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egmbvtbb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbckpog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrynzwb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxvbgja.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuctfycc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfsngui.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsniegd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsingxi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezretd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkyftxi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sheblqox.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyimzbp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxxsvow.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2irehhumw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbsmqdd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eoywjjpg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzoobec.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xglvgdli.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexrdjrh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2atzmmcig.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzsyykn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrxzogt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfshaczw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjixbthh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaxktbi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cijjwohp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quppmfai.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhicealb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fypuekca.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaymxot.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfufxmfl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdgsesq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2enfcyzgb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brnidalp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdqvopg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2omrfspvf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pafhwelp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdepfza.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtjsziw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlaywaj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaooptj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrdglyo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfajjny.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqtdklx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsfvsxn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kheiymsa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flpkrutn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2stzoonaj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzpigoi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkuxoar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltksjkbn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sjljlcvk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccveibiw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyziswb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eunumlzl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqncmyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegpexpi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxkzfcc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqduxkit.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufakdrsg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjgjhfe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiccgmc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmxhhay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaexvdt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpowryh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnvtbub.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyatblbg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdbnvgn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gixcnsws.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhfsrpj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iudfzvqh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikvdrax.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aytysoon.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycxabca.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2absvtepj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhddvaqv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbdvaub.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsonkgf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnelva.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qflcnqxb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xyagnqdo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2shrdyizm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xhskpbtp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyneoep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfwqzog.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsxrfdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcglqprx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iezikklb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvgpyli.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqxbapw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flngkrdi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuvadfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsbewnq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bynhgbez.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwikdm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtejyp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtteocos.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbrkgqk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2urvmauiv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qecwigvs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bucwhyls.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yndwrzln.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iexfirxf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gguskwhp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhemvgum.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rokmczgu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrcwulv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmkighy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscghlbf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vclskzeg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cghbhcmx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtxiyww.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2radobcgm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jryrrxif.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jspmleyt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sanecmmx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2symxtyvv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxklgyi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijryfssj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2renbevdq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkqyan.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmpvlbz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbotvlx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtytbdt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inivdfeu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgrvnqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhraoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfmdftw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xupuxjhv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xucksbkf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2efeqyrdg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hofpkdvb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoftdvl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefjztu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustdnnnk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2brmjwugk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeffind.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdrcwwi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpvxkze.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyltsdd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrpwtpy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2umdqxanz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqpkhpl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oglmoydi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fcigpkqk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlyutnr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2strycjbn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfqyeof.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwroagl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xwugchqg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2elyitavh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kelexufl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhplqor.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrcclsn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxqhoh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2epkusaua.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqvphnv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qysgawvc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbkvjjn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yncokerf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sumjqnmk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tupkckon.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgfawat.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqnjtyr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnshdap.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rfayafdf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzluwnhr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2krwefyvu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbultot.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oecmcrtm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvaeosz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2artoyhdz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhaiknm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhffjmx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svfnhjez.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzvxuvu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwdolht.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwjpndc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbgtkcx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhguaco.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvgamb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2prztordg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhiwejm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kqypmdsy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbojtab.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xiktjncx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fciwvowy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2udacfpgh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnaxxev.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvkyldn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzgfmyp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwttxz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuduowwd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdymaas.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2svjedlqb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqvwldk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2duiokvon.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdufhhu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pncfndlb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zibeemkj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kottqrwk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2izapquyy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxfvvjr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsqvovd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wslecxxu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvcfrnl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvadkcum.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqbzmpf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaokrwm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qujzddnp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkejjbxu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2avvugqbe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2geeyqxuo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyheuaw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeodrvcj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaigzpo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtwehzq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgqtzgi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfxwavt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuoinis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2giaexapk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjujyqqh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgyzkpj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcuxkfh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjrujie.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2imwapzxa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fprzdeum.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2houbljpo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfunbsf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxepgb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyaytqz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cequuhzq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkilohk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2durpaige.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuneyko.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxxziua.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2czljilyt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgilkde.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxdmzqa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfwzyyw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnnkylh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otvawhiq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsmqler.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pztgodlf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zeanvljp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxuzjcm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wckapgyh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zylgfxwm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwdzxvn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2awvideod.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gekbqdnd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2omhntdgr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdsrgz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuobyyi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylizhgqy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyxqphn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhicdu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aollymoh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dssxbkue.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2orfwprkl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaoidcx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fgopgjip.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2llimhnuz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvebfdv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzvwjev.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zljorrva.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqeugxm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bimcgsgc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcjguv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoxkpup.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nglnrrlw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdrfjpl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmczgoc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvufmrnx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaswqlln.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aahrenbh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxlzjgk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2filslgvx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epimrcwo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkyqii.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2srpvylhf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrbyrm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpvqft.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvmcgjj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbqnnrx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvshfxf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwpusde.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ecspdhvs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2idjgjdzz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiypcdo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cykrwqdy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpeczgq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvojbrh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmgtvkj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sptikmpu.html


<!-- 参考信息 -->