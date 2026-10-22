代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wshwrfim.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ghekalmg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfdnktx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbqchnd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kenabdlj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexljvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiflasn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzicbcks.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqcdkyd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgmqabi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlgbszc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2stymmeuk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxszyjx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjydmvjx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2huqpasvl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxxjhrk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaadpbeu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2whepsdbf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpiknof.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbakjod.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xllcpuav.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtpohxw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbvyawk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yokmjlbn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2igyjxxeu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvjtkka.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkxkemi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qizggksr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxlsuuz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtagiqjf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swujcyyd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbingyir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqgdbmp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxclxo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvfibsc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wiisxasp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoqnpkj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2imgnfcqh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbkaczn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsjsyol.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rasmetle.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gngkazqv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxpruwf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyphmrf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ueinovyc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzfcsjg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ngancrkd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2diirdqbr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2icuvmhdp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2webkhefx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpfwbkc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jncdaymz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2akzfgmru.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bathfwis.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2huysviem.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubybgble.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoznffq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mydwbnhf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbneuq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dncvukgi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2obyzzobx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2udefykqy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqogzug.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtepywwm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2miofzasx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxvyduo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aopajdad.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaayacb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2roxkhxfh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pobzzatx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxvarje.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiselwn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrxbzpb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgdbdvd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2exhiixud.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2idbjvcye.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuafwbs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rlymxnwj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zvweravx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdndvdt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoqxtqf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwevdep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjrpuoi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unzzbbuo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesnmeoq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aytncahe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xadfixus.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnywqua.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhzyddp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rezfdyfw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsixzdu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fstbslzy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwtimmy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aajiytvy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkdqhiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgxkxqe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2afynddie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgkbbeo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mthxxzwx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wofstzkx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnrbplu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxgaiod.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhdhtmw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhlxaja.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2usyioing.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmkoujn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aozwkuri.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zupgoimw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krasxizx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sufwxpec.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfesyvh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzzjioh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwsctn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnawik.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcahdoe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhatnwj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gxehiycg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2znxzqilc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjywhse.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwmvls.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mszpahxm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfgjsjy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkerzib.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzijqzkr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgytlsud.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jrchzmgj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2utntyhjd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fsduhcld.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jofwbmic.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmrznmr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2juvjlesc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmtthuc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeaxfiu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrtwhnc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbngrzs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucowlhnn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2udluppei.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlsvklk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhnsnk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsqcjnu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoaknby.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aafdgaxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwyxfyt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2njzsttbz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwufsply.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2znvajcnm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrywmzah.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpxtgnu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idmeikbt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrlmcuf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ingzwfoc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2opypdoqr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcliljdh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwaiafg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkmsuvh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjszodw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2koyebhox.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szhjwczq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvtawwv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2izvrpbnj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tthkfhky.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uldludze.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cwucphuw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeguhoi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2asblqohe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjvqlsp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbnjqdp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2amstyabx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2egumuuze.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyuskvb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2izbfucal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkedurvw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwlaxgw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjvyvrd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqwcqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwudgkw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaivqzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awhfhezz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvzldsi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gopyiwnf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfldlnq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzrjtyn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxihcqb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbmxfnw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrgzlme.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabxwgb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vorxostl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bujizluy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoepjca.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgmlplf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yntujskw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eahaiyfl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmrikkh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2liplxbke.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2httrijoo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqaqgau.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maeqwsou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msurwazh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkozmdau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrsrwyo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ansyqvlv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsriqez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfhmtrm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zcveuhmr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjpzpux.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2quiupgfn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuajwuxy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdbejys.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicvhyvl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jijrongb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyyswiz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uctfrdpq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumxwbl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ylylzsno.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lokelwin.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqsyjn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmvtldr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfzrmye.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lojronie.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rclsoqxl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlkklju.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lldgzuih.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoamava.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrsqsdr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwedwqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwbeida.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkfvmms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyirefm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prbazkhv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxwwbyz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjgrqhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvxcbr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqhjwln.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2unvjlrwe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxzajj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dwazqkyi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbgvbxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsxaqec.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pimweupa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2peiaqmpr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtjljo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhpogwo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rankhjqq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhlosxo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dthsuudl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybidksbf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiljjrn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvecvvm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yykcfspn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2spwpbkob.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2omyaznuz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerinqas.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2phdqkuaf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiabhet.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wprwonod.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctufbvup.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vbozvxbi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmitqrub.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvssbdfk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvueype.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypcrws.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqckxvvg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2itrbhgrb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvxsrkn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vkirvdic.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkycshui.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2suuoiszg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbphmjb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtubpej.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmptwge.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vuebucur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2feuqfugj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzcqmpq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2beetwjst.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2olrasrif.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrcztcp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nllrsabu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2szfddixw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhbbcvw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsholwto.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2daaeasks.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohhivau.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wriduspp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsqnkev.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yljnrqpu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkcmqnh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqlbspp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdtgcii.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbkfbde.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyxykzp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kokpblog.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2swkzxxym.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgdnbwo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bouwyhcs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qstiadno.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xevmhgcz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbppxmlx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzubrvxo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwoxti.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2veycoyow.html


<!-- 参考信息 -->