代发 wailian999

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtxifywxjt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjvcgfhav.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtebqegsyr.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtlykpgpwj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtirtfjkci.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtcqxchdps.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtnqhrobxh.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtwxsoanhe.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuygaeqad.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtyqrqmzoe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtxsihgcmp.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtzaqwoxsv.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfgrksmbc.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtspjeuwyx.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtmedgjmim.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtanoekdzq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtczjftoks.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gttfrpdmfo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtzvbthaok.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtrorylqwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtmawlaebc.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtmyiqjrrr.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtcppbiyoc.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtpwjzlott.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtwbmsyccl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtbdypmylb.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtsycyzhvt.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtcemscloq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtbauolprn.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtroojdnio.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtubarsbrj.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtfazfovvx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtwnfjmmce.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtklpuuljn.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtzoxjfquy.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtlquslorp.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtghtkmofd.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtxkugmvdb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtzgmvruuq.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbzjdlyw.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtpvkguvts.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtuyafdksq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtjdkcbpfh.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtdlsemszx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdqaqfga.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtwupxfrcw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyugsnxaa.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtpckiwpek.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtxaxbvnhn.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtzhqgwjmr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtwbcqkvpg.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtsqiyafbd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtrorygdof.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gthcsxjxxr.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtndjgukoi.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtvobfatui.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtrfwfavpa.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtyliwbwjo.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gttymafysj.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtuutpwzol.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtfwczqoxu.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gttwvslrrc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtgopxknre.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gttkpldeyj.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gthqtglsmo.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtwpasnpzc.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtargoksyy.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtflwcuagt.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtvqmzyryh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtipsngddt.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtjqbhgqgc.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtjrhqjbif.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtdeazwvjz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtrngzpmar.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtibkotaod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtddlelkcx.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtvakwioep.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtgghvcafm.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtokfhqlur.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtlnvaswlo.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtncrktlhe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gtkglyhzum.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gttjsinken.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtsbuofnwr.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtusanrooh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtfzfjoocr.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtjdxixcit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtvtapjges.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtvkrswbmm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtmitienxw.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtrksmgjeg.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtmkcselvd.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtzitnyiia.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtiuwqacod.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gthxkwkkjj.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrhujsvj.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtfzuganqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gteldlljba.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtyejgokuu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtrbsygywj.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtilzalrak.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtjdjjcxaf.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtskyxwmxj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtqgafjvzq.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtgjsbuszf.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtbhxasqxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtvffedrxg.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtlcneesvx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gthhmrbhlp.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtxvkdrxfa.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtfsghfifr.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtjkmiegpw.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxscqlepy.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtagmdafqf.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtbpkamzry.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtqgffokyc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtvrmavosq.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtofmydxgl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtjocoypsg.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtuuqfagwm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtjtzaqdlx.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtpkrvzuce.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtfjagprka.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gturaxumyk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtrgzpehgz.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtemibhhdd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtszeaiefa.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtxuufzrti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtozxsauyx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbenayjzm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtvkytrgag.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdcffhopo.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtxaplpzir.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmlepgyq.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtobuwfwuf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtrqmqsaha.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtfcqwkstf.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtuoohzyae.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtsulckxds.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtquvzyltg.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtxisnxuoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtbvmhewpw.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtnncrucgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtzagwqlxc.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtygrnlibm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtbutcmwok.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gtzksdzezl.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtvgavzsww.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtekrypdlz.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtcgzgdrrn.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtyofrxjle.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtkhorotax.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtwemzqycm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtszshrzeo.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtiiknbvzv.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gttwjacqja.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtnymstovk.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gteocdzsek.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtnfwqeoqz.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtowhsmkyf.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtryjffnna.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtkpkeqvuh.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtjijbxfff.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtofssgwnv.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaaedehx.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvrhvgxn.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtnpunzohx.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gturkutdoh.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtjnnijhur.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlynujnn.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtforemfsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtacxnvaou.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtoiakdhdy.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtsummezws.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtrfsgfrci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtbipnhivb.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtmhzsyfdw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtklsaxmww.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtxlmwewho.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtmxoqbfvc.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtptyjncqx.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtbaulicbe.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtqvngjyeq.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtzuuqansg.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtrfjmhkrb.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtvaczwoqj.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtlvidbzbh.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gttrdbmpha.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtwjjtmfmw.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtkfsbhzyv.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtpsqpebmm.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuekbdskh.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtucatlodv.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtmkxbghly.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtszkiwfze.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtjbrwtizn.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnbvlzla.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gteazkilti.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtzacdxjte.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gthitjiyza.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtspihrvjy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gttjtlqtnx.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtotnsdbyc.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtfzhwxnpa.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtiuzqltmc.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtvnxcovft.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtxfnlptkf.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtbtdfhcae.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtkmrwoast.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtclcqvwch.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtwqbgvokc.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqtexant.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gtkzstyzqh.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtwhtbcaof.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtuxncmbwn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtspeevyjt.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtaeiyosfq.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gtpzygavbg.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtxbaxfmav.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gteafyzjoj.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtrlbprgvr.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtoqqufffp.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtcpetbezb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtltqyxeok.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtnunlpnao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtjxjnxxsq.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtcpkxillg.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtulzvsiog.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtpxrzgyet.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtpowbjgmf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtkvgqqzez.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtgkmgehyw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtwcuzfzjp.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtrqxihpdd.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtycfrkiwa.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtwwrxalmf.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gthswdjnhp.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtvweogqsg.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtgksvzpol.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gthxjdzvof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzugypwqb.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtzzslemxg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtioxjlqqz.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtwkrbjqfc.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtrmygxqxu.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtckkbwvgb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnijkogg.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gtkhlqmarr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtaeznefwh.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtqkznebeh.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtjifqtsls.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtfhirpadq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtmkrcxyvn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtijgvcasj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtnufojuqk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiutdsebs.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gtwyppuqhp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtapccbaje.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gtixbxbsnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtisdbutio.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtndciwunk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtrtwgvxrd.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gthawgjeue.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtxomirbpq.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gtqcxrgqkw.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtzvwnqpzt.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtdsmaaqnv.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtlewkclba.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtxnonjpmz.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtknppobel.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gtbprifhli.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtzfsxqsxb.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtotzmcdey.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtojwsgyvx.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gtbrclerii.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtvemakspb.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gtyekscpbk.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtwencpgkk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtahnrxgfi.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxowdktxp.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gthpcwrusm.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtjrfsspxb.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gtruhzxwht.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtwufiuehm.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtatxqdtds.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtrnsktbnl.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gttodwotzo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gtjcxtufrq.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtzvbguiwf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gttrodiygz.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtyeaacefg.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvmmtpeo.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtxfreeaxb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gtwzbmfnoe.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtcbmjvbyd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtwqcqljlk.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtuhgoiqcv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gtwaegxaoi.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gtwqmcugad.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtsjpzcepn.html


<!-- 参考信息 -->