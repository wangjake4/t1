代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gthdptonmi.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtwchydjsq.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtnxmziqcz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfxswebfh.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtkalokzmg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtijsvdgmr.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtvplcuzmz.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtvryeifak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtudeuktbc.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtabxozdlw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtqxihmrez.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeumpufv.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtrrspbjmo.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtxawwmcfm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtqktsbqaj.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtikjqqcfi.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtwjxzczfp.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtvhwbqlab.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtxrxvrisu.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsdnddsi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gthksrcoyk.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtxuquwbcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtthxqguyi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyeehmur.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtirphyser.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtqljxbawv.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtiexvrudc.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnzzdrfbl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtjzbnozvb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gttzcbxaus.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtvcgojthk.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtnrcxvizd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtrckjpwvw.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtvtwpiole.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtzvcoyobb.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtdtathuiy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtftuyyxks.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtxjeyfjpa.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtedrfqntk.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtqrvamsbs.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtifrjklau.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtwxvqxuip.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtbxdqktoq.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtckhyxfgg.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtzsojvgtq.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gttrkivrnq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtwvamwmmu.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtuknzvwkr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtldpvgkcd.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtmpmkeimo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtuliujacj.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtautyshen.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtnnogtjmq.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtozmsizzk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtokwczymb.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtfzvclilm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtunmfhikq.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtubsjmrag.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gtvmtmnstu.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtmhyuphqe.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtrfcdwdpr.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtvmhchymu.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtxzcujjls.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtynrwzctv.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gthqgfpejr.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtsmidsbgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtlujqsfxd.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtzkboicge.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtuahjgbwl.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtqdlervdv.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtuardxgfg.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gthcxqhftu.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtwztvgrly.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtiqmrshoy.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtgzdbocnd.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtqnmbbyow.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtxcuynphl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtvnninghr.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gthbtlzpyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtyolqnxpf.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtzqeczohy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gttylayxvj.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtnvnkrfkt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxumjfnnf.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtppvtpbqz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtkgplcijc.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtykjglkwe.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtrezccykw.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtxbfdxcxu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gthojgqozp.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtsaiguwuk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtrwkhdccn.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtfsozrmfo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtmidkbucy.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtcdzpibfp.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtycysedta.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtxmgnnjpe.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtihubyzdj.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtmexjsitc.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gteevblyum.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtotwdgtoy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtcpysodxh.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtsfhewwac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtmaqhwgwe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtvdjvbebk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtkptzfwya.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtzztsuvug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtynblmoxn.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtllgjraot.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtdqoabshv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrfzcdbp.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtzdtfijkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtsseekqyk.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtropkjyku.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtgnhevoot.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtgyqschjz.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtgarazzfl.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtokogsahd.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtofxxreow.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtvwkiljfk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtdjsureus.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gticxvzxnd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtzyusupcq.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtpewnkuhi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtolcibvoc.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtdmpenhzi.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gttofnqdrv.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gteillocsu.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtysmmvxye.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtlmhiqucn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtvtbstdxd.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtrotokiil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtbgnocycw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpmrnbcsr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtdarrbgeq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwntiiewy.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtgcpnuxuv.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtmfyecuff.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtspbagzdb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtrijwkyzl.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtslsepjkg.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtimejbmby.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpplmuemu.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtytlgekqu.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtilpbigod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtnvqvaaio.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtzaenycbd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtgppbuxsz.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtzjpotgjv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtqyigfbmv.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtvhuvisco.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebcqhnha.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtdvffoooj.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtcsavuzqq.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gteylnmmip.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtixxkmddz.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtuexxvhzt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtpostfrem.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtlhuerevj.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtfofkbkvm.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtmakdqytf.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtjqmyrnkk.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozurbhdd.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtmaghufsn.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtagvxivnj.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtxejmvdxo.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gtnaruraad.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtbwafkayc.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtbuhacumy.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtfikwtvci.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtycaimjxv.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtokbipikx.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtehtkkzuk.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtkofzarun.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtodzpcxwp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtzntvxuzb.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtgonlwsod.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gttzaxutya.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtivredehf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtmvjqmdvt.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtxnzhkhkt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gttciqagce.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtslijnybg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gthfsjjntq.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtvnrtrhbw.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtaeeyrlga.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtwsvskqgx.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtxgkdmqij.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gtubzpkzmq.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngfeogsy.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtvltzpxzl.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gthucumfqt.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtqgxuuyqv.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtmnxvxjww.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtiqlgwrig.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gtyvshykku.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtyorepmfk.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtummtqoxe.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtmqjqzfgu.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtbblxnxre.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gttkmxrwnb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtxfdofalt.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtvgxievox.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtadabxjfb.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtogujzkyj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtntzurklq.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtpuaycpoz.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gtqepyrpvp.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gteemxufba.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtrtdxihvn.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtrbfdlqau.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtiphjxuww.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtzszhybzb.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtwulalgov.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtlfkjerqf.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gtifnbotwq.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtkjtygvki.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtacgvqtwv.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gtcsthtzes.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtghjisyju.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtimuztrcr.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gteqxulnuu.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtmworoiap.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlxzkceis.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtacgpregy.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gtonisjfob.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtyhqekuvb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnsshijfv.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtihvjiiax.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtkfryvdzo.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtcoizdjgp.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtlfksacsk.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtrrbisonl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtuvqidxzq.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtmkhdzshj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsprxwkm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtodtsmjja.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtegvfdqis.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtyxjryeqn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gtlibgdswg.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtbgmlfong.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtrezjbwld.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwfcizgd.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtqdidwuea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtigeyickt.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtfksncsdb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtesnpducx.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtaiyrageu.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtwglwlnfz.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtjfmxexkh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtyeckroos.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtdvarelvs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtdllqjnse.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gthxuqmbju.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtgopbjjkq.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtbagtfeql.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtcsduliwd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrqbgvevq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtkomnqmkr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbxbkrxp.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtfbhcvklc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gtnbhgtcip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gtsfhvzneb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtjaylvbwm.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtpucouwry.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteemxianb.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyujnseco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtbpkrufmv.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtalboqnvn.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtwaacxzdh.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtjsjakvwf.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbbolrez.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtxobdknwm.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtawjkacgs.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtcbkrkvss.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gtvbnyxexp.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtlyyhhozm.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtmsozmgpo.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtzciagwal.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtlrnhujci.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzknknxu.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtjiegvzbj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtkyvzknwn.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtrjubmypb.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gtyvagxkkq.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtatxyigie.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtcjwlwmiu.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtorshruqx.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtmkhxwnku.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdylxein.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtqlqlbpmn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtkpggpjug.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtlpdadjfn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtmcwwfohf.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtvfecuegx.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtbgwmbcnf.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gtukpplath.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtmdyowzuh.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtzdjaaydn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gthvoacgvl.html


<!-- 参考信息 -->