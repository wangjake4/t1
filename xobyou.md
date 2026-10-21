代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtbdbqctho.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtnokwsyvc.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtkgzcqrpl.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtpchtglii.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtiwbeoqrn.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtklnargav.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtklkdutqm.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtwcklento.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtbmgypfqv.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtaqltzjde.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtfiqllugb.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtfcymimzc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gteejuyhah.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtlliodppj.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gtfqtgtqnv.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtlcrqojnb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gttaoyffrz.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtpiuvumfj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtgrzdnnii.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtbzcmnfnq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtmzujirpq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqqlxsboy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtpncupbrx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsevzbmvn.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbeqeusg.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtezbcwyuh.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtyvgpiles.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtgzxacmrk.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtjdwszhvp.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtjnsugtjt.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtbifganpr.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtwosardhx.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtsvbcegdm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkfjhxfc.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtvetptujf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtnnibduxt.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtyyzpplnp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtpjwrgoog.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtgqiamoqi.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtghmzsium.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtkmfdztdd.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtgplhuxke.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtgcmftjoe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtbxpclomf.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtemqbzgiw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtmstjayux.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtcktnrpvy.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtwavwsmdk.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtmqfuhztu.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtvxaqgjab.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtcjcpejpf.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtreemvbjm.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtsylnthzb.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtgjjnaijm.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtyopjucto.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtijftukvz.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtpnbzgqag.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtzunfddxd.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtwmfdyavw.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtfiqyqbfr.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtdkvwocgy.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtjrinchbj.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtyencjnfj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtzvrvsnvg.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gtxdygtcpo.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtuushoedt.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtuyprfnnd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gthhxijvpf.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtrutvxvxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gteolphhzd.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtkdunzvdt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtxwqodnmr.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtportmfja.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtclcjtdqm.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtwjvxcpei.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkalspflu.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtsaozlqct.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gtseyelucq.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtepfbbhpn.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtqyayeily.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtizfpgktm.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtnkaschyc.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtyqryzlla.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gttqlpbwuo.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtbfoghrql.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtnlxvlkjv.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtajqaxkcd.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gttbofkrkj.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtvghzuhft.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtbydvawlr.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtidatbjze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gtinapdils.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtazfywfjl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtfuupdcwz.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtbigvuiyx.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtinqbhrmz.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtumtryozy.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtdffktlov.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gtswyjsqve.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtvyfmckfo.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtmgkddgki.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwizjsreb.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gtxwjrccdn.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtpdzkkcll.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gttlugsile.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtjjknzrif.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gthcriszws.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtmwamjkns.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtskqivhtg.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtzezsvxdy.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtprmzktuq.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gtdkiyiddw.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtottkhnfq.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcnnkoqo.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtdpiblehe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuabzikma.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjibskfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gthwulggpm.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtwlmfasaf.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtcpzvtlsc.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtiawumwoh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtzpdfzwtr.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gthwvjoyvx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtmjuzfuwj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfxzdqpr.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtwibkxfop.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtzgpcfrhu.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtjrnidtry.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtnwvwwkff.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtimqpdmvb.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtrccivbgj.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtldhuyifz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gtwjxlhtfy.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtxyupyhit.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtrvujdwxy.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtziwllqvh.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gttifsuskl.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrugxodr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtwiutfucb.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtmkrbckhj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtuttfdtaz.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtlcwffqtc.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtpoxkdpqy.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtmeifjpsw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtlktmcyme.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvhzwqigu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtmwlwjrpr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthzpykhig.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtduwymcmj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtunabqipn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtqifxjjgv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gtvcegokws.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtrcoykcid.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gteiklppvn.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtoizpgomq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtmwhqbfcd.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gtfzqzrpgj.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtdipodptd.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtvoiemidv.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzsbceoy.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtpymvdzvs.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtszkfqkoy.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoczvbes.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gtwqllzftf.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gtdajgpgon.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gttzeatffx.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtendvelts.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtntqmltbx.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtugzuripo.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqjxekzvf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtmishvwvm.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvilevhde.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtjlzxqypm.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gtrjdhnpfl.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlceisyef.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtpvchjxjd.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtbrkbhome.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtrbcjylri.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtwomalkkh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvderfnau.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycveagop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtuwuywcez.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtsufzxlhl.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtpbclorge.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtrsibtdll.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gtdvitqkcb.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylyojmbc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtatfmckzt.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gtwzlqqyps.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtfpyopgaa.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gtnlpkehia.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtfeqkdgph.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gtfvahautn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtpksabxfe.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtkeyemfwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqtlljtw.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gtchrjufpc.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtmlvtxxzp.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gtehmhmomv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejgyyrec.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtcambwhyb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtzhgpkzvh.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtulqgqtud.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtiptemgxa.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gtabeeeotb.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtdzsjlyij.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtdszkuvbr.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gtyuzwbaay.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtnaejkmzb.html

