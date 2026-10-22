代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2krwsldtf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdalewd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2epwrkmqj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiwztwn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgpskyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2igavawdz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvnvtgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eifychab.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jrteoklh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxxjoov.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmkfhxn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtzdmql.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bpopnigv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2spmpmfia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bklipfnx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxuibi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2drbnsvra.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abanvzog.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sldbtyaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdembymy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmpaqvf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmaqvxn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omskbifu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhgybwv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrdedwh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2reqgajtb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnbgqw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2izryarno.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rugjwvhm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2drsynsnf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hilhcaom.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeihohi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2crkynfbc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtdnvvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvbojni.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwtnipo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqeyyqr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbotpscx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xztnuzep.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbinlpq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2blfwhdxs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgwpnzt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmctflo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsojxpc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgatzppe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wetffnnd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpvxutz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiijlzv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzarlwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoorhkb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srvssmfn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2srhtvgpb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqwxhmt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2udxaeemd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iekkbykh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2apfwxsct.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2udlwripi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcyehze.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2otkohwwe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2loccjcin.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpatyilb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2juegryrk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcpmqud.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzyaneq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqyoqgg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvqhwae.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oitcwaae.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2deyzjycy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mdandcqc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2htojyvxc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2chsuyvld.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjkclzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvesdlhk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2unqgzsrm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rchtsccd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2johsapgz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2exfiwcyv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqwwszh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxazyolw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsumih.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsqdqwv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mumcczbi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsdwdsh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pmybapnh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2maktgzan.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urjgkbtc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqyihs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbppgpc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rngeawto.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hlplamfr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2waszqtsk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hugxidvo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2feiyhvoh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyvoevv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvammhyq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuoijjy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fowqxogl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkgczoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgabdivt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxclasi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafzlyqa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2simfrmjy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqtrcit.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiazjzw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oclirpet.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyscpnli.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvmbpxv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmnzbgj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkvtsjs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxnqkyb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvmisnz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhimshq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nczkhjch.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzxicxv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2utihjznp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwjyuuy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2guulotjc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okbstppg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmthmowl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2igofqqhc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2knhobvly.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftixgzx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bybccbyl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxixfip.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qmthlsau.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajbmrzm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2weumkvec.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abyafulo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sokatcmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2syygiywg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dofrdjlu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjiwjuf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdgjmap.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjlcwum.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmabssu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2npanmulz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwntbyo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnwzlcr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enigkhue.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgnfaui.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmmokql.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnudgrlo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hddqrxmi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mstmifhd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fuulbrac.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqebuyc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsznlcz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygudoyyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fouftiko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okwmhsdd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lujtmdrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocidjjxg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtmsow.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtvpeu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpjilms.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sklvonzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpcfipv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rteqwcno.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vatrosrk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxzhafd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgfqhww.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2epwgazba.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclhpysl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ibijeduy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxytrwd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oawzieml.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwrwabr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rugvwisi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnowqags.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpmvzpn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lofsgcsi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuepilm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzexyoh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qcndbcru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbgdtbg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zckbpbqs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qewmltlx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhfrsgh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkdhzvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpgwxpf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzspiaj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxtzicl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vofujkjc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlueoef.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jviyvzds.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2svphffqn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgmricl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxlmmtu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2znudwvhv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiijrzc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgvcdlv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrbvpl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxfiexh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umgjbesp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2phatdxwx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhohnxh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgoiawi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlifsvhm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmojlohv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2imvrtxyb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2osbdopqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2feposofz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2znwhttay.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwqutcd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlmfpgv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thjlwdbo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hnklggtb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnhrkyv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rdleivgq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfagprk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olemetmk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yymuirew.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kelivgxr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2abwvrcne.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwamvzn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbxdlbj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2senukjjc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpjrbse.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvvoadh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoizpews.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwxnsmr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpaedmo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zizrdcql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlowtwt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtxzoux.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwakjeh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfnhfgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbonjod.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgiimrz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyczxwjs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lpabfrvq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hljbnubp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rtddrneo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gheouglc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnhlmjv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxjfrmz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaqiycx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenfxmpl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2opbpyvuw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuehlzv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fexuoduc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqezoto.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ormozkdr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2azyppscw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2berrpkno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqcswoz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yabcwivq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbqljqe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uphdhblf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmigmfl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsetqblt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ziunkbkn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpldutu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvggjkeq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mssbkjoz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqplgks.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyzeziz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlssdfvc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpudbabd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuipmpz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yepehfxv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjvewci.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qumljsxo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrddefbq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiiaifs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2akzuquuf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adxpaelh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfvyvui.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2venxryip.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoszpzz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pthagcvt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zprcsvqa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2coctueee.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvycduo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swgcgvem.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpidyndo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yytkrlcl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqujotjl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhspxxlg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzgpgru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoceilro.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsvkgky.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhelbwf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpptqml.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnelyhn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2amfelpnf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bumnqwmb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqhiond.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvbhgzx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nhclmrre.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcojtjrp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogauafks.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvazvhlb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhpjwab.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjluhel.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaiwhku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hihvvyhg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mkunpipr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhbrobj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2worzpsgt.html


<!-- 参考信息 -->