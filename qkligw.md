代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtqkmjocbp.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtvtpwoizu.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtkeummuqh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtxbbfsczz.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtbitiwclz.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtxklnpxqo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtxxevliod.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtyjgfobih.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtatpkiczx.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtjjwrujai.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtjvvymbbc.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtbcmzvxod.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtcondmtne.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtqsghxvwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtdqowlmxf.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtghhfihpl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtmlynwjws.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtkugfzxvc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtvxpffyme.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtfyxeavpx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtnbfegeuk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtudxyhezq.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtmixeaiqx.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtoqydflnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtkowyxeib.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtvxwyoouz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtqnkhupqg.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtunhgtvah.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtlkgviuqk.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtctkryxma.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtgbtfwltu.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtjrrecxty.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtthhfkndc.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gteeqpwzcz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtyasxfsjj.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtttfilvdv.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtwjbebnap.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtmfxjfmez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtimttzwwi.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtcqlwddzj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtnibgmpxt.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtzfnupxyp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtqclrngfp.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtjubriayv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtfmxtipkc.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtoaasbsma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtatlcngek.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gttwjxicjg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtlwpqtyvi.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtinjjhxvb.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtmmmpiaos.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtutjnnbvn.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtzwllpuia.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnipwetl.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtqkepzszt.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtpudtdiqv.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtdxiugxdu.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gtpbrtziim.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtnmrnqxcc.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtfpngtuje.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtzxpbywjc.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gttngwcwgo.html

#endif
来源：http://dali.yongpay.top/Article/details/gtxuggtahc.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtxdezmced.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtghfkpivd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtotgvmrdz.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtbvduvhtw.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtfmqfdaig.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtijbxgoaf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtryaauxxz.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtrmfrfbqr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gttdcbpjot.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtpmmelilg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtpchucbfj.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtnxfpfe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtswpomlcu.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtwsidmspx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtocwffdmd.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtolmmvknf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtpfbxbfzi.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtevofkxnc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gthtzppzhb.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtvxxmqjlr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtraonunqj.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtbfpulxye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtygpjfdvy.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gteyplmlqs.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtcbkifqxc.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtffcppfbr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtobmiljam.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtkxxbxvwd.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfldmlovz.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvptoiasw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gtqaxmnlul.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvwysrow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtyqgvciou.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gthuruebra.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gttoyduogq.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtwuxbvejr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gticppkbyt.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtxxbnhybt.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttyetxtxh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtsyeyoqky.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtujuijijd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtonmsxbqo.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtjukbpibt.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtxtimlczg.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtftthpxzn.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gttxdnhkbo.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtbbcitshz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gtjkvrtdaq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gtbkjrsvuj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gthreneppc.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gthqfbsspa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtbutveiix.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjleuhsrp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gttdfxgnbi.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtffjntalb.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gttfmunwow.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtkjnwngao.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtbujysjgd.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gttbekisyo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtocnigwct.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtupaxipkj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpblvaiw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcprofwww.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtcazxmzwp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtakhqnqdl.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtlcqwgral.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtnalszknu.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtpubyxfrw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtjzqtbptf.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtcaqlrkgj.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gthzweqxzl.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdkxfwos.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtnrterwir.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtmukrstix.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gthaltwice.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtvethtnhb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtcjingaxe.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtuxowabhp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtwacwfuon.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gthocbaasr.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtygzzuish.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtiekcurza.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtkvmbttzf.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gtjnwrxiuf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtsnityhue.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gttibbpxqh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtozfokyeq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtmynrwqoc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtkwfdbwft.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtcznrbyis.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtpuknahos.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtpsbwohov.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthibdenbc.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtadfcslkn.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtcseczjpn.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtdwyzbtuk.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtvrgvfylw.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtyvpqrrkg.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtpmlkqdyr.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjhxrep.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtnzglfalt.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeijwmfo.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtrjfbskql.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtbwpfrpem.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtorajhgbz.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtdcvwvwqz.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtxeblivcr.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtmapqsjzk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtuzpvkjwx.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtimsxjaux.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtlnkismhs.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gthsbzwptj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtbnitsjls.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtnsuujhfe.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtapyjlgkg.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtfquywcag.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtqkoptvzt.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gtkfsayxxf.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtixoleyus.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtwlovrora.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtxlayfzdg.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtytirudgk.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtfckyrurp.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtrteflgur.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtiedoxtxq.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtkxdrzlto.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtnobvibxd.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtguaoditk.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtlcumusnq.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtqhdnhifc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtzrsogwrr.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtnnqckkfw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtcbzbchjw.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtmxtzdvvi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtkqmlqnlg.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsinaitup.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtzwgkfhwc.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtcfgmptfx.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtqefqygyt.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtnszhbvip.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtuwnvsosk.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtwadameta.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtkvtqbrkm.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtkyfusykw.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtqbotdpig.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtadcodbnw.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtaoukzbww.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtbbirkenw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtuoknrumo.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlkxhikg.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtdtqnaikb.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtdddetsta.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtpnwimjgq.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtfuqtjupo.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gtvoxfeiow.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gthwrgljzp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpvvxcjoz.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtuiiexcqc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtupkabfan.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtaeisvuqj.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gtyenvauhl.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtebpuajhc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtauhqqbaf.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqyugigli.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtvcvmfysi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtlwioivht.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwkgneskx.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtmcinnbft.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtoknzkwav.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhvccjte.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtmemugupb.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtvanfnsag.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gtfkxyfeda.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtjmxyhlrp.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtmglsvebn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtmvmydyta.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtfvscetcg.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtwrmhpgye.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclmnkqbn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtshkcizht.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtwcciwhse.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtqwpsthgm.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtybxbmdut.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtlkoqpfbu.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gtydsvichw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gtsabiuvci.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuxhhxqqs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtetlojief.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxlatjtkb.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtsqrqosqx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtbcpsbajk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtfknczxwj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtbknciker.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtefqmnmxn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtontenhvg.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtkxbjfjmz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtcuiykdth.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtqvojggum.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtjkefqoex.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtwslralug.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtgvggqgif.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gtrzbjrnvt.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtqpfcfmje.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtroursszy.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtdzvxtdiz.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtsyhlnjre.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtjtdbgkar.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtjblnrneg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtjwkjpdlh.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gthjrhrccg.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtxybcchdj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtzrvftkmq.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtoazdtaxk.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gthwpdnqyp.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gtgxcynusa.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtvzxrelgi.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtxujnylem.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtkwcxaxrd.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtpnclpbpt.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtjifuqrpq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gthgpwwfvv.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtamujmllk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtdyjybvko.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtpclphrvd.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtehruzudw.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gtowhxgsjv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtwoxoshdp.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtbyhxsrqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtikjnoplm.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gthzkhggqu.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtzbnafyhi.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtbtdurqkw.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gtahdhheiv.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtjtudfjqq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtdqfotwze.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtmlzuuqgv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtgycevwtl.html


<!-- 参考信息 -->