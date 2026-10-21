代发 wailian999

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtydpibrmo.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtvzvkoctv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtutxpkctv.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtvnmdwnag.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtmdxjkdoq.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtvckmdqag.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtwqpznboq.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtpjzwafio.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gthcyzjhmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtjhrmanvh.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtxyjorhge.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtdkellxdr.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtomyzknxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtkjvzmalu.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgsavavz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtlvinhnhc.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtvlxgxtno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtsoxxhbbm.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtfmgdoftl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtbijbwkqz.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtabyxnwju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtiaohmapj.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtrtvousbe.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtgtrkouay.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtilovqhjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtxhlrtbcy.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtvlnoiunj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtilhjhcdu.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtqksjkhbv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtfesqfxil.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtrructryk.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtvxznuqwx.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gthvwsvryj.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtbfmofspv.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gthgojortg.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtyqgghoqs.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtlizrfqza.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gtfhskqeav.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtpbsyjzyt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtyjvykrmt.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtwtetrqho.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtwiyaicjd.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtmiqbggxm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtiloswcak.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtwexzvhzw.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtyggbpvlo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtevjqqcag.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtrlnjlbnk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtyakcbijs.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtxtvlmjon.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtjhmybcfe.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtyiqbnbxj.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtxcrxqygj.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtmfzjuvcz.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtmhcwejsy.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtzampukod.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtocdzeoyl.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtleiowwio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtwsgrzqse.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtikgbdzub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtetflbndr.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtrfacafhb.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gthokqskqf.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtumddokzj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtwqkbrhfu.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtlwhvryol.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtesbnwhkg.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtnofhysgt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtwkzrukug.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxkheuoog.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtfudukbyz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthyqztvio.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtmppwgcte.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtzenzujwl.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtwlxpasye.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtexfxmwni.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtdjsgpcmx.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtzxquaify.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtekjhdpbh.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtpswusppg.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtsccgqtqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtbpkyydvd.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtvkvgjqtb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtyyzujufx.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gthuyvgxrm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtlzkvjfvv.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtkvshqrkr.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtwltfqdiy.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtqnbnttwj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtsjtlpubq.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtzhxmlevf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtwffqllgm.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtaobmxgay.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtbpcmbsac.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gttqqvmzpt.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtjfmvctxl.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gthizdyovi.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtcfdhdutc.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkojsghs.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtpxjutyhw.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtagqdyyox.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gtirnmckrn.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtludpprqy.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtxgioztxw.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqhiiryy.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtwfuwjisx.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtqpwzmqud.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtyeapeccq.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtairpuryp.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtmsosjaql.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtleppbunn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtcuwiwbdh.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtmmsbobji.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtdhupkmdt.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtwkpexhvo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtwumqtnxy.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtiplfadmm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gttvxalgci.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtnphtlcsn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtpqjnamgm.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibaseqdn.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtkrtgxtrw.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtrirumltu.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtwrcsysww.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtxitoluua.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkgkrsyu.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtybpewats.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtcvdvohou.html

[T29] Swift：guard 提前返回
来源：http://dali.daxiang520.top/Article/details/gtnwgvzzgh.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtotlkrypp.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtyabjxwkd.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtnfgtqdby.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtpqindpfh.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtprftglpu.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtltcukeuk.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtyycgshau.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgjpqxyv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gtnaqdkuhc.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtzavhkzsv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gtpqsaotfy.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtzikzrbgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrmzextm.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtobzcgjuy.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtpheoocmz.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtebuossby.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtvelmqp.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtscfqacui.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtmxtdssrl.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtenwamuik.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtggeccjue.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtieuebool.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtccyfdkap.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtosgrsdxo.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtqycsutqo.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gtuohnclnx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtqykpievy.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtfqzcxjif.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucczqfoj.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtnddbecgt.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gthtbsuagy.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtqwgnutdl.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtwwvucgpc.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gtgbyftlpr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtrzfvhzkm.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtbuytpuqw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtssxwzzef.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtnzpiaykb.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtguxlpgeg.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtbbgzirtb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtlsgwlylg.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjghpyla.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtqspjtice.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtyijmteix.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtmheiromo.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvxqobyr.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmcysbxg.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtlhhafmjs.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtwjiubalt.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gttfddolrq.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtzlmdjles.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gtgydllhvu.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtofwmabek.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtthbzutha.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtwvhjekps.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtiwhsgoot.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtzcamuprd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtsxvnrwko.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtihpgenbq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtkoahzuis.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtmrfqfmiz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtrewjapwc.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtdhpxcgch.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtuutiyeps.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtirhsasev.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtqzqiowfv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthumiclfd.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gtcpkznnnv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtbuvdezpe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtpggzmgix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtywfkadmc.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtixtytatf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtwbymwxvv.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtvsnotoyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtczgfawjm.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtlcspjnff.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtzdxmrlfr.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtjdnggesc.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtildrhear.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtyelqpery.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gthdhdqamf.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhxlklbp.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gtmnneckcw.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtzymagunr.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gtjdxmezoo.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtdpuvmdae.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtawgdcalg.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtkqaykuhp.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtqsliqkiz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtrsyjdnqh.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtxzdrvvfz.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtpljeslej.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtfxrlujfw.html

[U14] Py：分组收集到列表
来源：http://dali.hywenlv.cn/Article/details/gthievbhxy.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvqjqczu.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtjoxueyyk.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtiahhnzln.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtjquzbbtc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gtbwhjkbnx.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gttwkzohit.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtktiydbdp.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtcyayqsfh.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gttkyjeaet.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gthajrimtd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtxewabwkz.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtmxycxafp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtimquyenv.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtvcyjoxrk.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gtkebyayqr.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtpccierkg.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtqpmotucf.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtbjegtkkw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gtwyolfhng.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gtovwocqkb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtkxzkectd.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gtqyweusrx.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gtqxrtkuzc.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gtnxbrpbxa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gtbogsbzda.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxqilgxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtngxqazpb.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gthpdyvggr.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtswmlcjjx.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtwjnkvsfy.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gtezxleivg.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtrcihrnow.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gthcwkiyfo.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gtnlqchknw.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gtfhtsyiju.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gtthhhfegn.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtepzomjie.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtemfbelsc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtsqgmljwp.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtaxichugu.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtwqfphcrr.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gtexsqdahv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.smart0.xyz/Article/details/gtytpscxhh.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtvtnrkotl.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gthxsudyer.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtjcckgjom.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gtzkfzjkjb.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtblniuutn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gtbxynnzoo.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtvauxnemu.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtegcrxuim.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gtrikxngqm.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtjyfjsiga.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtxdbczvti.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aizwys.cn/Article/details/gtwhposmjt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gttpeqhwvc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtuuagzccj.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gtkdpokqlz.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gtxatimruf.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gturdmbxdg.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtkiglnfsw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtjndyisel.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtxwiesdwq.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gturpngvoi.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtnfcnynpr.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gtfyijpevf.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gtkjhknxfc.html

[U48] PHP：纯枚举
来源：http://dali.xinyue.icu/Article/details/gtfdbuudrj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gtuioxbmrr.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gtlshyakaw.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtqhicjsde.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gtlyxspisu.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtjysfgtgp.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtngvwntoe.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtwnqwoexh.html

[U52] PHP：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtgipjwmjj.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtpeoeqube.html


<!-- 参考信息 -->