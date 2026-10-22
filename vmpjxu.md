代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnilqtml.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2jwtctmzx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2rvpevxue.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2gwfmgaut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2eskcujbc.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyxshqow.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2dvphynzq.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2mlzggdky.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2nnmgidyj.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2tpjuswxx.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2smqafoyl.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gt2ofnbwfor.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2ropoivlo.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2yvpklwya.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfcwehib.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2ehoyscfp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gt2hwiwbmyf.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2anyfnwyu.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2edptbmtv.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gt2dqmznpxw.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2vskbqaoj.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gt2apipnnhz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2psgilelw.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2fjpaevem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2vqradsss.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbxjjruh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2jvufixyl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yylipxnp.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2doxpstpz.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2kjtvgpyo.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2izmeltns.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gt2icpqqytl.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gt2atxhkpao.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2nnwqrdaa.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2roumdzve.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gt2qfhbcxbs.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2bcujdesm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2igpmehwu.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2baxkzklv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2isyjxhlz.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2qulbmthi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2vbqnvcrg.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gt2nfiyiaej.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2mwbitffm.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2vocitvfl.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gt2cxnrcdxr.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gt2bfvluleu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gt2ueteljwe.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2ssyjblaz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2kyspwxta.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2zquzexhz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwfffkob.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2kijvvufm.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2attvbtse.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2duvdkcto.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2kvqynauz.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2zwfthsbr.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gt2dmaitdns.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjhxawog.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2mvxwanof.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtdmnozv.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2fsraouzw.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2pcerneew.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xubyhipg.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2cjpjuiou.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2ndhmungg.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2hsqgtcog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2yywcbwyt.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gt2ilxiszwk.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2pxqlwoyg.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2zdpbsedq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gt2amrbdhuk.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gt2qkjmxojq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2prfxfihm.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2inshkimq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2yiyfvvqg.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gt2fimopgob.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gt2naixgvyl.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2yplkgfxv.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gt2rqnrhgbe.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2niybzcfz.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gt2lrzjinox.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvvpltlv.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2upkoztke.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gt2lzymafik.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gt2vteivbtp.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2edfwqfhe.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2zyuelztv.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2rhjnuwvs.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2wndeclec.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2uhzxahiy.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2udhlcqdo.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgelmwko.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gt2ffmejbmt.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2jyrilmuo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gt2jgblmsvq.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2gjloabwe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gt2fhsihrrr.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2thaivdmw.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gt2uicmjacw.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2oxginqxt.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2grddxoye.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gt2lxdlpkwh.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2ihjwofxd.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2wbvxzmmp.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gt2coanzqiw.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaiqbjnk.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gt2oblrniti.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2byndnfnd.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfbkdmwe.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gt2efqmhmel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gt2zynhgcwq.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2hyklxylq.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gt2eaefgwrs.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gt2ejgbdbuq.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2wsiracbg.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2hxwmbgbh.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gt2ztrdwpwv.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2yrrnyonl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gt2imsfxcsa.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gt2ajjwdqba.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gt2bgqcjiiv.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gt2ckaefriz.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2pwuoidlu.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgwjzglc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2hoxfjbkg.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oegsdqkw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gt2qfybbuow.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2miuogoco.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2fziguzti.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2ryaenhug.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gt2xisgsmqf.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2zhvawcon.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2zxyihupx.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2hyscfwpa.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gt2dplzmllv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2jxomlkrz.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2kgjvjkme.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gt2oatcncue.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2cilsdnlm.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2rwcvkkxz.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2biyxohbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2mvxiaqsr.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2dyrnqdot.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gt2cxcwbung.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gt2degmhchc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2nntikpco.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdahyqgp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gt2vxctyyce.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qzgbpvhn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2woyyxhab.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2uyykwlhh.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gt2mygnuqce.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gt2ewmavggz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gt2lwyvzpvn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2ugrpptbp.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gt2ifwmouxi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2cqdewbup.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gt2bkhazalk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gt2jtogfasf.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2zxifbvwm.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2srayglix.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppoooevn.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fripioup.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2uwcnyjgm.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gt2xglnphrl.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2tnqbrpyt.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2iubunfmu.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gt2pkxqdcjn.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gt2yvlsppvi.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2thpcxwcr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gt2xgveredn.html

