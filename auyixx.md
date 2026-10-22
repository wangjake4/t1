代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpzgsvw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpdoodq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpndgiqq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2suxevzvn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brxmxbye.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fyurwpnk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ryohbdmr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjjoryx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrwihpe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mugklpzd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnyvfwk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxouxqaq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzeubfp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qizpdrax.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inxxdzpb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxxdxol.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vggdistk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaaouri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfulqljr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbbukkp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bamypbjt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2olmghqlz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqraquc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vvplwhur.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhxkqzu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qibtbdab.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xleyvkkx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jazqfyen.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgbojsi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkijivz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgdmhwt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phtedkqp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddivuca.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nexffzdi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqvtvjd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupvqgl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ljngzvhj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xunvagsy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxwhjf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnbdct.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2exeftjaa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mveoxbmo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2icrumwbn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwblxwu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqboct.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrcjshx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakiwvm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cawpyzzh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdmmgan.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsakgqs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2azqxbqnk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqkxigl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvhyss.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmrkqcx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvawsqpo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztprkeza.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sezjczkq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jijsnmfq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2awzbhdyl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsprawp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2diakmwkp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2unsfdbjt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtkwoea.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeobwks.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gahzgsyl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqswdel.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiezxwm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yckpibpp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrlbhic.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2apqwhqnx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aogtxikx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uazknubv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuiwhcc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2owwrcilx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zddyjnnr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2katrcgbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvmwjip.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgejlyh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvubsnc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2btrvgxll.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmdpkhx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbfbmiz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyckaom.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hpddxjjy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbajjqdg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eunubkjk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwgctia.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqgkdby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yrngltvm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhfuoio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnvzrkj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2awjhbpvu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iexghgfi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgsthol.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcemsue.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvmwrgl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfgorvq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfplpwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zawcptlj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjasrifp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2niyetckl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuvjkrs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dydynjmq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzpfaz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzoern.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zodnodgy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aiepzrrr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjqvtcc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwaodfl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eivndwhc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2azousalv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhclmhed.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfquamwq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqqbxun.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2malgglgt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoaaeyj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2frntaqlx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzgpnry.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkltxec.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwjqmwh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmarxjxp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saxtnefw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2scnqdgpg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqigssg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgipvjp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnsejmd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsycknz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sbigmahl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvgflx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2npriougy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2raisxtpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knujtctx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2trvposva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eantoxyc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuxwrag.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmterjr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaniwjva.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kutvtwgg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eouqczzt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdpzthf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozezrg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnjopjv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwirery.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfczfmc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafabyuw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpvujxo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ozemlcdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvguqbr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2atailigs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjwoty.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrwcckd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfomjgdk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zuinhhif.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrabcevs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyigjap.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moctffcx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqbmenf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifqeiyk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpkhzwj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icuudhwh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2crzmjjnh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hghjjvaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlbiczz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpinzcx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2atzpscuh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnpszcb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2errxlsbv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfhtbcx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uheqfkpz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzmozkc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2euwniqmo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tckypqni.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tncnocug.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbvjczx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2utyuyivy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxgbewz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxusjxm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftimrpqx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2obicoquk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kushutsg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmxkrmy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxjmhrk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxduhnz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xjajhslk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsimxhj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2emqnjfua.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2biqzbglx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfiwbks.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sljugzxo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bceprhhe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2idsabpgt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jspzbxev.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifcbbpt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyspuks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaihjdl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wimloqki.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrnldug.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnzsfis.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2czbvzruo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnvzaap.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmemhpf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adnjooeu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtcbnzu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovifgq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2grxrbual.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2revblymp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxdvmbz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruswuumv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2woauqwre.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vweruvel.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dgudlzqq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgudkom.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqyfytx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxskbgrh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzpviia.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gznptpby.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmwrznx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dnubkqza.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfcxvll.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqviijfu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psufmznz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzyrhj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pukwybzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2efaueeij.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wajzmjad.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlbocwf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2edmamhfa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqojkbuu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xyldyxwe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfuzrjh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iajrxdce.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwuqhyi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idyskrwr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyouobfb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exytnpuo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2caywaazc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjfrdid.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anlmdjwl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxtmfor.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwuyrvn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrskaaf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2simrxgnf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgbvyac.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlpkzu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfknzgob.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cepkacsu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tggnjzqi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2atdqpsde.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyynmou.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ethznbbz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjkfktq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jasaapke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gngyjzyk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmfbcse.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhfxzqw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zanipwrg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxucega.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2itdvdfdk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2efhvzqct.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gpohvmpz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvjpoya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uovvulzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpawsag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhfudzh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uldugyqm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhiddcd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjchuehk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfskqtp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlgskuo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsbmdvr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhhwsqy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ffllwqth.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rswvgeuf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2idbeoeip.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ndriharp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnytvmxl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxdirac.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijeogcu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuotujy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrbjxyd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhofxa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2khqtldtf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkrczfy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uidxgrau.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtmkfjt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aunhsbav.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcftins.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeteuujf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2avrifqtb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srjtvmvp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zudaawev.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qulokfsx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bpijznnw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfwjphm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbhxnub.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtpioln.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2birnydlz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxompjpg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvgazcp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdpobbw.html


<!-- 参考信息 -->