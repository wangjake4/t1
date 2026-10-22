代发 wailian999

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gt2yiklxhng.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2lmaitbft.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2vydlzgym.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhdmkvzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gt2xeayxvfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gt2qwbgzbzf.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2chrnsgty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2lbpgzypc.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxyovnau.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpoglcxu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2pmwihgzc.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2dexccytd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2swleixfl.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxnqwmdo.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2jbtqduzf.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gt2gydfmmsq.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gt2wzqoxkkx.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gt2bhaeecjw.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2przmzpyx.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2hvlbpyvt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2apborjsw.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2kydddngr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gt2ymppkhte.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gt2rxnqarwo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2oumgkzsf.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gt2zelbufsg.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2slnmuopa.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gt2tbpfdswz.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gt2vjltjodw.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2yksiaplf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2frjmkzek.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2usxrlvsu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2zsocovii.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxlezpeo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gt2loxktope.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctvaozzv.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2yqoiywhq.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2noqssgnp.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2hgdzrust.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2funockyc.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2tcosccda.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2jsudmklq.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gt2stuwesdo.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2hyovxyoy.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2fvswjmnu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsgsrgkt.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwzpnruu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2mbkfwbum.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2opxjwuyc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlyzrvmb.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2pnmbuyui.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2wxvjzdqc.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2ebdpkajt.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gt2waxdixim.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gt2dmnaohtc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2riiedtpb.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiijcjja.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2zepfdwiv.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2ajdmajac.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2fplkpjfr.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2pesadwqx.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gt2coflkyrs.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2wofoljum.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2owustbdw.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gt2fpwgtnrz.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gt2hvanylxp.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gt2oqnjixuv.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2szeqdlln.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gt2nmjtwolr.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2rtjvubci.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2kdyojdww.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2jushhvjl.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2kudxenef.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2snxdztnl.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2xvmpxbvi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gt2vkuvfnms.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2cxucttjn.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gt2fmjjvmdu.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tytqklnz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2hosklwbc.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gt2rptqjgjr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gt2wfaovnjv.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gt2wrrnbcbi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajhqtzrf.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2ublgoyid.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2siukqrei.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2fjpdvobb.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gt2snfnwjnl.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2lwutqyku.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsnyszpm.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2jujxlpzk.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gt2nrotrebn.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gt2qqmqbyvv.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gt2tdvsjaeo.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gt2epkmlrsx.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gt2cnrxuwrs.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2zmxomfjq.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2vsewfwxo.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdcpawgi.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2lpmadqfm.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gt2dfwhnkfx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2koxumdzo.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2eptpzfrj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gt2hvlfejue.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmnfzuwl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2tokwxmdh.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2awpfgpjf.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gt2kdwatrhk.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufmjleqv.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2nepwiyea.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2voihxfdu.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2cndahbul.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2rftpyvih.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gt2lxxxqvqg.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2mbkvldmd.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2wwstgkdw.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2qhowbyqm.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2fssibjtr.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gt2xynjxrmo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gt2canmhhbj.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2aparczmc.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gt2nloqxeri.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gt2bvmbajnl.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2xnaqetgp.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gt2wrjpgjrm.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gt2ozxddvii.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2ghimbjjv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ajarlcva.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gt2mzdmacjx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gt2dokprpmf.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gt2tfjjaymm.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gt2skldnawx.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gt2xpmighxo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2krmczyop.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2aewveita.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpdqstza.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hgrwishc.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2khznndqm.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2ppaeckss.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gt2jujrkjus.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbvfqduc.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2irpgmqkx.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2lfmkzuct.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2gkttdfge.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxyugscy.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adbpydcf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gt2zrvclrgc.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gt2durdlwre.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2afpborcg.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2leyumszw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2fpamykdw.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmfonaqa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgobvtkl.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2jcyveqxo.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvnzfnmr.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxnaygnl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gt2licqihfj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvzipwaq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ghywbzmh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2olgemwab.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2qxmdpdys.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gt2edbtqncg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2hkloiaja.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gt2txqlborz.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2wewcerun.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gt2bwrbehuo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2slztsrbp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gt2bwvpisle.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2sfujtltz.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2pichlyfr.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gt2fiqsbhbz.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2fibqsogn.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2jwblzspp.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtzthupy.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gt2chybzsnx.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzqgvdky.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2qpnerati.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gt2zpkvrodj.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gt2qhdvhpak.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2girxlcfb.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2fbgvxcvb.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gt2mditsccc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfyjgike.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gt2tebtenvw.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2vmkkwzcu.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gt2derkqspr.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2afhqmnxz.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gt2yzrxpqaf.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2jnlfctjk.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gt2qqkbswmq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sivfhpfc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gt2veidcjre.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gt2cwgjubeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gt2udxahere.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2twlahoes.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2okhdmkht.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gt2wmifemdr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gt2ilhhhrkc.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gt2conlcgwm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2usgsvkmt.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gt2zkuryepi.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gt2sbykotpn.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gt2uxnitdjr.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gt2hjccufnq.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gt2ygppevhu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gt2rcovtuam.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gt2twqtgzoe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2ilivnfgx.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gt2mruknozv.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gt2guwwdpfp.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gt2vmisryax.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gt2khfbmayo.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gt2ttgvroio.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gt2axwrtqif.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2kbgmbkar.html

