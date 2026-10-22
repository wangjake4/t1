代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuilmlix.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzatpnx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bodevdau.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqedqf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2egspjxjs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2edcbsxdl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bynkyisc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npnxfqol.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2taaoseig.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dqztghbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcziifu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iirltjic.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaarlii.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbpwgpx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaxpwsy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2exmbllkq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzbhxns.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lzewoikm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gkolgrof.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpqodvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpcgqsq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhtmwfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfuyjxt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdprzvu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jocpawmd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ditxvkxg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrbaqnk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chrrqgcq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iveercgw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jlglopgd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxwciac.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2queiftix.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hweybmpz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ucntuowt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzfuvtf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebikcpuu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcgaufg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zdibnjxr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bspagimm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzlkif.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rkljhtox.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzripmn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2anusnkpq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqssumb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmigojt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eivbmiax.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erlsgavb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwydgsim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qfngtugx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwldzsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuazgqmg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbefpdu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzcjfol.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtjlptr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pecgvdth.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcuhuxr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzslbbde.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2admepkkl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfacjtpv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmeenkp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mohantdo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfpyzy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrdcgz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2akkumukh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlydossk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkruaio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zjveiijp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgijsrn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkezetv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2upmtfyjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tfleaqlu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2clxdntiq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuzzboc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjhbatv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rtushqoq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oufwsvgk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxldpco.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxmmjbl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hochyczb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oicrictp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgwmfmk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2irgbsuej.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgskrjh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2axgkmlqr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ptehalby.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdmggf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fticwien.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfodrusj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeziimj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2negibqdq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uzunadmj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdzdob.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpktfpb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvvnomw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qohsxjwr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxqdxgc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlmejee.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqqjujc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmblvelw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tawcwbgz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2flrhalzt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqftgqnu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkkxvoc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqhavhr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xxurmrth.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeeoajb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2copqqqdu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aposkpai.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lspjhsct.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfsmhze.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lbapmuit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjqbuq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kccnynez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syghokzm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaxdalm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiokzaj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhigmfzi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kaezdvoq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyglrkcn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdcnbmo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqsehtj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyriloo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjnjseq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfgxpvj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxfwfac.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nukbuqsz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpmhnra.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwseucx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gayqlvfb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpcctpn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2aejaakkk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcdvjlg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiyvvlp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsobyov.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtobogd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmmsdmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2beecbtqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlliqaqe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcthrgy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pibrdgfx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2awlxwmfn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mctkssck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqepqjlf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuwhsmb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuloyuh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2clegbkhv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxiokbl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbsmucb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvrgncb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bppogqxn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjaytbx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnyhfgs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqmpmlx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtjiuqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwcaexr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2myootyqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyioubix.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwruuro.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmggaiy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pkphdbtg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqloudgi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcktkip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2laakutyk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpabojpc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yflbfieb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2unwmoylb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2btutsckc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2egkvhreg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzxmkni.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xduenryi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxjatmy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbijvvdc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2whrrqeda.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvowcpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tizgvfhi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2swmvigos.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhhqihp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsugrd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lcybluai.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyzxxpx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqtnlbz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmrpnoi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbpvmod.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2llmppuyr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkazoay.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlaskzq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vtndvmig.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pljgcdmy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvalawt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qozhxmbv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlctwmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arbkfqtn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cskwnkih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2paiagebr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqcjksi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tusrkeph.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stxcthrv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kldokvqq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuqiqlg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkvnkyo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyzpyyh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbplppk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xebpwbwy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2thxfgfux.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kplpfchg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mllgjgut.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wsloktbc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olkcvmnw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuljtsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2payauzos.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlnnljg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqfnejb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzynnvnh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdiutgl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvqjavx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqpxfvp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hziqhbal.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpamjnnx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrchomq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqjoyzh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhfmzve.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2totokont.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2axshulmy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuxqcxe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanjbbme.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jogevhmy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nelbopmk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwllsqgc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhezbj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gyarshng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmxqnm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wifdzdgr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brnumsaz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gefjmdtt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpztyne.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfvelev.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdpinmm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cymdghgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odebsjuw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hupdxece.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oiswwtsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ormqwntq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2filjqugr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hipmaspw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2celgzxnv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpenwaz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbbzvf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzaryry.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2aczsycnd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcgrnnc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jsowguob.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2stleminl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvysbhk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsilxrw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ursqtpdl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bijwnaxs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrtpswv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuoruuy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lefznqoa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlukuvi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkquasa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uerhnosj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2thxiphjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sozkuxub.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdymrh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqjghhx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xrecrucy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dshdezei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxanudp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvfnjtt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqdegch.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpixcvjc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbjikro.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tounnmva.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axhupdea.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyzaclz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zadrfita.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rndholyc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pypotkov.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bljnumgg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjcawtm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhzzssf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvomoxj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqgbgam.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdwfyzl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuquihl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzzrgbf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zereqkny.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrmlvvb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2axzqoclv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pojcihfl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsmciqy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mbymrqsz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oceimbdf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtekfzj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbaxovm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvukdks.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdosje.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafrqlg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbrwvmt.html


<!-- 参考信息 -->