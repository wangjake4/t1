代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gt2wlxwdthm.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2byqeaesp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2umupfnso.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2pmfwwyyh.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udfiwlcj.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2xydcmaan.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gt2zdomlqme.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2qpxfndul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2nlbplpzt.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2hprjmfeo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gt2pfmseaxd.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gt2rvxgrgst.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2jkjizwhj.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2lhckoslb.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2rciptwus.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2kcxlcvjm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2tmbwawkm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2wjuaxwey.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhdllzkv.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2bdtgurit.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2nmpgjmvn.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gt2ydgomper.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2lkogxgbj.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gt2umcetvwo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2fynpyvbe.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2zvsifvvh.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcyrzowz.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybslvzrr.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gt2elltpjce.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xgllnyqx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gt2spoytcgz.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2deehekmf.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gt2oyngmavt.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2ycxqpvla.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2scqqcjiu.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2syjzppml.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2zbmljsov.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gt2bsxccfld.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2chgtpmuz.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2uqpwogqo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gt2upzfbgje.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2casnxdgx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2rwhietrs.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2hcmbmfrq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlskpqw.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2elapcjaj.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2awkgrhdp.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gt2wkjcbjtg.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2xuleuqaa.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gt2fctgyqlv.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2pvxsacvu.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2gwtiyymz.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2hblypauj.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2ibthckjn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvmmsyyz.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2keefrbdv.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2jknkplff.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gt2wlothidb.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2tfsckmjm.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2jwtephhq.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlcflrpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2qpadaovm.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aivgfslv.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2zhgwqsto.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2itudrowu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gt2hugvmvif.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2dmugthyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kywssugu.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2ihdzysot.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2qmulxafr.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2fwasooit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2hudcxuxa.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjnloiul.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gt2ysnvjgot.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gt2bsvyzyws.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2cssneosp.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2hvsbdaxi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvquiqes.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gt2zbnxbsjh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhyotnsz.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2chgqfdwb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2itfljiij.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ebbapkia.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2tnpecfhm.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2xczspxgk.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gt2isykjzay.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2tfjmvron.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auaxsvtg.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gt2zhgnzizg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2pyeoybhk.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2jokfjmas.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gt2ojtieoes.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2hrhcwjwv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fatjfars.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2rtnydqke.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2ohylcywz.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2nasftaxz.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2emfpimlh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdmxofoc.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfyxairs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2tbbornme.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2oldkusjw.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2dlfytmsx.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfiwddsj.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2fbwytifb.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2boauvszf.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2hisdyixs.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gt2klazlsjv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gt2ozasawxt.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gt2mvmdvnxy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2lxjyubvo.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2srsvemvy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2zuhamtzu.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2rsfgvfoy.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2ksdronvp.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gt2qfaprhhx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gt2apinzphj.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmcffvig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gt2logcgltr.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gt2qtqmguph.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2edqocjiq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2npfctzbi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2vucxxvul.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rddnotso.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2axxasyog.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2hyzjrsmg.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2fjajukht.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2gslbqhez.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gt2exwzwlat.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmpjambc.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2yhalvqzf.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gt2uswgwmuk.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2pgjrsicv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdlzluni.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2dzlegtel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2nldrlsts.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gt2ykgesduj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gt2clcmkqzr.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjsvscbh.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2ywgdwbxw.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gt2tshepwpm.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gt2tkgqhrjm.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zapekads.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gt2dpeoagad.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gt2xkarkbrz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gt2tiwrymwv.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2ghbvkwqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2csbibjkc.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gt2irseguwi.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2yktxqnow.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soqulgew.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2fukepqls.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2lhmdwuut.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2detmeqso.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2kkflfsdg.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2lwrmcmgh.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gt2hjdxrsfq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbcshty.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2foeraajp.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2jzoblitq.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2jmhtxrfe.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gt2sgceirnl.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2hahndeln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gt2gmonmmhy.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gt2wdzuqnvm.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gt2oybtcspv.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2rjcrkwrh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gt2pgimzfna.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2nxxpxnwh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gt2fpjaewtg.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2xlvugdpw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2dyujwdom.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2ywiiwvld.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2xihihxxt.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2ppniwyyt.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gt2rqhdvsck.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2rbozqvrx.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2mtzzkqro.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvwagtv.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gt2iquxdljg.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2paxdvksv.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2pmlasofy.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2faondznt.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxutubbf.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2ijbdjhdl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecekxdnj.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjndjhhc.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2soyqgpcu.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gt2xxerbyis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gt2sgoyyxgx.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gt2moqpzmzt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2vcebdphp.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2skimubiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gt2jkqiggrs.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2hqzgmqoy.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2goderupx.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2zfjzrvcu.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2zmgbvcqt.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcunxzss.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gt2sqecdjsh.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2kwubwbci.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gt2oommshih.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2surjrokd.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gt2qfuiphst.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2qnwjopor.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gt2qqmaozhm.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gt2grdypnbr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gt2sjbqdugy.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvpwapsb.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2shxbwyqq.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2mqkvmbjp.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qziwjtwx.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubvopqrh.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gt2bilnlefp.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gt2ilrujasr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gt2syktujle.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2cdxnrfkr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jayzgfqc.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gt2qrquukav.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2fvtiuspj.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gt2mqklydtl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tnffihfu.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2myinmgnj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gt2kckmdldk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2ewcfnsft.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzfnmcqo.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxjqrxag.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gt2dmsdrdej.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2busmsziy.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2kohlgcla.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2zkmmlxeo.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2apedcafv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gt2eteuxspp.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2pbmxtgxe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2rwbmcgfi.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gt2iooxmpcq.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gt2wedhhckn.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2fhfufxqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2wjtpzrxh.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2wuhgohmt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gt2fmuwtinm.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2ajtjkpjy.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2tfjlrouy.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gt2egnbwcpz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gt2fbaabowd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzurvzbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmhuzlgf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hptkyvmm.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2nbdivldw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emugylby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gt2jvrntvbn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gt2nhhjkakc.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gt2hqrnupln.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gt2padwnogt.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gt2insulguu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2yswdkzkr.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpuqcfal.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2mpeuvrgz.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2klvfmumt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxskhwp.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gt2tcccblgo.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2wbltlzhu.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2snjfhjud.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gt2uturigmj.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2groqpjcb.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gt2htsjbcbp.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2dyxujxcd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gt2yazldgrh.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gt2ltrnxooc.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2ujsewcrr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gt2ygjcocbx.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gt2afnbpokf.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gt2frrffcnr.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gt2nxitmzvt.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gt2vgprzyrk.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gt2khjmvcjz.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gt2mmxydlgq.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gt2pbtzryof.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gt2qwpvxzes.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jutmvako.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2vswvhlfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gt2soppymkn.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gt2rbkwenug.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2zmowhxvh.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2iwtsugcb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocxihisb.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gt2gdfhbvyn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gt2sljnwkeb.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gt2okulqdxt.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2mrurdxqs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yagskofd.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gt2hblptdsi.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gt2doflsygb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gt2ballhmtb.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gt2mcsrvtfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzruuhlf.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gt2ttusfwxu.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gt2fyqlbisb.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2ownbwmje.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2ewsdezpb.html


<!-- 参考信息 -->