代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oohyqtae.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgysvly.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgjffw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vumvoxpr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhkgxjh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxkawo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxgjfbx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yueoilse.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpytcifc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxmqsar.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwexbbwc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txczpskm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqfozyj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvdsuyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kptzuvao.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxkzmhf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhvnaqp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2spmnkwdj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdygcffy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwhfhnf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivncnrqc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwsagjr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpvqhvr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gssfhcqi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kspcefsq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkhrgfh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nletpljm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjjcroq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zluopgvi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2usnomynh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xehuozcx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zirrorfp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rttngjaa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2isaiuyiz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsupfc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uubxbmke.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mibjyoac.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdbmvxf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2urbgbzfy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aetwvsdz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsdwauu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwonpqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcncbpbq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xspmvdle.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbepingh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xvipgypf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjaxuox.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yhudcwmt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwcroxm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmfizdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqsteiq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqxhwlb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjdddxp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lazlvxrs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2euhaabum.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpriqyl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unilhrgs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2skmoapjw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ptumfaze.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2seeadqsy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjanhcs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsmztxy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aeshzoat.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cuewdmas.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rliglopj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbodmwc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dctkruds.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeflawyr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbertvo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgalggx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qruwommk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwuierl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjezncp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nquylmmi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsqlscp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urxkcxbg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlgfatx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjufmfq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atnhufdo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulusdqrj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jejiupgt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ifticczg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urnmlzjx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmsffxp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pkemleur.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxlwpvj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgfovpi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2euoearfk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbmaity.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owqeovfg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjylmahc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eohrdkum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2deukrtop.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfekrap.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbkunjg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnlgdif.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvsfkkq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtsovic.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoqalkb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2epamqnuw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmphkpg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpnwkli.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gjucdlll.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfumsfi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwavmvx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxtkckt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qikjjlvi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfxnajm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjrudxj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyrnynl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzlydev.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdifvvk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhnbbnz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdvdnuv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzldwmd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlvzhac.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2anigbhqe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjlcjxj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzzliw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcyrjzi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfosqu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgipsyj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgekqbw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aieexivc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgazgu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qqskqqxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djkrzbkk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzjjygi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iepyhkij.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjflemz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaclrdp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2furrswww.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqecvio.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxelsxr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgqxexr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfaexvf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mrywkxlo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pnefocob.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chvhskzd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fevneoki.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uesopzlr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpmdzod.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2risnzwav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plmduibt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qborttzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhekascd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykewypwv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdfyjp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmckapw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2taarxhhk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivofwiw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqozfik.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhpyepl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rypzssee.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2olrqirro.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhfzxvp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkybiou.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnddwhf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2giynlkmu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxmfbwt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vizbrysk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cixpmbre.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlyrfrv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwqzwxl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxdsvva.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iatfiyss.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjckkxs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqonoxa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vilexoqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oociqgom.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2swizxkcw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkntovzb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2woijilvb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmcjzog.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueepbllg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxibtjoa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ulippkgv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjdmeg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvdojmg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsavnww.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2swpychgm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yysougwi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2odxyvbtq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wejfhyrd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcxneii.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2quauocej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dftzyfgw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhipheb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpmhvlh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnuiwvc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umrbxfbt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rravreot.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2urplynak.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkslunk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoercsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eibiatax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzioqmh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lizznkge.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpazhgz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qumryjdn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzqazki.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2halxyuwg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqvgkox.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fruzzntd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdyyjzw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kamllklp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2alxsqhhc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zexunbge.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzmccza.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfmmop.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jczbimqc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekchawvq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aesaabsd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkpxskq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tujbjaqk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxedutsm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrxbwmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sshuslns.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dearmtym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjstpmxz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsrxagj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joaogwyr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlqzyuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxkxfkv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqyufv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onpsgcak.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaaupcm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2apyibsxs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjghhkxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eickyimq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vunhwmdx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiusmxcu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkebycpb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2njbczyxk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hteftcvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjgzzxo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnqcrh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdwmtev.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvuumnt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtsetsq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmshtzb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asgehntv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pszkqwmp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clehivql.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkfaqrl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvxslvo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nenaeeeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpteujv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2reiszvph.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gprkfqgi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmcaclu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nozmxlao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurgfvoq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2autbqcnw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbecgz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ahirkzlp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphtxtna.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqzlydt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2btksbkzb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxxnza.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqkwjzo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhujjwy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxrupye.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoctqfr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mobttsxx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyfpsqn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkjaljv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeparnl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cohvkugp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsvvtzm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2npgfgiam.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvfpcjq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqmkici.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhacsce.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdphwjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fflfbaoq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxclbwan.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqyrini.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnmwqdj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hksbliyn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgzoyqk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrcfpew.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjenoiw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhfgonp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzcjduv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xveazudv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lfipqczt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohzekcz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoscmep.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficvbyca.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2edouizrn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2toqkytla.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svfdvend.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tywazuzr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwkhxz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wooqxeqc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dscivydr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunvvqyh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfplsi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuirphbb.html


<!-- 参考信息 -->