python -m pytest -q
来源：http://dali.hysaishi.cn/Article/details/gtbsufskdl.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtwmprsplh.html

ruff format . && ruff check --fix .
来源：http://dali.xuetiantiany.cn/Article/details/gtbptyuerz.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtgknpesoy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtuigmidso.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtobkhtuyr.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtxljcflir.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gttbancevj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtugatbrol.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gtcqnhiqbn.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gtsexnbvxk.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtqhnpuzmq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtrbkaaefb.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gtmsnvnryl.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gtiuwoowqi.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gtuglbytgz.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gtlslehxan.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gtrpneqntl.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtefyokxng.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gtivvomtea.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtansfapjp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gtxfemoutw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtmjndcpjt.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtyblkubqg.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtdkfotomu.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtqvhiimzi.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gtxwvgughs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gtmaedidzw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtidnaunlc.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtjpfxgwei.html

?string $name = null
来源：http://dali.gotoacloud.top/Article/details/gtndenbleu.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtetqbrmza.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtwsmzfbqh.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gthqyomopf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtphjotlrv.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gtpzyfrsya.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtjvzeubqv.html

[U50] PHP：构造器属性提升
来源：http://dali.316326.xyz/Article/details/gtnqjattxn.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtsxrljkbb.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtraqyzcez.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmcowkrc.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtfvrvxemi.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtouifniej.html

[U53] PHP：空合并运算符
来源：http://dali.nanxinkj.top/Article/details/gthvjawmbr.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtwjwqcqsx.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtrywqyqwh.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gttnhffrpv.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtkjskovpd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gttahrizpr.html

[U56] PHP：命名参数
来源：http://dali.snrcjt.cn/Article/details/gtclxoaajw.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gttydyznir.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtwghodkun.html

"值: {$a}"
来源：http://dali.yuanzhike.top/Article/details/gtvpdpzidc.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gthromrans.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.redwolf501.top/Article/details/gtsfiaszjg.html

[U59] PHP：自定义排序
来源：http://dali.nwbrower.top/Article/details/gtzdnvqejl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpolyuaji.html

[U60] PHP：JSON 编解码
来源：http://dali.ehwqpu.com/Article/details/gtdlsglcdw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtjjkttkpe.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gtolvmmobo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsqmqxcoa.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gthvlxexxa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gtswlgihdl.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gtbaisybvx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gtkrvhvnzq.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gtebjikema.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xziqi.cn/Article/details/gtjciupvxd.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtmuefamof.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtaulvtalf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtxccnixjl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtjsvexvug.html

[U67] PHP：处理文件上传
来源：http://dali.chenlongwang.top/Article/details/gtoutmzkfv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtseojwrby.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtedyefcob.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yongpay.top/Article/details/gtuikcbyez.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gtkvdbbkrq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gtwvmbnixy.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gtidupjunh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gtokqsgyzi.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtwbgsxmbk.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtornvoeew.html

[U72] PHP：写错误日志
来源：http://dali.jqgufenzy.top/Article/details/gtjhjvyzxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtxtwdyymm.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gtjcsnedqq.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtncjbiwlb.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtfdwwmszb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.meibo888.top/Article/details/gtfgqgkwzk.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtgbpbcmnu.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtplxhmkcx.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gtzrafhmnc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gtzkwswwyp.html


<!-- 参考信息 -->