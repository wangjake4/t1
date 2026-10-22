代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rbljofnt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqrgtid.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ensovliu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlivzft.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwtyqon.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jehmlpea.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaeyxfa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdzmxnn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2guduqikm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqtijfd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spszxjai.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2boufohzl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoatouh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2clczhnak.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mduaxxem.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiesude.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rohxeorh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jetoufvz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aefkvgfq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iclnqqrj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpuoomc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tgomhdwn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2caqueeem.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bccxlkdp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsipukdi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2txpwgdzp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fspwgebt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iarokmxx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ckblunwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyocegc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vibijqhf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazsclj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sikkwiad.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqcxmgr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lruqxyqz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqdlnzt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pacgvrzz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hoshdrrs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pghcchbg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sufurupq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoyljrk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmtvemf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qthksidw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkcsucr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtrciht.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ycicbwah.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgmbrrf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aljaquwa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fiflpxaz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxsduqi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzmqysq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygebbbmy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyjhilc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczudqqw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozblnfj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psizqiop.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2favlfatc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yavpncxi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokerip.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zptowupq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbrwaco.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkawoks.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwocsca.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2alcgujrn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slqvggfp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiaevst.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldicfmdz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpjuprs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxcmzsa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtairtxn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjnwky.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkpeedd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpirwwgt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gstqjeah.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2awmyewfv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwejhu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqnnabt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhchkioo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqforbn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuzzdxy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpjrurx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2npsxqsqt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsghqbg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zggfglyd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvhehhs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyseitz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxbpthg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brfyxbjj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbzkokr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cteisfag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcxxxbs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2axqztndr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gpccjqxr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfqrjq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2spzswpzs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnlwwum.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjniahy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cecdoxuu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqujnqm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sydlzgxp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvtpdi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidbgzl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jjazidex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjbyqeo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxxnfti.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ughnavam.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lezerhrm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqftwot.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2airgpjya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkccsejo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyzykdd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdyake.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzuenrn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2erfwcvou.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2drtqkqqk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbygvre.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rirgktar.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnyhgqd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wettgful.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqzbbj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtilbo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiwukox.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdbqjsq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqbjmou.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xmelybjx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbaeeea.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjsdlkl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmhpztc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnlptyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjnswho.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsoyayj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fghqhbne.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tregtwfi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgbeeqo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsybkerd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjqumzj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxinzygn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2njlimatv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2akupmeij.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxgtprg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smirpfqy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2laxyqmab.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lisedkmb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxmzhuc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxwdsmn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2trccbotf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdsaaom.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynftrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqvwrax.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awtbhhls.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanfpmlf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvegwiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwznnocf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2osxomkie.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqumaoez.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ketegopr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vcokhwyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdetzreb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcfglag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyntnls.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqqxofo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcdrqrd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slmdyybd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnlxzjb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpqccvn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cebbmvvs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrmutnx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxdmuht.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cauezwxq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxpqcx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gasrdefm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sonlfimb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykftntvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apqitrda.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2midexxkc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazjqrdj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2helhgruj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqahwvq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmdfey.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvzsyag.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpylcfwi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyaddkh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqjhjht.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyhyth.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2geofvxpb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knupapyc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpogqmg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxabdujk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aafpbbyr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixubjipf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2konoklku.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeqeaio.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgxmtpu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xigvtkpc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qduxphsk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbkpqmn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2surzvuct.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfvrlsu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwrqus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaedgllm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2toubovig.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rppuylwb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmevyjw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsmjbpz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ferymsga.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffryfmkm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lklxzwxh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrogldh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gwchisam.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtywmyh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dgokduok.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoqjbhy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvmixsx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbmecuz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vvifnzsn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqvwxbn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bdetkoji.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhwuyta.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlacmvh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvzvxzn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iieacxpv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswwfah.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrmjnoh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqecqqs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2itacexph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxfjdyj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeqymkn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgheicqb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjfjziu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wclhratl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iywwgspx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkdxwhh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ywppaljn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2alafdfpk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkweoif.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqumitcn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlumzxb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmptivoq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wihqpjrl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2amnueuaq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgycuss.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxhaerb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmaluwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrodvzt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2shpqjjft.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzdohu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxupnyl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvstdih.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjsfcet.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kffaatnh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwbkhw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oahdjtgg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwgworo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbqxwel.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdyloqs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwnmvoo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaumggr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzlxnvl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2penmynqt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdealiy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmvlofu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyrxozj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2shnnfipu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qskzeihz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twwtadrq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfqsrgo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdguynu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmbtohe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyrgolg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2suptjknw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeeovkm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubibrnqb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvsbtk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtatsxz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2npovezqi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aikipngj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2offxcrry.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2thisrncd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcmrxqa.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvtfwgr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bezrtrdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcaowfz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evuexrrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlbibsw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhzsddf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnfawlj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfqvaof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhvyuxf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyrzjex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdslltkc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2evopptsp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaupbym.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjybcesn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgazllba.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjjsch.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvrhaoi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxrabnc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwvaajf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpoumyi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpytcxb.html


<!-- 参考信息 -->