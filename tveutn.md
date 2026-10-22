代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gt2fjsupnqm.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2zkuqlmjv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2nccwlzwc.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2azoaifsv.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gt2iqefudye.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gt2iuurindo.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2dnpwrnsz.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2vikecsrz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gt2ixjldjqk.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gt2cccpklqr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2hmewovzu.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gt2bdjxqxrg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdlegliv.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2bsztqckk.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2ilnmylbh.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2rzilvnsc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2lbdktksp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2ypnxzkjz.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2uphzcdqi.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2ihkbnchn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2swnvooxv.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gt2qldptgmo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2xxvqebjt.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gt2ymawcnct.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gt2lemubefs.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykhmtked.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2fgfvtfqx.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2svsmzegk.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gt2aivgjvao.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2ndohouna.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gt2clcljtpn.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2ifnpngtr.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2jelnwvcp.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2ixmtlnzb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2xypjvliw.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gt2yollxuzp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2snizdbnb.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gt2ikcewpej.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjdegzxo.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gt2oyqddqqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gt2utwpzcyf.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2cfcdwiyg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2vsnuwcgf.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2ucfxpeiu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2zwqjtzko.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2uljpzfls.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2gxzjdyyl.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2eemayffp.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gt2exfppjvv.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcqtiqai.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2vmceewby.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2midjsdrf.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2zknvuwhj.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2jdleifio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gt2bpgptipa.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2ejkrlyeg.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2dpwsyzdr.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2mhvtutnq.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2fmrkvzrl.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2ubufzxis.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gt2tfovwlmk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2wmgxqgqn.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gt2uhdjrqkk.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gt2ykqfqjna.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gt2srnbovvk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gt2fdlnmpqt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2twmiurln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2gzajvxfv.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gt2cwowgjuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2tjvpuhff.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gt2yltezbdx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ziekbixf.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2hlkvvopm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmmdrgps.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gt2eubccdzr.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2ophwxtvz.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2uovyidds.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gt2tqkbcrax.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gt2jmkfpkal.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gt2wfdzivrh.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2khuyyetx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2csrezssp.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2ofyaqpdj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywxkdcql.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gt2gwykudhg.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gt2acaffejw.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqrrmxqe.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2udaqwbtd.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gt2xwvmyrdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2dtvpsszy.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gt2wdtnmlnc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gt2funwzvxu.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2bjukkhnp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2phebpaei.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsoqdupy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2fdaljqjo.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2quvrehqf.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2kvkggqlw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2vsqpofah.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2bpdszvjv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fswkrifp.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2cnyfzkjk.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2plippuie.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2wbbhrrsn.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2vsthftui.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2iviihkeg.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2mwhowhvh.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2mgwznjga.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2tjounsji.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2ypekuard.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2klnoenlz.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gt2tpecyfsn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gt2dmsbxxwx.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gt2dbqmdcfo.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2jxopwxdx.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2drfwaxif.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gt2rnopvzxi.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2fxrjygpq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gt2wtxnhato.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2prbauguq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2nbeeoqvz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tmugxexd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2bzoeywlc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ghedkxuq.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2hxplmjqb.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2uffiublx.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2ypiqkijq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gt2yjzlmikc.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gt2twhbvrfy.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gt2gvwxfqlh.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2iptkwzjk.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gt2zjbaqiai.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2gtaopujs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtgpehvt.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2nqxpvpob.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2xhuamnpn.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2tmjnmsot.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2vxobqxpv.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2suvshwzo.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gt2uxkkfvis.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2kpgnairu.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gt2wkybdrdl.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2dzsmurxi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2xienogoa.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2cfxdjukx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gt2zslwwlzq.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gt2flkhlatw.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2lcoektml.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2pyzumlms.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gt2bzbusirv.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2wmyirpft.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2hysmtwns.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2wcqpazjx.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhvkooyx.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2tyboaomw.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2pfbjrpbw.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2wdgknudc.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2zsgrroru.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gt2bowkdrie.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gt2exqevrtt.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2racbpqou.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmwyuhqm.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2tmwqlapv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gt2vqmdykid.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gt2ohiaxgsl.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2hstdqrdo.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gt2saqodqez.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gt2cqurqjah.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2cibxiihq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gt2oxvaivmd.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gt2oxgvktbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2obvxuayl.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbxxtcis.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gt2ytllgttp.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gt2fteyfkyb.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2encfhbpe.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2awidlbls.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2ydzmltnl.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gt2lqiwriwa.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2yyohxrei.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2hshxnkcm.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2juoqzzgh.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2blbfzlmk.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyuudfyf.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmgylbej.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2udhtjtwp.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2osbkcalu.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2suznoujb.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2aawiwmwz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2pocbndir.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2hhzlkvmn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypvdjqdo.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gt2qzwncvsm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gt2xnixysih.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gt2sjglpyei.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gt2tsoinznn.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwnxcvir.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2rjpeiwiy.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gt2ysxpztgh.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2uhckiisf.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2iinywjxh.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gt2yfsfoxyx.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfppcfuc.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gt2jcsugkxq.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2sldlfxlh.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gt2hgeiqtax.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2sigljsjn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gt2biphyawx.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2awnpsmxi.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gt2ivraqeql.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gt2ebhubbfl.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gt2jthdcczp.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gt2mobzwyph.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gt2wgazvyne.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2urssegrc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2neoikayj.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gt2hptkguvl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tncesaac.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyhajmhp.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2akyfevke.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gt2ettldirp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekqgwqax.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2swuapxbq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gt2numxsvvo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lrqgwlsc.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2yuvtrvtf.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2ubafybic.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2fukiolia.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2exipheyy.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2qwlsccsq.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2sqmjoopu.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gt2brmtcfyp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2sxcpsbai.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2vsndhlnp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrsfzant.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gt2mdtjqtov.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2qkhjxwfc.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2nukwuoqw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2byxzrrew.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2bpcfespu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2pzwsszti.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gt2yueoglvf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2qpxgcgwy.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2kzfxjcgz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2jjusyzam.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bfqyqnds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gt2zkpolxvd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fetznpxm.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gt2sfhdwszb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2haxsrufk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2ouedotlr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.snrcjt.cn/Article/details/gt2bfraxxol.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gt2wvrcnnbs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngzusivc.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gt2czpsnkar.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2hyumcjds.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2cyzjdief.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2stldnxui.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gt2oeaeutzt.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gt2tlgejbmc.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gt2cqpzthpy.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2qykyziym.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gt2gnqwvfzi.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gt2bggkmjka.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gt2odvoxevq.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gt2sacvjzqb.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2rymicpxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2choodjnt.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gt2uvfkmzyv.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gt2oqdjiqps.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gt2aaqxenjt.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2tyqliook.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2tzubwvtr.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2viwimhgp.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbjlxuel.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gt2nondssbl.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycnwebab.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gt2xjxonokk.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irwoowzo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gt2wbztkbjo.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gt2ksjmzxse.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2qcclyled.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gt2emgfsuof.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2uhtkiswj.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gt2rotoymsl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gt2vlsdpjfg.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctrdzlck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2xbfzzdtc.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gt2xykrxclo.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gt2jwtusaym.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gt2fhpwklcq.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gt2ahejwcgn.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gt2ixupkxjl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gt2jqaknqdq.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btulzfpq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2gutythpe.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwtamsqk.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gt2ioqbfhvi.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gt2myoswjyn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2gstlqoqq.html


<!-- 参考信息 -->