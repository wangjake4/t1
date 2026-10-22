代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hjujpgef.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqlphbd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wolgnsav.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymircjct.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpucfvq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyaglql.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrubekc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfharac.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pppgozom.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjwrtmr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnatjhg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eezjolnx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dagaifji.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrsduws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcayscu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzhelmm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkasxviz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhcral.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rscyebif.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxanfhw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yezayiak.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclueyl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiemhpy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eysjwvtu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xojofbkj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzeykoi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duzsavms.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjyagf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipblgcaa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuwyqbm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkkjpnm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jytkeelp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xszvietx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoxmkva.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpipvcuh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqawmza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhiiyto.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpttepz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbptisd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcoybqk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2flcjxpzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrhtlxd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwizrdih.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jejffqbs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeadizuh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxluyph.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2myrybnrd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgrojiy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhyzrov.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cesspkvm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdobzis.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubwsoh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqabvtvb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtzfdkv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnlkdqu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2avokcwck.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxvzxzm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrcspte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2soqawykw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtzjvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2riosbhow.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gsarjtnf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eslmbuar.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfigths.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqjgxvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrvjvly.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxokgqi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otkmyqzd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfccmsg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fmafrdmv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rggqdqhf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbesvmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlsghdr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvupzhm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbinjujp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqwzti.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwcxiif.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dknfeehg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzgqdsg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pblxrcfv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2alqtmtwb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgpkhwk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2stmpbdnm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdqvwls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcxeusv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2itnnzxfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2saoqkbty.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2goakzbnc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrzjrgm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwhiusi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptksnjsb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2liytvaic.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdhwbst.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ttulwwnl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhpujtp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmybnwf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqalbyg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpaucyu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaggrna.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxevfwj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfesaewq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoicsfgx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibndauug.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2saxyedci.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fovojypk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcfmsin.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2boawgubd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njmhcudh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlltqks.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afqwiirl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oshjbyhw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhipvnze.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwajtff.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzdtoig.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmdwuzz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzkcyet.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2afdtatqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scfbjvzl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iukmyzfa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2owywtkst.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2peunkuzc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzxwuok.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chqdnnfs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2unaiqopr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrltwagq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvyebhq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjcaax.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrkkmtc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvksnen.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjajqpq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fakfmysf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdgsado.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mizsxzab.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkpefqt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wslxkeac.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazwletd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zhweulwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvdqlnb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsbbwtl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjnzisz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbdzbn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euywwvvn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqfifej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwenjjth.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2htsnlvts.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhauym.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfrsehw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkhxyiv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdjabqv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxvoywu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkyjiia.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ydayfjjw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbiqnby.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zaromzwl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2auchmmpf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfzbwso.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbstckl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2syuwmucu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgwfytf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhzgvzw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiswrbph.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuebzbd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvldqne.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljayeamw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yprafqkb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqhdnpk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qphbgtoa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2udcvbgun.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvykmhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2equdjwom.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2klrdljgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtglrbq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gflxavnw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtonzgp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zypljthc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdiqidk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqgbogb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqzefac.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzhgbez.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqavitxm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zghljxyp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxpoqsd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pykesdad.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyuslpe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nustumwx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfpclrr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvprmu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlftflf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vklaxpnl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpuuiv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmzqlvh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxcnnwl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvouhdr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdajytxp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnhnvr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyjcyjd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpvlsqt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjtwubd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brzyemvp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mowqlwdm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkogeb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnostui.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdbnqry.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkceato.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrodinr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlcilje.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cuprebvj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtklwsg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nctyckvh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikociyqh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwxppox.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyceovye.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztydnvuf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvvayrz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddolrbka.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnyicl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azebpgop.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lalvztzn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxnwbsx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtyynbt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtxpkvr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2foqhfueu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lotmdhqk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2unckptul.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtnojhq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwhrlkr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wletyeku.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yonoqsey.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aratadde.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpsoskp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjkrxuw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcnsofv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpsjiwq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmxknq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uehacdvp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzoetmd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgwkvlt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2linrxgur.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sntuegmb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnlqyvo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjghmpq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tswuimnl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clqhzneq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlmnisj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ottmkgeh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zswmtdav.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dugrctbf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbidozf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqehghc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnztamjd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjctcki.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdozbqy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kynshfaq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2axswvlkg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxmiqlg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqqkqoe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtswgi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiueuht.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxacsva.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbqqusx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaliytc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiikdhvb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxeffhk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyalxnh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2infyrkmq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvjdkuv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiakfgoe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iycwxfsm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzzrsbh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpjptdh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbebblf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqejaks.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csshmhjk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejchnnrf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2blvjxvcd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwdygsk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhnehhm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzxaecb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhwscft.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qipawbfj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyofwlpm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2acrrkpko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyqbsho.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cnylhvbb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2exayvfpe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cveeigwr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapxfow.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrlarsu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvstqsa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vrehfqwr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocphrxy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxwapf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2joxgbssz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlqwgc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wenqrrbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtvgkh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiozimr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yehxlrqm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkngtrj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhhuvqt.html


<!-- 参考信息 -->