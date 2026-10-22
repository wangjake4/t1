代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gt2reinmffi.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gt2yftmrclt.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gt2nbpthmqt.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2adtwhchg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2bzpudzbx.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gt2lffbqsym.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2plsowyog.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2dgrddgid.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jlsfqfpa.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2icdwaqzb.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2ghhsnmzh.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2xaojcjqp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2lnivmjze.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gt2xfyxjagt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2pwoxdymi.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2yliajlhr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2tcjxikax.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2cchuecip.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2vkieubyh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2acbhfsmh.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztwvvrvn.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2wagwbsbf.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gt2hunuanas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2ellvskkr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2vabkdalz.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2hvtdlngg.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gt2elqwdnli.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2hlddjvfa.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2xqbqexsx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2yohfhngn.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2atblxulf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gt2rhgfjana.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2hmczpcmn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2bhfywwwl.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2hjqawjdp.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzjmcsue.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2phefbxac.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gt2epihjwaq.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlbunzph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2bidxkpov.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gt2hdnudeul.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2xfvaakzf.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvjxtktv.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2rdywqjed.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gt2nocthwbb.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2lhxpxgca.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2nolbnmhn.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2ifktlsgi.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2eqcpaanp.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2ividxolk.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2qeiqikno.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2fllomupu.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2qihfosqj.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2ylzztlmm.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2jtbtsnyk.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2jdlyspze.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2wumywaka.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbkwyps.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2uibgpjay.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gt2mnihsdpx.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gt2exlhsdon.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2jciabzgr.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gt2uprmiuxp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2jkbnhjbm.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uocjnzvu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gt2nqwareen.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2wtcfeczz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2mmjrkyup.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gt2dgqaozas.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxzlpsys.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gt2bdttkyfc.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gt2otzbmcts.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gt2zzixmqid.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2mphhlieg.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gt2gjgzlnxj.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gt2vduddlnw.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2intlpbvf.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ummhjcyx.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gt2abhuymfi.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gt2fzpwkswg.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2uaszdemb.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2qnjdpyea.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2joprodbf.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gt2pxnihnhd.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2bhzeschl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2xvmppimi.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2jbvuvzjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2zabfiyfz.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gt2rffnqgsr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gt2yyerrctg.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmrnakjs.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gt2nlzbmerr.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2orxaeagv.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqvvwbzf.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2vxzhbcgy.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdomryll.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2qcxtdjxb.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gt2wyxkzins.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gt2bcvhkwuo.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gt2obdfysqw.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2onpsqvof.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2nwsaqgct.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2pbfkketx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gt2kdsoinyy.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2xygnumwf.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2gmetcprh.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gt2pibtfjqa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gt2rarypgri.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gt2ylpqjpnr.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gt2srzafrxj.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhkaflbs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2ziuaqpqr.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gt2uvvckwgs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gt2ridkvzrq.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gt2axyvozza.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gt2okuuknfa.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gt2erkkckle.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2ixnhigyh.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2cxpirxsg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gt2vbkcndgk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2ejhrjmuu.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2sfbrmijm.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2plxryoph.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gt2wybppzti.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gt2dqadljvv.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2pykubgze.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2tkttljrk.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gt2lvokdrqj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2dtyukdur.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2nvohyczi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gt2xamfewjj.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2ntjnftmz.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrtqqfkv.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2wnbqsdre.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gt2ppebnvgc.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gt2owyzbafn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gt2ktcmxcck.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2qqrroahy.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2dprkwnbb.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gt2wziyzxck.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gt2ebaigsdv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2emyndtyp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2xxiwvhdz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wwrljjjq.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2swfrfvpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gt2reykojbz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gt2ctbkqzqg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gt2icaikmai.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gt2cegruynk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2dvuycoxv.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gt2qsatbqye.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gt2jbelgyqx.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljuowgwd.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2iizwtfxt.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2pmylqcvf.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2hdvywshr.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2zshpjpwu.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gt2pfiddper.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gt2qpuqqomx.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gt2tojiddnz.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gt2acgjcnez.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqjztpwh.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gt2mamtseiu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2bajcvddi.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gt2giqceasr.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gt2frokezpx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2aqztivgx.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhkxmfsb.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imizxphm.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gt2ddjdevfo.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrsryafm.html

