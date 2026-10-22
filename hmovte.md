代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrbavup.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbztsrh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtepzru.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfvdqaw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqskmmea.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkolqtrw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyooloz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiworlgl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enceedaz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kefswkyb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sowzvdss.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtsjjcl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xualdmhy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzuvcmd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlejqqq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzbset.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhluwpu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jlorqsai.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvgcefl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrqhahd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zoekndgt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuznoik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2riymbxby.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwmxwup.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbppibd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2genvjicj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwuaqjl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vymzwqvj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kzohaiak.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2luhqecyw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgzvjep.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqyzmsw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvvbgjk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftochixk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqtoujy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2craxpsqm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obdmipnq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxxbwi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hgydfcll.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2shwqoasq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfvsqyb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2klqgtrqy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuruyqm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxvaiw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgohzzsu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsghwak.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swqoyngd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eihcoumm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvywcpk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2upfwrhgd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eawtwbrv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdrazzl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cyojbyyt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lnslijdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpayughl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzsumtq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amgewkmn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mziozdwa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isdequdw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhqsmte.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzjjkfs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2htdzwrqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibryedwr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2redefjcc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyyhhor.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2srpxwxcr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttovbtxo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtsgfzj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hseywwsw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbfhgmh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yujrnhsv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhmarbk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzflnn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zxilqmxv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zfulkqyr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2brlvfkqe.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuqbgam.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksojjeoq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfmgbaw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hymejzdd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pllijmfd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnqypff.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnailbp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pldjphta.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxoloym.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jekwjaly.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ziineicb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fotqznnw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qydyqdcm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2utzkyntt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2noskngzg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdugkr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaagcel.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwygpiaa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rglwquou.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hajdlruo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bbafugqk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoawpyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdctbjz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tphmanjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aziqchjw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtqjjxn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyjccjv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvxrlgj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtcgciu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzrfglb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmavzbl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rntothfh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdyntc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vqencdum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hcreqzar.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gobtbnmv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2obgmftwl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcauhaaz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvasald.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyajgij.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmrvxaw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeoeood.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2betrcawi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrtelnh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2euulkiqu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfxfvib.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuuxfaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmskhnzi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuillsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnisjzt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2beayooiv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2stjvvyfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiqfmri.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsbwtwt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhmvake.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sipajmcp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzchsxxb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jczcnnfb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsoleum.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcijpij.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykotjncr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzuqhk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqwmnfe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzmeumo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iubdvfab.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtdsbb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiastng.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmkrib.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpedpqj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2srdobejd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tijdbult.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tumxclzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hshvloul.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vauuhxrk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkhapxi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsrpygc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2btrvddjk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lsszypvt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlusfdw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2erlvuwds.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkzvzkg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2brrqdgfa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezethsbn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cgndlgoa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nejnener.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmndegll.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2goeijmas.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdrzmvn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmccxzxw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjigqjp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2enpcfyom.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2werxdqoc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsyxtpq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvjwaqu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfiqvtb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cngyoctj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjxrxmj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaoghwi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oficqrzf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaddier.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchleqfn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgihnjl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtdltho.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uqshosfl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmyuxug.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2meztgflz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgajgyuf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2heotbpnj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsryvgs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2paekvyvy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvwkmrf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fezwgzkx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sngqvwcl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bcivkfbi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2skxqwuzl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnlzfqc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2drvlnzds.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxxmhh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gndbofid.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iergtmzf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2igzvjovk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wedcaywu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyryfhd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhvzear.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vsewfmmt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vunhudpq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vlekuwoh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zublquee.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kspkbfqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2leqlermq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrppaqo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xessvdnb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywioxsoq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vrllrssk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnesqd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdicokzi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjucbvat.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmkoyhy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otjcjzyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2emrdgeua.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ejheouvv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2urjonali.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdikyft.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvsbquj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2moctbjiz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kasfdkgn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yhggpvbl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvbebsm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evmiwqkb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqtgwzz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2napftsdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwbtjiz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxebydq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btmadout.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkkgmoh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oodghxfk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2olcnxdld.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnvpzhm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxgzrti.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2barqlggm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyzsnhj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2exozmwcb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeedegp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkbhtqp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxjjhgg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cnffixjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyfgmu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2shrmfsmw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjttybi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiszpti.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpavrze.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbjipvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgybfslg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zclhvxvn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvghprxy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxewjagx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmnillf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsmbsvv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlkpcwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhalghjz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gulykxpa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxzryxo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhegopbs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fnddftkk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuepjzv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvmxpdl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eogdavsa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qddyolqt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qazmafcd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhywaak.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bcazrnmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoulvgi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qbravyva.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hppraghi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2shinvdst.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dofujfrx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebmaps.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxaxwkf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpgppko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwolopeo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yyymiqtk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkypbe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fthvzqmx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujisstto.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqemqlh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulndlgkd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoqualy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjvurue.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vludedxg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlqlnmw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icqceodz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tapsqrpw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqewjlep.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2viqyxtdh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxxnmpg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iduzbsdt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2llpbsajd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iymjhthc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvbzctk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhgjhpa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dccdefvp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2andryjvd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2elsambyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gebupdpd.html


<!-- 参考信息 -->