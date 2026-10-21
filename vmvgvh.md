代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtgdefllip.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtxqvcmkpv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtmzfzlahw.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtsensflss.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtykytffot.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtmxjmedfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtdggdtgno.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtvaovjamf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtadvwymwi.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtyktxlurm.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtcfrjauwh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjztxohgp.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtlnxgomzc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtakkejtwa.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtijennohj.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gthqrvlupd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtuiqwqdiv.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkeyvqye.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtfnugmviq.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtqdxghwui.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtjzjeoehm.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gtbywfzntt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyussfvgp.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtqgcoxaqm.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtcrjskmiw.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtgvbyhdjk.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtqmolmwqe.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaphfedp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtokqwggjh.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtaxzibhng.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrimanius.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtrhidcwis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtlfmwplwf.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtaialqbmd.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtgreqmprx.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtcvybivbm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqvfphvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtboagyeqd.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtuwpfwppb.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtysgxrery.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtxnosushi.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtmapzybki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtdyomdgnd.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtxgkgcuox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpezyagxe.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtcrhdwgha.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtucojndjf.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtmcdlcjvx.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtigjklvtv.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtqixuvvis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtupfmkgms.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtoplozthe.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtaqdfakvh.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtyrxubenl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtzezamaex.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtvryooauk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtzcizpiph.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtfhygqduc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtanzgufer.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtukiqediw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtnlffymzm.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtzcleuelf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtozqhodsf.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtracweyin.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtanarxbnn.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtkwawjlib.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtuvghuwzv.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtyibdeauw.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtvvtpuqjs.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtpdspmdno.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtnjxuvymc.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtrngdlssa.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtxvgwvcrs.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtkudlgffp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtujyjjnda.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtiurafldr.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtvhhpynjc.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gttotxqwzi.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtlisntffu.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtnugkkmdj.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtzlfnwayv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtqrysklyv.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtftrxmrwj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtbjfnbiws.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtfrqoomtc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwlktjab.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtftgqtees.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtevhzidiy.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtszszxhzw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtujmuudal.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gthoxmhcfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtwtayfjui.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtojdzmcfl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtodvzjcuk.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktvincxe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtshyqofbi.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtdfsruukd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtsrdvrjtj.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtltrmarny.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxdkgomy.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtimwkufzg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtvgartjot.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtjlvidgny.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtwosepfmh.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtuafiwlqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtupxbjkym.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtnwrbahyl.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtpuspspzg.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphpsinsr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtypeoiilv.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtvawjbbcy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtruvlrgxh.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtcmpithvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtchbvpgbk.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtcqfaeqps.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtbqyopvdy.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gteuhepchz.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtwkjwtrgx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtskclbyww.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtvghhyxdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtclxtsufv.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtpzqjnlcg.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtwpopnylg.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtnusxoyco.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtslckpztb.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtypfbthxl.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtsqsmalbs.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtfhucxmhw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtqestiqyt.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtywilhobp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtcpamerqu.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtzjgabdjz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtmigmgzkl.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtegcihtoc.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtuflvjbub.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtkyilxirb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtrjsxhhik.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtwqjkfqup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtjhmqzvrg.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtyvqdqmmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gterjeacif.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthhocnnxd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtdqigjmrk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjslgdbec.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtlnqdcicd.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtvmkzzkod.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtteexpqvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtjzmtpnfy.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtudbitumc.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtpwhewcmt.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtocwtkvtq.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtechshebg.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtokyxftqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtefytmbcw.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtioluvxvm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtvrakqanz.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcfyutaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtfqgpehrd.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtdkgzwyuz.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtmbnnbafa.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtzgwowzlm.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtuyxuwwyt.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtearnaicj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtkvmuufqi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gtwfzwysai.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtvjkdrnbg.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gthtsmklzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gthipakojy.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtjtvwvorj.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtbwpuukun.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtjojmviom.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtsfmfrdbn.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtbeiwjkmy.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtdlmuesfq.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabeokyta.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtopwmtyly.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gtqnlmjfbr.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtdxcfuand.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtlzswjvfc.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gttdiufyfd.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gttkpvszpk.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtstoejqze.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtmdkwzhvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtidvasbtm.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtdvcwyrmj.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtjagtiolt.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtllhzwhax.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtaoagqqkq.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtbafkusms.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtgqqhwejb.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtrpakaobw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtpwmcflsd.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gtanbrgooj.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtslswjyef.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtiudxhniw.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoynazeqx.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtlwelckdh.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtdlmfrhtr.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtgqfafdoy.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcawmeol.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtbcdfqmuv.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gttfgrhkjl.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtfugsrmwl.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtyymipfha.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gtqmqqbbix.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtldjvpmwr.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtaypccuiq.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtkkkieboo.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtcoeymsqt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtecmwbfiz.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtwllzyurv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtkstdzree.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtahpwfnyy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gtctwhgsps.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gtphixbhio.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtddkogzpv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtsgruktow.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtcnepwvtc.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtcylajeco.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtnfkvulaj.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtfujwzkkt.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtgzzghvvl.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtdhosepqi.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtsazmgkfq.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gtaopanqsh.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtukstsmnt.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtplfzuiqh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtuleqvalw.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtratscqao.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gthjiuqsjw.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtoewzxgkq.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtpvevbuqg.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtxpdqszsb.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtxvzmgbgu.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gtbmxnrhys.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbftujwcm.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtszseatgg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtpqhhxjbd.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngikpisq.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtchobsafe.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtkyudvbgb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtiwxrnczr.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpfzwnui.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtpkxjnrls.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gtjjrpwomj.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtmcuqslfz.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gttzbzcxdw.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gteqlzuciq.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gttscemkar.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtrfnbwivi.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtfjbroefj.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtzdzteinc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthxjbziwz.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gthqehjdsy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtgzdzylpw.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gtnflvausk.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjrxyyvf.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtmjaggyec.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtrlarjdmv.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtmpktrfgi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtjajncwao.html

[T59] Scala：循环
来源：http://dali.kuanghao11.cn/Article/details/gtcopmhwwk.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtxvbukwhy.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtzvcsrtwy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtppoqdapk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfqptyuqt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtwcxxbxae.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteibjmrla.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gtwseahcry.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtcjipsbnd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gtzpvyziow.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtjghhuvpl.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtnhykyvek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtqfzqoesn.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gtsdpafjac.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gtjebvnrbw.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtchqawbwb.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtewrukkde.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gtikejdgzq.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gttrdlvknz.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtoyygrsfz.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtzurgwmki.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtlydybmro.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtwhuypvwl.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtgwsimzwy.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtnxyjheqr.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtvnhrhlgl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtalvxignr.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtsilwwncz.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtccvyxchx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gtehpgaufd.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtrspguxiv.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtrgpfbaak.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gtgyeowbsg.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtlcutpfyk.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gttymarlfp.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtyhorcoyk.html

t = time.perf_counter()
来源：http://dali.gaohongyu789.top/Article/details/gtmwvudfmj.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbefazl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtiubwxvak.html


<!-- 参考信息 -->