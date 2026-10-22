代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxgwnpu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oifmfvmy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dptwaaue.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pheegqaj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iekjuslk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhauiqlk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxnmyrw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoeqnue.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbbfak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmartjum.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwptrsm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpogtjh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alvcoauy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemdqeh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtalierm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jusdnhmm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitwqite.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuzejyh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgqtgvw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iybxwqau.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdaiwom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aidphbho.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbfehtf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2khaworko.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgverck.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcvpufp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2augngyar.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2epicpkff.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wftfcpqw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhvrqkl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgtvsbi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmkwsfg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tebaagbv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjyzwbg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wesnfnme.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rienfzzi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzpggbw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjryyat.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twiafpin.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsauxpp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaghkmn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snplgttl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhzmfz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spjrprus.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbphfn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yghilwze.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyacixd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixhpsvq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuywtbgx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwzkah.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjtnubi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2emjihhzt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kczjlosi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asnnqccf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zstztger.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfutqnxc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebimdfgj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhggmjgh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzppjic.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lnizhxrm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzssfnq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tymvkdrx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzwjpbs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqlcqlm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbpxspz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetwpld.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhoimyl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhweuyh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ziycxfxx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhzaete.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdtsdtu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeatqew.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nblwfijf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlljury.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzlnjnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tadejkwy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehunzfdb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nkltqpra.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tasmddxa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcwxcgo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yakaaoqs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eifwqulv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaymqyo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyfpgkp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqutrv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqrfztn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gnknskod.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnobvfx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnybhrvh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vawcublr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvijhda.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrdiere.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzankru.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzxxkbt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cgstlujg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbklnctf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thyccman.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeakmtpz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqywdv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbyfbtw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjtgevc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbuangy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkgfnhj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lndysymd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtxtnzq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoeritf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxellmw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeitnlk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjuyweb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbnxike.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wuehgclv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvwviml.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nupakqmw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2libptnkr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrpgiyl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2diiyvuob.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzafitp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wakfwndo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfmyrqy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qljnxgmn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwnuzsf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2navpuouv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhourxp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2expwqwza.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2taugdigf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeryxcu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmiuftg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2agzdlspd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2iygsavbh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jibxndwh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbjhzes.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjqljih.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlbbjtb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbwtwei.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2knyxqrqr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxatyact.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zelhwcrd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbrjxq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vnckuiui.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaqdpoe.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2icgixzos.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mddhanca.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgptqxx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2eundytyo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yinaxdsb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnchycw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmydstam.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyiwrbb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pckwekao.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzxelet.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jbydumlx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoulacs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2igyfeggw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvsbroj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2amiaasjr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2czrmgyst.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxgdymq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjpihpu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2okphojqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhqtycb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjmqspk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjguwef.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izqffdpn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wujmpudc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awfvqomw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxubmpn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llflirzh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjsrgum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgkgkhf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkasvkqu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eosenbfj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzxsxkc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyfhnnz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ulthznue.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2euaksdmo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdfygp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tddnfevs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhfaorp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqolrkr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdgqfat.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2omfznbov.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2etvhdncp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzkxhzh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcywshz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbkfypf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2opyzxenp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqzmpnz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdommil.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzfwss.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaehdpd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pymdwrbx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oekbfiqo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2puhwloua.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zroipwra.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxvonnb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dggjwggj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmvzsld.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvgqcvv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmiysnb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2obatgqfq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpyuihu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyrlers.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2glqqpztk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyknxvm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2quuhegzl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmnpesg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gorlwbxk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoagnub.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gsripeaw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdmslyu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbvnprm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2brgngyev.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbicwqv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmodbma.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emmuhejm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqobhed.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkzysv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcbwumw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzmptui.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nybugngb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhxbyi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2irevxktz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afvvhhup.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2liujauff.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2peptzzdm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsfysmu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2diiuaajw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgxmijb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jafpanxq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bopydmrk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2scthvhtc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2webitlae.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzktwvl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dlngprcz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzmiku.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbetffe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2krunqmqb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bqguzxjb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgziqwy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfxchgc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxbesi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhchvcg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lamexzim.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxbvwig.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2usxhkbha.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrgrozk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvqrup.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzpyzsp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtwseok.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnbevbc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzokoqo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2msujwhjc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeldzdf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qptknmqo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uifizkjv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aujwlirp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbbijhp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qcccqolu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bqudkafo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjwjhf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irriepet.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jeklblso.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsrzaxr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqmhevg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzbowye.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrhuddu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdrnwu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wefwjbym.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtangsq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbhnhec.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yfffilhf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqllwtyw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dmagsvel.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2paqwpahq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnbgxtq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxrcdhp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aglricfr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsokrgo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlatxir.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdphoqvt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2frpottla.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfiwteo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvxlnti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2idirpqwy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yimgtaao.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpbijda.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxejxiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolmnwe.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsodandt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpwucnl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgofjnn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpggqpa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfhgwap.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojrirwd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrdjjzn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzwslmu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmsjyeu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjzzoqs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jzishpdr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrrwtpb.html


<!-- 参考信息 -->