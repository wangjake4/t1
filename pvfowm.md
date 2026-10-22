代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cswrhxfs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvqqibl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnjabmj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2thazvbvq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bebjsbgw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xglkckla.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sarsfndl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvdgfr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubmgpb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmvncfz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zspcdukk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbbjscm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxqumyj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2selcdppi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkvhnph.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpuhyal.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gpulkoey.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqycwjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvlmly.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzicvui.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fybylphi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urdjbbmc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oequytvz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhiplhk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2redluzju.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnqzhf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgemjyov.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mksbilco.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sswouxde.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ivavsimu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzfqecy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flmoztwn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2elcvcxkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btungxtq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnfrek.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvrtyjc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdtktaz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2veovygtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdydghle.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qktrzpbk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2biuqfsem.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yliokizy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2chluwsrn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvtwycd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaowutw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esgbzikx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybpqjp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jglmvbdm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjawwax.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2igoywgub.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2afnbjesw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnwcned.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pnotsymy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzqpdsv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvlijaj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuofbma.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnulllnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2neytxzjm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yszxjaay.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woueujlk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnqhgnz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbyidmd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiouaqja.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsjxbqu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrvwyzy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czfgknae.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wvntskef.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2umybbbje.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyfegfn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxdbfwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urjfuekp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqteosf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyrmpvl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwgoiz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwickm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sswknxka.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdkxxdi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urmduxur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2focskjuc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zuemsqxx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2chsiwvhe.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mszdmnnt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdnfkgy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dknwbfpv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2irutkvpc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2icrqwisj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jecqrudq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhdncyj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbruiern.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhwhgqi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmmhhis.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znkbovvs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjpgwod.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruagcjsh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvlhioe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2havxbbne.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhlfsg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeocfub.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfulgip.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlhhiul.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bokerivl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmghnnf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdymdwp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwddneo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cftdtctf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjxcnf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpriyuv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obajhhyo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmpdejj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhlfpzf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2omsgosio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqexvbge.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoqporw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hczxzcfg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwzshyz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzuzwxb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtafoyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aujuusao.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvclwuyo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwmmlyd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiupmrhl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrlobbw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmxrvng.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiopmtf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jujjbrxn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxrlzwx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xvitjfge.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnyussb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2szkgkipq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2curnzvdn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2isjlccog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfiyfhs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2robecuwt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edswmcnn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtwaeuv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oejzfpas.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglzllne.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szimjizr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2arjlauvk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2quvdmzlw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vutzbypw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhrfei.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnprwdvc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iuknuovz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnacqbk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgzhrxj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismisapv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexwmfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2snhccpai.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqxbpli.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfdrbnq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xiynnlpd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejrasbb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzsmlng.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2povkywec.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsyvryf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lppivqvk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxifzmvl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsnasaj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bsckcwmi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlndvkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmbwry.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cahluadl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phihntub.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvujnoa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvkwnbm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imlttmtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvsncqo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjztujw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2grsdxilz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyzaga.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jaudcqtg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dzntfvhe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjeuako.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mcljcazu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqakestp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlianxc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoophjyx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxaryht.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoslnaqs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrjrryp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2imqmodpj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvvsakv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpspipoy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuoeruo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfyhzym.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvjfwbw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrqdipe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlzstuy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihporfql.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojxoal.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjldbbsu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nujuaien.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pamgnijl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2biqzuoaj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcwxesm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibchuszh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vldmrknq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2styelqhr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yawfmtov.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2msbrcdhk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lztmlmno.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzvsxfs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtucqox.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olqvbppp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaykufm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lrajxrro.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhcgxp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uneiqqid.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbekfgaj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kroizjqn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvvvnt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zwipytil.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuceqjwy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtahpyuz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhgjgxi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aibypizx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrixnlv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jozimiph.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2alnortyw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qapllndt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eawgqnxa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pigqhnrk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkyazsr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uydkrnur.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkimpkp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhsufnx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sofjgata.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkrviif.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmezkcv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzybze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oetcftxi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gizzmdmg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqybkog.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwjxmgw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcvkuzi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfgwxcm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsltzgfd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgujdrfp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcxkzkn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvwkdyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvhlvaz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2riwejqim.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yiphbtur.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxyqutx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmtbbbd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwuysbg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfaugez.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsjzecs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2waawhlya.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdccsf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwrffhs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2unrwkusp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guvghjas.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqivdryj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmrhxpn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2blvflzck.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnekiqd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvdoqez.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjelzgm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npsepisv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxqconl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inbptlhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ararqroh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djhfhrhw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2piypffrj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpgtolo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqqzfb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2soyhelqk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuxxwab.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rivhaoim.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2awmqtlzo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdvtwzv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cavbktoa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoaqoju.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2duylplhr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpynvufw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qiouxrcb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnesjti.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfnxke.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgbslle.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqvxjcs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgvvkla.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2luxoljog.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2smitqlah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2temnnrqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjlheaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyicicn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2einkdlhv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvodsga.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiddkrs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wftxrwie.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ddobndwq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmqlwht.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2klmhllzv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2crwuafyu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuwvolu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsszzvd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bpetxdrz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zklezfdg.html


<!-- 参考信息 -->