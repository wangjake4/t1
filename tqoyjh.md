代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2coqgvpzm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxtufqq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2epgiyjth.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxiavuv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdpwhul.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xavqlgko.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zsklrefi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcfywkh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxyohiu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsvokyo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgstvrma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sexnfbea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2prxsjpqz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzaqwbl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzymiwbp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cyahyuuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaapydt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awpsnkpl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkpermc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2csnfrzhm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwooiqt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xieccoph.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2misesauo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nxykmjdw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zyznzxxf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mykdpovh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbckxp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxbqdzo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tjztytst.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2klhbdksq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2scynyjql.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ectnvwwt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrpoesa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdzdtvb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2stwddvlx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhchxqn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiofhlg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqilbvve.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2motaraoi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzfbvun.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2srnstykg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndooxzjp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcsejej.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2myxaygut.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irnfpvpd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2acvhpeev.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbtupca.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxtzens.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuazlmp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2crybmuar.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2svwtdvyc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyschep.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqikeqfq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgqpfcc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjwunrt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuskfyq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aircbtqs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xitjehcc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwybyawo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiadoea.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2skopdsql.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpdgcjt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhslaa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkwanhc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmryobf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2aswjyqrr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxwgbd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjsyvud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgajhzv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkfatym.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjafqep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imzllcmo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdzifc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlxgdrz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wznmaoiz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yeihbqed.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgslts.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hknhnyaf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcfjudn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bipjggjj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bynfxepp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oopoqbfa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kozmlmyi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igzzffpa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjlgkk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsspgetg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zfupsvgt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcxsulc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2przcrxdr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fizwrabk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2thweqhms.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lhchunyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rztcrmbp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbamwcg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqorviki.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhqjdoq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnlyvra.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxbkeaf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bamdrsuq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdmfheu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzdvphp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvziiyfj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfscukje.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmipogr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmqfdj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpfvwlz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzejcbrb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2memibrxa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtsxvve.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyfpqxg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2enicegcc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaruohy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuspobe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfzoybi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmogqkk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mcryjijn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxsdogx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqdibtx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2drvtevzj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sckqoaxu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2klidtnin.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrjxij.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvqoeh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrtocor.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lissskfl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hacntsli.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmbofcx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuojzay.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlontlfr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvavxa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeugwwp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkshfxdb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2linzwbvc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhlggob.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2swgnzfow.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2czjgthwb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdqlgti.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wriudjzu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwzlbua.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flzacoph.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkccww.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mybmznwz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgzxarh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2joncxnxo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zggcjnfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlycmow.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhxshc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwkypir.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvzpbeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawkxbyz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ahauuzhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puguunsq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqzekvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iukezrjn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iakkjyol.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfudqos.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaebxtq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvjxcbq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtpyicf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nycfaefg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxnmhrf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cphwnjkk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piqqkedt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoslbsd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zojwyjol.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpyvuvo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfiwsxa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfftchn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qulzjdfv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqogakl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjcvkwu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexyepk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hyydizdu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idxhlvfh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzqjnhr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqovinxw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiddpdk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtdoubu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcujuii.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uryeonko.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjgqdxb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utgfjrho.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxdqmzi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ycddwtsr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqeutob.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwcfork.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrghcewd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpohqiig.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2alvsqzra.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nrspwznx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyswyahq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2optyowqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdmynhd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aybcqmyl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvypknmb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpjmwhk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjcnbyk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpdwptd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqadnwfy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrigkdh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2coyruuht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zihemolx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgullot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsgzzxe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uswwaefz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zebzcjkg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzducbi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nodzxcny.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbwlcpo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rujdiqkt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2paylqlty.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vurkskyz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jqehyizk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sppcytsr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlnmtbq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvlqasg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qdobskuf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdizcqwj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2khnrhnfi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2beoztkfe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2decfjjoy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmyvfmt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ollvfwlb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkkgfro.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjxzuqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzfwdsu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjitrcz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdebvuzt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2obrmwges.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxtsljr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zcskorwt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xchytblc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcfygjt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egcaoigz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eioklvjm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvohsgf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2suivuzui.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxbksio.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqgupdh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2znisybhs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ffejyluo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pufvpzph.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqnlcbn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2syxsvmpk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sosujkqo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtzrvkc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwmbag.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tupdjsva.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjsukag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2epedzafl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqveha.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtehkwyy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnizoow.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hittxoxn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jobirxqa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjpwmvb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hooeetpe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkzbnrx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnvptnx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rleeolua.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2srshcrcm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyddawm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pmohbfkn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiqpyzh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2herkdppc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfankpu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2virweewh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bswbxeng.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaqjqlp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fthdcyns.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuvjuid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2otcqwqqr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xidscovq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iavceeyw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sicxihqs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rclnkzxe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhkedxh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2puofgzka.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2btituyto.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuenceo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xejcrrws.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2npyeqaaq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiowfsn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmduhxj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eojaazae.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcogmpui.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgaghhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2othpnlkq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfjdqxk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkesvccd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojetlacw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpihkcdm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvusoiln.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqokybml.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbuxvlx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgjnbgu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhzfjwu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tioydidf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agponnlw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdmhivf.html


<!-- 参考信息 -->