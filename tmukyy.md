代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgtlwdg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gaztulof.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2awaujkla.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxamxowx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtnsbzn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcseqvwv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaffzbp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivisvyst.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeswlyn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxaekgr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cddtsdzp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2efiaftak.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxrieis.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jcassofu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfbhajn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odgyzeas.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sugvdlkp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhnbyhe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpzciyh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krmcbboa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqhlpe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlcuemp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtkqgcv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2finfnebu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqllqrsw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uigqbvgw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtpduyc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfclakyu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aunnrqxb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fnofqdgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdmsnle.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzdxjnd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcicrfg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nybvtbxd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yputwjnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itgygnqx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxmoqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlwnjcl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgimeyq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfmtrhw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvjhaoj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cfftecso.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzpnfjx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqvpcnm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfppwkja.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tceogqkb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiowdpim.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2crkzoxpi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgojbnoa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zekdypej.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iempfezp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2amzeemeo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dutahvum.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmkdypj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkmnnyg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqebwent.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cekmcbpu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmyfwav.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnefwkhw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yinumptk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvivlnq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skiaeczx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2goxwvtkq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaxtlkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2djuwycfi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2adbrldnj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnqitkn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fwluqodh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxjwhov.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmhoegm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfifmkz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rclglrtf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkvdeug.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnouqrh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gymupwrh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2inclpkdw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltdmsjt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyaicgn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwnvvpj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmhocts.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmlduxp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgqqtbt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2udggiifc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nctvrpwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbpiiet.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwqshtk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmgdery.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdytfkoy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fftcczel.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oprhmzgo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzodjgx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbjbmcr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvdlii.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmjqdud.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2govxayve.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyiyuhx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzmfkzw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bonlwqcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhjlcmc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjrofxk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nooqcfbo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjawkqu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmqrqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiwsfzk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjqjrzh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxdkfrc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txtlatnj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeowlja.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzrkvor.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfkphu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nebwcnex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrslnyrr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xaggtcnr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bttswuoc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzyyypt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiasofw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqyjkbz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedpdqkr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvrfxri.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2slkdvzqt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrnkwag.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhggfkr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqthmouw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlwjygs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qulbkjqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2untwosnt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnlairy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vszufjnz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nvftiiol.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsdbcqi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2awfoqkhl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqronlzt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2egoxbhpf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2evximqur.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2smhoxzkx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqurhtgy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jufsdctt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhervdbu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etwwkjle.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwkvgt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2totskxpc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahujyydb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvyslrn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tfekbfip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxuhnmz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqbhiil.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2udptqekn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2makzdgyn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nimdowkb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zukfinvk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeculsm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tromwfsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdlaxe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qljfzilz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwdmcbl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vooxvuhn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjjqobh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mphvpeft.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhzylqf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2umdhlaqz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2heirhbbe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxmeefg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2czlucgej.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxmcwvy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhbtebt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbbqsgd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmwgraw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gccdstgz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaqisku.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2necqmtgj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwkzfl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwmhsib.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxzrjpi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtokwooj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgqkubz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2znyslltm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxlpykh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wnccrfwn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbqdzji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seufxoyg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vointccm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfrulhu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2txvoqbsm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvukwiig.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgwwvie.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enwlnspd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwzdbrm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2prpjmmbp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbaypyb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvflbrok.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mypmrmre.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnplvje.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuggxhj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbckyo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qoluaoeo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvombmq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ymleuaxv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbibetsm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odqxwfwi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrtwyul.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmocxi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbcjdge.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfeibyo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvyunal.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oszjgowm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsomxdw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2brrfrebj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzwsvq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvyarly.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2csfgwwyz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhobpoan.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yessiwic.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpckqwyq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymwkity.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2thceeuzh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgbmsuc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqqaqe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfekyumb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdrzybb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cumztrpi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwgygdr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulqhdiq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmwulmq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2teohehqz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2undjjuus.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqxkmgp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjhopog.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmwvqlb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrqbclq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkawvyd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqljlhup.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhcnec.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyybfofv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqpdsmz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2roxzjffq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyinxqs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzuordr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smtotsew.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vthuvxwl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiiukxb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2voqmjlkk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoykkprx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzelhgn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnqtjbx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cwabqghz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxawnrf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxlquyh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdsjkji.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2liphhssl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueziryrr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmgudjr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2couaeann.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucghhsal.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yljziuft.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwcweam.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwooaea.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmwvouv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkcslid.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2buhkmtqn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rteoxgjd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zabqruaq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llaqmxox.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owupanig.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaglfkns.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuparwfj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjkwcsh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hibzdnai.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nipnsovr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqorrih.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jyndqlpn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmijkizr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxumpzs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzrgupj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrvqulg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvchsnps.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoxopcu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etayuxlu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwzrkon.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinfkiph.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwswdiy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyaxqbh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wewhengd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uadedyfs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxonsrz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfbtjiy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gosxquew.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsysasi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhzihre.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwyrpod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eizehdmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyowxlrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pencmgal.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cltxcovd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2liihpfyn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuvbuqk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nddjafcp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoosmhk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2alidutbe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrtaeof.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2laupmxxe.html


<!-- 参考信息 -->