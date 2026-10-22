代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2erfrukly.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhtibay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acjyeyml.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmubxjll.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kktqnuzt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvtwcif.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pbavbqoh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsnsqhv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldikvwab.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkxoktk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyjpaws.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwdhtk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2daphsyoo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wijnvbry.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxfnbpz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqofqgk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2utkjrdbo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphgdqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2akpgxdfi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xbntsyeg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbtbjke.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cvunubrs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjyljmh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgjxkmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdibwjt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpbfsot.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwfrohw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrthhkwf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrckdxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojhvme.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zprpaczq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlmouvj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlesbukl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvavzqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapbmge.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2arvctjzd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2geagndeb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmmyskg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2neymrfsx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zyygexqz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqwqume.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwokcxg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pzztgliw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qrucfsfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hctpmuin.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ougxoxpy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdmlwej.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjhygzb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lmepiauq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqvarr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2chlpeeep.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awnnatzi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwiwfzl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimifvo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzztcna.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzaqila.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2khplchsb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pifyrbwj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsefpvts.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzsibad.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdjuqtd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eimgykfl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2utnauhrr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yubkfkzg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mswxktnt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpekxie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqizpt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuafxari.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvutokse.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gtedwdly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dizaqyns.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkjmdgw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodfjrc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmraqim.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwlfpsj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqqqghb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkskdzi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwicckrk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtearmub.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkdmsvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bueinroe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hybbokwh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mznotioc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nopenzjx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmozzrox.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcbtfmz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zccgoasi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etzzatnc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdacgjcc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkhbjkj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdhioq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvakea.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhurxvy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hejkbjxh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bswphicl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsbsqdv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzfeyeo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkhfnq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzraatrk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jizrpdax.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyqvcdl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2alargtlh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2naswpkjt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridgmqgm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nfepctcd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiihopxx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyzkpiq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2asebridv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ismubwyj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwyyulo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrmdbjk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gjodcimn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfjhoze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2evwactor.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmjtpqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkvkkos.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszreeu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhukesx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgpwiet.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdeuyxf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjgsbld.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvidvdwk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fxydpfsh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxckanxs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2puiwmsoe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xztkqugi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmptpji.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffxksxb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkyyuxd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iouxpucv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tphnhacb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtmhvh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2opqfswzn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owxhersy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeqebjw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mscytjgh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuztkbel.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2untlpzny.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxhpmfg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbituoh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mltfztdd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvmumdy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvwxqg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2larokqum.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mguhupue.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rognbgzp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2efmyzxoo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlfmip.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hntqgkch.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaujgyq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2agvmrpad.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsoyslg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqnlogq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vphqdeno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bejrbeku.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpifiugm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kncoxtdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxlemkd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhffbgen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvhonrz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoygzsd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoljrzl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmckoska.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmhjqf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tncjmoqa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjgovfv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqgcwcj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcgwdfi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpadbru.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxohmny.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2khjwykjs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sclmmkyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyivhny.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpabehmg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2strrrzsl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2clnhfxxm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kucjwhrm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrwtib.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tphyjlkm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjatodi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2acganbwl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyksast.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xawaswzy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfobcvr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eunnkkjc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwojkrj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwdktpd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmnbebl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvoyxm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgatkxq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuxducn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqesprh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznccjz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtnpigz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfgdvyc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqzxsaq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2stppfsei.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrebjyiq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgmatfb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iagtmqtm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzckjr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkwupfk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmnwru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2efveueix.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skphtyxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxopheqi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2goskwunw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgtumn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvipphi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcxevti.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoqvmsf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhdpblj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kpanydmz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2etcmvjor.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuxkfop.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwbjwii.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkvedu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhytjyv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2onwkmjjv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2byydxzet.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxupih.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcedgna.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnesrsl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xngrgjmt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjjnvdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhuvbkl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdwuxgj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lowgmpet.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzchned.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmrgbuy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dumsbcoe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wscipweg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrxmecd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ordcyebq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rurscrhn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2onrccyby.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvfqfpl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzclogej.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwexsnpj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2niegnbid.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuonjvd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhbqqwk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oodhadfm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fovpfgux.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2akptnaet.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnaxws.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuzukpb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anqctcud.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwxzpsc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbnzmhm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcjhupf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeyolgk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mdolymew.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orhvkcsw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiefbvem.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcketrdg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znohhdaa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacwuyfs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbyrhw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckjutyz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tawtnyte.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyxprfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkbohvg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2goljwsxh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhetmxge.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgseqjh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rscncrff.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzgqgqw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arydglul.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqwoeca.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakdaqtt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vaodufen.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2solukrbz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxgoqq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwcakey.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xumrjacg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gimlaelx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tirbvfzi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2olobyqxo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfyrtyr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkoavdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeaeryk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sngudgre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pffhtybb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lrobhgvk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrpodar.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkgihns.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkghjqa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnzjszj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2smrncrih.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zgisyyhe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeqezjn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ommnobki.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaswonin.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atdtyatd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuytbos.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejizkbdj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrrpzya.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2elvcvxaa.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdoymuu.html


<!-- 参考信息 -->