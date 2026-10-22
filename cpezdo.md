代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmxdqcj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2miksnhfj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzysqxrl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zeafbbuz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2csqoipuc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2siaogflp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjqrctk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgsykme.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2itzerasm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaffjuu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nowknokf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjylmtt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarywcri.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwurxtf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzfgvgn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jseptrsm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2durkoxcm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cznoxwdb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nuenqgxt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2logilvnc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbvsuw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2luqdiyig.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glhidbur.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jindpboy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rooqtsna.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ictxbxeh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnlpczz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqwuebi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ymntxzil.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2msmuuwhu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsfbnfl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbsfluh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvohygqr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzalurwb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czrogsiv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfefsnjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jexfzssj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdtuccb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rstxginp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oftnrawi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2perwckbe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgaced.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egbxfnup.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2keqmkozz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mibmpslo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsspxebq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2beovxgpb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvsxjnp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ydelunzm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2twztbgkh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2koitgrmw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmabvhl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyglgljo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrtgedl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2clrtvlsm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbbjzmv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsozxnl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpbpejq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pshmfkll.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzmbkhy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bnevlxyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shqzcmxo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkbtiak.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmyvekg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxhckwj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sklinqxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdrmfae.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2crznbxxa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2slztmaxt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcjdyys.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pexthxum.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvikdzge.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgqdejm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdvxcef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhiipqt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxtecwf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxmvcse.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2smosixhw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdasbob.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrktoqg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2owtpgiov.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbemidx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wruhetby.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lycixsro.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyvojav.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2utjblhin.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrfcxuc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjctmlhx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qucnxlyn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isorzqkw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kfldgxjr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzplijt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aadyijac.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ifddxvxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqvbpr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lguuhwwf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlvdrzm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2eghstvmc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgwfbvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtxdfox.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrwqxbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crvngxaz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqlhftn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2frjamduf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdxiozp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sakipsds.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qakzdaye.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeafnbe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2thiehtkr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2evejvhfc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhsarlh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdygycwa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxujcwc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2usvxtgef.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2crckvokn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yaddfgga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2czftrfdc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnnywi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftpfqps.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuburfb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsmmrpv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aicrmmwz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjkcwgg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdzctca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxkngcl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcbbvkt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjpljcf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcisdfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqxdxus.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuiefer.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uejyfslr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2arnsrlhs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqhhivh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfombhsn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2whaaymkx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uaabussv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhyysjj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kyifrtpa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkvvuse.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwqgmit.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rifilyik.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlrytag.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwwyvzk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbklhc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2acqhsrja.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oniwqgrl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvilngg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnwyutu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kudfwhfu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ollyfsvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjrvtaw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbkzmwb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfqdfzg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnlhims.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqwphzh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvwxozh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpocltc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhcvwvx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cktenrxg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yippflre.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzaezrt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqdalpd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2smznzxlm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tfktkwmg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2phujhybq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnlnbmu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2npiuftlp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mudbhrld.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbckpmq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxviwncc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gaajcjne.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrueuad.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ommpudup.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cknplotx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhemffh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sduprzai.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cldhxavn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwryqffw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmhrfhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvfjupb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jalsgiys.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxwgxzc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnpcaqp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2euvliofm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqepqsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qprqzusk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjdcluy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2caegelwr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdugihsy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtimwpw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxghfcy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcgkhae.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjdehre.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkrfnhc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lfibqgsc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snbryjzf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kauzxsvs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoxmqow.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xtychfps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwinfrov.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2smahfjxw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwigpaqq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgszztfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2utcwmecx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpjiwf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tllauehu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cojhjcsa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxvybed.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dntcoagk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmthcbab.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2avdwobkh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoyxrsq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuapowom.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlpmstm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyobsbpd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyydqvr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtbeuiy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgqjnd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbkxkia.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjdydwb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qljumuop.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbxnann.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaquwgd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tzokuucu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtddqxh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmmzbbt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lohxaxgk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikhjgf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnncbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhcrhb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2anurlpta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvucnxtp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isiqvdoc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoccrde.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2laymomuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjwkxjw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mldqviqf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqbxren.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2askpdthk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlbqhxo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mresqviy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uogzjoei.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cezheuqr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvkwkhp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rhupgxuw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxvgxfl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwuuknx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtacvpg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elntpphf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyidpymt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxthjqa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yavaocqx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxqyhz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrqcqdm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbunftt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwqghs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2alecepaj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwpgwjc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpuacgw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2naqgahun.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kzufminx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqgxfmd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwanfy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkuoihx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgdokyd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrjquvt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbnsdjp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbclefaw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjmxlma.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjspgkz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xkacaiyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmmtscj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvpgbt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddsgnri.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nfluxvvd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2knfumsgk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmbmeg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2noithmpr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2athkmxzp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpvuesj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zewabduq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lepqldwv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxjxowc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpizwou.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2htrrqisv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirrwzob.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuxueqm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnsxwey.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjnzeap.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfanjvyh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bsovjavq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qomztciu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrfrkue.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouehczqt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdkwmby.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jonllklg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqavrnpl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaginei.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2obfobazs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmdxtgp.html


<!-- 参考信息 -->