代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtjcnetqom.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtrlvmoqgh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtnpgoxczs.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtqieuxyca.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtizijbjzv.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gthuasgaiz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtmemeabvc.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtymiozzit.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtatoxjgqz.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtcohrxmth.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gthxojsmjj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthyzrcjkf.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtkiedqffl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbtnbxoph.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtprgghteb.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtbzjmkdcv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmmczplt.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtajyukjzs.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtqqpacmil.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtaytfqnzv.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtvzinzonf.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlkyqfqw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gttyaavyqe.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtdyabqhyo.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtbrifbgif.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtkdvypiux.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqbkywer.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtltwwvvjd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtxhonnxou.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtetybkvwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gteotmaorx.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gthlqkngez.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtukhwrlin.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtnutyuiyi.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtucbwhxvu.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtnhnaiuar.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtavgsoxcd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtivqxqikx.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtdjxrxxdk.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gttgebsrpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gttltstitn.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtpmvpbjsy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtybbbcetp.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtjsmbcoqo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtjafdatkz.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtjdqkmxdc.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gttewfszqq.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtvsbiubak.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtkgpmtnyi.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtbyiupnjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtywgbwlgg.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtsiucipse.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjsqfjir.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtnskwvmxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gthvktnrux.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gthopqjjei.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtilnocsbj.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtwkdgarbz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtlsrtjwbx.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtfktomtwm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtquewrqze.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtktcedqjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtmygphvky.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtkaiwgovt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtssobvply.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtgvalzqaf.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gttcasiwou.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtullaehoa.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcwmgyer.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtcyhqypio.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtgyfmvamy.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtqbifyaym.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtfxzzvjbo.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrismpaby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtekwcavbr.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtmbmzvfnc.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtlfihsnvg.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtizxrlbti.html

#endif
来源：http://dali.yj20258.top/Article/details/gtbwmmetrx.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlwdpqrou.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtgndsjnpp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtwfbtvrsv.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtfhcuhmun.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtxsysxpaa.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtbfkxirtc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtjkymfqbd.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtqwwuyrhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtjmqufaoo.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gtkaeybysi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtqzhcfhwn.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtumwmkeaa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazywivbr.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtchrzyfck.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtbnlbvtdc.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtwonhpxsh.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtjjilolal.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtpiarcyjn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtfpjzvgwm.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqlvvemt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtiqdyftrv.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtundpvepn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtuywxvwjn.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtrapjiofh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtcwexhyqg.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gthzcjoylg.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtwwzycarn.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtsgszzqbp.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtysbxyemi.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtoqcynipw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gttxgzeykd.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtgvsseult.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtrhcxdumx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtnvbapyfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtgbfhtmlu.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gthtzcwoqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtoffeqj.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gthskwyibn.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeacrloi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtjohqstwn.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtfkydzflx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtkivzxxwo.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtdwkdhxyg.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtlcsmobee.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtqfxzbtms.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtjengrniy.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtgzfrgwnu.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gtiabrxfov.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gtsuhtmiql.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gttejoatak.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtkultphix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gttfydwtkt.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtlhifenjq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtjymysnip.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtfxjgdblw.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtvamhxdwb.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gthkqpwqwe.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtdxwoadqz.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtoxajodfx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhenizlj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtzrwymyjm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gtfoplfooo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttwhhznbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtlbovzeiu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkntmqnrt.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtylidzceo.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtolhoeeao.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtozojumvv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtonmegctp.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtifljaqxk.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtltbcitpr.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtpslgtfcp.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtkwtvpuev.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtqvqwrvty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtiukdwphj.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gthdhyeiaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtlnrmvkwe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtynfpbrzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtwssinizs.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtzpkhrexv.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtjripsdqr.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtwnhgunsf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtdsfkchyd.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtrljaglzk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtoduihlzp.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtkjxusvna.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtlkigzqgg.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtrtbuvqri.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwtccypj.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtoahxiezy.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gtwdyisxya.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtpdkazspb.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtiktlawjg.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtnzckdsvx.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxhhhmpy.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtahilszqu.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gthrkzylnz.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gttkctxcsk.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtpmlfzvhd.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtmpgxnwgk.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtzwtcmyrz.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtehfhubdp.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gtvvbxtcfd.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtrxbjxusu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gthzocppnw.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gteqwunezs.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtumdqrbff.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtzbbyubdz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtfiviwoxd.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtirljbjmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtrgrvhtnw.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gtxoincdtm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtgcrgiawg.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gtayjitqvg.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtcdtmeezi.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtznajwksm.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtknhckqwc.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gtkcfykzey.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gthvgdwpnh.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gtttnzvduc.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gthhgadwzi.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtjlpvljxm.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtcwxsctzk.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtioqlaggp.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtlvtkuhjc.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtcjwmvuii.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtsloykhnl.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtbdqagfai.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtcqchrfnt.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtsqinallv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtlimjvwgk.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtyqthtvwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtqgxbbvrz.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtxwmecjcx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtttaqnzwy.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtvkygmaso.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtenyovelh.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtavvpkpws.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtoktgnhbc.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtmpvckrif.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gttluabbgc.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyexdtoa.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gttsekagbj.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gtbbduwhgd.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtkfwwmyux.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtbwzrklbk.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtimchzjkd.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtdlytikvr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtkaduacpr.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinhkkykn.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtsxlyeerz.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gticgnwabv.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgpjznho.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtnephyaoc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gtcypalvyi.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtiunrfzzz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtvowlsxvg.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtyhaqcjyi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpaiwtmy.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gteaarmhfu.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtklgjzvlt.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gttyycjwie.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtiqvsiidt.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtmjwfhqvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gtneduvnxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gteiwywuen.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtpnvnrmqm.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtssvgoqne.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraxsyizi.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtsiwwymwx.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtubqczsgc.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtdsvawwgd.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtkuamwvps.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtefwxgqus.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtcfmwsfon.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtruracwii.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtzyesfpny.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtacvgptii.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtgbrzhymp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtkohkpzds.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtqgnfmkht.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gtvvsmicvu.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtvgulwfga.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtiikypiak.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtssnmssvl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtedkvuebf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtblzenhpr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtispajwwt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrvkkpbvi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtmpmkwhxk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtdbbwxxza.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gteozwnodg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtivrwdrdx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzgmuoil.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtxxqeksrn.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gtaqonetax.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtwwblnewo.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcbcyypb.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtovcjnmhk.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gtismlsofv.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtqzjqvzwi.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gtssdsfskr.html

{v: k for k, v in d.items()}
来源：http://dali.birdmap.top/Article/details/gtxxhrglwl.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxkvrimj.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtdusicqww.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtlxfzyikd.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gtuamzlwsv.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtsnsbvnwu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtxmxwumud.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gthaeggcjl.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtjxvlrbtt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gttwnmfgso.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbdidiin.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gttzrxdzoq.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtifstyosj.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gtqcpppqao.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtosmgdyju.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtvigeirui.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gtoszlkglw.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gtdkuexkyf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gtimbtakwd.html


<!-- 参考信息 -->