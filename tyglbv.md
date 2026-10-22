代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkqcfn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjyceft.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrltyi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzznuqwg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sybbnjet.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyjamna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rixqnqfw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wskztxhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbhuddq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ieakybgu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcuddsj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tknmtzwj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbgvofq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2simrxkzh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbxbcaj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkonfsgq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuezqrv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hslvbkwy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyysjcct.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wndoccmr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2feupdasb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvzdndj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lyehgzmp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaagfxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elzskbyb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2haoymoqd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hetiickj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpoklaj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnabrem.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvejjfw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aijqtnxq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwonnsc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sovomiye.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjzigvg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2orpqrqyr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2croqriho.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2molobiia.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctghoksf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvpdgty.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxmqbxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2riluafny.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjihumvf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwfugjh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrcphgf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmceclvl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrxrmdx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdscagqo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiwswjh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvizgmwc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bckhfiqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2avznqgla.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqfvqxc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrbtkdb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjavfiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2avozlnsh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxymranc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuprgor.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvuudwz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjddfhaa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfxruwy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2raqmvcge.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqjtnw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hommphka.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jygbpnfr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbtxzhi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqypghnf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vtznclvc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnrnhms.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebysznmc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbtovnx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmzvuaj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbtzldf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2goehlkkl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbonhmsx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2baiaztpm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjxfezi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfehwkb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqghhdt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czfnleic.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbkopxi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tiylyqvr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyoabql.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2afziphgd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsmtzxp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eufnpyiw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yoktqaqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sexawfww.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frbqonex.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atidajbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcrxkm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzxgpcx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwvvfrt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fspkdskw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oostjymj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmionz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2szwvhrwr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqpqrxn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbipyqn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omggdwch.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fufwzyom.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xyppbgcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvawycv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhchlck.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiuiqsi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2njazwpuv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isnbdrta.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fybxhhin.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfwluft.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmhseqk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbradcw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mipyaqfg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oylmlduv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lggugrsh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfetdhlw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoktenb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmytzny.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhmvea.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxeozt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2anyypthp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2whpxekya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uivnrayt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vzztdztv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2txiuktmv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtqttxs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukyolv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gsutyccs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uinyorkg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsajibti.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlojlrl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tctrfevb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jsupngca.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmmdca.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhaaywx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2blpszvii.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeoarqp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2apeeijfr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgsfflw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hlerydlz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scwooqsf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgaxwuq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2selzajbj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2enlcjjrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2empcrhlq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvvzqgp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2islivkkw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toccncgl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2huuywfts.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bimizism.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2woepezaj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ymecjyrs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmwypag.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuaqlcx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swloihox.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzfcsie.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxnuost.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qerbhfnp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lytseeue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwmhvto.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tijanrpk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2klcoxkbs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mostqefa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrsmrnf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkyhsw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmjlegw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ortunlst.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxzhoct.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqnaolp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkrsvh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvnknwy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qetnvhsw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iapjqccx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xxacpmbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qicsttrf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pckuwlri.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fradehzf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrbfja.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fyycuiwy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtwazwy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hootjrin.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wawtplsh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ublweiky.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjmtbfy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjmlltw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljotndqi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljajqvby.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgltlwaf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2icbypdck.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysepewrj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbusyos.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wuncnluw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2drdxazmj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iispvfpp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmcitdv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxajvapy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrypuvn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzkwzsv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfoxxoh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2okmziqxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqtbjmv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgowlocm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2czqlcbts.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqvahzt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wldtwgfm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxjzsfu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vebpdvuj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxyfuqo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgjryel.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cwspufdg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2epjhqrlt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqbjvkj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aedcngbu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oabdrnwe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxffyglr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqanvquw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2idbqnvrr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkocddbl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hprbmwmv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjjtonr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsddubzj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2neawkyuk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfccfpg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxihpqj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcjeqmx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2caebbpyl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lypnofle.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fexmsvqd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxpcfwd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ughrjzjw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2amgkmhxf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmhmbmu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdfujpw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnqcrrx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsesruq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edijlgrk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuejtek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonzbqsw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ducslmlg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkjnkbz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvfeqtt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrtqfgl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnntukv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxgipcr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vabkuppn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycnwbog.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mapuntim.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfmgqn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysahfqlp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bixcomkg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyeussm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuidpkl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihepkp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvvera.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yeajkbpx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfirgkb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgjdanc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2excahyry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuvfzwh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpvvukf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnyckst.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmfemvt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvdakwz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kikbabjn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2knimyadv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdvmavj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdykerj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfuvqnf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dklyihkm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbcwusw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgrayhd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2govigtxq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyroeanz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxgnink.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsqijvc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmudzjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqrxoiz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeldyxj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtnkphp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2topkmbvu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fojsmozc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iosheryu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkcpmsz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2semdhuep.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjldpyu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgktzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2muiofewd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phknkhsb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxqien.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oguktphc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsuuqqr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyseynmy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stijbohj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaugxuy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eozfcrjh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqemeysq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2monxbmow.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2quhraskp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2srmoepyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vviqprct.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzizzrx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcplnoqa.html


<!-- 参考信息 -->