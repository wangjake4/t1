代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpghbog.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2udfjmegx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkzloia.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mehnniri.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkimddq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiqmwty.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ougdzbff.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mekyegez.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upxqmpbq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2netijnfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmrwgsr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jubmotqd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgseqwke.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkijth.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arszgouf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsbnuxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpjwuce.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imzcbnoe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiltztup.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdgjfa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqbztc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvakztpx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcanxyn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kswxxabl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qympdhur.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2perfodpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2peogkvzp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxekdtvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plcmbhbl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oqarnzng.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlmnjic.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvhsozn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdewsf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvxwne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublejwew.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmsbbqo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsielb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdmjest.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbjwnt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2szmtunmt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvagvfo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlfftci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zasvljmk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcrvhic.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsrscra.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvmvltz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iwugphxm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzbviwg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlmdyow.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2velfckht.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eimsfykc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2elejxgab.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqmqowl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2veaxlmdo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxzalwn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqawexbc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2twhvvets.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzvfwwo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrpeqco.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iqurruqb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wkowanug.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tvajfhfr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuqjjke.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgrlhzd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodvwfr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpsnyoz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bsetfvmv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jggzcwyc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsbtebi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmelbgz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkukthas.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrejfae.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jnechcuy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfkmlai.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmfyixk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpcjxoq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2urvtuayr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiajwmc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwmlti.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2etcrkoff.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jkydpdph.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkhpqjv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pljvxqlf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2neyidkkz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqmjipo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcwebbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlckem.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdlwrek.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfezclr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdckoea.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cktbcwkg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2odflwhim.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxnudzj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owazihsg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtepzbnw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nncnungx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2symaippx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdeephk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoyomvc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhyjfwj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ximluxpm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jotjuptv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2etagownh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjbsvwn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzjidmu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlnvbne.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eejylkei.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tglaxttd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqvhzjm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeckvlx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzjkjmo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xahgwsqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmzxiui.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvejndv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odgjushu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqlhfnc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zeydvusu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yazzfhxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwymftvn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlocloqq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzqbbg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nixakikv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvytymi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyccyrb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2giwayhky.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qveoeane.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ziywcmtp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgodgdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tiavjwli.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyaqgkq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vczkikag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duguwxzq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dtposdgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbewgbot.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zypshjol.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxkdnwm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgnggp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2naifjsoq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2idkhnply.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2erafywuk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvrtgcc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wccctojw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jabozcuv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrltdxg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbsoody.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frdrjqud.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaxhwvy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqabgbap.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmarkjhw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2brssnpap.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2adrkubgv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnfjcna.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxspbvs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2monvjpuh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhmcjyg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnptqmvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjbmicl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrebtxmh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vojydmrw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiymkeb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwbyulp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2immqjuco.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvatoxn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dchzbdty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2emlrhyhl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfkhtwz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmiuecp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wljepslq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmekwyu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzlbsc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqrqyon.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvmjgxu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qobhzglu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hoawhqzr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdxyafx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyofykr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlpbgfx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bftbbrzk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcchuxi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrekseo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppslffej.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgumulzr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcnelih.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiwauga.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeomjhhk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uemomkud.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhmuowq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tqovmroq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqkbooc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxcdyec.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfrekd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lexbfehb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2blxyxttv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfzlzhk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2maxdrdfy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzpkvxc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avaqwtuw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhbcodx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwfuzdj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlabzij.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxhygfb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpswaov.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmpykhu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2beqiqeua.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lwujumlr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxldmzl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepdfwf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sabilozd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkvwfrk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqgctfm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2orxdqjaa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqzbaol.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfavnos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2opeqjafu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnpvwno.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjaxyyg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2imlttdnf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kthaaspj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcpdfqj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuhofyx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orisrkod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuoongs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkltecf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2efpqoacu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hivbrcxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsnhktr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2alscdapz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvqxszb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tunwuaxr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiygdfsq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2otsnwagb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxlpfel.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqbexl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvulbsru.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tohjvksd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2igoyjrmy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iidribvy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbtqlzl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lujxjbtd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhoogsw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2odricwkv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dufuzfyy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bltgmwga.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fquhtlom.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkbblzf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2knogupht.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutnxuaz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2anckfifo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokiqzv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpocevy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dogqposd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2popuwawc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waqdfyau.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjyntoq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tofxwxoi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlasnfu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjlcqak.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqbssxv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjccnwyf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dekovpdr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcmdteh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwjotqc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpcdowa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uerirtah.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhysnch.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbngrgxo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoniste.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jokqbjgi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fvugrsdk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smycclsl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaktvco.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jphplxez.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2opsbwhlt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsymildb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrjnzpu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivlglcl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfshgyx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgqjpsd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzzkgzw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxotkbl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqomzelm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehbuyo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrrouju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxjwwhe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyeahhk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fijroign.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mttxiqlc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaqnqex.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rcedldrr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyrtlwq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzqtubs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjfwwjh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjgaqan.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrguykcx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnscstps.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cegbjzsc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vujhodzx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpssyrf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcykteo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eirirmmc.html


<!-- 参考信息 -->