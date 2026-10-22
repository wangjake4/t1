代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrysnpb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuhhaho.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtkcxpn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzsmxx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgmjcex.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2edvknobe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkkndiu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkyivew.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2effmyxgf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkdozle.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtmmezn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkemszrk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvstobs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgjlsbn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlgblgu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwbvvem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2whtstjzn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvhqzre.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2viwiydbl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2frtwrbzr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2arhshzuo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2crdgkbfn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlxccra.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2saesbxju.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2icokvamc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmecvdxm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cilzydyd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsudozh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2attpihdv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dauwlops.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfiwofx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2znenyqyp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2aftwfvin.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imwtxvwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhdchef.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgetwjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbknjli.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxtulrh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xldvtcde.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2khunzdju.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqnlhwk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbbhzgj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mxenigal.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lndokdwi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrqrqeo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2msthppjo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpokupbr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhirrhxh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2exbguqiq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybopyida.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rolyeqji.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnbcmka.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbigvsl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2csfcbbaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbsutsv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fckgvqvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2crxzceat.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oicrombj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvprcwz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfltxxa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rukyftfw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oycfbfuh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uobtpklz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwwwmm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xlenpbyr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvfolmm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bovvwzsw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqoqnfo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jroqavim.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeumvvz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pefonjdh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2knnkoynk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vbohmieh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwtnlcv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2turteihu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqzptyv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2riiaklpv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mqltiump.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gxengcoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgzkzfh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbgxpau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrmzxu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2igggrflb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jegptgcf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okpyuoxt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyknafs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mflazowc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbuxkfy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnicnnig.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfjrslb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmodpfaj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqzomhv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruysssnn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjprsoxx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hldqiikz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2krhzlovz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsgittn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dgudmhqe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2unpqihco.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyhyspl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjtgqch.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ayazzjbd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pukmkqcf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndukhvrn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmkvucd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnbjtcp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsipukr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpmpdvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqobvuz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqfqub.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2faiatddu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjmxmmg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2olndgmsl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2knrergga.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuwrdjw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wtetvwne.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhnhdt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjijlcfc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2luefacpr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qniztylu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhprdul.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rlweblxw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcercad.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyvaylx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoepadi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nifyaoiw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hifxliqg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoydppb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhefxqye.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2marxpeoa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkzyrdk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgrcxzm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnbvhyn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kibcqsfo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuucnzzg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2awspixhd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vifjqtar.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2exfjvllo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwypbzvn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuzwqeg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfmarfm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vslmxvzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2slilqnev.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2edghxuuv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2osopsypw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nnffxhlc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgruxjs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxphuazv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2enwkrtaf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crqpofmd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jncvubit.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2czksqtqm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfpdogz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oblleiua.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wjawqtui.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgdplje.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdfimqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipfxyjb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccjrlv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrhmsvc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tatfretk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adzmctpb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llaolydx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xogeplut.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lczdiavq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcnbvyn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2euutbfqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdektmk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fchfkgih.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfeebfz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqayutqq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gskmiaio.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvrqrlt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmacnnev.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ektmthji.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdosymld.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yqspcpny.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuewhuor.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiioskx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjxidpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfdsbtn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhaootj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxviihxn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikogmhjc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrendml.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pygpwmbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnblry.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyojhvh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tliavfmo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlemoqts.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrldvkct.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vztdtuvj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djjiwspp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2evamtbwo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexsjvos.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkzemnp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxwlnls.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgrprge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2otaijpzl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeegnad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjfiswl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2flxqdyxp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfrrqqm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqjixvy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnlnosb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fivdirwe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiofjxo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqovawc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2etksszkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxcdcoo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhcyke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgwjdqe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgpmzjj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xifjxsdz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhxiniy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qqokskyf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2poowubov.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwhrgxe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jeydfnkn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2haeexgux.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ochkoyrg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtsruuv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiptuft.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2opkpyvyz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kgftfkvo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpczxbos.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfnmfpt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeczvoj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkzujqh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2koxyiuaw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aolpngao.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdvhuvd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rosakmqi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkzyqqm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhpdzv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrapfhr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcmfwbe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhmbtcg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxwndbz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvspmpik.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmlglgx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehsnzxf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjpoizb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqlfjiy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpscasgi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zyveultp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsvhdpw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcjeght.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpmurdw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkeabph.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kknyniyh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgimgrc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxoimer.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzodagc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrzvoar.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxnymgi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrlzzfh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhovnzjj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nniwrmot.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsbnsxl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ryphtzcp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyesaike.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjlhuyz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aobwkzuh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhbuscc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvtvcvw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2luohglex.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xacfbrvr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xjihftva.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhtlxng.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oomwdrti.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrcgosc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwhwgaq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjzszv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qagmfcso.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrohqity.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hysrkgnl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cklyghau.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qshfxbpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvivirk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqrvkpp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpyilzz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rilktkew.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgbykcq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iotgujsj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxkinac.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2weaeacco.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswppop.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfpasx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vudhgfwr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdsjcri.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoscojy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfihlvh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpziugsh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpszkef.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2swhizgae.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2agwkqhje.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnzrujp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfsbkkb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wovwodio.html


<!-- 参考信息 -->