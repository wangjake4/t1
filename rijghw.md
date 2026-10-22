代发 wailian999

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjfeccxh.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2reioxplx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2nqmipvmb.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2fjlprpkw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gt2gktvmxdi.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2vjciajcg.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2xdfmucxu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2psdibmdt.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2ydplvqye.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wjhuxtjp.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2afriqgzc.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gt2nkszbyed.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2khxlkets.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2ksmwyvjo.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2yjptnfmx.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnfbubio.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jurepltb.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gt2gbcmlpvu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2dybcneax.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2wkbcvtdg.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2enpktzca.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxqupjej.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gt2jvtuwoew.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2uvazyfev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2wjpifgzz.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klutnwzw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gt2ruugsyor.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2yhixvgeb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gt2jpvmrqsu.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znebkaos.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2qhdxhebj.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2fbzrmeba.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwninyul.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2uxnqvwek.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2jeylnsqo.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2ouuufzzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2serhxqsi.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gt2tbbcawar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gt2jyjxuneu.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gt2hxxzsrxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2puaboalb.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gt2dqmzijzj.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkxqgenk.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2juzrvgrp.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2nnbpmozv.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2muljfhbi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gt2kyqlwmjl.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2qtwuehyp.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2pgnmtvec.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gt2qlhwdzly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2rebobych.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gt2iftzzeoe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2qnpcgheh.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gt2rwekcyay.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gt2lxzsyeuz.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gt2yqdxqgoh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2zpkaefcz.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gt2dxpdaxqk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpfsrxyn.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gt2cijmckca.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gt2otzxloal.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbfqkjgr.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2savlduup.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkxrpejn.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edpngvuu.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2dgvqkqln.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttcttkff.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2ayezsgkf.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2bhktihmo.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2ckdcmwhd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2czhadumy.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gt2cbupqywg.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gt2bctcipyn.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2rwegxexr.html

#endif
来源：http://dali.shuidangran.top/Article/details/gt2vubrvizo.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2ueuvlhml.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2burqtixy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2lzpxgzqb.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohzinfyi.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2nrdtwayj.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2ntugabky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2oexrcdis.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2exmcjtlk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2kuccpuby.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2mlnqoojv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2daxklsrd.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gt2vllzzsnz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2ghzyhszp.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gt2byejaqvu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2dqpcigui.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2wadvwayk.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2nayqslsj.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoywpzis.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2hrfmplbn.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2krpktugg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lakzafzi.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2rmzlxfak.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2wasmgafs.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2votkusus.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gt2xmhpfwfp.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gt2pctptngo.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2cmjlbyza.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gt2fgphftbj.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2cprxvsdr.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gt2fqqiamtw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajenfmbq.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2emaecayj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hqvdekyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2gphuzkrl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otmnmojk.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2yptvwpvg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gt2vynrsmvr.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2mcffudor.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2xhdtvuqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2trmckagw.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2crpyknyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2darlgdap.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gt2krlhplms.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gt2tzaiglpt.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gt2ubfldsym.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gt2fdlbmhkv.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2zhfoxslx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrdttp.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2ioglvfwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2bgxaxgvt.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2zygxkyea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2wmdvigai.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gt2jvfybqcl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gt2ibnlltwn.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2jacyvtxo.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2zfatgofv.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gt2mfhzimhn.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gt2dfncajhg.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2dvtmahzg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2rfijqjsh.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2vddlcqzm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gt2bvkdgbsx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qihoaldd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2lbtbffxx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llfgzucm.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2mehzobxm.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2skxzxiui.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gt2knwsankk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gt2ycgfjshj.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxzepppr.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2rqjewqih.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gt2nwigkyhe.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2tunwdvxd.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvnbtkuo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2njlcxfgz.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrmlwent.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2dhbkazjx.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2jeibidzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2dvyygams.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnruchka.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gt2gvdchhtg.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2fjolqgnt.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gt2aaejsxnw.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2inbjsgmn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2vsadqfes.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wybbevmt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gt2jugzjmla.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiergalw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2vmbwvaod.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2wbopqgvi.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gt2lqjpzqhg.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2mlalmncx.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2wmqdfsis.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2btakxnxe.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2avphewsg.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2goqeclen.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nltswunj.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gt2sgqvohse.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2mexqtzil.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2cycdttyg.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gt2tifpdfeo.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gt2lufjuxxg.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2ixzmjxli.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2qvdafngr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gt2ioduevzj.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gt2ypsnysdw.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gt2rgzscumm.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gt2xcdanriw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gt2ejyxrjad.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2fiehjcmz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2xfpcjuew.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2ckdlwvlv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2fxrkcajv.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gt2xocnzbni.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnqayswo.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjiuopng.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2huhbgrbz.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gt2qdicplgo.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2wxojabix.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gt2udxnjgau.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzwupkiz.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gt2kkveahpy.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2afgfzosw.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2liivjvmt.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzyupfbo.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2buiyisap.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exnazgnm.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gt2xylvvvwm.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiandnbq.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2qlowudqn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2ohhobaab.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gt2gdjwlsii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gt2cjhlqsao.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gt2rymupgli.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2laocccvp.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gt2nfwnjvmx.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2kssgsdiy.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2fehcurhd.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2sdbabhec.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gt2syedvlst.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gt2ucevmnlr.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2nhyxjamh.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gt2akkgwxfg.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gt2koihlvvq.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vheggxpp.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2rtxbbwho.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2owxypdlp.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ttwypwtr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2hmacbwsg.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2nzxglqck.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2pgoohtyc.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivokvlzh.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2qmfeibmr.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gt2ggjoaynq.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fscsuzej.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gt2ceicsiys.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pwfhhkjt.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gt2dovfwjmx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gt2rmipynmg.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2fzxvhbhe.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2ahxtkxbh.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gt2jfttelim.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nsiroiti.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2ymxwqoyq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2vpgfzvxt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2akskfckn.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2vprgqokc.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2ygrsqjsp.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gt2jovyugca.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gt2lfyjyjae.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2nxmzxcdz.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2mbjnfisr.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2qtvfekkx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gt2kyagwjqs.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emsfgpdq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gchrpcbo.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2tctxzucg.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwvdlqfz.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2wplzoeim.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2twaipors.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gt2jtoqxcfe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2dxuhpqri.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2kxmhhgio.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2lfgfjjzo.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gt2ydwqyuao.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfryxlzk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mfsuurwj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2wwydhhlf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpcvsdok.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2netvekii.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2ruyrdoxa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gt2rappdpys.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gt2jcmdmyrc.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2myutirct.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gt2bnujvrzg.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gt2zsrxebhm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gt2pcecnufb.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gt2gbmmoucm.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2eajfforv.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gt2lrgdrwea.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2dkhihboa.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gt2xndygwyn.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubzhyqre.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2fqucupen.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gt2bkjiamgy.html

[U09] Py：字典取最大值的键
来源：http://dali.sxryk.cn/Article/details/gt2upwpnglo.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gt2szhlbkxf.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gt2liqudwyg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gt2vfsahvvd.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2bfddbmga.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbmlbdok.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2smhtfwbh.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2svqerrlw.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gt2qdrvwofw.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gt2pxxnjnye.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gt2crbjbawd.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gt2lllzaxqn.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfpqirtw.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gt2ebugicox.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gt2ewxfywco.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gt2snbqnqst.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gt2omonmxsr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pniwrnbb.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gt2yjgwgdzu.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2nhohhelr.html


<!-- 参考信息 -->