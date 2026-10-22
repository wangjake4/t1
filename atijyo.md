代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kirkiwth.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfcsxjo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgpnzey.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsewhcr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzsqqby.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuifoyu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qybshqoz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zzioqgiw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdgxiyf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2javbkcqh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mscbjeji.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkwfzgd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukozgpof.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdudhlj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osdaucua.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dknqkpnh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjryjcsq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ednorinv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfjrzeh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pheozxwa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2trewnajv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vivgjxil.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxesqal.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnjchvs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cquqidme.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxhajyg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlewwhbp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfxvacl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyjmsqx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2khuisgan.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoynvhf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cioaqcir.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2icxlydvf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbttzvqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2arcgynob.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znbualod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpthoko.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zotctsww.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tqugksyp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2goncbrdf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigvfhai.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kshfcrxw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsqrva.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eemjkvkp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuyvbqh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2etvbecut.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cndsoknj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2puolvbrs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaiwqeo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2thcqhywl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwesjdts.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbdpxaf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzjyinc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzlhrun.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwgklkz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pqolzajs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lquyfmwo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmrzoks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2plfphkhe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdpmjje.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoogrol.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqpjeel.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcelsmb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzeuri.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgjwcfs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jiypfzij.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kactizlw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhxsmfr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbrgvye.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgixceup.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrzzjfb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ipllrieo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2izcbosjz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoszbhe.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vowvulxh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2twbltflu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsevavn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvidvev.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fzblgmcf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iyflmujo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjirfmp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbpeppn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjmdicq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iumucjdg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmqxdwv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdncirf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igqrbhqu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmftiji.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eixftkfq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfcyxpo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ltufhvvf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jixaykyu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjkhfv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbfsfb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoyjltk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrydmqq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxvtgmj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nudoirrk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2veoxxsza.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xanedmzb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mdknsvsy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnpredt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhraokx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2upjilgvc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbitwd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bxadvvhz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xabpeirq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2udikzjcb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkeegwh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zhczsvni.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpdshfo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxnczcd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vubjswqx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yyocylbd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yatlsazz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgptnsys.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjfntjq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgyanib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqhqovv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wumabojv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuadzfx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmslydp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxndptk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2acovkmto.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yznbosqf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vevtjasy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2igvyyplf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abrtgfez.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sgitpmqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwunufgr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rswmgxzk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxbneoq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzjpzua.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbfchca.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqnyzsh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnhjpun.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mblkvmlw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlspxjls.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbyjfsa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovadlyox.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isaxjmzf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuafkbk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uaczxuye.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tapphiva.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wheozvva.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzvsfqw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjfdsth.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzerhiu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fybxzbvb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcyqysa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdijijso.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyrbbdj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sivqgakn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srdbrplw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdinhxi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqufsfjz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcngnxld.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjjrekx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjefcezp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2evlyaujv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwftigpb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbeispn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzftusvz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcfntci.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqdireo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvvujzr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkruchii.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqpfxmc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnkqyn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxbfgsx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oboheoiu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iobbiewr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqibzzy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkvdbim.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhszzazb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhoaylx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2impswbri.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tybkqcyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmqftpa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrwqrha.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbymaclu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqbupsn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqgcwnw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cjddyrav.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgbmvxo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lukamsjr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2crrupaci.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiupyaov.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxwmgbp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwhzeal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwicsvrt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wluqvcvp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gntwrobf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qttvidug.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tchsfpcb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxldrmsf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aysiohjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzpadwo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imiazmln.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzmhsji.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdrsohn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlqbasz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuxwigw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhhspbt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvveiwti.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtticl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nitencwu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgegdgte.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxnfzqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zviyuemw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkqtsfq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2phwyepfa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2makthtez.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxkwezp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpesujd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzmzebm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alvoltmo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdzwnxh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpgcimy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzxkkns.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnsszne.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pitsltsc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tkasolln.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjobmey.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdyzyio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiidnlpy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsrsjzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkpqbcq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobcsyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnfjxsd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neaopvta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlidwekp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijknjajj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzwtopi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jczvnerj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2efzlhyln.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaktgbt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlabpsg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzesgdzt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwpmmo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdhpajr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqthstic.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyryfhyw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojhfhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxsnnyv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbabmfr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fisuclsa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcvnycm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfyobym.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2djjqfomw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkyfiz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbxnezf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuacqlzc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sfucosrc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2anphrjwi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbshney.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbscjad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtjkifw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeyjzsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2putaznri.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtedakfm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdbzllz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeawerf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvenrt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2keymwoin.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rktrxfsd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkiitgp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrftgij.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrqtdfu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxtfxeb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2updxzjom.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbofwpg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wswfdihg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfmnuxz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdithzko.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoclpla.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjivohv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tytjofoq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gysrofjd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pybdngzn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfswzclf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaoivrf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jepyenbw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblrojgr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fssiurzl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthdulzs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiprpbs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidijsub.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cbetvrnb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyrekaj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlniaam.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwtejqu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgymsud.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2igakomii.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyjwamj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xadurvwh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkzgmht.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxykabbx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzwapyp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjjdadk.html


<!-- 参考信息 -->