代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweammotc.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gtgtzclvkh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtgryjcizn.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtxbvzsynu.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gthnttrkif.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtklxidrei.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtlvskkcip.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtksbviyga.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtyymqlhpd.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtbrjlklyl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtvytdxuml.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gthssqydly.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtkeezlhcq.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtrhcdyxom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtmsstohdv.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtyuwizkqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkfgxfclj.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtkzqkqycz.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtqpxpddgf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbjjutzjc.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gttciwpwjq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlogyynip.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gtkxrxhbza.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtyfgxadkc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtqmcptcbm.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtsrgjbbas.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtaqjccgsc.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtdwvxaynz.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtbnzsbiqt.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtmhkvzknl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtdjkfwfdk.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtgqcxmqtu.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrrgmqiha.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtxrptcafx.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtzytqmlnt.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtleyjquid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtjdolfjah.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtkxaimckj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtjhtnwwnq.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtrwdrggtk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtghqlauwk.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoejdlyc.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtiwjvupna.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtqhtpqwng.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtfnatsaem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtltbboamx.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqoznlsk.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtsdzhwews.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtwcobscwl.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtaxkqorlv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtwpvchnlj.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtzamilqwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtlkeloobs.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtxonwfvyu.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtfvjpdvtw.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtcpfhfjrt.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtsptgqagt.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtawpmainf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesvzkxdt.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtzhnhlfxq.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtdigkaqlj.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtrjbhiluc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtsusuxvyu.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtzwbparnw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtxdhthfxk.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gthigbdpio.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtidavycgy.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtxkaolird.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtojeavrys.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtlzzxogxn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtssexrxfy.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtnfbrzake.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtosajehuc.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtfbsyxnjc.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtytxmakop.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtgtrelnxl.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtvfwageyf.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtushknwsx.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gthhwuxfrp.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtkomixyrg.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtjtmiqfxh.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtjgkfeozj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtvivpffao.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtdbyfxxlq.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtapsvjzuq.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtpdflrjoy.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtklvdgjqd.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtommyovsn.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gttxlsmtji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtiihjsgsb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwwuggqo.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gthtfvmfry.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtdusubkuk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtezmffyjm.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsurtrgnl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtaelezxdn.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtanitwmlz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtneahupqk.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtmkbdkvyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtcewnojni.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcezvgfxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtndrheiwo.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtzofvrntf.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtoukficns.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtlfcfhpsw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtfohssaio.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtpeowzuvw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtlsgovihm.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtalxtyfen.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtbvfalyex.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtzaexmgce.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gthlwkfwlo.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtfzvbybji.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gtjkqrodhb.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtjygjihpk.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtdxcamvyn.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gthaommetp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtnyqupzwd.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtosvecvrw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtxwtkfnkw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtkxkmkyit.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtojtdgkgc.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtfagenkbc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtdyflvaxh.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtgjatobru.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtfhzzfosx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtdmoaokzz.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtgxjystgo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtkgfzmnjj.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtrrrzjvzr.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtdoxbaqww.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtrszidzvo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtvyvveyqa.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtrefcvxny.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtzlknkopq.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtkvxpvhun.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavwandqb.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtgspztfic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gttvaponlx.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gthkmsugae.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtlwjvoczp.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gttmtfmhck.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtircjpqfr.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtahkvyddq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gttbyiurgn.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtuzfjlgbs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtyfdeabfi.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gttkdsffma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtaekvyetc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmdfkufiv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtcboqqmmh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgavnubje.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtrboivohi.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtorkmobiq.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtedwzxpuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtywievsiv.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtwmjiryxt.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtjsyzhvdc.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtumyjgwnb.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtrnnpopvi.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtwngnnqmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtgnrcntey.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtwhurbpwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjnfgidb.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gturgfnekt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gttshxzdzu.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gthiyxoqqg.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtvremntlp.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtbmsbyymf.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtkwqximdm.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtdpnyaaou.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtmcisdqou.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtxgwxpstm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtbjrrloic.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtauwikwpb.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gthmosivxa.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtojlzntgv.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtvihuzyfu.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtexlnassg.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtvcyxaqbe.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtbbivjdxb.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtfhpypsle.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtmmdqeuqe.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtekwnpvwz.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtsuhhwyxa.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gttbrgjldx.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gthpajgwrb.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtgzhqlqnp.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtrdpcxzkx.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtlljwozbd.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtlijxcnkj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtusvszaas.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpuaiufxq.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkiuldrh.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsxijpsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtxflrsroh.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gthwlhuigu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtovzuotph.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryhdlxdw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkzkmngy.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtkblpkwjm.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtqflzlrou.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtxpfhfmio.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtcnitguhn.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtdezjvxal.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtniihudke.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gteojhvbbq.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtfkbvpuhp.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtdjyoduef.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtgjdbqivw.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtiynfvoat.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gtwsnabmqm.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtbgsmjyvp.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtpgfjnlyz.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtivqtnmiw.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjkxrscs.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtblrzoxaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gtdlzjhowm.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtvezteydr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtyxzstkrh.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gtaevgrpnj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtjsovgaho.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbomrtwqi.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtvosvpzpo.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtaqbttmxt.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtmkmfamdf.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbytbqaiw.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gtfayanayq.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtitqydaxy.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtlvetuuvn.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtqjdpkipw.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtaeogncrv.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtdgjchhww.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtmajchsfx.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtbiiluiyu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtjsejqinn.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtllodkwla.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtwharggvy.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtnbasoykv.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtrcmjniqd.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtyuifxmcs.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtlowkdykk.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqejohpr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtmemztvsl.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtswpboqbr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtggxecjpl.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtrrcbhxwc.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgglkorol.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gthqhqmaql.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtdknbkavs.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtrnwqjmjf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gtttlqxorg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtsxphcohy.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gtbpzbhreb.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwknuceuo.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtwzqgefif.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gtxaefleqs.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtjcusvazb.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtnurflvmg.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gttrizdhfx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gtuoinmddl.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtwvdvroxc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtrfqbckvz.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gttrcxiqqv.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtujkdfzqk.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtupgadgka.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtcfgnuuru.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gttrsnzdea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gtydytaicm.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtsblcxjit.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtuilfbsow.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtwrwgrlbi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtwmgjjobv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmwurxzlz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtederwzzl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtykdzuexs.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtbyzkadin.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gtdrljnfco.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtkqypndoo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtzhpkcnnq.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtlamygxvl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gtpkbzprjc.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtktzxewaw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtaupuxswm.html

[U05] Py：列表去重且保序
来源：http://dali.meibo888.top/Article/details/gtkqvrccpj.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtexrihdst.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtcadokwne.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtwnfenhjg.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gthxaghxkt.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtkaqvwebi.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtjxkyldil.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtxuqtwrwy.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtojmbuorn.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gtrzimzckq.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gthtvpmpea.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtgqlduedn.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtiqiycaxj.html

(x * 2 for x in arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgoxzceiq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gtvttzrzdf.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtgnzkqlyo.html


<!-- 参考信息 -->