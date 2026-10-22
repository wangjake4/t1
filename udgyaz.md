代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aozwamxz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hptxpeql.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkekzjpe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dchuerur.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmmgwdm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpamcws.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wmthayih.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffwsbiz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtecepm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzavmtj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kyenqdyh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vweocmnc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhumajpy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2igljxpxy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpqmkvf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zblzcqoe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmbhwsv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2izqnatkv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bviojmkk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijpnmez.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrsqhkq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggxmsph.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlugpeo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kutmqoqn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2noiiezxj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xinascqt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ocogrxjq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2btqcouyj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqikotqd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvvmmi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhszen.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaegfyj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dofxgsza.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtnwsyu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jezxfyho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2prpzcldy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkmlbtb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxrybfb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiqdneo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgpoow.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdehkvk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amxorsnb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcdwlnu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nsowopou.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hodaqrtc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgimjvyw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2afwwsbyq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuznele.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2extraryc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2htkoamfm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcygeku.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbrrvqc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2diaqktxe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fddfuiof.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kixenexl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspniajs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmktaxs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnkmulb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2knksrdxd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzapmrv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xguitffz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuvcyjh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drrsvjam.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpddwui.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqwukqq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcvrurk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxlmoa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xktoqmgw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbeazit.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jshebtyi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwvoajj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qysytxxr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbufvcp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqimgn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ostwbsxi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvxytgu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoqrfau.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjcpqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizzuzih.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcefmvq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooazdedh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjejlwce.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjkqjom.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlqzafu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2prfxewvo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2viaqjcwb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhvieui.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xttsbbsx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2eshjluwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhpswhz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssctgnpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdbxhfu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgedyqzw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhvvnky.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqqvnzl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owvsozhk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexfefu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaazher.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2meapbqxa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodzuem.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyulzknn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvsmnyw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaecpav.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgfsksv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tituxoyi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcxwrud.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmtbjwg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2utlsgbnf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bxomrqrg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oazyppot.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbgvcqt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qldakemh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwbhejc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elzzolsn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2buqlebnu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aharhjkt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyovhata.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2redsoyto.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2brkyapjy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kknixpns.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxpvggf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzenmpdv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qmubxcct.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsybrx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukpwgk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyzdya.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmaigil.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hztptofs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2decokskp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ealtnroa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfilmrh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewywqoo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2okmfcjll.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmzxrkn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2brzrwvey.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aftwkeyf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgecoylw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zmasnzyj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmdkfcw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jydvpntg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2boktbudh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mysqlnvd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkwovqh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcjuilt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ozueoibi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2weumcdhs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wooclldk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsgjjkl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2watjwezx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcrrrbf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkokcbgr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeqtlbl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2toavbjzo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fewthmgg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcewuqfc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nssqaqul.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzacrl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyvuxyc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwgxver.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2okmysbcp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2smulsrww.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ognpkspn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owmtidvs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2teiqvyoo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oqivfopv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2haexodjh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lohdushz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lddilpiz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2onkaovju.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nshbjxxt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzonswo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmethsxr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2avevjeio.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmdvhtd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gdifpwyp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bncdejpx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pkblmggr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2halrboak.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfzlipw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vicarcnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjvjtrw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rasymrbj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oalnphfg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2klwuhhgy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdnfpgy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2spbllubj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ubindlxt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnelgyel.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2olvycici.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrkgmym.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2svhlbggk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afjqyavk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcqijmo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntrrrms.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npgytzif.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2csdrmyhh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvwsddg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cczasvme.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtnracc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwuqhos.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsimjsv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lifvdkqb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdirrxl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaoddsf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjlkngv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udxtbxbp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzqsmcp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvetjlhi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igbhnspg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjblndnk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmeqzca.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2goeucgmp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzjbjwo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ambzpvwh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlviupp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2udinvmfo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tushakca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnrdccx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afazpdrn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfswgmp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sheosjwf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztygzvb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjvvmve.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvxqrjk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgzlzan.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oehbjeti.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gixaobiu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2idbruhhf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnknpk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfglyuzj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzyxujj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2torafbby.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxarvpk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkvmcme.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zajorhgr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2blyqsqzy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zckzxovf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjzoaao.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dytezaof.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlihwx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tukpouas.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bustaubs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrkmfyl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xditxdpa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2flmmurzo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2icatyahk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jmihywhm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxepxwy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jdstcfub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rimmrkwl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfhnckt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kjggsozr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuhsrmm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2psuwdqoh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2klfxkpkw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgfmba.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjzbrim.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxdktam.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiyouzv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpaepbm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhwdlnq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyoecsn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fafbmrhm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpscsjo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpdylmy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziudrwut.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2llxzugdk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpofngxs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oubderxa.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbktfsrb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rudtnffo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcqhjuw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qayxtxmo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hljsnqcg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhbifro.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nugyirwr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brgbfmyx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vuacdhin.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oltambnw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpcilfh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iirrpxle.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvnirvz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqqunj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fympflmn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeoiqab.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkzqcco.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2emescsww.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbcuzjb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyvrpkc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqhbqqw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bsawyvqu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzkxgwx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzhybhn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiakeftz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzxxkcc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpepzdvu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nixnizma.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhgucod.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lubjqlor.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkqhilm.html


<!-- 参考信息 -->