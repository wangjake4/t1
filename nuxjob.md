代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwzvboh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwssuya.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrkyiwv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjwzhyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ilijhako.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zksjbzsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmkpoow.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iykltgdx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbvtdkh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhofjygw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxqjgmg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjjivdw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsgwlsp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igikqpwk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yndgcddv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsucdbx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lpskgilr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkzawtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aicgthga.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvndqdgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdbcpar.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rctfthcb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuztcroj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyephtii.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaeneft.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgwhvzn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwrprbu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtiyitg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtyjqri.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyrybcp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvmbybv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asvhsrzg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbqyxus.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrwfods.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2octruohk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfeaznc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkrzrbw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyyetzj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqnyfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoypily.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcenlrax.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hniafyxs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnhnrnr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lnspimjl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vylicfhh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2biuczpxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpvjtbo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olsswvpi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnslbdo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mruysuhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tchidolv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkralbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtzbqfd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jypuomss.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxsguyw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdgnhtx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgulhut.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kooyjosu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdvquqb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bavlhpqm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pijlfszs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2povbplaa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvbeeiu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omzqcutf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2higbdqdt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxzauvh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pplblzpv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpulhgb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaipkwx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iscmyzrh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brxlavak.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzrtdam.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlkoshl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsoobgt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phhkotmu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jggwaiah.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2agkhwldu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsinvzn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pllhpuep.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jthvageb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiasire.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2blfzywhn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzjcwgp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sooravsy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnawwio.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqttivxk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjderft.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhoydkm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2buukwlim.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojbbdi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pljfwesw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eohfvwes.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkmdeou.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kietisnv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiegblag.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgsqiqi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhzssd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerxydn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hytymvof.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2khqjfmqc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrtjazh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qkubdcfq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2siwwdccm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aglbrphq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2poocvxnk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjzkvaw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkkkjxs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2spkocnqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfkthty.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxtpyol.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yguyodfa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yppdwhsn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtcoxgc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlnpogr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2meqojozk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvndds.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zchdnjmx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwqrnml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eawsiegn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbloayof.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hemhsxqy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2igiyfamk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqrrlwm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgkutxz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgidvlc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeyovjb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvhhvml.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdllpwx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzqophz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2utwocyhn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xmugzcja.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2atqwfhlv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqswjba.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrisvpn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnggqrok.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbqgkm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtgecux.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2otiwevbe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqsbymm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkithdgt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2parstofi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omvqnykt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wunmrzln.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mgatstyk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjxbywg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pyezotql.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnovkmgx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2omxshlrk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sccuftqb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rymmeaxi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldtcgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyerwvgz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdmcari.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sapjvxxu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbyvarn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcymxnv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkxtyus.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjkzhqx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmvalpz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfbfdqu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnmewli.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2elbehloe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbjacix.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glyablfq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqugpxia.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slkcmjgv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hglhymit.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2llphyjft.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iczjcpbf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoicyoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltotalfe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fgramhlv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mngnxirq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2npekgsqo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmrlwxs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2corxsuaj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gccrgthl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmhbuqi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyazdrz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmytfhsm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgkirjd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdrlotg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mthpnsvz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iwswjcmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzidijj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oggyfcro.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhihmxuc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtjaqjs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmupqqdq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hufkypjb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlkbjs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuhevqd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpqwekw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaebqvph.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfyfgbl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wihcniny.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxrdbd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcsdjcj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwdktmr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjvticr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpovwuwg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtkltyk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbikgfjc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqlbfzt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfkezae.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpkkxfa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdsbgpb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2roevbjun.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittnqpli.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdsvdwy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocjpvy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfjrzev.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eceopnsd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujervsbr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2evjcmaof.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxwsyhi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzezfin.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2riexrsta.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgfpjks.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjbbhlq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdaakvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqridqfu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgroxshl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjokjbx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvpffmk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodsldmv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zyipfgev.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldohnbxd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ruihneeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnarhxcn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jttzlptv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswlytx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2txzgomjy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoewrht.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvenisr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2umosgeyc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzqkinv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqcmspj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxwiluf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdsdtga.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcoegan.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnbnkke.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouosdkin.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iupzxxuu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdqosnc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhlltvu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvwfeex.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojivlps.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iwroaxos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwmfilz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nypygviq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjmcloc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flkpwbyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goafrejv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2illewcsd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqbeytg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvzkhvh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brtngjpg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2obcmhdwa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvdofhp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnbgwas.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysijfpbt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kccmdchi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhlkzcs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnbtohx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdkphmp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2txxqnmcv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dytipdaz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mujvybnv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdyjwvx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2whqcydli.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2flubkgvp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqhrqeg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuvscbs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmryaiwc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2usnjmzrj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvayqzpv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjsjfzn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqeuomo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcjqlzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzapgku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbyrzq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mezoriis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxobcewo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eknshyhx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwchtwld.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqaxrhk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kybupsfj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsqhsiu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kopdjqmh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvylrmf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2avbwcjso.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjwvamu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uishakte.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzvlts.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tibhkhgo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whfkrqkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexrhsgf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuudrfg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwtcjwq.html


<!-- 参考信息 -->