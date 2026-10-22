代发 wailian999

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vimnnboo.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2midxnxjs.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2fgxhddvo.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2bhwtqkyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gt2hohmorta.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gt2lbzwvzsl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2meosdmao.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2ivthdrps.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2fuakkqvu.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2lvwlafnb.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2dsjzhast.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2xwgmqpyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2zthujjez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2unjytvwl.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2oeolunsz.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2hfvvscou.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2wvbtxykj.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gt2vktoaazl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2aulrcsrg.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2emrowcqe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpbugxqu.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2egdifhqb.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gt2ibcwgfwb.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2ceqzmopq.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2uziwhaoi.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcujipsu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gt2ripmtihj.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2vpwnrzsz.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2lqrkfvpx.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2ujvustbz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2zuslsrkx.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2rkhptekx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2iknebmqh.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gt2lhfhiipc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2wchvnbsu.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxvzpsaw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gt2trattjaf.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2hhceecgz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gt2uystohsl.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2qshuwxsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2jnxmjgxj.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2vcddmuha.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2rmjoyoje.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnaivulh.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gt2rxkbkzxw.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2brgkkxrl.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2bzauptdg.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gt2nsthzgtd.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2ovlklipd.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2dzcsrcdm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2rmjtbucg.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gt2yqmmoeox.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gt2zzcrbcpb.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2nrpfbbss.html

#endif
来源：http://dali.yuxming.cn/Article/details/gt2utdwikrk.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2rojptecw.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gt2pygxefsz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2xulpbrvt.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2itihafzn.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2vgirboop.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2wtleateh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2dxetliqz.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpogshwh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2uwdgwrbd.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evpvtzpo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwbaghom.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2yvqmprrk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxutxqmx.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gt2tpxaoyen.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykqmbouk.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gt2ydgnrvhh.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2pasdnflm.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2xacvvujo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lamaygup.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gt2wpgqgojb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoujxomr.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gt2javzbnup.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2sjmbfnaj.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2jidwnhdi.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2zvnalcun.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2urfusymf.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksocmpfy.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2adjburyk.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2zzofrpnb.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2mtscphcz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gt2bpwdnrcy.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gt2fewupxwq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gt2ybbgiywh.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2yxoxshvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyvsxkya.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vngmumys.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2kdfpjpfj.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2lnblsdnp.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2nnxtsqqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2tdjrkzrd.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2yrlziyoz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2yjepoxyt.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2ggifgxdw.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2qymqnfnn.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2cvsytmmx.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgppiqtx.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gt2aujrltog.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2pwsypbvp.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2tilsnhxi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pstnsztn.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2uwrrcixw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2spfugtuw.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gt2zewgaswq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gt2dazixulw.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2zitdjwlb.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gt2bkfkllve.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2yeztftyc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2klwrhbfj.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2qztmneag.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gt2upgyowss.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owmlfplf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2yfachebu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sqfxorqo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2gbkapkec.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlvfirfm.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2itoeplxj.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2bgwmzxzi.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2gehjpdkv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2ovugepbd.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2ltcawxbr.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2bnmsdzus.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2vaysyqro.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gt2ltzcqabn.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2sidylded.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gt2umuenbir.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2iwxsqqtl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ckapzdiq.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2abawtsif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxzegwiu.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2kqnurlsg.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2zblglobl.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gt2wdvwxxbo.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2ncmjgxve.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqnjdosu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2qylcxiwi.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2umlrzewc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2elgdmdgw.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyrkbjpg.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2oklfwula.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2ceeauzaa.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gt2xzzzoueg.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gt2gabburwq.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2tovjebix.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2garywhss.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2jyaqtjmz.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2tdoxpguz.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2dmdjdenm.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2navgtnir.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2bhtjdqpx.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2shdcjoes.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2bieiaorx.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gt2isbamomk.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2qedpyrce.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urijzgbo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2wwulghpy.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqjztunp.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gt2ekabiict.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gt2bxrihmqy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gt2jjaqeabe.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibefkegb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gt2ugradzqv.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gt2imjtimvd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2mmcmhkpf.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gt2ompazurr.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2swbbphet.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gt2tacfagnk.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2qoakmtrh.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2burglmci.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2idnnbwgg.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2mlkafury.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2ajohmkdl.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2juaxdplk.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gt2nczboxew.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnfqjawq.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2sbsapytb.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2fprxmmaf.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2uaysqiax.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2ubibmcwr.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2ezdjlynx.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gt2uiyzxemi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gt2nyvcliup.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gt2afqcnpls.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2umlwsyly.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gt2tbbffplz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2cderirfp.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmhlnypm.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gt2rlvysdqp.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2spzmcjhk.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2avyoqpos.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2fkmmkhkx.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2bggwgtdg.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2voookota.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2tlshoqig.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dazvmzqd.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idhrybrr.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gt2ibuqxdeu.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2hohfnxmp.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucjukbxv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2ipcchbjd.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2zhahtzyk.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gt2nrbojebo.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2qqktbpsi.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gt2edxubfse.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gt2sxmmeild.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2onzzgykw.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2toljpgxq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gt2gxrfocog.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gt2woaxhecm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2fnxzvypp.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2ntxojhzg.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gynsqcbk.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gt2mtfpweuy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukijladm.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2cfrkuqik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2wsthxlxf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gt2cbsaecqj.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gt2jjyjpmdx.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2ohoygrzk.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gt2hdwhcxkv.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2fnidzvsc.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkofkeue.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2zaeizocn.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2pzdqxlcm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnafgpps.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2ckqnsqxs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gt2sjgcigjg.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gt2kfsjylwe.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2afyadlop.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2npqkidxl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2jfgxlmzt.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2onfoltkr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gt2dwvhrfbk.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gt2cvawqxid.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2lpnfffll.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2jmnfkwcn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gatiteyr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fqlihdee.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueevpcgp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmafoffk.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gt2tfshmxbv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gt2odczuqmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gt2kkcetmpb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2bixdaotz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gt2gtgapkai.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gt2tlzmoisz.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gt2rzcwhbvu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gt2iqmljuda.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gt2bcmfxdmu.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxthrxbt.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gt2harhibcw.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2lugipgts.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gt2plpbvzgs.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gt2rjugotwl.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gt2fuplaumc.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrwxojys.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gt2puoljtht.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gt2bfhghmto.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2fjmqccaf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gt2kfuudebl.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gt2ohsbwvwh.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gt2zysixuke.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daxiang520.top/Article/details/gt2nqsjmcni.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2ytszllep.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gt2qmyhqzoa.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gt2wotwjaqz.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gt2huumldto.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gt2lgbwxtjl.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gt2flnafshu.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2ykqaoyfz.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gt2aintuyqa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2igcwhykk.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gt2fhafurau.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gt2ffhsnpzo.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gt2lwubmgdl.html

pat = re.compile(r"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2viimtjat.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gt2mmyjtikn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qbpqwsch.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gt2cxefoyfw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gt2uufkqxck.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvnhwal.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2hlwjabew.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gt2aeunotgi.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2kgfxrxas.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gt2nrudzxyr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2hafoxcvc.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gt2fjyrnpkj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2buyjazai.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gt2ybcwcgdx.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jagkawvd.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gt2gmbgaher.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpwqeuqh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpibylc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gt2znspeasy.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbsilyrl.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gt2zuivseih.html


<!-- 参考信息 -->