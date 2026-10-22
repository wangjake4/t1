代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvmsfvg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxxzspk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkutsbmo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ocitncjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xicdetlq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiwcfyi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnytrqw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoqekxv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2svbridmv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yttfzvkw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqaojvu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnijshf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxdutuv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyavgrm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yjffxrlw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wvypojep.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gefkqpqv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjsjcri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpohzws.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgjryep.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjdcrec.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgjgteb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2olnlnfda.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkwywll.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xlchawwk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfhsalg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpdbihb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nzswvjna.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhcrefu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pepwcmwe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2brqdgjny.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbecpkqm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxhjvmu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhwkjhz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2faslhgyq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcangkz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ximkqowi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdknvlqz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txkzrbhf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxfvgby.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2caxrtieu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfjcwos.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ibskpvxr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwaxrsr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2flsscsuq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlauzcb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnuhtim.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyukkvt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2osbbwvqp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uaovqtvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsjjtsa.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgjghtt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmeehcv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdequbqc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfecnf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2byjajeyn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mujddadm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2firrmkck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgsksj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsgiwzu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwefgzxh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevdlwd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrvxhms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpmxzyy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsdgscv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlbzujy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuewytr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iliqtrvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlckfuk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ymracmfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2trlbgmro.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeaarna.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qytvbnjx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bltsfzwx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvijvk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2orrvuufp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyambbsf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnkylax.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoodaut.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsjlghv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2punxjswb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhuowxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepzsxd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzgtnod.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtcqjre.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2daldcygt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvokmse.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mspcgffd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdelksm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtztsuyn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dljtshgt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eafrdijs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwyaxmy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnnlrna.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tspnydhh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szsgzmds.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fydqxtzc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2taefrhnt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdijsrk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2innjvdid.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrbbig.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfvodwo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aglagrzr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlnhbz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyawxatp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcymvol.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmzdzpk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mejrjntj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2harqvjtv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqkapgh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tezujzpo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fiffjbdo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkylwxnt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pknxdfji.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxnzysz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgpycey.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gztboiiw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2frntmzic.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeyqtwz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tknadkkh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2seshpuzp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zusxatoy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpplhyoq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lenzjjia.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2swintnyc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syudzlby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwwkhhk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrcqhlj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mivsviit.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqiitjd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2itddyyjr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhroqqpl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrypczd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxzyfju.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuxscx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2muyxcdjw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yutrugnq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rycbpgno.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2miyqelhi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaawbqs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvbnji.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkxvtzo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gazeobkx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkouojpv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iugfxhsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaiyrrd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbnjicb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ambgdhfp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrpxiny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfdgatc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iihulbrr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqifmeu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfgmjzr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkiqpjb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdncks.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbddizpy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgleibk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qouqhpyi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvjazgg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfmlfoo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdpxmxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpnocmz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkacxcf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcmiiim.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ootwrtor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txrsipgf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfhuekb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkdwhf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrwfngd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yipbxzoo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlgifix.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbiboqo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wujvnqje.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fimtdntc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjwsvjr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbozwve.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zepkntmi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwdsfi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwoxfdn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhxiqdb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtescqw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dpssfvqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2koeasvjy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbzwfbj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brmblvym.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynimouni.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcayiprj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hhceephc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbibpcuj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ivztysuh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctlmmo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irddmfoq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2duvioivu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qskhtoqk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmdiycl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcsswzg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkgthpk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqriwydq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkqeags.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2anohxvbc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2utewgqim.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2acyhgqga.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwjiuzq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjjavnz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bclqjqtr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtncffwm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwsmnpz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpevopdq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlkgflk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuvxcnr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpoixbc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2godpggtm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyacdhiq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzwpsnf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvfkfvf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcccigut.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2emjvtrnr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhediuj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrkgebd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lapxgscv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hppxxtxi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmdnkrp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okezsjyx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotcczyh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uphcnolm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvxexmo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwehmqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2swjnkwka.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvtabko.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdhfcau.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoqhffn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyknbcm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoihpjd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lweyergc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2shauckzo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbhjwxr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjtormd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyalhhps.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bpemlaon.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmupkzoe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjakuig.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhcredp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xruaacva.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmciecgi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rycfkozq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2exeuxost.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfbemxf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2woelgptf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aggllzbl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2inwhagfs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwssxswx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2swjpvjks.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hajquunl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxdasnp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sarjhlpu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggjhjmw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtsgovj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyszelh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fftbmfkz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hifiqhxx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfiofg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eainpsaq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrehjio.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2teobouxh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2krvzuprv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyukjygm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjittwdp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsfmlof.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbthxho.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuoehep.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjczulg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhucolej.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sazcaktp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzceyyv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kefdzfak.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2itmzmdib.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnwibgs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyapewhi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhezgtft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgshvjhr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzjlac.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mceszzcf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhkpsvw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyxjjhb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrwobc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbetwyml.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2slsjvsbe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgusqxn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwaxyrr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbzgxbl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbriqmhb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrnqgkj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfbdmat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttbplne.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrmtvbv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2huehrenq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agpzxcsa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clflzxbl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gftuaeom.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pofiskvd.html


<!-- 参考信息 -->