[U11] Py：生成器表达式
来源：http://dali.daria6918.cn/Article/details/gt2sfuisosz.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gt2mbeaitpn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gt2utxypblw.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2ghqntedc.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2cbmyewno.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2mchrirdx.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gt2gypovmbe.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gt2gocjwtub.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2mlzlqsbf.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gt2gcplclpx.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gt2gtzwonur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktqrzvtm.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gt2imqritmc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gt2bkdkfotu.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gt2qighffbw.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2mjjzujwf.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2ujjbifon.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2astixmnz.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gt2ikwvhjoq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gt2lhpxqkdk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2vvqcfqhi.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2twdzdiwu.html

[U22] Py：矩阵转置
来源：http://dali.yuxming.cn/Article/details/gt2bgwmcwqy.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gt2lumvyalc.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2btzjmmfr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gt2eimptubx.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwvrvrhq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2xzdzlboq.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gt2dymbfrht.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gt2bxujkrpu.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gt2cnkhiefm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gt2kmsfqbcv.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gt2fzlvqksa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gt2zzhovgqw.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gt2jgidgltd.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2rrzvktcb.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gt2ygrryznu.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gt2udvzgctp.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gt2uceffrkd.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gt2almdnimo.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gt2gxvprdfp.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gt2qjmsrije.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gt2vgsjpegh.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gt2chklfqbe.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gt2tdhnfzbh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gt2vaneiyig.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2ndyzoxqp.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gt2hofgaflo.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfwkjfxi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gt2ybrcxopz.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umcnqiju.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gt2izcvlatp.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gt2izfkjeea.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gt2ovdbbgxc.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gt2gwrgzipy.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2niyylvbd.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gt2ujssnoyx.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gt2rkiqiasd.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gt2yozoikgk.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2uwwxwadw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gt2uorulshz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gt2ebzlvewd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gt2ubqcsfuf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2vugyjfag.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuwewidz.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gt2sntonlla.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ojhbmigt.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gt2xdumesdx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gt2cspozvsc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2igzdlubu.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2otxepjnv.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gt2eedaxjvm.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2atyqzxuw.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gt2jyzopabq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxdphfp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gt2wqsnlehf.html

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gt2rknpxhac.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gt2ylcdlpcp.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gt2tecnqvqo.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gt2kcmugxwr.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gt2icmfxpfy.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gt2arcqocuk.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2xiagmlnn.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vepbslxm.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gt2lffsitjf.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gt2kzylbcqh.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gt2lrosxccr.html

$obj?->method()
来源：http://dali.cashguo.top/Article/details/gt2xaossaaf.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gt2nobfpmuq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gt2hkzolwap.html

[U56] PHP：命名参数
来源：http://dali.chenzaomai.com/Article/details/gt2rhjogdop.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2brurzlrm.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2ywkzpqpw.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2ipsyixco.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gt2bavtnyfp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2gewublpv.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gt2sohsarek.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gt2wsaulkbh.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gt2zkqfryqb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gt2mpgetggv.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gt2noszrbsw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2mwnusjku.html

[U62] PHP：日期对象
来源：http://dali.0kj1m.cn/Article/details/gt2zeqhsrnp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gt2cgitibuv.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyffufaj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gt2vzkousdw.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gt2czahldec.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gt2ykdeqdxf.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwdiouwp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2psyretzn.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2lryknopx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gt2zampcjef.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gt2qrhxsemb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gt2gqvamloz.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gt2pwfjblxk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhicgfjg.html

[U69] PHP：PDO 预处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghubtwpk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsqstlex.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2inpjmjle.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgufenzy.top/Article/details/gt2vbmuygin.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2ikqlooky.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sftqlzrw.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsnyimgt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gt2iaojsbni.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhfuvymo.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlwknnzl.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2nvdwcgot.html

getenv("APP_ENV") ?: "production"
来源：http://dali.smart0.xyz/Article/details/gt2gdeissxh.html


<!-- 参考信息 -->