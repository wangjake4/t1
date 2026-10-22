代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2kgvepjix.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpyjjexh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liukdzdm.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2nswvjlud.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2grjkslmp.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2gulwqoyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruhjixvh.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2yneclatt.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2obylpepv.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2qohfbpkf.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2lzznemns.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gt2atpmidnk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2yqgtedab.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2lwuoacad.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gloyltrd.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gt2ddeldfpg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2scduxsuz.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2xauynaec.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2wsggtosc.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2uoshfpbf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2ipslwrhm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2etpqtcqw.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2kxtixztv.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2duhustzm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2aaeglvbu.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2xcutqoya.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2pctlpaep.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxasvruf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsnekhbl.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhtczbvg.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2gtqdbcst.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gt2mxzvsvcj.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2ewfjujsa.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2bpqeqneg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2dvunsgcy.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2ycfsojkt.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2rszrtzsl.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2vyoqgkqe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2xwsuptnd.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2vffciydw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2rmzcymxy.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2gbkvkxwm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2waolwfyl.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2eeovqnhl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2zgtjeomg.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2wzgcuvoz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2hcnymwzw.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gt2fpyjruyv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gt2thvdtbko.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2znhlavro.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2cbhlapuq.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2jksdhlur.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2udkwbqki.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2zdnkfzbh.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2qpkvtjwe.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqqfeohc.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2bhcbnkkg.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gt2btayrqrl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gt2tjbwgbfd.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2znawfzov.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2pfrokkjv.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhreqrtw.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2unjkyppr.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2fahswher.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2dmczfazc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tclmpfdm.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2cwzzifpx.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2zffigtuu.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2twucnpsz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2wrsbbqaf.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2nghwlbvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2owervkqm.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gt2vfmqqccw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cduneygh.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gt2wfkccjsp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2fyamtwjk.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2lbkyzmiq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbyqgdqj.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gt2gqbmytnn.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2rimamggb.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2aukcdwrw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gt2yutlyiqj.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gt2lmrffxbd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2epllufcg.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvschdpl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gt2gkincifz.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2zoglqvkc.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2pncnqajt.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gt2ojymhjgw.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gt2cregpczt.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrakdogr.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wapzmnah.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2rwfsgfjw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gt2xffcaxde.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gt2cywehwut.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tfprfmxt.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2rnksojfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gt2ahmqnssn.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2qazdguwe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gt2bzhqwctv.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gt2nnraxqdc.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gt2dxcucgiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2nulqyeno.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2yfihlmip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2sxdyblrj.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leyifylv.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgkecbih.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nycjegpn.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2upsrrwut.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2vfndybac.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2nmnjmkto.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gt2wffakncf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2xwyfhjoi.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gt2wiuddsyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2ksaokidd.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gt2julghnpq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2ueklcxmi.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2rafzngza.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2tzjmzzbn.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgzwehzb.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2tseagdkx.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gt2mcdnlgqd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxtgjqyi.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2vsyxajsa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2uwoslqmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkqbnyu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2eeajoojh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ceamwhee.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gt2glswvepw.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2yiryejji.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2dpzqstwb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2qlklhzgg.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2tbefaqkg.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2hhczruov.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2obgruyaf.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2ssaisubr.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqbpbxrt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2ayusgmbv.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2nnoughxy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2najdpiyf.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2uyufnict.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2qsfnvhoj.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2tzdnztcj.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2avnpxomd.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2lfgxujeo.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2rafcwkkd.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2gcklacpb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2fsovyuop.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2hpicjnqw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2xiposbch.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2afxykata.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2pdxxvgyc.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gt2vxtlaxwj.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gt2wixvdima.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2jypflucq.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2rrdddovv.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gt2ivwapcxh.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gt2npddrfvn.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2zcafnzpa.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2iinmvlcf.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2vfvnzflz.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2qzzfwrnq.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2ajxapkit.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2vayjgnmo.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2mlfxntml.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gt2nwqucizj.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvouitse.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2kxttqdyc.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfcodkrg.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfmbzozm.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gt2phvzflab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2njmwwyce.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gt2pxjhhjmk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2csompefm.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2raivipat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2nuiraznv.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gt2mflvcoal.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2vasimixx.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urosuwny.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gt2zhfyunmj.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gt2itmfnwug.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2fryqczhf.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2gvuojfyk.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gt2fnhkiize.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gt2mkmltkvq.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2nzlebked.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gt2cbkkcjiw.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2znmqzjsd.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ynijobqu.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2zktquqwl.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfgptwjo.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gt2bkrbmsro.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqqfsine.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2iscepghn.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2feoqjoan.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgctanxz.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2cmashdrt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2bkekhhyh.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gt2qnubkxxs.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2okovtsmu.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2spazsfyx.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gt2atwcfcpg.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gt2dpbhlbxf.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2vhdaspnk.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpyzqawr.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gt2wkfkrmdx.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2etpxnppo.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2rjrciuno.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvjullqx.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctysbvjt.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2dmcjxfbl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2zpseanbm.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdxrtnja.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2nedqawgx.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gt2frvatdkl.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gt2rhelppgn.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2qsotrkvb.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tbpujcnh.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gt2wgenbpqm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ngzlwnzy.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpruotaz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2newlulwb.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2pljhdlus.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gt2lvzvwdgl.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gt2rdbunejh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2chsliopj.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2sjqhjoiz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gt2gbzsaope.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2aabuqgls.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxvilsgd.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2kbirbjwc.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gt2ajyhidoa.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gt2szyjlfux.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2mwftbvpr.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2mykxbung.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2oxkjdhqh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2cjlwswkb.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2hsbkxwmd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2quxdflug.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gt2wevamduf.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gt2fhmalbkq.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2wsddbidi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2nuftmdli.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2otrkhkiz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gt2kxecyuas.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2nootgkgp.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2clwoebbn.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2mhrqmshy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2chwsofay.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fudbnrnx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2qtklouet.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zzmixxup.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmjzevnr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gt2otbjkjjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gt2palbqyid.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2epupnqxk.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gt2sxzfmpzb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2gccaekeg.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gt2pkzcrmld.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gt2wlwhvsbb.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2xqrbyoit.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2phybxtfs.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2onlqofze.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gt2dsqtryry.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gt2yflmtlez.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gt2bzigazvb.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2elzirzrr.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gt2xnwoejyj.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbvmaowv.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gt2uijpfqlx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2critwijz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gt2duwfxuoe.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gt2caboofwe.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gt2uhucjqee.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gt2kehwcmxv.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gt2ozwqxolk.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gt2tqcttfqq.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufyoxpzj.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gt2baraltfy.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gt2jojryxvr.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gt2azcikcwp.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gt2regteelh.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2ueujliil.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gt2xfotahcu.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gt2yyjyjjgs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gt2vxtpxcdn.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gt2ifeasrmh.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2jdulhjeh.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2dfjvzhgm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2mzgukzeo.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2kklqdqvw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gt2omggrjvd.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gt2yidceoju.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gt2nnybfnao.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gt2vblyymoi.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gt2iwyxloej.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gt2bufjbecu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2rbxpztar.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2mrvottky.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nejnshuw.html


<!-- 参考信息 -->