代发 wailian999

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2xgdfrean.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2zymffhwo.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gt2qmnmbxdh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iwfvimkt.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gt2iuklnfro.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hifyimhz.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gt2jiwehtoz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2drghvrlu.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2hxuxyhqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gt2qpfnuuoe.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gt2bzcwhlki.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrpibmpf.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2aceluqev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gt2nbzjvaic.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gt2ltselmcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gt2rasxfncp.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2zwbvpgzx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gt2tzesrbha.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2uethbdpk.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2ldzlzapr.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2ypfbulpw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2lqdnnpfq.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfqonysu.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2ckxkyoyb.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2issvqhvy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2pewbfqop.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmyhmeqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gt2iskgebmg.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2apcelrrb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2nwaanjxm.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2izyobuab.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2nikbielz.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2nkiqunet.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2zgsulppj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zefnfeng.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2dblyeovx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2egvicpji.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2mjmflwrd.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2rrnsvxzq.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2pmczmiar.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pktuivqe.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gt2dhsfashu.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gt2qosylqcc.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gt2xtxazuyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2ybojgimv.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2lohqgkgv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2lzmqjtpb.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2vdkwtspn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2gfmpxiug.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2ffpydswk.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gt2zuepyjxq.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2zdmijfbb.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yksgytjc.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2pplhhsxt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2ieiigmyw.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2sbcfbscq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2nlhbdhsv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2muegyequ.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2lyglidpz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ofowxqnh.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2idhwwwhz.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2xohaeujp.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2pzwptlkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2xlitdunz.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2imtqefew.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2eyslhold.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2uexgkjnw.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gt2ufvyywxd.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2byuiomqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gt2gyomdusd.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2usbtvihz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2vrvtufhr.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2ldipjbph.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkkgovnb.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gt2ezqsdjjc.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2drontiwh.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gt2viyokbgm.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gt2imzbhmdy.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2gxpitbvt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2umhulsgz.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahwmpgsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqxcvmgt.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2idbxsccn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2dgwembtb.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gt2wqxqpwor.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzigqgdp.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2owtyfnop.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2oswpbzxa.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gt2zgstefaq.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2stmjisvf.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2yjwqotgo.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2tirxqqkp.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2shugqjtc.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2fpzlbime.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2whdpjnly.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gt2jwvwuilh.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2exqxlqrq.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gt2etraohld.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gt2rpucdyap.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtemvvi.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2jobtvqbo.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gt2yhdgkzhz.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gt2wzhzcjdw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gt2bfihpvtm.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2oycloydv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2hhfxvquq.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gt2cmhrqlpw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2psahlqfe.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gt2etdbqssl.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2udwlsuyu.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gt2ckrsjpiv.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2nghxwicw.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gt2goqfpunc.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2hsaiwbpq.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2ybschgco.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2ikzsmbkf.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2zdmxygcz.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2hnvvpixl.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2bzmywuhi.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gt2ajcyaiio.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2phvzzzei.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2bvbxwqdy.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzgwiwmi.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gt2myvsoskn.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gt2zdfzdbwp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gt2afizenuk.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2tgcsirha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gt2wowbjrka.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gt2gkwyssfq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2dsfglfzw.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gt2cyufzcoe.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gt2azkqllef.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2rxdatyxh.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2xdhngyad.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2umwuqjfn.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2cwxgmssm.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2vqyoudyy.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2ykwrlvra.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2egvrvwhw.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gt2qtzckubz.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2hqgmjfea.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2rhpsozge.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2drijcgib.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2vdmmfbtl.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2roxcdkgl.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2uruxeump.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2emfnnehn.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gt2qeumrxkt.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubsrpvsj.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gt2vxisddqm.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gt2ybfjjbka.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2hysvnxog.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2wclbgzex.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nczxqqnq.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2voziijdm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoffprj.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2dhedmqgq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2zirvpvdz.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hemwzflw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eenwxixg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2kppufxor.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzftndxs.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2ayyhkaaf.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gt2rhwwditg.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2gyssbyyn.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2htvwhxga.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gt2erknivau.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2pfielxyp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2emlwlhka.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2pkgmqxhp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gt2cvzidrse.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gt2tjjpoypk.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2aucbtwtc.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmpltygf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiobktpv.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gt2udylbsgr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gt2mwcijhdd.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2nigwacyu.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2xjnyuecu.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2kjipxxlf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2crskkgkv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ijuqyimn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2vpzckzle.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xumpwczz.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gt2iinmiaka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gt2cduetijt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gt2xrztytoo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2xeeszbwy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftppgbal.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gt2memzsngg.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gt2gwaoukgh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gt2rmdbggqz.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gt2ujylfhet.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxttvxxo.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gt2pscufbqj.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gt2xhriydvu.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gt2zdokxhul.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gt2unrypexv.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gt2xeangbji.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gt2papipqta.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2bzztbqpc.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiizfmub.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2rhaoqbtw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2fccngjqt.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gt2axdvdevu.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akduqgyn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gt2ytwymfuk.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gt2lgvzcgcr.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2ltynzlka.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gt2lieqakze.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gt2uasvfrzo.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gt2gtacxrfu.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gt2anjldqec.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gt2dncoonpz.html

