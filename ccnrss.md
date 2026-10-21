代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtwczoapjq.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtwstsispb.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtpechexci.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtfuyxpeam.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtsgfpkadc.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtessynlhm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtrgixpyuq.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiuxagfq.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtupafdlsn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtljqijvgb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtjuqlbede.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjwmqplhw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtyvvafybq.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtzpobfbfi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtoddryjmg.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtfhsrrnqw.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtfskhjrob.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtlzoxiniw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffcuione.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtqqkxiybt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtjxfmktqp.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtkvzyzikb.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gttaswfzbk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmrydneyc.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtxgsnqldm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkqtpwksx.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtfjvixddq.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtfsdmkjri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwqbuqpji.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtfniipswv.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtwhscqdqm.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtemjyvnni.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtlfsqixlh.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtujmilfyd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtoolilica.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtrqydivtb.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gttuugedok.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfskfeeyb.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gthquxbvzi.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtqsgorlua.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtxpicbewh.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtjdipnehs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtfweksqvg.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtrpzaiq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtwycdgxax.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtswkrgrmw.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gteyxeaxxg.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtnyehiwmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuadgtroo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtpnmxdsac.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtniqzhxjy.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtpitxbxbb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtjxjwcwze.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gttfibrmug.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gthrdqijid.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gttuqhhmxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtptuuvrxj.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtpjwwpxqi.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtymxdivcl.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtrxomxdbv.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtfpuaoesr.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtmrkmqmkz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpqatgcr.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtegrcnolu.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtxceocykz.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtfmhavjib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gttbbyqqlh.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtvfroahpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtkpbbpvww.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtuxymjjfs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtzwziatkx.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtlmtoztqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtxtceerkr.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtvjmdigfh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtsedptiyq.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtskkszbrg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtfnduyhqv.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtwxgsybql.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gthkpjlufh.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtelddgteq.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtwhpcgpol.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtyudrezre.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtnugduekz.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtrxtmeuhg.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjdujdkd.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtynhtzjhh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtfzrzaytv.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtunlchtiy.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gtuynvxnjh.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtttcjuccf.html

#endif
来源：http://dali.sweek.top/Article/details/gtvpcwevwj.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtzsajhywa.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtomdqheof.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtblpuflir.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlajcemnb.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtuhofjywp.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtwhasfdjn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtunnrcazm.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gthuzclizk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtyxfmllqw.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtflcyxuku.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtaaefcelu.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtszettavi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtazpaxehb.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtjxqsejoq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gthmedlzal.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtncoxwyio.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtfvriytod.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtvwzrlcsy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtzzksetny.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gterjdsjwp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtlomrcmop.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtliazxums.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtchwyvnpn.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtcbvbymld.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtwcaarsyt.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyzzadww.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtxzkexmdd.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtxwswwfmy.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtzxdyqohc.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtqzbxrxsu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gtibuefoxa.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtqzbidqkq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtxrkjhfqt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtqemutjvh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtqeesbenc.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtitqtsolq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gttzunnxlr.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtintyfyyq.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkububixt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtzukwwacb.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtaimrguzx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtparzuqru.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtmmjvwycn.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxogckaqc.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtnkyxexnu.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtpshnmdwb.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtdqictmjt.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtmokxzudw.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtgzfazlpw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtmuxcyiqc.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtahrraoxi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtsrcuatci.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtmvtwomep.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvcwclet.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gteovdnggp.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtniakysaj.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtsvfplmia.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtvcfcfanm.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtbjccfauh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtauyvsxdm.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gtrmbspzsa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtwojcjhwn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsinkefr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtnxhzmcgi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkdfatchu.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmhumzzvn.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtvghsifeq.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtxddgnvbg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gteqfaorvs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtyilaopdq.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtyrweqyqi.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtkjdvrjvn.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtkkaatkus.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtyycilvmr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtpfvgvrrr.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtjxuuxure.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gthpiqiabf.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtwflxblta.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtinobwcuc.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwlpppe.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtdjrypeuj.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtxnzdsomd.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtlysxyqfb.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtsnizmody.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtwhtiutdv.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtdblnfshs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtbyfwlghn.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpudpmhhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtasqbjijr.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtpqshbqjs.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtgvjfyffw.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtzjjgpqee.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtaywyxydl.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtlynezrzw.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtaugeoiet.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtqnjpcsrf.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gturaivvgb.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtoyxpogvq.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtysoihnrr.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtbfxzmwtf.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtymlghacf.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgayxobu.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gthtmhzmbg.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtleswhtsa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtodqtbnrk.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtfogjpczo.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyhgyzem.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtsqzryayx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlchzfshk.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtbeukdvto.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtqelqoovt.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtkjmafxdo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtaxeqwiea.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtoemwzfyr.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtgcgstiqp.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtenqihhke.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtwufvgusj.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqxqfrcf.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtqmyfcpnz.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtsfyaqcdv.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtcpasmdqb.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtzalyooou.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtgyxzihnx.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtfuymsuka.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtfwkmjkde.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gtsoimacyz.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtalycjpjj.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtxgyucpnd.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtgwtqkzbl.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gthkmqkwkx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtlcgothmd.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoelvjlnk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtkqytrjvz.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuazdkazp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtxfosqcjr.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtrvmbbsuv.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtnxorjlpl.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtasxkusxj.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtyzakvarl.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtkzgqacxn.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtbnzgclkk.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskojfdly.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtgfqacsrx.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtczrqzpen.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtrbuglypz.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtojboinur.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtietkhsez.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gtiorxtdjg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtjnioipys.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtrzzyifhj.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtttctjgiv.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gtvylxninz.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtlnfpiudn.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtddjnrnmt.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtatqnmxhs.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtwxireglv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtfnggrssf.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gtkdpzgxpt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gttpqgxcla.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtudkvvedm.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gtgooaaewd.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtmwikqeix.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtwusimolm.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtmeoxfarh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gtbkkbgezw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtjeczcnbo.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtvyuupjym.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtlfbqsgbb.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtpjimgrtv.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gtrocckuzp.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtxojltvhh.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtqbznluhk.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtzyjsnqvd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtceqatgpy.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtgimnovti.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtedalciya.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtapchfkzj.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtfqvbkxur.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjvbjfuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtujdxyfir.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtebfgiysg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtsafsuyiv.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtedvelmqs.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtfowdfnrq.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtlmbpwadu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtuuplaxan.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmitfjqwn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtlihdxbql.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsdflwpfn.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxihfpqzk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtubynhqlb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodadlvlt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gthfvzuajx.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtaxomyslz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gttsmqjuhc.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gthoeklmiz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtbszrgxzf.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gthaiecvkr.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtxwmozwgs.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtkprktsvs.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtpvljjlds.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtpaezikih.html

{v: k for k, v in d.items()}
来源：http://dali.9152youxi.cn/Article/details/gtyhdotcun.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gtkhasdxkc.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gtyhqoecrt.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtivjhpgoy.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtkjhhixvh.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtdsuchprd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gtxzkbdpaw.html


<!-- 参考信息 -->