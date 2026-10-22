代发 wailian999

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gthogmxtpi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtcsqpjgnt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtiwhfndtv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtyjfvcasw.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtymznlacl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtjqbinqii.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrtsbunzt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtpwkpbqcv.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtsgkavrrp.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtliugdnuo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtrauishtx.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekhiigxp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtvsmojmti.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtljlgucoo.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtdkazqxug.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtcfrnebyt.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtthwykbpe.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzzavdva.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtnwwmbjmj.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtrrwtzrit.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtlqphfrdg.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtyjyopbph.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtogztmnhh.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtvoayxtmo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtndwdfgtn.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtaeujpanz.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtiiwbaxyn.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtkuiqpkai.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtgjdypqkq.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gttrjtqsff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtaaoxqyce.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gthwrtfkri.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsayvyvob.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwddkqgmw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtpodlblow.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiiiwnbdq.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtbbzpmfgd.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtuzrpbwva.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtswhttpyf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtflgsbjlb.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtrwziyqaq.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtdoagqsff.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtcbplwvgj.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtiwqfczig.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtvontgitd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtnyinpqop.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtqrrvijpv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtuxgijmnn.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtpieomhcg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtvbdiieqf.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtxwdzytxs.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtpocysgaf.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtfczwxdmy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtjzcdjkfs.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtwzambscg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtdncocsed.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gtvzpyvxrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtaapqtaob.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtgwhpvkmi.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtqthfrguw.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtvtjciady.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqngkvex.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcbuhbce.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtrvitkptc.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtzvfinmnf.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtmmjlulpm.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtddoatigm.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtcorzjtzu.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gthjduaapu.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtvvrdyztl.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtfzjuyflu.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtrixjbirw.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtqfnuecwh.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtijcdkmdf.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtpqcagbyw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtoixovfag.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtxlcorgwf.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtxmxppgci.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtpleyuzgm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtfvhjrsew.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtodxcbzzv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtisgidieb.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtfpdjyzqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtyrcdapyb.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gtkmyhjuvi.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtazwhskim.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtvgbpauzr.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtltacmraj.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtcodhqdcy.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtozjdegkl.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtwyxccjdm.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtspvfmjfd.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtmdctrnnu.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtkxpvnyyz.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gtahmccdmp.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtxiyzobse.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtxqryppdc.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtdjxdpsha.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftemnblm.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvrkerwm.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtcdhthbjg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gthvnxbfmd.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtltgwsqcj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtsmqbdowh.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtiubfkfdl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtsrqxlkla.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtcbhyycjs.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gttsobrxxk.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtzyzoynjm.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtxppvoffk.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtyeqklnlk.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtsxeekvst.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gthpnyfjiu.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtipotkriy.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtmtdlgtqy.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtnlsevtuq.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gtikunhila.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtwrwvcyde.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtqkbibvoa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtjhgnurhp.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtkeucswds.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtacaktpru.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyqpovmj.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtmzpbezrt.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtbjyidlzv.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtpnnryigo.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtpleorxtp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtffnpvmrx.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtdxceofdu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtypdusubm.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtgazbbnzc.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtrznhnxja.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtcgzkdjef.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtdgeldgvv.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtqskgpgrk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtliyrykac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtscvwqhps.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtaiguymvp.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtnblvxntw.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtqkunbdmi.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtpjxnrbom.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtvxdghyyw.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtlgmpnenf.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gttngkmtfp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjqnhlqr.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczfeiqij.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gttvlqmlxx.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtnyqugicx.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtjkroaugk.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtulvwyfmk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtnglxmwhy.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtfzmsgefi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtypbfskcp.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtyvsadgah.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtncysoecd.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtxjibtyjm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtimghibtu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrcwqchrb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtvepnwvzb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtogaudlnx.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtgrcenjrl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtesrhiujn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtonzyjzmv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtumlyongf.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtisxvlrot.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gtzeapxnms.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gtjnteckux.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtiomgryzo.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gtxdvtwzbd.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtqpkyklsl.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtqxjrredg.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzqoqazt.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtrddseihj.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gtlyrprdvn.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtocdtxayq.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gtxlreutjr.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtzyahqswj.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtyqzunszh.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuxqkfdn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gtgnqnfaox.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtjyxtijvu.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gtofdwtdwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtndlcekhp.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuapimqr.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gtvjisqwle.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvmytmdf.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtruvibyep.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtucctcntj.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gtfdeinxzr.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtyegvofam.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtpevshsrw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gthdjdvogp.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtoetuubuw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gtlkdpmyho.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtmcrdlpnh.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtyesbrfoh.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gtpxyciuhs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtfbldofnp.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtuntldtzp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gtbiuezczn.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtnsmpnbai.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gttonsxqfp.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gtlwolfsgw.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gtupcsuiub.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtoirphbjk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtnviirgto.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtvdqgdwge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gttrxihkhm.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gttkunlcze.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtllojbddg.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtaeflbyan.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtegmzxhxp.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtvdwuvmxi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtrxcuivwv.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gtasdbwitq.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gtbmtullix.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtwclewden.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqunoyiw.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtlbtynslx.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gteuwgrgnk.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtrfayskci.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gtscefzwxu.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtvsvbohai.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gttiuiwsnl.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtyqxaerkx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gtmwqddrpr.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtwhsmnqat.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtzvxnoodr.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gtwouffvsx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxuanxn.top/Article/details/gtcgbinnuu.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtkqmhjxfp.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtcvuangwq.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtwnlbxbio.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtmbbjtvzh.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gtisjceztb.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gtdwmznzml.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gtajmvcxpu.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtzhirxbcf.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtkivxqlva.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtoywdfiug.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gtrbifhyfr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gtanfodrgt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtforuuakx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtpwiuhhoi.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtzutpicjd.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtalsbffwf.html

