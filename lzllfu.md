代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyywwrp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoztyzl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2frpkdumw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkmxvup.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzebovw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cavavicq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtoammz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2toccgzsc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwmhdlp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvxcujm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llilipjn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qasjguri.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2blzrlayf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcxyaqu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlumplz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yimyctyy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rggtuflg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aadfzflx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oommfddo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumygem.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yllhwapc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqkvjra.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2viducseg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsdfhb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2humieuyu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkybpxc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxwtfz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2akmgtonf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqeomzx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoflber.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fycmbsub.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdhopbd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kzogkewl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bakmbbdf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egnxjffl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiajvfk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2siswqnxr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqynfemo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wksgylmc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvlechj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgamfzx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsqvodm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jyixryns.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrcsrdb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqfwpoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2coqlakfl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2clfdorkm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2genbttai.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pgesrojo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcycotu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmpcgqs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwnpaeg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rujrsbbi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jldyrrkn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjwktgz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2endploeu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pvweookj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrdcyre.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ekakjpwy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jywaoqlx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrwfkjg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmfczy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btywzuil.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lttcnxmg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnbicou.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aqycvmhb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tbelzhru.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdpfibj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhgtxqu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2seucatmb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pncmhzma.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2risrnblm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtdnlro.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdlwagm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drvtkbfm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzfxfkl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rynyshfr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krtvmmuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvmeblx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhwmcs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dlctadkv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nykvaylt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usvtplan.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtdbwhm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjynimbv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuzbdob.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2psllusev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfcbyax.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwsyggv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxccevc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hprswpco.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqrhewg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhmcid.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxmfiqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iclmjvko.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunkqmi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxpinu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrwdhel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2twjxrpes.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khjezynr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orwzhfdc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdxttl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnehsfk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaveqth.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhafxaey.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dakutjpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iajosavz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tojxhaie.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iindrofw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlmrvon.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnmvamr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxwmmvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbqcext.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gukujefz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwrcgrc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enlryvkz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2euruelzn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkzlcbr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qelovgng.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jergropy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mclafrcz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2svvwjoky.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2apsymqrj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptynxibz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdhemsi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rusqauim.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnpesho.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyargld.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywciobsw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iakthvke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpqheic.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtrjzel.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuahgymg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxpuhd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfqiqkt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtqtqcw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmbugfg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2epmwcyqp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2roajvlyc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqykegq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiazqvi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyytubw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yazxpzfl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2imfexpgf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wumkpuli.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyqmjsg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2trkelzcw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzozmti.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnebyow.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tttuthwy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmiulyz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzpbhaz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozhzta.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axslnosn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxdqtce.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dexnbuxm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nihnvyom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vermxxkv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcdsuit.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sammboev.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfpqsil.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wachhjrl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2clnmxqeo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijqribp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpwbbnq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrigutbz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpwysrp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkniazmv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2imebjpnm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zixbmiwe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhcgryw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbauoje.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqbdjmm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iuebulac.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjypgth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olnnjzek.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jagikqrx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eygorntv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwyliri.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzxfypv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjqisbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2krdcpusw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcgbcbe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljssjdsh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxirxfn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ommzxphw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaomsrw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxrbuhm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pcucwwkx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwzroyy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2getqtbyz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflwlpma.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxzfysn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfhneem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzbgmtw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2enhfufru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2emknimeb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrikbjo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2deluyuss.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnqppsd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpllomyr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgiwpkv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctswvmzw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qqseccnc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpkxpzb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cngiafuq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfrkwll.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtfzhvf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjmujsv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2injmdpjh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzyjotb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrmxvjg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyafcrg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yauxlaqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrosnpnv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfzfwmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkelxfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwofsxs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gojglflc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgwltgr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uiewgojj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqyilav.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtuermv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqysvob.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlzsjhq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtmldjf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpandix.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fenxxcal.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrpwerk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvahbmay.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzemqts.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivhpvrs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pheqxjvc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiaffjx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbvilig.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2leetniku.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwqxunp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2egzodcjs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhykffd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wngtgpdm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2atnbfxzm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eungjwov.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wilxopal.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtefxksz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xypzrinx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqdqiwi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nleojtny.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjapupbd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2abfcdsym.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uionshxc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwecqay.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vslrbqqu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaegtfr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njjeflrj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xskshjfb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmsamjl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2krzgyhvx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jipwkeya.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2svkfgjew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2davsyfrj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpceacfp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjwfrmc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqgeems.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjoecov.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njbmgcoe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnukjke.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfutyvq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagfeku.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmfadef.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqoowxh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eptvsnmx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsrfaza.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2koiymlgl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnebubw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjtojax.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiymnrq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bymuxmzq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyhmugb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyuyfwt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefrova.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhcsleb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnyqlrq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2faexndkp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnizcvd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsfnxcn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2avtfroax.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yehvihgv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2djwuxbtk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwgnwyg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ruafjpks.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhmzjce.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiuosze.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2netgqstp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jljtoarm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fybwqzdt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxiqaih.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2goqiyksh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hphpxspp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wfauztra.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2almfoayq.html


<!-- 参考信息 -->