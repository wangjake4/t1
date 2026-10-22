代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwkwesd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irkrtdsj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeeekhs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mioluedw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjdotx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vplfcfyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wanogmbs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyikmoc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpbjqhd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnuqxww.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnvderz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wexfkzlj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekichsfm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiegoyia.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpodfup.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgbqgri.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvqxkiv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqcdakv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kihythun.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qffjriuo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdopdwe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fllztyyb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjebquz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njlrnugl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpecfqan.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrnytcg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glbfddom.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzioiqz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hklfszal.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfzgjap.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avghjydx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwttrpu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdbtwiv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jymggbam.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaxqzvv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgxbvdv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwmxvsn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqvcvhv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyqmcbo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htbwkgkj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjxxtwz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yaimtpae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uslajgsi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfcrlms.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rscdkqch.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgvytwo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdohmdbu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qetjskiq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkfhzqa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ychpozkf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fffwuahq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhoxkdv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejasbowr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qnczfmwz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpkkvva.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bldepepv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdhcntg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2guzqdccc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qipimsmv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2patcmpnp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2utcqpelo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogixzooa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfnopfz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ttucjwwn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvljvpk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zeclalxw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2reawgqee.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pssvlqmv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgshfhj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmirfvi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfirqvr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnnzjdx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrzdnxr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyomfju.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ueammdjr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awghzlrw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrphphw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2npofuxuy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhwmcri.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2clxrlxlp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tqedehcx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvjkvzg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwogqdt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcwuxop.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xupyiwcs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvizqca.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yehsytmq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpfnuvp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzilavr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfelikoe.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxeora.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pldksipz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2orhlrlkn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lggouoxq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qlunyrvj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2codddrzo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oeejjydc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfwjvcl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzyxtmj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhezlli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsfpakb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvihcdxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2etjrihlr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvbtmgi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2trudpdbd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clvdlhcs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqgvxiv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dujsxwll.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgetlq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbndnpa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzftocsz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaapspl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2htuzqjks.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2snwtioxk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qltrlwbl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2trhhsjkw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2poijrnac.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhsfgvi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjsaywf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxideav.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcohtvo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwtvtrj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vocalcbw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggklhf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmjnfef.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgaesyf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqysohy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxdasjz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoidtkf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeudtwm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrlxmrr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevjdvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzyojxy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeqscgp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oodijlzj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhqcohl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xlisvtoi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2isibpuva.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvbtygg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdzupvs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dznuqhgs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2otbufgqb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ztktpdnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqyntga.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sknxavtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2andzetgm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srrmjrfz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2psdrvtax.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqgfbsz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2msxkyztt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnkzqzn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfunplw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wotiikxl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dscqdkwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sipcrvxj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oyotvhhw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoiafgn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ystqealt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xaprsewj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dwadcajv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hokrmfgn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrmmiy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytyjyif.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qubmgoet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzkspzf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eequnmfe.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nomdsafm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ontpmduc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrdpkqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzagnvs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcbxyhc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puwrtjvd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvzxgxt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bucubiyt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuihgkmo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkufhzv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsjsxqp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhndvyd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fccohfet.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2itbrxihc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzlleck.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2beabgild.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2spvhcjhs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqkvzye.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohcrovx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xcanfcte.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2orqgvrrm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pivouqzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglfdbnw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmeomwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftmeedd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uypdqzka.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2filjyqfw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbyyfdf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffugdjpj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkbuwol.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyhtlxt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2boufzgaj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rouvvjkg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhpwiet.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxznxesw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeszbxr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhieszyc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuragnjw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2attfvkra.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqabygk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmorsjzt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eefydpko.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2efleupdb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ophknjde.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gupeqcnl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqwlusf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qegaquap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjxunuo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfskodsz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyzlyda.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdhtwph.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guswegvn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqiinjp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjklrky.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvxmdji.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbngkuh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsxqubx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krdqpbkw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmzeogx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhshobp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swjmxvdb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zblqxfiq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aolbuden.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lphveksy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pklqcbqn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzevjer.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfddplx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsdxgss.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzedpf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rewbmsdp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqhgiro.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rolqbcqc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wswponbn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpkjtwe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfujxrh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgvqmky.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ltflpobq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whfpssme.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klaugkru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmbksaz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npwbeltw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbbozs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2geojbaop.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqtybck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuhvonu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuoqrvw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzibmet.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gziallzf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2osdivbtv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdqvdr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rilvlcda.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbhlzaf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pghonlgo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhxlnyl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpwrmjt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vdspxtdk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnocntzc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrrvvmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnwvvnc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnsyefj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwgvbnb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtvcrvd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwfqrzv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrsdbee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lakopqus.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtboiek.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mitncfoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uozwdmiw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hampbadj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dokvrdqv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnffqcyb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2smdgeobp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjxgkk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2evbgdykr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbyvich.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuecffcz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcehqa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysodfvaj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqmvqba.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwtycyq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqyiqij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyageyb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsnydvk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znbngsew.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2umrukirv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcplvee.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wumyyztb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhions.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvutghab.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoolzerw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iztzezts.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgouyck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dubyvpmn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazdlgp.html


<!-- 参考信息 -->