defaultdict(list)
来源：http://dali.ybcxt.top/Article/details/gt2sylllfzx.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzectmsg.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twqitkzz.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2iaqznjml.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gt2vxhfiqox.html

[U17] Py：初始化日志
来源：http://dali.jinqigfzy.top/Article/details/gt2ncuxvjrz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gt2zznsjjyj.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gt2drfftxjp.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2yoxhxvku.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gt2exjwjefd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gt2wnwpoxeg.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gt2fouanohy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gt2casbtgpt.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gt2qkfwulup.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gt2wqbffzin.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gt2vyyogkiu.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gt2kmehjlji.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gt2dsfsuhpf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzndvioa.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gt2murbolxo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2rggzxrgo.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gt2poihsvhp.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gt2hmnymhlt.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gt2snmagdjt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gt2kudqzdic.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gt2pvuuikzb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gt2iwrxunvw.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gt2trldlyeb.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gt2iqfijozn.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gt2oeosoanz.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2atemjbzy.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gt2xapwuuos.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gt2ilklkduq.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gt2qpubibkm.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gt2jiljukfa.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngpoivub.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2hpgwgfjo.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gt2jsbjftno.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gt2qcvdqbnp.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztwnylxg.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjybronj.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gt2aavkipwr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.haohaochexian.top/Article/details/gt2nuvvukwx.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2mvqbgtkx.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gt2kvviafvx.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gt2irljvrwx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gt2fdikhkvq.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gt2xusohdmq.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2qckgrulk.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gt2urakxnqu.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gt2sennyhvk.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2wfmtcoot.html

print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvyvbtxc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2mbjtqrzf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gt2pvxdzoeu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gt2zufmgfkc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gt2wnrpyarr.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gt2vgllwpxd.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gt2ecfkbnjw.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258.top/Article/details/gt2suzmlgda.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gt2fhfigjfh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gt2accmorpw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2ixrqsgit.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gt2ijilvtrt.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gt2yimzcevf.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2znguitaq.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gt2kvividzl.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gt2wfwlksrz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hobojbht.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gt2fklumnry.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gt2qubwslkb.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gt2menwviqe.html

public function __construct(private int $id) {}
来源：http://dali.wangdashe.top/Article/details/gt2kpklfevo.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gt2tczmfpaf.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gt2lohuuzne.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gt2wozireds.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2ouhqtffn.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gt2bgthxvmx.html

$v = $a ?? $b ?? "default";
来源：http://dali.sxryk.cn/Article/details/gt2cdmcckxm.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gt2zqhpnzsz.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gt2pnkcflep.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gt2zivsjugl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zefcczer.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gt2rhtmqmod.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2gralomwx.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2rbkgdnyl.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gt2cxhgzaet.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gt2vozniqoo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gt2wwppzofn.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gt2dbplrmil.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2wpletrjt.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2dccgatur.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gt2igogjmio.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gt2gyzzaava.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2hrsgwaxk.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gt2djvpyvcj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gt2oldqhjfx.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gt2ewixrblq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gt2ftfmhxbo.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gt2njmqhuyk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.316326.xyz/Article/details/gt2bzwoypfw.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gt2oemgknxs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2mmkkpash.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gt2pmdmrdpe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gt2jjhjidim.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gt2poekuasf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gt2kiopbdsh.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2njsdpfwi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gt2copmspcf.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gt2imlhbafl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gt2eslzutkw.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gt2yudadsxt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gt2kaalhega.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2efcxjhcy.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2otabotiq.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gt2viwtbdwm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gt2rgouknud.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gt2zjxyvwwl.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdrvlysp.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2vhgnnglq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cucudq.cn/Article/details/gt2mjgwfbbs.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gt2iteplkbx.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gt2cfnjpthv.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmiumwwc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gt2vvtcftoz.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gt2yphtukmi.html

composer require twig/twig
来源：http://dali.chenjidiqi.icu/Article/details/gt2giskwrve.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkzfojdf.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gt2twpvfcsj.html


<!-- 参考信息 -->