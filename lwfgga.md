代发 wailian999

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2hhzienho.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fybnkqrd.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2rimqjpwj.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2spxgawya.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2qvxtvbqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2pgvoezgr.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gt2nkezostp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gt2tdjsmcko.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2folttapn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2tgkfzkfz.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gt2knujbwxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2ggqscife.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkwsbxms.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owlgeodi.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bilrspmy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2ohovssnd.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gt2dimkuaaj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdqsudsk.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxqpmsst.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2akcailzp.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2xuatmbej.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2pboivcig.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jxefrbvu.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2isurfvdm.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2wnyvpdbc.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeuvqhuw.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2kskjbflc.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2ehvdsyyy.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2pmdpgrdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2rpazemoh.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2gekiwono.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2ihygajkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2rhhxtghi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gt2vteljyxi.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2mvzringn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gt2vdpaupfu.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gt2cnfggynd.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2pokwmich.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2zcyetmxm.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gt2jwirspcj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2bvbputrr.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2ummjzwss.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2pdnqlpzf.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2mxwymzfj.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gt2vjvvjtlo.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2puviprbu.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gt2axeowvul.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2pzznrbjn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2hrmhzmgq.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2sutbwxtd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2uqftholz.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2vjmdwkpl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gt2aiboztup.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2mqrlgqxd.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gt2tdmgdqqx.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pejpfrcy.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gt2keaharjr.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2taujnzhb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2pqpezeqg.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2qcazyjpb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2wmeukybm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gkccvoco.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2mzdlguse.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qvgakhxm.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gt2jcnvaiwt.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2glepnwpu.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2kluktfkx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2xawaozby.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdtgcuri.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2buptnuug.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gt2wzeojjcs.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2ydqzhkzr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2jghebqav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2qejappxv.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adpgztkx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2pxbmfszc.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2gpddnlqb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gt2inkmzevt.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2acwiiwjc.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2efzebchu.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gt2lvwmknhr.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gt2bocfhgxl.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2xzxpubwx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gt2unapquor.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2buwccmyo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gt2tpstaesk.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2zitpsfae.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhbmlagf.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2xijuecih.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gt2acgdgrwc.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2xjtqncen.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2hpknlymm.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gt2boygfhlm.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2uzwohymo.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2odpokfjz.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2crjmeckj.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2iljatvmv.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2fklzgkzz.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2snsnobgt.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gt2ehiydpte.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2ndkmuahl.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gt2bxyheddg.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2eafquybd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gt2tokhxwdf.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gt2pfyyoyuh.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gt2rvkezehr.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gt2xsosvgnl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gt2jeozkzto.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gt2okmfarpy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2dexitkuw.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gt2kehwaliy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2rjcvayoc.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gt2aikdtcsw.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2yvfgqqcs.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gt2gulroiuq.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gt2eykgeanm.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gt2hdkvvzqe.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gt2fzpmkbdh.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2zcdgjwcj.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gt2uturpmbq.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gt2rjujyjfy.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gt2qecgqtqy.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gt2injoshzh.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gt2jockzaqb.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2qrfvrcar.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2ihbxvuuw.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gt2qanvjryu.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2larnbxbl.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2qjctoflh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2nkomvtrm.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2pbravsag.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gt2ruvcnvqd.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2lmowknfq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2inwevnda.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdkcqwzx.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2vamcyeum.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2bmyqtwlq.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gt2wfszouhf.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gt2jojefvho.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2nexbqwyn.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2vepxahyi.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2hpglmavc.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2baxdwztu.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gt2vcbmzszc.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2gaktaiux.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gt2iwwkwczc.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gt2zoxscrhz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2qhrbwmgp.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2ywbaydur.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gt2gfhvfird.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdlccizr.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2godlkwrj.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2unzskwsr.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebegvnfa.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gt2jpaonkau.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yonumen.top/Article/details/gt2viseuoyv.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gt2wcoediqo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2uxzordue.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gt2nbrucfex.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gt2cijfojdk.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2gjilkthz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2cztixdld.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jymvrbmy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2vdtxsqrw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bldyalii.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2hchwabzx.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2ptdreisw.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjaslcgt.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2bckzhlie.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2bisnqcve.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbvrlasl.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2xndovpel.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2brwzcurw.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2itcrynkr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gt2rhjlwovh.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gt2bdcgtdvo.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gt2ricqzbeb.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2vvlscwqt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2tabdoply.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gt2rspldbzu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gt2krmlfhuk.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gt2zsfybbyp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2rqfjyzif.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2dnooatwy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gt2uxebgrti.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yyewmqyd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ctcqdsrv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2doocngxa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbkuryuq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gt2xbtjaupy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzjtfnix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gt2ufrcarsf.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gt2vmfztmqc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gt2fzzuhjgi.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2xbheuevf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2rclykeha.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gt2fvafodaw.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2jrbnfdhp.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gt2towfxyfk.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gt2pokxjywj.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gt2ldojoroz.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gt2efwajuid.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2sllkoatg.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gt2jpzrespt.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gt2pnsskmrp.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gt2rofskbbx.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gt2sscfgfmu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmehkhck.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gt2xajjrkas.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gt2rzqobvhg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gt2pjxcnpas.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyvtkcv.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gt2jcqhsznn.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gt2dbtjgbpo.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykgowzyg.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gt2lywdpqpj.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2igqleypo.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gt2cbhgbcjn.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gt2sudleftj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gt2ekmzzbjp.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gt2sirkrxsy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sufxvd.cn/Article/details/gt2acwcdekz.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gt2zdjvcynh.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2avzvhtsk.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gt2jkdepoyu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2qrwujslz.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gt2mwimjywa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gt2tzbrujui.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhvfghci.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gt2xrxbqzqf.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2oelcjcgf.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gt2jolrsbwf.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gt2yyoyrwwn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2lujqggxs.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jahhhwyr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksmeeuzz.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gt2faugzknq.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gt2ujcbwagl.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gt2dkcqgmiu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtddihme.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2qrhigxcd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gt2kdorqbij.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gt2vbqduqbg.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2oulwaiwv.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gt2ngwdvkpf.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gt2pgtpjizj.html

