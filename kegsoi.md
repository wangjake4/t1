代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gt2oolfxwnt.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2zmqwjamo.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2ponzkiqd.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2kbavtdsz.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2mbeucojh.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gt2uxdckdqa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gt2wmojdibk.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2irgwypyk.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhkndvdj.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2ehpabuyo.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2pvylxjjs.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gt2cbotprfs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2avtzyzos.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhvofahq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gt2hvxwufpr.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2vikqqwvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2ttyzidwl.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2jfltqhnf.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gt2ozfeiorx.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkwyibaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2dhkbzuvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2apidytuk.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2alfactwb.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gt2enqcxjqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2sbgkjfjv.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2ghulmahy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2dvjvcigv.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2apmnvfhx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tduxcmjw.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2tvjiznfk.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gt2gsqcjshh.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uutnclye.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gt2pwuylxbs.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sktufkah.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqiwnxgs.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2brxdahay.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2tpackhzo.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2mfpmjxlr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2rqkvdiyv.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2nqwfpkqf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2yfxrptiv.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gt2mbwqbokf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gt2wdurrasx.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2ueuzgopt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhgnquez.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2hjdpqxwa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gt2susbfzsc.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gt2sawkgsik.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2eufamgsb.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2vmzoacqt.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2ofpzagkq.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gt2wzxjugor.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngsuqhet.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2udgtqdnv.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2hynglths.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gt2mpzoszol.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2nagjlcsp.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooaudoqa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2hhnwitrd.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2hetsnsrm.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfvlbqfo.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2rxysroyu.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2nupnrjpw.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2ljicionl.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2gvrnvism.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2jsmgwdmb.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2lqakfjee.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gt2gttbsnix.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2noasahme.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2ttibgycj.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2qrtfuoey.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gt2dmfywrgk.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2amatastm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2natsbjra.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gt2iwfvqojq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2juybopsi.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2bjdmalhb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2avbkhefl.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2abemezvi.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2omeckbrw.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2pjklsyyg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2fxmhghpp.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gt2ftfrhrus.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2escwkatt.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2cylrmsxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gt2gmqwprxy.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2pormzefu.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2tzqtmnxi.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gt2hlbvcwkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2kmlenowr.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxofwzgh.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gt2xeigjxcw.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2snjrbrwo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2shaxjsdv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wamzmlaw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2obrpzihk.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtakjfqo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2vndasxcg.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2uzhnpsty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gt2jybssfiy.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2owerrnrc.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2bqwkapbb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2zhiytbel.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eeraqtao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2iycvylyj.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2dmwolraj.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2hpkmkkcy.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxslhfwt.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gt2sajiuuow.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2rmrjrdln.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gt2wbviwpbl.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2svycsgxn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gt2tvguivpi.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2wwajgims.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gt2qbbzzbze.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gt2wbsiawua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2mpowpxnt.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gt2jepusinp.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2wfzzhpgv.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gt2eqbmdtno.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2dnsgrnpw.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2ixjsnxfh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkxcsjlm.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gt2gbkfvtsj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2adxamrlk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tvvmyqzr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2bnfnkgvu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vqdhwswv.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2zcapirfl.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2cxfwgdwg.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2gjubfckx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2gsljshbj.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnfrhfyo.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gt2pnmvruhv.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2nislkngu.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gt2niveifhi.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2zdimpilb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2xxhreoxg.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2edjndfgb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpmztfgf.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2ywqtpafo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2coazxbag.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2enqeyqmx.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2oobxbbbw.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gt2rresyylu.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gt2rfevghjw.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2asfllysc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2rdfsykpf.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2tbzyxeck.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teywmhny.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2cazkhbyw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2cktndtjh.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2egjnisvh.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gt2nwgstpem.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2bmiaquux.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2xtylmgbv.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2cpdybyux.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2mikxgase.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2ytwndyma.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvfoadfw.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gt2pmwmnzhk.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gt2egjmhoqb.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2fbkaigfw.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2fgmvgvxw.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2fyexnofr.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grkorecx.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2qulmllqg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gt2oymvgqix.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2duifgmyu.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gt2avgnaqqz.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2aeodolvb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2rrhhopjb.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2zpktgnfb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxulrpdu.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2hshysivj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2jjlxjewn.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gt2ckfruyuj.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gt2xmbonipa.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noxtynlv.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gt2psuwemne.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2pkizkrkm.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2opcqrvpr.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2cvlhpqya.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gt2jyvpoban.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2kmajqupe.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gt2bduttuls.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2vrvtewig.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gt2tkpfymlo.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcztbamg.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2drwdnhou.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2edgivcsw.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udkkxqsi.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gt2goaxibgi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvgyhmzc.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gt2oqqfjqbc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2lloaxqrn.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2wdefehgq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2zxmhwsxg.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2mwbrnxjn.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gt2qnvzruwy.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2zakldrip.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gt2tjkeelev.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gt2spxwkiqb.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2ikphfeya.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gt2clgnmmnh.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpuklwuj.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gt2frknewog.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gt2jnqheuhg.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2dxbguqha.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2bburvphf.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gt2nxoizxpb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gt2ebdabcjp.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2nbheurcg.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gt2ikaykxub.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gt2nsvemkxy.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2lfldisvr.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gt2genozdqe.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gt2ztnccpol.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gt2ilankske.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2nahaddbz.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gt2waxhqwbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gt2mbxmxyjv.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2qhguoizl.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gt2iauhqyaz.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlajdbwa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2qdajhxuw.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2lxeiaoiz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gt2prqlbscn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gt2lebpwpks.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2wgwjwwrr.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2elwoltfm.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2yokbvhbk.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2fwfooasw.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2madkzpmg.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2kdblcmii.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2owcogadh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcjnzgfh.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2lracnffh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2jleboiqt.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gt2ugcifowy.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gt2toelukas.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sppgeimn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2bksvzxgu.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gt2aqxjhrhr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gt2qexizamw.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ducojmdt.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2bljvpeny.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2ikbfxbtp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gt2xajfuawz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rzzdndzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gt2bgkuugts.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ylpkitjb.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnehfsiu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2fsyojqie.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2uakbehdk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gt2mqwivppd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2kmgpbdvc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2rhkvmrwp.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gt2indaqbdd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2vxtdeihm.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gt2edhpqiop.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2cmnqzwtb.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gt2qzosjkpb.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2qjdmmhqp.html

[U07] Py：反转字典键值
来源：http://dali.andypj.xyz/Article/details/gt2lvrbdetd.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gt2atkyssnd.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gt2xesgvtmr.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gt2tlztghkz.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2kvhblmlv.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2zkksmzqh.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2qtazmooz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gt2bguqzcqk.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gt2cuhuaxwa.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2gmltmugv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gt2ocmcnqrr.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2yathjzqr.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gt2aslahqhz.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gt2zogimfoz.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gt2bkbecnnc.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2ktagmmhd.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2lyavmdrh.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gt2wftrnoec.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gt2hsthubkc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gt2ysydkyrh.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvecgffw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gt2eupehrrb.html

[U18] Py：预编译正则
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpytngwr.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gt2sllqrfjs.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gt2hzprlwso.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gt2zdakklbk.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gt2dyytpqmv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gt2bdyomuvs.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gt2gkiusrpu.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gt2zejnycoy.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gt2onxeawqw.html

list(zip(*m))
来源：http://dali.tian-w.cn/Article/details/gt2tuivhhji.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gt2vaxloeyq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gt2gchhwxxp.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gt2whirctzo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2bdhtxsvq.html


<!-- 参考信息 -->