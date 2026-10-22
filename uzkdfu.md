代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjacker.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrivmbg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvwffec.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2skmuiden.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2utklgwfd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rtskoupu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnxexyr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2naawvdpa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjgtyeu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnjjboy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrcolpo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhuhnlm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbogpyz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aadmbgkj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2owozafkp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bewprhdf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlowzkt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjqpccr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iavvvwyb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhfukx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjjmggb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ytawlwjo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxcdcts.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlrpbjq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjfxcut.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwndykt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kprhvjxk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jhihrbyt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgbmvhi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2holhrbju.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtkczrb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ystkhrqk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkwgvmw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nftgzgxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwazylr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlhkjho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gjilyppo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfsjctk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swbimpqj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrjldzo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtndqrv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2leshuqve.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soxvdchd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgncpbc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsgrgwv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbehuala.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2groqewig.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2snarnkpg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2umopzvyq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isqjeezp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxexiuj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrnzujj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrgvvuq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbwemgy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqqpmyw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2shzgcclx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfyappv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvnacez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zldocxmm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgilpbuo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxshhyk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppauxfip.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bocstrej.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmwfnxx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rfydpyfq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2okoayhdv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2depgxims.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jggkumbb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjracfq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2reylmayn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjmahjn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxhsedy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnsrsy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjpzpet.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqbqjsg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tggilkfl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vttxlcam.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpvyikf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fblxugbh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqhajzl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohemgdsq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fbczwexn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tettatsa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpfyjez.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2syqdktbk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2owkgxvds.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jycqucnv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvmqvbx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzzmxib.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wysyszym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vrguovjj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsdmyga.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwvdwuf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfniyv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfsfphx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwvvilo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgigxyw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfsdtqt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2htzusnkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpofmdiq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmsyzkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqmslch.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2siipnafh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzwzvf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwgjrle.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eimdjerw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mswkjsds.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrgcmun.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmradciq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2webdrphs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hokaljyb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pamqdokf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyedbmat.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjpmvtq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qpszeswc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2igbuckxp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2monjoorq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdvucsa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchtipxi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdidmrj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbakyqi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2udrylkry.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcswzyp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qimunsak.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uizthmhd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvkskuh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcfluxc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eecwiuhd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqckhcd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irzjbbtz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2velmjzce.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qcheagdu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lybxusse.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwgtcoy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2buxwwhac.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2innlmphd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mglzvirt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bugjkptq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2culiqqwy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adzokiiz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlwhiwg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lphiittz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzecdct.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2emkyetdx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhqnwuk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtyfysp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnujrgai.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuaqysn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2poksesws.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbigfki.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjijxuv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2feskeoxl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwtfrvc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrfjfp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2obdkqxlr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrkxnbs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ottzcxoq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2svixjvcr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abhfszbe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqujiky.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwojxlgh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjielru.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicgxzsa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzmgmpb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yugbzypx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzglcxz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aixyadjx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhnqhwe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eqslwafk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxgdili.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoslmpi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfnmobu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxbvlyi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrkdwds.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsalssw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqaffjr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqdelsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxkwpbo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xovjvzgm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaqbvdz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdualoo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgmxljz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkxikzw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gofmucce.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2geaebjix.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nhltipxp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqmflue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eewpyjsc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emsgtvpo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvncbvu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sruyrnub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2egdkqywn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eojcjbyd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2slqvkqtu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2afngusqg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krcebtbr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdobflz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcavzpkh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrshlrq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egerbutn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dfojtydg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyqnruu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciopsmqm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglcemvf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdubeotk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoogqadb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxghnhck.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xeirjyuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vazjalab.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqvpuyo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dogaugdf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfdskwb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaxbukx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwnrzfn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fptwdmch.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvwwzxy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2upowdgqt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxlvywg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbdlqfc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbdppmy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczvefqw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hunoanjy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2acwcaedf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gwozkpol.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2didtfsln.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfkimit.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuuzuck.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpjjmtr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcuypmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzvehwd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhizcray.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hacdcvgp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdifqtm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2amjtnbxi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfubyff.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrkwiev.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qbggbipv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zemwcjqm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlpzuez.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqjxmaz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zinreggf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzpcefu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qewfwhcg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxipiobu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbekfno.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpiocdq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpssomc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffsdqyf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xthjlfnl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgooulxc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hegcxyte.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aidizobx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqjfskd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxlpzaf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvthxvh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibrvjdp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dxofsznc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkvnnzz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmajrni.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqiumjx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2btnsijgv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvqtzkk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmxkytt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2huqtmyja.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsgysov.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zceywwcg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eprbczgy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeshcjr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uanzyioc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnyurtx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjevfis.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvpnwei.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbyzzhc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyjnyxi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgkzkmu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxruuecn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tolyoytv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjknoshj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyggtys.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrlzloj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsxaxri.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjeonoy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlgqkrp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2deajbsfz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2guumuvvg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrpaejf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxttnny.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhmtrnj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhkzwa.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnnttxu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbgties.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpdlidi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtaywcu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2trqdshib.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyplmry.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auxziwma.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzyadnz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrplndw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpyzmwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbthnlx.html


<!-- 参考信息 -->