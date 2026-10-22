代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqsufd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2klintjti.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwjcjmx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgnplwp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2skcjscst.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghmsjc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vatnzwkj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfltyfc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsjkyli.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fukzdjcw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxtbymu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdzuyw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fccnrksb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2imbfyuqh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qzljcdix.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mmippgwv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxeglq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjbjczw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoztoiw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xswejkip.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qshksmvo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwattwgw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2spopaeio.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gthcrhtv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yucifolz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxtvdne.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrggmtb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfvuwkc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtwkimh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhgqkji.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyyaurv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvjcdhv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nudswfhp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwkviqb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kbclzcwr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjibonz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sksycldy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmwujdp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzomjon.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmddxam.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fkanftll.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkrcavu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrgsend.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fluqsqpa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzzaszo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfmjclc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvmvrgj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rttebnzr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlryxtu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzemmly.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvjcfve.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuscadye.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbatyota.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlidqkqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgvpija.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jerowtol.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ipindnon.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaevhtd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxepair.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxwjewn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbioozqi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bosjhkyf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvukvyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetmubi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2inazaigj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joqrpyzw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzydnkg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaqucw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhgvqg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vembbsfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsexkuqn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvajdkr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiixahrh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2erbsweww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tldxppgw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muwjezdk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdvazyv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhllahn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2idkyggvr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akdqawbv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fahytxrp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeugsvz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsshrqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrvnylt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqqzzhf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwionuua.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmjxjpk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwoxppr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wytbgxrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aanxweyh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvdguwy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moexzwzt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgfwoxr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irhekzrd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjplljdz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yskoqzrv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2navxdlbs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkevopk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhylhnan.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxbbvat.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucgtngk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbojtmqq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmshmbr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuesodw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lttzijno.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hiebjbex.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aisqffll.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2unxnuxkf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodqyqb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvomefo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvaeyl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgefum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaywxdd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2frloynkq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacdkol.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwrjdj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsvbqrw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oorocokn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwlnmtu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrwuovu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgozibx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfdmyrr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2unurlyjj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neopioys.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qspgjomk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkyhih.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvzosjs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjthowz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2srynavbw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ngosxcvk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xnshwxdd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uigdewji.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgckpex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwweiga.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmphkkl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eroawmrp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2esqxkths.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgswkfkt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbjnan.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygssfshk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpzrkww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxujwzwu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cwveisbj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tymhgelz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgowokm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfdlrfl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfskcuyk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqavicts.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2poychyak.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaejgxv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icrgdqxp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfelbytm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpreiuoe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzisyum.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyzybrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrzpwr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2flkrjahj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2otoofmvp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgfbown.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdkgns.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pzulkhuv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lahyzzon.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxdvag.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuitcbt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rppgbhyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsygejb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjcmfqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcidgmz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivytfxar.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqavdcq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhsdnyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vviaxccz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfqvwoo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjjuttv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzbxxzf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2luhbcepi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmknvaso.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lolksrim.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlfeved.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbyrhbn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgqxxhx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xljnufdi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvuzoz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmrcdsk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csddjhkv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwalwuf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoldtuj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nukhoxiw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fubvrlax.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkrirrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2agynjlzz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpbujtc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2samrzlfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmsbih.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vktjqxum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otjcwmgo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnaxpiv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpgnivc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2newcstai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjatesh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hlychvuh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fihotvca.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbmodwk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcaukyy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2podsaivk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvsctty.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvewob.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlkfdiy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjntdss.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqcopkr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmifxzxq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzrkbbh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbqlzfc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pguvdkzs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ertnagcn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmemxkys.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjylujb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbclxa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bhftjirb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfexubr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtcjyfh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdxrxgb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdvmcgc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsujmjy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2opinjtcg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeknxee.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omrzkyzo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2efcqetkn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmadik.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeijsgq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejggtwrg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqpavlv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dybaddjp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2abtqhzjq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pgduiafn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujkhxxa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsesyrlt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2halhulwf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkakybb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhltncmr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iongdtcl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvlsaby.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2asxinvlu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwymvnkk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jzglxqmv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iryreewt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fedmvxfq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2codsxvdv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrftzaj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qokmsftr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2knfjakpu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwnlie.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmimeub.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwtqcbw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2loqncwlp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzjvhab.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zflcgifa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhqclx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fglcxdik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2robvoykx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fybasanq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qvftfrwh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwvqewr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvelbx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqevmrg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpknnrra.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zingyknm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sypegwdi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuxdiki.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwdgdcj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwqjpwk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaiovgm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfrqdih.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uycivqlk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpctgrk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsxjoes.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzmavbe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfszcrqf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbscpbj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ettwbxow.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnddzhne.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vccrqhzx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiwlcqu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvwnbzd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2udtzrnju.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplgqssj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjuepqj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nextldrv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qfupyihf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtkriur.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsttncvu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusszxtg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2entxfjaw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyeyqzr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeetztq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhtbzjj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rouzptua.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quilvyvi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcrctys.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rutggtjd.html


<!-- 参考信息 -->