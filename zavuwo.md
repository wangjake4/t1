代发 wailian999

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpkqmnu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxibjfwd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxlhves.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cidtdoee.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pccsswie.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dftqdyzn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdpyecn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aohhgzyo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uymrorjt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdyxqep.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2utkcvidj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdxsfad.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyblidij.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojodqjl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzbewuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2unktgtzv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoutyzg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2skhaqkjq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fkomnvbi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrejgqo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iasydetr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnbxqxv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkgybir.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzolrsgn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cukadtvw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbeigvl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuzxvib.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdlpqpm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ithbywas.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szxqvuxc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqwuehj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmckecj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwppbetm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsghhvu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bijcemak.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhcmrra.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bijkxvlo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udyagmya.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2menkqjdr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eghifxqn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zarfzdtw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmibnnx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrfseol.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmphguw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzinfurv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoyyuad.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjaanev.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjzmank.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxilbuu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgemnxi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qonkrwbw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2olipriqo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2imjgffdu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdxandk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwiscbp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqlnalc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwceuvst.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2attplpql.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2knslfavw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhobabg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fehrdbsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtyuerc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2btvvxuyg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvvwmne.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rocmzhbo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmdpaod.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elguhpxx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xscqpoii.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixygzrhj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myuiggbf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqdepvy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvscfe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nevltigk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhehvv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssifnvld.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dggivzql.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuaerqt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zkchsygy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqkqkdm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyzhzlo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2psxieqxb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cshaibhd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkztrsvb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unbxfurj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2knznappl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopwhow.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaxotsm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmssbdx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbirqnbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqvakvj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsqliqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhajncu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gujqnnxc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlmgdn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzcrbem.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpfzftq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2olfgsfht.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxidxdn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnfsnlk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqijppm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mklyhris.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlaudsr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iptwgsoq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2agvzxioo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oedufsfq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2glunrktb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhrdayp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2msntczsz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2smviymbi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrxndff.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtgjhfd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oanfbcnw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvcijnf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwwdvov.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uviwovks.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qepzthoi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qybyoozz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2acftrxjg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sazschzt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhumeyjl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2alfwpulr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyzkdh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrconub.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cizlymrb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2issyrsct.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfchhnl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fuarnmod.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgspocp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhbawav.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxytqjwt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wscbjjpu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlkkxgh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyyhglm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwhrzz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2idajglyq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfxobpd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihpolf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2agpunboa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2scyogxwe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybutpz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgxhagt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2snikcklc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hfefzqna.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsrtawa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfvixyf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsaqgtb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkgxrr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcmyuqs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fspdzgos.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hztphpni.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnjqnia.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqebqpz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kairvdkm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aklnfxhg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbrzusd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2olbahbgr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2upghhqjz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2auzftrxq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nviwtipb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwohlfei.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwlkwqe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcztuiag.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrrwpu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrekyfv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sfympodb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fjejfwtl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwebeii.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdtvjnq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hffwnjao.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hivrrvoj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkdzkxt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaekahc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vincbpcy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwdrzla.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pzibceld.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oefflboj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhazgyqf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eewltlwa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxokzisp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgnnnim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxinhki.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnekmpq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjhvtbu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2thhrmrjt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtrafor.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2okyfjtis.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpurtob.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmuzery.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2formauul.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fabdyqit.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcdrhvo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmdyvhz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mopvbxdd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wniygllo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnshapyl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fintcylc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoejscd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvfqah.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2glozrhuo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucadjkkp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2asjehlnf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbzaltq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjccioq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvfiscq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2krorfvdo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkzdnov.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdrrzlh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtwpnru.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsrjjnj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwcptlb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxxmsm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcuiarv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lnayovsw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnhbbqk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrxytzp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqidflpd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cewbiqtt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2skbjuqig.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uflsonyn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cervythx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqtsmit.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmerzmay.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwgaesa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yirtcymb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nkypsxru.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzzxxsh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iojjulgu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkdtbuk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjjcmox.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvjzwy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzeszes.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrocrjcv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gteydbuh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zugqbrnx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhekajps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjwpcvz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tloitdck.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvckelt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbryfhx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaciwtx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcqnnwy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uliahjyq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzimgee.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrgolsb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oeofbyxl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qdykxbvo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kunvmvhj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2auygtgce.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqfrsna.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoitbzk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkgoent.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2snufnzzq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbbgjhg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zftkjiyl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgzkyiv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceejpbkg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iimoaxtr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vysnqcmt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tstyhodn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhmbfkm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fyievpkk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iwipnkdz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcsjwb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2boslnyqx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dexxbcft.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eowtpfnl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjxajip.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glabeeki.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyebtns.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2txafsgcl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyablha.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdfcpn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdnrunv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ofalnuet.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxexcsh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywvmwxe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhprhar.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rlikwmml.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgvjiye.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcxtebe.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2knrjttbr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmktrmr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthapxw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orbroyvj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjxnwq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2idxmzkyd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sawpbxdz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tocodync.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zndnfhkw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gwizixxu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtidvlcz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdstmfmu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twwzkbsd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfxkrit.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pccajjcn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdqqfux.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zyucgitx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdgnqip.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhsisyd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdlghme.html


<!-- 参考信息 -->