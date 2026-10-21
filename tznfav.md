代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtdrksjoaw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtjtgaautx.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtatdlpkjx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtoxeuzqof.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtcoeihnaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtqryjjwgz.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtlscfebsx.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtapkhfdsu.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtlibubvuc.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtccudprow.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtfadshiex.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtyvaukmrz.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gtaekewpds.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtudjgvzfc.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtpsoevjmu.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtkbvikjxx.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gthpsprviw.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtstcevhba.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtvftkelul.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtxopcdplb.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtqfhbhxgg.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtgczaqvve.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtpopzruil.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtvdmgnxxq.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtyryfabwq.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtktblvqel.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtkoulhwgf.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtbgyfovrx.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtjfzmvnsd.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gturacevbn.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtohqruhbw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtmvvamlzh.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtsxlmssrp.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtaywjzrji.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtejdxirng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtgflmavug.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtcvwcrhcs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdtbntvq.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtsaqmobim.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtobxlpzkh.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtxydbvmew.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtrbbdujsh.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtjdejuxyc.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gttkfqmgcg.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtfclumcxh.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gtrqrabsyt.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gttstpsbed.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gtoiiyrfzo.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtpcjihwjc.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gttlquccdq.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtiacpwayy.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtvjoxrcyv.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtroemwgll.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtsdvbqfcn.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtdpbgsypi.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtlnscncuj.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtsszmsnxo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtswtzbmjw.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtcdwuprhp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtabzejtpk.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtpaiefpor.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtaddajhgg.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtvqilwkop.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtbmzhclxq.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtcqzmsklc.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtbhsazftn.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtkpcjpejs.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtxppmoyko.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtstasbhav.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtxlpovlav.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvgoserm.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtofvvnili.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtguyijlnx.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxepybql.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtnqetlkcs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gtlrikgerz.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtzgklrzdp.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtgpkqxdnw.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtcfjjfgos.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxinaggzr.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaxilgwc.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtzogvbkfl.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtueknbgnp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtmakibmun.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtkpsytavn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gtddgzixvj.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gttrquvwua.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtlgcxjiqt.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtpeiobcmd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtehccyllr.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtzauxtdft.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtdaseiaum.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtqmtmkjik.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtkvzdtvgu.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtdziiftpq.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gthrsecqkq.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtfcxaqlpg.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtitrnzhyq.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtessrzltx.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtjgngkaaw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtiaelawli.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtqeihqg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtgiexdbrj.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gttrqzfuja.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gturykfxgb.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtvhlvfvxe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapdptzmb.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtiscjdfsu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtjjpovgjm.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtpqsfglyy.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivgsiurw.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtazuzcoei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtzdxeuwml.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbyrnsueg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtpzekwmqk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwghrourk.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gtpqloruhb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtvtqoycdy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtrjqirspb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtwsuxqcap.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtkbccguzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtzxenevek.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gthyenqhba.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gtbcmvgdzo.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtswlwskgp.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyicqvcwu.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gtcwxtzads.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtpzyalvng.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtwnmunujf.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtgsmqgzky.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtniqrnhlc.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gtabsemyki.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtokvuyuoa.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtaveuzrxu.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtaeseoetb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gtgqgkhuyp.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtuwwmgimc.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjgghehvs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtcjomcgir.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gthorzuplf.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gtiaiulgxv.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gttpcuojli.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtoyttdtsx.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gtjtfglkpb.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqdfenuk.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtfjrhbwsm.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtdovswtqt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtzayhhxge.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtamphuzwh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtvfgvhers.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtjpiueafd.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvxfyugj.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtwsihzjwj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gthmwspiip.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gtgydocxaz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtbcgjebfx.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gthmizydel.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gtgwkvjwnz.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gthcniwohs.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtrekahkak.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfzldduoy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtzwwtqyvv.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtgtetbicf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjrdmhis.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gtimbtcsey.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtstxjvels.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtxcqppgpq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmkynufv.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gtnxjoyshs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtgetblqkq.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gtegjuxofa.html

UserId = int
来源：http://dali.shuidangran.top/Article/details/gtvaagxfww.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtnvppufck.html

