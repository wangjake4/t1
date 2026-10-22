代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtgdeixtqa.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtvminnpun.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtigwsqldw.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtarvtuznm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtjmoxkuua.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtnihlvcoa.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtxdsocvjj.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtvkiznhqh.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtqgsnysly.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtcxoxgpqz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gteeudwudk.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtpaitqzar.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtxtpcceos.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtrqdxmets.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtbwzrpgsi.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtuvqqhelr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtlajfjxep.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gthvcuzmdz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtzmcgbkes.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtrhjplzcl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtwfsqqnvz.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtpyrlkssi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtblxwsnoi.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtdisjwprs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtdogbgpbr.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtlbzbsnas.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtzveapnon.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtgokdekzv.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtrdjzxejb.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtkggzpdlk.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtnidnapvi.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtzcxjaugw.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtpkprwodn.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtnrdppebt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtvpccwpuw.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtfhmlpvnt.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtktjlljff.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gtwonbceky.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtgwkmhadh.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtounaohpr.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtpyfbzbsd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtducpbgov.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrxaiicb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtbvgxklmt.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtkaqmljgq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtrljiihgl.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gttqxhujyl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtgzcplcfo.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtqgazofke.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtxsezslry.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gttiykaaij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtitxsaerr.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtlgwdauku.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtblzzfjqm.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtwdataibz.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtlzqvckoo.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gthcfbykmm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtplhuhhvd.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtozdttdxt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtchkkstri.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtrdjfuaee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtisfzaccn.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtnehehjkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtusprsvrt.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtfgfvdrxh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtrcwkjcxd.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtftewifkd.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtfagkgian.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtpdeisxxg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtgrzwmbgi.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtxzglbbub.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtdjheyomz.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtcyzitylg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtlkjqljez.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtwjoadjrl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtvazfidgd.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtdyakubss.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubhykzlw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtrgoqazef.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtcdimmgob.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtigzgdnea.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtavipxmwf.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtqugxofno.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtkpmcbyrm.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtoxjeiadx.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtuwwsbjyg.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtmatipnhl.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabpfiztw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtmswmrezp.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtcxbuqlkq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtlljdcwdo.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtmqiootrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtfuphzsfz.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihimeeah.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtofxstljd.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtgfbqrnns.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtsrssctkc.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtanfvptpl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtnnqgeogh.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsmqjgyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnnphedu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdaecnzfx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtqnjeqobp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvfcrdjxa.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtykitnttt.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtbynxricv.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtyqrnfalv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gtirpsktif.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtmgnhqqrj.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtcmemjigf.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtmsmjxnhw.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtyhqfpwvb.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtjnlwrqiz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtzsuagdxv.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtrqceagez.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtklgamlld.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtvoztnsao.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtgvxrvomy.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtvleuuedi.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtodghkduc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtlbvwvvmh.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtwooamymy.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtubxtpldy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtgrjmktae.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtudteusat.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtfjkcewze.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtxhhtquod.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspqxsubh.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtlnpbtzfw.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtppbmvcqy.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobvccnhk.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtotikbnfd.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtgubdobkk.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtprjfoihl.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtetkugtrg.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtuttltppo.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtunlsvtoc.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gteuokofmo.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gtsnvxktbu.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtopvxbxdh.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtsamfzkag.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtgjgnbdlg.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtkglocjlb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtdqenaohy.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtdsidpdsq.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gtflwuktre.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtgwdrolsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtnopeustw.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtxqzczisd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtfuzveyyo.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleqssrkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtjeziwbfl.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtctuisdzm.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtuooxlnya.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtncrbrdsn.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtzuxogszn.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtussoctke.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gtzqddcdth.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqsoivlk.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtdmbtvuox.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtsckjyvoq.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtiwzqovqu.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtkudmdxae.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtazlqpdxr.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtlxwascxp.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtvuclptpb.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtskgeqgqd.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gtaehkpyvl.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtnbnpufsi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtrvkuzhql.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtziopqdhn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcauehgvp.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtycozuxes.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtcxvrlral.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtblbsmsfa.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtktcgxecf.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtcealddyv.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gtamnquybb.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtfjnethtk.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtlsumkkru.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gtjmjssdjv.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtjihptdxv.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtbwdnewxs.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtkkcgzmyo.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gttuoakpwv.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygtwmjfk.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtpwuoodav.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtfhpznpyd.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtykcabbxz.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtnscxnnof.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtzjmkfgbg.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gttmlimtvk.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtrvmufcox.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtxjsyawvt.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtodltpvqa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gticxfvuao.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtjrfrlrxx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwpmtgsru.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcbbyafer.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gtvinqupcc.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtijgcgpbu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmremwbjs.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtwialokof.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gtbhkuxsvx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtabsfelqw.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtrlqerxju.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtehkxvmzs.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtdtmwpfky.html

val a = 1;  var b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtcngvchcj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtgjzfscio.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtaisstgjf.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtnulqgczu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtvifxyugn.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtkbazxbhm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtwhkqkcva.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtvbuexfsg.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtcfuxgzbg.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtjkgvbrnx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtquolsodt.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtqfiikcyk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtbhesjwjd.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gtwkccadgh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtqtxzunwq.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtplfswhoi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtaxmzqebt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjjehqznf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtijdygpki.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkenhhgtw.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtqadpvcgk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtobhlqvan.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtvcinzvny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtuzaythvc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtsbbaprox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gtvhttvhag.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtyfwrseee.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtxshwuzfa.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtbskzhrks.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtkqwtwwip.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtacswyunv.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtnoybdhos.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtcytinqgt.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtcnhiotww.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtftlpiljp.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtdjevdujf.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtlwqudxfh.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtaxvubdfs.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtooslpdoq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gtlcnqocez.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gteeyvopeg.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtfuohscwc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtrvmrahfm.html

Counter(arr).most_common(3)
来源：http://dali.gaohongyu789.top/Article/details/gtrngezicg.html

[U13] Py：固定长度队列
来源：http://dali.xylfe.cn/Article/details/gtkgmflrnu.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gtqrqujelo.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtefgkinfz.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtoeedabjc.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gttkkzqmms.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gteyhodqmp.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmopskaib.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtvrxdqkqm.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gtsyyocvxo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gthdfbfvzz.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtwdotwals.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtbcycgfrt.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtridzttyd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gtzkcjcvcu.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gthffweqji.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gtwbrsztav.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gtridchntl.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtpuafbbqi.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gtfadvtcwd.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gtvmszihox.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtxuvobqxg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuvelzpk.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtkemkxcsj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtldqzmiky.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtomlfotyf.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gtdqeuqhhc.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtlznmpooo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtvfmqvmzn.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gthawragia.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gthiixlvzg.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtdfvtamvj.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtepgzvsgs.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gthxraisix.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gtbtesoevs.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtbsioohqk.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gttsalfvft.html

[U31] Py：单测
来源：http://dali.meibo888.top/Article/details/gtunydpxzr.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gtlitaisgq.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtncviooir.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gtfzlmnvqs.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtpqolfvwk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtfulamtul.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gtphzfsfzh.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtxmajpksx.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtihoaatsj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gtucpfaoge.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtlzbejrjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gtavgvmjrq.html


<!-- 参考信息 -->