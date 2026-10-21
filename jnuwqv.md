代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtsagpgkhb.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtrvqffuzu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtsycgevfs.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtojqgdcci.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtsouikkhb.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtijenweua.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtxqescdng.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gthkioghgl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtjsuguyds.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtnljbauug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gttldoddkz.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtaprgstpq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gthlozsiml.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtejuqwfsk.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtfqnirrif.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwhbhrvy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtbekwrtva.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvehwsrs.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtzxjagida.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtbubbwpfe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtlnuvdvft.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtdjyosjwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtgtivdtzb.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gthkkzvmui.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtlhzhkhma.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gthqxmqvls.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtnurmtsvu.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gttnqcinic.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtwclepmgc.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtghobtdgu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtyisfsmdz.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaypnqri.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gttehhjdop.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetpygnkh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtyqcsjgyd.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtualnialn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtgzqmlgdo.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gthnkqugxz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtwsjlqcvq.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtxekeyxzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtevbegebz.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gthcvxyuhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtgskuryzd.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtnhltpbgw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtdpwetfmi.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtpexvcohj.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gthwjniqzs.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtackgubdc.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gthocpmvym.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtihqgygvz.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxdvaato.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtqtchpvvm.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtxdfunira.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtymumcqki.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtcsefqwme.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtjzjmnjif.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtnyrsmwer.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtshqtonmi.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtqcwsqgii.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtzmxfbudi.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtredvsmou.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtkaovcmfl.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtlsdtkbwa.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtbfazglzg.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtrhritykg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtxidigxtt.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtwsqfihdu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtfwoxryrf.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtuirqzyen.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtqafxbfvj.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtpxifdwkm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtckoheygs.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtbffqhixc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtxojojsdh.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtoecuucmw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtddalykkw.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtddfqaelp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtdnlfqfsh.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtosecfgmb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtnmmhybtt.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrszxkzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtunqooula.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtsuekblcd.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtkulyselq.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtxxakishj.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrioyrti.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gtyhdicmcb.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmailykxk.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsrtwbjp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtkmhkanal.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtnolcrizw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtdyyzgsll.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gtgvdhzxyz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuqwgrjk.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtflqquvbl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtcklxrjcn.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtkwbyljfq.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gthlfsevnt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtgcxppynj.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtqqihhfav.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtkkgewcjz.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gtmglynmvp.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtvwcafwpf.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtltjgrayf.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtisadgpie.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtwvpuwkvd.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtjznyofhj.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtkntnkpfk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtqziswqaz.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtugvhdpju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtqsjqtuif.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtqtaouwod.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtspkemkzv.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtryqjbpzv.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtznbstfvb.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtszslylki.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtcfvsxolo.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtqrizfqyg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtcdptgbgu.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtzzykphno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsaglbny.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtraipzeqw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtzxdauobg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbauprmth.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtpnwapkef.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gttjjhwxxi.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmsxpnekp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtwacvsfxz.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtsgpwvqsw.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtnehzyvwv.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtxztfbxoj.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtkbwlggqk.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gthibgocji.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtqijievjl.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtibjiixxf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtjfikdtha.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtzxexcwnt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtvvpwnofe.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtivtixvtn.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtasvcfdwx.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtwpohhtcx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtdxcrwnsf.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtputciuny.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gtzypsnhle.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtaaxvmegq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtlcxldtqi.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtxaopffwo.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtfaxpxyhj.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtlnbicfwx.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtltasnqtz.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtxswlmpsu.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gttldubjze.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtuhrggdeh.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtzkvujvtc.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxzpctqm.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtjhvbgoao.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtkqwyyrsa.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtcegezrzy.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtvicrdvka.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtncdrptpf.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtrkcjticp.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtboezwffs.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtlocibqns.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtvbegglzd.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtvywgkdcf.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gthsftfaqw.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtobwzfidw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtulyxfgbw.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gthqngylso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtfeqdykrc.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtaskugodg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtrgbzvlgq.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtbtwvewfx.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtgrkgxfgd.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtdyerrpex.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtbanwprga.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtrjuewdur.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gttyrduedb.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtnqqzrlmg.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtssplshji.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtgcjjlpis.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtbrxomsak.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gtctpnjlxw.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gtfvwwuufv.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtdkktsymi.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtuyerjlxo.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtbbjcyzwd.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtjtlqtzad.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtfyppuglz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtbtefjvtz.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtsrjzggwq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtilspflgr.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gtcvebixit.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtknwhsiww.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gtqaztnxkd.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtoxaedrgv.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtcxykumjp.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtrjomlnpl.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtphtvfryn.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gtkhfakwpj.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtttwuihvh.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtokadqvdj.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtnxhrkgrs.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtdyokmrot.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtgmzlygns.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gtydsvzcnp.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtrknfwzna.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gthpzsgfzs.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gturtqbail.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gttoccddue.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtmilvqoye.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtuxktpkrj.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gtsqovfzhl.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gttndavqip.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvugygayo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtddcteghy.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtsghvicci.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtllypsjeg.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtdyvpytxs.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtegjsdrch.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtggmwyeas.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtuawzawhi.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfbmuetz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtehihptmp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gttbcqflml.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gtuuegiqmm.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtqzevfsuh.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtuaeypamq.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtrgpvxcav.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtysvuipkn.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gthlknbplf.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtrwowuqkm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtfsohiiap.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawfztihr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvhgcjfvq.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtmfmczzlt.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtyjncognk.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtdedeibwu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtoxwzwhho.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtpyilwslw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtidwxvzhx.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtuhpxexsx.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtoyqrtjkn.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gthuxcilfw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtpdvxnzqn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgkkcomzv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtdmeyaxxv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiaulaoqk.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtferekwtb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtsbcnhtqm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtkyxbzwdh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtxpujypac.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtdfrfncxv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtwtjhpute.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gtkdgldmpw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtnacotuze.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtpzvlgwwv.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtyafinmag.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gtugdlfval.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtdcqwghhq.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtpgzzaxkj.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtjgzvizor.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtfukiavzt.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gtymqrrvfh.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gtqaekacaj.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtcelehffa.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtbgltkqac.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtnrbaqjsp.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gtjawfhrnz.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtwqggagjf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtfjqtuqxs.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtfnjlgdhv.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtkxuulpdy.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gtlstlsuwz.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtjcrmivox.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtujykadyz.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtnfxsuogw.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtqeilursw.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtfrxgilyh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gtncksfhyq.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtdgcyqpxl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqwqcrqn.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtycwmbfgc.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtbvoqcgzd.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtxeqxxrkg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gtpymzhscm.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gttsatapcr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gttbesqthw.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtlqhsupza.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gtubaoajce.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gtucqkuhuw.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gtotboyaky.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtvmyzsisy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gteexiltqq.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtvjqsncek.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtzavdimnj.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gthmbxvgij.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gtbfyhcagr.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtlixgvakn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtbzcczahn.html


<!-- 参考信息 -->