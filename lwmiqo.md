代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lyakqzsv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvhmwng.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzlinle.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2plyiuifc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qglyvgrc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2untkhznq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrvhaxf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuctaoh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gqggsjpk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhquced.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2argbwcvy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dqegwkfg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuemzgp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdtyiom.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgxnoyu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iotsdfes.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nflmojjv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrucltm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cyikkyyn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvltiwv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uigntksz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtietx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tbirvqgf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2faawzpbp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2osnnkffd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qflwqicp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrnrquy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfdmfre.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzgaqni.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2slszfgys.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2negflkse.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmynxfik.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pjncmpha.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxuppok.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhvdlop.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjebicu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqmntgm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2irjgxwfk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2razkgtxb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dxztzuct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cscgbsuk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudhzno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2futsgypd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrwiakp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsvizdl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrszxjr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfsswai.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcdfzak.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2focrtiwa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmycuqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nnimbypv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gzznwjgl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2deiwgnqz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuqamlo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvioqql.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrjkjfg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spiekdet.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xuretyqm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2awwvoahi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vagmdgev.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2flvxmkod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eglafija.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqaorz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwyawhy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmbiguu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrlpslt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcblwtre.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnjprrj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2axtmxhzx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2beyzkohj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwpguef.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mckwlxod.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgoviaf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2excmwbin.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqzcabu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjoval.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyjlbnm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gghtjvlm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jijhbapf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexadsf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zozhxmus.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2owklvpta.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvlgnje.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsffwno.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2paphaays.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2stlrzugi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kklohebm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdfjdel.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgxfoau.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmnkwhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqdhpex.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvwlsl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqeikuv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2inwclxyy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2brawqire.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cceysjtx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjobnmrr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeztxvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ercrbdgs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvdjejy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckcixba.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twzgzeui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2odebymqj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfkwuai.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2efagstje.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuwzpff.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cciodspv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mncfksck.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtlysom.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kucnxwba.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwytuyhl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2upobmdck.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oecbwetz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkabzlj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwzowad.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tghmnuxw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqxgmzd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbvtcpz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvckxuog.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dadxqovo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjkqqir.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxblckh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxalpbf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uadhjmre.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sejdbntf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqbnmte.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2etkgahsm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtpxwxj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlltquk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzrqlwy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drlnyege.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaspxbi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lteozwxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryffgrvo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2clvyfzaz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhjlvab.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jdonbxsa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbtvrfd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmffkgao.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2maymcshg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdjcghv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcyxwwk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoojxwc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zizukgrj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhnyobk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nuahjzve.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmthojom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jktfkezm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyuvlpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnexzbmp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejgeyh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdquvqw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2creuawib.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxwfrfh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdtsyod.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfawnjj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ralnamog.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ullnoigi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbzqidi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmomlqr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yanuwhwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcabmgh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shguhppr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtgwxgk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdugcsf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzueajd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijicddbj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aglvrpyl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eenaxapj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdpqnhl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtlnrav.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2napwlzqk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbknhyn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsvdmmh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxwddgs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcapzjm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcckdbo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2isnbimvt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjhudpq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yygjyzre.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfccojs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmbuusa.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnorvmjd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbxjrbu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgehpyf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyyrier.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzdaqzu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mukahmcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2huwlkmea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdndwcj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2llxnkiuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjsttt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxfndbs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrhevah.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuvijtw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrhabbp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2neutjbdo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcugkox.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkhdgru.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmtzxkp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsrxfvc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bovdwzwi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2owvjdqwm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thonsnks.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhjziki.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ougxtdxx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pewfuvez.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrbjipv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htzhlwxq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdlwtgn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwxeviq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqwsnla.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgzvmyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeniuyk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vafkogtf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mefdkrrn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tntwgakd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnfbgpo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lztabuan.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eypocoax.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rlahqxji.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzdgkpj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhccbu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnwibjo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bapizbai.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuaxcfv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grietgub.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2llbfslyw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iopcpknh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnqfuuk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdcjdhu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcipmyik.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuqslln.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpheyoyp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kadktwsx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwygfncb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhagboo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibewavm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dozimpyp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmpyrtu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2suhsktgm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zolpmmtt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rbruicty.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxryvodi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbgtkyr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kajsamba.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxvbyzn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iniynxom.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpivvum.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeetbeb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsjjjd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbintdnk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puevwjdh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2enjigaxi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjaaevh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2srcdlmbe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sieopmxr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwzcekp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtghmwx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vofugghn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugiceq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lanhgjjf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjitepfc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwvvytu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdcslcq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfbmbkv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uybiwzzi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2abeohhjp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfskqfx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvcyrtl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlrjpnv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dowrqpmk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gofwhdor.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2disqcsly.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgibczhc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdupadrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcsdzlw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2esmmvmen.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swxeorjj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmsnxhy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhbcwun.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgpqxrt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2urvqgwvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skbclthk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jezkainb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asvcnbok.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfkwiml.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnqzhpx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ergzmxrg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmvnnzk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aunfgiyb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzrtlsg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgatcom.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtofwdq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znitvonr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrmhiad.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brvwzhqb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfxzvyk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2laectgdd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtnigz.html


<!-- 参考信息 -->