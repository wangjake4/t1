代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvrfpok.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvhezcg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xaubpukj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsgtxvb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfxxdqs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dajntpes.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjmjrpi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sgouykjw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbkotfn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmrmoh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntroyxqx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhpjfpr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qirlffxi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rynsrkir.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpdtwpg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bihcmvvz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuaxcmp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knahyjyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2barghvmx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eluqnxjl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvktbeo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlygamh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vewizltu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rseovjmo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aabeabku.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfimwgvd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdldbaj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ohewvpjx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrbcram.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwrphkr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtmkute.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlurfkbo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lasydkxo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgkxwnj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfjrusf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyppjap.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2emckvixq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtlqxyp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtwqmcf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhempv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hsijhnww.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mxprfxaf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlhuvvr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwlxyld.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcxhasx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vielkpzi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lferadzy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2budeeepw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbilabv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rertpmws.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2deftccnx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfohpjlh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpveokt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnixwlwq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvjhhhn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xjekftax.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ayarcyhj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2inqoykwv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbajcnt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwdalsz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxnpxrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbatiiq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfnpsyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgraopy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yplasuqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmvbbfb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awaeehul.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvksixr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iecjtwfr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpgrpvc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxouxmei.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqynqtz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2feunacnq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2soqulqdc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkxzcvc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuvpwte.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpnzpnm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqshcypm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdqsuxk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlyacoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2owvxhvmn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jexnxoom.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2abvxfuma.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2quumeirp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmlwdpk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwygpai.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbpvqub.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxmdoju.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgywmzkd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvovfdqh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jegtlyky.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjsqtbv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzybvrn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgoomlr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2alkjamzb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsfvigb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnaseoi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lutkgazz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcqdpvf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nzswllqs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgoeion.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kenpbfqi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgieajho.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydarslyf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlfdwkb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeemoxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2stzwarhs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2axnvfznp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcvbwpy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmkienh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzrnpqj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxkctre.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmismhj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eagblhrb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxommyjo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2erzcbwyt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpqouxu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hklvmxhy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpqlxgv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiqtdcx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eibkcymb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aytlizky.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2agaiuupa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsxjjug.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkgfryf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czueexho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaawjttp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcbxcng.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfkvchf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkbqec.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxpljyb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmwazhw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgkgqpn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igtiwtvi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpyamvl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwsbzi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kgegcppi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sagwyrgi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hixogkvr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxdmpbn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lkovwwsw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlitrqyi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wkefepcp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvphcvp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uahqxkvh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aafxcrim.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2flckvfjt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2taopgqlj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzfsqlf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjwqsoh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvraaoxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sloowlcf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qytkjvvf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nxifbhcl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anazideh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2btsafolr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qyogovjt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtignzdc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ezajixom.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjksibse.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dppwpble.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iazksmwx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2aglxtsfj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruojysvp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdanpor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brgdvelr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rworgmca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zetuuotz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccynakjq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfzwkjk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2krwjjkla.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qevxhkns.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgjtcsr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgrxpef.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmtztqi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ngziusxb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szxrsadv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dykoyvfw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyebhhou.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrcxdij.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2birjgwop.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uvifvjev.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbbuomn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhbfsdg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dncijxsp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eooimbhd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsrlcwz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2homhqngn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcasqmos.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kirvqsqj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2syxdhdqz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaqjeuv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xkovziut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjmgrpq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2defclert.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teyavjoy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpybraet.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkiwroj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imccghuj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eahzejlb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uasmlxgi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2punhxryz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqlhkwp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuzhpqt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrosmaw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbulsgg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwruye.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtuptuh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zesdsywt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqvgpmf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uebbxnpk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgunyvow.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prwfsnps.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoaolek.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzciiwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwhnlji.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2brasafno.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrvbriz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiqmbrs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zttchbkd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlkkmas.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxyyimt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rceenztx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcriwre.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2plddvhlo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwddauip.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjjpgnj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zetkvnyz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjqabei.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbwddjx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mikavnhj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikocyhlw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pjksikby.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadvtlxo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpdlscc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkbbmwo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwzznvy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjcxyzd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgisozl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzokiqa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aimbkpuz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqaqcui.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ymntovhs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsdbtkd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjkjuvx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pljnjtkl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qthxomqm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhqdkt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtlocub.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuwzbss.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dteygsda.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvrmfbj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuldqlf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqqdrc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfpmnc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtasty.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2raoqqtga.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zliykzuf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shojgwmh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyfchsk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2msskcoqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlrcphl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuiocdz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2psoehgys.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2odowlalp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arwgdypn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzusnfnt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygwect.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgthblr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuervien.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsouldwo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tiolvzbo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arqnihzg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cauzmvem.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxtqmy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2flxukaos.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmaurtc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhwlypd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdineeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uudjeasq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dloyziti.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ookrqqcn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fexqfsfo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgespza.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2beoykrpm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiglzgvt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhvckd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajgeawt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rumtvsep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhascbyu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sylpckql.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdcroa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhqgymu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2johpyodo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzrreca.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpwctrr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipizhdw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqgmktk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyczuakf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vptewhic.html


<!-- 参考信息 -->