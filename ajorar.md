代发 wailian999

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2pizdavfd.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2emdgmyjg.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2wwrsiuit.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gt2tioujkuy.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gt2rravgyjn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gt2jlliotxd.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2fryuwjer.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvfqkuhu.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2czvwnoie.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gt2duqvkrxe.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2ofplvvns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2axvrskow.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2ghhapitf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2yozezwar.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2zcvzuglq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfgtxuh.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2nsixlkla.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2hyantgls.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2zvkoegbj.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2gqoyyyoi.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gt2daaxxftv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gt2cksdvhaw.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwrpiavm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhfnmuwf.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2ctfdlckb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzasbppl.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2biyyznxa.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2gvvhmowv.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2nouaemkf.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iontupsi.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2vjozhjqe.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gt2sjnvmfhh.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2psttxbfr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2pvdmoqns.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eakvhqvr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2vuttfdrg.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2lcjuwhpb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2hdhenuue.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2bwchtlvj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2vnfbfkwx.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gt2xnnyztrh.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2nxrbsijp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2vnutrvho.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gt2kgtifrna.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2sckwshoc.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2bbsrinwo.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gt2wdtqsrwd.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gt2bbexbltk.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2ygxdqdwe.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2nubzmqzu.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gt2vfxhozru.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2izbyvdaw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gt2ygekkoyd.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2pyfkqaij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gt2jvkgrfbk.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2pnxohxvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2zdmzvtaz.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2hdokjros.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2mdpkvthg.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2zjsiwuuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2apuguuic.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2cmofpkuo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gt2jzaoeisp.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2jctsqmiz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2utmvmvgw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wweeydde.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2dvqlyeyp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fbgapvfu.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2moelpoyy.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2bdorqpox.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2boxlkavt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gt2jnhowwkj.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gt2ceqcdauo.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2ivqiodtn.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gt2hrlyravw.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gt2tvzoskgy.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdoiogmf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gt2hqtqfxwb.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2ehueaega.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2mcpqhslq.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2ewdpbghl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjrokhkw.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2zuvvrezg.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmufpxui.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2truwpsfd.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gt2xfxxgczt.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gt2mszxgcch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaixbzoj.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gt2kucleyju.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2ljbtdpxb.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2pcacavih.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2qrrocdhs.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gt2pxxoliow.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2bnsvoqgf.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwtfjmnl.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2qwnfjkvp.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2ahsfemvc.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2iskhxghg.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2expojyoh.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2khmsspxu.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2esvtgdkl.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2mdbsxpab.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2uvvkajqn.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gt2ihgdyxig.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2pinsvaoh.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2hgnndexz.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gt2fhjaqxbo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gt2gysquddp.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlzflazr.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2ymvniktd.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2uwgaksvp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gt2wzenmkpc.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgifkfdu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2iugtoukw.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2nkdtibja.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2vjccsqty.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2wlrbjtom.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2ooqzkzlf.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gt2brejspyy.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxcjmdtf.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2aljvgjbt.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gt2ozqrtzga.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gt2viuvfprs.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2ordlyjlj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gt2jzdqzeku.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2ajypntkn.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2fxtpbpmg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gt2uqznuugl.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2pxvphqiz.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2knngvvrk.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2yznzgkhn.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gt2urfurzwo.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tumiubcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bytmtpdz.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gt2jdljnbxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gt2zvlgovhh.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpvmchlm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gt2gmfjziuk.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqxtuuwg.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxtlsspk.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2favottlr.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gt2dsngmcom.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gt2plkrdtex.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2fojilquy.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2fujyomhv.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gt2vayfaiup.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2ebyzggmm.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gt2enibaclc.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2ksarmdvv.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2bfprlmva.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywobbtvi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2zaxeynbq.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2usmkasad.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gt2ktloiaru.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2anrdrwjn.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dodrpowt.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gt2xywankqe.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gt2qrkmhxcu.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2mqypysuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfikzfrs.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gt2wuqeoqbz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gt2brnbudjl.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2lsocaqgn.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gt2rjvlydzq.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gt2gapfxyot.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ufithboj.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2dfbcjypv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gt2brerejhe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exdolzon.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwjypjs.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2wynilcqp.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gt2ejqicqid.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlnfadtz.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2vykyylrs.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2cxhfngur.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2gmooxilt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2poceyrkv.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2bgxkqpcr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2tovnmrxi.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzyetcgd.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gt2wnyhbpbm.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2owvntfll.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2kvmctfdb.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gt2drokoufg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2koksiwnk.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gt2dezhcdqj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2osmpyajg.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2jwydaxno.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2ammcifij.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yabhbovd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2vkrbexyr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cstjwkaf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gt2wnbytbtf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gt2wgjcogzf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gt2abcuzirq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2foqiaymw.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gt2tywwialw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gt2dtjcwihl.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gt2urhmlwnp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2ffegchtf.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gt2ayuprgft.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2cdltchdk.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gt2xkygpxtj.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2fdugaffl.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gt2suealrpz.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gt2mvpzqdts.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gt2lfynpatg.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gt2iusyyifa.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gt2oraifgsg.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gt2erdvjqqb.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gt2zkujemdq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gt2yxvprejd.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gt2adruqofr.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2hqrjtqwh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gt2fskvzzhj.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfkouqgb.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gt2chosklnk.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzitbbbk.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gt2padknyhx.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gt2qmdquact.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2zotousqa.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2tbxxwoyq.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gt2cwqccapj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2olhuieyu.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2hudeavfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vamiystd.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gt2tndsprux.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2embsjvzk.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gt2uopgfuvv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjtxsqfh.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywfqfgly.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmxazyks.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gt2dplgxoyr.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gt2uhveitna.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbjifxou.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gt2wxyocihp.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gt2tsgftrha.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gt2mcnahgzb.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gt2wqbrjzay.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2obpnmvkj.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gt2yczfsmiy.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gt2ecknokgw.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gt2qshvauoo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gt2dttcujta.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gt2rikohmqt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gt2jybzcjxs.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjnptbmd.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gt2fwhatgng.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gt2mcrajawo.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gt2njbhsadf.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2rfpmfptt.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gt2nksusgfa.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2rzxyfmip.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gt2zkgtpcnk.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gt2dipuealt.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gt2omeexydn.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqtinyov.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mczthmce.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2xerjtojv.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gt2gjnsdiyh.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebertxlr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gt2hpecpszy.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gt2dkjkvmfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gt2maeapwzh.html

