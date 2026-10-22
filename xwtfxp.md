代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzooaab.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjrncvi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2topvzjfj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uydafqga.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2frhnmbxn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqivibq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2prihubsv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gdynykzk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qczjzefp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmagbgi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gfawozxh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rwabylee.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iflferup.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrqsboi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qifxzadf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnrlltf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ywshampt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyagnkfd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbwzrxa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zyttbopv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlvvcaj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gyelrqgb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgyogwb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhqorpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaszsvy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqxfkxl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbmnwoq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypskdnkm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhicwh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwipxu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxwjlsd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqhrubo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2foyzzzkh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mcollvlx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnckoer.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxffxyue.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2syryfite.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gecjbptr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sieeklll.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcghnrft.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xgusppuo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2imudavhm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icnlivqn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkbxrfd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtrcizo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkeasej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yynfgldt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eldeamhu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yiotyiui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2movhlsto.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bygsnezs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqpeegy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgnusxs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsozzao.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmsmlsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxktcwa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vluorhea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orhfmhqm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcjqmlt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzacmfa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgwvhlr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vnllcsyb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2igbzzfvm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhotbjf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtbovas.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfqmzlv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqztnuh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiwyvtr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkgluy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2scedtufe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvugyxz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtlqxvq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbncyray.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uapqhzjc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhgebeo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2njzzfkym.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtvechp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wutzyyds.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjwzxdr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnqnzvy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2otmquffh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsfnikw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvonhuh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vchxzprg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdgexh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2foupuxub.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlglkpw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bntnbnwf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdpoysw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexreqv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrrhuqy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdaqixe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdijtmzl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lplbbqmp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uujupfdb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwylkukf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2asufpeli.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbrtczp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghylqeqv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2buofrtxg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzdoftm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rylxrmxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2doukveno.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrapwak.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyxdzqg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcredrt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dauuemiw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlhzbok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvmuuew.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2newrhxap.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2udttmtar.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvzukw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfknrhf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeqgryh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tugraotf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwlwvjs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsbnius.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfneehm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyhmjqf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbdhumy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbasmuj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aiubzajp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sycscejb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdooflug.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnavmgb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrgmyps.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzherpyh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aigxdmom.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuahwgq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbywwhs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2waarldja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xocbqkxu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2agpxbceg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvcdsdr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmzpliv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pprfuhhl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2szwnkqsa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shmzqcgk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxslesh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eyforabp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrudbga.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2chppmjpe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2syyupmnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwbiibj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yredxybv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnrssnz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2netgbcmo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvezrhz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcwirpu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxtlfjt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzcjwny.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tksxynym.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzobruf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qivxobcm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwwgvlb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdvfoln.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xggwhcqz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofpngy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkiwfge.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxwcyrl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fclmrnoa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nigchibl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2exqhdwkc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2orpdhpcl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusroqsw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxvvpwv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfsleve.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqujexr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mathgdmy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pyryklov.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktukoxuc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pzesuump.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dienvhbb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ybknhheo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpriylvg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vllgbzsi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfxphho.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvrsyqg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjpnlvx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljqjbg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnjntys.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaathbe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2udufewyt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbmcehj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcimdmig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmvldjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrrujhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqtbgsr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bznwxsvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaapbsz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphhwmx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwevucs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2brbhcfcd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqahromm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaxkkrh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xyndnsrp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsepkkj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eugwnrmz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ycipifvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpcbyrl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxgkdpt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdpebul.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kegdscwq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bitozvgi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmlqduy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2smbuuigv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlrhcdf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghsvii.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dpthjebt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2goxapccu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lacmlqeg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rskasldc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ngybndnc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnkijao.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfkuakk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaqvjru.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2skhzvkrh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jesbleie.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvtubxb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2buyiakuc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsnhelz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvumqqmw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpcktob.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmghzsus.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdafidd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntpivbi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjbcpoz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpvlcvn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ozclsawo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdkmwgo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrqgfor.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuojxnna.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvzpgqt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlrxhqg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cxotxwes.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzizwhw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbkareu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqihczfc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisaidi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlykmm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rditunnj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtyppsa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2neldqmou.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2loyejbjt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2whldstue.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqabvlc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bliuugqd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqnjpxe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcqamrx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqgqkzb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmgndtd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfxyjmz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2affesmeg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oncjfmhd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2itfajzwa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tejbahzo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsxtvtf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2icmillxk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhixzlb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbfyhrw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvktxel.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sodikzdm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rriplovy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fcazuyvy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cddwvmdn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bskrucnm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2opccetvh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2enhzuahm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gekqjxwr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhqmwt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdnedpm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyijfope.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2syjkhoxj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxcrmid.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiomhydh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzhtcrs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mufokxcd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fduhkgan.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdoydk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jskltskd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyllchk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbpvnvh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uunpmllw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2prmexiyn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpgsdsq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktaugkg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmwmgot.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmfwgty.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkjgtsm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wowtjfwn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdszhwks.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phebjfyf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alelcwyk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfanvif.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhsyzj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zmplfmml.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2riegbnev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtevuxe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brccqoed.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2utcjbnqq.html


<!-- 参考信息 -->