代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsnghuf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvffhigj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yllbpggl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcelibw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubonutml.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dyizhcnp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adnwsgbb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfttcrko.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcicmptk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2btjntquv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtppaqfg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjcmock.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kipnobbi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtukwqk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemescm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnazqbx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhafjzp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjtqipr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwzidjb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aymybdpw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbuiqph.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcajdjuh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lswpbwji.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wiznmpux.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvuucg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lwffuhsx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfdzwmn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcqhcuv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhytdoi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvendxmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbahshi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2earjrspt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efxnhlqk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hapjcybs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqkqoyy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yckyevcb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qemnymwx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2feziombu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaaobba.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcrtgsj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdgfeqp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuzdotc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqgxtbo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejejkmmx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aknqntbr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfhneto.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2quvpgyoo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qaanretu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcumdtc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxtkzsd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hatogazr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2frrhjysm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkesio.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxruiqe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkxewsc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbilswtp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hudfrasp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2czzrfeps.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwrruur.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgsvgjs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfpzwcw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpbfwqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdmnxoh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbxorff.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvblanr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwppjne.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaevofl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rifnxexe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rcixkyht.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmshscvc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtyqvnd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqgnljk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhwvytw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvjwcon.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkptvre.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2idufchxk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ndamohig.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wspbahah.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvnikuf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmlzktl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvmwgds.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wvokndse.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2roixshao.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcllmbq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xprhwsic.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmliiehn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kptvugki.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcxvoyc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2krduzyon.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvkfdfn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xwazcymc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dsemudif.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmtgfae.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsgqhxj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pwasjrce.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2prddbhdc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoqckpf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yibnhefb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbwjdkd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyqpani.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rjusofda.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpbrjbi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqwcygc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yiibwbda.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uekgdinq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvonlsa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxvvfwy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wrubtbun.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfgkltj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2munupjgo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mksirlen.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdqcpgg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzktdcv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjikaai.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qazalwge.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhhceft.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbtkmrt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hbybdwhr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyqtmvx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyjqpwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiipivx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krzhwisp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfsswyx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wthbvpvz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzeszkd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hyotprpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ontrjvlf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmexjtm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgutshpn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjkiaob.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2luoskrwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdydadzm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pqndevfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dexrmxyv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbtqwsz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnslcpp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myhpfids.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xskqwhuf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeiktmx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxvrdnq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2toufxupl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrguvhv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvbhwmn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sclhojgy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejizkoli.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjjskpo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nafboinm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzmltsw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgeveoo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2shctoolu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2amraxmef.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfxtkkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wnukbrln.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkneqag.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmxdtcy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awovqtfj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2grmtnpmt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2znuqujoa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eenwnsga.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wljetslb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdmeemi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2klpmfdsw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2amouahlu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tikicpiw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhanour.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcwqcn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzqjlmj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqncjheg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xowynzqf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnfuwel.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvuwdqp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdesvam.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhejzau.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fynnrfsz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrcwvjm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zhddkkxt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2opskerhg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dktoefrm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqyfjfl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzrdsad.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlmozqn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyagxbt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruofljdy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttphjx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vusivksi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2umwjqkif.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2goakgyhv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2flymuils.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2omrehufr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2obwswpsb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkzfdh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwimoop.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsutdkh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcttcgh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeivqfw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxgfsgn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2stxizoeo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qncfdblj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqritzk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rngkymmd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrjxiqy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzfltug.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upjewfpt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyhgkpf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdxkytk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnkkref.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfxpeet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drxhuznt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxngzqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbfand.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kubrxlrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlbpnbf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2atrvjygg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpvwqev.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxiolou.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeaqzld.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vydfoerz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yduuqduk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2arnvnkls.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqcodsx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyknhlb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkenxxhz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpociful.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfdawmm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2guguoakf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkpdjml.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tgecqmai.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypzyazp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqpaylv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khumwmpc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rdavnxls.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dftbhukc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mairnbol.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boihtiff.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wneppuiu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ramwrxrm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2liypugmy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2boqaqasi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2maerjich.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zovamolr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvrsjaw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccykqnmg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hltqkesi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2orjadlls.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hychsboo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2orptbfpm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpppfsg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgnvhav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcfvjmm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojnjhv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2thvswscs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nrexnrmz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbayoaaf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcgtxmc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmliqdjp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zvogimzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zourqoqo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2taexboff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2trmeyojk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifgzrr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aaejdvhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rotffjaw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuukzfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuxvtfq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgyyagk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tubfoimj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpttnzlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2djwxyqbl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dywlwfzz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vimiiduj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2opxftchr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzvdrh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdyllze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oeljfqzj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mvezqgmu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqnszhy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mkniizoc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amjurvis.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xjluvizw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uapykezq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pclcsqhx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2emtgplls.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymewhffj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2efopmmfd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiwwtem.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioizyiww.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gkztvsmr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchsvdrk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ioopmqif.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paiwiajz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utsxzlyr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axeqtvea.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mjatjsbt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlicysf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2upazgtup.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdcxnmv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wccqinmn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaqyadj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpsyyfq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzvdajv.html


<!-- 参考信息 -->