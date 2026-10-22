代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhkpsvh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgeikul.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2efqwtgxp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdbhrdp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcsnlel.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjbjoin.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdbpbst.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2khfjpmkd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxoauej.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskpoaai.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzhbrmu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwyzwrx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isgzessl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefxnulw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wuttmkdk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kadpgfbx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxjfsef.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeguekbw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2naprsdoa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2agwvralh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkdezlw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrvutlu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2glekvnnf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxigjax.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lecpmqrb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgigvyv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvpdmck.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyxskfa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkssttq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvgejfo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnfynrw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgotdxtn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfcqbef.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pihwuipy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsghwke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2soeeabmz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbfxlpq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxverrux.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yynpsayt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoelhewd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzuwayi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwsqhdp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrromfn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzgcyid.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlmpeew.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgimvjqh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkypkygs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjislsq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phitpfps.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzookbgx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiygcbj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnsfhyv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnqzgom.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ighwmkfg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbnmcbk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riufgtvw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcobpsf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhkepeb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yqknwogt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rborevku.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ofycyilj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscthyd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fztguvdc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqkijh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2telxggsb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlejyyix.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tosdmqfx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzaxewz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yafzopux.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhgmoho.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkmwxys.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyutzsu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2crnriqpu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbqsmzj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfezbvyj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pautcpeu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyjlxms.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkipthw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbxyqkz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uaneuckx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbootaxq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eymcuduh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnskqzh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oygbuqgj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yznwqdof.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrsagkk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhduxyy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ggolaovp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvrfybv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqfmeeh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chlymuhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujshtqys.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjcloii.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cochnjif.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfmpvtc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zinqbepm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2znouydnd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhixmepm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rlraitxb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklxlms.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbavocv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvuldfs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrssvwk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssumzadv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2frykaiyw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcguixbk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2luovigaw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwduwmw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2chejpwyu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdiohbe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvvbfjq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrkqab.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbvwmno.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vysuutuh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrtkekx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwrbtn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yajnaaep.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2usehrgen.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzajirwo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntirjfqq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nbexhnaa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqsiqbm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rluvmbjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2euvnbxbl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lefdqlcx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqxhbta.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rboatfwa.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjqqoqt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2amluwueu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqitjpbj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rixtcujz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlftxhrb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bzennvzv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tixyibdb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxahmro.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqorltrs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfhpqff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfvctox.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytruagwo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uebuthlw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wjllzgqp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlhnajl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cljwfkem.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjlsliz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gregmzzk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnqlupj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xisdbyne.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzoreyz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsxpzsh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vurhckzm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjveexde.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtwzdkg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tiysedxl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vnohkehw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xljnvsop.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcooaqq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiebdoz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfiwvbu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvugirlm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaivdvv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnovsnv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymaozfy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhiqsbm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqjsiay.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhtikwl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ywceuxjs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbdojvz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjyuqsu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2soacmjcg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgehjkcz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtgrtzh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asinakcm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lppekmyr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuzthge.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqvddps.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbacbts.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tgacejcy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcysqvhb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdghgqwu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbqfegk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fabafxrk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuykoxbb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qehamgdu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtnkqxp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2calqqxiw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgnrew.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqzmchd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjkgijm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2otohfhjw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufokaapr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzmrxlx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rljxboqf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbtotiv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyxfwq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onymgppx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwkuwsy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahlzgq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2agrvfwhv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmojji.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2smwervqo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxyhkm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vivpdjkx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yadufpzi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyactxdw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rykioztu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyalgzts.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pityashe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjyolqg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpiybfl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgxanae.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbvkalv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2svrjwvut.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjithtj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftlqhq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsvjnwp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxmxean.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fdexiztz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2duwuriyd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uaicnygx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglqjvw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zwebogag.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnvxapo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzrvvfi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwltqudn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dwceakli.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzyublf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqjanfu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxslomqg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdipnhof.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoakwjmt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cksrgtrs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2iahcaoko.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkkwjjh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hspbfdmq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xosttzgp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cetybqgk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fuciyumz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvovmfi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icuglrwr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymunle.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbueqpx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcgtgro.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqdfjcz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltucmwja.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjffuus.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtsjjjs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeuwchn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgfoisl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnjdjnz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uogswary.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nubkpigl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzeibhw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zzesybbi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsqgfbt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvvikkh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2quqisktu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2juyawmdw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeitazxj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rnovqdsm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2oetyreaj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2npjwtilv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ereumntv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2guhrzklj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnvzvkf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2huyeoxvs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxdrplj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dtffvayd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqobiidv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pikpbrda.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaokyup.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vemgwpfk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhcmhwp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbhwyjd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtugvle.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dcntpamp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysssmrcp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwttqft.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jgocerjw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diliahih.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhungdyf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iaosnngc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tenkcmvq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwsgrhy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkemerix.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvcvzqn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2evcskigf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdybspa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2duhbizsk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2laqsojqc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwcdrzu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqweggbz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsnnozx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2byrrzgvq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbtpavy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tifdottr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeyxedi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2satbdxpy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjyobem.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiyjzxb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cudppbpg.html


<!-- 参考信息 -->