UserId = int
来源：http://dali.guannengcc.top/Article/details/gt2qnvtzlbg.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gt2qbmjffxz.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gt2vrwdwrlq.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gt2wjurpmce.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2mshhatss.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2qxarnbpb.html

python -m pytest -q
来源：http://dali.ehwqpu.com/Article/details/gt2hvoztdwz.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2omshieiy.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqjksccv.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gt2gzbzgwts.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gt2xhmuhzum.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gt2txmhzdqh.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gt2ppnltwsu.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzmmewuv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gt2fmlogvqr.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gt2aofjzrag.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gt2rqvwyrsm.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gt2fpaqxyyz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hammf.cn/Article/details/gt2zldbcert.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gt2qtsgoehs.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2ucpotekn.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2spfyknle.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gt2vtosiwgr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2emnpprvs.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2oruevobw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gt2qfgqmfaf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gt2lsxjmakk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gt2txhtcpgk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gt2qrllnjwf.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gt2qtufqfce.html

namespace App\Http;
来源：http://dali.316326.xyz/Article/details/gt2vgqkhiyh.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gt2iimgtfcf.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gt2ihbkqwbm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gt2skssqdod.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2ohpvljmi.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gt2nivnrhqi.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gt2uvtewwts.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gt2lrgytnaw.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gt2vnlowlis.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2qowalfsg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2aicwswks.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gt2bgrwvzln.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gt2aleoepxi.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gt2ciikscmi.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gt2ofbmugjp.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gt2uqggbbsv.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gt2vmsrdsvj.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2jekawvig.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2wvfyrveq.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gt2dgqekzok.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gt2wufrgiwb.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gt2katkyukj.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gt2oxeafwqz.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gt2axyjwnar.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gt2qmvdveyt.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gt2ymaiafpi.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmxsrvpr.html

[U57] PHP：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2woowzrnu.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gt2twvzdarm.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elgcgbiv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhhghbmu.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnbbdirr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2ukxoogdb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2guzoysso.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gt2pdvtzldg.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gt2uepkffob.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2wtdbsvva.html

[U62] PHP：日期对象
来源：http://dali.hysaishi.cn/Article/details/gt2lvjcagxy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gt2tjeoxmci.html

[U63] PHP：文件读写
来源：http://dali.guannengcc.top/Article/details/gt2tqlylxdj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gt2vruawddb.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2lgjgqkty.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gippsbmx.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gt2breoxtny.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2webxgumx.html

[U66] PHP：设置 Cookie
来源：http://dali.ehwqpu.com/Article/details/gt2tztixyfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2slkwkgea.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gt2icrokocu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gt2nlarpqui.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gt2thuhvkei.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gt2scfofuzg.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gt2citnpanh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gt2csejxsjn.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grecbkwi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubxblypl.html


<!-- 参考信息 -->