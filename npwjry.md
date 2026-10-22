代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2damwkohw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2donzpvcg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2blbvwxay.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2crhcicik.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsgrxko.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhastqg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pccqbqzu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iotvrcyr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2trdkspka.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwldueg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphuxlkj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2spvknljj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uklfvnuz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwruomua.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunvzpe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2idtnmprq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ceegcmxp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtyubpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbdbfaw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhinjpah.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bauuxmlb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2apsqncxt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjmgqnw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2waackcxg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtdmfbi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jujbdsgi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pafqcklh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olrnptkw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpwjqql.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2btdjstpl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woiwhonu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlclngg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxrrxga.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvnoce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzvcaxi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwnlfec.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyefrlu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjrovvo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imquyeun.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2squoawsd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdnzmwy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2orjnance.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiibqyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keiozllq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jswgaiax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjgvbyd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2camnbibi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nisnslse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdazxruj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2twtgtoqy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuztann.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fobjncyi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xajddamx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2grbqheou.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2egmbakbq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2foblggcu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcfptym.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrofgfkx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxiwfll.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yilaalum.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2atpmwwht.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgfceov.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfqycgm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfhzcqv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nzynsgpf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aznpjier.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2duejyqhl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdppsjyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2idetwzhf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhtrikw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgmhgyd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzodugsk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiueaqor.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2knkybijo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyecgguc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzyvtdn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nugdqfkw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2unybolpq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kyackrpl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mujmelzx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkxdlia.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuvfgdi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemqacyh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaabsyj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxxskxz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qptezyib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdmjavb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zlictnlg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eolslfvq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2unbakfvz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnprxdvu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwlomjt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazppoeu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpficfv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulrpsa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2olcnawza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhoamz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzueksa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2erpedumz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwmfztv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnopwkm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtmsnuc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2norbwzxa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ileypstt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbcfajo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mavdyugd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrylxju.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2stfafald.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iksbhbbn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwghwra.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qpffjyds.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdryxos.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2muhesrcx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkcinrp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhmryum.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2okxkhaut.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lofccdle.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zelqpnqm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmtxiol.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcuuopb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjnowqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmygcge.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrntpvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2viklrlll.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxfole.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltabsdqv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2donnlgxl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzmoeb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpecnnb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mezedsne.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wunklwse.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpznwxaa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkcvypu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aztvlvws.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwadzyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzobjkbr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lpydqqts.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhgfybl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzizoc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrisuvp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sqohhtct.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfsdona.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2begphyqb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjkdptn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqpfyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdezexqx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xukecvyc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2anewrhtb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmuoinz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kycrdufh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2alstrxrx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpfiheg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drzsysic.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cputrjqj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ybinxxmm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbdiroq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtazfhw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlmtbqo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gopjxbbl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bouaucxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2inrwqwnw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjigwbc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtfhyqi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuaposa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowhmklw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucggvrfk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrczugwx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2arstxtxs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvuawd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvqxcxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uamiofcb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwmoouk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyuowva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urjbxcen.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpsdmcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lliwaahp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnmjgxo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxeigg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2razkkksd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhekhht.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sevnraxa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2agzkgbcp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmssgq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmsyaxj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yzujguaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdbudkm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhrnxmm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuywrdam.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cywfarxp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckpibjh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwquutf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktautjki.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfxohld.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sceuewly.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmkenuy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ablbypuo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjzengv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2algzjpgg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnhziuy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjbfexm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjqcwyc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoyzhcs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrapsogx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyfvfvk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vicuilpu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpmxgso.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnekagx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ularhohj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2plajgbbv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzcefa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tllfawoz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwkgtim.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2otadvtcb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lucdvihu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2scqqhaep.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxbayfh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtypyety.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuxqczn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cykaslup.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdamezz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fousqofy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgmpjrx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyqvkfg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lullgyrl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhowfma.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaekzgh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqeasc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqefrm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etnhgizs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqifpic.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msmsoeqi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2umseuqgk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrkjshk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2czfomltn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzhdylz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2czdhsiio.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czgalmxi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mljsqjvt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mruvmdwk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwihwb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqkeehz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2atrxjcah.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2czymztts.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvwzgew.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvaxtvv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fibuymba.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zylvigwv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wizmyhqt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kabiyghv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpyssii.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ondoxvlb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvbcmlx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2scybngna.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlskjwbr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpfmhij.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pwagnlqs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iebbhwgm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrszyiz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgxlhfp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fksikzpq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpskrmxd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwcmtuf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uolslzvi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysktboqb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsvlfff.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efreebvq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjmvhji.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzwwnsb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2broqqcad.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnfjfot.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyfhiaj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwynyzer.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yahyuvvi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzslze.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdxjqng.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrikhlr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yivazxvv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ievhslfc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqwjsbm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slwjydvq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2poipxclq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvrvfw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmapuza.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkvbiwc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbtksgy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyimxbd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yamcjibb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2acnjnfkq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xncdifvd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cjknnzcd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbffnxey.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjzaefk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfzzrxf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gynrvzbn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkawreqm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzhkkxe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzdkeja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvlsjhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2miimnkwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclhlcl.html


<!-- 参考信息 -->