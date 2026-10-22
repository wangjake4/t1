代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ancuokmy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmqydhi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdujfihn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjorywvh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcbzzoo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpxjnxy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrejulz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpdzliu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwbssqd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjjhnva.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpsifax.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izmicuvq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2meweggnf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoiurwu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbouvgi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aglppxqx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxcezmb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxttlond.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjrpyvb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrygduy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wpacebvl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzvqqfk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwzgozj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nouaoysn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xaojripg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiooojtw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xppaerbb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsjcrsu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkilhmnd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2khbljaou.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dianehpo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gubihgvm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxloqoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnqafgv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeptymzs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsdmjmz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tejlkrpl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmobvcfr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnknccgs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwupuy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jtddzonf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ispszwlp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeggzkj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2onclfqee.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acouxazb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwtwqtm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhaqhzw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2quzzaktu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeprcql.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrelmbs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwybntu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyavmiry.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2toedjpqc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywnlamv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqktaivm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxhxacx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2whembqvg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswfvlfq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogledntt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoqccpn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbuswnf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiklaqe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdopirdu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgfxbnu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmvaouq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrggubi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdenqdej.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzcurhu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrqeqna.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmmxunm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzvmgww.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghxdzw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaniztib.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdwvsdl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxywuzjh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zngehorb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwzxydd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rllleaxi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgbjlwz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cekvlevk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2esvmanet.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuizwwn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cychfcdi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiaswkw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeafnpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sikwahez.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuskqkab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnewkdhh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2esvsgnxy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gphgmxwg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dupjsewb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgadsvh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyprfix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyfrpug.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqzptam.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rarsjkle.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqrjsku.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsisnxg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2imafpqlt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgdtahp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdrotvs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvskkgqa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnuewbm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oprjwgbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaudgsc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyvaegq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtszcak.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fambhgbu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2esxkjzhc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvnisox.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoursog.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdocllrt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqikiohs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrlwlqh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgfpyfp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqpcmto.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtxscjt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvnpwkz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqzyokc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vibalryv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhhjusd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qflhspwx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2npipyfag.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmzvrgi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eefzhtas.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkszflbb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wozugyxf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cktewkeq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2betvtggc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkqxdvv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqxgyeq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fudwgluk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmpthhq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxglnv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdadpyn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwnrujp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2liphbmzg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoysiph.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wygflyzn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxvnedp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cokapxpn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyyhkib.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgqjjnk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2osbsnhta.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfgtrfd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2auzytrez.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcvwroa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2islmmhsl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrsdjn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqkttv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kztztiie.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrvtryi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlgfqos.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhsmsi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dpullrur.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2phimiqhi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2huryfjyk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyynpfxu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nimbogaz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnyjlxi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cmikoypv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgrhcxe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2auftmxqi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qavaslsg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqzudac.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqhklyv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwzasey.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuthwwc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qquchvmu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eebozvzz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnkcqmv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvpmvju.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rlenixru.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtztpnr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmymhkdc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcfmbto.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awjysxzd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zahfabcy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaudslh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdzollf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuzzbem.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2samchbgn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsewooh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ratysgrd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvmnwrz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mltiwbmr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlbrykn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quesecvg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuzymtx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhvjpuf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidgpsf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtrcfda.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uoihrmew.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2beootvau.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxoguto.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwphkvmd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsjvmpq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyhhlxt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoxdplc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgzljkm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvylbzo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwcwiix.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwimtlh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyvnyuh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwtfvmj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiauwtlm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlqlpcv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgahfcyf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdoxhva.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2skfxlima.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxsqplk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gemvbysb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbbcrrk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwaaszi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orndiobz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtwlokm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnnetif.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smduufps.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2juxgtgwi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxtdlog.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxpntp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2idpjwjdq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2opspbckt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2txstrrbk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2taofyinf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sstftacb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqfhelk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxcjooe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwmvffl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwtltop.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2seheneka.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2trbwbuey.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtudvkrs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2boogcfpx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bicvsmvj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiboike.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfawwqg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zetwgqwm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kyynizob.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uimpwxra.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kpryhvii.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zislbciy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsvukyb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpxxhp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ejovxkwx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vvduldca.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jzypvhov.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vivcuwym.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kldhflln.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcaavhc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yyslmbis.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2whwuvpfd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcmhvs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qodydwdd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2suaywdmu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvepahja.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohugqh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vmudpdrv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vudonmfo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljunzg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqugrnh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjlwjuf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjqyyoz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvsjtgo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdkisuk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvgbbbl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbtkneh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxqndlb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmpyhww.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cofldiqm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iijresul.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hubgmakz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zutqtxwa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvdghkv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyukrklr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2racppuuf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfacyiw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fbapmhdg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcirdfmg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqgizd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzysbzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxngzjdm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2irjuilts.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2asqpcyly.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaeiyja.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxmpvfk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcvasej.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxblpzoc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtpzlou.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvendxs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2skvhsrcz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejugagnt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmhqzsm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuqlbaw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2krwfcqsr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wytbtxhn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhtbjcw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxhfdmn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnsvvbk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwayjbvb.html


<!-- 参考信息 -->