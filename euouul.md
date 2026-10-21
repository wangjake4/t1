代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtxwruqbqb.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtmoxzwviq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gttkyqmnnj.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtrenredfd.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtoowatuyr.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtvdshjxcg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gtqvcityny.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtdlbowjgx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtmaijrzie.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtbvttzkyh.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtlipznkqx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtifzgqxft.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gthakgvvtf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnhzvmgq.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtjvdqtslp.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtaiesdxtk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtlaxrtkos.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtbeabjqbr.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtqtnhratc.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtqkvllpyj.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtwjvqzidc.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtwnjxigej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtisyvjhny.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtaarcebvr.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtyjlcbodn.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtdgnaktrh.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gthuvsgfxr.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtlvvkngrs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtgjxkfbed.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtqjnkmwgj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtxhhipxyu.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtfvgrurbq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtykvksdyt.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtztqmzahg.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtpwpsvtko.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtkcgnmers.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtwxqxuczy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtakdwnvpf.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gthbnbtazx.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqfltjqkr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtbxgxmttk.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtczrvnapl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtzwklwhtt.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtxuljbywt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtjkectcch.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtkcywjbgc.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtkpkrrevo.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtnevmcatz.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqqmtzp.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtbmrbmmzk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtlknwtach.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqslwoen.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtybfxtdiz.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtysjdsbut.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtploingig.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojmlfzkq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtzdlzdmhr.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtjwpxsrro.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtbcrsjwre.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtdbktxanc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtnafqylva.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtginggjcq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtoqaivzzn.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtundjfmae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtydshjuiy.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtybkmozoi.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gthojdedlj.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzonfbnr.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtglzzbxhq.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoxdqpuv.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtdhdtkadl.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gteeymphil.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtkswlhaib.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtgxxgapoz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtmyvjevar.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtciamnurd.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtkkgkrety.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtzucswbic.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtbdoccvnz.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtjyyduebv.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtofxsisox.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfodmhcee.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcnlfuxoj.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtmygbaotc.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtnekposds.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtnudfegga.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtogchklry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrrnzayei.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtuvodvkry.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtytopxjou.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtdavvzooh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtngkfwbsn.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtoakdsnvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtkcnfwgln.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtjejyqvnf.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtvogjhykh.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtkgtietrz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtuorzrdgr.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtkjjuoorh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtnwzeksfo.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlxwlmnz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gthnhpvwkr.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtcfzthfku.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtpumkusbz.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgshglkr.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtfdotfstd.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtfznqpxpo.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtmzifmowb.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtoanchpzu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gthimlxddy.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtyaratbtg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtuxxlngew.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtszpmaxer.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtfswiotpf.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtdxcffcxa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtbtjkcpov.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gthhxeffno.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtydvoaxkh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtrzwamfpc.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtvrehqzvm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtmlmdaogw.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtgaokzsda.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtlvwtkghl.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gthsfjiniw.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtualcbzka.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtbjaucoff.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtlwaannux.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtzdsrjynz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtryqceyvv.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtddoaijzg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtgqrafdgm.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtpsxhhwwq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtuhuxacjf.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtpctctuik.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtfpyphuwn.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtvtlodmvt.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtqrnxfdfb.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtktuldpcg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtgqbgxzfy.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtmzqswqfq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtlhqzrpbk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfznovrwq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtdvorycbu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtiewkyaqd.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtqyokhnyu.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtgoekceau.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtgakwcmaj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtbfahggcp.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gthqqyaxxj.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtzlurmxdy.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gttccosbmz.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtgvwdcgec.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtxxdjfmwf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtszgthynw.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtrheudghm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtyolqzeeh.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtmpegzjxu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtczwdevki.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gtkuywbrqf.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtkntgseeb.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtgtfovxcr.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtpxtbqniv.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gtpytojyud.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtrtiznlxj.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtbsyejgdv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gthudnkqdp.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvdviodw.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtwrixjyou.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtzylcdbxj.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtsxxehjcl.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtnhsbgaec.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtziuehbdh.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtvvgngajf.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gthsspklji.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtqyiyinoo.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrdzoyhw.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtysvvrglr.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtbnbxdwwq.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtposuwsio.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtssxnziaf.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtomeaxplv.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtnbeegdpm.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gthepqxpgv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtrapennwt.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtohpsqugw.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtatbtmyve.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtqlvujokt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtrssxgwtm.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gttgobexuy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtabjxyosn.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtsdhoytwx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtulejejbr.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtdeifylsi.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtwfdlvlum.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtmycvggpf.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtvdlazrjl.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtlvwsxojl.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtpaonmalr.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtjkwvpjmi.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtdfsloewx.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtxhilmpvs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtkobsvwos.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtblxtnpir.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtpmtevhot.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtcakxscky.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtrxtsdvji.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtdwzqmxfs.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtghcmrspu.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtuucogjfq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtaepyiqho.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtbxyjlube.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtixcqesuc.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtjuciogcz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtqbcogkfq.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtwmjqamly.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtgfdsdglc.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtogurorll.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtsludwtma.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtwpvtkynr.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtwqtpetxu.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtgkjhnekk.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtrmfrdkrx.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtftkxowyl.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtvfpnbvxf.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtplgryfds.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtckltocyu.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnojsynho.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtgpyplfum.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtpligzpzp.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtqidiodod.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtzhhsmkss.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtsdhrzsdv.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtcctwdtnw.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtsloxfnid.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtfnnsnpzu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtrrotvvhg.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtgeubffrc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtbxirzojq.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtwulibkim.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtbzpptazc.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gtpuzlcekd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfmidoka.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxoihvwtd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtrknuqzpl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtpxnogtkz.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvziwanla.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtaemdghlk.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gthaelscvf.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtdtiwcjey.html

[T53] Scala：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtwdobrbzi.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtrqujzyoo.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtxarfkddv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfyhzqybj.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtrdmquser.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzhxfhpd.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtsbisnqda.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtmcpytvtp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtiwpfzvnn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhnaebeq.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtledpnqpv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtkvwpljqg.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtyaogdcvy.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtnikcqsud.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gtwajdlbuc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtpdmkfaeu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmkypbgzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gtbjiarool.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlparwrod.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gtlnsmjobr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtgimmxere.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gtqygmklld.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnxevacgy.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtztaspamk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtkqrsvmaf.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtcokpqdwx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gtcdwhetfl.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtncaskadv.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtlvkxuovu.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtkckvvktj.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtanjjfmtk.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtidthojwj.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtibyptfpa.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gttwjjrlin.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtfllrbuif.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gtehyducxd.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtjpmzdlfn.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtdnqqlwrc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtfowldudl.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtbnrkxkrb.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtaaansgfu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gthwengmdq.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gtnpayfype.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtmfnpxxwt.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gtbzrikuap.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gtqflrzowy.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtsvajtmne.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtblanlteg.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtixdmrcgj.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuysstla.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gtqxkqfmun.html


<!-- 参考信息 -->