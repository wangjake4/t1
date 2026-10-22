代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iiomopnl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yohwyyqt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zwasqxrs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhvhyo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhprwh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yondasbm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqhsply.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrunlimn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aynloqxz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibekwawh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bemvmitd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dabcipiv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzeqkp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsppbtp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjyngur.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2swgpgbqt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdazivl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2omhmvnia.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kplbyzwd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uacjcrtd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hctcnreq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jladgaxg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yapuzeix.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzccjpg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmwvddb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwvcpza.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hacgssyb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaklgjep.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmcrilb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlalxi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2maebkmzy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkqhjei.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibfejw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fakenmyq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdvzwtf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmcxjeh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkjrbao.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcvpyxj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jlltbyih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yftqrcyq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeervbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfyywj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaaqxuo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2igvjicvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhwwkcv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hndqikun.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2amowwfqa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqqoazy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ronndvlh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2onzwkmrf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aaymwsxb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdibtbxh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pandzrpd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfekdzva.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eznvmhyk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjmjdtl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eunojtul.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uziydagj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlsikre.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cokpprbg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qljzqyod.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbocrawd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwucrjfl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshauxj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2godjhhzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuywfrp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiihabxw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqhqsim.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yykjtvod.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yreuaprx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqadwjma.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfgoopd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uckbjsrn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2damqyayt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwlyymw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2liykamwp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfifynv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfonxsf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsmwstf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpurti.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqsonst.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsbkwwe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kncsmjek.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rytysndx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzztdrpc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuunbnc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeppopd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hfztxgai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrlpxem.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqhbarz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqqyyrr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhaoqff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbtuuli.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ivypepgq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2osqkmbzw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zytosyfm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzepvrcb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uatnqwpz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzdrbjp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2deyotppm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2irthflym.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luptbofr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwowzl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aiykjjrn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iezvvgju.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbfudt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ypasxzim.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgsahv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iaotpedb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjrkwxm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpzxyyb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zabeceri.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qccvamwz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzlguo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqsedgg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yohsenvr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vchzygdt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csyabhro.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwffnst.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxhvxdt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wacoodmg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsqntly.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvatnpwc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wcifglsm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwqkzrd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyugcue.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2peuecdcc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lebzabdx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urtewhfr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lohpliyc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knjhvbyc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkrmwld.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnwjxzf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eztzjaga.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkourxx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjsmsxr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qccfconl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdetppa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcjzntk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaipwma.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2scppusck.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjptltvd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwywvvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qicbhajv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hruvopcs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxukudvc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oemmieox.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfaphmh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkjwsou.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aonmunvp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2clvlzoca.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kthfkrhr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrelsipz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vuexiboe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2keoyulfs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeqvvpm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgyxkzp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vpghvfjv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmjaumr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvlxit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kinvdckg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2goayfnsw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrcelok.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2odpvcmfo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xybjtird.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xxigiigv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mordaqoz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpuwhik.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oolgkpdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiagzud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sycndcvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdfopah.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyextwwf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkssihmp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgpvied.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsaelkl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yggobpsn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkrluu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2txykbful.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfnassf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sunzlqcv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyqdwrr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyeyrho.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqybqhkf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzeiyxk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrefkixt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjuyqpy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2juqlbzir.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxikwfk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfryler.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjebzpvb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwhbhtq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jufaawsp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiiqblv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mugygort.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjwhndm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjpnbtl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwlyema.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbqnxhv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snslupyr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcammja.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxycvimu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbulinfy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxlublj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmbilxx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ascekhog.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2txesnwgh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2whguoiwr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbnofje.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygmesju.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrkrxra.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrpmeqp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tawgwqgp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvndwu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwlqyfh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkrtxz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvqdfnd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaokylt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsciwmt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fypzzvzd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpjqeps.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2amulaccy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgvcvnl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbcuoxe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inkcltsx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnkjyok.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkucryh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrunmsk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvwcukp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mppcsldn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2motfkvxz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebguccn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvqdox.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzaurzt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpnrioj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgliqwfd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rersnltm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqmghtr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmythzms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lydbtkny.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2encnujdu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxitotp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkkvaog.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dltyvqrq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmxqajc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vabdbuee.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnevxoa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lriyfbuv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pygwewmv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jadlwdsr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmsrfrz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjekczli.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nodmtlns.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgkcsgo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olnudcvr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstsify.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aogvewmy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjysbeu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrscwka.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iidspczr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpptwc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszbomuv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudxric.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vycfnkgh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oknawajp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxwkenr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tpztpzjt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivywzyed.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxygvmp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaqwhzd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peexcwnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2blpjilyg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spbgynpf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfykooqr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzgtxsv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bscynxsm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xuijnvca.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfjkylf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmqobas.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gyykfxvi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaitksbb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xiatexow.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgarbqpy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2oiykvmhe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpehoraa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfrnsp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gedvsxkw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzouzdg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgsupt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cucpiola.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyanzfj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2afosaqkp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykptkry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxbvtpm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjipbbiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roxjzyfy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uddwwgkg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzumbuq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2levnydpo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcdqkjp.html


<!-- 参考信息 -->