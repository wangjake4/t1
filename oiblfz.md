代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ghexqulw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mltytueu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlbkbqq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhbabgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rizahmdk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwafati.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbebkcc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnjhywa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwpbvbb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzqxdll.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuilwqs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2scdthicx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkgprqu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2djzruest.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jltzjxzd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqgikyo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzlwmya.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qskvowrg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iorkqiaj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2puzuinnt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhzzysp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2atdmhfrc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmflacnl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgxpqph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbogdf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqlyodm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrqhcei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abjxemzo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwbrqwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpvypag.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndryzycg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfebuoog.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnofmlon.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uravenox.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyraeda.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvldtlt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcsexoj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrejfre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfarczq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puedtexj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zogamwwa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvbgxwb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mebyeudt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oazpxxwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuuccah.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdsvryc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2btuzuwxg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpuykyh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaloaxt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kodbtuik.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywvsrf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrolexk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwpbwtp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wprybmen.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjzjnz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcwpeku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzqcrlp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdszvtf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2saxuxjfg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyricqu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxqtfwx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tamwxtoi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwjdme.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kwndafcv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjalkhin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbibckw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxopqtsr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smdxbaqd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysuyikr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2epazczmz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeeqedz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2krdvaksg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcrqjae.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uptjfvoc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2migowomh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjamvxi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhhdvkj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvkbbia.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtvefcx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2znjhglhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2odidyvga.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pdghpswg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gscrtoch.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyzjlsy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pruungrb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukekqgih.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvbmtwe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elbdawna.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xudeeqlw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrfkpos.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahqnkmg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bamiiktx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcumbvv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmenyn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiiljpr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ennbhhsp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfklfhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxroypdn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctljtsbi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbemtwk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gevlewld.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chcbvfpu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pcylhjwi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mancmncl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdghldjn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edimzyki.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyivdyl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoaylkn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgzhlar.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptjtgn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pydvuvoo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdolio.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glzjlips.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiwfvdj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpiqhbw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kubanyas.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwscdftm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfbxvdj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxxpyau.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrxscyh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmywmsc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwexweoh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvvmfct.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymigdjjc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpaizhu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iellmwnq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rexwfzne.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuyjkhs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaognme.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duioyanh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtxdins.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpneqtvn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnukovo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idsgsnmi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkochmbo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2faonefdh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2azixxebe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxtakwr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwpbsac.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrymddv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmmdtr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2glecupli.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlvcyt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkvrdsp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbymoots.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodtjnc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtradchm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezmzgj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zklxialh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2varvjxaz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2csobjgvc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhmqsba.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqchlbeq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2znqserhx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrkznmk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnckfbj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vguceceq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjmegwh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqsnsmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmeogqc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brodjrek.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiplvuvj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzvjsmw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2onyjjjnx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdxdnii.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxutagbz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2noujtvuv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2znhfjuke.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwxtwcd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpnoaom.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2arybtzjp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouohzjme.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eojcckpy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2keniwzku.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwrnmpu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwreigl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpebdsnz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxmljag.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pacqpzvs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwakfoj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2peiavamn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2epzfknqo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgcvlys.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafxxwq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqpvszn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdmttdn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2daepvxwh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfharoh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uvknmovk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnkjygr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnjqsjt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnrwcip.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxzwpwb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfjnchl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzuwqqi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2udxbaujn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aivdzsoc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zofnytry.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2darfdgxy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dewvuted.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvftmthx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfjjcz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqqgxy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwqcdqv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjribmsc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whcmcykv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xbefuoxv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zowlbyhf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yceptwux.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqokzx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkkzpml.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsinzz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljicvcgb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeqbyec.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgdvrja.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjjphja.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bivbihkp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlixtjm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjamncf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwdhheq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jikwkczp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkthqre.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nktzjrip.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2swpkuuwv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkvluta.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ltifrsrb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2luhuymsr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzsudho.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctbyna.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnjztmb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhksvoeu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzzwjkh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2skqfmlrt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqfcaw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2juoengow.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwypafu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ieymrycv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdusafoi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sueslolu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwpqhas.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwtilmj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlfovgn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bklkozkx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2otonpshn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqjznke.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlaspee.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxbbvju.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwbcuou.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hahnufys.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcbhloh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyggisa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnlixpy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrisqhp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsinseg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfclhtg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqumttv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynohcyhc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbcjkpg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfcdcwl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2atwiyvmf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsgkhqf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swahwlen.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xasxamqu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swybpzau.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgtbftp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbqazef.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqguyaqk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvausfg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkgoeyx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2voyxlfpn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rybjvrfo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwvyyvk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hydsalzf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2reckptgw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnseliq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhpgsba.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvbaizf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbclybgw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzysnedx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nngwtmtr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qawwuoeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzltfgii.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvptcuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhwwpyc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jakfxpvb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bcalwifo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgsmgty.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skuagndu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ussytnni.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zznbmxrd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgqdbqn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gqutmxgq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2irzbobnf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvumlwn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hemxyarh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfhihty.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2datoxjwz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyjhzxn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqcslbz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdasxlzj.html


<!-- 参考信息 -->