代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtqjuzslwn.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtdspwewqq.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtxeosuywt.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtdjtsngep.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtcysbygjm.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtodpyyumq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtoypmwfps.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtourdytgp.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtgwnutqgq.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtttbarvzb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gthgmpclwd.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtnxruzvrp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtmaeopsro.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtuvyksluh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtvvdudzir.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtiyfxcpuw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtzfwbzgzw.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtgkgkwvwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtpgcltoou.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtqfboydyr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtzrtitooc.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtvijegdrs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtbasfjzvg.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtqvqdoopn.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtjdgdzotc.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtwwbhfnhb.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gternisxfb.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtvcmmdtcz.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtwvmrlqlr.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtevmlovgc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtmuzyscji.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtrjiunety.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gttcqlzcat.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gthoxtxpeb.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtadlmpwco.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtwnshzsqh.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtqirfjcvq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtinogohjk.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gthxfxxxrt.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntpjdfxs.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtqcfpgeeo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtzbtvoezu.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtaaswlcwn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtihujtqhy.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtqbrqdzme.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkfznthq.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtpzgosbwr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtldvrkcvq.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtdugazcmt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gtuxqtjpix.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtoezxvban.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtbvzyjfyv.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtjomlogsf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtuitdtdtv.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtnptqbkzy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtbabpdrxf.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtlarnpnll.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtwoeedqys.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtgymbxqmo.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtdyoeghnf.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtxepwqizj.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtpuhnnkxh.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtxwsdojuu.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtdkhdkzqo.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtoxopntai.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimmjisqq.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtdjuvyjdd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtfotbyjeq.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gtmscnnvet.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtoqaajxkp.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtbbfgdmoe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtundljkwk.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtjzscsuuv.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtqapzrzka.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtmwtmbdrk.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gttzovxyhh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtvuezyeex.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtlbsumaet.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtvdwcpbsg.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtkiiwqquw.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmiymycv.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjpwxwhl.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtucthxvwq.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuxcohpsi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtgzcjqgnf.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtjyefutbg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gthmpiigjb.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtjjkrxbxq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtvfszxbcr.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtfzjfxbmx.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtfyqnbaal.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtploocpbs.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtgzweypnu.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtuxpmzgrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtkkdgqwup.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtlmpxrnaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtlagkemjt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfdkdogto.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtzcykwbtd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfffyzhgi.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtcofpmpwu.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtlfrnvvzi.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtobyyhrjv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtpnnfruhn.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtiogsasph.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtameojcux.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtcwiqkzob.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtsghjmytt.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtgyuhmdni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtafsjbbov.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtwvynoecs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtbdnsyovj.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtjasfrkjz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gttksqzukc.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtskvgzmqm.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtrvwojgkk.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gthzygigql.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gtrlxxcedw.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtqnujojuu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtjqkaqikf.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtrjfzmplp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtiklnoene.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtqrpgydmg.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtvrdqwory.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtrqhjqe.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtjdrxsaep.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtomjpjjmp.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtwkbyhdxm.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtrbdpmqtr.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtmhfrfqdq.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtiaimpxbt.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtzhcwvqsl.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtdyqgrvcw.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gttizfjrof.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtxmddatvl.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtrrtznpqk.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtnnvggjit.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gteqwqxlux.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtqjcrkquy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtyxbmdewb.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtebhrzsqh.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtsujfnngo.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gthqdtaerl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtyrpiaxxg.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtchhzedab.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gttqmujdkv.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtbsgyqliq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtgvyvqsti.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtvacchdds.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtodzcmggw.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtldvkuvpl.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtxjqobfcc.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtikkjqcnl.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtglwafpvr.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtoaajvkeu.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtcenmrixv.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirargkfm.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtsmvcrexw.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtxpobpymy.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtidfxkoxd.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtcpvjoyrv.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtrptkyjyc.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtezdabjjd.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtqefwkwzs.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtqgbpmmbv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtrhrelowb.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtrisozqjb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gtpvcixwpx.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtirantipv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtktcjvwee.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtxxcxrfjt.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtervuxtrp.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwrvsbuk.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtkcclpdkc.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtngnqkuda.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gthzjebdik.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtnbbxgfdg.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtoasheckm.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gthuuktsha.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtoxuodkpl.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtfjxxnrvb.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gtwzylcyox.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtvavnkcsc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtyjyhrzhk.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtaxttekrh.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gtoqmzjufa.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gttcgncucz.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjfljwkvk.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtmpzjomfh.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtxxozvkhn.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtupbxogip.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtowgkxcak.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtstscvkhb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gtcgnhrdly.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtxmwaafqs.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtmqujhlwk.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtdvxyfquh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtkajswrhi.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtbspvvcff.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gtwxwglcmy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtrecemdco.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtwwiujics.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtngkieznz.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gtpuegxnwq.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtouulcudw.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtpaszdwib.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtmtfxjwsa.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtxtpesqbp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjprvlld.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtlwstwohm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtwjpansqq.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtkvckqeco.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtixouiutf.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtoktvkmuv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gtargdfsqy.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuxdnqld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtuyzkbmxk.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gttsifsvyk.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtomlddieb.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtbyvoauhq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gtlhrmgiju.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkkpwssuc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtvdaptawg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlhmvwlpz.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gthltzhgbv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtjwldnxzb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhfikkx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtelagjlvr.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhpspurn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtccrgjhjv.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gtehgerlyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtyijvrown.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtylkugqby.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtxbiooqul.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtmoluqcbt.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtslpahuad.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtahspgthl.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtknejpa.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gttzbgvztb.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtazqfbznq.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtcsstgqvp.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtrqmzeozq.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtyooejlff.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtzxcwgcya.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gtugkwnzug.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gtgmxdezsu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtmrczkswt.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtwftafdrs.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeaxhzqh.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gtueectfgj.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gttfpmlboi.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gtwbfttscu.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtduujoacz.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtriigilhn.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtbcsdzzkx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtuzfysknt.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtjsqiiqay.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtgjhhlrnk.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtxavgrkoc.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtxencmjxv.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gtwkekggax.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtczjmueda.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtmfdqujii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtefgglzvx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmkehegi.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtutjhnp.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtbwkgiixf.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtljiiwtfv.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gtlvcmocay.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtqjxunhas.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtkwqngqzv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtlgbwwgie.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtmjvrtndp.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gthmvouadj.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gtwyzpykcl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gtdvsngrjc.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtfbuzhetc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtuyujcrrk.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtgwempkon.html

UserId = int
来源：http://dali.jinqigufen.top/Article/details/gttawuictt.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtianicxqn.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtjqtvtobi.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtfhgwgpah.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtjcnvmqke.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtmxyrdald.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtxqffezvn.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gtsszaikut.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gtifthbtnb.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gtdjcfebsq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtvxdjjnps.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtdxsuqlpo.html

chardet.detect(raw)
来源：http://dali.meibo888.top/Article/details/gtwkpxifch.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gthtyclwfh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtutnyjwqb.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gtqqwymucu.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtkskugwak.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtrrdjbumq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzotztqt.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtryqgvosy.html

Path(__file__).resolve().parent
来源：http://dali.shangyingyoupin.top/Article/details/gtiqpxlvzu.html


<!-- 参考信息 -->