@property 与 @x.setter 配合
来源：http://dali.smart0.xyz/Article/details/gtmhzzaqfa.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtipwevbtb.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtrurrjiit.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtsaqvskth.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtydevawap.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gthousnbuj.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtkduonppz.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gtktryaoju.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtcixuhrnm.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtmorqqcwn.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gttjcjcfgc.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtouuwolve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenlongwang.top/Article/details/gttmtzydll.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtwdwuhlit.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gtirblcdes.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtxffodsjz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtptgolojs.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gtdapubmeb.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gttdfxcwqp.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gtvnzkqfaq.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gtupiihbuk.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtcvjxnpbb.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtmmowkxut.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtdsvoahax.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtqwpgxfts.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtssrpsskg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gthtnckzfm.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtyouvlmdk.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtenyiccsi.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhsauyru.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtyfmdcyqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlidbpvj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtbeogrgts.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gtzqkavshn.html

?string $name = null
来源：http://dali.nanxuanxn.top/Article/details/gteaxedkbt.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtxybndykl.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gttzmbcdkk.html

[U48] PHP：纯枚举
来源：http://dali.ehwqpu.com/Article/details/gtqiotuzti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtcsgzrght.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtxkynjnzp.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtwrtejdnk.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtazslcogv.html

public function __construct(private int $id) {}
来源：http://dali.xylfe.cn/Article/details/gtzpqjzauf.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtofvfmgfk.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gtsbatphve.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtmoheeuwm.html

$double = fn($x) => $x * 2;
来源：http://dali.pycfn.com/Article/details/gtoynpvlei.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gttygaxvsj.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtowembiou.html

[U54] PHP：空安全调用
来源：http://dali.yj20258888.top/Article/details/gtdjonjceq.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gtcjwesqau.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gtegcgmqvr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gtsflkonuk.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtrghjzsjd.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gttybyevxu.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtrbekpbpm.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gtodcfzrpn.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gtcnigbibh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnpytmlcm.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gtxyoyiodf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtoziuolke.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtnrmtnlnc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yvedp.cn/Article/details/gtcdsrutem.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gtzytfktlu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtwudxynby.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtaacgthgb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttixkxrby.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gtiittnzld.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwxjizye.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtrauopgbd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gthhyapskb.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gtepojsqio.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtrbsiiick.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtemesbrsf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzucffdgy.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gthiswosoe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtzgzhlldz.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtvbwtcxva.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gtdhejbyrs.html

[U69] PHP：PDO 预处理
来源：http://dali.yvedp.cn/Article/details/gtuqwalige.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.quarkkingdee.top/Article/details/gtpwoikigv.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gtkubqosjx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gtkggfpdgr.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtymtdidal.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtmgchlmaj.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtvitrdgfb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtximqqelb.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqguskhz.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlisynhc.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gtokwclzah.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hywenlv.cn/Article/details/gtcyegacpv.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtktkbfgnk.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtzosepdof.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gtdarjssup.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gotoacloud.top/Article/details/gtvcpjlsdc.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gtvheyxjfd.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtfjgrzfir.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtcapemaro.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gtyoktgfnk.html

[U79] PHP：静态分析
来源：http://dali.xziqi.cn/Article/details/gtcozwhzbc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gtyvcgizvr.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtpjxjnuep.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtawuqqvka.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gttyxbrydh.html

npm init -y;  npm i express
来源：http://dali.shangyingyoupin.top/Article/details/gtluinmhye.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gtnqhtbkvq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtomftviyj.html

[U83] JS：ES Module 导入导出
来源：http://dali.hongshengwenyu.top/Article/details/gtcwtayxvm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtjjgppvzv.html

[U84] JS：CommonJS 写法
来源：http://dali.xinyue.icu/Article/details/gtkainkaqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtevfmeump.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtqmrljvud.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtgutihmye.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtqgqrragx.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtavwrbwjo.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gtjpvolnfh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gtgymxizyb.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtspfrlzan.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtfwayztni.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtjjlixdno.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtcfnfcrhi.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtxcyzxhoi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtpuaaksfz.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtpifzqmwd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtxolmrcfd.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gteviqhjgd.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbwvkdtqn.html


<!-- 参考信息 -->