代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkibtfu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcortzo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xuredcbi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hluwoliv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtlerag.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcbgzzf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ozknaucj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qrurcnxx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iageisdr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzhvzg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhwsaya.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpehujd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwnlsoo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcyhire.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leoblhyg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzvshnn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhpbpnw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhjvoo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqzwgc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzyzolu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgieyjg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjurgdo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eorxchez.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjytiku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlumkri.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgudwab.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhfzctn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxgebho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gemncfxz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyvzmfl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfdwzth.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2totqusva.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2raikttvw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiqgsse.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csfudkgs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjcatw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrvqase.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggirdoxq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqjdbvu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnwkcsg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2coxyhadd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xyywmkks.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsxuqpp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yubkdgdb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiyumha.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpvofts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgehnxv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvxgpa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjvcqea.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkwfpla.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhlowxt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lashpouk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjrimeh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfucqppr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2grpsqhhz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjcyggn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfsvau.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rstrfwdq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2crljzccd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvivkfer.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2derbwuez.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdmuxmm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2waszpyim.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cscwpdln.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2begbjdiw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2weypjocd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2folqpoew.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqxajei.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfszbue.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnljnkz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwvjjyw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wtswjiny.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqtohc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfxqlz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrijwvjd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiyyhbs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uoimasyr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeulkxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddznlpre.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvruowom.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhopdhx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkldovd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnnxgot.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kclhohcs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcisgkg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoitlrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpnpxhx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kaefolpp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vonyrkhq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tyficidb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxjdrap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgimcyk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2olxhizvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfvihzv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vftwgkwb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nwybjakm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azxiyxtd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbvxtwa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cridcfae.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhecwdr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqvico.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mscpaghs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jikwifcy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnfyccy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erejhamr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvshyth.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2drppilqi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyxwngp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vaisorgk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2spazpxoj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyclwvl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvrtkfn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2artypcli.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2olqovqit.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznwmwbw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzifakw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hidcjuez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywtjuyb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyjsqqr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rymnbgyv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwyzrxa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uodaqccb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiiwmoj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzuwwsf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2buxmxhim.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrvmhyl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjymvbp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbagzq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anaeftby.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2roarcgao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzteokc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2riyomdtw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizglxqr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2posxigew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdegidhf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nkexcdcm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycukpu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cttdjtnu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeitinpz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hssomcih.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpmuaem.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtozwbie.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eepnmlen.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2foimyhud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvymjcs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogjgka.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrstujm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2thpudrql.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoohexk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbguvgey.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uesdleec.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqzrliw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdmcmfe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkuoecq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2emwlwhyw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2npgxykpe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qxapcmqe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2blzhbcbe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uycnjxby.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnlignk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2noakslqm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzedtsg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imbjjdrp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxodhmk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuurpea.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlfljfz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vspmryrc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeexvyzv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vrabzken.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrgwkgr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzvxkxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjehlznq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mwllvtko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eahxbmvw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrfoieq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ovokxvnv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svsbupbe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkjylew.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fszmsasf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzkalkq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oypvixov.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfkacjm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jejtvlco.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2llibjaqq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmtdufz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfqyjqn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhbsbed.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olznciyx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdrtax.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dixswezm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sanoigpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcgubki.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdsxppl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oezrobww.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eudwdfnj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvgmsrn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2omjocyzi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdrkgmf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhhvuob.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjoltuy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqkjnal.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnxogbl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxifjs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vknecjab.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlgacla.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wsemknqk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoduqsuv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2migdcbfw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxotwm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2duqocrqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxdidxw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tddqxawp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmcfgmu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnfqbem.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoonqtf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzltnbx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgagkgss.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhqfcyx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2suzecvcu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiyjpfa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcwnpvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daelfpeq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlygbjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvbkxkx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfsqgnz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ochmatzb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnlduer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtskhyi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdlqpbr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ognqeuph.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvybawa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lycepneb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vipwclhu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dheljpxq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmgdosq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaqkhdb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hoogpsoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwzcbmq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2erwyavai.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdwfamk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znuauixu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcctaqt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swkdxoja.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2itbofxlc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvujzkee.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwckhbfk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ainfcfaj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lltfhwyn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pcftirvr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2difumpxv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrzllrs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gweopisi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cfflgwqy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2trxrwtih.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdjekuo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mederupe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynugugmt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeksyxsa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lafmdmww.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijfxuj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfdgllf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkzfusz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtpgqgk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdytmjt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzqcmhj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sprmvypn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wemhptgw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2znjddeso.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgztut.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjwrxcm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlqimom.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2isyzrccg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2skbuvbmc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbrxoyd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dvziunxf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafbuamb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whcwiesh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lriwlsyu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlcuvfj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2damudyge.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pcokkcmn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqzwsqf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeydvsm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfgjiqm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaytksf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgeoxii.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uszwrwlw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrbnoyo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmdseqx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2itfmmmjy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sklaavjq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzylccqm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdbalwf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqenpox.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsgeypr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoqbsmw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zenvnexk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lktkzpxc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igleebfr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjsghcb.html


<!-- 参考信息 -->