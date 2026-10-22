代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqonlcl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcaiihz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnnignl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxdechv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uktistre.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hgowqmwz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfcigck.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgqnvwj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhahgbw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eaohlqpb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvuykpo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zoekrzev.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdhgrbj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdlsbwn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2umvubhyh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wepulmpa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfnuyra.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2myiuzklc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2libzphbb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fimadbad.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsieisl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbxxjxr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aghzqkfl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nrucfgxm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtazmmzu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbswnym.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnjxywc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frmsggkz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkrofdd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hhigqlrt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nelansnw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2otsobzgj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nowwkyyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjhwzxz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuomhvp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpcuwye.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihmmoc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsteudda.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsxrrls.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emguuwfy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2befbrlwl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aerxjine.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvaygjb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmbeljy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2znhzkcqp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuffzsc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2carxqelu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cvotxuqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuckdbv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfxssx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itlqmsmv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrsqhvv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgyozlr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2conyzcxu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsiugie.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2edbzmmbu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2voihwapc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efdkxjkh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2stfipizd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2slpeadno.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbyuqtw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nimvkxnr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ostknsre.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmvgtvt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yziyyvkv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcgftil.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cnytbaxw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nibctepe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpncxae.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2deurffvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjuqnjm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2korypnuk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxbefyf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wzasbnqa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kmadbdni.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvspyot.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpuumfi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgdyqaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjricvg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbqwmvr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlmahqr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2grlbddxg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2aaagrwjd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wprkodol.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uucudozc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbjpkdo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhdvbcz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwaeqwv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqcbnaq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrwwlpw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yytycxnn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2doulfdwc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uttncvbd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cehfyoqr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlhiaz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wadrwwon.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2skryfhna.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqyboxq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epplfrsg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgdiqpj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrigntp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiuxfal.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyssdzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrrshpv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tninimnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzdoqvm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sngfaill.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrptwan.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaselrlf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzwbwpn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaxyqws.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdulmwo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdtvvuf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2swthnbrg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvusjull.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyqwubs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqklmvm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdopwvrx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2muzvvrxv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yaphxjnb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsryxxh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmhbyaa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2joissqpd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vxywiyup.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2icbuhqcc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqjrucm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigbivjq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrcvikr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xthwdrjy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbsmlru.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2amuavjku.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqogeytg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhylege.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drqqntxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmdgma.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jvayqfiq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhgowje.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvzmenb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyyevom.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzcuzj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yspdnzuk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fubeaeau.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgztnimf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjmhdqz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhulvbc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unrdgojl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxrvait.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2brxuuzsd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqkkpnr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbmwrez.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yegpxbuk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjoaexu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkcrfym.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbdpwez.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjtdrc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tupmprgu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2njgorsux.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pcniebpd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2botenusw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2alhbpjla.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuhvkth.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvydsyu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgafhnvl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuompwa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdljkkl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpxtrvh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkmkpfv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2etxmbfcq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsrqaiq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2biwxhoib.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gyecewdq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmjdeqz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cmusozdg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkwabfs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvqjqxl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzfnzfz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewvnfb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueomzuzy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uhypncmk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcnwlmd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uejjhvmt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gixfcfge.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuvgjop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igtvyznc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvanxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqchix.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2neznojvu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tggetizv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvejegy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2taqvxtmu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vodumean.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpdcqyd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqvniin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzbgrnb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fppmyymt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmtlfry.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aghxdqvq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhjmnio.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fplppdcz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcgrhhq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwpsskq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxywcaos.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qfunnyve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrfvwhf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sczuuspy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqlzpgk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sakwvqdh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2teebqtiz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbdqant.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pztygmpw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuidoqgu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yltoskim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbrrsm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcdzrtc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhbalc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uslnrovz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bammstar.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2krgcgamr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlmvahw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2npmeaebl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2febcvptb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tlczjspe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aorbwuih.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwxfepv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vicldmnw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjtnbq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvmkdxe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ronllmik.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2feloyonk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgajqvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjknqaqy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcrwngo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2txpbvnbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbkgqqv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eulymubc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaubpgk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spfjpdvi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bguhgllp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jimrwrkp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qhegrrui.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtdtth.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvodsov.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2acfbczmk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvjvzkd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvxszch.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbjejab.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qneirbtp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfcjlpb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iutnyvkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zygclquf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwmwesf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhfoslt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpanyyt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoexhxji.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwfzyzh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nodfwzow.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kirwfjad.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydfddsu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkacxcs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzadjce.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uczoahrj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqjvbkb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwvyhrb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnerpxon.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbgqtem.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmipxfj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ermwjysc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqiyyan.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqijogd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lavyruyv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jckhpgem.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyghowrd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fwowjujn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mitdlbeq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdsafhp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrahtcvr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lkinuwtt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfofekdq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvylilc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxadblir.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzqitat.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmusmqhf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmzlkx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugahyfga.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2trwoopqe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwbeyac.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsrmjxh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bobtyssf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmosuhz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqafltuw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2guskhlzz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzeajih.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmpoavf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmdjjzn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2waikgepc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jopliatm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghabnrnn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sciybosb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gosomahb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpkjbju.html


<!-- 参考信息 -->