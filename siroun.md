代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bojyoywi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vclvdiky.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2huimcguj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cefhkkip.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fdurwshg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxtdovb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epybbhmd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfqcxrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smzszfmg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxqrrgh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvwdlh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ainrawhl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcjtaua.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2psekkdvb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlflekqx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwskdkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sufukhvs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvpabc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwyadkb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaztzyss.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzxolqb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2szhzljqn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dggehmll.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bedktzvv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2garbwceq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dinfftbk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sihehrgz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeovltw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaojger.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2riasgpda.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvqjnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxtsryk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpmapam.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2spnofnjy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2obtwuvun.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wyusqdzo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xphcqurc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uduyxtzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmqdmzm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprqnwa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2weftpmbb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlrfqky.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuyfcuw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyfccuv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqnxrud.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxmsnth.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfsurir.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jnytyonl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dysorkrm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrsstek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2exnyopym.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxwlerx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnabhpb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2apayabth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwpjpqm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmnfrnm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlmojqa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uejrufza.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvwfrsw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmbjtpc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsslldxn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oolftect.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmnhbbr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hakqqirf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2itwycxok.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvuubbq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzmsnnk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuapbaf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuncyrp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaosogi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2snjwjyma.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iejjsarp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpraiyz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwrkzuf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2isxxgoie.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niaalgks.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvgamat.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssokplke.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szhtxgwk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gylyxjjp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbowwnj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwmtdwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjubhwgx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kuczycwc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2htillepm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlibona.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcezprwn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpqeoxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vytiyddz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxndnrw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zbirkdqh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eovvppzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dskrlqgh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfocckc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuetrcm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vpszbznf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnjylxm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgdyyos.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcsykwo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ippetmqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkffzax.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqmzay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xfasdzcm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoqgdcx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhqgkgg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niihedbm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvcsqg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjmxkd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcdpxea.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wphvioti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyolshe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oftfakoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvoxxfy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsurgtk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmlrchu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vsycxjvv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2neaayzvh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fszmgixx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjlwtaj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxeitct.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrrfbmt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlbfqsr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwfhvlo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbbenwz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqshpslr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dqllduoz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cofmsfyt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bszxvcqn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjeezmc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkacetc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyuzyrc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqgmnhg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrewvkmq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbmznko.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxggaki.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoqtztq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdaayzf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bponluyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htvppcok.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2slidzqyv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmtawkk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyqoomg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjgeszp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnizku.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbpmaqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvsihmc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdopoxhu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2snstwoqh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzempsfp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmffinz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnrvtzt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwllohvs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ommwqont.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgnfvvl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2maiktcow.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mloszpyy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaoveiw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvpsjgn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mekmxpdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iuljcsof.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sthkrbwf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffmkmb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vozvgxwv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxuvyak.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2txrswbyo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dirisyoi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqkbuc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcvjedk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmbwlfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaerihxv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zehquprk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeaxbrj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlfxhbz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pzirlusw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyiodwp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeniurb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2awktfkjh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxegjuo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2krjhvlxi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlqrwud.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anyvxqlq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ynncqfpr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgxywsx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtownfl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiujxpv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcccwuh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xddlziun.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lydhevvu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eagiudxt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdxwrzx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2snvkrgbb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pztofmzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aucbydrd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdajihhx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqnvzzu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjsxur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2advpezma.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2juxolsue.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2urbefhqf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gwajhfmw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2luunlogd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vttoqqrb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhgubgj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjpzmad.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwsusbj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apyqjdon.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdxurt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqnqawl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxxxlq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzitce.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2avdhprxe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtvlrlv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jaswfgxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byveursw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkzdgsl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2urnvextb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2anxlphfz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuptvdg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nvncclrj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvnafad.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrhtwtz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiwgtjg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uvworstf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpckdhah.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2khakneev.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqfhalm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxskipqc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjfwfud.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmrjco.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xpulcllg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hijrktns.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyovzac.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoypyqf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgdixtv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yljipwiq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtaujm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rrknogmq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvvvhdv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfyjdju.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrdwmx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwepxzj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdvecnw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvyvsl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqucgcoe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wevycwfl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvvxibo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyiwmcw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjngelfj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdlivml.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvflmul.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2whngeagv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2witkgjqy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtefacjd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkuiynx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyahhmgy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmrdryr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzslqmmr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzcbln.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sweferac.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpyfbje.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwciddu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkwrjwa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bherwuty.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrdtgbz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaoevrv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvngdapj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdlryus.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrmdlwg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdzjix.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2clxtlbvq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvzfwuj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pazbavok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2igofjujp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sikkgdma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nquyfodv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbftwtf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nntxtcmo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgujgkd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jostlrys.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hjccagcw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwzkhmp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qesnfxcb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2syyakmks.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpciiyb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiftzml.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfraxkoy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pcakfztb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmmqhfs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbwrqjl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmpvoe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyqnqgn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlehbdv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hydeunsw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxdmqqq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwacovfi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2btjirgcx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jovtbdoe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcsecun.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyksswr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2peiicjos.html


<!-- 参考信息 -->