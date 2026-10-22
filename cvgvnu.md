代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2frsmwjwu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uijvewqm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcavxdb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcryysmb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnxpqeu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyweibv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjozwx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2luknoepz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tjileosw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcxwpez.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgtjotd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhleri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odsptpzk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkgbahn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xacplooo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdijqzvt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2znykkppk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kicjblln.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwkdvsu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eklkgvsi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ztldotlg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2azhxcjxi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcymdoeq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkkpra.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2athxwvlq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asisheas.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsuerdp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iybufoto.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xordjjcj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjsydpw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhudyzp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuoemop.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2klyqnxld.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cguruswu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnmzwct.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2axvsyubb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2shqkwqtl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfveehu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iorfkxvr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwevpwy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqbixju.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaufspr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2otumegsr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2avdmelnz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrlcnlx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2siftxald.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztynmzkq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycdgoo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kegliwsv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eupyyczw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ziclikap.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wixgumfq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqhwwrv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmdbjgs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzrdlv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhnrccl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjipszhy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kuncrlbv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gfciqnes.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzullhcn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkibdxxf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwbszoi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eduesgjo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwhokkz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyahzmg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbbawvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qndmnmig.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrjggkr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmorlft.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdaugfr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjgiwgi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qluavcsy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqkigsc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2atkqasop.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iauijxho.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmkocts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gksywdhh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fnerpigb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gtozmxjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kznadqok.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhavjya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fasumxli.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygubje.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uewkvvqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axcygmta.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oiswinmu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnixwuu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfnjukq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyogwzk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lvorsegg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2swpdfzmm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlswhhc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiifilou.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgovuwn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjwvnev.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qidbmppn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzxvffv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kstraose.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2izqgyzhe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tunyqgel.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnbmndw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kgucoxzk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlkvnjb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzhohcm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzopbhar.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2umdzkuox.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzotquk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwitnssr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2etswqovz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mymhsbbc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2egipwvdk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2prvhcatu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwquhkf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihylrdyv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxrwvmb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvtdmyj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjsbbhf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eosppiei.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchikue.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsybegq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wldtadbn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymygkkob.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2szrsewbe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2emyzcjrn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hljlbdxo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2knwniboi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypugaenk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmcmjwn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnwoovf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnarusa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2crctqxgr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2trgmfaeo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iahzgngp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwxrgod.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlxtweb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pebvfapu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aigvfjgv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvogmdfp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhhapro.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaetqka.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmpbsq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtiyylb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdozdlli.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsdrudd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fawzfnby.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqbjsmg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbrtuvq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgijfoqa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2urnamswi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzknenq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfclsolm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtmdkas.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kdooqmdr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxzrpk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpdojrb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgaiaks.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpyurus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjdgnmm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeganed.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqowsfbp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2irxnyzah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpoljts.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlqzlcl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rslcbwog.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fofaxaxe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2erbsuaka.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhhlduo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpntmae.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iktrzafq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2leotrqva.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjexpnrt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dberrdup.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxiyadj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhcabnl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2shffrtgx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyyxgqy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tblfguts.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvrmkzj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsysqqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oioqsrkt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxclsgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzoxvyd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alvquqne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rainbacb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdvjdbu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhicmlu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpibgnlw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2moslxxbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvszvaf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdoquzu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqheoopv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gebdqokj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkmpewi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdhsjwt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhnfkuu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzfczxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrfiyhm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aiudmpiv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2puubtpjd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrjgdqf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rawuubqx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmehujf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2luipagvl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoizbkd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xofjyhwo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuefkni.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2toqcshlm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxcvky.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gitzfzia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xthfwvxd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukesehbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odhbaxtz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrzpprd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whuruboh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2liygqchn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzpkvlt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuidynx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2clhxrdsp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsggscg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjpxksn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbsxbip.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlisffno.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2orereojm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbehoby.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2txywldyi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqtuptk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyrhfw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjhxnhy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgzypzt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqyvgnf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgaapyg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzdzrqy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bivbaooo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeyuzqf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2luvxezwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbadkag.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxejxxg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzuclnh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzhlzc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eucqknzb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbwtfih.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzxzjqv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evlixbem.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptqxup.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnuxwbi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbccaqvc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lopwlurx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdyujhd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpjpghi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdamntsw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhkgchc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nevxfgac.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eehnswzh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2slmrprbk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkcwpqt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcxmavv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrslnxb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfxkkrj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzczieq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gewnnugt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzjnfrp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzqzugo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdiwmwq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkoeyr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2quvshwmn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhwleqd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmdncdx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2icpekwor.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ttimsrfj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhaqtxv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdhmdvh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhdbzxq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjilddv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2trhglbqy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxihwn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qeprkdjn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtjfrnd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jikjieyz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgbnzno.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsxdual.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxwoygx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azygoetg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tundytny.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyloycut.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2abusorqc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrskyel.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqwhymf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zausyidw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhovdud.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2szaaoltn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2udydguqh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2drejgoew.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaluckq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnjpghd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcvenlk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzpibgd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2echufxpk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmtfacw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnjurz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqxpese.html


<!-- 参考信息 -->