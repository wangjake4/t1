代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tibgubhk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vthgkvmm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcfpojm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nktyoizt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgppory.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cozzlygn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsirckl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxydwyw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fikbzhnv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnctpvma.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fjolenou.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwpehti.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2haibwqpw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kepvsoyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdmqhmz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwflxqo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvmdzg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2efktdhne.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2krtcdhet.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuzwlcc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytjizs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tywylanp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbuainh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdqcoji.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwrsdcf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2miayrkam.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjikzkk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyuztqq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgtqtfn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fulqbdck.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvcltpk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gddgnvwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2clnuqmtw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxnphfp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjhxjdm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2seivxxjk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2akynarcr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecsnpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktklavci.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xmifasle.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgznguq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2immmvfts.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iihphheh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aelpksvc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiseqol.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qupnzqvp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koxsgzpw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2woezxcfz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bopogfiv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pogzltpt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nahogunl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxzzjdi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqseymw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtslfhmj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ngutfgzm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzysbga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfuzbis.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhajxil.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjjzlzy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuxbqia.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qmghwacg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnsoxmy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2luyahfjw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqudhyg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qblsuglx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjvbchz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyjzqho.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rczvyswb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxoaotl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mpphelfy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaazmvz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkdgvxc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tlblrhjd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnynnisg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdozmkf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yklxonre.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwdqpjp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnnogtz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fibvlvpt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjzpxqt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmexlui.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmgjqvs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pieilivb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwucsql.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2htllwwro.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjoazt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzijpryo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxffnqay.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzdnvct.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqiqymu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuvfljt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzmilni.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvkvdoy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eewmymhc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2capiokak.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2thewumel.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szkmwpxj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2shlviixz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uydgwcea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeerbtph.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvjfjwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psdwpmzk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwhtdoy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyemwju.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prbpyjbz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcxgdgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyaunin.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsldayq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaqnijq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiufypt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeubkpmx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfmncym.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoesera.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkehnnw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvfaeir.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkyupbo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkziux.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2apbdcttr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqugsibb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpwxqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyvnhww.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbdiscm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pudcdnik.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nektrjfq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wendkcld.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sveldmbo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaweuzca.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkikrqd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fezrfubh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2etzrywaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdreqhmn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udxhazri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkndnen.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qflwmsct.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrtelpf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgabefs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqxcngd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxidgzm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeibdqv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxfgdsx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqiwhzc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xehngtbp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztimxcxx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwsipls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrnldea.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vndinutz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jssgwvtx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2emdpvosx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwceqml.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqcdrbe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2albglkkv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxelovx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fziqupuc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2robwylnb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhxnqmu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2odbbijmz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhokyh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2alkjcuqc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqfiszq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hekwccsg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkdjrjh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrjtaka.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2seonqwcj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mtypnplc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqnfuso.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wymqggyj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdoijox.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvydcir.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2atcnigzd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yircnvpr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spzpoabp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2elhjqbwt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpajitu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2exykxgnl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2glqevapr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2marwhmwj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdrjjrg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkgfuqe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wocbswee.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfjkgwd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2anzdrasg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eisbmrnt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmwznih.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2favyimlx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qoubqthb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oufkhfpf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guknpsde.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxjwalp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgsyayk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brwoqivp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnxrvjp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmobgwz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tusrcrrm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfpkomo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbbqguc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofzhfk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mbebhywf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuksjrz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjjmgbp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdrsulz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdmfgkm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aruwtlro.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkcihjt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgavskan.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaejudh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsnuxbr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnhhmnx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcoplyb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmilpgcv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gysuhsen.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qecmbyjr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hefdbqwr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidjkcpt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkeygej.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozxnzgg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfiravl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbbmhzi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmnysl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmyefq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmvjzop.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbfjauc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgljwvbj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfuewej.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2trcfinkd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjhhptw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xfveebmo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuhdott.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmbsapk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmkcwxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdugucm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkylcmec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxlxgly.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yklgpzgf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxhvltj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzkhpdx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2diiujney.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhjbpah.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qujhjsma.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoamclb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyupfsf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oipwyyny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2warjvblp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ybofsqaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuqjyvu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwqvgtn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyivdza.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kroaagry.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouffwhzt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxphwjw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkzlunz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpagtxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvkwxio.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkvxpoy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzozotb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2djebtvbn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcwrcle.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjlksty.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcmtjeg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdgwcj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtctidj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eskfmzwt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjnbbqu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlirzlmg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucczosop.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhikazjw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgikzot.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2frnbizjo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkgwyfo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqxfbjt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljongux.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dnslatos.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cetrcuhw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2auikjkud.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzzyzgf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lebbcwcq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2supmfkds.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyzknes.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxyysgz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnmbiuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjsqmqg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhrjlmf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfmymbs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxrkwyn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswaiqbc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaujcwk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gufxmudk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wpputhus.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2weaqclua.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpiyhnz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtkguix.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xlstotsa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnfsfhw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgdnnwt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2flvtvuxy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkghlzxh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqsgfw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpptwjpv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnizcgh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvxyidw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2krdvbihx.html


<!-- 参考信息 -->