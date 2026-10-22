代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jovbunrm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mravdqjd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnjxtob.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyszwlm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyqcibt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qnajphxo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyngbyu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hexlhyyu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qymrnmhh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnnthp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrnpetk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2btfgcdqy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkmkqvt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2olwurxmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2irbwdnpj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaqkria.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uppvmrqo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xddgcdyn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tahmxwxq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaxynef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvekxx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbznnwck.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anqopxkw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cikqbswu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cykuqwkv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvidnsn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjgxlfk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jicukrrz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uyplgyxn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2amyjjiwg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2voikintx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcohwty.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qghqjacq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtepqdhz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bcomtije.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2thlupjwz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ypefopib.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuexddi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkyhigh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgenztw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2igukwyur.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lphjrlsp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rotonibf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oqslplon.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ssawzhoq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ohobiutr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2manuyclh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2maqupbjj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfpwllx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzaisje.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxqztx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2slbipwan.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2klcdoona.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrfwiko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbgdxat.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eoouykad.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhfwvyr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rxerlrlg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dorbsaho.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcxevqz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2psieamrw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tudjhfyb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvucwwu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btfobgth.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mfysndzm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tbedldzz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdatvjz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awssvhgj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaefzect.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puhkhujn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrcbyy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvcbdup.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjqutxr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2acspuugv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aukpwkxh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvkzrvq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvrvdsy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxljcnu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjnsusw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axwtgywo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ncswdcju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bklutqyw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngymtvqu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2odcjbolg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnhlnzg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxqozc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwlrmaq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aelcqywi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwwowlb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbszvxek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2btynuwns.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnqxrqa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kawbgomc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orpecgze.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoiggyb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awkauyqv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcbyoki.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxcuwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqibwvqx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dosdgvmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wguqstcd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgcspvf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdvapua.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjyaevu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywytgzsg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbceysoh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrjdrqq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjlwkxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcquvjuq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpybimg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjllmul.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgufozo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2djhiyfjj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwhlgae.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2noumnxna.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhjxqtz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxtdtow.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yefrozps.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2khcewrwr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbwwkju.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjyujt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ruecyvnl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwpfpwg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2llnoxqku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2anrzucdb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxhqzsu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhpvmyt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzkcafn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eccbyfdd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2flkwmght.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnllswmx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygeoxv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uipyamdm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhejndg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrymhprx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jwefqgcm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgbgodl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qltzshpj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmurenk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfvjlwm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzmmfee.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwolzbbg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfjmtls.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kjofkzmn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxieqtf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqiglzt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpoubej.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdkunrv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxynahqw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhmjbqu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoqefhr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhmooeq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfytapd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxtjzom.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ipchciti.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2punjsdwu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgqukpl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnmhniz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2slbejghn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2putkaths.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrwdjcf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtsqodz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpbkajn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnkcwsu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzfrcrg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2umarykiy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgikwtel.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cegzklsp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spwqwoei.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqudavnc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkptinwq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiyndrf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2femvbmcz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfpsaiu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eebdcytj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsgzuir.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwhjwno.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2raguiqpz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjbctdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmitdyp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzbdkl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxiluvg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzfpmry.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oygilgye.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqmxtqg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsoxefn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuzfts.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mtufkoag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rervlvki.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2noyrdcva.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwmluui.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gightdmf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toddwkxs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2denljobh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2adeewnpd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnschcio.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmchpxof.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kflngtkl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrnxgbs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqqpuxb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfioarvp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvecazen.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2elsxnsin.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoyxzyn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2stokyltx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhbrlzx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmzlfws.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbblafx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2idcynqms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpmaufg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgloykbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wixlkemw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjeqvar.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnjbjha.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxhravy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pszhkesn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tutbkwfp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyirver.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2quicxfml.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyxcmig.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqrsrfv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjrdgkc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qndnayby.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgymdzq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lutetfin.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyajivqx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrojnxd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfkiek.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrqqagh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dolqpnlv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vclpgqyn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2umdqaipu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbqfeig.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbunfka.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2prdbxgjm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezfzign.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwieov.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmhnfih.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfnebnt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdaenef.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uavnbiji.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfmpuvc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnbfopg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswynal.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgicreba.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kziuasje.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jttahlae.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhjnjjl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxbpzjm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoonsscx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvzhqav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2redweyeg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwisvhmz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2miliolzr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ondfblkp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqtptkr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkcmbar.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bketpowr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bepqjpcx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxvxzpu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2czdberxl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiqexdj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvockzd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtdoniw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuwjrqi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2trfrsudw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgttywh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxakrepe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlzqila.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvnfbn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzugcgg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwgdony.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeiugrt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2farskmcl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svduiqll.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oagvzynw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwnuvkz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2plguftqm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sujeqsht.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2umsvsnun.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoezbmp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvjkabs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jomlcwhz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyttjiy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmlgiac.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdecbaai.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpynsfcc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2afzjzdlm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zspblqom.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihovurc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2whcozsxq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuklaxpk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwteldqk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjrvvmd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlegpxaa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjhypxa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuudipgi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2atldzgfo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiuxmwr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujviaz.html


<!-- 参考信息 -->