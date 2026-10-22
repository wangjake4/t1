代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnixjbdl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdrthcf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsnkbjt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuczxxd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhwzvun.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2urwsoqit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yojlxlfk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yyftteib.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sygkicck.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujivkcod.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeusdiv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhjzqg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgebtlmt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtxwiin.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tueimpos.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttreasrp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lezvhwnq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2khntrlkv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eeheetnh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2btoftilo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbfpea.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2odapflhh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jratkwzq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qljtztoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qatttlly.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjdxlbo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddymhlir.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrbscik.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nusziymj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2abomcfja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbjbxfy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wagymjpa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vywcunce.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ounljawe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agfnqgzy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mecuqqbt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oqetknsv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwxsumg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nebobkre.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnatqyc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvzzlzv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxvxuwn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsbjmsm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkdrzhu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkncqsm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnywtg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkilfci.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xpangqsd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvkqvfb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dixtmzhk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nqseiuvv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tgclgnhf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2trqpkxxf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnvtpaf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rndmmbiq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iricabkh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjfosv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2owoyzler.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgziokzy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gewovchi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nlccehem.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsejpkc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxutap.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lffinttc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mdupwplq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhzzpqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeatahd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tntewjbc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfaeuhk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lqibbeek.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsitqrr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qiltpskh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2znaisecs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yviewxab.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjizfbmk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsefsza.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzglvtd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2epoxangc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oszutpoy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iutmzzye.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zivhozjf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yynourkv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfpdegh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpuecof.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdyxtqx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xerjywvq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwezkgq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgafxzd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amptyske.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuizvpd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkhnvoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufchxomm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mruktxry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkgghgq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzcjypd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yyywjgyl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcolyqa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxxacgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmuyipb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgnwfod.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dntbkedt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hikehhnq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eowvxvtt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgykrclm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezowota.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ctffaugq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqwjsug.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpixcyf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pejrwrpn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfflzel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqlycma.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bokdyfig.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2noucbbfd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoojpnf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzjwxaq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndidurwp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kemjqden.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdfpgal.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdboyzpv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkyjihd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwernkik.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dndhcnjt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjejftsp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyssttmv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmwkcqv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfvkffx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2deyqsuzk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2blmmgpad.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnvnxa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyucvna.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dteahfxy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xilgsumy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlvezau.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrlvntx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2adzrvdid.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nwstgffc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvettwte.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfainrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2buuzzccq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2veirwlfi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hobxsqal.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gphziubz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rakgxwio.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2camroxvf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkactll.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2etayjbci.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfxdogi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cytkjoxe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2akydaela.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrfojfn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oavcyksq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmyycxe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmcvpwz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zceapzyg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgcpapo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mkabrnvy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbkthem.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uniqakwk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tmifmzek.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awhmenkh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qgihqwpl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djcyggco.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvglpoy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdszpqo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwtmsbc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgrljqx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnzctm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmjdcol.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujybzosr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oahxjlbn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcwqspg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfhpght.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqhbgef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsudvmfs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdhfgjj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2prdztjpf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgpaokn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaxbfth.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2clcygulq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avbykcln.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwapjqwa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2upottbvn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuwkxok.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgpzrqx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2halwpgaq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzclofi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aaebssbu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpvpnwi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjjrltn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irkmleub.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhqtxmj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nammxrkv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iloohkmq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfeenwf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otjffpbk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgbdkzr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qowbkvhk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tplqewyk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2unyouako.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxnkvts.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vddlpvig.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqulqznz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ziamahdt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aplmmznw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rudzfvdg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yknrpngi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nikorscj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2steephhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2daofzdmb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gubodnqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfcajwz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2snvzftqh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuirlfh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2blbizmej.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpaukzd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2juhbqhop.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbptvnu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvpmllt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwfudky.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbsabvv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdzxpbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqynars.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ellftjam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqujnajb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvkndmf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulchcinp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuhbrff.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zozonqgs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjiivmc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkhmbdz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnwzrru.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rniopzak.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwwsulj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfxqjwd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzbuid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thtvpocq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eavvexwd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqobjzao.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzadfeb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhultxd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npdtsuhp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2atudakho.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afxdvdcl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgjrvpk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpmzghc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvpscol.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbdadji.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gssjuybw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgbqwjy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfqpyrn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgvqtak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudpjou.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rfukepch.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhsuzbj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbkhjbe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2raxmfxqk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atvfgxmp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olygiibs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgnybgg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2djjhflwb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2whlsxsup.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewheoeic.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxqonyu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2onaqpscs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvcvucm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyjzpds.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoyoatn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uayxksse.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfupqmyj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklfezho.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuphymp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psvmuevk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyezqt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvukzic.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2trieghrv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnlweok.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsjzjwb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hftqxdlu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeyndso.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgsqjde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvxrbtk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsiicff.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcvgpiu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2npulquxu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrdlrbc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ficzibrz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imlokttv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbudcywa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrazpzay.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2auplwyeq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxzvuvc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhisikfw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtznkai.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jffmnpgs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgndjwo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnanmxft.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2frswazvy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwfrjqp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzayagvg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxbuerw.html


<!-- 参考信息 -->