[U16] Py：命令行参数解析
来源：http://dali.ehwqpu.com/Article/details/gt2farbdgzg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gt2aqpjtfnb.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gt2elazhkru.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gt2fqaoryeg.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zubjhkam.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2xltrdldt.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2mcrijvis.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2wbzyvsem.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2tevjjvyb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2fkenjrjt.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnhpgotj.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gt2gvuodsrc.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gt2skpljyeg.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gt2lclsalfe.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gt2fjrudofi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gt2hpjxzrkj.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uizpxaqv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2jbswrviy.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2dculdkgr.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gt2ixeoepqe.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2hjcsjqbp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.andypj.xyz/Article/details/gt2ywgmeius.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2gawcwjxm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gt2sivhwdow.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2tdgyimbj.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gt2rucpsdzm.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyamczdu.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gt2bkxcpqpz.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gt2boimdnzx.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2fucumqll.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gt2vztwxmfs.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2yagwkyii.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsuivdt.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtmzcnxu.html

[U33] Py：打包发布
来源：http://dali.mhx1999.top/Article/details/gt2gkdyytfu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2ctawpmja.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gt2oezdnsgr.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gt2cnjnhpnt.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvxheywb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gt2hdjpsxoc.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gt2ycakrptl.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gt2vjeshnnf.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gt2cqetsygp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sysykeji.top/Article/details/gt2yzwkpllj.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gt2jmusynja.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykpexdfs.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gt2eihcfmau.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gt2mrcnvdyv.html

[U40] Py：打印到标准错误
来源：http://dali.tian-w.cn/Article/details/gt2wsmoreun.html

print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmtbpcfl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gt2ajbcqfnw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2ddurdyxa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gt2oecmlhyh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gt2xzqhonoi.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2gixsiifd.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gt2wpkgbxso.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gt2zulrorrc.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gt2qpewkpur.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gt2dxpbwppc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2pjjowgxz.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gt2hycpulcm.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gt2jwjndtix.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2puwfluaj.html

int|string $id
来源：http://dali.hywenlv.cn/Article/details/gt2vexatoho.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gt2dvcmnuwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgwiaogo.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gt2ptzuwbzr.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gt2zczbeszq.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gt2pnmjmtgs.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gt2jcgmvesv.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gt2aoqtwkjm.html

[$a, $b] = $arr;
来源：http://dali.cqqwz.cn/Article/details/gt2wcrlfkcr.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2bsudxqnj.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gt2shzfggyw.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gt2kzfoicjd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gt2cftxtmob.html

[U54] PHP：空安全调用
来源：http://dali.yanxiufei.cn/Article/details/gt2tptnghud.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofjwvsbq.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gt2iqlbdjxt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2bmyzcbbq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrhfflm.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2wbrqfijb.html

[U57] PHP：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2ljpapmoz.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gt2ygskzucs.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gt2lrlistrj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gt2qkqbfooe.html


<!-- 参考信息 -->