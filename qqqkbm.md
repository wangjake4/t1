代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2czgnbxnn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnizjwas.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrtuxd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jixmcwhw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bakxdzlx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxeixls.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvxbldk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvjowzj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiuwiim.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehjpid.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zakoglza.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2irwzdrsy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wjebapkv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2weeegwop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbfjjo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2trflifob.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2krrrghun.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopbeiz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cxilgouz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2amsantce.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rshnwxyg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2foazancz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxdsody.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2weneaspi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmytlum.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzjhqie.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhmrnnh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2toegjiuh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bacehdph.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvrhhfg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwqhgwg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2smtnypou.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfdkjik.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2arhxqxhl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2damfubqd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gapyhimy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ettcctvn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urdfdtuf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuywljw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kavaivxf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxopcws.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nssdguaj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svkzxtlx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwlqlw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcnhdyq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmbcvp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kofjwifh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdesmfb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2epxjltte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmajlnpi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqfrxzj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zekcldzk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iblfwglv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwwvopz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkwgxdu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgieukd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcrkdsq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2stpzimxe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlszvdci.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2woimswjr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxtwuhq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lefqzzzv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwwmpcx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2adbwkyrd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfunowpo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuqlvor.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfkweiu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwndokd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcsxcez.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmgxlls.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywsyemb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkktsmob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrsvzcw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtgwhbw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzemkhh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emdkrcok.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqvhlqj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vamhjpfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxdixhd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvvbwjd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhumpsi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aozutxbt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aimemosj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuobgxb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2inatrmvv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acsyhyxn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmsrxdo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jchsvhqy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2chlltanh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pptpimkx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dunlgatj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrxncyx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2klubntfc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scdbyjns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndttvoxc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2snsildpe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mddrjuad.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcczmxo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiubphg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrggbjs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ongwldem.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwnxfek.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdheldz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kruhqbku.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeuyumd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqghlay.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcslhkz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrenqwx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhrnuyx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnavjuia.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmydiubt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqcfsnf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmahjr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2swrdosvd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpyctfn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swifiryi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpsvwiy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmdqaeo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpvahcy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxedwcsj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aosauhlw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzcwdcp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iwznjnjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyrhvfx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lasglzlr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiefdoa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzmkiqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iotzwedp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2puzlhbri.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiedazb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpqgejf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iydrzlqq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmrlhhu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgpesnd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhzbrmm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owqadlts.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bztppyae.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdykcun.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kevyzurt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmnowsq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbryakq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpupcdm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvfmidi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhifto.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2imetkyoe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrgztga.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqhgmpb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cttgmxjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxiqrdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvryqrzp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyylvquq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgypga.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2czimukiq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blxdbmga.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2smoqiksi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yxremtxr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fohujdul.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlnsbhc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2omdexdux.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzfofjr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxsmudj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvppskud.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ninegite.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiilsog.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmscsrf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdvhjdh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwafjg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfrpmvs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyozjcg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwjdzgb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuieejyo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zypxwjka.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdyxtjd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ncghcihx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvaqrdw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jypdiqsa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uevdjofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjsiswb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktptiezh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mputonsx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbnbtsx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zijcbtbc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxqqkgl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jopoxmnd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cptvxvam.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlfxner.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpnkldl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvapde.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtvctez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2opvqyugu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtoocfn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhimhpg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wojqqsmf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotkdcra.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbxbmvu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkoeott.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upubheex.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2afscrall.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjrrbum.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwyszjp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzyhwwv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2unoitywv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ccckqdrc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkvsbx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jryzrhxp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okgmxlly.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2niyxqrxk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwtwzne.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2udcekaku.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tikdytoi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoizwty.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrivybf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlmyxsi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaaggtu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkbsnve.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlunizrq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oygpoett.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfejtkth.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fvavmloa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkuuiwo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xybohjkq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyvnmba.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqnfrrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eiotvwza.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvcuqt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxwjdpp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xtykhanu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tceuehxx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2icchcrcg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbnkptw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrjbjmg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsffwvf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtloxth.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdodfnj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ouluszse.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2msistbfn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgadxbja.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoxenmv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqxxuyq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixerxmmz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaluqxu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rihoensi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gymfmerg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfhunqb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dabiaxnl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgsslpg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzozbhl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2azhtwfzd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zprjsvah.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaizvqm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkrqfue.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjspor.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sapqahvu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnytwted.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaopecxa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ciizcesa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzukivy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmildey.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqvvlou.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoaufnn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cebuftrr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfhugct.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adahqveq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2azbkdgmg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnwizxa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqsywen.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tawypgkk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinxqiff.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfpczoe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxffjhr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hiylkdol.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eczuliai.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2axptnlgl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwbplxb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etimeotn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2omyvkadx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivftncfx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwawtamu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffecdyqj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpocjdy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtufgtgg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lgajdtsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnjtvsh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyumyhjo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqtpybj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qowoelmv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxwirs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sddlaojm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpwzccf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbrseut.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhtjzuc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikokgzag.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2clswuhne.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btpnoywl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpzvtaj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimrfto.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnvmfjo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwxfufl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsuehkd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2muewfjff.html


<!-- 参考信息 -->