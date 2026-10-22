代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zixxzyve.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuwdjxy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsnwhpr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlurqjei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uadvbrgx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwlbrix.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqbelfk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vapulioa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2suauyhfz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2relaixkd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqrrjuj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrxwdvt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2agftbnre.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xreekidx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgtofyo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2holxcjea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2abbuhekc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvjpejn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvwlnuh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mwosndln.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aufvbwat.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeisxik.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhojlrjx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egnszlvr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxhcrbz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzjrmg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uckhtlva.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfnzcur.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2irzilbps.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2freumapy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frmzlesj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmnsxya.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkklzwh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2acwspglf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tldmcwju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnwjovn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mydkznnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lybgfhck.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyjnxb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wmihrcar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpxdemv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnzxhbr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpgkeey.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbjkrhj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlhhzsm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2avkymirg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hobzsefe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rayrykwn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyguolfb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2leuhauqb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpulenz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2inqqlfxu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2twawtpqr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jsipxiwt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfaoluy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogufltif.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ojspdsha.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vibrirqg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygxppck.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwydwhnp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjqjzqb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqkfqep.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxnnbta.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeqtfix.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrkdwna.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdobgaa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nduwjzcl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxfgtxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2abgtmcyo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qghjfwzb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlkfjfp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhkywgz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2euypakpc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrzddex.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2muslours.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzittetw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfgvnev.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwvbty.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxdlkmy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eamsfpuo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqcccy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fntoacui.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsexozvk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfyayyy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkauiebg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjfryom.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvcayhe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdlvcrg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iplflgqz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2exdkzkoo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pznnypnl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2taogkmba.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeichfwi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmtdgcu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgsotwc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iziyvtgn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pilroylw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvniwgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdsztyw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lurbyknc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwenovw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qazbsrvd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqrtua.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwrvxpl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzjorts.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxbsqsb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plvwawgc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2edenvgyy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhlibio.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ustdruga.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfsuxdk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeszrmry.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfkuicv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlycgqz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yylbyoxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdoppuo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uuctsdnr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ralyzqfd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqmzzqa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2evfnwkao.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxhwfce.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnisflq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrldqhi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzdkrki.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgngkub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bltjyyws.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqccvorw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnsdmfq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kvalcvpx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2navvxzaj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2efoxkefn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhnurrv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2etlfkzrm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhghdej.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmdbwde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnvpzxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awijjfyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxzhmd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudfnit.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrosnsl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2awutvaxm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlvooce.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmcuyik.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsnvqog.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeusups.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awxlkwlj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xvocgdyv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2evyhuseg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjbsuae.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2czsucjib.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhweewsw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyleryy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbigasci.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqkpgud.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfldpmpl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2glqkagmp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejuxkkf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmoacbg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurocwd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzpjsnf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrswoxnm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzyvhrc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2veoutirb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvrdir.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2girihzdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zecnpels.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwfxqth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iufpfwhs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tufpwmkb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgzwxhh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnxdfrv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyvqjhg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zbexbzxm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhjtygm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdgyclb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvyellm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zshtfquz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fezvltpo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhxbzud.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbplto.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rddxuzzp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jenfiycm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvmywhi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnspsep.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tleaaqtj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkedycab.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aopivtbq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmxnixu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqwzyxb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvogiid.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2liqpgptt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenhteq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltguketm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfaeia.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2athoolnw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdapcdo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2buaehvrj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdkhedi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjfacac.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmryyh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnwjxtv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjismhu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2drdusatd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpessuq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2evferpmp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsmnzrf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2plscksko.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvvjqxw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2avzkuecb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkqdwrl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfufazf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjbyft.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vloklhwr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfnddfa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhapybw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrzcovg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fagdomka.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2riehlfbm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tstfwiec.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpkqio.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vqobxtjt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krakbmam.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zghrkqcc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lliuoaqk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmbqxze.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzooth.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwowsfc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egymlthz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqtwkrx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfbtzga.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efnlgwbr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owgrquuq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bayojkgg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iergdqpk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2czhdcuvw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oabmvmtj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvnaiay.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pwanytzk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gttxpajy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2umwugvyw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuacttm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxlthpb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxtmszl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmamecrx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkpyyly.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdjryoe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsycfwz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgemlyzn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvufykk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwweyml.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rufygdih.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjfhpip.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpdukww.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzjapyo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqplffym.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfejwtz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pasnxcsp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hexzqnzr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqgysvl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilhfmxu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhmdyep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfurmfaj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jldwqxfq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsdizdg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwxeqvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgonpqo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtesmjol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrfotmr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgtwfmz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iodiqsph.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyroreso.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxvqutv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dftzhfda.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2soqtnbia.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2abpotcov.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jnippqdb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvfgyok.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbxocsx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zavmzfiu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kysrcceq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjocqvo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iccihwur.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtxnolg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmyhiek.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2onlcamlo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwzwnop.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavguylr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sireodsk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciybdces.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrjicop.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtldnopg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trhibsqp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gigrhthh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2msgjvuvz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dwceulaw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvmenmb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpfukuj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoooxau.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2heflboxo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnxkimi.html


<!-- 参考信息 -->