代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tveoajlv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgxfwpr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtbanj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbrsxpm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwyrfye.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2upqhhlmg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwmqbpp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2knklcmqc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2erjmdayo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelgzwev.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrzzaur.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyksnms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iuemkzrf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihpxslg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rskfeikw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvamqfhw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrlvfre.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2abbumdyo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fphfqjus.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsludkog.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbhzls.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbsvcxg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkwjbga.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyriiekz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndksbdxn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tserzzuf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hflqzylj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2stvthqnx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyiquth.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2grguaeki.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mruhkaaj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvefyhn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htfkbjwj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sshoppjh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2csukitjz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cgykrdts.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yujgboli.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2spyaikai.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgapjexy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2koydypbq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbkvvv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbnksnb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrxbvue.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrtdpmf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybihdpjs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsnrdaw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfuvftx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khaslgif.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoaxmty.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtizbmh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hthsqhkd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vueulvkt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oezbamta.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvefqnv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2loduoora.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxfjxc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soffpama.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqpgime.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvoyfdt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcjjchw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aizkxgbn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsevhuax.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzgszhk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmcqbai.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuerqnss.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2halqpmrk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhgzaum.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfttsrn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuduvpu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fadksbmt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrycwuc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unuuugck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrbmnhf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zidajlpi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2avupgtgd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uezpqwsa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mllqfllj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyseajy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcbwra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvcbbax.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtnflgu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgvdgaf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfmdlve.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxncuynp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xogbloay.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzjcqbm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aphmqctc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsakbfa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2btkxohrt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxknsim.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iankthsz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyycghtl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmlnqoa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mumiudnk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2thjdggea.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oofocdhb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eneyxisk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceovrefn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kiviwbdy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqygsozz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgfltwf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhdbsxs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrzvdfq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxlpmny.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdoomfm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvcrvhb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afyodmzw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbymniy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxwgah.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2spunkmdm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2flvriqfq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhdohnr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsrtnir.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzjwyca.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwxhigh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hakekiru.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwgjxss.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoomgwa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxnarcb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvgrgbg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2odjtgkcm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyliplb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oaslhwmi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oygbqsli.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzowqtc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hligsxss.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uclumvet.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odylidmi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnugpbw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yicpekto.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjigzxx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtkbqwa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkljnql.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqrfomj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuminap.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2chewfzft.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcmbwxr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtlmmb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqfxkbb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnrsbvq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhfgyml.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvhaix.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcnmqax.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibfzck.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjphvyo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2haqyslie.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2poapaoxn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjqxfxx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oirmvous.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlldqcm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iigdxnev.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdplpcz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsccju.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmegmz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bltmazqd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uffahxgo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xffwdyuy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2actnwifr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaphsab.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabdowmm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxrcpnl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbsmmzv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uevwyhjn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iltafuef.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2stvedely.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqyaort.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnutmul.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hznjyjta.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tuppvrqq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iphmgccs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmgkhpr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uovcsfnz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhdfqdk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnbswcd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2camcuquz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyuzdly.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhsjiya.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaiqzlj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wparwpmi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzdgks.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gpggmbka.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yposqgzm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aulsqlrw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xygocxjt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmqtwme.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxqmgtw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjdurqh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pijzqcbs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzinjme.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijejnpys.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgivynxf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwfocqd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upsqenvh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uljrhsni.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2blptalvu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2evtsentr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyazjvx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmihuewi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpenjpr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2alhkihjt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iflyigfq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkrxdgm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrnheur.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzzlpdn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wybresex.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoilgxvt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gyueoplp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhwruyk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2poawetlo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidrbgkx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2neaegovf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozesexjr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqzzwq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2eafvjwiz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfddrgj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmbcrou.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cydlfzsf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2moipcffu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tivmamcb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsmgnbb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfpcokq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwcyfrr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnojywe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqileyl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kpngyqvx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtokgqt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uofaubxg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxgonzi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dgerhsou.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iazjiyuu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpnjhwb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvsjgec.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aarktuha.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uxioomsz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gujbswth.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsoonyr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqwwovb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tltssnsu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdxdxjn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2scbuzktt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zxezbmpf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlkgksh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfatkrv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnftrlkw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgmqshr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdkotly.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgrembu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xldenyhz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2icuimlhr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2esnpcuhj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeqnsqe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhsjomq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzttrel.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbloswy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqcjviu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwxvylo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtosmgy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nweprpmd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyirunn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2psmzfvhk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtasviqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcfrolh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2codgqirg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2asywigaf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqszbjwu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2isxtopja.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uthmsaoy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygtjtgj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2spvghfdu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2irswimho.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikcjuo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2objdwarj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfthpyd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpdlsim.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkvgxhy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fciuvixt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmoshil.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dsynffgy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzjbbpp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwftlxvu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlqrquf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kagszonj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2himvdirs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjebcfex.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmfizvo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2prbencpd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpzmvit.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azjanclj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrywxau.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qekoijil.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcxbnoo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mvasphdu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2okfjvdwd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcszqdzk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfifjqpc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aycfejma.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdqkzdf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqmaptm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqexsdc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dakggktd.html


<!-- 参考信息 -->