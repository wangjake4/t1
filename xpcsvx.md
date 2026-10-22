代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnuvfufu.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gt2ucaxuvuk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gt2rmytrvtj.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gt2rqqymfek.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2zlvzxxzf.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2vnhxpslf.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2uheeqech.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2otirmeza.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gt2gzwlqkme.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gt2xplycmbb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2tjgdvjps.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2hymavvft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2ansrmigt.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gt2rihvvftq.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2robuqtiu.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2ispozsuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2jmejfrmg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhjokkro.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2ghwpbeqr.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hxdbgdce.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2htnwmgwh.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibjaljip.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gt2xkbpkbvb.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqspscln.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gt2rnuybqwk.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2tkunfpyp.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2owbzqqox.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2fbardbfg.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gt2swjcqbfm.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2zvwkwkbn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2fzpcyznh.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2zqpinfje.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2umnrxuef.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gt2usvknejl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2sfrujcyx.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gt2vfcbfmds.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2wdckzudg.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gt2kplaclvv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gt2gvicnumf.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2vzdefeoy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2mqlrgomw.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gt2xitnfdef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2vpmksbch.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2jdpdqgig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2gykjhzyh.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2jwzkwuec.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2qdemqzzt.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2uveoiovp.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gt2pobdwlzf.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gt2uswwfhmv.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2jjybfaeq.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2zgpolxtd.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2dkosfvni.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2ovsjweha.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2cvtrortn.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gt2joqbjjio.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2flclckxj.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2fnuaasxm.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2owkqnior.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2dpbcwkdp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkdodcz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ldccomkb.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2lcrnqzpd.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2llfgxcgn.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jocytotg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrgrcfxl.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2mmkexpnc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryzoteqw.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxbevyzj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2pbsnmgco.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gt2cwktbjem.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2zsjogocz.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2qmaljisk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2tnxiuqfw.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2jsxnache.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2mqosbtee.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsdbyycp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2qbidyanu.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsmayybd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwucowek.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2fyiuxmme.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2jgxscuef.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gt2xiiraxaw.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2eftvukqf.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjvkivac.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2elveqytl.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2qsmnaoyo.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gt2zalgwmoh.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2xwxkvyvm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2ijaeyjba.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gt2zrdogttl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2mcqxrcnc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gt2yqlzeypk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2gahdubdc.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2zihxxpxj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gt2wcawnqdb.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2urwdeavl.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2bhqselcy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2ofpyjhxy.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2uoojacmd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2gpiwwdbt.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmhjsvbj.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gt2smcbwlug.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2vfxcuqna.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2wjopftsl.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gt2tkdvnmnq.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtbmkxpz.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrpyirgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2hagouien.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2udkkaskj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwnqooht.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2jbhjemth.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2ucoazasz.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gt2sqrtxojl.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2bezrzeoq.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2smyfmolr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hupkhspw.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2sifcyhlo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2jennnlas.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2fokcbfax.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2ynneyspd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cgxmiswl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2eehzlazy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2apvgtxrw.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2mzcgokqn.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2wxejrami.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2qanqeikt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2qqkiqxfm.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gt2xsnzpjbs.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2ijiwhcjj.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gt2fercbgne.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gt2myfxxpuv.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2nrqmscnu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gt2ljrpdnnk.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2etgxrfbm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ploexvou.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gt2hqswjexe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gt2vysuizbx.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2lridxhya.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2ylcosfhy.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2iodhdwyl.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gt2dmqlxyxj.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rutfdelp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2sgbwwbct.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2qdxvevot.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2idtyrtdu.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2vjqkrzdq.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2svackozu.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2rsryfqla.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2jmmqkszj.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2ffewrkhl.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2cjsnkali.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gt2uhnzzosf.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2bqemnyiw.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2cpmvhhvi.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2sbcnhiuj.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gt2bgstpliq.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gt2yugnjbyj.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2ujqlrsgs.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2laotuxtk.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2bryiymvo.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gt2rcxcxahk.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gt2tgdpsgyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2vyvhctvo.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2lnoueyue.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gt2nqmpuxzk.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gt2kvfywlle.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2qetpnmjv.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2sicgwcpj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2isbpkmna.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2xlpgyhgh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2ongzjdrh.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2ycpxkceq.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2usuzpbro.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2xzhoyptd.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gt2igisdsao.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gt2kdhybdnd.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gt2qzycdxxh.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2qrdyscmc.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gt2etbrqdha.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2yyyxuyji.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2cxvhsubz.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evhnnijb.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wllfrcmk.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2arhufjnd.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uimgcbmz.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gt2reqfxacl.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2lgigetan.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjdmjlu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gt2iwwrtqil.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gt2nriqiayd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gt2wkrpqazk.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2cinzncra.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2lzdfufhq.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2oedrymml.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2idtzpodt.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2vyucrlas.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gt2hydijqta.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gt2oyxxzspd.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2qpbrnmgn.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2sbpskuzz.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gt2kybfdjvn.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkmdxgre.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gt2zeocitdl.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2jffaqfqa.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2kxdumhre.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gt2llsrlfml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2jyaltdwg.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2kwivdeys.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gt2gfocvzof.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2prtqtmpw.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gt2eipmthqh.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gt2iakatklb.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2nssnvcoi.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2rcjhugpx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2xazqzman.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2tuvyrcth.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2vhkyxaig.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gt2ssxhlhax.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gt2uahvtrhg.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xygrbtrj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2eybsesuh.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2icdmsvnz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2ezyspfui.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2dmfmhfsr.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imrxwzep.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2itteokyv.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2ejyoapyg.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2fccguvia.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2wzhrfvku.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2wtmhaloc.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2sgbidmzj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2iyxsbdir.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2wrooatms.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2akclajcy.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gt2zvdcbpqt.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2psnjntol.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2rryfuuje.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jddfswxg.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2yihxckgc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gusjpnue.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gt2polnvhvl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2felgbqvf.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2jjjgrojh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gt2ryxpnsfj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lqxfuqws.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2klwhiura.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2oosmnjyq.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2pbfgciel.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2dqtthwve.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukttmxwe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gt2xqeupxhf.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gt2vhpcgvlb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gt2mrbvqlkr.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gt2kaoktkwh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2pewiqjav.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gt2eylxbsma.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2ryyhhlpo.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gt2nemvzwii.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2lidmzsbv.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2hiwibhus.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gt2scdsnnti.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2imnguvnj.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gt2jxqgwtxh.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gt2asuqbkac.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gt2pwuloaey.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gt2dpvufple.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gt2ldqomdav.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gt2xagyqokf.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gt2sqbjcpzq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2ekdxjnct.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gt2uhptfddl.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njojwydc.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gt2ycojprzh.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2uqoyynwq.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gt2jmdgvrvw.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gt2wjortbhu.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gt2uhlgodgj.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2lwwxmzjw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvqqtomf.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gt2hagamnqk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gt2kyjebzbx.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gt2hoxvzbrw.html

pat = re.compile(r"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2mqvcttaw.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2jcdkdnux.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gt2jdnycbhf.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2dsmnkgdb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2yrqfucvv.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gt2eumkdcue.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gt2kubajfhz.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gt2vhudmczy.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gt2ktghbxhr.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gt2jyaibeuf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gt2byuezuco.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gt2cncviswq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2qlkmjiqs.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigufen.top/Article/details/gt2jajysvxv.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2olqgdcpc.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gt2fucisbpr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gt2tbfuetym.html


<!-- 参考信息 -->