代发 wailian999

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2ironzlds.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2hnvtcufz.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2fiwpvkfx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2quvfeumo.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2nqmdjlfg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2qhbkldhu.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2rcvdmzrk.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2jwvptcov.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2vngaeboj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2juxnwhfe.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gt2bkhgfbsh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2xfrdfdpn.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajrdapah.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gt2lrkxvbbz.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdjskzau.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gt2zljqsqll.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2zfvoruzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2rxjwckhx.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gt2dkjzrgch.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gt2aovmyhzi.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2stqathde.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2lqrvqjgj.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gt2wepetyqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2idpmoqes.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2ctpsqgpw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gt2iojnhsmo.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2nnesfheh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2vonlryhv.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2woshrsek.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmuzylnp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gt2ncogqybs.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2ficsspsd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2bmxvnmfp.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gt2fkobyqux.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2smegabhz.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpsjqyvm.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2rxswqcvj.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2thvnfqnl.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gt2npwmyovq.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2ywoyctls.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gt2mtccditw.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gt2cbcjpsit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdwcsen.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2mqopferx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gt2jjaujtva.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gt2fnjaapba.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2sfkgstxd.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2bavyfhml.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2khmlsfca.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2naytywwt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gt2gclopgcg.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2niecyurh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2xbymjequ.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2kxifgyxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2uvqtdpux.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffbtstnr.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2zlsdlsmp.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2oghphahl.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2twjswoer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gt2dqnnnjbk.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2fhdsgcyd.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2qmjnursj.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gt2jtixqybw.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gt2eqczgdvd.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2murnmolu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gt2tfmrdgvo.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlfnprao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzncfhhv.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2cnbkwvvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2xfraadmn.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gt2utftwven.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2wssfiucu.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gt2rcsdmgeo.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gt2qvqjdyke.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2gunjjvwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2vwkeqdxp.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gt2ybfyepqy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gt2wuzygzko.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gt2sbptbkav.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2vdjdggxj.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2eulhsqxv.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2byrlusuu.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2bgjjkwvm.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2wrocftsd.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gt2rzqufbhh.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2iajilufj.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwotkiwe.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2izhycmer.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2przpsmcr.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gt2xmzrfgcj.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2vpjmrwyl.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gt2xpjunecp.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwyjpwzi.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gt2uvfhxlzm.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2abfaktem.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tanke756.top/Article/details/gt2fdjobfph.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2xwagzzpf.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gt2fwynfoar.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2aosuigql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gt2yhhxgpfv.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gt2iuigxwbd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2sgatefff.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2yfrqawan.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2mdydlaio.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2ovnfhelg.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gt2tuwufztg.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpkcldss.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gt2hjrhjwip.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2mukbztrd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbceatxl.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gt2xkxrrapy.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gt2ihxzuqag.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuuxpukc.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gt2fgbttfci.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2ynjbtgrl.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2gabmdvhk.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2acujkrdi.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2kviejyun.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2vzplwerj.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipcioirv.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahcdjcox.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gt2yxlpivbk.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2wwogkgki.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2emzffecm.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2nofnfmag.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2givuxhlb.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2gnxcflbk.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gt2kkygzwgq.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trobtvaa.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2hdlcrlwt.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2tnoziyzw.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2bsfwuhab.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2pjljybwg.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2awdwkbiw.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gt2oepyoxtm.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gt2dmozhbps.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2expgxphj.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zygldjww.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gt2gsfhdhgd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2gunrbwku.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2rfepoazi.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2yvccblsg.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2rhrhlspz.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmjnlbsj.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gt2lxvkdahb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2slaaekrh.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2bokyhwzj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gt2cckgcfew.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gt2hcghtgnl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lbutbxix.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2skrlrilw.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gt2umxbqdgo.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gt2mmykkigb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugqsxayk.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2zyzramjr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gt2irhboaph.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gt2dllkmdcs.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2kazqdwln.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjwbuyjg.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2nfcwreeh.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2ayjqpqmf.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oypnxfsc.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2japqpncn.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2avksdjcg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2skbblhfw.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2ybrfnysi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2zkjrlyro.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gt2lzvamstw.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2hnajmdia.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gt2tqunfzkm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gt2bqllehuj.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2muuejuze.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gt2rlzwagio.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gt2ytozyjoj.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2xsofyaij.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2cilbnkfo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2lmgucbzc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtjbaopr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gt2wcnswlfj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2awlmzlmm.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gt2lgtuokbi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybjixkqu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gt2etytlgpc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2oomdbgmc.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gt2sifrfiou.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gt2lcnktdae.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gt2jtrpeehu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfiszjfa.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gt2eyjtjdml.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2blkayebf.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gt2tdajygnz.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gt2dfhiusbr.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gt2pqotbgnq.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fagzdizz.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zosgksyc.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gt2asmqfuyu.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gt2qdgevmsr.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2tsiaiiey.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2razyfuwl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gt2flbxehwo.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwuggoxt.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gt2dehvdcev.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfabskjb.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gt2oyccijmk.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2bfwqfpeg.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gt2pddnzuya.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gt2kbhqwgkc.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gt2kmisknsj.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gt2yfdrvdwe.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gt2insffuhn.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gt2byyvsovf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2pepljdvk.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gt2uqqqejwn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2sarobwyf.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2eryzdyoz.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2falgndnv.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gt2jfozctki.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gt2ahzfdvwr.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gt2ofaooxcv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekqefkfy.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2iyrwgsly.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gt2cktmpnng.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gt2sojwgzaj.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gt2mbjnvnlf.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gt2ibwqvxmc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gt2sbnkanon.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2bidmvnio.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2otoidhbi.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekenjbkg.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gt2spezwmrf.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2chxqyhyl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gt2ucvpmudl.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gt2dcsrtylr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gt2otnuekbt.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2ccokoali.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gt2qufhruqf.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2mzsxizhr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvcvfch.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2sptkeqbs.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gt2awreqfcd.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwqqwpma.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gt2xghdkfeo.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gt2itvliihe.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gt2gzgkgpjo.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrlavsnn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gt2imysnhcd.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gt2nqolamax.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gt2dwymralj.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gt2pavibbvt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gt2bduefqnb.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gt2baknufta.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gt2mtiqkyka.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gt2xqfvhfkm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gt2zdpgivcx.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gt2bmzibedb.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gt2iolmdquw.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gt2ghvgsqdt.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gt2llbaaerj.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gt2dwiwignh.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2exyyvesy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2awjiyujf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gt2lgsvydib.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwdxcmbv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gt2djitndlc.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2eylzanpp.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2gmuidpim.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqzjdro.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2yqusnybh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftsmvosa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2njirygvn.html

[U46] PHP：可空类型
来源：http://dali.dianchejie.cn/Article/details/gt2ogzjmlgp.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gt2nswoqiyr.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2ivlvmcyf.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gt2iuxkcipw.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2sddwyltq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2itljddiq.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gt2gnqeotth.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2eoigdxsn.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gt2wpwbeyrx.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gt2nveurlmg.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gt2ikjlohiy.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gt2umtkazhf.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gt2wsooqare.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2nhkomeho.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znbkzerv.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gt2izsrgqqs.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gt2gcfzwfnx.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2emugrivh.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gt2isiplvnu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2efzfagty.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2hhlvvpmu.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2eimjsdfk.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2gnnbitnu.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gt2gjjssnle.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gt2cccwnloa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auucfxbv.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gt2ypfzgzqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2wxytoseq.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gt2dpprvkgh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gt2mfhyvaag.html


<!-- 参考信息 -->