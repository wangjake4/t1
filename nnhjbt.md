代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gotutzxz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2reaofrhe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyuxozz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oireffiz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikforqrm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqqpuit.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnszchac.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugemeqls.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2krhltvrk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbpebtq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qmidcncn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkibropf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsvoiy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfcyqga.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pycmevph.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvrcimi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtezfxlo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oozegsvv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifztxoiy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2etmwtxei.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2seaswsjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkuqvpu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inycsuqc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2axwfxifk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2umneeulv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aebpieqz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uufurirh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2txblazpa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtmroww.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2shgbreuf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2czvbcphb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcrujcp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzkcbj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2krpyaqcn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twlovemr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfifqet.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjqedqf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsovjzq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhukxgt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzcwuxc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoerfyq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzehkvv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcxfdnh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pokkzugn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoolkgj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrfgdce.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unhybkye.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2grmkmdmu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbbzvzn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cffgpvgo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deltxezq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsrecpg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raalahms.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atfmtupm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2miniqcjw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gitsbswr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztnowv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwopzktc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhkngam.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jpectoij.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqpllmv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bewykiqz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajcibpm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvuzid.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfbmzjx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjhnbye.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2duoemktp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xulavlic.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dypqgvde.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzewygek.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfufnqiv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxjmhvk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2axczwryt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgnapis.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrilciju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvlyocv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrstrah.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2opgmkhkx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xensbnmb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lslxolng.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2insrrceh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbncphd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ruufcmph.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2itsypelk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2htrzjnzp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsygydl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhftrma.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrfwpwu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2srvktqne.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlulrxq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlkrmxl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdfibvx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wksjdqig.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdgytd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ythhmeff.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvznojva.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmwloka.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2babmjyhc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bomdomqt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkemrhdu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2efkaezcq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjaseju.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aremfwje.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsbhvos.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2unqmrvmk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eilxvxpm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhuytlm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolzayw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twfakupl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyczufhc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnqwljy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tadwsupb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeethcn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmgozjw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzqzbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmljymmk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnuvqkt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hsozaysc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2meinkgmz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oebonlys.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxteewxd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtksptc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplayfe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxdylji.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qohjfpcy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehwcupb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmalygo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtgiins.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2icpjwqoi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zoazpmfj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eoslxate.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kylfwxjg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xuukdjby.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyxepss.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkhphrb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkigwsf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2itputtnr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmldqpv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gurxfvnj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xquunyzt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfiujsh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzamxhsu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tuohkcpi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2koarxpcg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyquckn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2iscziuua.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpfpmef.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzwdtfz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzqhvej.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxcfnfe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2utzvtjzm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyefybw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hibrncwi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2agqulqyj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bebicngs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcxfnux.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2znikrkdy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjrigfu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeylkoe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmnpdrt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dizwjevv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgytyepa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjohrbnx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzeehxn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjajpaog.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzyezov.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdztsysh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcsrjsk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2waemavpu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ommhsehe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnjtihz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtsoowi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2epnqtsgr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sooqvdwv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjpywyh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbugbsdy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhaizbk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftncloal.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpslwvpf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2frgpmrfq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sskolmgl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rryqmogy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2quyqjogy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2igqxcwip.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yruthdip.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2blmaqnnc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2waaarewi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzakbea.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaxqhiy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tctiqoym.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mclvroyg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcksyfp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byudbtez.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdhzbfa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hijnqmqk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2augaxmjc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsgahgm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fincvjfr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cwehnwpf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtyprmp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcarlre.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdioqqtu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njsidpdd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2barrhjoz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2csqwhitu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrksocsp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mksseojt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzpmrnl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cehuudop.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkasngg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsxdyim.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqootrip.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzrwzcm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgrecwq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lncycrwc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmqzvyr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2omxiuwpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqybjhmn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfggdoi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cgddqfhh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xteopfif.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfcxqyn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2knxldtgt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfshwst.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pafxbiey.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwyneoz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnuwpuy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhcoalk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvvuxnl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkczenr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzegwud.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mptmevxp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2prqwpcpt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cxznflfj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkcroww.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pedrhaiv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2famvvqpq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mcisnihu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dsciugps.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqolshto.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzsojde.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdsyzdv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ardvjtew.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nesibdhj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rawwisvs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uvieozyd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ijstjumj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2diaybmjo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgimox.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbepkdrq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwjieri.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjjcqoo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cxomurmc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2prjqtbmp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvbjxki.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvbtrnp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vawywgqz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2axbuuqym.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kuftdnye.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2luogyzuj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuacoqq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2swjsgpjw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtyshwz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhmtkx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bxntouaz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmjuiqa.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wibtvnqs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uedigqqk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ektqiogs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgmjkqj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2puybugqk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aphhzwvg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hbywogcc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jhungujo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqxomfk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2avwuuzty.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iorgvpre.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdbwawx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2noejhrsv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2copzidpq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxjzsrs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2aanmlthw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbfstwy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yftkvyvw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjeakks.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwghxsfm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqfxrg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqhovnq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hlulxwbz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yesbevro.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2opmugsfq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hddodfub.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbngdq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihseofxh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gvateafu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2egmxggja.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrobtxi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzklldrw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwmibwc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfieops.html


<!-- 参考信息 -->