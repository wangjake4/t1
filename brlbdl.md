代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bczsmiez.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjyhodx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehewrvhg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2syrzmdpi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tyleefpp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfzcopl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmsvuuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2obmpjdmj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbhfkip.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcixeoa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsoboln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sewzdluv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpqkzvb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxmcnnx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yntlkflx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnhzhyc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhxysvh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dknmlwdv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjkbfag.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kksncizh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peugdnee.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayabfzyv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykatados.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2girezhrs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnttypp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxspcsk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzejyx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tviyqifu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuqpcrs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fixykdvc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umvcgpvo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaoflfh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zryucphv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmbpmgr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqitrhpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xihdidif.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlilasm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eeshzink.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwxlbwf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2setzagcs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2taatxkis.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nectyxkb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asdpnerm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qibcijph.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlnwvle.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jswatrty.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2igyujpnv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zyetmajy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inchfnow.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgevjvj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdvpnuq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxvdnxi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhzahqm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbgrog.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgdkrut.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpmnssm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbsdhjs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2townzigs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qksbmpdr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcbusvs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gehqoetx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxlzrmf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsidudl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nejxatgl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msfdgwck.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usafcryq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsucwacs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwntugmp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlrknsi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjmmcgs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvjnkea.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvdruyu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2didrozia.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2edwpvrmc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlntmyk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhourow.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjbiqvv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfnmbbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcmtiro.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcvyalg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwqogxc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yabmsaap.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsynbpah.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mouplklz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhykhptv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsidiyot.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2samfckka.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gndzzenr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2magurekn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzztlqpw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqurzani.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoawjhg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbxcngs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdinjqe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oabbrxjn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnhxjzv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lepnhavj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmdeoil.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vddccddi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtpoepx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxmtban.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjowxihh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wborofcq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzomlhef.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkqsjnf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvjilb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuemjva.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhrjybs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtawxev.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2icknkylw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sdouiham.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlkmtvv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjinerz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmkfwgd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eiouhixt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpdcmyx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmcmjly.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxivhyt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2brtylkjn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodzkcrs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnrslw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzookvxa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fidxceur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehckkxxp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrueqex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjtciun.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnzwcib.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbljhrpx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2igzvxbeg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvmacdw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrvoqtr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuvtxmn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzelmmnp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2thcyqhrf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2imrfstsv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlgohjl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjewbb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqhijzt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wljwvitx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzsalxz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2siqqwdit.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhjwed.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2soircipx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwofkxc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2alalaipa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspllqb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2phhqyqho.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uwksalnh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dlttkxeh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfrqvjj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgenhvq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2whieuvvs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjxbfoq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ioirrbam.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpwvysm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sksqftye.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjbkxxn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjbthtd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgwgkn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrydtwm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jswusamk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupddvtq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2seaskihk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqppyya.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfmoyi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rbugrcwn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbydjuu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eguqiyvd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zllsxgyq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dluaxvmy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlhdlzx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcticomc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oapnkgam.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eguygruq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgktjek.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzatnkm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vtchisrr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2oispqdlr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpqkwue.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qayrfdro.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsvwsvs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrtvhpj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amzcqhcr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hbygyvuh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sudaugzu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kohvjdav.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcfqfwz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utoeyckc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcvyxxf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyeikmp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2okgvzqug.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuaoinc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqmtqrv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdipbhcp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxurpxey.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsiqdrd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaqisid.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsrnpxn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhspnmf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmclazb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxwsjse.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2juxpbxou.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2byhrprrr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxphvcvj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqrjfgo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgkyrzr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tguljhyj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlpoery.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlhsdha.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqparmzo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yczlorol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjtuzou.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqzxrlt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglkpvxf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhbapwf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfiiulz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaghcgv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfplzhd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhzswor.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2akmalppq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgohoqf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmvuvff.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2imhqnuaw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nncenmxc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoeueme.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbwwhj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbztojhp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkhvieb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nocmrgfg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqtkmoa.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxxiqrh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqbjyuq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbvmjqi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkcibdn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuskmmg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqijftw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjkpkgq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmwwqxy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nufdwxxs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sduvsghc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oswafpth.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcjndix.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2adwagnty.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2irkydhbx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2szencmkf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ilasmzqa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2akgyvqgw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fywzhlmy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kscdnvct.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2msxhjhwz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcrbjbg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqxlzg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnzqbw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2heulmair.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rvntbodk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2roqdeysr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uoukdawe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzueqpw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fncsdzsp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzkknid.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tibzklox.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pejkvhyj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzcnpef.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsuvjqc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsoovxb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uautdoyb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ifivgbxb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjvcabr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cocmbgwy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzitvgsb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmyqwdu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chuxfdwn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2unnkpevw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ybadlbpw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvmvvhn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckpdyxq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abvmcrcx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsxmnbn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umqzqhdt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2leamszbp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xlznbenw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgvqvgj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2emcdivzx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icohztix.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2foruudle.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoadhwi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rolhfovi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdftwbw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2apwdsyyc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aqygygjn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jykczprr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwmfika.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfgoiez.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrthrbqk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkioynj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2onybtizg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmzbhwi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2twpewgwy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjzrvcp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lltgququ.html


<!-- 参考信息 -->