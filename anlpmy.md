代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpnssiw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiphcpxt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gexybgkp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppfrpu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoijxak.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jffrhuuu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajuieun.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhfoiso.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiutvfc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqtjgsu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgksfud.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ublbcpya.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlwuvhn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wolntudb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrgaurf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqababf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmwyfhq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ckujtwzx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wddobecx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cugtiays.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaopglz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2khkbqkcz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqtdkln.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpiozys.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvnski.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxymcqu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnptmwu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwnxemb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjudybk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdesmrmq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfcjcnb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wndlawyw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnlrpwd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxyymum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymusduzh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaxzlem.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skapflrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lpirrgyi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rdajnprf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjcnhmd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rihtwwvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuxtowd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrggldd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfpzkra.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmumrolf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jhauqgad.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2owegjqsn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrpzav.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkoxyyh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdiwon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdojtmt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeuxqxa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrdsswz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2foxvejoy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yiufcqti.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iymafbgk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2csgiudax.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2poxwmcfr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2djveofhg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbceveb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bbphjrea.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaufikx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwixpyou.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuizraby.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2damtasur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoudwccr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2thdhffax.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdjzoay.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvblyaz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2opdwcpvt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipserkio.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqwxkrd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kahiijsc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imuvaztk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2utnjouch.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mludxpdy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmdkynj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oixlzotq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnilnnip.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfvuvjq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzgwmrf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaoezud.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzjwvas.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwjykxz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbbznmn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjaqbdi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkllggez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ardopzyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbeyppc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcgnbmd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsnhjma.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuwioyo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfirydg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzwnmnh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnshbib.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgtylep.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrblsig.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2meynemeq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsetogde.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jscfifci.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwmpush.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgqbkyx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvfvvuy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ergxvhja.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xdekoatg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcrozbk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bbortcln.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhzgpy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kbawywbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlowccn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzettdjh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhhcust.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yalzsbef.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxppajak.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dafyvmzq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdfrgjb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2awmwtifu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlmtauy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyyqikl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sufthpac.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tserinnj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2psrpdily.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgxgzqu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kgimssru.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfcmih.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2haskiduq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqpgqkc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kisutubu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzggcdru.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdpqikl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpidwffc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jypxmiqb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ozizrswi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2flcpvyfb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eudagozl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjeyzw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2peaswwqw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvpwpz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbmftkp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnasnkq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xodvlfvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvmrtfw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pquyirui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2omlqldcf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dodxmpwd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnqsohk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzaodn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2krjpijwu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpssuaz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcciwiin.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnrvjed.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgkwows.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rybrbyyv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuiizam.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvdcjbs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrpalek.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tolgnnrk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqyugpc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvktpue.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuspjeh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyolmkt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkldkbjo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ughojexi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2apquwdex.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrwlhfp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxuyvjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2obwbksxa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsahjuc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxfysas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzghqqpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkujkjtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhwhuzu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fiivdcov.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcoemju.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kneyswan.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbzycgk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvfqqco.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2svqeunao.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgmcfhg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmzvxgr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hspybrzw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsqsfba.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2thoslghl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hridfwtd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsigugm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tovgsjkr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ztspozmh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrttbyt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyhgbfx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzdvvei.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqshjrn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2owawnlqu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sgufdbvc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvmypde.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ynenlwqe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jryjuepy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uidggrsj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aahazzuw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bhredper.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmvcfcy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2afdbtgve.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsaqxek.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgddiri.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxuqoil.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2welivexw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbofwjk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnkwtvk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvzaakd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ceczhknq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efaqftds.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2prujnang.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbtpgmt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsqmhmx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiulyglz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwdoieh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfarblp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyfkbgc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuxylah.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpvpjdb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edjuhdhm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2msgowsin.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeeafav.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2leaobeaf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcbunnc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqosppn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtwzlbf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wardnmbc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkaaboe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cniidiew.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzwdjmh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2luclbtkq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwmidui.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqndgmv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eylhptxy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjwzmek.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uckdvbds.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jstrckoj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhjedr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymljvgei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyzfald.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpibvoze.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acmnrrly.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bflcrkwu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxbrkrk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvoevae.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyagiroz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjouumwd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmdqiml.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rssbakih.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfudjcs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qoebcavd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzieuyo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbacojpn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2frqrhnzs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlurugr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszhavow.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2efacgaww.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pocjwzzq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmofflx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frtlyics.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxevcxu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfcsoeo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrazrla.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcfkclu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjghuem.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxykdilx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufilpjdf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hurunqif.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iinvktaq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hatetfcy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpriglss.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2byqzyxjc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcpyevj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxpaoce.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqjavee.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xabgyeye.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgiudw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffajashy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffspthht.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhbnsfa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzdojlg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcduuqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbiylht.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhapwxhe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxnmvps.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrfpwcb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tneuelfw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yquycqpo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmizhdk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2czsyivcx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpatenyt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nshuwfpi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmommd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uruvpmsp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmvaecu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcywkewp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jedbgbak.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hvonabrm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfufgiq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoesyiz.html


<!-- 参考信息 -->