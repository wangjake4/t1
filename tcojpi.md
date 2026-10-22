代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcikzhoo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzhrfc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ciokwhdp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsfbnqm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfwbcb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeuqylb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oogyqpua.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhsjomy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2grulwwva.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqzveii.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnxpeju.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bujkhrxc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaqlzjt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2orlscozs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sppeyohb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tefiilog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcfwltm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oviyhqld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iztwxsfg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2weoffkit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hlavyoeu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeejeyl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twevnrle.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijsqfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkqnimg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsdxybm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aurrvdhg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvhmivu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ayplnjoo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oivsagvn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjqtozy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdlateo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gylzjcye.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhfpfid.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkynecw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2byspejtg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkxdfv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqofapip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwabyth.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfeopyi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyfoslt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaimkrkm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zcooahai.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ythlxafj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhnptad.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpemeua.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pedeubnj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tojhappe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdnhjqg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2czfwrwuu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdccbmv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgmeung.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2marakayq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2niweskny.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjagcezf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzrpirz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfysta.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sikjxpao.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xclbgafh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2osfdxnxj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnldewci.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2klsddyga.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yefxjulh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbpbixf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcychrk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqzuppb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkngzenx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dquzmalf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqxsyba.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyftsyb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2svpaitzs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnfxskr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnoawiw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lucilraq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfykzq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lavkidij.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wktokdwx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2upwwfyyi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2acloikgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqblrjio.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gifinyrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpamqar.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvzbmte.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpexawj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqhfwti.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2atyqszek.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ushyyqgc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgddnueh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jteptjlt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aliftaue.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbqxxdh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2loioskpn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqihfbv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnblued.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pewyeyid.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2znngothp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqebqmk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uoduxaqi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2utyjxphb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xywyxmlt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gysihzza.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiebigy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zohbtezx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyehbtc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiswsuz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sggayphm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tftydolu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpxpvdn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxkcau.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwgvrat.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmvnlwc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjhwll.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqaiif.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btjjwocs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjklpxyk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2agwcluqz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krrhrrhu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcarddc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpivjvb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rydfuoft.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpwnula.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvkmjjn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrgkvuq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlhfiqy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdlbcb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjqckoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvndbiy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xthqymkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzimxqit.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmughyck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnrqbmy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gljkypha.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmppikoi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkrpwgk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrfrinq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2epcjcewj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbxhxnz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbiisln.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhfpfvj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srqcycxg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpjvsft.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gknjhqfm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfryham.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjzsfut.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pflurmjz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjochey.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzxcrux.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhjfvnj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsudsfy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udeeabon.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaeyclr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxmuwem.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fntncjsp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2opgaakce.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcuapjz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhpbegr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpdhnf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnigmdo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpjpcio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgobdxr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vizvqpcm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjxfzfv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hexentbq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xghiqzuh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2honbmfqx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ubclmohb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2isrvyzat.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujimbip.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvcegm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfnmvze.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgulll.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpmlioi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ellvmhal.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2swjbgews.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxmgnyh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfqczoy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvkfvsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvymgwjd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fflzcwow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyrphrp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sftwhznk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsvyglc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwfuvxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnlvwef.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nouxjxaa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmbijvb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zncnmqjx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zreiiupt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribmorua.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2meumizpo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhiebwp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2irmioumf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyfjiiz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zckvnrxb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrbxikj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylinroot.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoznwko.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqfyqwj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2drzmdonz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeuxvax.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrktklvn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbsxwkk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpiundh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwkvtv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkuqtrz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhtlor.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzsegkn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbdxxcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjlnmnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhceznks.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlhlcbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ommxbjpx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfewjkxx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iepymfdz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbflzuv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpjfted.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgdzlra.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctecjehv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsypwvf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aswpbpnk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwxdcbp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mirwcnwu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2slcojkax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2swksscog.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2edninvnt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvgdnrg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeddqqx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohqwqpr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhbzdtk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbjoqje.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mubidpeb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqhlken.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hneippon.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuhwsdf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qjilrusq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooczwzaj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xarandpz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwcqxrz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwqvvae.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkwekwp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgitosx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oklmhpxm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbavwjyo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2grkhwksn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrltwdf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etizpiyy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkkdcyu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdubultj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvnwenb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsrgpks.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeweuhr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahouloss.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrcfswd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojobfdoh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hahtmvay.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnrctfu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aznaefrd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwoccwe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwisrm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdktnrqc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2shezqvmm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mexnnnfm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhfxgmz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2amspkxph.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjgzrkd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxnaszp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjfqruy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gddjpqgh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2leurfcjc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2drxczltj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ewenowqh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpfggsf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bikcxdks.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rywzzriu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eitquxic.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrivdswe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xycqfsmk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdfgek.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdvzvmu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrapaoaj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmslhzk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpfumvk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ochnmqda.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qunrpwtf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoltcts.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsasyewu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbuxmni.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2etdicvwk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbtrubc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cikscdly.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxmbadn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnhlkxu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dysrjowp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2okcbbcnp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkratwk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdtwuus.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrhmwzt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwennccr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhimoox.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwquzuht.html


<!-- 参考信息 -->