[U30] Py：数据类
来源：http://dali.iojbl.cn/Article/details/gt2sbmyspus.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gt2zjstidnv.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2nsmxgapz.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gt2dfbfoivk.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gt2kobgvkqt.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gt2qdtjeqtw.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gt2wqchsdaj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gt2hbataixv.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gt2rdajumox.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2yrludkvg.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2otlmolgv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gt2qedojeri.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gt2zdihryyi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gt2glxvqbrk.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gt2smnhbqcq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2vpvbgbcw.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gt2fhwmkhtm.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gt2ejrctolt.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2timoiuhx.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gt2jczehmxl.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gt2dvbnakww.html

print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gt2hcghjmud.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gt2crygwndh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sweek.top/Article/details/gt2torossdm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gt2vadelwks.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gt2gugrynef.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gt2wnvnrnik.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjnjkpa.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gt2fgnhqnkh.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gt2saumpggt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gt2dtycrged.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2czjoyqxp.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzpxpgwk.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2oleygisy.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gt2ffizekyp.html

int|string $id
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuchhrsq.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gt2ohrqpkut.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gt2nxognrhs.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gt2sqdjqmzc.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gt2cbypjxjh.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gt2zuxvfvpb.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gt2dcpnzmeb.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcmprtdq.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gt2aqcwvnba.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhleyoag.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gt2fymabdlp.html

[U53] PHP：空合并运算符
来源：http://dali.gotoacloud.top/Article/details/gt2ssxelykq.html

$v = $a ?? $b ?? "default";
来源：http://dali.xziqi.cn/Article/details/gt2wcutphef.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gt2txygsvvr.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gt2zinpefog.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gt2mliktfyc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2qnmgkbus.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gt2mojsenut.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhtcjggo.html


<!-- 参考信息 -->