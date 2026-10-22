代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uccftrai.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkghebd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iusoxxln.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpdkrlh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzejrwi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhjejkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nkobrfua.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqfihst.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fshqhiij.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyzmoai.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sewvdrcg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlkffsk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzsjfxn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsttbwh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2quchemym.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2usjzuqnn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkaxtl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiiddln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzcqmwd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlquxwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfpvkaq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2obcxrzvl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgwgoep.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeduthk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hazrxwyi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmedpzqp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trzbnqwn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwygcmtg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvypibip.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aeywofce.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmyqjr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxifisd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgrlesa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xquwmlza.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sduflljv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbajqxhp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otrpgjak.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfhlkbg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrdbfuf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzapufsm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pspoibeb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyxrtpf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyknshu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nvotemlz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdpwakk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsqokmy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjjqlyf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsmroxk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2degahily.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkxhhae.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqairsg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vibsfjxd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbvhwgx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hecgyksw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kawbhgjv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiygmyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxcogpg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yszhqqfe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwywkb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhmprqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qaenzohv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2siiuwesf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uupqjuzp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2krvfercj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvbdqaa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2etpeslhp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eszyppft.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqbhezz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2raaogsut.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzeavef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzvdljq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpslynn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkrcdcc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yufyyauk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnvpirl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qljolxfm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnrurpy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxmtlhf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmadahox.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbezttps.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtcsuhh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoczklf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmvkpo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hsicggfv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzkruod.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjstklw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2imigohvo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2llkgcjwc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wydvztfk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvexqlb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiikzyj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeyxedj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xokcvufo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2owbwvnbn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiwsxfb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnrtzgu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2crwduyos.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvrrsfi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmwinzl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2argzxfme.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqrrtky.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrgzuw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbofvem.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfgwdor.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsyotqw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdqtzxp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywfhog.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwffwjd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrlufl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tchweotg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pehuskxd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hwknmxhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rhljzzbd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbbodc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2akprvbwe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwlxtij.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qeffjpwz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlttjhfi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnjxlxl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nhszwrkf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2eiesqifl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wotqcjrz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuernuj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgrldk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsckbev.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2znvwgrnj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnzhssr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiunbnj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpdxooi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yymviebj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkfdwyj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnyvphk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxdvrws.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsmanpw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkrijsw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxielkqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmnbfqc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrmeuro.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trdgrtly.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wzebxjel.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2clvkmdog.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kccddhwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkisvmos.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbogozu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzeaahh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlugscg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwegimsa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxpnptw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwfwuff.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxylfww.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbhmysf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdvnhth.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2moezhust.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdupwlm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jrntmcxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnbfcf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuupcaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tawkxuni.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqyuuby.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jguaeocu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thktstqi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijfnbr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2klblbnws.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dksavzrp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2obhffymn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qswcuntq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyqjjdu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmokgca.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgvucf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkqkvln.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaiullm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzecin.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcofibih.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tybpmrhf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yggadrpr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrzkky.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpzyksj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpqnpig.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkajjonb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncplcodz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2geidqcvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfojybs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqalgnxs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsycajgi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyozxhw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtupbso.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2czjpivjj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzncdlrm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ockdnrwo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaduoub.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yntchuew.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdovpwjf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2crahbxxf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgfjieg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypohwmel.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciccopce.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdnhclx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvuyalw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afmhlvum.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2httnhvix.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2roauqcnt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuolaie.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlefgup.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2apotoesk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2swbtgqvh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzufglwo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbyvzgh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwlmvlm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuwdnb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2irctqudo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdulmmat.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xncqrpag.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaqlnzy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kavumwuk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aemckjzb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mobybfhy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichhfxsr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqecayg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyyuvio.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jleghuii.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qzodidor.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdiexvb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oryedema.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbxtyzn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqxjwfv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxutyjbt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghccbvyp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjutwsfo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xytoynul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpuiaiw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwahra.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jghgdqat.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbnpvia.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyxnrzo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvnokc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsmszha.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvltbuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wonyfspp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tewtsozk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxukesfw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dguirbjc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyoiwus.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdgjdlh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkkdpib.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhzffbt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwrylsi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytddfzc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwvipz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2blghotmz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzhmgqa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ueogopod.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gynpnyoa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2irgxgizd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bquhngif.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2quvislcz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzerxtwk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fanrzbgx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuekarh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzauwpk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2krqrqjwl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhqsqao.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akpdmpin.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdnnjcs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmpjsni.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkguhzz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlihdsg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjwblgh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iucdigoh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnulqzud.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmjuojc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oacmehvk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzhgavn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmzgvct.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjxwbhx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfaqcoo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpnotno.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzavzix.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnqiwbn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhdjtup.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2movafllj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiliblgh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zslagbcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxzykfw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaymuea.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2njlvayiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrsfdct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhoclca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atgcxfno.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elmccdxm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2trlljpwv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaeudqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqkoiao.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqbvvtr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjrrag.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2thhmzjxm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xuravkwl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdpffos.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfftozii.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklrgvt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnsouol.html


<!-- 参考信息 -->