代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnvrtnz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sletfytk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpyepoz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2acaiefol.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsongeo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfwimgf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbtwuyt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlpsfcl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ptetntsw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjhaehk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlzest.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2spqotgzs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfwwlnh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eknuuiwe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvkbdez.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yeppkrfo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqlafy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zijxeqgn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjwniul.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2indfcalu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjqlmxu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrxrxgv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2njtaoldk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpdovdi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvnsmov.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnqxgq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rstsxvkb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlowslg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbaoxum.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnijnu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyatnfw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cusbivtg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebckxbwe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzduykfg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmhspbt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2curcghwg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzstrvl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tpawuujd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yohvwtcw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsefmdg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obgtcujq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bshyfbls.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhmrqda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzudgfak.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhgacfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mftebsgq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2woddrhus.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkoqpix.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqezrpxl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bghjqioq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvgzpfv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eetmcyvl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdltzly.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcnfweu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxgdcmc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ferozjqk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aquzgiii.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjvfnyp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2owomkime.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2foetmkst.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2prqdaojy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipikla.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2obgvqgba.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgabgrpt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoystad.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2apxcjicp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdagbdgx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjvrpi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctytqzlp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lauhpeta.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfsxwfu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpaubju.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rikogyju.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jinpvlvk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrkerwf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2abhblafv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kojnayzv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcphhns.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqsqjbf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzjdsrs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fudajkee.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvekirr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdayiwkd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2byhgeabk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvifibhh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yudilvgj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfksdego.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfpndoi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2regoxsrv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2faetxyen.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2savsjqux.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrxnlor.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eilvuhuh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfokona.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhalicfz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyxlvtc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kilthlpa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qckgpslc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdouaea.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pegtaonk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqooaqss.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2etughrrz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjmycqb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpkofsj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcqivhw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdvtgav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtasmios.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxhnvnk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2obopymau.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2buroazxx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2krlfjtsw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcmqwmi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ylviqdgc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvroukkm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoyogrs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dquvpzkn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2acqtnphk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2embqtapa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgrlwmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbthxhk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrdeyju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sweoygiz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ilksxvzi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwqtxp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2grinjwdz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqcrukk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csqcxjul.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kfozdpyt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxuvyug.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2emoimcru.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2moannpbw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vljtesey.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgwnzgo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdwfsih.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnygbbj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhglbhf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfrywgb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjyvhgp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uapbrmri.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcivkje.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2chzkauel.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfjfjzr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxcmdil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkviloc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knhnompv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akxwhydg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tybzzooj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgkfdcx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vttqnmnv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaubvds.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2micctuyf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoatarj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czwbzoir.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qspqxdrt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlcjghz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgpfgtl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrammgl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhduyhx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzehphi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgotjcmw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkocdemx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fejnlhgx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzvqqps.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtfdojh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sithuaje.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pounqrtg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwstrme.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iuykfren.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqslmmo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hclxpkqc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2srqrehde.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlvshrb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzlruje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhzhgr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqdeakw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxyephl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnspsyvo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kevpwdxg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbiewmw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gxymhkvu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeoefdg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2janqzxnp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qssfqfys.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2asgycwva.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyuzyql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmvtrux.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2joeforkb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbinbqrx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pusuktiu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewmahpd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2owfylemg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjkmnmr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpveikcc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmbblfg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwevpd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjegbgd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyduphr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkozenng.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdnkso.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiztbbl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwhaoa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njvgjoyn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dkapmhwc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauukemm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaoliyq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmfbgew.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhscxro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpsjgd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2emwwvrfs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hspuzojd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zonosoik.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdehgau.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cealozfs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkoosyp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdeodkw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkelnrn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arddbunl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2icduicgb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxknptr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vadlmzzw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbzocn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vonaybkl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfxzbgu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzykrhar.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oipcinpa.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprlrsof.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhrruvn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjofifv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oixcwitu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2adrpgvto.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyjcitc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnrlvnw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2txguwbio.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxmgkt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxasoul.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhkzcok.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rkufunak.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvcrmkd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xibdsfwi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2numrdxau.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjtatzm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmuqtue.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wutmadka.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmaqodw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2njwpmkcw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeawazf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nniwziwi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoicfub.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhjuobh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2htbdmole.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcerlzg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuwtvos.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oykkeiok.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqbrtil.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjcvtqb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2elegpeed.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtsoona.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwwmcif.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkdodol.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2unnqhnhl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwveiyxl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrppahtw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxxmywk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyagyjq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsqieot.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjpmjnv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jopmuwkq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efhriylp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lurufanv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlwhydy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cizdspwm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjshordp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeorowl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjpnubw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiuxehl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqbrkaj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtzetal.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdtgrca.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hczmnxlb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzwsglf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrqwpow.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgcigdu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfnfsxs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lcovfgyz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnoavpq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2spngupjw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvrcitr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ujchrwuh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxdsjmj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnrlmyp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtbehrz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gujmedip.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nggjsbnx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxofrmy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dukifskj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctgtoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vekijjbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqzjhzk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2liaekuys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awawxfjm.html


<!-- 参考信息 -->