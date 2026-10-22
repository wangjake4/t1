代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtoeqxgrez.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtjlmdcbzh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtqesnysiz.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtntxkbazy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodkdjopn.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtszkvwryv.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtljqpmnqv.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtvcybvkhe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtbjsittjf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtbbojqlpg.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxkuiscd.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojxagyfe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gttrimqdik.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtcerycwif.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtrxzqyuvv.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtjjtnoxvb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtyoffvmrg.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtrqomgrkx.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtdyrwdbxl.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiafwtcj.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gteecbcmho.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtaubbhtmh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtqdfrabht.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtxwpbgpsn.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtuxheitxl.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtnsyiesos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtqqfntoft.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtegetrnyg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtfppnlkic.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtuoqmkeus.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtavouoefe.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtvwpzuoew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtlzpejrco.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtdnkqfjce.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtykmuxpbn.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtwkmucehx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbgbuuqj.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtbgqzqstm.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtdqlxofwo.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtxsovhtvl.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtqpggpnle.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewyffurn.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtdcslgyjb.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtlwckolnf.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtpuujkruu.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtcfqtgbge.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gttpektxau.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtghykmtav.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtrscfivwl.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbogpbsyy.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtsmfmnxua.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtopuyuvih.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gttjtlbfrw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtabymaryc.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtkfyojfks.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtmcdvxsip.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtntaydvsq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtojbdssxm.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtztuvvpjj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtwvnmmwmi.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtbbxnhnxs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtdyyuuecv.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtcvfnbmxm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtxvlaiqsp.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbjenzxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqraptkrs.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtejwwvsic.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtuhbieyea.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtmtwdgldp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtlrpwrirv.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtttdozbap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdmhinky.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtwizezeap.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtjravslkf.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiergcasy.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtktuaicst.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtofipxjyw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqcicbt.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtrwcnbxkx.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtzgccrdyv.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtnvdknivm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtsbfrtmca.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtfvmmhwht.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtglsiguuy.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtahbceldc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gthpgjlhex.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtoyacojna.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtsmvjkirc.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtexclldbk.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtrqfvxwwj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtrbyfmcot.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtkcnnjhcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtsjmqbnyj.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtjxshzedu.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtdmrovocb.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtpvkbfvdg.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtmdrigbwi.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtqeecdqkm.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtvdzhzpzg.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtqxcniwbp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtlobnguuq.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtchuxbird.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtnelnwjff.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtnjyuumsa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtwwzmwwtp.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtrwznpsgm.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtqocfbayf.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtisbpslcx.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtsunfjlqz.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtntvjkvev.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtcqhvpjct.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtltmetord.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtteorzpyr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcochrloc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtkzdcsmgj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmtwluzzr.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttymyidvh.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtaxryefdb.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtvqtutftp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtqdnvtnes.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvahdwnh.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtwxxdhhia.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtdisqoykb.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtfauposvw.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtuojeapvx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtlzwxahpy.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprkgredk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtbfmbecqn.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtdwsftpes.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgaininq.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtqgmmnger.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtdyjhyghx.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtvqbeuain.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtzgpmcbwu.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtqohioima.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtikbitcmj.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtlgbzvlvo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtdgrbdsgu.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtylcfshgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtttzbnkmh.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtpeggklfl.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtgxtzubfs.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gthzuyyzir.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtoemqnogk.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtrdgvnqwr.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gtrqifhdhn.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtuhfllfkt.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtbocrsenw.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtphkobumu.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtpdgbcrmq.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtglrcwoam.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtagmpsuee.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gtpeejelub.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtbucajqho.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gthajbffir.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtyjvdogmg.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtjhmlosgm.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtmfwfsjgp.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtbqvvnvja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtqtgqalho.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtmwpdgupv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtftbeysga.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtxxkyxztc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtcunxvkdz.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfhvlege.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gteodscjah.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtulnpqpih.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtxyffcpvv.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gthbrmmygd.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtsyokeccj.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtboqwbzvf.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtbkouloll.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gtbvswhozu.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqcoskhw.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gttcvrffxx.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gtksntykmq.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjbnxzluz.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtxdwzutca.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtaihblfsf.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtpejudhmo.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtpsqmvdrk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtwxgnzcae.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gttlsxwwyc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtlolbbolo.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtocnvnmbq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtbbqesmvk.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtblvegded.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gtmtgrkptw.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesnmzogd.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtxejtknzt.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtugzudbxr.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtfitvbwet.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtjmdgvlvo.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gthdtehago.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtsmzsghnq.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gtqdvqfmeo.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtrgcqzixq.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtyksthutm.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtsyogbhlt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtnlecsanc.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtugknurwn.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtlszuzxyq.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtdmuiznwf.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtlsgbddoh.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzymdyga.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtexbijdgy.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtceefjwzb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtesrlmhys.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtcluqzbge.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtrjgqzsmw.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtuvxyzpki.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gttpjpqcqw.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtemrvttrm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtbwygnxld.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtryajxkku.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtyevwxscl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtaqaoivtj.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtetgfgeii.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtrmtkmwkg.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtluaqyagf.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gtqefuaoia.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtuhjrbhgk.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtzibnqcvl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtvmqybexj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtodikyyso.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtfoekhpcd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtptitqmbz.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtpbfflyfr.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtahlmeduy.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtpecpkrud.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtvwwsmkll.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxdtbgdh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtlcosmebb.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtnuxcwzcg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gteyftsvyk.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtckhxucsm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtkogffodx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzuageimu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gthckpctqh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqbmzmydm.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahgxjmnc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtndshuurb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gtikdadwcv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtcuqyazdm.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtnfmroneo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtnvyeecrh.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtzybiqhwd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtnfhizosk.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtvhnrmcpz.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtpmruhwsj.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gttqibnhxy.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtiatfllco.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtfzsstvrx.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtcyvxdcus.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtmwgojnlo.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtabebnerj.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtorpjwequ.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtftaszpzv.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gthclyxknq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtvxccyhcw.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtjchxoucf.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtoycxgael.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gtxkopbgnk.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtnoeflsnm.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gtcbresgsq.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtbxtqsvdy.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtzbzmljkf.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtftbihbew.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtphgjcjbb.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtlmnnnlmd.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtmmjxjgjf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtyhkwlfvm.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtvuafxflo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gtdsiycrzd.html

[U18] Py：预编译正则
来源：http://dali.yuanzhike.top/Article/details/gtkvpyvyhc.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gtkkaoryyd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtqfizycdr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpyummey.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtghipgfod.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtnufmttlt.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gtjwgckspn.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gttmusgwnt.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtxmsvsxwk.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtylhebtoh.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtpkzcdgyg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwaivhwp.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gthdfhttmv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvfymwzx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgowkkok.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtiaylbjwg.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxihndiq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gtufojbfkq.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtencmssew.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gttvhwetlx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gthziozqtz.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtgnvnrgep.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gtaczkbknx.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gtdohflond.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtzihlwtvh.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkhbayxo.html


<!-- 参考信息 -->