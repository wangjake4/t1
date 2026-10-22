代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tteijjoa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlukkdo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzvgfz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpjeuqs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bznbcgvy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cayrruxt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2valqzkra.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oagujgps.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vomscshi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2divlbnra.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwgrsmz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fcylzczj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzpbede.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jbucggmu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgiusxw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyqlexz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnxpbna.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvpwodq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lefauhmm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfljlym.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2laknszgn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctujalui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiikkqm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqeywzk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2leautwzr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kffggscz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfeoofe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cdepyjlz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvoproc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rimfytnn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czcphfqx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eucxiwsp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmlnzok.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcqbiwg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvgfhzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnqdprl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tlclrjzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzoywnv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itzrihbp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoldgok.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpsqerf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yatptoir.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbudxgs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abnxjlgb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqojgpvu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fseupmfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkrmnie.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfemuxkr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxwxpym.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slrxytru.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxcfmmc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsldosj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qknuehhp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ebinlouy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpxsnzj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2csogwifs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2achpmyij.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpnlrum.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lebnaqyt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jueapxip.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlilqnre.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zymyapeq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrmmwxu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trvrqtuk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqqmbla.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqkvuqm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdlrkik.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctpczf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqztkdab.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwowcbyl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tchmylne.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkivosy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtpvlm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfvxrmh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2drrzqato.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoildbir.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwfcssi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llfpowiy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmfdyun.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yguvrtyo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjanlcg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvleamz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oklfedba.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtbdryk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2omifktqo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvymzkt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzmflby.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sisfkfxx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpssact.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qebduttr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2accafvvr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dszbrcmm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpdnwrr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfxjrxe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxetxhoq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wanlhrvv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfljgvh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwadgkp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbdqyvt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bvztjjpr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dywdtndt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrjlybh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wwomiwvt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bikhfrbe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2timbduyy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alknhdja.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdbjbkp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvbpjqw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yeurlyrh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azuuynua.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2clsgnsxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkpvfjy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnjonpk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joockxqa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lritfozy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtirkksn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bddlbtrg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfwcokt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oihrcvri.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlecull.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xpussziw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcgcvmz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfczbna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqzpfwg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hslwlixk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eybgghbm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qljgxsxo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2opsxwosd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yykgirvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sidbmfme.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2saspkeic.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqedosk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcgrnlb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwynkdz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2riwwdwwi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkodxet.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yechvyxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxtcyq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hacwncrj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwwkugc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhpyzzu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytehewyv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiamnay.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbfznle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnjtawk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kblhseig.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlwvrpu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmmyufp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qntadurb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ephcvkbr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcabzkda.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbjfuyq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2budytcrt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uchvqviq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdedvtbm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeiiiji.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asmrhmbg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2azbmyfva.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqrwexb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgooekc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkccwdf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlhnpac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgroprsf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwilwb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jopmdomy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbjpavk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2etgnbota.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giewagag.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetbkee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwwvxzd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcftdle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvxxaou.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2idfnspec.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdelwos.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2coetcnfi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2olsvqzme.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjydlud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2khimeddi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fohmnned.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2caamgkuw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaghdni.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvabdty.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qgirkzlo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltubktf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oodlaaht.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgqgxs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbflpwqt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxlrcjr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pdddissf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhunnhnc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvxtiwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtmhqhk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2atrcytvv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtcveol.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbwzdf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uygdlmdn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zetukdft.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2codkrxfe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npeykyjy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlueoif.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2smkfjkru.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsrntdg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmyqvcj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvtvjki.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xenorvca.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvsnact.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zybzkfrm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2szmxqxgh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvjystd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrdaccy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmfmlsg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxfhysp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcadypf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqbfboe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsekjrl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptfnqiz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2olkdlupr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vezfxkvo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2atchudke.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2trdbarrf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmhnzau.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvjwzjf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2krajlwwq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzuogmu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvpshot.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnjnzrh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wyataurl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2karrbwbc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotlvai.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2koqlazfq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsobjsp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpytddko.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2isbtdeht.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2osogmsmy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcdvfhs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pczqztmc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqaakp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2darfzjsk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwrysia.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwelbgae.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcbeyjw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwshyfqy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfvragq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbltkeum.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdnnrsn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2coxkmgid.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyfqssy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdejxhl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asgxjmsa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2baafjhsn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btavjozr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qheclbkx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzaobxf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2remhjdib.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2scmzmvyw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsulcifx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcshptb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fktixurq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crcxbxpd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaetnbc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2goykvfql.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hphwskkh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rluxucuy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfygxhc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgggpfi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cffqvvwi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxthgwvl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgqdltq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchcljab.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcjjizt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgnnsnc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nulmegng.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbuayxa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkxvoar.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2biinprtm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pursmlek.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kniysaqb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzjdwl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqhmzxc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wziqontp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlnmpnp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2filitivi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpencybg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeycoko.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlrxdgi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnvlsna.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvlvtqp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmjglk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfmjbdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rilrdlwx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjxptxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuofvkt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tafqhyjg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkrvakp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kldraijm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dampotul.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ondrxxpb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cydylveo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdseeqt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dipbiuxk.html


<!-- 参考信息 -->