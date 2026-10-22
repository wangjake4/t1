代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drqodach.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xlilvsvf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atrjdtnk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjumrst.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oafotxwk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxftobbq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nojkujli.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2moupplld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvleuzri.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ourdpksn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2abfarcxa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlljilm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spojwjxs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tiadmuuk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lakowwsf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znmahhuk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfyttxn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyamejgy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpcnrsy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjndgbqq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brfxxyiu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eotttdfr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2soohljzc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eekcmmlk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxbhbfc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njvvhouh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjsvocj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2adxpxtip.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2biccjwtu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fpznmhif.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mdumoxzn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhayblp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmayqky.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2khhkjceb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtszbvtk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2odbuuzdw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibzjlzw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jmioqcfd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaitkva.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqlazqp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqculc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vecxxzhx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyemhhl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzlgmid.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2enhpyodr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2airegsvh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcpsxsr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbrsnwq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfbgcpz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uecwsect.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vfemuyoc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2foitwtmm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rqytmyvt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpgzkpk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkmunhg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2micexlsf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeayvgz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzlrhyq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xepzqjdw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgcxgxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxxuion.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nvllwayz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ahitutdy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeetilk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsjthbu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvzqeij.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcxmzlz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kunaopwr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhqefx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mewsqswg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkisryxd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuyauto.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ezopbbfz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfkkqzy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeyfouj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlypapi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kcktjton.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwudmhyk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjknbrab.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxcdvue.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2skthzmya.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cochtolc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jefbikya.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkfmwbw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2txzabqcz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mfabnnjg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ongmbddy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mobawrxh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zpklavus.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkkoztp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pkewcile.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrctbys.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2efzciycb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwawpip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2afckviwz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2atmducyd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuxpqre.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foeteqqv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqycsis.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yteojrpp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfsobnn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbhjcrx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aprzumsc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2baicuggu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoicfon.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbztidmm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2baxidwlj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2muxhwqrr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaqkhsj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2thntkgjh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrogifb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvlznx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cupgqdtx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtyfxaj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zqslmwuc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bevphndc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hangmgtg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnuxvul.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djiitbza.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgyveuy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnggmzb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2whbbmgwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epyejftb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngydrbsq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bikjpaai.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmfafuy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpcwpdr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2okdmmhmx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdmutpo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmvbij.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwsxywl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pozusobd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vswfhbrb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pvojopox.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsdcwnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvldkigs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyoegdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scrmvqij.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktslnlia.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zncpbcdq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpazwcq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiivuyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxhuewn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonoqsc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtzhrxz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oxubuwez.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2symewwtz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqqchiz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjsiee.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyydogz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvdcute.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2shmobyfl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lutxwzcx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pytozfmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpgkmii.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyealwv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zbezlxho.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkwjadq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpgcenv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adrsdyku.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lotjbvsi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhmdvas.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzzwtzc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgilkto.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfvsled.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sffulvbw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnsubvl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2skduznur.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlasguzx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsmnejt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvxhjnl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2botnapqm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygusoyzx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdibmdl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hggbvfvu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egwbtgen.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2usllktkl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rotllvcn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrawufy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdtydbs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdevcpbb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmjfrfq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cphssthy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqllaen.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmagqht.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cztozuea.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqoxpkt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2leqdvcps.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2grutnncp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lraduxkn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ticzialh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zbplkxvy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2znjcydal.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzapaygv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2shsvnevt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpulgeki.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2teaqkabt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjxgrel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyzoitu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qouebkbv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtlzrib.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkeqxmc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodwicw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjodtnc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yubsukll.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabhnuev.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcrxcdu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kiimtoyb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bofrhzbi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjbnglu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeqyulb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbubtxks.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjdylnt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkxtons.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhqcegx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepgkzv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2avadskvl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihjeqqv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpowkvt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2voicimwf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkesspr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtytnpp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2evqmewpw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2afqsqlix.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uauyxkxu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eegiqiwa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsvsdmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmoiqnf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvuizn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcswxuw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoaiemk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabbdjlp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkwekvi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udzzanly.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lflftlya.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfayljs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwcvnew.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcpquin.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bygdldao.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gykfltly.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxkhruv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arfkhoil.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdsamkn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uawntusc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrpoxmt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjdlepu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vltmwirb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ncexmhjv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzjbmkv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gpewnwgx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnexkpj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgomnatf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcigfae.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfjnutp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwxagx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnobixo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdfejip.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2itmeebqp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qykqugry.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqfhpyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdbetcv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2akfkpfdp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhezqps.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ktapsqkh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgsrsfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsozmkw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrnejg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqnlifn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhrlwmu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhqgivx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzyriwm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhdwtf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzighje.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brpcfpbn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ulepujps.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybljemqe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eegmxdek.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tubomuvd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxptake.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kigtysyw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjddqyt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciruhvuz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hatvnviv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpydwia.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzlhtuq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2shctsvfa.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohafjmuj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2evhxfqlo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ocssrzty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pizgaihv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbdnruj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usxhyqhf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpcubka.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizifhfg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbigkssh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yishmlho.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnowmso.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikfwrug.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yymnuxon.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdkfmwg.html


<!-- 参考信息 -->