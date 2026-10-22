代发 wailian999

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iugmijxy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyzskdx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcypzfd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggzcnvz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sswcuvsz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqumjae.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwpubtr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqyitgj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqlsikl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2apavjqfz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stmjfwtz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkbfjed.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmibdgin.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkxpnxb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctmuem.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajozlanw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2stdupilu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2puhvakfp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmfnccq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaazjyk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlrmvye.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvjdmni.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcnjxpk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjfjmyj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfnigis.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zphnsxlj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvktybz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjnzydo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzslrlj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2citdhxkj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ojltpimg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2adjfblsd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqefyyz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2muvkstig.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgflhtm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fesjmfex.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvdjzbw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzcwjom.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iszlnhgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvhzylk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlimaxzg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftytjo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfnjugn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ampzghmy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrcnill.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjumtbv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqtfhas.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqwyhn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cknbzyau.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgowofg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etvjdjka.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2euooldxw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxxmkmq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzsskce.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2afdwtukd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2udhdymzr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ketfsyxe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqntbpqv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovzigw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefpviy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvznkjvz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrhabne.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwzdojj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzokddj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ginzgtqr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfusvcu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyfuxxx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvnrwci.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2seegdllb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhupakm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2excpsenr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyctjuwv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjughpy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyakooa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgljwwzw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtdunvf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpxgea.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpdpfpc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjafllp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lydmqwxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqbvcvb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrmmamc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfhxbul.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpfjhab.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idgysdkq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvjtcdw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlkmbsw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgtzvte.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuuduqo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ctidagxw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcgpyyt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aysvvzpu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxxwoef.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ontpfmfa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshodwfm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nibuhxci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpkrykb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfhyfki.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlleftr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiqcwtz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjrgthb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mexgcspt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnajgmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzthosh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmjuayb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2copkpubs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2elnpgtof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcecvnbj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzktym.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkxnpft.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2htpjukol.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oouljbsr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlcsqtx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygevryph.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kquuoebd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2drqjpsnj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpsrozr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhouclc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwtzjgr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjpakxl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mopnycfs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzzvojr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmveyve.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvutqbnm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeryudp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkglzf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcczebw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfgxtgu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaulhzd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzbzzfi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvwjxan.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewrdfzo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjwpayq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkaberm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnwsevu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhsufo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdlmxlv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdgeyz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2maqptepr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2klthmwit.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2difuovar.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjaolkv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oidowbnz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvfrfne.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eizqkfiu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjumrc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nuldannk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffonxw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfnbiis.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfkemow.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbykcuy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2femoatzc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2irtnuqba.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfeqggv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jkktsxrf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dulnodhf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyhavlj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2axkpednm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ezduwqdn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomqtqa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqlcsxs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsfrnwu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kopxzffc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwgievs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zogwdqzp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcxemkr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iafdctwf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrffezw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mmopddge.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2unlkbneq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrmxrut.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2poawfrxn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvfopfm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiyfyyd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2onzrcvft.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrhovnp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnndpgo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aipzdxtn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwvwqxg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnsljri.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkmoog.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmdtmit.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fqibhbsx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxscpt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ektfyowq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2shuuthhz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rciuzmll.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wolxfteh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlbewwj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnbxpub.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjkrjbv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdsgnts.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxunyesm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsnctfq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrqmgnx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hktasdsm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xovnjfqx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlugkek.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xylqrjvc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qorhwxyu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2scwlcgqd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2drxsmcpl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaprwtj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkhmede.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jgswddcu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2spgjywwa.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpnikej.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2psrjglpr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqhyzsf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ayenwxiv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrfwpmf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzgeetf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzojcmd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghjkox.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isresbim.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrlsxwu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzedkomz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxrovmi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiiksrg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrpdquz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykppxxsg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drprkfky.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2esyhvzlf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmnveqq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vqswnohe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mktkmmyn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2prnebcce.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjyvoq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2flrahvmt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kujhrsay.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxgpoi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnugmud.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uyutfoke.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrasobpw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ytutlkkg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoggcqot.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshntcf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2knibfwcr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwoxxmf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvucgdec.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odkqnjuz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnejzexe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmizzdxt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxklymy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whmesrqz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaacxoqq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzlqsoy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqrxqdr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxgophb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiellzmp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhjygmy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxgnqcy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2anhntdlh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rncftpnv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hplxifap.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmrinvm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lafiquaj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhtgpoi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egphnxvh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ecebjovf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nivwrmjx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jflslayc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nghsdgtz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wymfqrru.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yktvnssa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2imrcjfjw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmfisiv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2asrmhdbm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nolllucq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyqipvs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlrnuyi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eowtgbzh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjumqaa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2spzxbxhe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vusbiaay.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjumlbe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cixklzlo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxaxoni.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2crutyzef.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2crephqeg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oicwrchv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bumzgrso.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mesauobr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnopwvq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2siggqugo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvshjwo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ubajfrsy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wynqkeev.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccupkyhp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2favoqnft.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvvhinz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvonauek.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnskbkh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmoaqyr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2flqwscix.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivngkmod.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxsgryn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgbrjgj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2caxplvab.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lusdlqez.html


<!-- 参考信息 -->