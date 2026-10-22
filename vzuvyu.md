代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqxezgy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gatbdhzf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjedflb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sqacwwva.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxmslkm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xmextvmh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqdzkxt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjvcyhj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgyalyn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2acojnpeq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uyalbptj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jeocblig.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfcxmnm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbuersy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuywqse.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2caxttgdt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnnavqn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsoswjn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhyywln.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sleqwdhb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrajit.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlwijrm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apinldzf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2olraxkgi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlulxwn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjtugbx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqghuth.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdmnqdq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2frzrrlch.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvzbirz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjnczxu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kmucupom.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuxjuqp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtgjxip.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnrpvfc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrjqxzi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ybppppzy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suoxpoka.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuvzisy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbamqnq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jurykqow.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vvntrpqr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjgyijo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cobbzfav.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqrgtwy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwvzew.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bnufipwl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhicssml.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2thrngdve.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsvuaia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdixifn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kareblkd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ekufzvtg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsyylbk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2skowqeil.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlmcwoo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rnifqwhu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvhikoi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwrwto.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gejerxvc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwszgtf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqbtyoh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cpehyuva.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2njsgavtl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfafmwza.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2redzbbkb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmixeody.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hfncvdiu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eukaabsz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmukwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgvkeol.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgilfhl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2agkrssvi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nscfappn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vainwung.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwtattc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgcyaxp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzbkcvv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyrpssb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmnpmen.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hazckvrx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmjyztf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2shnaalyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egrrsliz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbqeyek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqtuso.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zffoxvxj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2skyhbwwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nncmjvlv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ijajfppz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2epsbibtx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaiuyeh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pshiwayl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeekfqa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2abvrvexw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuwuikh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfpaikv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kluynvil.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgmllsc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkvllea.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvprrtho.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kqclmhfb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwiwduc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcixaoei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgeapfg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwsiykx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhangeyk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfipwdy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhctjrq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjebzcyp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cchjduui.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmobfgw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuxndsr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2upfidqoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2twxijabs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzscvuk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2koifhtnt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlfukrq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dyokgsxx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2srhxoadm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdeudbd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovficzku.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uolsssub.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbesxzp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrdlmfg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2merlmevq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdjlsms.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaodxzs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhikimal.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjwtafd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sblefmjz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfavwac.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxafuf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjizbqx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ochpzzqp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bihykpwi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kumtmlfw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoufveg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqqxfre.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnqczgd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xllmxzgb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sutcsnuy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyckpud.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvryuob.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrkpuzy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwavmiis.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxtibki.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2awwglzkx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrwtmaf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ngusykxw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhrfoaz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwowrcze.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mtapaipx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zstiboel.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjaidrk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqkiyee.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eqywpkbt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmyzttw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2livtnvqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqyasb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mswhsetv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgaqirq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2myqquiid.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgwooty.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpdwwf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpujlgu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxiorjk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgvgfpf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vknsabjj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdjrkis.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eixivpbp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbiovkn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blxjvbqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oidjsocr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnztuha.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqstzdy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2astrxrwh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaflrlx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vylsgyyk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omdigrpt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvkdidb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddhhai.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkcujwb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkcbzds.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yijpmbgy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acpvhapg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzzwats.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtxshes.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pacvuylr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyukmqd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sldddbmj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2trdjepoo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnqcvck.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vltprzxc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iodgzcqt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxdgdra.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjodphm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiopgai.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2heprccir.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rofebhys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzpkzef.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjazctd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsqqxsn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vihbyqqs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbsuosv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2viavvtut.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtwrfkj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tioqzauz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjdupjf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsliyvk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkghafk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2maevjpyw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrevkuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjkwmru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqktdilu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzygqbq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnibpotx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhozhupg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdccdsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wjggatnl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yrufrsxn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmieylz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbxymq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrmovhe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdwnurf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2knmgveol.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aokdaukw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evtjqwup.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yjitdaxy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuknyxlw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfxkjud.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezklqrvg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2miafcmmc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2etnttffc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zocgswjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcncycoo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tugstyil.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kchcmpdb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrhzaxs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwpqbsr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrqljqn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkktgmz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ombaiggk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2epsnbwla.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2szvtazsl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2irtlxrna.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvjmbbe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwapmejr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxlqrl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjrywnw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzzuozi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnbofhj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hypkcffb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yocgbytg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fltqcxok.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlpropv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfkdyrl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzctbspl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eroihtdo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbkorog.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsitent.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjyrjiq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zoydqltg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbhdjfd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlimono.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvhimzu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kllgwdxe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgncuys.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mioiuetj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gifvasqi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxbawer.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmnloia.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrtizz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsmksax.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wdblgays.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbxnsn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wejhtabs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnofsfdp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiubbab.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjcfiqc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2spvyjwdb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtdxgnl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrpbxms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzjcsko.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuknyki.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbraduzk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdtfths.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2brgkyqxk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2enbulljy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhxjzlf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brlotnzk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iahkwgeq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zglwobsb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yznkspyh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkkelk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjaqunp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pccjfsgt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcbojrs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vigetnjy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbdxzdd.html


<!-- 参考信息 -->