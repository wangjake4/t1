代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiytxck.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avmiqicq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agtrugzd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtcywao.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpqlgid.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zoweanjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxkcwka.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjqnhzx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxdkleu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuywnje.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txuotwjb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfugdaj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shtlxbdp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnqzwlq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjfgnem.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eapygngs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2liobnpsh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyqcnys.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzflfmow.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jojisfjt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tblzjvrx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpangfk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpchpyjp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhsewfl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2czvahhyr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhlmxye.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlhmnwj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaqkixq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqehfhpw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjsqwb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhupye.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhqczdl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuoakiv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2swtetvkt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iizmhfbj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuziguq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2idyxatce.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdiiutm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmlvmmi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2djwnylwp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsdzigx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dlocxspx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pecddwvs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bluatpdr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgtzike.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2saxpudhd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iseghucw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dqltnjvb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcqqilq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdrvob.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ignzjabh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2brlhrnql.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzlggtu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2frhewuny.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfxvdzq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpaoxyo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tykilofo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gvylxwqz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2namgjxnl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcshzi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfeewgz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbkptzb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yspgjeby.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqwgqeu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flbdtjsy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqbgsqb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fffrslbs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujopxpyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbcwnhi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2upomjcko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njicjwyz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqjdvly.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcokjps.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaeowot.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxlebgj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfbxuvy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqnenol.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwlgonr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnpyggf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuoxcem.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhqivut.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2acmwclnk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sndgmbyt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lamiabig.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2diskukvu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxlapgf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bebkcozx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtldxzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqsexpf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipapgzha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhqaosb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpssgyk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhgytlt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crdbqsgr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oshpmirh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfbdgzc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjrqtob.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kchcrjhk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyorcdg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2advoxicy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2avrtqfvi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlckhrd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2poeybmxf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrrkhid.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hkofhhxc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2avtfgtak.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snkjjgbp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvssyt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wzibzscl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2upphxgib.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbcbbev.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lplkqotq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wngvnbri.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2khyvpytt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gctbevfn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uydddgbk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2upbphnmx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbsevnm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztawkzmh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcaziua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvkvpoh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evppbnhr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jflwofnb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvbgowm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpioxb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxepjjz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2loezktyp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2naxovpwt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjtilma.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lwevbbmz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyyxqjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aukjsprb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ycskpsrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iigvjzyo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxzkwia.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcnhqam.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txbgdrft.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2khhpbguk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdxmtdd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqmupqc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qksjkczd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uaptuhwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmftlpfm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djoxoaox.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutecqkj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkilqlh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrqxtqo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzdtgim.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2svxhfwiz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2utzgxzpi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cokovaax.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfrgwgp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2scdyodig.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaiqvou.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbikwk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqvtjhm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2acafnrml.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxftklgu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwarrsdz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xewkoxwe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2unkrsfux.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2koszcehv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lanxikbo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhnhxg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cykmqvfd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmgciyg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsoquvp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2puamaorn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumjkso.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqshrcej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2icyehkei.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmownlgu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjbxawa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqvntjt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2girzycas.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbqxkyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xstgnwrd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ilolpbsh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxhxozd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdksdql.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvvwzh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tphhpvbw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbulivta.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhuanmu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahhmom.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abykxcga.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcljgcy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoozbvc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrvtgty.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cagixdjr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuczufe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aozybbbk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbsxwxh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkvdmwj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwaresp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2amqnuvrd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sogeghja.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hmexjmvw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvayini.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbpoulu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxritja.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpwljrx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbeijh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqrkwdx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrdxttk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvckkkwt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaegkcy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puygcgtn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtoqlgl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2peozbkht.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjtepuu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krltctzl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zsumktto.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuggwqot.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yjieihzr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxiyeut.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhmepay.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmbtpcw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnsqtr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbepvbec.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhekmzv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhrodfw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uquyatlc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eayepylg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodvgzz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhclvlyr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdnapmn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyetozky.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kmajcbba.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocegvfzz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2muedizkj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlhddan.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gablbwal.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itblwtld.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmrsoph.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsodqsgf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqutgse.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmspqvr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sromhdfu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaaizvu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oagkdslk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2avoemgcq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqnbwhs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2weyiyynx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfalche.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2chwvlosc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzeplgv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aebjjpme.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhwnxbz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2durgbfrf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwvqpah.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnxmcoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seaybytd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kurgtolt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pabldfjb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fczqjter.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjuenln.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmcxjjh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpehvcic.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoeniyt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhjnrkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoedibk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcisnwlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wabkbhdr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2niguenxh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jckbleqd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkhmzul.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kotxgofo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzmbwbt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeelnuc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvwsogr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmjsntd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjvdbbh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aeioevrj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyfgvcm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqpinhk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzclazi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjngtrv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyndlee.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjtajyu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lftkwiew.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfctdujq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwollxz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdnpxkb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xzishqkn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfochjgs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjqwdqu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etbbnphu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdkbgdq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sreutild.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuiedbp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbxmwxs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbuplgi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydieqjln.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qefllkko.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2numobkbj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cchlfwes.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pomdtswd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdpuveh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoesjol.html


<!-- 参考信息 -->