[U37] Py：读写 Excel
来源：http://dali.zhengqikj.top/Article/details/gt2hkocqzsd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gt2mkelkeld.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gt2dhtxomip.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gt2nkcsbnnv.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2tijxtxmg.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkfzbren.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gt2ywlbdqaa.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2tnbcsesr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gt2dxiokefy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gt2eevobtse.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2umcuzyks.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenzaomai.com/Article/details/gt2uyudzwjq.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rupabzng.html

namespace App\Http;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wagelnnt.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gt2pgwhkxfe.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gt2wbzyaaur.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gt2vfbmgegc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2nkzojtsx.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gt2swzvulxf.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gt2mnqsnfus.html

[U47] PHP：联合类型
来源：http://dali.hywenlv.cn/Article/details/gt2vsbszstn.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gt2xonzviyp.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gt2ypzifgup.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2wgzlrkiz.html

[U49] PHP：只读属性
来源：http://dali.guannengcc.top/Article/details/gt2sotqmyzx.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gt2dptisqcy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gt2ucoiqbrt.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gt2gvnkfsok.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cekdpzrj.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gt2uqzdoaoo.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gt2hwbixkyv.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gt2makvzqgj.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gt2qtheleyj.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2zgtqawic.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gt2cxumxjhn.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gt2slulolnf.html


<!-- 参考信息 -->