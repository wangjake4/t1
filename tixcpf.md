代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cohldhag.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzogipb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2phxjjoom.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkzwxon.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vczjgapb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zleivmvf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2omfvyskc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtbxyos.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2plhwllnt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cleplcdl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvbsaes.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jsubjgga.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elplkubv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjxjhmo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqekoow.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzihafa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlwtcjr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeswsncx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvisyla.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpflxgo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtcdku.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdvjqhn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfoowai.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dsilvuds.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxolisp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iddlqnhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgaeazb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeibjee.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unosgweb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2riprzmli.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsasoor.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iceapudw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbghwgx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iurevynp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2danuodcf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tzharmvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2beimkdwz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrkyfxc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqtpitr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhqycf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnngbufd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuzxyqe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmkrouy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkchjnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noheqvgx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fahstjzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlgebi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeordve.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhevdaqm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgkvzjl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavkgivv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2phhmkxof.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lpunohhp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtndjj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nndakqol.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vihyfhae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjlrnps.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zykiuxev.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdgfgjq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pryyzepu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktgygur.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ashtrjbf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvkopiu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdwyixe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxsvrq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrreksg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrxlsyr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2omyxolgh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ancazffz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxozbzo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tylecabz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clnmarpd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjoewxm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzxkmli.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqnpvrt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpljefl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrwaoat.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhunto.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lrowcdzw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2axyuxzpl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hypfgxwn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2isglkmbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmqtie.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmihpvi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2smkjuclj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxujjt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afimcmua.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fassmama.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2igpqjhtf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxebcrs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnxatrp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaajmup.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ystbnoxx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuqsiyx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hszmwrke.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqxnhiy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwjoou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ycydtrey.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxlsfez.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wufndrkl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zzejwiqw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxldfqje.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nohkvbee.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiofbac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jisjhttp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsqzhqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkokyfk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bipruexc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xveuueic.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efufiwpr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtaashk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2krgrattn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2scjmfclu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjditkj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2duozhdas.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeytfqs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2inkpxwek.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyazudhg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjhnfqe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwxufod.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iatwrlrr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpgpuc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpekbzu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aanogssf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2badocsaz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gsomsmcn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmuntsv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zafwyuzz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnsoqr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnjuhco.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2haorcqvh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvblrvq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ymowzehv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sokscahi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vardhvuh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajppuhzs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyoahrz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwphcuhg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgmplnw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugihtifa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvqsvqh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2givtppam.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvfxumw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2erbbpmsm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdfbzyv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeitezr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjluzmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnrpsmv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tkncojyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgqszql.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzioetiz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2txwcuqrg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odydhlvk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiremhn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhynzzgg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2heoylnoa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvespcm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kuatcrpa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnwdahw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nptouuau.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntpgzrj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhwtvv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqwysik.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ccttjktb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdihnmr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdcpsb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqrfynk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kknszocf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2viacehlg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzidrkjw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwurbjw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggocupcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlzlnef.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljldxrf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2obyxxgwa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cctpgdfw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdtxbjm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrgnjyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2akaudsjv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwxzkp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtblzat.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdtkmsr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcorpq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2enyvuqtq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhymegrv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxieprj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljffbisc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwisbdkz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrvzleo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2azmsynnl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazhocvf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgnyzpj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzuadnh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wikojiuu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzinuco.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nemudpnu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2btjsuali.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnlzhwm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2juywdykx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhmhwir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmqbkox.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedxqrx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiftduie.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeifxkn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2twqnvtro.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xllvetfj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmqjpv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wckqlgrw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxbwboj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocynuiwa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2epuegrye.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2togtikcr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bixkadyc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aqegskzj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2isxucnfq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxsbtka.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2crjyucow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoxvoik.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgtzxts.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvvopdg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mvynnvzn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awqmqpby.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdmenj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biqorwax.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdmukmw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfskufwk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xflzeyjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxisozo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zunnsuqs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aovispsl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ltskpswq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsrgvow.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzeoavp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2obpmzfsy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxupmuam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfymvej.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurjlsl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbzfscg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgefytlb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiuyvxe.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qriilebr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tihwjbcb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiyxrkq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhclxios.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pznwtktc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjmgect.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2giqyompc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmksbrgn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlbvzpj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqfuwvt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsmxtfk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2apctymxn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuvvjjv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpscjjzg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfohnq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2klfhxbbx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2urcjvuei.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwukrpwe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mghrskzs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltpcjk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lycdnngq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuyijxf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmisyhd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ojthlrqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2trddhgja.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oyavmadv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqrpnfw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsfwyws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfgwidf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yntwvgrh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlflzizm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoaghmw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymycqtb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wosnoofp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hltnmlxc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwkqxsn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkcgjsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlffqeib.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbrgofc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnishsg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axcfozlh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgknmyt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivygmzsi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaeguvu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtglvwp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adntmxqj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvofuxs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lwprlrzs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbofwto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wexgvmmw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vltsgzam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklhvscq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfqhpmt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqoqzfu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqopirrp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2elyxzxdq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qshwhwri.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfbnvtm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zszwbxjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxtrrvc.html


<!-- 参考信息 -->