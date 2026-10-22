代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtsysdxldi.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtqdkpawnp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtkpzkaykv.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtwkzujtfl.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtleafbmmv.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtszwrvuqz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtelitfzyw.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gtpzgknnjl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtvtwmuyeu.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtpdlchuyl.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtikniahit.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjaeawqlm.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtyxsfvmlr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrdjacuda.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmuloqch.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gtzkqcbioi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtdskhrkpi.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtefvqhiua.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtpebxqcic.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtbxwfcqew.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gtvtelmcad.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gthwhadnvd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtwqyzvery.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gttfpgrhcx.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtjbifagvs.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtkzqzfqxs.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtnrojrkrx.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtlnlhjeui.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtigjsrfrh.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gttnrbeqrg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtluvbkuko.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtfaxfcrkb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtoepmplwo.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gthojriftl.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecqrzhhm.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyoyararb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtudsuzcqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtieadgdwp.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtwciutzbx.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtmrjclyzh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdowphsy.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtgczetrqq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtesdnfemq.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtdsefxxka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtlhnfqpeu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyklnxjnk.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtrfhuxhgu.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtflqjhqpx.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtokohermy.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcvanitm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtyashtdsc.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtwosbsrya.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtudgarqsc.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtaogokjnw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtbckihloj.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtdmhhdjmn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtlesibtvo.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gthwjvbshy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtekioigsl.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtxnjfuziu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtrrlqxncp.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtkcaujsta.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtpuoovnpd.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtwvhyvgsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwznynymv.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtakganaas.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtfkvsawei.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gthrnjxzqa.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtefsjmxmq.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gttwnyuzks.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtnxfrmhey.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtojuyswrm.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtjrvewqec.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtaxwmwzfy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtfzuoepir.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtsvfkhvnk.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtlwrelnld.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtpzomzjkd.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtcpjjgnmm.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtxphpsgoj.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtfxxrwzab.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtowominax.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtwtndhkgn.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtbwdqernf.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtiiyyrmrx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtyjeazomz.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtoyidyayf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtzsxyxvmr.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtzpeqixye.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtgczmwgtb.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtwlwzszjt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtonggzwtb.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtdeqyghwm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtojvhtnkp.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtzykouazw.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtywhqatja.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtjfjqcqxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtanidwrzk.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtjgowdsqo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtokcpxpzh.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrueqxgm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gthrbmcdiu.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtqairdztx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokknlnei.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtdowfavgw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtloiujaic.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtmdutuoyj.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtxjbvmdqu.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtnvoicqcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtytgtpmps.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtaskqmoge.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfwzbqhdo.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtodvaymzl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqgwyjbnu.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtbajxffhe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtoblchuow.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtknkjzjsb.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtctjolkdm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtbftxizon.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtmojiyjsf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtpxritcum.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gthrpummag.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gthxgsstoa.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtpgdashxi.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtgzdfquog.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtwxnopjuc.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtpiqlbyjs.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtxduslkyl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtbxseytkf.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtdnxdhiqx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtcxazdqcx.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtwgorariu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqbdlrpg.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtuqyzdmuy.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtfokdsoxh.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtgnwxopna.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtkwekyltw.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtjdegnbpk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtgabwxywa.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtdxgaelto.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtvxkskagi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdmhgbkkl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtveybojkz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthbcqurye.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtauutinyt.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtrrygrfti.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlbchhtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtxqdwsqem.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtwsubpsqq.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtceilvkpp.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtqnyqeeva.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtadkvtjmd.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtxpfmjsaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtqwekrqlj.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmqgaaik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtkzqakkpc.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtceeysdht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtlkkqpjrd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtlhswmtgp.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gthuajnzax.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtxeferjvm.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtotsykqyk.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gtewuhuyds.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gtjrepirjo.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtcgkmhlej.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxztzcjsc.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslbimhso.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtujrgwito.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtnemfgtuu.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtdgpsvvbr.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtkcnkhknz.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtmrgvmwec.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtqeugbqsn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtweunujkw.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpfwjxiac.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtpgsdcobp.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtxlrzzbvy.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtmjbyzmdc.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtpdqvftmp.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtklgyhbni.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtdwmecpzb.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtzdxwujcy.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtggrsarai.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtidguwrdj.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtqaiymyeo.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdkzdgsp.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtmzpmixoq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gttrrqhpfz.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtgteqadyw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtufjraxji.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtykflnbyx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gthloenqqb.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtjrgqgrwm.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtpeiievon.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjssduqc.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtyzrhihhr.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtmzjgjorl.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtdtaqakwz.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtmgtbzjau.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtpoazfqpx.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtonxeochm.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtdvbimaqi.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtgcvissjc.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtjacqohqu.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtychtstqf.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtfkjhccui.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtgjxmscyx.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtnjxzyllg.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtezanynrl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtpgbzsjvc.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtkwqttuuu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gtzheoakln.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtikspuwcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtsmsvlhcu.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtxvahytpu.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtnufkyrkt.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdozocglb.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtwxdpubcg.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtjkuoqgry.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gttgzjluub.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtfbljshsv.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtfmmkugmc.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gtsxahonwu.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtubdyyfyj.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjnwpuyia.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnfpiqxv.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtjayjpixl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtxsokoler.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtdnyqwgqi.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtleifmubl.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtcajbijtr.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbhthrtd.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtnknvqxxy.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtupshpytj.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtppoowxpq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtspqjavqz.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtgazcshcm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gthcyxhnjn.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtkkaajxqg.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gtlbcrggux.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtwckgnega.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtpcqyrrbl.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtiaxdabrv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtmiibrtfs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtpagqvptd.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtvwioedfs.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtekwhgtql.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtsgyxhygn.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gtyzyawwdb.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtvlckxiwx.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvyliopv.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtlxvwzihm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtkcclezqm.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtjdanudda.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjyuxwvgx.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtwxvhkxqd.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtmbcwjntu.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtxmrftgbd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtpwsqchbb.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtvlkbxplr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gtugbhijdh.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtqymmoetp.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtpwnasisr.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtdufwnpcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtkqxtaluc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvhjmufhr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gthcmkgrut.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpmimzlyb.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gtakukyrfp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gthocfoppr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtahxapsqn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtovpzuisx.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtzzlwmrhy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gthonqfogt.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtjyoiamgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gtiegccowd.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtefftevfi.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtrogcancl.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtgujhlxoz.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtcddqtmix.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gttodibjtj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtsoupdutf.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtxesesfrk.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gthpznachf.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtwgppfkly.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtxpzilven.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtzguwuosf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbaxcbfa.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuzauecf.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaqthghe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtrelgmzuu.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtnvcwwwwi.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtrsdgxnok.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtoxfuzcuq.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gtxxdtvtea.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gtnulqsrjg.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtufxnsnbg.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtyjxnppxn.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtujbhwzjt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtfshrovfe.html


<!-- 参考信息 -->