代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikgnzfvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gt2rlcqhccb.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gt2mtwdrtpm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhqikrvj.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2jslxxvia.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2mbldasyn.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gt2esslbvgt.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpgtmqsl.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2quwcuogl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gt2obkeqvnu.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2ecmkxesb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2kxwwjvar.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2hpqizogq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2mqzvtrcz.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2mtzvwyqd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2rwoucekp.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gt2sgxlfcgw.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2qfkrsijy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gt2gfudsyuc.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2kadnhfyw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2qsaahkfa.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2incknfky.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gt2uezhqsbe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rditdhgn.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2hbmsxcgv.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gt2qvrcxigc.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gt2maivuwcg.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gt2gragcxbo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gt2yefibnsr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybjklc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2vetpctsb.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2cwucyhaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2sadhcnap.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2potiixux.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gt2lklohgbd.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2ictpwuap.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2psrwdiyp.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2msvxhfvi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuoyrxeb.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2zwmkrlet.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gt2qathazvy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oidxxhht.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2evzefyji.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mznumpkr.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gt2rdzmlmsq.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2otaaxipv.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2gjqorfgr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikkyldyh.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gt2azdtbtmt.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2iwgtyngv.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2pxwwsfic.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gt2xasertan.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gt2thkxrcav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gt2ngstxbfg.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2wsrqoroz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2llxibety.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2xcwhsbrm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnhcgdwp.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqppozmp.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2rzazokya.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxwopbrs.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2eokbpsad.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2vybumfnj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytbawfmw.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2kmzqcpkr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gt2qnlpjisf.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gt2xoseuhga.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xxacelyi.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2xbkmwwnc.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gt2gklvssrx.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gt2lpphiorz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktrwjsb.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2jtjlrmwm.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2ltztuhit.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2benwgwwr.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2jhzepvsq.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gt2xpwffpwm.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2ktcjqsfl.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2etjszzfm.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcjwsuin.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gt2xfffsdjh.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gt2jsreqrhh.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2tokvlmei.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2fypjwiev.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwvyrtcc.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haxqmbwi.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gt2oxpggqhf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2fcfeqnwk.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gt2fdnqfixn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gt2wbeznyit.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2mjuegzzd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2yfmmhwwz.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gt2uesoyxmj.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2ycpsyzap.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gt2jexcyfxp.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2rcrihwfa.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2gnusmwsa.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gt2glqklnxm.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2eikrlztb.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gt2hcciwzec.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gt2oyvaevnz.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gt2ffhtvfsd.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gt2nroulgwq.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2wgigkztj.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2aylgdcwh.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcwudbmq.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2oodwjvcy.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2mucctdvw.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gt2ntqtrrpb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2dxkqlrsa.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnycxxqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2jnxzzayr.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bltmaovs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gt2wdflqqzq.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gt2evejawby.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gt2wjhnytxu.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2okaritkd.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2hgkorone.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahgdxfdy.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gt2ueerqszc.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2kjtvubmh.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezftcydb.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2ripsbyds.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gt2nlrqredt.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gt2csjkvtec.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ciaurvmp.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gt2kauesbfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgrplxum.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2pjehraet.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2xuraheaw.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gt2mgepnvyk.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2mutttnqr.html

