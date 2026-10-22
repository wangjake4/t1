代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgoqhzk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vidgjyov.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcasphua.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfyjefj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsjhrdv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upyhjpdw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2magnhumd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ictnpida.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyepeod.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2anbejwwm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkhatsd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcymsho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmusuag.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aamdgcdg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmkrhdm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdlmea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtvjvdl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkzweqc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgzezyh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvswmhl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbofvrt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxlyafd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anrjyxoy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iofmrkjm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoufxuj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdwhntt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvjlcco.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdacgqv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2arergavz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfemnjje.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxjpibq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dudokoem.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxheivhc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjnfre.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xolxjuhl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2olcsslbi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbdzopm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sbssvxyb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ahptwfkf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjqktzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjqqdcn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaxgccf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvmghdg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpniwxg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhinjbe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkdvswc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwrqry.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwyvnq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qcczaflk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mishcfsd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2htwiovps.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yyizajar.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkejzika.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrckoxea.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aucdtitz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywskspdi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bstypzwb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbhgihj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaeaaau.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nffsvcjj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbetcpjn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2evlnfhgj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tkknduoz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxdivia.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdyyzny.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkmmgev.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flkjsvth.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uknifxqr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wlehlkyz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yuigpzso.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbcteqp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmfnlwi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2itiywqqt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2comtpciu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvleguqq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwimqwr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbtozrr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgciznk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlubwwj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imzgwbmq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfzlhbd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rakvwlzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnginsm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pujqrgnd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qypatotg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqgayvz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdjujo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vccdrfpx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uxutlbnj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakygde.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbipygck.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvtoeqx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ptotsmas.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqohllc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzogirg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uykuokdo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbbcrkn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqscoqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjicjpd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwxgdxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oecozvol.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2picvutat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqfljdc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2evlgkuam.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhzswu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fblgynal.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnhhqnj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pngijivv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oblbngoz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyegkxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2imayixjw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lknuevip.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbrjjxk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoorrzo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxttofz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aoepfgdv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wobpprxq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiwppvq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anfxndlw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjtgswt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lmggwseh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwcsebq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2umwarlvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kojgaeag.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvhoovu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtztvse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcofqxvd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocmpkc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yroizatl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fpidrdgw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrbhgch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkcfvym.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtetjyc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkmgsfs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2juorjvhp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgyrlsg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2imrretmh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mehwikmn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2anaioibm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kqddzhou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyythgs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pafabanr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwhmfpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qssxekfb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrspfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxkrjag.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnegcbqp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zekmnycv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfshjw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwetssv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eubialqs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2piatcozp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2miegpvbp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fxatfdvt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cymjugam.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpslyhn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkabbpb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkiuqdw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tlltkpjq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2turevfxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wianurvt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjbhgy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhadasbj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aahzkwku.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnavwn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2grkartnq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkcekke.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkmffkb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzanpxzy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cismhiua.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkbaesu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzgtnvg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qumlunjs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhaammm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwmtkbs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlybykpq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmhiotz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpwxoqf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcogiz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bfavjufe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxinvpny.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kizxbzqd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsuiaao.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txjiiwqz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvllavaq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvtbodv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmdunjz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2idrjzfpq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2axkzuviy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftstsjrq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrparmz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqhypx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnfdcwr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mugbeszf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gznkemln.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjsjhjl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzybwwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtzebhm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkafskkt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtvstye.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeakoiz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2crasihja.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eciiiwmz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrrykxd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvghuue.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sirrnwxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxtceme.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2abkevrmv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gjricqdz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dutmpuzp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eorspkbj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etkzpfmr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlagluvj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmkxftc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aiomwroa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzuwibi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2viyccskt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyyqtwg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvlzya.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujnjhnp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqzqvvi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmroblh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqmywau.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdubaaoz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyldfvu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2koqswsvx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqajphpl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtwjtfp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqpdvmk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfhgvak.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jscsbhrw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkardkzg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkquvdoz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yivgbwkw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gglamyrp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojegujov.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzuuxya.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzzelgg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bpogzmtn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgjjiss.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhsizvt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zasgkybp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxrrvma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavzntbo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtxcdku.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feekjfgs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrrlmzm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiweqnx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclwcsvt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyqxgpo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpcgyrq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjqbgcn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fliibxim.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vopytjjk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgquboe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yulhtulw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqxyndj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbonrrnf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jneymewg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpzxxmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeofrgw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxphzwr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeiwyhh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sknsbvyf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuyvmaq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzlsvk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufveaypo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2trfxglxc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhtaptl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xaenezso.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzkcint.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bauritbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2syhipbgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpgsri.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsamoqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crqkejft.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgculxp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiksqtu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkslpws.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnjvcax.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoyvptq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbuglnh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2otoelqbz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgcgffg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uivpqees.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbwkarn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwsozcv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdrbzwv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2htftlqlj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuocirz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhfujvv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypnwnmn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwnfiv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2afhbkgyx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrhucoe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrkrwht.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpzspfj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykppdvrd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzhbieb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzicbsn.html


<!-- 参考信息 -->