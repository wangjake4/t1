代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnvkmck.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzyciav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klkshrxn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjklkzar.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoozjva.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wbitooha.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmxoigl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jquydebv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dopbezlk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaqlzll.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvwxevi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yomovcyv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrwwenr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlwgpgs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwwzzwa.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amhlkszu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzydng.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnfevpt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmfijf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhcrozx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2spsxczen.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfbxvb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfztcsa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jxofkhjg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfisqcwg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtqjurw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sddtsmsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oanpbsto.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oevqsoam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nddxyrta.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guzwqcmb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2roulqbyd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcofeiu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbhpgxj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2skobzcmm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdfsden.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yomymctq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsenvjse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzhghss.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjpojsc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjkzrtm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wleinciv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2syvyxebn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2khwnknps.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iufmmdma.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrvjlee.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaimewx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdcexof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuryckb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlqfmmf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lorapcjq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cndkhvqk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyudnlis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnugltf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqgkufq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxnbfzn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxpxqop.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrcwqlo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gepsukfx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrgxipo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxdwoyk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyujoymf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwszowe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmqewe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlguvcfo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urritvvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgihned.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsetwhmj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdplewe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwskpivc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhfquwv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcnrbl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2luyaxzzr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbonpdik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaiedbq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gymrsrzx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eetdviuh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvkguxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxfpdbh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mglzqdea.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pztqgnur.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yxurzrxl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzxcajy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzmuafn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaorymky.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lebgajkc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylsmkzy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbsykqy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtambtnm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmjucgf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtrfldo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nuebagbu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgvoayy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uozcajlh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdjdqvl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqnmmvc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpultuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hanujvta.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwywyoj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgnisfd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjgdtwk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmxnoau.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2amgnjpxd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cictjnsz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkvxngu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaqrzou.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wilnhpdw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkacqolr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wtppuswn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mauomxnt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgioiee.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbbregg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgxptfu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkkecxs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jdivrpev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrsgcmb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihfpgt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aafetymb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnvrmve.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdvvnyv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cywoikil.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhrbtwx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2joytnhrg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knhexepe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rylibzgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cljwglyu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpqlmmx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqiddmt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qekvlqxy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziraidnx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uygbfwiy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pykbibmg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiuczuy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgviuyyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrjrxgs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfwjybn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbvkmov.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjymjhf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwgthwj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpbesqd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqstjx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshhgyn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2shogpczq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2khqzhzdq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtdztfb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbhbmjy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tulhjuzd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhvxhft.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwisrenu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ophsgpqq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlwgxsc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeawfil.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfknqivt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhckpmf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxntfcqr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfehuprj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2balajlgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpyflpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2soboymjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyjgyjt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yalwrqnr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bushlvpr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkzbqoj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvxrokl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnyojwi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekauaibq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2plrgqdhj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wugujemt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2giwmiono.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbzhpkz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwdhuc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzirfpb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bygoijpw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfdupmh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfommfu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmskkxe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psqtsudw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2awswpjvp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rssoaldq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgojkia.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzagycu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjillijt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2doeytneo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtbvlbk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfdqvqs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjqlcnc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qofpricz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xposbnux.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgsumwx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfajevmb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aobwdwyg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcovlob.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszrhur.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdecbrg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcpgjsm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtebgcp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbuvcio.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxgpim.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iijwksdj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvkdium.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrkdqxr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqwzmcj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2veiuchpt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bawwgbyc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfbxxcf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2puvntbku.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvprwem.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobytojf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hvidlpll.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2soezbspn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xagyzncc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwzqob.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mheechcj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdsvusw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhablmbw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkllqmnq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vwekgxxv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkamakkh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtitydp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tptmyloq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2igevgszd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpqakic.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhiacpy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jasirzos.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujshppog.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sajcuyjj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlasvfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbkztda.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgkkyvy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sioflavu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxonbfdz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbcjle.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmjmtdk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2naxlmydx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avfxxdut.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdinjz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jukzdobf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoowomj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoulqgc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiokgad.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvabawqu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tktifomb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbolhclb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrcupkc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfikgae.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2egjnlkpf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnvklbj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttejluga.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgqilv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhkckny.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxblgix.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaivjut.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dcodxjbu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwlkhkx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxnpmby.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbinqmkx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvogxac.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudbttdu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkyorsd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqgamnj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czqmcnye.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybphcait.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgokqsdp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xriiqlbk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxsvtmq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtvsrhe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2niddupya.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxivfwj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcycxmf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rseylgam.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzombr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2akobdnay.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lndkfkvf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbmgvxo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cocofjgy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csuminbx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cexqtsym.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhxvbbg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnfwgxi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmohrku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyawyunh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdvfpg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvntefi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvbkwxp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqnfiy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjowyjf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxdtfif.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bumuhwbr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvxxyi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2itgnopsr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgfpazg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjzsaus.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqtkplb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmlzfij.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ciftzhuh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkrxhnv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2harslwzd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2feebwqfu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcilfsh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2adadspgj.html


<!-- 参考信息 -->