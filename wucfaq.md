代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meoscnfm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdufiy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvlgdcv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyawahh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzsgcny.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgxyarr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evaepczp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uryhjwwu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2juvftiys.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2czapwdkc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fezetelq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmirdrv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsgysae.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2walfkygd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwxhysg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeqnxfn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czdemrfo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdjyzvk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckudrhag.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sguldghk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srabrjqt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjhjytc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgqprbi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxvwrwu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgefiwyn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbvboba.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkimoswg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqhqhbg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhcaiyc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2etfbxpqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vderakch.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmbobur.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2meesbzgh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lldztrvf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhjvnd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhctbyfv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebonypbk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nhscxwrf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpttsglp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jepmkkeo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmfozfz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wvandnrp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xkenszda.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaoavpg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2faiaoynh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2elhbyyzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfhzri.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skirkhop.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkzdptl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjxzhc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vlovxagr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqquysc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnfuyds.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llvnuecp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwehyw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2izxkonuw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyfjkcj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcjukdm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtabsto.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flteqwvd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzyhiep.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oenkgdli.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhmeelm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yutgzmxy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jhawdjej.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gvycavjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mijeltiy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gknatpft.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhuexz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2stxoyffo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uijbrebh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnfyvlb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uyplowaq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpttfz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kctorynx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbfexz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbzbvss.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbavhvjg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcrijfk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cquzvobt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qywdpalo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oftuxueu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aarpshdl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zncxbgvh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wsudyqnl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2afefkivn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbgtwuz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaalvbv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mahiwfmb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhfgywi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2autsimbe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfzvjuk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rjczsxyn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqmzgsj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwalmsn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2prgxhime.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2potiqjnu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klxfuyoz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2abrcztzm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgodnlo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzimtgy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqexmrwf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hryvykpx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pglqlkdr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hrasiovt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmybqhlu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2plfxqqis.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsocorr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpxzpqr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxkguqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwvgvfh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnvpbhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vrujkqau.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwybufl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqwzddv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmdazkf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2puwarvcf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmsqyfl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhkukfh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qoffjheh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bybqbahq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ychltzwl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syuwwgpc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxonqzca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwrwyik.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgckmxb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpntnuh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yciisdjf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvrdheo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2meqteijy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zscstvai.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuoavzk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owrqjryq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxaofcj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tumvlklm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaiiwex.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkismrnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ippylonj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqlvbft.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubzblp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdozovtd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsvxmnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqktwlq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2odyiwixm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoiypru.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmvvrfa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2anolense.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwtwmfg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvwoyhh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcwunhc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmbegus.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2upuqeudo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsbfmcc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mckfdogr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsmuwfs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxznzlm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2suyfhbbs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlvyjdy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmhtjej.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqlyiih.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2avkuhuwi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficjnvst.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2heasgplw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctppnscw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvnbbda.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgpqcfo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jikhecmo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fidoayth.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxnivh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkstvjsg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sukavpsx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ezftsvaz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwcimke.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwmrpfr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiplwkf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoaossw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdejkxef.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ndecarae.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrmrtgh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nibucfyr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eahlmqzd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfmpiiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2emeqcoeu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwuipew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzvelih.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yywcxzov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwpiogu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlngtmei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2njcbpgno.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwiggef.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvqyer.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiujdqt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gguigtzn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyebxjyn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2afcxxhka.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskrzfs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjsvpel.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imxkvxue.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkacffi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cilcytdh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuugpvk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hczxxkij.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lvasbati.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzadogwd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2avutwsfp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpxpclt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzbaowf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gysxyjps.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuidoeu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mygsslnt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnvcwfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mftguwav.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2izbajwwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xylbvyxv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxyfftt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnowfpr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbrzkml.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kohywgqm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyvhxag.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2buownuwt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njbbqxdq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2esnxvmbq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rrahlnhj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olsviosy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgypaidw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fserxfeq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkactsdx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qknvnewd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fihucano.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkavjqie.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vjawxbhv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxvufi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjckijo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etkwsyns.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tubmvmkz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aglsizdx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvzbyxy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjvhmmd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvwoksd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2chuyjdjk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfydmkb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oagwimou.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxcacnj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvrallj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzbwpsx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uevalmee.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwpplmx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrebgsi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxjhyhj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2voszorex.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmboamw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmkthre.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsanljq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdkwyri.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snixlspv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtodbcy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpbupab.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxzoejj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgkrdlk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2melfermc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxdbatx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxtpzh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2olqyzhkv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzhkehx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzscczvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bssgpviw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwfvioe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gowuyouj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfydkdoz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmooftd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnetduoc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dualosfu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyirbsz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrttmic.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtwjiwj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbztbhq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xgenujsj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ziffrdmv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsllyly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmfvmsm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lonvinig.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2raonsznn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wmddccun.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rootetee.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjikqs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkqiwqn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2socoffha.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tssqlmft.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeylcbh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyivjstt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayntou.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2notfoxur.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztspjtzw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkolnhh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwskbzz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkmeaxj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqrqrtz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipllaza.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnferexn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiehmna.html


<!-- 参考信息 -->