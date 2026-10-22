代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgrkuwb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wccwooee.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2caejpgun.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2llazcqen.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzjwqix.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nhinmmcp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqwxkgq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pncaftci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvzssi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmzqxvu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsswxyzu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tevsnyxw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdcgfy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jwowvziw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxldgzz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znywczqi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sihemyzw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vetkbdqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcwwpby.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxpbio.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2etkypfiz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfgptdd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orpuauoe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ihodifsy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuxhzal.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wuocjfrg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuckrkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hefmdbdq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzrzsri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgxkljw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvybiyt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfpsopl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxtpfro.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2idhxcblt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvbxwav.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqujblnt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbitazme.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mahrwyjr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeaqivb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaywbul.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfzectv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yruebwib.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qntdaotz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fexuuryu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyytlehn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xufreeai.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajobtuhp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqxrlcu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuoyrrm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2leverqaj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eokscxgn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjisexkl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2twtevjqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpopommz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqcwcul.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlebpafv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahedzxdb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxmxqsd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvehfeuy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfpqqci.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dsccabpy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gveuvskg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqacnge.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgbhoah.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcawxvpl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuhsojg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnituah.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuuupzf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnlcqyl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjtkjur.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eojhhyaq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2udbahubo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ardxbvhl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvzznjs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpuaoc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhqftuy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjsmvtz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kssleecc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkppdpl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxgqmrt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpypakf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uglfdaen.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxsscef.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnogidg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oikdojug.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyszerqv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mobxnkyn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeivlel.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2niqktxzo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvlwlkx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkailna.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vcydeimu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ololsqds.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqkeglj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2siglzttu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfikbze.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hpamtyms.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yahoflet.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arghtrnk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvurbsqs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvvafcw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwoxgnu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgjnjbe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawbgarj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zowraexr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgowyegj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynywdyod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyonpwy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgpfcht.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjfhwpl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpdrpsq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtpmldn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onkjqowc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtcubei.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dzieklhs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcljour.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qimorrth.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcjgtpi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxtffmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2odjjpiww.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzqmlty.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jivegrao.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kuachpcb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zftdyhjx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2emhurryz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuvbfib.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cixjlyzi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwcgase.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tihguvpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvvlis.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mysmdblm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrszhwly.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmpjjqu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqioagpo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rottzamc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmiavv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2byqrhlbr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjswhef.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfdhalb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgozfl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cneerbwa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2poiyefaw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujdllwd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqyyvur.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jasoonel.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tssulniq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfumhgp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2teiuxpfu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwboyje.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oibpdqvz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrqrxid.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gacfljar.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vidsivjg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhedsml.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptljyvab.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdrbeiv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxfruj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqccqko.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtxkgon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmjkixs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvdqpvw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiesajq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrupsfhv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2febbchsr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cduggmrc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwemkvhs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzvjdij.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxrtykb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlhkjdf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhvtvid.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vancbpja.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgpheln.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgtslkx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqlkgip.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yacykruu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsauhkex.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdzokcf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fszhxcxd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjfsdtu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxalhye.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxohrkt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjtqjij.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwlufeo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravzhmtc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgsbnyy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqelbmk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpwcvxg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cieuvayq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wxucftem.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cluytkho.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jovagpqo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkywdors.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2juhkywbs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvfykti.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtgkdsp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzjwsg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhutxaz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaeyiwy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ateqquru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2reuaocpc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxbyumq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwxutcb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwqoekx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dmywwwsr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqiqwai.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwzhiqw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2stgifxph.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whzvzonw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsnicoh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbkdmkc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqvgmc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2usoxrqrs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epjkpnqt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzzzcre.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zovxyram.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzhhbqg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mlshgqsp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2advldbxx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwhqoqi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zflqusok.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2poawmkxp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsfdlhl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzbwfv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrticjzb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecowbsqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwcjem.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyrsmxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnywkgi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaxzdis.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmgfxn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jstowmzw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjouoau.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uldsefjm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byxpwtcz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thbgmbhu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaovcim.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbokzhu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfttcih.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cszibgry.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgkwny.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwyzdvj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcepcpf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmbmraq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwatpglz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmbbwkj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2svdbapzs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvshpnpz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuteiqy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbiulk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpreksm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyuxjxs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnvcaop.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtfxlmq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtihmei.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2derenrug.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mutesqum.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjhpfg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ialrqqty.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyszkit.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrffqfcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzczkws.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqcrzg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cobmdanl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppaevs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxbiyli.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzyijcb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwmpzzv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeazxgm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyycvgjs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2miywdgmg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vccnbaiw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ggffhvfc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghirgmsa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmxqnht.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlhnsgr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuvcmgl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhemaaxd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbppleq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2themtrdk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2olvgfajc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmsewqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qayahtuq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyydyfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhnjrkr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmdslgo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdgujvi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgedpvd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjjmmqv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrsdbhg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eowdpmdg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tffmzghz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aasdktrp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkslteeu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdetspj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuripjh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnvutgx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eliyqrhk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2crsaenlz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipptjfci.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2grkikqps.html


<!-- 参考信息 -->