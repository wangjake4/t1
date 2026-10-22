代发 wailian999

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nikmeiyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gt2iwukkboo.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2todlaeho.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtsztnnp.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gt2xipxtwlz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2duwbqpts.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gt2oissubzr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2cqdjcxng.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2umgeuyns.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vbbtwsua.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2ktrfcuvl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2kidynejn.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2iagdovzg.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2oquekthn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrkxlkiy.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gt2ldeqbxxh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2hdxctgkt.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gt2rrpqduvu.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2bpeyvbxc.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2gnaxtqkd.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gt2nrnveuju.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2nerhmyum.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gt2ypusmwlz.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2mvyqxiqk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2bjjrbaey.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2lpktyopy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2qqejgvkg.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gt2jkxudlgx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwdjlhtm.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2bzocvgjv.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kamsijni.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2nujneaee.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpnlnhyu.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2kkrcxscc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2voumeqmy.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2ciqfyuha.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2bzcplsuo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2picmxdtu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2ygdiqexg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bpoczynu.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2ofyrcplq.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhwhejtg.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gt2tqdrwtnl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gt2aqqfyokp.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2jwwuurhf.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2ockehxke.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxcyreil.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2zmaekqta.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2tpesffow.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2wadpvlap.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2yaigscbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2zlgzxznd.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2yrzwroei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gt2vweunirx.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gt2vbtrdegg.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2pvdhozxk.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2fhksykxw.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2dhvewylq.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bopilvko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gt2ndeinbru.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gt2vushdxig.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gt2ysbcnuod.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gt2cdtquomz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2acowgmbs.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dctnkxic.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gt2skrrmupj.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2jyujqpfz.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2yuvosuus.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdvwnzro.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2kdgodboj.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gt2yatsozpp.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2ykdpqijn.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gt2msiyqgeb.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2sswqixci.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2nspyfonh.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gt2jtkmronh.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkzlyqqi.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gt2gncrreok.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2miprvbyr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gt2pxoldksu.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoinoghi.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdutfwhs.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2fknhasbn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gt2fwyiiokg.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2pwcncxbu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2iwxqbltp.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gt2fyhmywrn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2wawzhtfh.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gt2xupfzddf.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gt2ptcrdtaq.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gt2dobzmuzq.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2tilppvpz.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrdoqnbj.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2fqjqwmrm.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2eesjboex.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2ytztvlvs.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2qrljdmgc.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2ysjwrfhm.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gt2effnehhz.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gt2yvjkmzxf.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2mbuvrqmn.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2wwdnzjjx.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gt2fvxtzhzz.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2ovhedcfu.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2musmjmok.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2xhhiiplq.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2czecugwh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gt2wvokjzmr.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2gqtlzegn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uecoexgo.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gt2udhwpdnk.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gt2pxdqovol.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2wfpsnnwu.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2axkdkqjt.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gt2egcgaaku.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvcpbdra.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2hqynytff.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2ybfojaol.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gt2ftjboptg.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gt2neqcypfy.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2wscqnohf.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gt2vhdbkwhb.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2fbpvflbn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gt2clbwwvll.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2grllywyd.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gt2igjbzscx.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gt2wlzxelup.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gt2fefawdpk.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2wuyrixmt.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gt2hraezion.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gt2dqwukxeo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2tgmjoxlp.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gt2vaksonzm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ckacolsw.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2supbgvdj.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gt2hgkdxjgi.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2rljnegvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2dwlafrba.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2tfgntsvv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2zmencfzg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2xqvxcsqf.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2lpftwhyz.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2tebomely.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gt2cvhvealo.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gt2rzfqypnc.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2lqeyjyic.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaanjitg.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2iijvhipj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gt2wpwnpzxt.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2qwootcew.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gt2zpnrrvcx.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gt2sqwcmvwl.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2uaiektxo.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2hcrzmyrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gt2hxcskcvh.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gt2tnfwckcp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gt2tyzpifcr.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gt2nqesioxn.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2lnwgixdu.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gt2iwuhnjjx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2itckcvyx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tydmdfae.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gt2vstvfbrt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sapptljk.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2gtfgcdvb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rczhkbfm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2ejkxgfqw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2qvmvvdwj.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gt2prfvhchp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gt2vcymlvdn.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gt2mtcqwfgo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2xsdclukm.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gt2qnefvgnm.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2gjfnxgao.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gt2uqxdtjwq.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gt2ttbkazmw.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2qycmslxh.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2gxcfbsql.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2xkhzrzeu.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gt2hzutgpdm.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gt2oguegupf.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gt2fuovlbix.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxdsgagq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gt2paizyfvq.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gt2eotkorau.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ffjydfen.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmqjvxci.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2matrgisb.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2rtlbhtgv.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2niiqzlsi.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gt2gvxrqkmk.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gt2evuqvpjk.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2qgqnupxu.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gt2honcscyv.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2uywcloak.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2fbxrndat.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2oxjyfaft.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gt2cbfcblqi.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2fwhpqsah.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gt2rctrgeub.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gt2helmucrv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gt2jozxrvgm.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpqhaptg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gt2gmdgpswi.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gt2beqvacof.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2mwvnqejp.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2cosjyxgg.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gt2lcfzypzt.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gt2ackrpizh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsfkpglx.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gt2ygrgqnrg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2iqpmrlzw.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2ywcutcly.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2cenjkftw.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gt2jvjqptrj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gt2wamssewp.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gt2cqpzmijb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gt2kgljhnez.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2llqibsys.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gt2vtigaajc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzwnani.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gt2auqkfopy.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gt2jsyieqzf.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gt2jreocfvp.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gt2lfuxdjzu.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gt2zsuivyob.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2cdoovrys.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yedutvxh.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gt2sncjaphf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gt2yaghrfqn.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gt2pkrjpvnz.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2jrxzxnsh.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gt2gvlyhowc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gt2anvprszt.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gt2nobtaqej.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gt2hviqtewh.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxekkrul.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuxming.cn/Article/details/gt2uyuqfmlw.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gt2trzsmwds.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gt2kgvoszyd.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gt2cftcthwn.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2llgkawop.html

