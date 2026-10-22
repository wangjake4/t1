代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvztctmv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcgkpum.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exkzlxxx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrnnogv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhilthj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qberssxw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajigwq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlyzago.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wapktldi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdvzdyo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiifbsz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsaxejf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfxuxsl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzuwvro.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gzekilcl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lluytlhb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyewconj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xyziibbo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzlfqks.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkzrysp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2awyjtckw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtrrzf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myclgkru.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgcpeld.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2blekuluc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eeussdoq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bulnkwmv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fxylskoz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nqppxdwk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yihpympw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkpjvl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbuvsvu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sprmywqb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoupxqm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgwttme.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nczehccg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vldvokfo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jrychnht.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvyayig.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjzvwjg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yigtjdxl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqowncdd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpczcs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cljliqjs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdkpwcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcymwvrs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ziweekte.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cennirpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2khbdsxvb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwmyly.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtcefwq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqjpwkr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfijvdmh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaovxfi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzuuko.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbfavl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vddtoymi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uplrsvii.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2huwkyhll.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xyebfgdn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmzzpjo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbqoqmh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2edmuykgq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jluaggzm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdmgzg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnohcxac.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvhpzjq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2naxxjsba.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iwberdtg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cegfhvti.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrilvvs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2svhwgjoy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xxszxvqx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qilyxuur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezczksep.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2turwdozf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pynpjgqj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wphjpktp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadngvl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2foduujtu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmqhzcl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ddefyuov.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgrefgn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imeplwpt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfplfjs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrflnxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfepsvpc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzjueqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxazazzf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwddzdmm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lzouymkh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkxvcoe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyiwovg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2olnudcbk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dygpcqdx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeskdzw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfdfnyb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlvukrw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bzevgpcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ossqhuco.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjdhekt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rejxkamu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcxmvsl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bijyvlpv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqszgjmv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxvnthw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuqhiym.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhtmxk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aycuupjl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pacxgtlv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjdkxml.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zgozpnoz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiibnqp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pelwttlf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xsabnakf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvbvwnm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2agwzxcjg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kcivbbvc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbksjiof.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgekvb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcfisna.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ispvbchp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qevqvqry.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlpivcf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjghbgn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rymhmglm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfxvwnq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ianckzpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeriads.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxylvlg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcwfddj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdfaom.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwgnujg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqrtyuq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2krochrih.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iuswgudt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffhhrl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abymqtyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbbvqsb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nynashyw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2thewnslo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cuctincq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzjmbpo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtpvhqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlbqltn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhaigfv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2byvkully.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhotldv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbcroyr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlntrtku.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cowfnccn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwedufzh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkedvsw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dlehleze.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mylcvtpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2shjhhaai.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdmcdrb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhfnhms.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgwroie.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkfzugt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxufpfry.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhcjsbg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2byqonuwb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pzksqimc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kznvvbke.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfuskry.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2udndpegs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtfkjrp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqsoymm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buidypva.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbibmun.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gaagucaj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpbtawf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwbrgdr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ucizvnvs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxyseru.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchqnie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzapbupa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnntfmug.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjqimfq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvucwzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhosiqc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoustisa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjgxal.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfkcsyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtwuhar.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vndufons.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcocyzaz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaclzsup.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhturssf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqsbrub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqarqccu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqywnle.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uodaikiu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsjxfmi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnluhlws.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrlzktl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uljpoegf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hacqiggn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqutevgf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkrsgdf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cadiiqxm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcaoypu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2whxpwvnr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjtqmmk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcahenmk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrluoij.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxlkwxf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpwjqpu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnheupz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hiextigo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rvenfgco.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvjtfmj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rsudkixw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwnkkc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjbxpjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xermxxnx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hqutaqyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmajwbwh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2japbwdwo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfplilx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2srshyxhh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tknryqiw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcjacxd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbrusfz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtcpixy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoetirlh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxbvqce.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrjpkpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pngsyims.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2spobzxoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvuqar.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbxgvbf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciypcmwa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zolmyqmp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ruicrxpw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbohnwu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqiltjy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hcspbiln.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcrcfar.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmmuuzq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tpibqvfa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkdllpq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjddvhju.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvjxkpd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzelgjjh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hacvuulf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oedmhfvw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjoyuyp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2afaowuzm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmornzho.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2elhphaxm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bulxadke.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wprqaeeq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mvandetw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhbqxk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqyolq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmieuoqz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2shqbqkei.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qporqbmb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2smhuxjzb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdimylvu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtjggog.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvcepuh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpciulp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewycqsgk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhrtwul.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxstsgz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ficgnmfl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2scrcyyua.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nylvrpyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uofduksl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qotnanrw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuckeqm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqiuwes.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wllbjiod.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiavomx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuindka.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kamifnzo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njcgpxyq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjcyis.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2whkputpo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mbszqbbl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgibekk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aymtremu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzaeta.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ospqpbxj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2onromjet.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grvzaodi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlgcztm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2asmmsamu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhewpxf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apfyatcg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvlxkma.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sifoeeoh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oublebcx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmesehw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yargyask.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmdzqse.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2drlelidn.html


<!-- 参考信息 -->