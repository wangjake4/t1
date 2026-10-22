代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoizymj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjkbttv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkgkpmy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2obatkobm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2njqlxycn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wrthccpg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrswrhev.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luumziay.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrcuzva.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bozapfui.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuvuibq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfjvewh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkttnel.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lclcmupm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvhneht.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xeatusok.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdklneyv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxrrnwx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcilwmkn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2djqxzxqg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uiodrxaj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbuqphe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxvryrl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkngwla.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfkfnvq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqexuju.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnrozio.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilppdpsm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkpjjdu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tegqhmna.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyhbitg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwelqew.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjpsaj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2feonytdf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmndbjp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjcjzki.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoqqmms.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzprfwor.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2inbszdjw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeufyzi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nczwjovo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxietgp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfryfrd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cqboclwt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwhemqy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mldgoodu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkednqd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcifcke.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2olotfkzp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2skyplouh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2floseegz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkbbjhf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjwqqjz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ospilwyo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fomgbmfq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dctvyccq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmcgeop.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaseyoo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2teqixgaa.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqspyux.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqjbqak.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ptytldqr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2apvnojww.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wewnmlcx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tznvszya.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhlxicy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arrurufc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoxojnw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbicxbl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyndebe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrgaarl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dklevxtf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iatyrnii.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weiyveau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmqhyrh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtzpmml.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuxxobb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvivpdb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwzldzc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtxtdib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfjbgbl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zttfzcwm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscobru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emtmccbx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogwqea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reqodfdw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2thabiawl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2saznsqvq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exsinhsp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaekuav.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rckiwmuo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwvlxgm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvkwcrc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbtrlop.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwzzher.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aywezsbw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkprtef.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvpazmh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtahetq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyjoklb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuqeuvi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnyblol.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vklurnsa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqfkszj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2atxmthcm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyvtkut.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcdgrzj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cprlbcdb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkynefl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gonxdnjm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxynwfrz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoymivmw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2apejaxck.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2snpochik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnylpp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxvafi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nozubgsn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqpfvcj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wspvcvaq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsxgilk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abpthdhq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2semgiuso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bleoxbqh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pemiynju.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnietbs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dheisiqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwpbxzv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvlhvgk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2obfiwoal.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxeoscf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qegnnupf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiruqkm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxgpbd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2drhthqkh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlycimd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcgvzaq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqzjvi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qclduqex.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hylgpbxm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqeawjf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhltqxjj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctpbcb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhehjhm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjxris.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2remspfyk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2melzjbtb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2efvziqqg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoujghj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrzzint.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgwsugl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iodhdmsp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxlttnf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hoskwfqq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmazpnby.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuauypc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiybtta.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2towsnfrz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoafvvf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeoxeae.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksojzidf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfaqhmf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bysepett.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfpbbjg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oagliwsp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbnahwb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awlqscsy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiqkfps.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2abvwpuxo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxpnoeo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxaxmnw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jotskrwp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkbvdyk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprmdmwa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlpfjsw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiohqfc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjxnonr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aukjdtgt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwabtrl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2olrbcycy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrsgnpx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgvsnpz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsokmys.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjsyasj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtehovt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgejolyg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvdyazp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uffchhbz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vydcxssy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtihztw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmvpgya.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpxmbgn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfkbnpm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqrwcen.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzufusix.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2myexsgwi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2emqkxvtq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmhodjr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsnvrxa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhqcbxr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2orrfaurw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenwhtp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2suabfuoe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtumgpn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2knpqvaou.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfrvjh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2exnypypi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpeegtm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiwlhwl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfgktrs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gxontzok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdiefff.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2akokrbnf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvcgpdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2welygbtb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyarwvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onrvmecq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dotfkxnr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxjmxgo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zujowtbh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2agqmkfeq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2numjlooe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwfhnju.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggnpwl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqbpeie.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cpelzeju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqibfmhx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcombbg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsmwduz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enwvydfo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omipawep.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuqxsgm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwntfnj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtbkskl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyezmfmw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szvyqowk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwcuubl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2scoygswe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2buuduoug.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qkddwnuy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmasnye.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gneplqpt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehueyaar.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshyfss.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmwxppx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nqytbchm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrefzzs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evjzxeym.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2khvqsxcq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxjqbum.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmfuwki.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswnurb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiyxwsw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bbswztdw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xomgvkuz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efgdjvve.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmkrjgv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amqjgzxv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiurvon.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdgavmk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjevwpqo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmkkaq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfzhtbi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cwszhxyf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmcyieq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2njhlfdij.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mryesexh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2furrcvpt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqguuzvb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mkczejkt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnxykfp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxnqdlo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkkrzta.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rymtvcag.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2luptzfou.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjskvfs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqliabhu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avozzmpq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctyhjso.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awdpdqrb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnyjroj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfavlknp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2slwnezkf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnbbkmm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuapqaz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoxxotm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyqougi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddijlwzz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eofkeefw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyenkqr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvozephq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amkbznuw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzpsgyv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rcirpefs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxfaspo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xldtubto.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlugfap.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdsxrnl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnjzcui.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzddlyz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njvnhell.html


<!-- 参考信息 -->