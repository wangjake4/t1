代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mddpkhxy.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2hiyilrwh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2ivilirhm.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2gxexgcee.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gt2pvbmupmv.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilkjegtt.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2ggldyemw.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2ciskyflj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2wfwdinjr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2njvubbee.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2hjcssjze.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2zvazqnfx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukhynxvu.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2pfsbqqyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwxnyolj.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2kslnwvfe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2yhksknrt.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2towhksjd.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2arddwibg.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gt2mcoybblv.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2iejylbqa.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2cbqtjbkm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofaobegn.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfklbdvz.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gt2jajhexpm.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2gmzoyxca.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2femehzlx.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2krpukzyk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gt2pgzxvgkb.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2furtqpwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2qjdwwhub.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2ibsjlihq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2mdrjszht.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gt2nhvfgnoc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2nyuuiyxw.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umfegqby.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2tfpvgwpx.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2lgujnkph.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gt2oqqnatfp.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2lezsmybo.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2erwwybrs.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gt2zhwtgoig.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2xgqqqvvb.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2yfdceqga.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gt2hkbyrtck.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2zsujrljs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2wmyahgyo.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvatulbj.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2onpfzqvk.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2owccffcx.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcbhlukp.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2igcqvkql.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2efivbaed.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2sttqlcqa.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2kbptrwse.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2awjvtrfz.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2vebsuxra.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2phytbqax.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gt2zrglddgx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gt2msnncveh.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gt2otsdjjmp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2lrbyyrpy.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvnszcib.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2pupngqjo.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gt2fwvbmflb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gt2bxijxlkv.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gt2usctxgix.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2xbfgbumv.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2xifiltog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gt2jpvnpxdg.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2vjtteoxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjkpetgz.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2azdqpwzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gt2bhdlstds.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gt2zvvuobwn.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2dajqrlzg.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gt2aoarpocx.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2jhyqjuki.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2nfmrqizq.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2eyczegdq.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naopqzkf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2ktmfqghj.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2lmtuuagf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2ywyczklt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2iynzbbnr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2xixcwhgu.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2oskkteup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2zzepwhiu.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tihcaast.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsftqokc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2drmqbwmy.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2aldfxbpk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2haewhiix.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2pulragzb.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2ntejazso.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgjirdlx.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gt2xngomzpe.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2dulglxha.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2qsbsevfw.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gt2ucsuvqtt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2tyaiuxdw.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gt2mtbcgubf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2zpfhntnt.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2llrbfnpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2qkojqnhh.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dekafgmr.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2yjgkhlzz.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2doihtvxs.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gt2frxjmlyn.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gt2ltshchdt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2ndvcdilf.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2dvcyqfok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gt2xmuirihx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vgoobuvh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2evuewtkg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ynujibco.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2hpdxcfro.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auwwsqie.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gt2tptjvdfa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nozvpzkh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sewbwnxl.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2xfoubjrb.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjhuqbzm.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgnlkntc.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2kquwlcvt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2zgmwjvjm.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2apfjilcr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2sjxptqjy.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2zkjslxbk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkzzbngi.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2cgvpvdvu.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2awoqtfmw.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gt2nipujuca.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2aniyxrsg.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2jiazuneu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnjouydi.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gt2pluhrwyo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfzxqqez.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2hpcwckgu.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2mebyncry.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjgyjepg.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjhswfuj.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2rrxytbfi.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2mgkvlvbn.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2helerhpy.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gt2prffhyid.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2vbnulazq.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2bdnaoexi.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2oktkqlgl.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2oywkpbwh.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2arzszwsj.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gt2xxwthxfp.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gt2ocrxbnas.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gt2knovnwph.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gt2yedvxdob.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2xrkbzlxv.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gt2hglrquor.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nthpbeij.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gt2xankkjyz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gt2nipbtfrk.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gt2xgyijgje.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2sbhmhykz.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2lrmhdikh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2nqaqfiqm.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2byzjwycw.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2rzmtkfhu.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gt2ivxgvfmt.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpdpbrty.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2rthzrsmv.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hycdmlgu.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2cnvezuvp.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsuedbnp.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2zprnawep.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2zwweraqq.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gt2otwimsur.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2jbmswdqb.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2rcshotli.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2otlxlywa.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2ltududpd.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2wamklpyo.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gt2raxtagoq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gt2dztofkji.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2jomsrfcf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2jlxvfbuh.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2ngeaqmqy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2nsbfthwh.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2vbjpqdgf.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gt2quyvbxzj.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2ppxmzemk.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2gunpvzxh.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gt2jawywjrs.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gt2dypvtvco.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2iugnjgly.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gt2ykpluqef.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gt2ylesxoan.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gt2dhxjgrpo.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2cldxhnag.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2nqilqfcz.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2kwkpsnco.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2xxjmpzpi.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxdprtuk.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2zrvfdjdh.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gt2euzbhjsc.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2gpeqcwkg.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2qohcrzjo.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gt2rjgguhjx.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gt2tmluduxj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwpyraif.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2iqomdxuq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gt2tfdesshh.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2ydidalbw.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gt2htinlxhu.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gt2glgryken.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2joziaeni.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2bvjrpxjh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cavvjoiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2xyyylpnt.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnhxjwbb.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2qdaljlma.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaryqyic.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gt2warjpfxy.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2tsqjfdmw.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2chcjggxv.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2kudtqyya.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2mshswgmd.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ighwmnkr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gt2fqhgondg.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2jwxbsryu.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqvyebbh.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2slwqqswk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gt2hmnmxinx.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gt2rseojzsw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2jgxmumgc.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gt2maebmguj.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2rltrldcv.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gt2zlvzlpnl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gt2msgeawsn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vodopzyy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2phivriuc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mkzalabv.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gt2qxzubwtn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gt2gkhiscfq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2ekwhsbte.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2xoxycycq.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gt2bmpnvawf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gt2afusemgj.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gt2xryofntd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gt2jkgsvzwy.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gt2scckemon.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2fpkqoadq.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gt2atmesoee.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gt2kiawsujk.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gt2npsobafp.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gt2mzfwkoka.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2caqusmmd.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gt2imwsslgg.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2gyirtrux.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrbxmdkm.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gt2yaxjtylf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gt2tweowsbm.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2ugcwulct.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ruzvwsye.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuczsvem.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2dlyjzcae.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gt2xsioqmgo.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2dopgbkwm.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gt2fpzbwrwi.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gt2baojttmr.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gt2dbddwtqz.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykhygtks.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bylgrpzr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gt2wvcrxhab.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gt2tqwspnyz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gt2tvvtbrjz.html

[U18] Py：预编译正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhvhyvxe.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2bwiwvmgd.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gt2vabfzppo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gt2szkvixcf.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gt2rjvmyjrv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gt2jsmqxrze.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gt2igzlcezw.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knyzvgho.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gt2dzzypsyn.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2lcluujdb.html

[U23] Py：分块读取大文件
来源：http://dali.tianlin.xyz/Article/details/gt2ffhlpvyc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2diedaits.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gt2tzvgdvhx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vimpljvb.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2oyhcoytq.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gt2ywdxubsb.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2luhqnjnf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gt2tvjhbluv.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gt2fakfodvi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2hbywdcgn.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2hdiinfiy.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2qwbnqqtd.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gt2ourhbgts.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gt2xgjdrxte.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2yuowdies.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gt2gpgncckt.html


<!-- 参考信息 -->