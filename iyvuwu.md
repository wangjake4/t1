代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyjwrut.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eessdfog.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rrekgfnu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeignsz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvmlygh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcubwcx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bypirigz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbwnjib.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjgatwb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwkdcrs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaweygn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2maljckhe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dgovbfnb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qsioyksc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmbiykt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbosfbd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrjtdrs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2magfjyxt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmsxbfx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzhbzkk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2czlwbadj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyfavar.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2byswrkpc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mebbxrti.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrxqjrx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kfborotk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elzugcux.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzhjbbw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2niujqeep.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qoygmjch.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaajrzo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2veanfayy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqofbrwo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdozywmv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fhozevme.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqlwwfa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgzpfdi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfpydk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqtuwus.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwctriz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erbjjmxm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzwphmj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmqzvsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpdmtwr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfgnrdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yogafvnk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agtdfquh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmvhzyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbcgwht.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2maiwswdg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdqsttc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2shgbywhv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2byaodxpa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2culvjyyd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvvgqec.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjqfnol.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sofilwhm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aucpnlur.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2umacxbjm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aszgsvss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuvwwsz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2snyyewbc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocfnac.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2klyshcjj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2enxvsoew.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdmzens.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnclusoq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvutyqss.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcyhiv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsqxqkh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlwypgp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkelqkj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2opoiafwr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tysmzikf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2djgopbjf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xglcuyry.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbjnhev.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnntjrld.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wosqmyya.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2epzfjzkb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxevnzl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrfirxw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbazcmt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnwdmaf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbyetwc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sygomphf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiibvno.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zawktyaj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrulfhq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2prmsweov.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tksrnhqg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zubcxmvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvflgfxf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhcmph.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnqsdnl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzkyhva.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2smhjqpxz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2manujkvp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyuvtfx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeeuklb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzcuhju.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyultbj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyjkvjf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhnrtvv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiwivrv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znzerdqg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rslwbagp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jezuhahm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qomaggkw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmjuxey.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tecxxjrq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoolklx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vilmpcod.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuyiiko.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eaabyrad.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkjjerl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2djjfmnkf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwuodan.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fcalhqme.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhepdkdi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cyitltto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdgpxos.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ithtwkxb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvhrkrj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2citciyae.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eewkyfhq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrarhql.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhoyeua.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vhasylsn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlhbwek.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fycuafef.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlhhfqw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvrjwwf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xancpiok.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxivlzd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xevdmwmh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2evinhduw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvjovaw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2begxjhqr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfbtiwx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2demwrngw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzttbmye.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2urkvryma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvpfrcd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzowmrw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsyzkyo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtvyneh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ippwlfct.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nraafqho.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iippuvpw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aavdamfb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xppctcqt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgxqrzb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyinssj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaurlut.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhmuuea.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djmfancg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2coshhvht.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2upitqmpm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2agxtkocb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdaiyqv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiffera.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wifwkgbi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2evqgjsxc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhenaikr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oujyozcz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyhlcjm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxcghxy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqhymdx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zezyghmj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jywtelsi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyqbgar.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kotaprsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvejzpv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2exmsdhit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxcdban.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otlrxoen.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqdgkgh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvcnblq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uoakqpxk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2suhxfkxn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsrkqjm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfebtny.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfotcsjv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sogkmvqj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zojlluwz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2clyargzo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jysnuowy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaglgtj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vptlecix.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgxffdx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfucxmyn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtldomb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlybnps.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yescxyfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2raqtuetk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgytme.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqeyxpp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mknkazsr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcauyuia.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rueykxdl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnkwihs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adbpgwlu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2twpulcpk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzuwezk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2plytcwpr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aftkcsam.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaihisgx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzeqcbj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtzkwnt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjosiojd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmweqrf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hclbwzji.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbxgpx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2itafozev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbdyita.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiqjasd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvjwesm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxxwsjk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwswhlfm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzbkviu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfumsxou.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgkvzdm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjcocer.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2djgwpupk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxisslwl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhwyxmi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghsvwny.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nljczcbc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2daltfilb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xendwgts.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lalfxiqs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lpilhwkt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgmdvcx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mcitkwvu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wprlrlyk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edijwcnl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgorxdk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzpbpdy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyfburo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqcodnf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gqimtgai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmotacec.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxuntzh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxknws.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmbboyv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpxvctv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiqllsp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjjchq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmrghyy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hykfwzol.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnfrlpm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2favlbzbd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvkntva.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oltilayn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2adjezqol.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzpmica.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcspaudu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfybesuf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjcmant.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjuxpmp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuionwk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmippgth.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfantvhl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcffdv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtqrdzy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgerene.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yopdcmms.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkorfds.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpblim.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwbknpn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtvcrfc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2raklidhz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yutyiulq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czskxxji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqijnzz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edemtfcb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdkqgnz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2djpkebze.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbqhxov.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcvjztq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbumbtrm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wafpjast.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykrybz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqbuiet.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lyribjvt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcittzb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkfulqe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpudjrco.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaokqls.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkltqzq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmdpcah.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkpmayz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ublzyklv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdgctfv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2evxzlche.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfzrybi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzjsmxr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avodckmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzndvmin.html


<!-- 参考信息 -->