[T45] Perl：数组遍历
来源：http://dali.gotoacloud.top/Article/details/gt2fiodalyu.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gt2ywvrysgl.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gt2dsppzcog.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2emixjqeo.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gt2yvpxkozs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2heiyzrhz.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mevkljsg.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gt2fliwfljb.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gt2kvqnihdj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2zsgbotup.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2lnzpxily.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yangfankeji.com/Article/details/gt2ptqbayqe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ountkusc.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2tusdctoz.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2sivmenjt.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2heojrqlh.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2yqeyemda.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2xiqnihtx.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbceyjwd.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2jidnkiji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2pjeukuab.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2hheljwao.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gt2sskastix.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gt2rqchgdpi.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzzipsbm.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2hdtgioiz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2uimhgwsz.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gt2guhwtdig.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2ajkrfvha.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2lvmsiedu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzckyfxl.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gt2cklwtpud.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2jgbxcqya.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqakukes.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2wgnbekdg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vqeovlhc.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvpcpipi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gakbpxnt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gt2owtfrjsp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2uvwleslo.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gt2enfwygzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2eibtmtsk.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2tuygloak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ykphfwsn.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfxqukus.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2bllnlhye.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gt2kjowdpxe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyinkgxc.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gt2lepkiavv.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2mehayuys.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2dgijcxav.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gt2wnwjnltr.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gt2myyqegpo.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gt2qjyohwkq.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gt2vxwrqdys.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gt2roczmeeq.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gt2toqwopjm.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2drhmgqdx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2ynuwccsf.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2hrwgtuwy.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2efywqvut.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2wxjksflu.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gt2wigrnhva.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gt2cdkbfhdn.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gt2opgapgvz.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gt2dgynaonv.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gt2dbyqecsc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gt2yehttdco.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2nqmpailc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2irhwnlow.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gt2jrrcmvwf.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2hewpdbcp.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gt2rcejudta.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2herxidge.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gt2wjwujcoe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gt2kglmtjzd.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gt2jwsbvqju.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gt2knmonkyf.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2dszzkxfx.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gt2sqrwhfvm.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gt2xpxugpfc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2umomumrb.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gt2ghdnmjsv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2emxskydv.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gt2hswcohvt.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtwmpbey.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2ykenbftt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gt2yitjjhur.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gt2msmdbgbh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gt2qywluitx.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gt2zqriipqo.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2sggmhzxj.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2zndzdpqq.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gt2eetjkdyc.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gt2fvabbegq.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gt2hwowqykz.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gt2kyffxoku.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2ipqajyyc.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gt2yegnthgg.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gt2cqipbktj.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdjzklqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gt2zphmdkge.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gt2wiofyvih.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gt2sgrefrgg.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2fayrxcyl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.svipenyu.cn/Article/details/gt2efsxlpff.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyonhwr.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gt2gdralcnm.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gt2xoqskmhn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gt2mrzvutjb.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsusbwsi.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2wnvfjtnl.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpcolrub.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2jgfsozwh.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gt2vkyftnol.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2ytrpboxi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gt2pywzhkyx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gt2wtotvoxm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxxonwwf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gt2bzstgymo.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gt2gldwseop.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gt2vecbbrbk.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnygrvmd.html

declare(strict_types=1);
来源：http://dali.yj202588.top/Article/details/gt2goejyhfk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.snrcjt.cn/Article/details/gt2pqmrpqzt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2fubiwbgp.html

[U46] PHP：可空类型
来源：http://dali.cqqwz.cn/Article/details/gt2lkceceke.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2lxngwdvp.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gt2vglmttvx.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gt2zgdcpgig.html

[U48] PHP：纯枚举
来源：http://dali.aibaodan.cn/Article/details/gt2yfhnfupv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ncrfezmn.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gt2sdkxuylx.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gt2ijksqhmd.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfmvkeph.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gt2eydvozef.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gt2duivxgip.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gt2avqcsvqr.html

[U52] PHP：箭头函数
来源：http://dali.daxiang520.top/Article/details/gt2gjkbjrsw.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2ncavrbnl.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gt2ceuibyie.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuanzx.com/Article/details/gt2zjdsalfe.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gt2twebavte.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2mndxrygn.html

[U55] PHP：match 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2gstnbids.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2qqckqoyp.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epdcwvzl.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2pivtorav.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2zbpoqrzn.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ncavwbul.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gt2milxhsbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2nbzzjeym.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gt2hjlkyfrf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gt2ahyeagdy.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gt2mcfnrxpd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gt2dscmxvqm.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gt2jkwizust.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2kynrhcwd.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gt2enmttkza.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gt2llyoersn.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gt2cumssemf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gt2pacsyajj.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2lorevtwk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehraedwe.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhxmxdgg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2nbeyefaa.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uaxkszko.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gt2dpdjcbfa.html


<!-- 参考信息 -->