代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtfssvyqfv.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtuxafwcjr.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtgfyppsqk.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtcbehmign.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtfpiouudc.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgvdjzwnp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtxxhslqeb.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvzjrxrzw.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gteqjgarez.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtfbxilkhy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtosmxvxrb.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtcuboywzc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtdldvpogf.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtojcpmrfm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtkgeuudig.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtvmfsomwz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtnwdwfdxe.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtnqlarsbf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtvwzvihmr.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtgshyztlg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtaeiamnxz.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtptajqhtr.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtendmnope.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtsauxqbtt.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtieqtfemp.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtgfdyntal.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtzaioqkod.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtgobbtgwr.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtbxpldhfk.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtlugrrheh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtpjenmoes.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtogqjhebm.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtibpktyrn.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtadghwzel.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtdnmzyyqy.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthfwstyoj.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtsnavhuie.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtjeafrbbi.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtwtxualkn.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gttmqvbift.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtmxchbeyy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gthvanhqlz.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gthgledbwr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtapqtdily.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtudbczrwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtjnghwxoh.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtprbfhfsx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpmgcyuhn.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtobdxndro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtjdqqjxlj.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gttdyauepx.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtuyfzprpg.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtlvdtllvu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtnkdztefd.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtaodkzbfn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtwhmncfxj.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gttmuovimu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtijucwgrp.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtlqnhnekf.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gtokyixnuy.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtghjlbuyc.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtnkfrgvmn.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtbljgoqkf.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtdqyzinrs.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtjgjajeim.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtvhbzvvde.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtcnfmwqzf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjbqpmca.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtkofpkejt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtjnouwwnh.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtodwrzcej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtdtjowtpz.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtsxrqtrcz.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtpcxwvkbl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtdujyhcmp.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gthknvcsaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtshcegxwk.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gthsrvutnx.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtfqqpdzkz.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtpslntwno.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtoraphiex.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtysaqugwd.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtmxgrrwds.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzzdkzdy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtrwjawzwo.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gthihglzeu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnfhavsr.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtvudtfecz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtufvnzfje.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtqwiausnq.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrpkxdob.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gttodqxamp.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtoumygnth.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtermpfken.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtqndrreih.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtoqabsuwk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtnurhwlky.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsossewwz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmomrfvs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtudhygacy.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtwkuedipi.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtsithljip.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtznkxyrlc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtfzepnlls.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqmdffsh.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtmqyqludt.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtihxqzhqb.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtmsysrzdg.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtgpgihshh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtglnljyjq.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtmxnlautw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilyxyykp.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtgkscsmvh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtnhvmlwyk.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtawauwzqs.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtcepfrfhe.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtweechzxi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtmyuzatir.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtywizcriv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtfijfotat.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtocrlzfal.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtnsamzqcm.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtydpuollq.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtvvdvxxob.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gttjdckwrj.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmwwazvz.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtdzjazztc.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxozfrdxo.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtbiqowvyt.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwvhvpvf.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtnofzemew.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtjyliihjh.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gtlrmhcaat.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtmhiplmcm.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtbdtanffm.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtzsznwmxg.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtbwazryew.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntmvdcyl.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdomwslf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshrbvywb.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtclrcaetm.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtwvylykzl.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtwwhxgpuj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtpgzupkkp.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtnnlkopgw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukfjehuj.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtzgjmnczg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtojltwmrz.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gttmlmxudu.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtzdqaxhue.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gtikzbbqke.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gteqgupifv.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtfwwjnbqh.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gttmrbrpyp.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtshofvrxz.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtouppfbvb.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtdmilucmi.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtbfzdzibz.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtubgjdexl.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtaawxwzox.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtxafoyosk.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtbhgoiglk.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtztyvberc.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtionmsctv.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtcutqiexu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtfspznckg.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtikwsesek.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtercootau.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gtrgntbdxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtzfxrlyte.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gttrefikgz.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtumkjbtaz.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtxasvwpkt.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtrqcxtmuv.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtexfaewva.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtrxrvicap.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtpkxqpfjo.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtfywvqkmp.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtiolzbmkk.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtqkbmpfhj.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjfsuslnx.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gteqxwoktm.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtzrckniss.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtuikldlxi.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtukbbypwp.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtejrioujh.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtkuplaakg.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgznwdxo.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtvgvcurbl.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gttspoftae.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtrbpkypgf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gtkpfjinon.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjquqboc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gtcbhgpxok.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtwuoursml.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtnczfrgxh.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtuztljrcp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtvjaepxfh.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtbcpreotu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbjevmum.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtqcomsais.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtzhlplmxc.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtmjdcekdt.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtsdohfacn.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtcezmbrgh.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtomsormve.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtdtafspxy.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gthawxwygy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtssfxgdgj.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtipujkoly.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtqvjvfsuv.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwveennie.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtwyrckhtn.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtdchzletw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtqahpkljt.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtvafgzssb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtkvvtsewj.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaszmqvqr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtoklzlncp.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtbbifcbnp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtfnqcbmce.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtantsjnkq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtveuurufo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjiuefvxd.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtiocwoqcs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtqtsxsgng.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtsqxoacpo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtteqfcfak.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtzoozczbk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gttakqxfej.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtqdfqoqcz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtyqwnwkay.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtuzsqxzys.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtjuusnbxg.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtqwhpqmps.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtkiomveiv.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gtixbiubmk.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtzvzzmcga.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gtoonjtbpa.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gtdagzvxnl.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtnzyhgbfv.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtrsdzdokq.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtnixzyeqp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtgrwpyxiu.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gtufnkwuyx.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gtiqafflxm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gtlizrarjt.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtczaalscc.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtxwgwleiv.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtykkumweo.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtedkiojku.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtiaqiafud.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtctghjjju.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtuphhdbeq.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtqnimsoso.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtoeymdrhk.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtezzmmwdp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtyjmiuwtc.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtwyccwqyd.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaynwejv.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gtmwwrhuqy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtzhnzfixt.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gtppmcasbc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwdrokqb.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gtniynciwh.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtflbrnpcq.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtpmkzuant.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtizlxaehr.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gthueiaxms.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sxryk.cn/Article/details/gtthjtjxre.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtrsizzcba.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtwtcofylq.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gtkdyshvfj.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtyipgzlvr.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtvwoyahai.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gtqqhnqinx.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gtnojgxsnb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gtpuqhqpmd.html

[U28] Py：类型别名
来源：http://dali.ivvv.top/Article/details/gtwcwfvslm.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gtwaxaavtw.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtzzukdgcn.html

@property 与 @x.setter 配合
来源：http://dali.dashuyun.cn/Article/details/gtnhalrbio.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gtmkhggyfs.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gtgdbwdebm.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtvpfpebgd.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gtebhuqpas.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtuzrjvrza.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtvxbxmlsx.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtxpmhhaix.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjnfnejt.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtlnxhecfc.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gtyyejpkiq.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtykyjyacx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gtkrdeirbz.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtlkgqaryt.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtjxovzumr.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtmzmbvspl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gtynfhcbof.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gtcfypkshv.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gtgurajlaf.html


<!-- 参考信息 -->