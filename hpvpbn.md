代发 wailian999

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2byypprkb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2uiqjytfa.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2uwslxkva.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gt2jcughcae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gt2ykyufxpc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spqbbfqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gt2duisvwrp.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gt2qbxxznoj.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gt2xkhapfqa.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2vwmjkddw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2xfbktprq.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2pfyxbaaq.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2iirgowfj.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2yfhkxrte.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2khwnmjom.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gt2fihxrvia.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gt2zldppfkd.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gt2bwnyutod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2mrpobbrt.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gt2hjblwqfk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gt2hfqosdrd.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2vhpnozrl.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2pkodgtev.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2knrikkka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2uvwkddff.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2gclmxvwo.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2zbzsrghx.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2qkpajozs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2fbkhqsfc.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gt2gksyalwd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2psmdzcfb.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2kwbujzty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2mtuoaotx.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2jexvgemh.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gt2bgiwktya.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gt2savmaktc.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2ppxvxpbh.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2dijxdyjd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2nzywyvex.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2kedzvarf.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2ihkfvavm.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olgupnpo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2axlyqpzq.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2brofubxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2wmxdddmb.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2xglzvqfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbhlusov.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tddshjrl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gt2qnwdvgjf.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2inqmlann.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2kobeaowo.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gt2zzdnuujs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgmrykxy.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2symknuzf.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2bckvzmqk.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2pccpmonf.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enmzdutq.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2xgfljqwl.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2jehbgmtu.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2qcqusptv.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2maujjaeo.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gt2droxsmuc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gt2grcshnfv.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2vyxfnjfs.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2emhmhibc.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2gefpsbaf.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2ljzmifwo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vozubiry.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2mxojzlob.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2taiufpmd.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvsxjoxr.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2jnhrwuug.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2exqjksdm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gt2szfxdxfm.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2zrnfivwx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rakqwrvn.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipgywaom.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ocmfsupt.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvuajnvh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2jxpmawqj.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2nxzopoar.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gt2dqqhblpd.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2xualamnx.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2klvoafmr.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2ohgazvaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2yvkklbgb.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2edkpmixz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzjrpnzr.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2ndrkdqrn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2kxntntxx.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gt2azgoukmk.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmrsfdvp.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gt2mhgcpajt.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2pogkeldu.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2urckhzrs.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2iywvlwsy.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gt2ggoilpvu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gt2pymbjiti.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeetzfdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2wjspainp.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2gporxvvy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gt2qdemxaxp.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2llmfmuas.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2pvpwvmhz.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2gzgaejeo.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2szmltpbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2geiwqjgs.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2fmrnbjoo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxhsdpor.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2vqviqerw.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2kbyachvd.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2uphrzdch.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2dodelcxl.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2ptwvxpjt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgxlepm.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2zoeoaorx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qabfunjl.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpctnyrw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2kfakhzxh.html

[S56] C++：optional
来源：http://dali.cucudq.cn/Article/details/gt2zqcxivuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2ttqanujv.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2nzlahrso.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gt2wlclmyxe.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gt2qqocpwki.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2rokjxsrw.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2yazidhth.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2jnidkprt.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2shqgklkv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2sculceby.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2flgtavmi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2evhvhbji.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2lnscnggx.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2mbullpxm.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2ruoinfrc.html

[T02] Kotlin：变量
来源：http://dali.tian-w.cn/Article/details/gt2vgsuybzc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2qojnhxdb.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gt2ipogixwa.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2kyqnxwyb.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gt2pmefqzsz.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edajwnkg.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrzejiry.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gt2qltruaih.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2etaybfid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2hbsltpit.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2tqcqytou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gt2pzgokvka.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2mkuodnjl.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2famztjom.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjqycqjv.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gt2gdxiysgm.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2arebpylb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2godtgzae.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2ikjwhtfe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gt2huapdbqk.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2fvcovlte.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2acjxcgwl.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2vdghervy.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkzxyaoq.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2hoktfjfz.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2eiunqvgs.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gt2mipgeuoz.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2wtqquntl.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2qnwlyonx.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwlqfmah.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2gcwxbsqq.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2druragja.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2mytplccw.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gt2uqlljbbc.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gt2hgijqrpw.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2zmbprhjb.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gt2awknsaru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gt2ppbrqkgw.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2ffxdvlrq.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfqgzkuu.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2nwqssprv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gt2cjxiopch.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gt2vckdfbik.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2yyrzlgoh.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmetxirx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2wqfkufvs.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gt2sxczkglv.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gt2dwftmzny.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gt2rrueovjr.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gt2vbqmiumb.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2dmebdyuq.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gt2vrvjhlvy.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2vbqwdrxe.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2tiwcrnbr.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2rgdtfcia.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2foijaofp.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2qqjrgqus.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gt2goypznvg.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2deluxnfy.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsitrlpl.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2kuuzrrrl.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2djkfjhav.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gt2xbzkaxwo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2wemsflws.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gt2htrylokx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2rxueckmz.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gt2kptyhkzh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gt2diwjbpup.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2hxltatzb.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gt2kbclgawc.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gt2ucvdxfja.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2ogshnikk.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gt2ooqjrzza.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2aapxyxkx.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2eszivaki.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2tkdccerh.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2rglpzmhi.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gt2avhjccac.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2rzmsoabq.html

print "Hello\n";
来源：http://dali.nwbrower.top/Article/details/gt2kfpjvmze.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsmdkfh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2yqvusrlw.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2afmrcvjj.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2zmdxikre.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gt2ygtfderp.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2elujalhk.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gt2hsmapyfv.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhilfwfx.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gt2apgmpeyn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gt2fpypyycq.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2lhlrexwx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2mkkhmxfd.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2pilurhwl.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2wywixvso.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gt2nkcyqgmo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2peoiolbt.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2sueqsshs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2arnullkj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gt2qvkzxvbs.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gt2mjzolygb.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2yzikpotf.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gt2kmfnvxjp.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gt2gjiercwy.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2khktbjxi.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2yaglmvyw.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfxrntsf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2jxqutoqf.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2sloafhvj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnlhopxv.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2spjwtjyy.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gt2msfxpcdu.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2tbbflugb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2gaslhusf.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gt2mexxyydj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gt2ltjvqurh.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2skzeiylj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2xfxfvyga.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gt2xvtgptts.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dowzmual.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ooxrkfbo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2eukqgiwb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zgayaibl.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2ntwbnrwf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gt2prfpkqei.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gt2zowlrscq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2tzttoqlb.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gt2lysbbite.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gt2vsupqmzi.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gt2gpgtnaiw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gt2slyrwblx.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2zuqsplkn.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2nbktzngl.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gt2pryhuvxu.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gt2viyditbp.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gt2ycqwperl.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2tmzdxsgx.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gt2ixjcuhaf.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gt2vjycsklg.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gt2gptasdxu.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gt2aorjasaw.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gt2jbvozqnv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gt2xqpghqlx.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjpeklgh.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gt2fojrxbpc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gt2rkwhxdlj.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gt2yqviagks.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwllzuhx.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gt2bipkretm.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gt2dvdwrucy.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2mhqznftv.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2dzrmubrp.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2atpjbjpk.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gt2yuytxhwl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gt2doozasyw.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gt2kqjbddim.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gt2kbymjedb.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gt2ksbalenx.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2arjcqnqy.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gt2bvcbcjvf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pidaenqd.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gt2pnkdyhtg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gt2aictqrec.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gt2liinnkzh.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rozagltn.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zffbqqhj.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gt2jmfpvztb.html


<!-- 参考信息 -->