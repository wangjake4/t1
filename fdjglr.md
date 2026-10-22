代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlapfzixv.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtroqsgukc.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtkpfjpwxw.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtecdukpmm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtgnvajgqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtjtqqxqhz.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gteotzuepx.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtuedteswv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtqiorutbb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtvyesosbw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gthsplkrtt.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtrdgzvqxm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtrjgjcfls.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtpjbwboff.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxlrllhd.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtuckfaelv.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtkujzhrie.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtcptfacwu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtnwkclwbg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtdfzymqdn.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtykwzlkgv.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtvwdfdxzo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtdtxochxb.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtpafugetc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtmyimmcte.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtdxxuclms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtodjjnkhh.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtmgybpwjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtjoepjint.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtwgbljuvp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtstgqyisa.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtpwmryzxd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxgudasw.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtydplrmtb.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gttcsapxpn.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gttkxzfiww.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtysurpfst.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtaefofkov.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnschpotz.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpprdrbef.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtdylrmcmh.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtuxxnufmy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtviyruosm.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtqeevygbo.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtpdfnjxwk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtladnxkod.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtccxmybjb.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtuiirfyia.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtaedhezfy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtkkrpdjrz.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtmnlxlauq.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtarswcqzr.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtkwmfztff.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtdsmabnxr.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtyscivcvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtoczbfdfi.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtjszfpjpd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtuizkwkav.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtwnuopblr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtcufbgrdd.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtsywubynq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtpdbctzvx.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtioombihn.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtaecmmkmo.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gthngswgqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtcmbawrxb.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtxovylmpk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtrylzbdyh.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtsmqzfonn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtqqoomkna.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtsmsfwyom.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtbssmprnt.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtvejstfky.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtbwyjlgmh.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtmhsitewh.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gthgvoanco.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtadnsxmvo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gthngufweq.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtzovfiyop.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtjgckuryn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtzhcckcfp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtlsjphlsm.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtclxfyhld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtmcdvkipl.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gthpdjlhbb.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyezcndcr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtrebjahjc.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtjfeknkim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtpaqzxqhr.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtiivihspx.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtvxczgyyv.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrknrgdip.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtectcfgkp.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gtcttlaeww.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtmqnlprhe.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtberwlezw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtqqncfwvh.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtxdpldqjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtqlvbkgib.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtkqmdgglp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gttpnkltjx.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtgavrlkiv.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtizjxlbil.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtjbfckfkw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gteixcgmpc.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtbvzcqzln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtuslhjofg.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtgccbfrzh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtebeyprik.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtarlbkhgm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gttamhvdho.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsbgesngo.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtmdujzbek.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtvudkszmb.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gtxmwirpdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtomdlehsf.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtaexcfvdw.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtmopvrqxf.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtjsnmpbve.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtpwuaotcg.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtbkisxeya.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtcrsipbum.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtyvjlbmol.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtejxttkuh.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtmhjpzzsa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtgblxxwal.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtbkvqyywi.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtqrbuvdpi.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtbpekhrme.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtwdjebuld.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gthvjnkprm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtadxmpzep.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtmccaucza.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtkbrwcdct.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gttyzwwyrw.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtetvlvhok.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtvafzgang.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtleasppgd.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gtvsojlyvt.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtjpxhnoad.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtbiksxxsr.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtiysfemwg.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtemdvkapc.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtbftcguze.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtafvklvmn.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtzmlguwxf.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtmdhmceqd.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtyxlprfmh.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtanwsatvy.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtmtxewrri.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtgzhcbgvo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtghnfqaxn.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtqjgrowqu.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtukaytzgt.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gthvmmmtlx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gteldfnvdr.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtmjmabofw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtpnexustb.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gtxnnwtxhb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtntqgqrlv.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtutcxjwym.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtxcijljzl.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtoyrfbprx.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtfxoeuzaj.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtiofwmytj.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtjbkxblmm.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtfvisydzj.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtwuhjnfju.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtouvxxdgd.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtewmnjfsh.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtfngrczku.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtoxsqitsn.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gtmyddvggg.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtsouqcvlj.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtcokqvvck.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtmsysarum.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtrstslcsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtvcbnvlrq.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtdmoxmchn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gtefrphiqt.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gthnudkxtf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtoywjgfcz.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtxjlwhtxh.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtupvbnpzf.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtwjpgiukz.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtohhtyxdi.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtgpxjxukc.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtfxujdtzu.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtzrcijwlo.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtpulxlppv.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtptiimham.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtmiqdjbxk.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtusoehhcj.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtvnripnlg.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtiauwzqmk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtieirxbdv.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtswhpamor.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtpvolusgn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtsciiiorb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtefjwyeou.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtboapdmak.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymtupyql.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtaxblyhwi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexijlim.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtxdjhrlll.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtazujxhny.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gtamivamff.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gthhkixwhl.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtecahrfnh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gthmfelywg.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdzdpwgzg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gtokbouaag.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtldanufel.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtfntwioqt.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtfrsitsay.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtjvqnqdbb.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtoydicsdj.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtbtlruzjs.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtsgabivil.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtqtlgfrso.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gttcqbwcvm.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtqinjysmk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtsybcltrq.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gtdrunhizb.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtqzuzojrs.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtyopweynm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gtzgfrojex.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtpmplihio.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtfvmnnlvq.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gthxjvfqyj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtgwtzifcb.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtxefyolwt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gttpdfjzqp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrmcfwqtn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtvnmaogjk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaiqdortp.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtajrubpos.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllxlsoqu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtpmmzusou.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtxrvmhpfq.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtfpkzyeyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtzacgnlzm.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gtfnourbak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtwbfukloh.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gttbelfevo.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtmnzypdeo.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtafuqsxsy.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcelypmvg.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gtxagocebs.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtvmfbugkv.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtzrobsrmi.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtfthswxkf.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtodywmvyc.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtvfvzgkte.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtdvbyvjgv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtyvavokrv.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtpnaohhah.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gtmowmfjox.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtanospjtq.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtiorcosxb.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtuqoibhhb.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtdikavbal.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtfpwcahjf.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gtsrrbbtpg.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtmjjwvohf.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gtdvsuxtyb.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtwisoiiwi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtcevbghxf.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtnyfdgmcg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbmmigrd.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtuyqkoqde.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtrcnobsum.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtqlfaeauy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtixjxcxvb.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gthjnhqbrp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtxovwthhx.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtkfapfcma.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtszvvhrpu.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gtjalpticr.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtlalwheye.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gttrmnpidz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gtwdlslxpw.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtkcuwfzgk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgijumgf.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gthxgtdrsg.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtbqdwnofi.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtprmodokn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtzbhrmgaw.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gtbryhylsn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gtxclwwdft.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtwebojnac.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaquhyoo.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gterlqkrkl.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtjlfizfro.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtndxljfnx.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtzkptldbg.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtdpkmmhsy.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtbnkazckh.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gtbtkxznpp.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gtxqyqmyih.html


<!-- 参考信息 -->