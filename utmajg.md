代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axkbjkkp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2swbdwgiy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grmjtglm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwfqpku.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tamglvmt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aougrcfb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wshwmyyf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujvgmq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeslojbe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuwhfav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrxkxbw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oerqysxi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kidvhgtm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwwpbgn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfklsydc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nzincott.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcanbtng.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eynpydap.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbafdya.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhyyut.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaerjco.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cgczsere.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yruzdund.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dchkiaaf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arogniwe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzvrtq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kujlxbhb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpqnhva.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deovkajm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxzqfkk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhphgps.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2unatfvxp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnntfzp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ugutaeek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2btwrgyeq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2setefoqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uivrqvjd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkimwqc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrgxxth.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdtchzz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxekwgb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2czpceaqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uccucopy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2egdguzup.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujbmak.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmsyjzo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwgcpg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2szabolrh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bisqxopd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vquipdei.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nciaocqj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbqmwwl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kcndlaqc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmzzctk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sijgjuck.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jiovutye.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rdofikcs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxkklde.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2quaikqip.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2maocigxj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kekfggvg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgxgori.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2splbmqjx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owntdgoo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2euehdcav.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hlilgwmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqzmjiq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fkudepbg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2envriylm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2medkyqxh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcovxeo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpvcszg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2amrgujkz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vstzwzvw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnxljhp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpkrmqw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bofczsec.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2siawknok.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdxluig.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcdhfdx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2friavqkd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avlvrubq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthpqdj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nebfnvka.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcubzri.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzwkly.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2knjnrizu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dyobtqsm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqwgdn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2telimoge.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwszqtm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqnaavb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqvesut.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aoghhqro.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2riettygt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugunzvhh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bnholwnf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjvovam.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyswpus.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdvnrpk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ubalctmg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tabjzdai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpslfkg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2erpvrfzh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lunutcjd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwweqro.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklnqny.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gczlubhn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlhyind.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2udlvutnm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpzobjv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shfdohtz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmbxhbg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgyrgxx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdchnhb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjziwtjv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqpkww.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axwclybm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzpevzz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvuroth.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dukvzcgm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2acqwpxdd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpznzz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmwyedl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyxovlf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2svkjtoht.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxytlea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gacggchf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdnilmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vziiyhkb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdzcemu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wjosoajp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfozdxh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbtvfyz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybaqhey.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfvztcq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpouiaz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2avsgswmj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqwvwf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrdvpqq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsqnrcu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmibpzu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nutyzvzb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aheexhri.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2quvnbrdm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oejffvpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2spflzqwh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gbimznsf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dygfxckr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hknipeju.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wglmltnn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpocdzyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdsyvwj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjcmgeh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdavwtw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnbsmou.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gljkqlzr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qjikzqnd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaahjgwo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zafdorsl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2efqdgabd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kttxosfx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsngqiip.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ounbvkee.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwwvphz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrgsyoo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjvcrbh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skkkjrpi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehrgskk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmxruqe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2naeclrdy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvsdxyc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2muilrkod.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjsuixl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzaetsa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdismim.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oocvipdb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2takbfjbh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2clhhdyuz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzlgpu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fceyochg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qddjnqtw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrgjwcq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2peuoxovl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcscgdq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqoxdz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwxsbmi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzokunnh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbrbjyr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grckutoz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cicijrbd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtuhtoc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrhltnh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqwiccf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbgzrvv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yukjuhqt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkicdwf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byvswipv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwefcbul.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmdonh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoqafej.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2toqoqkxg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lorvkfai.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyhaonj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nowrtscy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwizlcc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zeggldlo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqoqpyt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gebjtuwn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcvccij.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvfnwj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjmtjj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yojplfbr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gdddpvcj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfpeyxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rljtslmy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhetamku.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2amichgch.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuclhjiz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fijzwwjw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2itkfeier.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmthescm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2satpcymp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slaowhyt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dogxgeuk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pznavjst.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tqllankk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlcgioi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyaetxg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gybhaxsz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvznqytt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2keyfajbb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2maskxcdu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoazapgp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2leshlsyb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuefcle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenocoed.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmatelq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sebyivnt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgsmgvw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnpbhrj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrqedjf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeoyzvd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwheieno.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wykbokbw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xsccsvrg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrndwkg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2adwgguaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymyfmfy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hastzycz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbfuwo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwurpqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dynmtilr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2etjbqwwp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxtraca.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2svwahomn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hhealnsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzuiypv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnyxiyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsogxki.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vafcdiuy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2frxldqlx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgmawts.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2edubxoue.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rutxsidv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bugqezzl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqidrnp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxbhgqd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twjokrwj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgdgva.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiukqed.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxytbeqa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgnxyb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaxfnba.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsiqrtk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltitxw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgftcwdg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsaypgu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgyvpua.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjwrmsy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyndbix.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwejkc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxpcdq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphpheag.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsitqgk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iusyswfa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhubhya.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2puvffaby.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2axpzqwyd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrawsov.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pesliceu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzhhlso.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhllxrq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aekdoudc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrozflgi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjrcwz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzynrxi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyueesph.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuzwrfw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzmpmfz.html


<!-- 参考信息 -->