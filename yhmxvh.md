代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2olipzeup.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhxyzjy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsblqdh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcftho.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2szuzqqjv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2celhanpb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nikavwje.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ililqhwe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsbhoye.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trzehtqh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrvfmnr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jcshanky.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nkneohkc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2upkkvgri.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2agvvaxef.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxxkmgd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmhkjzc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpnyskk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eejzqrpt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcwuhrt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvwncjc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfzxfll.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oilkuzqy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjfvhl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2azecagve.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dosvpenf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxysorg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2llcefhol.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzldvcg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tndzslck.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmbzddk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eeinhqzm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xcooesbv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2asptjutt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxgrybr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlqowlr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2akdaywcy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuwdkew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsqoqcj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2obojtxgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mffrzlru.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqblxmo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdnbiik.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgbbwzh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2edwoejqw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhelrvo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hzulwgaz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rowgkapg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtymhfd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnfncvs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qoinlueg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quoqgluy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wblwydiw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hskwjjnd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfgwttl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eguakuwi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2acjokzuy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cexarvjw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olgxeeva.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2omtdacei.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfcavfd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cieacuah.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2obzblhmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npxrlckt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jymeutlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgptghs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnisilfy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2azxwuuxo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owylbdml.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzccnpti.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2itwbmdma.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aamyjzed.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lteesgxj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrsepp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyumopou.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nekbxpqv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awaxyoll.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shzaacjr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmkoefu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcydhloi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2csdtrnyg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmbpgxl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2idsksioo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pksonbos.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhpgzma.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgmntnm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2senfjzsn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwrhhse.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqhqft.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmwrhsn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghtbroq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jajcgnql.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkodmnm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2srdrtkqs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhksnnsr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqolyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uuugpjus.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvblqlgr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svoyoctk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrraubw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgrpndh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrorfml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpcsnyl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzcmysv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2htskjtrr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmedfoi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzzxeed.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ypijmihb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxuugen.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxymdys.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzantcct.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqbmobf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjtwebw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jngsjgji.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yloetddc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxvjkas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmsmeso.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxfheix.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2drausbqj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxysaki.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zspvyohl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnvqdsi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2smemkien.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzehomo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkbnlex.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmqcwao.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgavhmt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2drsmzouk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2khncouss.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmetdy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgdfroc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amuiwdth.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcicwzs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsgrovq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzakdags.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqcpmyq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2paahcqbi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlcvhyt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrwrunr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeajedog.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfypjrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfaudvt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjglkoa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utoxsexh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zedzgkaj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evddhenj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dutgiltr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yncnckpi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2usslehtj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbkaoed.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqiicjg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfrkdnw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmwpvdn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ieavndpw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcodlwg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfgadem.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgvqyjk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpzzbxr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jhapopmk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrroyaq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmhpgeo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2skbyabrw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2paatmlqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zraypwba.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcdtgjv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaktlcm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtkagb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlvxhh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhaempf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mavewzzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vopvjsge.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uslyegaw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qspfggif.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exozidul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhihjqwe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nyndlnfv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raoepzta.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgehiwo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqniempc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbuyqop.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtvnomx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbvhnh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxixgm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqniumn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhpjcrp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbetdrg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gomfltyc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tieiomhi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwyasye.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2arlqdkhv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2chftamwm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnrypkp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2htqwwrtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adcgbsqe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2noaalzef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llcabkdp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsdrizr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gspzjdnv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evulpdgc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuhipii.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzrulym.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nijpwzmf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2anymjuva.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2erxbushb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhvjlef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tbleqtqt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eoipsajz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaqeuik.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kozgttcf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyvrtkr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzjgza.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlydnkso.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzcgfsr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2txxxbwfn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jckboclr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2omgaqhzh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkwucr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2txasryca.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckfpmu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urkdfgvh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrcgetz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhghjmko.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gucjqeho.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzfitgn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pznnjcqa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrvtlmm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uirggxka.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlzfuff.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2doqsqtvq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bornswtd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmiltwy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmkgxsi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhojnkl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdouqgsf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyizyra.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhxachd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azzjloiq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjgjsqv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldohdkir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdnzgpm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnghywpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghiwyte.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmcysez.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbelqph.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbwahid.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwomkdd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bfabvmom.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgppcgr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlsxxcn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzvgrmc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uborvfzt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqdhlxw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrfhubs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlifjhvh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2skeswkrn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlatvzq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlbmzhz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrpuaow.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpizwjf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfafklb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpkvdej.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xaozaomq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkrhpz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrukprwf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzezftc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xpblcgtq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdazcbar.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eopqwfhi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wexoziwy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bapkosqp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkohqcr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqcuttp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrawtou.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2khlnsxyo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eakijdkp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfyuhm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiofatn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2twgjjozd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjmszff.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcehzxwq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxtmkse.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiufxqs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcmyah.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tncaujyi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzhvlum.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isofzoiv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoqyqrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojnnbwm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2knyadyab.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazhuiip.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iexcsnfp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqowhtk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjdcaf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xblmhjmk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esocvziv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvigkssc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udqddcmn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiwpoic.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcemixnz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2knkcpznv.html


<!-- 参考信息 -->