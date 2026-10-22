代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdglngr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxoxmck.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzunxeq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzgylpq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2crrpgwbb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2seunpgqm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adfsrpdc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhxneby.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2baxggrrb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxendzvn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cceafety.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uouiqiqb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpyrkli.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pelgqqqv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyrupqw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2froyexnu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qkamlahj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hczruddd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ussrgcet.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dybinfmw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2luanavnl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dabwpevm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbsakrt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rparublk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kztqwobl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2juimyjni.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gcptqfof.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxeqviq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiyjdyd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvovajyl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yopctvvs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzgtuot.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cionvmcg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yzueleyy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbqobne.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfurtcjh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oahafkti.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zemsntfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexcjgv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlshrjzf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2emmwpxqu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2eyriehah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjjltrp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hofsesln.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mikjhfts.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaklclx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lesuhugr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwrofpa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyynqchf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2omnadass.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puezndwr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnuqspz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2avngvycx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsjdwzf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rynrxcys.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbpczhh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlugkfys.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzymyqbk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yirtvxti.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqymsdfo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2takkbgzu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfeqekk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zchfnpeg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2umcuabcw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxwiqml.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vuitttpz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaclkbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukafnhuu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoxumjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjvsukf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qehdywjm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2osxvovgv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftslfch.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yutcywqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uenamsxf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2teubrgeh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tesoengb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cynzrdxu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2akjykekl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dpapddrd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulwhidy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjfilw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2utzxuvsw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2anpjgwot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gflnwgyv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqbjbaj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vomebmor.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kimziofc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qsudtltg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjglfqd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeyyfeq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2renksedj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaazpug.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tevcrssb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfnmgqx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbrixdb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdxpkj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtrfrtm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsnjrae.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlgrdpd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jriqohmm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyinzgir.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuaihxa.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmdliol.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyudeek.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eueqhliz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2upnlvjqh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvuooxg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxumnoz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cakcbubt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaeofwb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sjynzrtg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgogofte.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btegatlj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjoeywl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrffnph.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxeqzat.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdgcngf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwdmie.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sotlmbnn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdygtvyy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iuokzwuh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2shthvkaz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2didyuger.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwbrhpz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcuskpv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2isizysma.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyvzfob.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsocsbp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mderhacw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwusbaes.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jeljfahm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbzbryz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2twakpywv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2knvjdgvx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psmylvog.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yahteioy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckknmizn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqstuevh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbhhgcc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsbtwhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgzpra.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnrpflk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvxvgux.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkrlsld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfdydyn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnybqka.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tateewfc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2okjkcsni.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2alkrxknd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaywxqh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gybmogjd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfzuodi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxiywdy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ogffsjwd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrquboit.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrkhhxt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cudljdss.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyrrzmw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2losgqlky.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oelbuikf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhsuveu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vnggusvn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owybozwu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2euxvxyrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfyzsno.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sluyxyny.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mddlppia.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrnrxz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfgbzrt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjakkkr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbstxodo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ariiajqw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rccdglci.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aocsqowq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2icifrucu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lchnynzx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvxjimf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcquhqiv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkmgmse.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvjofoo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2robsmkcz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2seuskfjg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzijwvc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptppiea.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2icmqfjxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjghegti.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2snpmrzhv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpxkguj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhgrapd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzceupzt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2faicmmef.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2snewfniq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyijxen.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rytyjnww.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvwvhxx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnynkoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgksyr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yflpsuok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaydxasv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otsvojrk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhofuj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgtyqro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiifvdz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sjepiklk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byrwbdog.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyvdjiq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddebxgiy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjhbozg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2albrfghz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dttjqfsm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxcdcpz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oubhtlhe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeainhad.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnnpbn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqcqey.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvojmzp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oysaojpl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oflvqaah.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2koqgeqjs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zudmbvsx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2naibmdtn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfaryxp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvbecz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2izwhlbdj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcasusc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lutpditq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fppeqpau.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2olajfreg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pymbrocb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2opnqutxt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlndrel.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eduhvsfh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnugqai.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkujing.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gommzfno.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeecplj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldjacjl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avnympuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdelyyyu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqwgdxa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhudviu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwycdhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axcobdgs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiayfbx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfinwle.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcjotce.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwijpu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vkohzyny.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuthsqz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dideaksp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtgjoee.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvhiqop.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dccgxhvf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmorpgw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeqssev.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zsovndbq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdechyuo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwippzs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwunkad.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmnaaln.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oocnwlwe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvygimgq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxrmus.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2olkcqwin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomiitf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbkaacm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xybbvfkk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2drlgwvfb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuygwsh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puhqujbj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpbaotw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrndkiuj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lorwulsl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqocxhib.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eveggkym.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyhuhat.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqerzqhs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmninjio.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kojtogvs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfipqvsq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2itjubyww.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgawtbq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ednlrrcj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbcvgmh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtstsxm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuhxqvb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfimtyqo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpmenvu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzllibue.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tikelhqd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjgrert.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoonzqt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gftsruyf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjzlsc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgtvatg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xurdgtku.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2useosqsv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upfhlzpp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2adrnpzzb.html


<!-- 参考信息 -->