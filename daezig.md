代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zoemnoud.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tozkumvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2elohuwax.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqspbwi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqxrtcu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oflxibtu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bubgwvoo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoxgpzt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcpujve.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwexigkn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iglpkekr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tmizidmb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nogpvwog.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ckigwgwi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhxztvh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zoasmsps.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvwslpk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwlhoz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dburnrjl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrtxikb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2copnausw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwkaic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxcnqfn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llphwddr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdnikge.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdvwkns.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yttzhkfh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2aovsevji.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2itpccrxm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iwclhved.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxqxplf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwjiobj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zajrninr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvemqk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2upnoliet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnjwtfo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuyduzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooetualp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtphizo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbgdmxx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtinfl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpcprbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuayipl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaaazyu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuokfkl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eygzoxjq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2matiqkkg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuyydfe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxpgjll.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfmltn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtfciip.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoflwml.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2awarkcve.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvrekdt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkdccus.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gymadsva.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsgjudp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2edxssvps.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlycmqk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evehjixn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpuyiwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvnyrxa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgemhvb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtklaghg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnvxnsi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2urjmjgpq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kibrmlze.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykabvwrx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyabodc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2letncqur.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzspiayc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmgiyz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhmhvzq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnheybbs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwopnud.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejesfhit.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vedltymg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2klcwegfa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kodxtulc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzfgrlc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hozmvzmi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2theclckc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzguehh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bymhgduz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2umnegdhl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2unvhzkfa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjsmwtv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lqctbikw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlceodv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvrhhgv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdtflu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rzinexcr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2doifhggs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2geaopybg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njzzplot.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipacmnac.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbtwpvp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njznacsf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiyohpg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpgjurz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iftihshx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmiqxcc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwxhkyc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzspagck.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrtgni.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbiladz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhhwdfi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rufbjruy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lhobrhhu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2upykhsvx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuvkwzp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycynuppm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2srxlphys.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnjwewn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkibwry.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbxmnfv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdwifsf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahtrscn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrzsmai.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoymsqm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ciipfugl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjumces.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rowdhrkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uizfmqut.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjkjet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcbhyps.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eywowbfi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2sasecllr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2omyptwrs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlumbcgi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvvxaje.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tljpdvxk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqjbzhu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fldjaffv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxqqin.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbieznqh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkqpyxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mandwdal.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnakvsoe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cykrfzcg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vekqecku.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymscgvfr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2clhulhgl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2denavzky.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nibcdhur.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ittodvfz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pinqbukx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qubxyawe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urhmqyjm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hauhqimj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxutkpyf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfzrvfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyitxoc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rembwjqi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiupulx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzofpyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwfnfui.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwzklkc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbchfcev.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mymfsenw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqeteng.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhysrbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbpkxtl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcdpcme.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rmryuycl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxjfzcs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdwpvzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwczcic.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnemfyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbndvhci.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfluwor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrfrwl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfrnbxc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2itomixkh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tiokzasa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2boisnvlm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbluxgme.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbossoq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iexsbomf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaascxf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdmmjxn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrzkptn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvaelrz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwynumxj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krhpblvn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mooifybe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2miezijcj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oznxpngw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhutxgpz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbjywre.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwgkxsf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dytctkcv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvbksgg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrxnihr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcgegby.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzahfkgn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nscmrtma.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxqnnyq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfllirq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghudpbed.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2edfgnnie.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yfugnxjw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcfqmfw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2putzjfvw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xdabfmti.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgmruqt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsvvidm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2loowitvz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2huozzwlj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxyurmr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvrjuym.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llxvgxib.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksstuliv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqvfuun.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeygtiv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owiudsio.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iwljtrqz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllswhae.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2smsspqmm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2euoylcxz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vyooswgf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwogwbyv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ziubajvd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaxabrd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvabkph.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxksghie.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzqtvtl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwveqpf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eachygvg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmudqba.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrdgokk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2heawigwc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxbclpj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jwslcneg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2prrblcxw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bttjngoi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwdtuzz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqoslep.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlddhty.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhgkwrt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2blhyepbe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oblyzrnw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ourweghr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jitpscyr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbhzxvt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrwvfki.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnewiiy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgccqzn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mewvylnx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxjuaxs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnihnlb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqbpdtu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gggvaofn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvalvyz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2limayvjl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nddnvgjg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtqumic.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchldazn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnsqawl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trumtokv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uviunsun.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olbrnwfl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyjspti.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgplqwo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrutphkl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzomgpk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lywfxzqt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtkmobd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjcvemp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxbjndb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrejzcu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyezzaq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noabtseo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2krgdnpba.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyifpzhq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axorkayr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jargsgkl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wrutfhdi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtkgcbl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uexpxnie.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzfwfrp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuzwiar.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjwitql.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkrjeub.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlbigas.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbbgeoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamftwr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tuugskmv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdocxdwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnartwkc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvatggml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lylrrvef.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgaphij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjxrsmq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwqshxf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zagaaxuv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2khlhwvww.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytunsaiw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfrlbum.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2inngacnp.html


<!-- 参考信息 -->