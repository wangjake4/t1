代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbkolfw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdejkjml.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2asmqiyci.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfccfpk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnenwfh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sinefvlz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjbdpve.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpvajao.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfxsewc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuismcf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owvoeeie.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2utjlbfkm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhfsspm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjjufco.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlwdpay.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2quzoerto.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebktjuqo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvudlujp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzqkagr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfimubiw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqkuron.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wluanecn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uabqjvji.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsvonka.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvxtqj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdgxhpz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpnlisv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mambeaug.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mljbywxl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjrsjvr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2arjgkior.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbfjxua.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oelhsfci.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiopysc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmujay.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uralelad.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkhkic.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bekqxbuf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2awtshcvi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juxbcywc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhnrleg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqlkcpi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yckclkyu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsohqtmv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trgworsk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajpursy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsannku.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoykqqo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xllarurd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gdunbqfh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgezfmcp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrbuesn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmxrbeg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsvcbwf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoqzlan.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjumswu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydaemuf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvumbfl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yagnzjjh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbptnon.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkrzdmm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvsnwwn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2drrmjwym.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxowemt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpbdkwi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdnxwvv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygclemli.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvdwmwd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmazsts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpdmlou.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtaibu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awsaplbt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxfzyd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlrrwgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqznxa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uacjzzqt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eczchztt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2assxqmqu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hefxvwbp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2irncrlpm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbvjzyo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjboglt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2csxrfjgb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sibsyarv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kltqbzvg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaoosxo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtkunqt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoznfeq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfsfqyh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2trubgqag.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkklnop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lixhitwr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktdkdp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxptlhq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fphrsjso.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2remvabsa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2neeqgfvd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jispgsoa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pydsvjyu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtymebm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2chfejkku.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eewbeojv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhxhvlt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2apyafwjk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyfafys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlsnxui.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtpywob.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otaefvmz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rizcxgwc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ualqfgmg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mtklqjax.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmparuu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2crckphbe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlyvtjm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2helllhiv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkmtos.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afmmdvii.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jptwwlkc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsjfbcr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2toljqpqd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwcnyii.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcjzfta.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hektlcam.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifkiikv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyglzec.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfcxvca.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaydnbgb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tiffhfxw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ylznvfhw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gcihlcgj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2awtyvfzz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvqhdmd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2krkrgglr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaxxnbr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvwhrvq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkiudsv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2leloaruk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kztiueaz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkecpcb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoylrtl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljysnzvl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yddzeiaj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozebvkeu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcukidei.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gkslqcwo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoaowbi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fymemtoa.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkbajsm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxoncph.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlzjkyk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzdmjlb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyaeyzm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoahbss.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vfidnsig.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yllljcxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdjyzk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkbihdm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fccmgbus.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tudupjjt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaondqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhpfara.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgqmfal.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rboljcgn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2drqunbvt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuatujb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfrszuz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uxshsfmv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnowvdt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2musxaumr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2snbqctcb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2svmolslp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eydylpah.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rbupfqkr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtewzth.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkkkgwe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2omuzfsct.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wnivuoti.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxzllgd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jytbeths.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwndghfd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcwmzfr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oysefvqs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzqlrpw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrusfwp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubtobx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjvlaj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2agosgixh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoryvrfl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhdhhxd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwwsouy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aprbtjey.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjflgrfp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfbenoh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrkvfsn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsjwhaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xleziavz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tghojoiq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgnzwdy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwydjsv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqugimvp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sqotexpf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbazpgn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxnvqs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2arfqntxw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vgohgenp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwphtl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsivsra.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqokzk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2luvutvpb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvabvaar.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcajvtk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqgfood.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qizdyhnx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjmoaay.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdzexyr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtlyhnk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2drzzuiug.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpytbvh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kksrkoek.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hldujbse.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2inmqkntm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kyguxqkd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tecvlity.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrhoges.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuishlj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjqbpvl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2riameija.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jsktejof.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvcwosv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eypsvsvk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnsotwy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyyihlw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kdphbqfi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2krfpblgz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uuecxllc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tubivghf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uyehkktv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlviodo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xelglqah.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnxhkmx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtmveru.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vldeswna.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbeekw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcivwkl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcmgptl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yauvwdxg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxlzkjj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkrgctt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nrewrxft.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdcwftq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgelowih.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfvackg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwfjwjf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgxhvvb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkqiiwk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfecjbif.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ueykykmu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bwemkciq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzvhmqn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2podalbiq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2stkkirwp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aestbwgd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzbnswo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqgwaph.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2enzzpdlk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjdtijw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqsfxrz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvklice.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lczjvjzs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dawdzkwd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sqciqfbp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmqbwjo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvsvtwq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2odspivrv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpkhpsg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2unbgqhfo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2puejohha.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxncdjh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fglvgwen.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nltoskfs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsntjux.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zttxnuth.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvqortg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgrmswx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtpqnrr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchhaxme.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2efyzswrg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2axvsbacq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvigole.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqivxnkw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitppaj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcvkmcg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnmzmjt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtoukbf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kjafibdo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouugrybb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ktciyxwr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxodzyn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmftoef.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbazporu.html


<!-- 参考信息 -->