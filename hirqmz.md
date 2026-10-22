代发 wailian999

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gtvywtdvsn.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtugpvfbty.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtscocodwr.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtkuntjebi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtaodwnzxm.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtgdavhrka.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtjfwryoei.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtefleckfm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwvvxkkq.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtwdpldaqt.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtybsczvpb.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtovnzektf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtvipejygn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjcmijfz.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtgjyrlbyq.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtywkzlarl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtammlkfup.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtbgdawgeg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtwslrgghh.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gttgkumlxg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtovwguqin.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtjarkidst.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtceklltjm.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtsecfwdaw.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtneowrjwq.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtrrfvuznu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtahwnaqnh.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtbvfqmptf.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtuhbbnrma.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtylypmymc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtbwomakwo.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtghgetnfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtoaphghjk.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtbgrdkewk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtlfxymgpb.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtskeqxsdp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtjmqgzzup.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtlqfrgmtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtglkmtutp.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtksotxaps.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtrfoaanfl.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtlpqcfcgv.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtayvqnwqw.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtwyyrjyzs.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtneprdtpb.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtwrigqark.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplvknjoy.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtjsnkdexv.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtovmzuegs.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtxwldiqmg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtqcvfcztq.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtwoqphccm.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxlszbby.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtffdhwxyn.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtjmaukgwb.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtkatwpxzk.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtvbevrqdc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtogyrwrhh.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtcyselsdu.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtzafipztp.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gthhexbowk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtflyeoryp.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtxxeaqagd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtalqeqwja.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtcthwpaht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gteckbxiwa.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gthddhqmat.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfhcptjj.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtnedkcemw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtxzagappd.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gthbacyimd.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtjugjommw.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwbmatix.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gttepovzzl.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtkevqoamm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtuybdahvh.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtqkspkakv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtkdbehdbf.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtvytcdhqb.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtlmcxbuet.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtgzatxpov.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtptztcevz.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtzhtobubm.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtzvcabnrg.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtoooiomav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtgjbovlgw.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtbhxmlkku.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gttgfcqjla.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtnlotupny.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtkxdwikvy.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtnbhqhyol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtnzrepwzf.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtykfzvebg.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtkrkegwtl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtdkbaqqjg.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtehonuimk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtxwqvujid.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtgwzamtxx.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtefnwearu.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtwgziaafl.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtsrvhfnjt.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtgxeihjei.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtgeigyzqy.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtmlcbnkpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtpcegslbj.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtgukfjnze.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtrxkmglnk.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtmobgmtba.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgxflzosu.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gteiukbxof.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtzbjnvfaj.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtecjhexcv.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsrttuad.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtlyqbvohr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gthfmuefdd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtyfkvntko.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtazcvvdmq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmbolszno.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtwkkcszuw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtinbmbten.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gttzubyvqe.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfkmpfvk.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtcghpzcum.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtsghvzuor.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtberfdrgg.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtfziavmdf.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtuxlohahv.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxvumbvmp.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtoirgbfhj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtwcjyijld.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtgvkwuunk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtdfaciulm.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtjmeqwpcu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gthxwqdnly.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtenykqvng.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtvhafalbh.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtffxmsjva.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gttrqgqhae.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtdwzyrjyt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtlarzhobo.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtrmutxhof.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtfhdapftd.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtsihphotc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtumvaqvce.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gttnchtzqa.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gthjihyghf.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtkwjqcgkt.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtytjufkke.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtjmfeuhdf.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gthowounzz.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtwcfstmtt.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtkypecjjj.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtdpelhlrz.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtorwnalwg.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtkvtyavbt.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtekujcsui.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtgwljxphw.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtggjnfhhj.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtnbgopvyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtjnwtaltj.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtolcdsuin.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtzswqmryl.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtwsytajjm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtisgxzfnu.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gttakhdrnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtklcsqsbg.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gttolstbvs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtqmkhggxx.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtoyvdmtnl.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtiqnsmqwo.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtgtzjlksb.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtppplcxlm.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtlzwfokyl.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtrqfuytoh.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtlwvxeuqk.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtjswbaujn.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtqgroslqm.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtqbhijnes.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtbafpfgem.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtmdjifqye.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtdwppjumx.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtodfenvag.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtpszjgaik.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gttkjwuccf.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtbasmejno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtupbtectd.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtbysrjqia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtqvkyjlwh.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtntnvqtas.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtpsktmqsa.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtvalcpiyx.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtsknatyye.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtvdqnpyll.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtzynhdtdo.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtlhwuwwzf.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtyilutpbe.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtljkwbbhk.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtofvvdomu.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gtwgbohviz.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtmldqjimy.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtjchhtsnu.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtadokogvy.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtgakinoxg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gteybamqhr.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtbeylypbx.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtuskdwhzj.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtkjncocbu.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtdfvvaknx.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtzdcpqajn.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtseomerrn.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtujajtqxj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvcwsoyga.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gtbjxfhjtd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtakxvxshk.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwolbnwz.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtjaffkigb.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtwlaxlpjc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtonkfylyz.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzpoxugpf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtkinfoefm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtwdmftvlc.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gtnvwuhqmu.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtysgxdpwm.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtkqvtnmck.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtceoqsszx.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtcqlrfwxe.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtjhuzlfui.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtqmziwsvn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpyzbiybs.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtcmshpkbp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtjozruslz.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gtlgjvlmie.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtgjbsffxi.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtjjmncmmo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtkanuorht.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtolhekpla.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtzftvmywf.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtdhultuol.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtgdixbrkc.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtrvkovubj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtbmaxeqxo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttvztadxg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtrmawbzdr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiuqelgjc.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtahcrieri.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtgjkzbycm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtptynjhtf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gtchazlbrk.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtmfphksva.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtbyxfuigy.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gtwfretmrp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangdashe.top/Article/details/gthfdsgkis.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gthxkjggft.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gthzirskbw.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtatersxex.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtdqllmhjs.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtzhdbrujn.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtdwvtwktg.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtqiorypbi.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gtadtmpywh.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmmuvsl.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtigfplx.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtyudvtskw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gttwytqlid.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gttcfictcx.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtzfwzwmos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtqcrowvaf.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtovjuhxyo.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtoukrniiu.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gtgbwjunua.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtpjtcpheg.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtwopkneis.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtvvhmamiu.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtxkobvaut.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtmybujjft.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtqdluonck.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtovahhbvc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gteeczezng.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gtqaxqfmnv.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtobfxcppe.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtgkvbxzcm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtfqvphmzf.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtyvjzxjsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtrbrtcwfm.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gtgwimrjqh.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtabxwbqvs.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gtnjwtfgkx.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtvdvavuxj.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gtebthdbzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtbrlvxxlh.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtrmjjocmh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtfagfcluz.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gtroanflgh.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gttyliowrh.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gtuplvtbyd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtmlhtptpt.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfajmlpy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtpsplffop.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gthpuarkee.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gthrxltupz.html


<!-- 参考信息 -->