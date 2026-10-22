代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtwhubvhot.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtqhmsbyrd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtfphylaqr.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtbzbumlxj.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtwosccyjy.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtmliswtyc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtzpnrdcyx.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gthsycoymb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtgkzckfdn.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtvkqvcrzq.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtwjispuek.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkthgptmn.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtewmyyasm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpqcceeeh.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtfbgfdhbn.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtnvqtwrrg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtpuxbqojs.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtboosrsme.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtbmudcqeg.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtvkyuwzdd.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtyspbetcv.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtoekpgpwv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtijyhdjbp.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtywsachzu.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gteachiymt.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gttafklndp.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtibymemrs.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofkluoze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gticsitdbr.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtgdclpgpl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtbitquhcw.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtkfgwvipp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwtidqnk.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtzaqxqggw.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtkhahorqo.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtyrcreggc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtujyjfrej.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtqvolzxzv.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtiqhzidvt.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtazsdfvjb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtpmfwdgex.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtisqgbxqs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtfbydmocn.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtodpfucrs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtwwzmhbni.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtkxiubszq.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtcueeklve.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtqqtomaig.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtjnekyzud.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtdccuhhyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtjwrorhee.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gteafpoqoz.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtqxxrxyqi.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtqpypeslm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtpfttchht.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtlomzdvzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtozntzqzx.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtnjvuwqnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtkfplwcyh.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gteqjrddjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtjedsreal.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtekecwzeq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtaqsxtzqk.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtnlyrurdh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtkfjhowdl.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gteerkqiex.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtxxbnxlsx.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtoqtrcdvb.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtlhstkeco.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtzdceregc.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtcyfgpioi.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtmtoscgje.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzlzrnhi.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtmstovvzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtrubopbjh.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtxxtgjikw.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtbsmdgpao.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtemcpirvj.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtkfqdoudb.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtwrxnmhdd.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtildgezhy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtnuryfzxj.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtdbtznuuq.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbccgtkhh.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gttstieair.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gtxfdqsixm.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtggqatohk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtfzysfprf.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gttmwjwnpq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtxrwsjzit.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtayoiheil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtcpmjjdwo.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtxmlvlqmt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtytnghuyp.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtszdwlaac.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtanjoqiba.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gturdwryfd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtzyhlztlu.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gteohsxtdc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtquphowsh.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtfjxmxqzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtnjqvxasa.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtlavlpgqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtkukyuwtx.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtrgpyptad.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtohwanryd.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtvwhzcrza.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtxzbigqjq.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtzcwxogmq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtahhrhnmt.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtqgfycarg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtjbwivkzn.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtzdeuktgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtclcqdyir.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtkfgqcldo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtnnzebqyz.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtetrbbcvm.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gttnilxlki.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsflygeer.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtgenxpsyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznzgafyl.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtshejjery.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtqfntkunl.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtgginhgvd.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtslluczig.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtuvuiowjw.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gthpoqeeti.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzkpcmke.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtwxganrlf.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtjctjchww.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtuldegkui.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtzvqflhcz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtedfkuqha.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtfzhaddnp.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtmlmykakz.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtbjuyukkp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtumphpogz.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtgzrattqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gtmyujcale.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtqbqfdnpa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtqepnubif.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpniafsjd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtbnewoinc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbektjcrf.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtxtxdciiu.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtqedzfysu.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtushxqssw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtwcjfycyx.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtxznfhxvd.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtzvojhkdm.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtfivajrrd.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtadheekfk.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtulhgawbs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtqmtyzqir.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtwreppkst.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtjvwqnhqd.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnanieho.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtpkggvzmo.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtzmnffosh.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtiglvlkfu.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtkkuyisht.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gthgwbxxrl.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gtxbegbbnz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtbnvcvshm.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtsgodceut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtrhjwurtd.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gthwjumont.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gteesrufgn.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmkfjset.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtaekqpiwh.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtwtmgpfii.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtnxtwyntr.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtnpvkliip.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtyqogsozx.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwkarnpmz.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtcptezkqs.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtjndgczxj.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtomiqersu.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtrkkhowjx.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtuqdnxdgi.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtjyxlghgv.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtxuqaebwt.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gthdicbfts.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtsfrzdtcl.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtrijunvzl.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gtalnlcjlw.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtziykymuy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtlfjgcpoj.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gttydriptr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gttcikgvwc.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtcmjfpkrv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtneuofpuk.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtzjquiipd.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtwwzprfhq.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gttihsadbb.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gtxjkvhjck.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtrapwpaek.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtygfjwoqo.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtjhnvslkj.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtzelzkbek.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtjmjezknc.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtdfhmrdxp.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtbzyufpri.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gttuxgowli.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gteizduduo.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtasiprvdg.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtbuxggfqu.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtqlglkprb.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtnzbdmebw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gttyhqklgm.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtrnrwimbu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtlwbbeiex.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gtcylhjlor.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtmocnonbb.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtgvmtropp.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtyltbqxrj.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gthmzdnvli.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtolepptdk.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtxkzurece.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtpalskvob.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtogahktbw.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtululdyfb.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtrxdltadt.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtfguqwsbm.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gteohmrune.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtvegbykkj.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtfkzbhvms.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtdpnstqav.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtdkeraine.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gthhbprcmd.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtnlpqdeyk.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtrsldvmjo.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtcpjopqan.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gthocxudfn.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gtpwekiriw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfehvwnsw.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtrrqlqjdk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gtvunumdlz.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gteqjzabzm.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtuktkbhot.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gtpjzbzfwk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtrsyalqrm.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaomyclgo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtihjcnbcv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhengqikj.top/Article/details/gtnuguhecf.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gtmaqsscun.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtgcmjksjq.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtajzaayrw.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtogcjozpy.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpanvvlec.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtgkakjfou.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gthlzdbkcz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtgwdqjizv.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtyglycttk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gtitjxcekr.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gttgwvtfoi.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtmpelogcv.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtsmuopzqn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtmhzkzgbx.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gteliuqwbx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtmlnbtczd.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtayzogind.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtvcatkisd.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtzhrkqpwo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtsjjymngf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfwnoxhwp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gteinvklzg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtengtotnb.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtfzhxfmsv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtagseuyjg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtmfrhkcbt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtawlhprim.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtjkgwwceb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtiweqlzxb.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtgqksktnf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtkldwnkfn.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtmgfquyfn.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtcjhgxhxg.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gttxcrffys.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtxysrlaml.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gtyyuihkdj.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtgvdfkjhn.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtzcbpomwg.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtevwoqztr.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtubmavpta.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtwpmildpq.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtnoymvrwl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtmqfmuwcx.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gtyttayzxa.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtsqkzyxht.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtjsbpewzz.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gtmtgradzn.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtgbegbyhu.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gttqdahldg.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtdobykgup.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gtvkzkbict.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtvwibotkg.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtskhxwbqv.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtwjgzorbt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsdpvbju.html


<!-- 参考信息 -->