[U40] Py：打印到标准错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2qindppdx.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2klsdkbeo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gt2hnpcceny.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gt2bxbakdlz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gt2rkonomyo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gt2ihzlvqdc.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2qvwekcrz.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gt2fxuharxy.html

[U44] PHP：开启严格类型
来源：http://dali.tian-w.cn/Article/details/gt2cnexelzk.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gt2iubsljck.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gt2ghjnhnca.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2peahbhjd.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gt2vxczyxht.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gt2adccizuo.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gt2xoprionu.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2tzrxvjqh.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gt2qmltqgau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gt2cpzujzqi.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gt2lrgceqxd.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gt2ejbzetdx.html

[U50] PHP：构造器属性提升
来源：http://dali.zycfv.cn/Article/details/gt2bbpfplrj.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gt2dgsumqqk.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2cbtufnmu.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gt2lzwjdxjn.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2zlugiddm.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2qwavulrk.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gt2rlfjcvyz.html

$v = $a ?? $b ?? "default";
来源：http://dali.dianchejie.cn/Article/details/gt2mnpmkuli.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gt2gznfnzst.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gt2sleamybz.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2bdbcywti.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gt2ojycdkex.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gt2uvttchby.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2obyszdwx.html

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2ywtlaezb.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gt2rnyeqejo.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gt2sfddfgfi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2qhmierun.html

[U59] PHP：自定义排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmtbnjyk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2zridchdv.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gt2qgjpzcip.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gt2twdrwzqb.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyixmutw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2dfuodnay.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gt2eynpxwhc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gt2aigqyhza.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gt2bzorpmwg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gt2kzxwrjky.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gt2efewbsfi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gt2pndfbwje.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awnytfvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymfxlbgu.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gt2qgyehpfc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2neeyjvhy.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gt2qdmiwtdp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gt2ywactwlr.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gt2amzrxvot.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gt2mwgjmwuv.html


<!-- 参考信息 -->