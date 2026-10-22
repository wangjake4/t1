代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbabutf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmnbfvc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzaauaf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oelrqxgm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmsqunn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jndqfrka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vciwfzej.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzbxcsa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apjlposq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxncffak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tnesnwie.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbkxdes.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgzthub.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylbeel.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrfwfib.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbjfoyi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2emaddxvy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecngfbie.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aueqwuyj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qleakxzu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrndsfr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcityu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dficmtug.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdkslro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aijeslvi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoaauxm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpvgedj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ursbhloj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyqpnus.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csldbgcv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxkqddm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iszjfivw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnmfsem.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmasqvcy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqkwkmz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkqtvvy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uunmqqdi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaozmxyr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otdqtwkh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnzxlow.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suaybnzj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2havctozv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yntntpzr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wijbsphy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoclhrb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eefydjyt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eayvzldb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iqinmjmx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anjohtbi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eswvggxb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaoxoey.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2boolbtkr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vknyrklz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvwwowh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaqjpng.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtcwile.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxdlxwm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ennbyget.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvjoqqx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gthxdyhm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxrgue.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iogtvofg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnuecvs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfqcgj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvxcfue.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvdqlne.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkptiub.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoeptit.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfvvyia.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfnwzpd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuddidu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmyqlox.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahlocqm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vugcpzje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgyhwnr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2acuvtjdm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2byeivayb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2skhttdyf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkaqcbh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnwjrqn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqcimxj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tknolxxh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvcckoa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ticrpsbb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ljplchxp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2geakdjvl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zielyrum.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmpplwo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wboypjlm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fbomeyjb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2baacuxyf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shxrsyqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvtqrcw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaoqtcy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuuheek.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmtvslr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkibaqy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aiurzinb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmhfkpb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpysqcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtnzkgc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2itezuxzx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewhuvl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zyekoray.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tvklppum.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzrajqt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fclbedbt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2skxkdxjn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uswbordz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oswhsldp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjvzlcu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2saatxouw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqnwdnh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqczodpe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvrxffd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvuxdgg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyemmtj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sndsjglb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbuyzml.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhjmxsx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsyaqnx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtirzpsg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhjpjya.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2arniojom.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwnhvgn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqowiqd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahrkuo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2alpissuz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2costcwiw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmgvokd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nurqrlmf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjnwxr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zsndmpki.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ermfngoq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buxzmeca.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvoasap.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xssmlsyj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xiotfxpj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkeguqk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgysjiq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmaewam.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2odajmqwt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfsybwm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmydcmo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjwugoe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ievxhkrr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzilbrf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrosoyte.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiijemsv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vazmphzn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2opiauaaa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2suqkuaqg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkqplvv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdmvlzf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atrrvyam.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcbuiaf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeevqpc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnxutuj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnoiziy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qifatraw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2faupatgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drsfwzen.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yehwghqk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2udvgxtwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxzkxyb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvkmtea.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2heghnsio.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwqfkxk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdxvuje.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qtelrrpz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iljwaaei.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2drurggce.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdntokex.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2caknewqb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rfppjmch.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzggfdm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjajla.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2smbnbffz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnpymx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2annlhyqm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2khkvbcmt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2paxzksbr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfjzigr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkiycxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2olirxdis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2otboytli.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rogpmqcz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxahsxy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xderlsfi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiuxkfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wckfjmns.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2devtrymq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mewnbuyd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrisca.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvgjomn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fupjdtyw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvdumfz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvfokec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2omldvtxb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2butzyytv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdlxlcb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmhpmto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllrkvku.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgpvfzd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2syixwebp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tzonlwly.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sabivgom.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uczjfqjl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkkewnv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfercle.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfezebcu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2znvkased.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2soyoahwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyzyyeh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpgawya.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2viydorem.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhsxyme.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uojqtpfv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzwvjt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aireitgl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2swakrsep.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2madbpeul.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpavzjfl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2onjjdqpb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eabzrcev.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcswkbt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yujkbkrz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zelrwfcp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pilpzllj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsestgd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjogctk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegxrqc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsqgxux.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyboqzp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhofpjq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxtxcxv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2azcqnvsf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkuxsdg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jgztnttj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dggugfvx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iucdjqcg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgtnnua.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnnbdh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rromazhq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ptunggdl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaqdkbv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtndczm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdvyrov.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwkujjg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ammeorjy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2biktbtqc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogyihn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hkezduwu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxypjgoe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2setunzli.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfpapwv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jftderfj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujukzayn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyapjat.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bevezmik.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lygxdpfx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsbzmfk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqmptcv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2toeieeju.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2quspxcgq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhahrti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxfdcic.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2orfdqcvo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljnjehp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajimtdio.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cijkrtej.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvwoma.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nizpwfyr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvtxtso.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsrfzcb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2isqzeyiz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gudiltom.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2plixvknt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemjiahg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2aacwugpc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smlpatim.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlizdprh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnlqqhd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nopuniin.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aldgiikl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfidvsb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uobsqhyw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2negzokut.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmcbkro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cizikmve.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpayxqgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrmirrf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqhkehy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpzzmgi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwipjrbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2drcuttox.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhtzrsi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgamxik.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlbztnh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tveuzhdz.html


<!-- 参考信息 -->