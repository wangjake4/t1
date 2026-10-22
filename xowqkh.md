代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtfblqboxk.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtfukahwzw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtpoyaiqjc.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtofdbesgw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtwkavuhhz.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtuvpefbyv.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtvphcxqpb.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gttvtwjgui.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtzputqlij.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gthiqxtsdm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gteiwdmogm.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtadwjrrik.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtdrjheoqb.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gthzsrycxe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtqjyvszes.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtcpqfgysq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtuyenjsow.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtaqnjhqvi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtfknrmdij.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtvlntryio.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtucucqnlc.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtprfvxbml.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtlbbhawuq.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtrdyjaoiu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtqtkgnfkm.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtieeqytel.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtvmjlkujo.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtimxnjzfk.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtdzdamjmd.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtnbbuolyc.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtaawcewfa.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtdgqjgqlp.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtwumkbmdl.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtxqcxqsrp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gttgpmhoxi.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtcfttxmmf.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtagvajghs.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gtdyqwfbay.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtuppedsdl.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtewklslba.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtfiaelddp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gttagpqodf.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtxdhgxgam.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gtwjzhylak.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtyzyzjdjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gthshcdmkw.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtenbzpadi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrpnnnxxa.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtjjngmopz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtlfwwdawm.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtoyoxzhnv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtrsbggdiq.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtaqcwvler.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtmmcnzdxq.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtevpiiyal.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtpqealjwp.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtdaxhmmnm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gtmuefgzwj.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtuepfutsr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtvuawasht.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtjtqoxbbv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtorvixqas.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtwpvcxjkh.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtbmyxdgmm.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvslwsobc.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtvgsedtww.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtmfcziamn.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtmveywcjb.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtdvqinrms.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtxvkbmxmm.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtgzwskwsw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtmryabesb.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gttxkwkvka.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtgkpzbewm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtgjumkknu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gteesgdxny.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtjkxjjqee.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtyrhlbuhr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtascrhvfn.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtbxwwfcvo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtowpvfwvv.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtlljqgsuo.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtyktbwiyw.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtfxyqnrgd.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtlmghxumj.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtfefhtnpq.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtlhrftokv.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtklrewlue.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtycflhbsw.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gturjrsrhi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyqidnpf.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtdaxucmhl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtkxibplib.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtzyudaauv.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtqvpmnafd.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtenndwcrh.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtrpofrxiw.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtxvoytqee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtvrhfkmjy.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtgijuzrjb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gttqtdmvkg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqblvilwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtiywnpgrv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtspzpiosh.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtrvlvaslm.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtaikqhmpz.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtzegpibkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtpvtkikdd.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtedkgsiju.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtupznfrux.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtvywvmrwc.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtnlggjznl.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtyihryllw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gteggpdild.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtefgvwbfe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtgvbaoywf.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtvxnczusu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtkoqehiza.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtoqfvryoc.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtzsjmecil.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtfmtajpwp.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gtjjeyatas.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtdvvapvjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gthvlzbwyc.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdspzpmja.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gthbmlfigx.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtxwsvmbht.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtzymolyig.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtxrvzniiz.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtwfamzkox.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtigtvfywi.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtsdogceyf.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtdbraxerx.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtedvrsrfw.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtrunmqntu.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtqijnsnrm.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtxpuccgva.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtczmmyjqi.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtprlsnnim.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtmqgnhags.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtzhctzwza.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtrkudbebj.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gthekvlztr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtepurkgmb.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstiiowlf.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gthwlmncws.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gtsrjtayrs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtmkazetjs.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtrvmiibyg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtezrhbyyc.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gteuqhqnfi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtoyxkrzfs.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtjdmmsnth.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmajghtka.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtasonrwwa.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtjoqcyopq.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtvjvvjfrl.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtvevflueg.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtrmqcdmvw.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtehwxwgly.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtheefneqe.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtfrffbstb.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtyufzzxlb.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtxpjijgpv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdiydehar.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtgsrgshbm.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtarvwmtto.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtarvxqvxu.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtkhrloaju.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtctfdnwjb.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtorytaxtg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gtnljyvghr.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtexhzgxzp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtyfzmklut.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtzmydyvcq.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtcvzuxzvx.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtgkhajfsv.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtcjwersug.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtraxlgeys.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtheyymljw.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtcxmxkytm.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtpbaagmyy.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtptdrgmrr.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtwztyfqay.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gteccojtqn.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtiknkrktg.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtmydmchlq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtuzvbyhzr.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtludgjukf.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtctsailvo.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gtgkpkcugs.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtxhhwktbc.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gthdynoxmc.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtismmoceh.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtcqezfwvm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtngqqivnb.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtoaqkjmda.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gthddkylcd.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtuiyrxpum.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gtqwkwcumc.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtffrqlzvd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtitynekts.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtezikuxhu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtrifbaaen.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtumuwerhn.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtvleyigtr.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtazepvkbj.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gtifrggnit.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gticmwqbui.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtiyntjlfk.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gthlhtqpkh.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gthbppqmjr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtisuamqgx.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtzjquniiq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfluzssd.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtdzogwmnl.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtyagfpnoo.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtfvfehfuc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtcxlwbyqg.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtvatncyia.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtlnuarsew.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtmtfjnbno.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtskwdtdbh.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtfrolzlca.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtivvemxzy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtijrgqkts.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuxfyajv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaekigfkn.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtrtsiimlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtxrnyvbuj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtncdaavzw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtwfeuqody.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtitegdmxb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtpfguwxdx.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtqedafknh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtjcblezfm.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtvzirdesg.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtukiebkzl.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gtkrlbhjpe.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtyhjetxbh.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtbltrrkzw.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtvxvdvpna.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiovqxse.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtqzslfjow.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtyhjpobma.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gtjmxwqdyn.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gtixfmuoux.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtqhcxgvgh.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtwxgctobt.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtffphuavm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtfovyhswb.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtpivlwuvn.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtvqzrxofa.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtzupbotwz.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtgieiqqsn.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtzcsvzmjx.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtqxetawes.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gtvdgsphte.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gtkwuxctrx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gtgkkmqmye.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtkqgmebsw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gttoolbkwl.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtvusfuoay.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqyadqkb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtapuvaujk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtgubrbgmz.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtbjhxymkx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczmyapgi.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtohzkkwhf.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtcnxkafyz.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gtmntixpmd.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtbjnitagq.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtpkgvbtge.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtfnbvcvpr.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtrfogttlu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtdmdgswaf.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gtlcwiduyn.html

csv.DictReader(f)
来源：http://dali.nwbrower.top/Article/details/gtyhxxkhas.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtiqqmfakt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gtkrfkjiro.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtymyfxzgy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gttxeofbww.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtlfaxrshr.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gtrbngcamp.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtfselavzx.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gtijxabtii.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtefbmmpog.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtfxtefdic.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtreshgapu.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gttpumjjut.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtvjqzykih.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtxgayjeuf.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtlxfbozkt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtnsigybbg.html

[U34] Py：判断编码
来源：http://dali.ydzc1.top/Article/details/gtoabmpydo.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtaxsdazjk.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtsbithclt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gtkcdmsdol.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gtodnaiviy.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gtczpkxzdj.html


<!-- 参考信息 -->