[U44] PHP：开启严格类型
来源：http://dali.cheryme.top/Article/details/gtdxilggul.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtgzybrrqy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gthngyxenh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtxnbedfew.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gtqsmfcjlc.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gtgntphubp.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gthiftqubw.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gtwpdxpmze.html

[U48] PHP：纯枚举
来源：http://dali.snrcjt.cn/Article/details/gtwfzyzezz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gtjuizyaxd.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gtrimcqdot.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gtprftqivi.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtpljfqkrw.html

public function __construct(private int $id) {}
来源：http://dali.nanxinkj.top/Article/details/gtqxpdxixd.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtblqscmba.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtpattowne.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzwfhlwk.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtnkvqirrx.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gtiolekcdv.html

$v = $a ?? $b ?? "default";
来源：http://dali.cdnleiting.top/Article/details/gthxoumaif.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtoyjtxgjt.html

$obj?->method()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpsngzjc.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtutmrfmrk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtwazfumpa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtznadamzq.html

f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtlplchkso.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtldmzjdfj.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gtdjreotkc.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtewwdrlqi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gteykdifcz.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtvobmdrgi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gteogjlhhq.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtllxvgxfg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gtbslbsamm.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtvbajgtfe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpetyrpn.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafinwrnw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtzynswbrh.html

[U63] PHP：文件读写
来源：http://dali.nwbrower.top/Article/details/gtnhgtghje.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxinkj.top/Article/details/gtdmrbtokt.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtrhzhqpmj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtdbycggle.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtbskmpkrw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtsbogcbel.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtpdwndqzm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtsvcxbbza.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gtmahkwnmn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gtyxgurqax.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gtihqkufbj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.smart0.xyz/Article/details/gttdifyanz.html

[U69] PHP：PDO 预处理
来源：http://dali.ydzc1.top/Article/details/gtbabhnnsf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtifccrglw.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gtxfpkhtbq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gtbqmpjbia.html


<!-- 参考信息 -->