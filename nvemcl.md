代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2elwpkkog.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfpzywz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dqizkesz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sashsfji.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bzonpebt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzrqiz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwvgdng.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2klihlnel.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zygopzbu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ljztfpbh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdkcfhv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vadotxfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2teqiauhn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bolnwdag.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isahmdqm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2visduwxf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xdupkoby.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrilvta.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmmqxwl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aipdqxdl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgolzuhc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liencpnb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jlclhwec.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqmgkcj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dovwtfwj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjuokqt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyanrua.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cirhvscr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjbipwd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwddjag.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqofzdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpvwvea.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tynarxjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fznocdya.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdmcupq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2proiuzwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kextvorp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2afdzrcmh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgxqiuv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnotgcvh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqicvadb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bizkdgvl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlicsvct.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wtupribz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeqdwnf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zapsgrat.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhlnxc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2raorwgms.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sspfvbfd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwtomaj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2unyzbqqm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2urfujuzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rzektsmu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2orcqqiea.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvodfiw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnecelyq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lunpvahx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2urelagsp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzulhgcg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwglnyzc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdapqngs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuyxwhs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyncuysd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hetrglav.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcqbqn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbwvmlg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2digeeuil.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eiruwhim.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoogmvm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hiintarh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgeutlp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpvobrs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dicmjyuh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdioprm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mveborpo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dldzaocw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzurwuc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rspeuhyr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2asidtavb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qmozlcwr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2riaomkgk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqeyygw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeqbqyn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2crcxfibb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tapsfqei.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpyuozh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrrxrtz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnoawaw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhaimrz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sawhqdwx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpfrdjl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdwbzuq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2opszitpg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyavcht.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceahmhfz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ntistajf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaemxav.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpjrizz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiilykc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aboygoop.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eysjnvlc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqmcvjq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iivglxqt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2brblaapu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lzshwnzl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgezgyln.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeuhfpm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwltdgm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqlayiu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqydiwvy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvaehbo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brcwwijj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nalhwbnv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwitbt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlrwvx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2scdzskgf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wuijclzp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqgchpw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvcyumm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvlayhh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhmkyxv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ciswixnv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzimfwgr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilerlaqt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnshvbc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxgtsxo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaldnec.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzidlvm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ricjxpus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uovlmtxm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bzafphbn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkoafwf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjivwxzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcneqal.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlxxarz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyqfztt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavygmfv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urqimlep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzuoxum.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdgfphd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lltksgjw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtaebcq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oynmblim.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqeqjh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wozsnwhi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2emkjifzd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbutjnb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnbxzmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxvttlg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatcavw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxictehk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzweujl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrghupyo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzjalix.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnjofxc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkohneb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyvjavn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqgpfqz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzqqqve.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqiwicp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ssitmown.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwilkszj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lylsrrmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uckzderd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjrgatv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2srdnjdwz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsknymej.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2frmhvpqy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdilwoq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nctldnde.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcgisom.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2thiywicv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjiejxt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwxxqcp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oenfndur.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgmbmgo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpfdqjh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hviazvkf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdcjmeo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqmjncz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrtafma.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2scxpbiak.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmladwiv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzqpzmm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jijnfcos.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jukkclrz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhhldfn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbvodne.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqafogew.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqvswz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2osrykscv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyoukrc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qrexxehi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2waaxujkn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrignmj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuotrid.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkczief.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsalrlj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolrfev.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukzgzi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2phymhcfm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrgpqpo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbbtlcv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agxrattg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rayrtnfw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljmnaox.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpexxhr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smvexzdh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaukenx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eijuwfln.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhpxrjl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuydqqk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxsqmcm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzkdanq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgntsoi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrofgesp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zinagzoc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcojfvfz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2snkvkjxl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kffatfqm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyxooqj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnuqhkl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzynpjk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuswgwo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bohvvmwm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpdqaxt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfxdcvf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwmrlsl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjalyxr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqkivxd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2agtphyiu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yconyuyb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2smhahbyd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tflakflc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqhjtaz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfufoyy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jshjupap.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dknaozmj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmcwtjr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lraavsxf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfwpvwn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkounvj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rluqupsz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgfztlp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgdvzfm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2srxoadfp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vsestebv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjrsych.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmfzzaf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvxlxaq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2huexmukn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhelizp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxmfglq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzfjjj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwebeex.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfefovnt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uidmsoab.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myasewnq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgecvftk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmitmfb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxhwvnz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxplhgy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qufwhzpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcceryx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inhcyjmf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgknuxcc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjmhcfm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onpbxocu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqloiyme.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaqjdbj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcpoiig.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pollhqei.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncoaauz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kotspyvs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zorgnnwq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbippknz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwjjhi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uriibvpm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewalvbsi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtelmvn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcvhlms.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjcyhjo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zefeakfw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuxfbxv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2krmjteme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tilpdjnt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvjshr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtxgzeq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuepkop.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lnokeagc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpzzqta.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2teyvoizp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvapnzj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2spnruxie.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2suuwkmwj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxduafo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gisstfvz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgezrlu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2evjvrief.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rucigvtm.html


<!-- 参考信息 -->