代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2icrknxfu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyneczx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcvgitz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pbygphsl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gibgyelf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crxkixxk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eoevjgux.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxblavf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2thuuseze.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwigwoa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuzpjkn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvixoefs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bggopfcx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjlqwbt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmzisaa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrxdexq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzgowuh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqewhhun.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qauahawr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpvammz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpojwxe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2neksgzkx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzamjjm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdxwtsy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyvkvly.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2amhjgsja.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wugcyvmn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iacqofpu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xztlrqes.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrbxks.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcymdvw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcobcra.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbquxwot.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2domtxuse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlcsinr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2witoxahp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2oaalccfw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqihwc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yarlxnzw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcoqhmj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjcbuln.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxgbhw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsmwtoe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hoksnuie.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vtexrmnw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbpezea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvceencr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqirnho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elcqzhhx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvmnltx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzaahfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbedhma.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvqmsfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrjtcp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbbnafk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aprpxgmc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbnqidw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsaqdpb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzzhwqo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2khkbaeqj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pifmbqaq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oioflzny.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcqrtcm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pafachsw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qecczvwn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcurahjr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iukyvbxn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsqsels.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuwuhhp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kmibolpv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrimhnga.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dyteuopb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2poslowze.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrfztoo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2umygxaos.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atlbwohl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2icomwzdy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsxdjlh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfixcxdk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmorxtl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmajload.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvpugdn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyipdye.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxyheyd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqsznvn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjooavr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhlgdoy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmzhwct.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqfotpa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzmuapj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrglnnj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrceqvq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qojpapsu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cigsnncj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoadrcz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yovlbjaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodvqjn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scvvmnlr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbzdiit.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkbhwpb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeqaqss.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vutecdgg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2plnxbceq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfezzhz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbybhdqh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ussttpcs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkdhgoy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uasetcbt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjagmber.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdzkoem.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdzbvee.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jamvdojb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdyghta.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyccps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrtavrh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ekelotfe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqytcll.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqucnfq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmudvzv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcphzmet.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kooqzcho.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcamnqn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dikmwwmk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rveyjvsn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kbodrdii.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nffinzfy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwtsogb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwfrmfu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vxncydcj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2refvozfh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbjuwbr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hytkvwbe.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2imwuofas.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uerdyixu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtcdfco.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lsungxeu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhwxxqe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vylkjmtu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwwxuvr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmevltpc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwquegu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcuslzt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvttsocj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdsxmry.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2elsokapw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtpmtdm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2htaxdyqz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgskaicx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2viboxmry.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnetfrd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2otwubwxm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfegaghj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tisljrtr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yalrfoad.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsglqlva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrpcqdb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eraqpgkt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiimlfh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvussul.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wtozjuly.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2naqgnwjc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlhzmsf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wicjxtbz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxwjzs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfamssg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2szswydks.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzskvkl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inxhomak.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvvczgw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwghurx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaecbwy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nekoujof.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwbjovj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iurvghcf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uryzntbl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaibihm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiydeoz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdfzkxj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2enuhviwl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlmjawz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dsngikea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcjosiq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tiruchld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlkbtcx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2caufhpot.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiskmxp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxspnmkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lonjzpah.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2piwsaame.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rezldwpj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgkbwkn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidwwqk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnpkszc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vocbzunc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlhenai.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjxoqrq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuychjo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofejsggn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uoobkrlu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpipijof.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqlqtwf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfafjxw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvuouco.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbvmxdg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iezwryli.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sepsesuz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkskpmk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwetvsjx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kjogikwm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxptwyhu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaydhva.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogigcsni.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2caqtgdyy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcnqsyt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhowcymb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agqhcexs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2arqapllq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wssvnagv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iffeimbr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2npybswsv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjamomg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyvziun.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oofencez.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgekeati.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klykhley.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvoxsqq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fiycveqc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amlhbzey.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zntzphub.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuqmyit.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fswiwczi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlfiqh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2syzercxc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyyxard.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtyqrsa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwyydno.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fwteeacd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhekgzb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ajypvjcr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbmzdc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exxosmpj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngquewtc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2btaqpbrh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nptlwxcc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awgtjaiq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qujxmtxo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmnbjkp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwiuzbx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2snnekydh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jiquyndi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnopuvn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2exnttofv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgppfwp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kodmyzyv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olgrovrv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckindlat.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxjxyvc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uavwsvxa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfewiugv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2erbdzkwb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgofziu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2onilofbe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzuhjru.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxrtead.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2auutdkia.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2amevneyc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wytrcmrd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpnbduh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2usgnyloo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuriemu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eotttczu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stpiiyua.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwykfizn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxewfge.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjshzzb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdlbmv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cinddfym.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2louzldwh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnluzhn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwoljz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asdybxst.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknxaduu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbefkoiu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2njlxcscb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoylvyw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaawbdh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mprycwxw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxoawxg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcwpdsd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rscnejeu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kghvkihk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmvlau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oduzrcfy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuvblzy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaaksvg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqpehsh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvgvspk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2linarwjv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2agoxdfwp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bawspcrl.html


<!-- 参考信息 -->