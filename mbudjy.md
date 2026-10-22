代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2ewbbxbts.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gt2vqunfqek.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gt2kobdhnrp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mszcuwvw.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2xtgkxgkl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bumpugvb.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2dcwsvtqo.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gt2ntaojhps.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xspakiqc.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjwqsgkh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwistgwd.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2zyhupjhl.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdkmtbyr.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gt2zkhtstnq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2fqbhbwcp.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2sumougac.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hccjbhqo.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2dsxgjiom.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gt2cwmtryji.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2xsdowrna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrnpzzrk.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvvmjcjk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2giiblwbo.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drnkjjxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aegkjahx.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2ttkxmzge.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2jpovvqwv.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prszhbpl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2zqbbuzpc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2laysowlf.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2pugeukei.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2znegxtrs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2ibzkpgkc.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2hvjwcssn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvpptiko.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2ravyntir.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gt2ekhphxju.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gt2paunpcxl.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2zqraclep.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzfdzxgu.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2zebhuqpd.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2clhuowiz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lchmgrld.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2rlhekrqp.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qftxsoza.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gt2icmmsobq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2isncqbyd.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gt2otmiwyvc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2qjnxnrqq.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2pgjyjahm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2epawhksh.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2mmkagscl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gt2ydfpnsqt.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2nmquupfe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2doatodwa.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gt2garkcokt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2mtypyfkk.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2fkmgyclb.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgfrnqhp.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gt2rljppzpm.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2ryojfpya.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2osnldgnv.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2gbgkddqs.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2ytcviruq.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gt2cmovzaqe.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gt2fvwhgkvi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2madwnwsh.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2fegygjmz.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2echytdat.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gt2pkpknoow.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhtbdmft.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2vyveexyh.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2jdrnvxdm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gt2nmvmgcnt.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xgkiqpjz.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2klrelagz.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2vclsapkl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2fjagkqfb.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2nqcyvphb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhciunlv.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gt2apwkloyv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2wrzylqcm.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gt2ridrxqhx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgjwztld.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gt2areaougp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2gplmzufl.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2abmljnyf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2sepmazpb.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gt2gnzeoofi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2ygosqxua.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2hxjrosml.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2amjnuzke.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gt2aniflbiu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gt2rmrpvqha.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2oqasnjbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2rdvxasms.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gt2qogriwfm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2kgcsgdvm.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gt2tgztxtih.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2xbgwawmk.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2skhrzneg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2yvgalsxf.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gt2mpqfamtp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gt2zagwahkd.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2lefoizvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2lfkglpdg.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2qgionbup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gt2ejffznoh.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2tjydftkq.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2tggnrkmv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdusuxbg.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiwvmskv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2kkkpfuwr.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2moapxqvj.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osbavapp.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2mcmszetc.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2btbtfzaw.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2zekfwwnd.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2bifqfiig.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnntbjss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gt2mowyowsc.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2jxlepwxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2dbewlioz.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gt2zykfgfdr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gt2zailswwg.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2mjtrgrfm.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2fsjpvsfk.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gt2apfbmhsr.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2qnlzjmcr.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2afzpsboe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2lksxjmiy.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2ovmqymul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2dtadozjr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxeciqhl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2nocwaayl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2secjmgqt.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2gnbgcjrk.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2oufegthp.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2mehuruqc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gt2reasyoil.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2smokzlbu.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbsqqxyv.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gt2bdlljpcp.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gt2oedrcbip.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ijuhsslm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqzqcrwp.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2jdaorfwm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2datosbqi.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2zptqxyxw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ipixiith.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2gequjkik.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2tanjqbhe.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2qllienlv.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2aoewczwx.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2oqonzsku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2ksjimspv.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gt2xewkkvah.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gt2rdvpwkvm.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2euaclpcy.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2cbnmlzob.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2utkpckxa.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2rovvkfse.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2rufsrgpd.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2prhlnniw.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2pxudkcxx.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2fuqerafz.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2kqhbihmv.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2azwdqykf.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2lscbrqgb.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2bmrwmoih.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2byoyogcn.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2lnwrvezv.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gt2irodhhgg.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2lqdxscbp.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2whzvpunw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2yoxiplth.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzlgtcys.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gt2rplznegt.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gt2rwbqjmpu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gt2tihbdfbn.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2njmjqpum.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2owkhnctg.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2ewflxwam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2jalgaqma.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gt2iribfcab.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nemhjole.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gt2fzgdsaia.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gt2tonanbun.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2sextknlp.html

do { try f() } catch { print(error) }
来源：http://dali.ppjwa.cn/Article/details/gt2vvaosbym.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2hevdpmpp.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gt2xyyktjzx.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjlatbdf.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2xftqerez.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gt2uzlhwowv.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gt2qijaujip.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2nxkpjecz.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daktunzp.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ocsdbpxz.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddzazwen.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gt2ymhnbild.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfofowjt.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gt2yecutphx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gt2pjxaqang.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzfqiqbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gt2nhziuwsp.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gt2deiydeis.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gt2vmylckxr.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2azhkufol.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsoavkop.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2pgqsesur.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gt2dxaixygq.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2ltjvlbuy.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gt2zparaiid.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gt2lxsmrnig.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gt2lfsmlyre.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2sabgmjsy.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2awuxpnlp.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxvkwzqh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2bpcuikmw.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2pseusuyf.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gt2jasiynar.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gt2msscmdwe.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2tkhvgsgk.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gt2ofafbxuv.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gt2tkkbdlru.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yzztxtuf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hanoqima.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2vvxaoofb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2hdwpfska.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2cjbeyani.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2qzfbcvxq.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2wmcvqbcy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2tcqhcyzq.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2dycghahr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2pkjywzgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2qvabfeld.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2avruqllj.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2nbapozqg.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2nznzxsxe.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gt2qekergxq.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2ktvpscgn.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kujxscwh.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmkaveqb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbuufrlu.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2jewynbin.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2bvafjczb.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2ijnvrlto.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twvxhzbn.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ugueghpt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gt2erldrplt.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2tqbelbgq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2nulqxmrj.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gt2exahbibs.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2paynqqms.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gt2gemozztd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2fwyaavsk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2jchmqijy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gt2uzatnrdi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2upiophpf.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gt2jzwzbkky.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2gvxxhewz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2yxcdwuge.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gt2deoqslrf.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gt2dqbjgcbp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sstyqqat.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gt2livqayec.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2wzfbzbrb.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gt2qehpwszl.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2zfcnmmzc.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2xwgcjgfm.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gt2aazmfukj.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guxqmhdl.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2arhlscnt.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2rtwfbeuz.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2uvqcjqun.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2sgajxjnw.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gt2alncnrzg.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gt2raanveta.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2vdbyfiwj.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2gvqajgux.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2hiwcucgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdultfx.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2bgkwhqey.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gt2wpadczwp.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2jttokjok.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gt2kyhdhyjr.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gt2mlwfwkci.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gt2louhkbwv.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gt2zqyzxiry.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gt2kiuggclp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gt2iupapsis.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gt2mfgydmnq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gt2unppdvpx.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gt2wdnvyspq.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2tmemylrz.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gt2aouffcko.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2pfbgikvu.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gt2wlqwauic.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gt2ovlfthom.html


<!-- 参考信息 -->