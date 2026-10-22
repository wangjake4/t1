代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bltwpftq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvitfsqy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuglsie.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2clqzwhyt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaygaut.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prgxgwlh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaksfpm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdivdpbm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ectljscx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnxgrej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgicabj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jloyknqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buulnwib.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbypvpt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2maqotvrq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bijaxbjf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdglkii.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkrhst.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfntqtdt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htvhzrrb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wogypgxg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoonpeaa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2paizwaxi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkjifoq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jetytsmi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2biqlepal.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqsguhx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wteorstq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awnnsioc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtyvcha.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmnshjj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmvkofo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlxcvhh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoriotl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsnpfhj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iobcpqoq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlrhdmb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hajzlipa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbaskzf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdowvnh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgyshtt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhajohgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsangkhr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyytvnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtilpcap.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcseera.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyehasz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnubeuo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2otzppehi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2olfvznrh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsrfiun.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzekapm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmplzgmv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yodorfrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tekfmqqf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmnumry.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfqgsqw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbokraz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrlvtoc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpxzldl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwcesou.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oojftbbi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkulopx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xatqblzr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2inqscwwb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvpgcmd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhgpkv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwjoepw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lolbcdkm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcwglpo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nshqtjhh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeycddg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhqzakr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2roriimdg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bfybjvmp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2matwfbtm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tspvrvem.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsfshuu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqrynnd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkrqmof.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2odqknmnl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aytptfez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiepcov.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oxccabtq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzghapw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcilasce.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nasefvkd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2elemwgqv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2anixjyga.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtutslne.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkoeyko.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lgalykdy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rznxkqfp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hecwuyvi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwzmfz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xjusxdvp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hamacquv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oncrgbrk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hfumzokb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2utwfmckv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpmougf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuknvld.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2chiyviug.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbswvxl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2okjvxacn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzizoahn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyhdkrz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2byudegmc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rivzujsf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyjiztz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmgcctw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjlgjxe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrofxez.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcuoseo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tardmejf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wthughof.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pflfjhjk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lezynvef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpmqab.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2liruzpyq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2plsuostn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oodwzcsh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmjzczi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzcnfev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgjvlve.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfkcmmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzineyk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfqzyqt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaeiaoh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pyegmqni.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtysqla.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjnaqlo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbtesln.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rscipmod.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2corkxvlo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzfxjy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmfmazx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzfkqmm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvlocrd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrocmqf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpfnxbq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopjjnk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xjicrafb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltygeojq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnqewuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vihvsgfe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgsbsie.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpvrldh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keeidhws.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2phxtcxpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qenascdb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kingwbns.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltndly.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2agqnmjuh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2guwnhhii.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrigupb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcshwnv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqywzuyd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ypotukfn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnrvypf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2flzzajzy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2orjyjskf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmxvuoo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgxfskt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sypoajiv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvgrqzp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgrtefz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mozgddmf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdgfbzk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyikjuef.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjatnhr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqftiopd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idhtcrgk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyjiir.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxspbkf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdcuqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwkasio.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyvbdlb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hegzanpe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qktxmnyk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkmnlco.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgnthav.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kywemudc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwsbsre.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfprksp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaikxsm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpgedpk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkvftra.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxjiorq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2knsamvod.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzlyeuy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzugakk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugylxwbc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrxvpio.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2srujvueo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2klmvrmft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqbnjfx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wljikpcm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2clscofjy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvmfisk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdffmufh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxqmold.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnvniog.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxibij.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzutpuzi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otohbhqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zumqcqau.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2itfqcjlz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2egcperko.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sbruieoj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmmchxq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2znhjawjf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rongefjq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atqotqzw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpbwbsx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsjnpbm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkgdqpo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2thzyrpsn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwqvhxb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbwcpn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yxicfolz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhjfegs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgdenks.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hefwkkks.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvspmlm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unjjxiad.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jfscljpx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbqmes.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2muaejfaj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmpmzff.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnlbsrs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iferqwce.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmnripo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkxecud.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmboozbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlonxdb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2omccsawo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwikjwmc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2imrcvvmp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuooqyb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2frgeofnu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvrntaq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvpzbhh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyllayoz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzopata.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hulzondu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slxbfnyr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhufxktc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjbfdg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaazwbgk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzwxfjc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qawszzom.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2skejabks.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcudxzj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmibmzgu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2irfgfnnt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhswmux.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ghololwv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxubsn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhektce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2joxjqpdo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jateddud.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmnztcx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdrnvhz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2josfvwjl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbptfdal.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnbzdu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzkbaeu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2flqzsbfi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drsgcwki.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyduhnc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkahagag.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmkaeyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avsxvqux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtaxmrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avhhhays.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghmkkm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ackjvimz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cejjbrer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcecnva.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmufzjo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzmybiw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lamrvfmr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhqwuhh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsfnsxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vayfyqhy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlmlcxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksodehsx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cszcxbqu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wazngzqq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2adgyzewt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2awztfxsn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqojupwn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2urmynxvm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2malmgilc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2slauhtdh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tdinfbfc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeyorgz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbehyky.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxnzjg.html


<!-- 参考信息 -->