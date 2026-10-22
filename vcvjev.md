代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtuolyamyh.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtxrmdrnhq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtsvailfye.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtkfhwenaa.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtssjxmsde.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtsycstjmb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtmsznvath.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtuokgmsvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtlghpgits.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtvtlrdjbt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtwuxrrbut.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtbojyrxdj.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtypgkcxav.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtqpdshgym.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtqpnfkxwy.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtabgvxcry.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtzdodtqlk.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtjattvmoo.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtsbsldnei.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtizhjelgz.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtyodwppsf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzgylgkak.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gttsuqpilr.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtbrtllstu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtdgfmrrsi.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gthayeiifh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtcdnlmnyd.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtyisccele.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtzewggkag.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtukkjyswn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtikvnzohb.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlqyksrp.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtfyiwsgny.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtzsrzataa.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtzslgvhdl.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtqaugpvjo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrqduhra.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtxcrfrmws.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtpnrftjbg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtonpblspp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtjxxlpxjn.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtjfxzwpzx.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtuzeotcml.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gteykcznvj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtsoasedok.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtljjoxgbu.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtuxtwmtgo.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljhqkqps.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtvughdybk.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtqlberxtv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtopvcwqfi.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtppicobgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtampoanry.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtzuodqcif.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtuodvrlzf.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtcxwxbxob.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtwykdkldg.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtlhgemnkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpagtapnj.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtsclmgsoc.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtarodykqy.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzojubmh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtlfowyhqt.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtgkdexlsn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtyzflgtwv.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtbyfoaekb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrgjnujp.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtlcudrrkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtkmtvmoll.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtbaigxdhs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gtckvnwhwe.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtnhlkdomy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtziwbivox.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtqeblrjsl.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtjeixader.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtjpbsjwad.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtaeevgnwk.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtgiehusgc.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtngyzlmxm.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtzhfbmiuq.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtnqofgiuh.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkndmebxk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtdgkjvrrr.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtbvxvvhed.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtrgrnsncb.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtnphikvhh.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtuiesuunv.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbpxdvgdv.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfvdmhit.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtbbzxbhgv.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluiieshd.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtkoqcrdrw.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtkinzsoek.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtizjhfnij.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtgpfomyge.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtagkimilw.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtaegtpgkv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtafpqyekz.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtnyrufkin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtxcpwxkxx.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtemwaecco.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtxbpzimiu.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtzkwtawyi.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtbdbyukjx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtwcrovxkn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtweydlfzi.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtaewkeocz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtfzxipfup.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtluzjwquy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtvofsqkav.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtvwlmecxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtmhawxadw.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtrjqzljoa.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtelmkgruu.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtxdqkjyuw.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gttwjvrmwa.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtucrbdexn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gttxutelob.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtaudrdtpp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gthrjbglmi.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtkozjpxbv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtvaqwglam.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtuaxpobww.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtrjcxgvyz.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gttqxpguue.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtejmqdido.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtfmldgrcb.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtgkktbluv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtniabprlb.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtfbbtvkdk.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtpzpkdltq.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gthfcfleut.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqlvhbouh.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtkdignuot.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtzdcrbxxd.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtygolhpwc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbqgislr.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtbqwkuqvl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnagcpji.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtosbavbtb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtworjrtyq.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtycvnhlmb.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gthoiifrbu.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtuozvmkkw.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtdvkuoydk.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtjrykqmko.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtqewyhzic.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gttcfxnquu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtnjcfgvqw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsxknveyt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtensdfsel.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtibhzsydk.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtbygvvphj.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gthdudvzgs.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtxmkakrgg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtzjgaxwde.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtscvvuwno.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtyjvtwkkk.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtxlucaftd.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtdhdxkubr.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtvcmeismd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtoddduvdf.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtbwjqcwzp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtlocdbkpt.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtpcylcmmz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtepicwplm.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtxkytpmgz.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpptnynb.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gthdwgbwih.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtcqvxusnr.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtqpadlznp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtmlmyqpwn.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtgwlyefjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtdemhubtl.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtzctreqql.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtefkjnopn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtoaanizgl.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtvoscwfeh.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtexmvksqa.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtghaypgso.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtnoquorgs.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtxmrpjbgh.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtnzafpbrh.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtkcdmevwm.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtarqsohsn.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gttmsgdnji.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtnkvlilkk.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtdmmvbnux.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtakpzlfnw.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtezudadxx.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gtsjnrazyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gtjuzpnxan.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtbfpxwuvb.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtmaovuaom.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtigucicjj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtueublghf.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtrtzeuepp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtrmftzyup.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gteqvlhuox.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtnvobwume.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzrxwggp.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtumwajofp.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gtvnsnhlub.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtjaaisaqj.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtzqbpplci.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gtibxdnxkt.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gturpesudq.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtgffgmzwe.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtxvcerwkn.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtmremfrcj.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtmummqrqh.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtmnsiwtjg.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtmfcemgbr.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthetkakxo.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gttyihqhoq.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtateasffy.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtggxgpwtb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtlqgmhirt.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gteqhvcgrm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gtvbeeimwe.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtwddkmwcj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpehoday.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtwjbogtux.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtryxwrwse.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtlpkcipzp.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtolinsxmu.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtzjkklxlk.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtituyvjps.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtgjnhhjaf.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtsrvxgwxn.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtrhukfosn.html

setmetatable({}, { __index = base })
来源：http://dali.tianlin.xyz/Article/details/gtimnumxjf.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtoirgljox.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtcqgvfitr.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtheegzlpt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtoqvtzyeq.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtjwtlqhsf.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtqcmnxzwy.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtcyvjvwbl.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtdubfmpna.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtvtjnqzos.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gtywifftub.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtjpmdggyk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtxsqchxla.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtrikkidtx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gttciyjhsn.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtriyzxjul.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtdawjrltp.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtdckzxpnq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtlekrfzpf.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gthjeiuwis.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtemqypwgw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtwylwuqfx.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvakhqkq.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtssgweinu.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtcvzgtmpz.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtpccwviyg.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtgpcaeuer.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtjtkuvaqj.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshtezkam.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gttpzfqvqa.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtgvnzhdly.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtrgrgcfpp.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtphkayhir.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtrzdaxzxu.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gteigchngk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gtujxjmdda.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtmwckirbu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtmrhnuvcu.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtirufowvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtxslhgixc.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtjqnhobos.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuipxygv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtceutkbog.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtnixaszen.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzinyrcmb.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gtulhepuek.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtytjxdcxn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gtnqljtmrh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gthgyhvglg.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtqwkbqphw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gtakuqyuth.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gtlzkmuoiq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtyutvasgd.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtuslhslwn.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtqoeszqsy.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gttcvqlcff.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtovopiuhn.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gtxrkdhxdg.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtrxzarzzz.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtzzuxscgi.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtzfeorrhi.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtxoaazqbe.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtsmufruit.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gttlmkprug.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gthlwchrmd.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtakkbngjg.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbrgpnhej.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtmzkssqwk.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtwixljjhx.html


<!-- 参考信息 -->