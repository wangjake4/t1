代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtwnrfhamv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtmzygdhgw.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtvzklpheq.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtaztqjmjm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtohaitwli.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtfdinywca.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtzbjwlcgi.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtaigoxuzq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtibplgilk.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtqfydjohv.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtjjkvghxb.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtvrjzigmw.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtnpwroxvz.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtmrxykdnl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtlmoqpvxp.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtcgdiytku.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gthyiltwyk.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtdcfqthug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtuiploaws.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtjmmhsgve.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtifhnkjvx.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtisqmblun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtxscxtnch.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzdobsok.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtybbuhetf.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtvzridjsg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtkjsgmidj.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtgebslbfj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtzdivqudr.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtpbaqjvso.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtcftkppaj.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtznwhxlez.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtbkkdfsov.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gthnkfljib.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtyyyclmsw.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlmlgeaf.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtjerfldub.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtawtxdflg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtugpqtkml.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtsmcwozeq.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtupeaeemc.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtpjhjgoxn.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtdgkrgqsu.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttjqduyig.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtsqcdwotn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtjnmtadlr.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqovacdgk.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gteyzmupao.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtzszbpfhd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtrunrlryn.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtogvguodg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtbksemifz.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtajrjedtm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtxbjtonzw.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtztiopceu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gthlyjvtcq.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtlbckamjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtfgxxjnnp.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtoxnrjefh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkjstfkz.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gttmhwtesq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtiklxndch.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtvrvpuivd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtdppkxyol.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtxxjyjunw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtfnkndvfj.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtcguejeer.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtmqqamunt.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtgtavfqya.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtseefprty.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtdjqrezxs.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gttqoxednh.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gteyhbyvfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtctuhirsp.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtlfcrtplb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gtbmlmreeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtpaqnxlmb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtjxxffcnh.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtzlrnxxlc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtixhojgsp.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtfgfluwkw.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtrifsbgsx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtzxwtxhbc.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzmvuqqa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtmiduirlr.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtdzujzrcl.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtyqqjikbh.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtxedhvfwj.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gthgtbqwhw.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtsuwzapvx.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykgrebrv.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtznkgluda.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtdbogplsz.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtjdjkgsgx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtkggysrxd.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtakdgielz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtnzbhkgbr.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtimcvtybj.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gtrupohmpp.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtpoozkpkf.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtjnxleeqb.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtoebqewiy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxknmijed.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtwvrwytdl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtsttgofbx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqajeyjan.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwdvrvbe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthccnlybm.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtbdbpmreh.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtbbzdiozj.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcwljqon.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtdtchfpac.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtycugeogp.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gthfgmlkpz.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtxkzrrpgc.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtxkjlaxzf.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtkbmqweaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtuvipobcn.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtoombwqcf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtdacygqsb.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gteafsskva.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcfpxmix.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtojmhuter.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtgciofesg.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtxggllmry.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwithbqsw.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtkncfjgyy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtotfrvvgq.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdtncrcy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gthxzuzaqh.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtopiovawx.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtdwqekqpo.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtejhikjjx.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtzgjgfqwq.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtzoggqlnr.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtwtgracqa.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtgbkokwht.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtqqpypbdx.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtfkvrsnzh.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtstijguxx.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtcxvbovin.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtdtvkqrzt.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtjnywykld.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtetgfeooj.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtspxxkvsd.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtstytcdyq.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtmjksiubo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gtpcjkemgn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtdrtfnowy.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtgksljcpn.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtlpxncuid.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtnjhuezik.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtwjjnxuzu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtkhbjofhr.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtozdxcxzw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtujvtdafp.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtukjutebf.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gthrlmfhwk.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtbaqgwpls.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gtzxlhiaho.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtwjldtrcc.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtmcdcfh.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtgcqudqyk.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtgsadsrpz.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtgtcikaag.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghfqfsta.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvafqcph.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtvlhenhvu.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gturrlmgnz.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtdditrcqa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtqwdjfxyl.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtdqzonpmv.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtjcjayndy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtvbgxtuff.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtouisopbl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtevwrhnkh.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtcpvjiuds.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtydknocsy.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhnjjnng.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtkdnoephl.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtnapktkdq.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gtenlwafhi.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtdkbfuifd.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtfdwhgccn.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtnakzaxgg.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtcqoywkxw.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gticgmtuxv.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtckkjrewa.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtxzqexijs.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtejqxomop.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtaqejxzbs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtwskvclpx.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtcvvlweje.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtvrmsrbnz.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtuyejluye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaufluzxq.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtiupnkftc.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtqoewpiwe.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtdvhtoxyn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtudykjcla.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtmznqdzna.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtomxwscxa.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtlzgigmsm.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gthfmrmbcc.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gtubndirev.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gttlumpuxq.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbnvpwbmq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtyxqmiisj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtbsubhbnq.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtriwqkvhm.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtztafkmzt.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtjzckvlgm.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtpvjpoeoi.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtccjxebuy.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtfdfrrehh.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtihpntynw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtstvjxlmy.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtoqzkyvgf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnkmzxne.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkbebvxh.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtzbuacahi.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtwkkednhf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gthugkluax.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtnuvqyzra.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtzqfprukm.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtzemnogmh.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtmwsdnurq.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtacxxslvi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gtxrfsifmt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteglrhecn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtynckctfn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcgqcycuh.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtdzkyypjg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtjdflucfa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtwuuyyyeh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtvcqcipnb.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258888.top/Article/details/gtdajhsthu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtnqpioalg.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtawdmvhnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtiyrcrgsl.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtvornovda.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtukmcpvpj.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtmjqjrahx.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtinzyoryh.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtcpjadzbf.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtfbcaxoqm.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavduqurw.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtnxwwoyya.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrcbryli.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gthwjzcqvv.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtfwjbscvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtjuwzokbn.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtykhfzsse.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gthjocpzzf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtzqvvdppb.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkltlowva.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gtmfcuzkih.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gthytrwrbq.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtwxlrctwv.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtqbvaphjg.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gtucnygazp.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtcmgwvkji.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtudtgclph.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gttxssfsrt.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauokczsi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtsfacrxon.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gtbdtpwmpm.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtscbfwxim.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtggmmisxn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gtnwykurwz.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtbyzrqghu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtutcvgjvy.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gttfptniuu.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gthltowupt.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gtnajgoymp.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtubrwempc.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtxxruxqvz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtxllrybny.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtoouotlkg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtkxpeukdm.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtchsitqqu.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtrssjhpxx.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtkkyyguov.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtuegoznvd.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtxjiyewzd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltkjwmez.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtxmsscjoy.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtpehhvrhe.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzfyrchl.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gtzjoqmzdm.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtgmrsdnee.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gteiminwlb.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gtwyaucpos.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtdamkikjf.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtgilucqwb.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtpzcnruts.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtuyoxyjpj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gtzgatbxcg.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtwrcrkult.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtmmmtedjb.html


<!-- 参考信息 -->