代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiqarwk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcchxiyi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsgphau.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uijqdmxn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pazshxiu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwycwdop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutuxzsa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aroafqkd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qswmcfen.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvcmkyx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aielcziw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yljsbnyt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yqchjeuz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzopisyy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyuangw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xizqigvb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eflscfrj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnfmnre.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmtewks.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vtliqzuo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmzphte.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqxurd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eafhhzdz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2covebljg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqqscfs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrlkbqh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvumntz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstefft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjwfmmg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsomixop.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvodevw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtyloez.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnmkywy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ufewfvnx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byxnpzuc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cibcjann.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsrvbjo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnqdonz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrlikk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdaphr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xduydbwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwifbrce.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qibrflzt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxkczkh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmutzwb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ebestjun.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2skixkizc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrdmkzs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkodakjy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfbetmw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkmdnna.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urhukyoo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtwzegb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pewppvxn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeifzvx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxqphey.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2owxaofvz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuwuqea.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpmiikh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbsseeg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjoigkg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkcmrjy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrcwynx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owtptkur.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qklozxkr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2niuuyxgn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwgifav.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shkwgxiv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtilvdxz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxpcgnf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsmgduj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lydpchhj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2exzthcoo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumnhos.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdktfkkp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2glcolblp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxwkojx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2effqnkmj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqezjz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuxtlwj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qolgqngc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xucwwrph.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2slcrwpxe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwyqpsf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sioojytg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkodrur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjcnzac.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sqialawf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2skppnkro.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaymhut.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlusrhl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyxtcwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pavkrhvf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2igsgthts.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzlujhk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vuworuqj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrprwwb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzobswdq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqgewqy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjswgpg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfmbcf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emwnmwxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkdrajn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nofwmwgl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdzexdr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vkanwcei.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqhryjy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuayyith.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2njkmxpku.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvmbygv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdaugua.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2paruojll.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jqprgwmv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdeqicg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ikykcbif.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwamnma.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2atsbzwll.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmllqobs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpnvxhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2asrqmdqo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2etlcibzl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsizbmxm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwomnvc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xlecslpj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhfnowc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2txlaeiya.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhsigoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcmisqe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwezzxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsjrjno.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owxupuxq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrpzkaf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyjeygg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tejnkjqa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppaatt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjifyxc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vaughdkv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlfddpe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrpugoa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2septphey.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvueihy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjotyuwk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkkulog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgnckdz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczvpjjk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeilolw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hrztamyv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2trvwprdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtqrjwl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trpdeczx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhzyqyn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxomawk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qybwozjf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpqijxx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rprsglym.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdqacyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyujzne.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfxduoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaztzykl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxvzwta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqxvmpe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhfoacs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonzusgv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxidgqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxheekkc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdwpcua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkftpmlm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvphpmyr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ztveiagb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzjyzkq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wstphvco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhaeulj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxtuqh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aohqivvv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewedslkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2emdpzlcl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ecijimcp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqaogny.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cswbbfob.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtrxypk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfsuhhp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnfcbfw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gsocrbot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljgrxxo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmkkcfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smypbrhf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bofaudtb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kseueygs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvpslzt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmupepjh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jooksfoi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mopvktcz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zeusbpfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwywofug.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkolsps.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gykcxztv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtwvwum.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fymnhbjg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amrmzddl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabfdjnw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lahtgrbq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiglvqd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jluaitru.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfdzttl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzehydl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbabkez.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrgszfk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lozeeqxd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvgmaaa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvynzkp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfudqd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkcsryv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqfwhij.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwtivdx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2subttyck.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiouziyc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fawaitii.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2evohgvhf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lesindwg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqkgrow.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgowal.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpltpuze.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2alkeupmh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2coxveljt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2trpxqpxu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxtoawh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzktzem.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2boayfuqx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkidxs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aanqnynw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jfawgcst.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffflwqxl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usitbync.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuqhqoq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoktlpw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rcixrwwp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqqmvac.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqvlven.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2krcgwhlf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzezzae.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kttayfie.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjjgdzo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbkpzou.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xouhpfyx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2npsrwwwb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgrcvcq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrqmowm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2omsqlgwh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnsyjhv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpjrgar.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddibpkco.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvhuert.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtfhhd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cejludca.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwctodw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnyggbe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqobixbg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyzhswz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrsmevf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuropvz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2itqypqcn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrbezw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqknsn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2canrezff.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjxccov.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubyuicj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqipow.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnymmir.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeqwheg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcckdwbm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oebsgngk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtrbbrc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmutiwks.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jngjhhso.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzfoctd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqdzkem.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oshdiopy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwjyli.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iojhobky.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqqyei.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fspdtmgg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpvbqxj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrovnek.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnencnsi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocitlgy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmqzkwb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpblull.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfrfarw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2roplvggn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hygdietv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2entpkhxj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2onkfzqod.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdukpgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrnrfiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2islwmnqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zahiwurc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xruxbafp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2banpnutq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yeanuwtv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwabcfo.html


<!-- 参考信息 -->