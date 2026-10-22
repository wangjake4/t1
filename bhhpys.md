代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2swkerjzh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkrzdxu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lxojguwd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqfgkci.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qdheplhu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmflgju.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ialxxaqk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxfscn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmtehfd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxdberd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpnjyzg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgbfcm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuqlojo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zokoejea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bazbuamz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzlctzl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ysemzgva.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsibpkh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyuvhpk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdnysum.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbsaqhs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeptymc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhfwtum.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjqpopd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hefdhstm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmnxlob.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxtppxk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lnokzpyd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2puzcvcem.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jdivltkt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtateng.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cumwsnbf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yzklrasb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfcbbum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dihzwafc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrsvxkx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2krqztygn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nizushvw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tuobemha.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gacaooxh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwkrrok.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2odohdzaw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlesvyw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyhtkpq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvivwcn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhjxenb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlsytpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdtwsfw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaczfkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yioyfdbv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fejhcvbs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuakpt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhueezv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyeyrup.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyawzeyh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2upadmabg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxxhxpi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2membjfkh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yszapgkf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxggsir.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wscdwedc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjqhmut.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hmltcucs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bcegszfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2poastlcq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmbjzeu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoaeiph.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgephxkq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqnfbvw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gkffuent.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpebvpx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzenusfg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbogxjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2giwqjvfw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmyivge.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlhzxzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2shmweihd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqcnzys.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnnpwih.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ittenhad.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gkomoyjb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpthrsby.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fllmroon.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxmdxsq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2seknkbba.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qozngnen.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgjzjiq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfhausq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xexpofqo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2owaepgsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ashmpuge.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kejyynhx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqfetqf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzalamnj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwaxbdv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfrbgpf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqksfvhj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2attgrbse.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swnidhme.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaewsis.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2czdrbgms.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eceiyfxi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eftzdgsk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehcfnd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvaqoza.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxptodzq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmocyroy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzekepk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oybgyriy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gucwtqxr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekyacd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrmnyqc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cszetbxv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uopehcba.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxwarzi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkesxnbd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdndhtt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbjrqgg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzteofhp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uepacsqt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2csswqcbk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aabdzcoe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2auwuejsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzytbabl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2veddxffh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xximcldt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2brqtdpmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxpmost.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ncclcezq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lswekluj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxujoghm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkqqkzp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzutzkn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmqshjn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwnqins.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2muqymhye.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujncstop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpylxlo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lstymdyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmfwbol.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvmybon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qurhtkto.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2brvyxvsf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yemqegmw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2crqfdkpk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrnwxex.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vaemamyg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiepxgc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oekdixyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2visywejh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kspssbou.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxxefqw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdwruxu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdabqrew.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nghmispc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2swdsqatr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzcqpsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvahpu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxhrcj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwnoeem.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlfpswy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvzbvfj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2brpuwioi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2txeuvpps.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpajqku.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lgphxphi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uskqdhys.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fniievzc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfmlzmd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoldmbw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2axipnraa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaxkmrf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwpulb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtgwrg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgcsqmj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yiusysuc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yorfefwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xacuomyy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnsqrky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyktugvm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yarapzoi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvusrff.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfrgayr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hsosmwtm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfcqtbq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2usmqxsiu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rzefrtpe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnponue.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmlnglc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyuixfa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbpzoby.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufquabwv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rsitiilq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vunacrly.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuiblqv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfukyxfn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trtpenbx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnnughz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqinuyp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemdgvf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2znlmmflf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrpklnj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kflasqns.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfwzmhc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zolupppt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgqmvkb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgdbrum.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaqvoyq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmczlyf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aebtquvr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itlvpkzv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfxykvf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmopuhrz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbuiylw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgotri.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwetmjc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yaokqjbw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfywzqz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mzggirfc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrejeeg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmturit.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2syymtlaq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hovdxvfp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqbtgan.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nknsswqo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeqsfck.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxoawz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cplvtgzt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvbcdsn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudycwxx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjhqbdr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzvqqed.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxrbbxs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijtmlkv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmialsk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpjinlo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uilfivhc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsxvwlp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2flcnzrae.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfbzbjy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kerxsyqv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vysxoksf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zefjseqy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmvozza.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqthggdg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cjecwujh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2voeugxwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpizhhy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmebccc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiqmmzz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aarbigrz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkaxner.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qltbejzf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvcgmbj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrtiisa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgoewly.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxbtayf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqhpqqa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqjbvug.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2krehkfyf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzipncl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxntilgw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kragkgad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqetchm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljltueir.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2utrdmndf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxscjinw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqadnvx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxhqqmb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmwdsue.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxububk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyednsa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvslnef.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcacwe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2diyenyea.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyaarqy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egoyarif.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjjcrmf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqnlabx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2afesapxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznmyeib.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoezoge.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bozivrth.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krtghghu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdmaija.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlgxghu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsjfjcj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdgaga.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzibpfqx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gyffmuby.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijytjncl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nekizppt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklncir.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swwbnfmz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryujctfq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kznyrgbp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzpfjbs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdongao.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfdjial.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xvihnoot.html


<!-- 参考信息 -->