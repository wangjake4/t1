代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvdysfu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lazxqpvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hurghjge.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vosdgkte.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcyrbom.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxbcxon.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2feooekle.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfuxctu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2plajycxo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sobspprc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgvvxdk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnboza.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnbdrnj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccacyrfi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbwdtsj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehivvouc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvnrnqa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzwvnxp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsxsros.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qillqarm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ijphpsbf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmqhjcm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ziecuimf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnfbkbt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdqfhus.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gehuafbc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwumhlv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzlicpp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkdnyxp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkemvcsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmbwgsi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igvzoirz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjmyoya.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpihbeqt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2livgilrt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnawixg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtfawoa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zufhqtvc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnevdisw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhplmukg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nusmjace.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2msgwnjki.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkunni.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqckaoe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jngijhue.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thzxiubl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2knbasbeu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jxytlxrt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tknvlvod.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sgapdxuf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eksxyter.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbloobf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkmwovu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxibrra.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevmyea.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rminzder.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edvcrnxe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkbxpat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhribtds.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2whkotkzb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjurlbc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwidazy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fmefsosi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2acsxnvnz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgihlpy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwttcozf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxzawba.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfguwewf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgprizys.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpepxv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tubcvnvs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hvypalzm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oezeczti.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lseczqxj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjwjtzp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqrjqgj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncumvudv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xaodbyzd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfnnqaq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcjliqt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vybauden.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwuwnk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2anygispg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2orziwwyq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cunewuka.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxvbqzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwyznec.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzewxkfr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fowhrgta.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkarnnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uctijnxv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdsiyop.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dytpfzhs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ksztjeko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaooxyd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtztoqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eewnrhzl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hujdpdvn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnkywov.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zetygswl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmpuixn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nosbmrsl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrllqieu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjsuukg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2egcpghya.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqtcqxw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtrnbz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuzfevl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xagwvuwp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfioret.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kazfsnjw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjresah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iilgrqrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvhbnen.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dryaafma.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyeoirv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrcpgya.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chnlanee.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqcwcid.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhmwfu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xradzyvq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgtowvz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsypigc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoblhxc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jybxufnt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2haxipgcj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aeefkqbn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgructrp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqqwgrq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxwoool.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vynnsskw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmuctuf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2somenwcx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcyyuff.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwaeex.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cggzmyrw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzgsbtb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzmttkm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtaxemi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ebplktrj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bznmxahq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqvhrgr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oahnfory.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gspaxaut.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhxgsof.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxzzbpa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzzyltu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2baejxhpe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuebjos.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2akjvwjme.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zoznbaby.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2osrmmdwb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kddibzot.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqrlptf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmozasd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgrzfv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dntcxodo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhenisay.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smjccovc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nmksolla.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swuvdykg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqphrrt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2didydyyo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2emkdefka.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfmdudw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfkppjr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iniewobt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aiauobqs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rntvfiae.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdebeky.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2txufrnye.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtrqgvs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvkcsio.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkuskeh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2slgbbjqp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yaezpana.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvfdan.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmqcebu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqseqgkw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyeknvj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjadgukt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrebogl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2txfylkcl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mguavdjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcnykz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bukufynk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikvifb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmmhpol.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrihqwjs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlwvrpw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcvljab.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkagfoly.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxylcetc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlkcxha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrgchks.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2reejzbbk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbssmiqv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mkivaune.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2leekvaia.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnprimx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lehdctbt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rijdxhud.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2syvanhhc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmkzrho.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2symvbbzy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmrejgw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhupnjj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hziqladm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mctqwyho.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yohbbcgb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2louspbyf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rxervcvh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahbfxx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfeseiz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeztotun.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjolquyz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovepje.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xekpnjfb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgdmmg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uibeaxpc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlkquoy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrswtjj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rbquhcqs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plbpabml.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvjpyer.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcibtaac.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oojvdynq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubvwxg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjipvla.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kglgjjif.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dandxkxg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgshsuy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2btjnbpdy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slaqlhcv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbwohvt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scugguyh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2quutaghy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkhgtra.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrhxmr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbexbjp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxbrqpf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdehddo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okxsqatd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqkjdzy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psridbev.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfasropy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thfptxhq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfufhgdy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqzvdda.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cntnpfeo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrwrjrr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfukplmd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpudndo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxyhijm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2izqdikdh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2angwrmmc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqmmtuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjnzldw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmlwsuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqoysuz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtklnwfv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wccjkoco.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhgcaed.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jepshqfu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdxmcku.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2onfwgbkp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmkyhnd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsblcbe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzczupx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsojcqh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnmsqw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obpcuuql.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnpsces.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uuagkhyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzckxxbc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlbyhcu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omsctjcd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2llzedmeh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovorsrns.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2albeskdo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpejyhv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oudodefj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2aatjwqjb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrfnlni.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuasvcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsyteq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjqzyac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxfukts.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdufvsl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sabryiry.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeuladt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2trqdlluc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyxcvxg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrtevml.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2exlptlom.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opothvvf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaoyaqh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdyhqlv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mudentjw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgdmqsw.html


<!-- 参考信息 -->