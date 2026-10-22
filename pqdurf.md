代发 wailian999

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtmpbmuxjt.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtydlzykck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtjakaxtby.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtsqxezyvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gteovwrwfp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtuinlpmnb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gterpldjzc.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtfjtychgt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtctkqtmid.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtujyafdye.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtiwrbdcdk.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtjoabxcpc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtzmmqhaas.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtwtcsbtdp.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtcllulyll.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtrdvrgplr.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtcjvqecsl.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtlhahjxsx.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtfjpkgtfx.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtvegqlxix.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtfcfdhjay.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtmzmrrogs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtbrqnuyre.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtchwzbtoj.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtxnuwesxj.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgjwwcsw.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gttitnuvby.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gtxhvpeixm.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtfohehhoy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbgnankg.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtivtxsiug.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtijpbtchi.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtpvdwcvuf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtaoxcmcfm.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtagmybzbn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtfodvsvge.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtfhattivp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtnktbuifu.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtsptjsvws.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtntdlrvjt.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtqenecbcg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtneqnpinp.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtoefkxaui.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtdnpepefh.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtgvbahyvw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtqxdusqzd.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtelnnimxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtwvmdnpss.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtkhyaooez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtqcyvmwhz.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtefdduosd.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtarojftub.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gteumeexpb.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtjerfzxda.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtxyfpasqe.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtdntdxpue.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtwvibrzgi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtnslcutwr.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgafsesy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtsolezlls.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtdkytvcmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrjqhpkx.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtboyuipnc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtndszslrr.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtvrmeuvtt.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtzlrmplrj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtzhymrtrn.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtzxrclsxn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtoqixjyaa.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbentvtk.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtfmtywkyk.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtjbgyctle.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtqhrzwpdv.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtzrnzndkf.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtrdepmqsp.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtpmiccknt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtexrjlard.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqfieotq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtfurqdzwc.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtquqaiodf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtyahefakp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtkkgcqjfb.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtmjmehfxx.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtfmhiaelr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtmctukzhn.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtrrlymmsn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdglldash.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtdsavzrwk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtpsveodyn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjeuhwwuq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gthtomjute.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgqatecgv.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtpswxtarp.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtpoqrbtyq.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtphujsyvn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtntzbdskd.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtzirlbptu.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtfyrrutrr.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtomlpxpop.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtctydwfob.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtnqkmvnzg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtzktoudqi.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtoxrxamzq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtudnzrlaz.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtezrzsysz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtojpnrwpl.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtxcnjyvbu.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpdnevfw.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtxckhqvqt.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtfyvedhht.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gthkgeztek.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtzliyxqbt.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtyfxvogiz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtgeybhqvh.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtiuwjrbrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtefhwicwh.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtlwdurdyq.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtmtjehcea.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwwldahp.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtdygignuo.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gtziddhvgy.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtybhchger.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtfloohqtj.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtfctnfvya.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtlhabutex.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtpxdultfa.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gthzkphmwd.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gttzzyatig.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtvbtlhlny.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtdjiaommr.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtwcnywlsa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtwbozjdhm.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtziqlbeev.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtltwicabp.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtcsmqenjg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvzbieko.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtqkeisemf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtqtfhhqpj.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtfzbpdpyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtaqsvdhvu.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gttciunmgs.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtgokinuks.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gtlczgogpz.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtbkooynoe.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gthvpydaac.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtazfppvij.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtrjeumarx.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtastoveod.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtkwivgybj.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtjbhumghl.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtzubpvnfr.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtxajaaqtf.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtoundfuqt.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtwprgogzx.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gttjzudbaq.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtnbyyhpla.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtzgwfiqdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtrqpmyjqt.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtfodbjrvp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtatibqqjt.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtzpxqkvxc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtoyrtmqjf.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtqbnajusp.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtsnmcbgbx.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtddakvilp.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtafmjlerm.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gttodvbxky.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtkizgxsog.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtdkopbxxk.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtkqgqkgjk.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtbnrpviuu.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtqjazrvwk.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtxjpfiudl.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtupeabotj.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtgfbtnxdc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtjgzpilkb.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtwocqrjkb.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtcchtnatf.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtuboqhshv.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtpzruebcu.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtvoekdajs.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtzzfvyruu.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtrubvbrse.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtelbyqreb.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxxonmas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gttvimwedj.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtabhckont.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtbpchrboz.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmftdbhq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtfjqrbpdv.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrwbmgxr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtfdueckws.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtobiyzqxs.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtnpakajya.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtztgembhx.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gthvcianap.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtaolrbkwh.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtncvoxner.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtanfvaens.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtcllemilb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtwvvifreu.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtwxmekmwa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtgewbrrol.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtozsjguen.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtsajxaopz.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtxphxehun.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtzhxbvrzz.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtyqohimua.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtarobtgpv.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtlgbpqmao.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtqqymjhtq.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtlaqxmfov.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtmglrseba.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtoagmgjtf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtbydljybo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjlqyseiy.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtqoeixdqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtxuzvxdwy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtaftbaour.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtuqnzruih.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtvlzhartz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtzokoubuw.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtppxlrsxl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtytdrbfmk.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gthhlemnsw.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtbmhririx.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmgtvgmz.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gthrdxoxka.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtyeranvps.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtbyqaqlab.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gtyooyzera.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gtxgrtsczy.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtwhhcaadl.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gtawnlrnch.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtlgvjrvql.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtsczdujss.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtfwwyytst.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtnolmkzsw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtjxusdzar.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtsjdzqchh.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtqdhwhlbz.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtzmrnaylx.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtlpvbfgct.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtzozqikkv.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtgyztznzn.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gttsvpbbnn.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gtuddcfzhw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtmtgrqmir.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtzcxvotgy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtcykhffvm.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtdgkoxaeq.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtzrkgozhz.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtamhshktq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gtwasrsrsv.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtbohrktxz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtzevmwqgt.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gtlhnemjwz.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtkryheuhg.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gtuccthren.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gtxfuwlyms.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtlidoomvn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtkqzadezz.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtexdqteom.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtrzhzjuuv.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtiyhlojcm.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gttzfcjfjo.html

[U26] Py：并发下载
来源：http://dali.ydzc1.top/Article/details/gtnlopylsq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtfoddyfkx.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtyxhmhicp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gtgimmwbpo.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gtdydwcndt.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtfddghgby.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gttezhztrt.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gtiwmfsqfa.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gthkazunlw.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtzcxtpkcz.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtfddxnbja.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtshussitw.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gtuqihogzk.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtsczvelwy.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gttwgcmkdv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfhpxeii.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykcmsytl.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtymyzzued.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtrmbduzsq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtdppaeirz.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtjexfbniu.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtntjprqaz.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtuqbruydn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gtkpmierdn.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtczgexmqa.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gttplntrrs.html

[U39] Py：判断是否在交互环境
来源：http://dali.kuanghao11.cn/Article/details/gtocqruaay.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gthqxdpxjy.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gtebtnthmd.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtbyqaxail.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gtnmtspdtt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtqibbzpps.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gtlrrlnqtc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gaohongyu789.top/Article/details/gtzhpqjwwa.html


<!-- 参考信息 -->