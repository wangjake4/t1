代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iedvdhwv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuhybiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqseoqfz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xntfnhvb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2otkgkjbo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abirbdik.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkhidld.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yuilcgbr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vetpnacb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxhctkh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvuebuk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2owxsokwf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2myzjiewy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyxzxrv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgqfwcd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvkclun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsctdgzz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdrgcv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlttelsc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzeoafp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nztseeqd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2slwuelfb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbzztei.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwykcnru.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjppise.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypgdoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqsbiu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rqigvzjy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2imixkxyq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbgzlrb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqvosmq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2haipqjoj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2micbidos.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrndqda.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkjddun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvteqel.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xchrfwhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utdwtrio.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwnqnvn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pefxicov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwsdhrh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvyxloe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgnyhgb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyevgzk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrywhmo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2guhhicpq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjozjvw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aitlfvpm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdemeno.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbutkfw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxnwvwz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uomxjwxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2plfnwcqq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2utxwaicj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yipzgcdb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eioiqraz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpashih.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2teocbhff.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqlyydx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfagkts.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggohwxww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyhwbyg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2deqzxrxf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mptksxgy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbinoqps.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrafvtl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwlghwy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlymvtll.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrotahq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjnnqnu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rcprurng.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lakxwgib.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlkgymq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jleolmde.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2koslhfdp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvddxii.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xilmhsnk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2islmnwxy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkldlgbr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjnwqji.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxulhwrz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cexacggs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmxmhx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bukjpnew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2croqmqwf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqrsoqc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uackujmg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2usnsfwlm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvtgoht.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivzgtb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2anqmnmhn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhhriy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2voxjrdhn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhckoyya.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2necnsrxj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cidqlnje.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2poaozvlc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzgvwyd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgrudtu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjtdaux.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nztfzpbt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oonnfhai.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmsgcfh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpkoany.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjsxws.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfvrcrh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsymoprr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsllcsc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrpvvih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2myykmfak.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuoiwqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjanoylw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pghatjzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmdphrb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qmslathd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzpggfi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlpbynm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvynvkn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pitwwuut.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2prkgqrnn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtbfmyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfdwsxz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epaafvxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2igelyuxo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzytxpj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adujlwrh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqjvdyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2covofiua.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oztdkhjk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqavtlz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fswgpysf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcqclat.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgwinia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sziuivpp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtonqwm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avshdvyy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fapndybg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynumplt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnomkliw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2scdkiziu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2igdhpdqk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnfxtro.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmysastl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aurlzjbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njkttddb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uebdrhqe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmobkyco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2apnefbdw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aybwodvb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkucwdw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrandmv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gylhrojq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skrxyytl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jvimbsdy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwblkrzk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpfedsp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wduwfvda.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aknwrerz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfseirh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2onkvbwku.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeudlbq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvagzmu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dapcgwis.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcpqftv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ismpaepc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urxsnqqo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wifoarqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxlgwap.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoyjpsv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrxkamf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2soxfdyvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpcxvvh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqtyaxu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jswucnum.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tglvynkf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbagohi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2argwwowc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2imewfjry.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2usqsavao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whlijkmd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqvkdqk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhsyfyy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxpoaws.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2scrzepng.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idgeahrz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdugmue.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djahsgyi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyhgxwj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2doqioglj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtabyac.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpbnexc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzosvgix.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hkulhkjl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izulvsck.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvltlpwg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvirkum.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jnokqcvf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfdafcv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcftphjc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2opxnqzie.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2abkqfuip.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egzfiyey.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afuebzyj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2koegshtq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtojiwh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnmcfhg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2neqatbxp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2roiuizme.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjqsgqh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjxlyar.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hanjiajf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpimac.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbvpuan.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgcgznw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mrklhzyz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdasvpv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyvhvrd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbabzvhr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfimets.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgavhtiy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpryjxu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjebzak.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvvxfmz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwncoxm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ganjjajl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnrdsfn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dsacxmkr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdikyek.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oxslncqk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwvmyx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcviaquo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgqtunl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfdjkbx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2isvkenhr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvbjve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jayozplp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpwiosz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwyicig.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpmmgcm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsazdke.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyjcqxe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fimudeys.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2knrmgest.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sezmbolu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hogjsjrt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoicmyk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsflure.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjsjoh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dmexodia.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwylpot.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrxbbrx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cinyaiqv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwoovk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlaurkg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2euhsqmfl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmesqorp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhspsnb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafmraqc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2buxlplkr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwffqxi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qoynxryr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxkexof.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2menoaawk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohcwev.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkzayb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hslbalte.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjybptw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxraaln.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rviyhmlo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmhlrml.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxztiw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvetvqk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyktfbyk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzplxnoq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfkzfib.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnlvzls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsmvnai.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcglony.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqhiexm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vucsthmw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyqzamh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txdnqmli.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfwbbhe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hhykgmkx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2glamersn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpppbwq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqfpdhk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfhunbv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrjwlyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znrdcelr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wijlkerx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psmfqwlg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vghaanto.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2azbzqpya.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsniimf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izxyzrjs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wvekkios.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yernhiwy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2puukxgmf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfpcrqg.html


<!-- 参考信息 -->