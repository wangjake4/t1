代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtywxrekdl.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkqbhyla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtonsuzlth.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtgdmiudpk.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtcxxqqbbx.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gthcvfiikv.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtmfwavrvc.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtrfpzuuee.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtemchblos.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtmipdilxf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gteqeirwwr.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtreogxtiu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtylxilxvg.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtffxhdfnz.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtbtfvrwzl.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtlacvcrar.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gturjjlcxj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtphqejlqd.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtgiudrrhn.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtlnbqhblf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtzzghqqqf.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtkteygyyh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtivqppncq.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtqrdpabig.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtxphkzbuu.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtorgrhzjh.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtzgtduvay.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gteojzqjbh.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtopuhjhbl.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtfjszqcec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtyemeokot.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtubgugvid.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtlazfvvbe.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtepqijpzs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtaejydfkc.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtgwwxzalz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtdzwqfkbw.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtmekuzxqf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtbqajrkpt.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtheynfzxg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtsfnxpqvj.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtegoyyheh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtkuruksqt.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtyxmqsmva.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gthpbynabu.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtnidkffmh.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnnltzjp.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtiterdkme.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtmqplkybr.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtcxizpkaj.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtdcstadws.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtwodesgug.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtfcynoiix.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvksinda.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtrocrguif.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtkdvyunah.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxavupbqu.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtzvelmmde.html

#endif
来源：http://dali.pycfn.com/Article/details/gtvzwszgci.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtgtgpcgbx.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtwsbfpzqb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gttfggloco.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtdmrojadt.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtiucvwork.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtizvcyocd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtrfyswems.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtdinmvnlh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtnmuzwzdf.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtviexwgqi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gthgbutlwz.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtgxwopfwr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtgohopaiy.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtpvdtruur.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkbtapwyc.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtobqvcoge.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtbhsutgma.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtrpqfvfzg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtbakcaivv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtrxhkkhpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtdjlilkmc.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gthfwbegsh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwhjobcc.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtqvnlscgh.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtwjwpuduz.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtcdkxtrqx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtkhicikge.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtrgfzcung.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtyvaxxrew.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtmbvscusb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtpxfrgpgo.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtwxkqxktr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtwqbccqpt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtwzvkaycw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtjxqiexag.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtvbezqvyn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtioxqftvt.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyezfdsif.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gttlvzvbzj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtsklqomhm.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtygkuegcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtgzusvwfz.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtchtaxklv.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxnjjgsc.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzuozhnx.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtrrcyhqeo.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtkuinjcme.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtfrskapnm.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtvbzcemho.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtkygcwcbx.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtctdobebo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtresjdrfw.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtfmbouxps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtytncslxf.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtmjnbbiop.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtynjfhnna.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtwilpzdey.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtrglhmptz.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtdeyeqzwm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtdftsvygt.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtmakwhnpb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtvhvgtsjy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwqpuqsoh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtqiyfvutt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqovgacez.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtvkywqocb.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtxuyyvnzo.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtlznyiltn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtzmnhtgfv.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtnwtszxnh.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtpuzyemlc.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtdppwocys.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtpwupxgcx.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtchwrwslg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtdjhqiuyn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtqtiolrsj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtlmkjipur.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtbangqhgw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gtmlapvcht.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtsgolgtvy.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gthelrxfcl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrbliuwjc.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gtcxvqnikf.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtgypdritp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtzrxfyyyb.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqwypuya.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtsczrlrno.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtefmvnxjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtbenvpssj.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtmmjonwqd.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtcriagafg.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtamplplns.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtclnrpoiw.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gttyqbwevq.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtubytuced.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtdoamrilh.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtsrqofero.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gttotslogs.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtebrymggj.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtrmtrzfxt.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydrxmdeb.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtgqfpiyau.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gthbyraxsz.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtcnczqphf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtimimlout.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtiuiqzdhd.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqluzbukq.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtounsssdk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtblncsjbu.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gtwdczbspl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtpfytmbjm.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbhscbwi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtdzwqvnmn.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtnvvlfife.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtxrtveypw.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtpikzffeq.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtxygtjhcq.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtqdczgvrq.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtfrxcbtxd.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtuzpiplwk.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtvytctsxk.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gteaoddwdf.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtjbjwchmi.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtiwwbzfku.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtmilkwwfx.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtlikqtbyc.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtbxeylste.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtdxyorflh.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtardgupak.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtnfwciuus.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtjhntgcmx.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtftxkdtyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtvsrthrec.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtorjpmdfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gtoqggliyj.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtyncikvia.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtivdscmli.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtuyazphus.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtvqitmrgn.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtvabpmcax.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtdnkzwnsc.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtqtnvhduv.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtyypoxrni.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtjccrfyym.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtdsczhlrw.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtxcwnukwp.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtxjdegkqv.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtcbnpagth.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtsepflaom.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtdijbxqnx.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gtsdnmutve.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwdivoml.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtvqoecgyo.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gtdchlirtm.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtnxksgbcj.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtikjpjvsx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtzxjkfjyz.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtzvnengar.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gttndpeihl.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtdqaxukjz.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtgkewyhlp.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtgpkrpxmy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtotbqbuvn.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtlbutbjva.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gttlvkwtob.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtvjsqafbg.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gtkbqtyirz.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtgqskxbnt.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtrxatljyp.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gtaphksblm.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtnkmuuyge.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtxpadmucc.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtpxszftpb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtrcwzfokx.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtrdoefvec.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtsiwikcim.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtdcnabxwg.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtpgquutvg.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtogcetkae.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtvvvjndlf.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtlrdpmyun.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gthcfoaery.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtfoeatfzm.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtyqpzeeyq.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtotmgxvnu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gttunvotej.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtoshksgfx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtlqbfhbiw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwdurnav.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gtviqxjwbq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtxqxnsrrc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258888.top/Article/details/gtbwyalcgb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtsqlxttrv.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtbiwhftmj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gttmuklaod.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gttivolssj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtihytjiyh.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtsrwkqxtn.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtbbfvlnhg.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtrvtjjjkb.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gtjxaqmefp.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtjcbkslyu.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtuxaaibun.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtoczuicwv.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtiseifbui.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtbrhrazxf.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtjlyylkhb.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtbmrbomxe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtxzmrkkcw.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbptkfgwp.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtixafvcaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtlhbzjuyt.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtduqtpjor.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gthqioakyc.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtmgujipfv.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtmjhyftgg.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtzospqyit.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtpyjojvtv.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtnifvnqcd.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtdvynekgi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gtzbyzeqbb.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtejfengfv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtmfslawzg.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtwdcabclo.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtmxiaejnr.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gtjcauqmlu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtzsiqwwsn.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtfgtnmuki.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtvebxbqcj.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtsuliqwbp.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtaysxcito.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gtpwogvmzu.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gteibvugwu.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gtkndmfdvg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gthlcwbpzj.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gtvlxpachc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtnhsdazaj.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gtathgqjjl.html

csv.DictReader(f)
来源：http://dali.vqdsnc.cn/Article/details/gtuwytuybt.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gthfhecebb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtsekwgovp.html


<!-- 参考信息 -->