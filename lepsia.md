代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bywjtvrd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mabwqqvn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aswaerzr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2emdpitym.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uctrlzln.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsfhtlu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuxhwit.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpkupsq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcjbhwu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpkpxli.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnkptnh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdehryym.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2orwhdxau.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyxkzbi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rageyidr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfckhse.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cumtekkd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtamcawh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yabzfczw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2erwnnmio.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcnwsdm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdgyrrl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuovwjzw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wukzlisz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ickdalwc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzxyoz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdylno.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bieltjyl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yslemqad.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpoatwb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgnbvlf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2anbvcgsg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjplnqoy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmnzwuk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtrikco.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinbauoc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjauhkf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujpbcqn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvxfngd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcdzgpu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2noehkzwz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxawpz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkipcmwn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlscrkui.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nisrrbza.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vijfdrvy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whxauzcy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhmgrnz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsrkboh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gtackvvt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkxzuyc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wssoiwxr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwbuvgv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdokshqi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmofui.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbcezkv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrknsxt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnuekhu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfufhc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbbaged.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmscwqh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuhcjte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kypsyibg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2grpmqhyj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfvwipx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxabgne.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbiewhn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbkhagw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuykwyvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtwlwvm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2roipmodt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeuauch.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2btnhoeiy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lapuggym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2chdqnrwb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwbgpxa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdptcwy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpllhhkn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwksrnq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtcqory.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaqhbil.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfhyeki.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtxatz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxxbieu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2khfpzgdv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzylyaqf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxnrbou.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aolphdqr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdmwngq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskymvlz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jejibdur.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkdwhqy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgjewcb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwohsnyv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2moxzjuno.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bguonfgb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzxbcdp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvtpcgt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vazobsid.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrldqlp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnikcmds.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yevpawqw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmhpckd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxmere.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlrekig.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxideupl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2neovemax.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zonoxney.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhxgayf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzdnmps.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgevxtf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfqmsee.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2urvfixpn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxgxjkk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2byfyknxn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrpcqmy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqksgiz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxrkqbb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2szbjisfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrlltbj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dicwrqmz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhelbuc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bzabfzki.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrocebuq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xemojkaa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxrlctm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2setctcel.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvggtgn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2puclreoh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnkpkyj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oumqlyfh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxkvstp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmjymi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbawtjz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fylinfcx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vczglked.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeucxue.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvayfwyb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcmiytf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2keybucuw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlnbdsp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyqfmqq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yocfdnai.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzjbwwe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmykulq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvqyyhu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbjxcqn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuvqtgf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwjrwiq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqokhqk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2blzyxqbz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcbxpru.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wemgejmz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2neenuvgx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzwybmz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiaeetb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2moyujfsx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2avldmysb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qowqqpcp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dabakvjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uifoackd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlcdvnt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnnfhjy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhwylnu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfepnxh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bspdahri.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sddnyqzv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnzuhoc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2avxsursr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ibszuyve.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdtvakp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rykqgkbc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiyunfo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbghtghy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsxrzye.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgafwldr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2deppctjh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyuvukk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaqgifd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qizhqhqe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2syxuowxp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdweexn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqgmgsk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brvrzhdh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kilwoftj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbnkjfu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dqijfnyf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyqzeev.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yocdyvfj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ankizphr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2icbyxhqr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcofkuso.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuarcyl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwpandx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmpxcqm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjklgwvt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvmojxp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfdnrqv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsehmtb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sllwkumj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxwrpzo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkthonyl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcpuaey.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyjpsql.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sjonvjdi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogikxkwa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fujtoiws.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyxqnyp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2upamiysu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfpmgeq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kruepilb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnbwpj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhwrymv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2byewdgoa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2giavdorz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbimpwn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aidzmzko.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2czpqpari.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaovwgfm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdbmkmz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsdormm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2djdekwfl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hmffwmdi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpdreih.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxmhssb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2auindovt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtbyfgb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2levuloyy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xbldwbok.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkesuix.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ywveklxz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sakcccin.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2coykfemx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwbrkpy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dohcwmrs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2piinyuiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsfnnbw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoabckl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiyphzg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxzgeo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqwjcev.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaulmng.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpevrvg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxxhqx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpvdrvd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccytol.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrcadih.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbikjrlj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fziuzjgc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aowdbljf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2utphazsu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmlaksx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgnzmpr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxfnwkm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tidnvzbn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpqebxl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkughih.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jichtfgj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lganurjw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyijpnrz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjklzqn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2owhrhzxl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atewcobx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgtgfcx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsxexrz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsupjlns.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2drfxbcfw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmogmoc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttlsnm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cykyhjmd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnuewlq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtkxgux.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azliwlek.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xckvbeia.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfiqldg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2szhfcpfk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2brnlmjjf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhibnmcu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2neobhmie.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgioplqq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrsdxwg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugklbl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hppfoodt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zveigiut.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkdfbbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrewxbt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwebfnz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzndzdk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2awxrkehj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2otgszhoi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vinxgfeu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnekvzh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rerplxck.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iydtpdqk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbqmjlb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqouso.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2capvwxqt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfftixvp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yuongaaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2upijsswf.html


<!-- 参考信息 -->