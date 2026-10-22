代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cplijnoe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiagaha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kmngbvtm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrusugzl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxicvas.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irlfthrt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaljjxx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhabuno.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2exwlelrs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iengapig.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2odurgtwt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gusymyce.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xdupmiaa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2curlhiju.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvwnaii.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iemqbngr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnknrki.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkgfqfh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdrkvsp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gavbdawr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvvhbll.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtkuctc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pufklpqv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umdnxhrb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tshfyxhf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dexwccfx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bynsweof.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jciaboxy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhldrtw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvzgsuu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdmcfpt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxubadsp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yusylbgf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyckxskq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2affugqky.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgtdfiv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pctytpur.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiwyvhm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yljxmzdg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2knyramhd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2axxikytj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hrysxxdg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkrrfzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmzersr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mankxohq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrswfjj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhzgdvw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqbvvc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bltyntct.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2muogubzm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrzydts.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpobqwqs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpipcvrb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sibnkzte.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsybhwc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wegoszxs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbszwcdk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jhewfhhi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmetvrf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mluuyevv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxpkxe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmnqmzm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2psukfxxe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdegouns.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtnuzcz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lhorhzio.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdhspkj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqngwmct.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhivusmi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvgyxuz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeyxfxj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhtharu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxvejiq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqmiyoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gstrugwk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2irqhmltn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jodjusog.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtnuslm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2adaptkae.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hsicjyrf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuqsibe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lozhrkxm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecziegto.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrdelar.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfofszx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkftqug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ermtrwxq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cryvoucd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dghucxql.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2plrrwgbr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tenizrip.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2twqtiamp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeenzoh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqjxvxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxabojyo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sadaipqg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmpwrqj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkjdrfs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2knuqztlv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2toghitnc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2anhztlcm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiekrypu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mearrevl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxmblww.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcqatht.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlctvck.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlapwyed.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2shlkcwyt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxuqolm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pzosjwxy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2diidnftj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdmekky.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xraduhak.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjaaerf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnxkdwe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbizlshy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvfdjjn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aywrfszr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ilidzpnz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itdskazw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaztmkt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiqnmyh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jseizdrn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trhvhpyf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jadqaarn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsipjovj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2najukqrp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eijokxgs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umjniyvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2avpdymxj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwikvqyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmpjmwr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llmxbkjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psdigjjh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoerljw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzblawl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuibsoh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2telcrkdv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nzygqxjy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvachktn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdspntt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkloyhii.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnuihvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gantjcrc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wpanfaij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztymgbf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyudvxxl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrvtdrd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwienhu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eudrnabu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkskxnz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jwijmeds.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtinnny.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdralzvw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqwrgqk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2modryytt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtskuux.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyszbik.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqyhzx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmddugx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyebcue.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2entsatdb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frszslnj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgdgmhd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnjxioa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdburveh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkmmwlp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmnlwee.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqjishc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xeybweyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2glznslkw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfaqhhu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jmubmksl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urlkxzor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwndpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exnztqbg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prpnjqkd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkmhukr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvzomqv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cppdzgba.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zifvwumx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2atslehdi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvhpbgb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpcwly.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afwxllsn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jdylnfdq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jenfztqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmfkflx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjeusuc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedpssyy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uaztfwpj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyeexcr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mggjuirk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eolzaara.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zasjaqxj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mietegkf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxfgzmn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctmkuvj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2flbdnehp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzliwcg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gosvkzvb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agexrwlr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlllocr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrllytm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcdulbh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtfwenv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsijbuk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyumrokd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjaled.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mauvozda.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbxduyc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qysuuhvb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oargizex.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2initghaf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idvkuktp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggfgsxq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xncsqbtz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tatdwdmy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaedtav.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzmjpwz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdptxiyb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtayqhfo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ckojiqiy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enhwoutn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2muiybnyg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfmearc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyuvcrn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqhodcf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjszaxr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtywyiz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sddxezpm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmzywnb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yuttyjhq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mteuiivi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaeztyd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2afuxhhrt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgsunir.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnrwffh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqahxhv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nddtvzyr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqggat.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgswhd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eefsspos.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibarzfnw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmvoigz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvzqkus.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khcarbnn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgdxymf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzaojie.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtqevrt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uewhidfj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cclgiwnb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpabwsd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxibdcz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mngjeyqr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2niijyonk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyosrevh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrrjxce.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfozuzyy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2auzgmcfk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrqeqi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpxfndn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2somgvkas.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngapwlkt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lfytxvtr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbifokex.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklkspi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxvjaql.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuykuiz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrbsgyj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfrjcj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkblupwm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtuboqp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brzguazn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tejcoxhj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oecxvdta.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoixphn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbumxshz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocztwpsz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzpfeue.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prlqxkrp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozanqnsa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2htbkavph.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiydknt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rixplrnk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njxmfttq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqhxcoi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rohanfsn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuyyzbw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlhcvru.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbudjgp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbxugkw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcbybod.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvxdsqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhklxik.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuswokv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcafujr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfwhhzr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2texcpkhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwawxy.html


<!-- 参考信息 -->