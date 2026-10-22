代发 wailian999

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sldgeonv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhpsdzk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2leihobjn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdknqqlp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnavvgx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczxgkbg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ykneogdd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjkmydh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumfqal.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrwemib.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydldffzt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrqhdgk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdocxdsz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnhhxae.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlcmjpc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgsjlsn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdlidzf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2teclrxup.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzkaswu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlnsluh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njsrgofe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sarirydd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpogklk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiurvaj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgxbmup.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpygzjl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2risbhoqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpflolvv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqedqcf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdidmea.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqjwqdw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzsgbmu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdtolid.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nojlfonr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hydcqpcd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzobuzx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nwavqxjj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xseectgj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2txmcdmmi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuemwhqi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrwsyvu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvvcjno.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgvchik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpbmbds.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yabqirvb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oachupbc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dshtjlzd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcjvqnm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2toskqpcf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsxqgkh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvaxrpg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdcimxz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvriusgm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbzjhcg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xckeniop.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlebtdmn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iopkiyxi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqircbi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2levclllf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyngdjy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtllyzzy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2blwxiuiq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvnzzkz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvgolzu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjerlves.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vowfcvwn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eulniiux.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwuoreg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jamybnqf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnijnaze.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vflkfbwc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprarqih.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2agsmklde.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgskaugm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjlygjp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjcrubh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbxjtze.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifldokdi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clevgkic.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqpnsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dinbnwtj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swizbekh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkenqmoc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzbwff.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djxeahdb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjmashu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtjrjhz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2merlgweu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmjghq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qafbhnxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwbeopa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ueihlepm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvtlrmf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zstrofae.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghxpta.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbywknix.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtdrkrh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mpllsnym.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptusxcq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2snzfpbpo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2detmiath.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwbwfrx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyfbdrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzjozqz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohkuln.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bxirutny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kilyvmcg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mojorsdf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2odoffavy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tihwvjva.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qaluogpl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqkkrau.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnoyccj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcewxabe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2shorlkhc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gayrqlzz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwjpfp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qopazzso.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhowmdkc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmqdqdj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtkbqwf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jldmtyzc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ibotnhkg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2boflkxre.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhjlyzs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfmrmtn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2swtdcjqv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqazlbt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwnlve.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnruylub.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzbhvgu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqsbqlz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnxrzjs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tingshco.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aennqeaz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmccwhi.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqnncla.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwavhojp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxeavar.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsupqanm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbuqela.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2keqffguh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeefhtl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jetchdag.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzubpn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tythgarb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2huozatcr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqzmrke.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkviyjq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkdizjw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmmsvrg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaewtcp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2blqnggly.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxypwutj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvrqsln.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zslwpyzt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zsizfqld.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ouieogyj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2arycudlc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnifqgp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vklskhuc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2umqicpya.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtstxsfq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtvejgh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvbqgmo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2huinrzlm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrfjnm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkmqjhp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmweidh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxubzfm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuadass.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwnjguo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzrnyvz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjtmofi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2szvlaouz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafjzrei.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclbepm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2czsahgia.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gwszkgon.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwqkbti.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxkjffd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoppfbdi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhjzvan.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfffepe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yhddlhjd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dzocgnet.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmhnvbq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaczshg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xggwlfob.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtojorq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuohfip.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaawdzw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwjjsbt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omnzoesg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jokixqkv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vypifpra.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvnlweb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2elfpqtpa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pkozijqh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrylico.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2atimzuyu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgwukr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrwanns.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uznfughu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tsslazbw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvrmtft.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsphfxz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2erqizfbb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pesfemmr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2euuqktgd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkowjsd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtplkmfw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbppjfoh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdbewkv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooowimgr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiplnzt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkylrvo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkhjzum.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yzszaxbx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wviwnivc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2syipsbnb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwsgivn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eceowrcd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qixyditb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwfgphs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfplqmm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vztjlsfr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyinkosr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyryicm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbdekoy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duwkgzqe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqkudqu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2whayjpef.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpxgsth.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxyzsri.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atsdgjok.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qoytaayg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtytibd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wgofdeyx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2phvxgntf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrfpxyt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsttlrky.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjtpwhe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2exknspqd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaalsdl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyqzuzg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhbealm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpskpiu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2elhqqldu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoelwia.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tybumbwx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sumczgmc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wemwbyqj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzjaxut.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxphanm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lijqegvg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxjpsek.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2egvdoevo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2clbmkwol.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgbxshs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqgfrxw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjunybv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2blqhzvto.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2txoggqun.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsldxik.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2megnchhv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aucolyke.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtykgvab.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxeyaxi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrtsxee.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kzisftdy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmvjgeb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cabfaztg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hvejnczc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kamkafwr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjkxznm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mucaatxq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxbvzkz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hseutwgv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylagcicn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rdripurq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyxtlwo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcjyfax.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vduxekei.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whqldgez.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbsrehr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudzlsh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggowwhvh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ourrglpg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwwjpww.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyklxhcj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxrwdwo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjhmyoo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2easycjts.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wohoassu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rawntqic.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hgranufk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxnvwuh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xriokfmg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2psaqztkf.html


<!-- 参考信息 -->