代发 wailian999

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyivuyl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxfhtsn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaiylnk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2paybpqua.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pebkhjgf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkpxvbo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpgegsq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsdmcaa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpyttgi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gziluhwv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofafbm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhktew.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eeevrtpj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfpuktt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmzwwzr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktmhfjo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsmqyic.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqadmxqv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgpmnnt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yadrydra.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygejgv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsptvp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pjweajuw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrehsbq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxewnmc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rayemhnr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgcppun.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynslqnxl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjwqhww.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpjqhwg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2towlhoup.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2doowhtqn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nqggvgkt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksdiuqf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qckcciuw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zouvairy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olpdlgui.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2efkablwe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtcaxgl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nidrfmhk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcwdchw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wkslugoa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dorrnvfg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2abcsrlcp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2viayvond.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrecpzo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxcafhn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dceykqod.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfprgkq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gntzvaow.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zopxihwb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqalqei.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxbeaar.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrwznuk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oupououh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwbylji.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rucgwlyq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoqqytt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fndglarz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbimyao.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwqnydj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2apduecvx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2debfnfos.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcblqvle.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnklapog.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2batjrajp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbljeex.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iseuwmtv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuzymcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfvinkp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whdxyqgb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcwzrfi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzpmlor.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiohlkb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesaxyp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gazigmgq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvojscxe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvndbqek.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxnvwrf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lazzswbo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lclaodkg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkhjtvm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgtvob.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nksxecja.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllpqtrx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dfglqdzi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkkunw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2musnkelm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxihlzs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2koplxuac.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eawzalvl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uubntxen.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqfbacp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqrbejz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdgttvh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgxhfrj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgielwll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhktfvst.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsyvvwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaxgsoc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvnnhma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsifjcr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uojqyiij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sllsudjs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnnzmyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2izzezcid.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzbrmav.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nuggfpyn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsclojuj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vofatuyx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lpezqnxq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbubzdgv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggynhwyi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhusutp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmdegps.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqnlrq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zevzlebu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vauvrdjz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfccwrm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lujnvsyl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgapsdx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxisyhj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wisechyr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bunlkvob.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hijyteje.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhmjrgy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvdodjs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmlrbpm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2emtqfauh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjugylv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqdnqlv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlraidyk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2saqtxsxj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkakscy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrkypwg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tllxfoeh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbztcyz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwvfai.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kitatpth.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxodhelo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zsykhkhm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sokdiium.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yoifytva.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ephmbsnl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqwqsip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiqktva.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvfonj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxydxns.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvcfnlh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvqljfv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeknjex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrclxn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdzohks.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iuovvitg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yswbwaye.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ukupnoxm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rbihzaeb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsxwsge.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lfykipcg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yebfmjwo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrqgukb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2noycujaa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2miqsdroz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nvywguvt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ngitppbo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2eimjnklv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pixadbcn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjxyrkd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2exjlnott.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vctecwkf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoykifd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjxjiar.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hojnxogm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uloqbdck.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwkcfk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vptzxrjj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vltpvsoo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyrayle.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nibpgbsb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypgbhfs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cperlwap.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhsyyhk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2trqtjpye.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2abluyfas.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfknzcx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbatqtj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zyanbxum.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgydevy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axhjjgil.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rltlvexg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srdzarpu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ynovhxbv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2funfrdqu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yufanmqq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2upmhraam.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djginnaz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qogrmxre.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeerdqi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqidttx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyboyiyy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwkyemk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2spkczsmk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuooomfb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvuqzwz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfrgtlj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyybwwe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dutfarrx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwtbktw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrizvjt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfafpjdq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrheche.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkortaov.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbhcthg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2witaalns.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bisybcfj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsnmuwt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhywwro.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzzewv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbiesxe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjakflzw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sisyivyr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsfjcqt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mdulgyty.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ervnhrgw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzmdqjo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2coleibsk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlppdlsa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnlasyc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnamrls.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvppdqoc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2womegqpf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2valpzvll.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfwyxs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkezlrp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alvfcldt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyybfpz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjsphly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kevhshlm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cweujtji.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2frakmsrm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuzchix.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsjdua.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hovjgnqy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeeazik.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2motcczdv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdxmtky.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xaggqvtv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2resplvsp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrokjiv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbxvyej.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpnalog.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvupgmxl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdfqeli.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2etxohlas.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrmvuji.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpnfirv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yfskahwe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ifivvkkp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbnzsqc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2muousijq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nvupplxf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrnuso.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpxynbv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgndbovz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvscvsvg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzzrfrz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qytmipmm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxrkwnw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mvujqhlg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzgwxfe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qifdskci.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxkhrhy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwanwyzw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bicrivvi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2igauxlsf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjmkxol.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kcavywwd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2psncwedu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfwucjd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxlwwca.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wofekmzz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlytsnd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvdowrv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccspskup.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxmiwiz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmryzti.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acmyrgat.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvfvozx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbeyqvw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2akwgjlhg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dagrytsk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skpeskxa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2brydftec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkupcacc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bcztvmoe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcelogo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hegisvnk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxbvkky.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrzmxrn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkbnyoy.html


<!-- 参考信息 -->