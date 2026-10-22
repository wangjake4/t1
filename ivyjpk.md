代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaeimuh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hucrricq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lveisyie.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pilnxtob.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmsniih.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yulvrgct.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umkustry.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eshljnxx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxahfywg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zipguccm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrlatcg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xanydjln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lybyyrht.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2puzbgech.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlsefbq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pkavtvmb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwryteny.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgqzkqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzrjpit.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkkkepx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjlrhqh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2huwlwruk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvbnxbt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdqzqur.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llmoogfi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuxovvw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoiilap.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lmczrmhn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vamnexrz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rgafxfwz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnilbwz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2evhtzzeq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jngutwaq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eugculas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2syciihqd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqboeafc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilddjvn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hifzanaq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wqywgzlj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ugleugdq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrvwvld.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2acyaykmk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgklpju.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gljybzrh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lthcwwva.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvsusaz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrdteoj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iymjaucb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yoijceax.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhhbepu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eebhllro.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbywjd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2znsltqrh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxdhmze.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvotnmrt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thxloyzh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgxpraa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzwmopv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqcxjvh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vegepzqj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuohrfn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fjllcmex.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlowiliq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2klcurszp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qjodbzde.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtjjxjc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmygxfjy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2keshmkco.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lalxnpci.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cylckqyg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2euzvfwen.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kurtgqpj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbfwpvg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2taejiudp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2soktjeed.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxoyjxf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrzyjjn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2budabypm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2evyjflxq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjcdbzu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pybjkpql.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmybmymi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvolpd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmeyso.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqneitt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbnglub.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2syvbsysa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwojvjh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcgzoig.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2myqatoau.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgsjtkf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2khrgukhm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrqnlnr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjodfggq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkdgxdv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aygcoxlh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtlzwux.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnizkir.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wniliyuu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpavjes.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhlkvgn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrupuzs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2foeeschz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjrqdeb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkkteuo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxvnftl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmupermi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gddjqtix.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2oxasmqme.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nmigftac.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlxfxke.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkvfpyx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuaarov.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skzsryje.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgrrkif.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmrgrei.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcwvefr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gurmcolk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfwyein.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpnkhbw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxomudg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mrejdjmb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkxyjxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgfnxis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsfipre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsngdlq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svbpguiv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpyoepj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnrygan.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuswrcw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2brqnfejx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuxxdts.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdvucyk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2neugwoej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmqfpic.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jloeeyhu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwixtaq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmapimbe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ouldlvva.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjmqpek.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dblajoyj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2opnfxqlp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhadabo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqqrkbo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxgpkma.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmphkdl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yknuuwti.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjugnlmk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwislvr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpljtjz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfstpef.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdgxwdm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavryvev.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqmvkwq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeemlgjb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqtxrqw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuzqpku.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xitjdids.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaqthjv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxjihyi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozhazi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkaqnad.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzuazgz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mthkqmgj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxxhpbc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrmpviq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2syosilgi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbecadm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2byxwzgle.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupismu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hljnugju.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxsomy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aspkgnvy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxxsbyu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjibnyb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wopzbjrk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2imrrqiey.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2axiftgbz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kikjgckn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jebgyibn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagubdry.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sisnghoq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwohflmu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhiljnm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlawqml.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtvkaxb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2grbfoycd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ranutibe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eorprdai.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axuulkan.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2brllvjag.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clahizkf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cezrueum.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsuuijh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvlygqp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtytpvo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mozkxtsc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcjcbln.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yqulhunf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byhjjjgq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzwzwlm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsiiixx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvjbjyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfpabts.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbrvhwa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hawhvnuz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agczjfzn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnbclbw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtegnhb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bumgjjmr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzolvwda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzjebzw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsifmjfv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqansfnz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vduyklen.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2poclsqxo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aztuickq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aarbylyr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mircfrzw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcesbym.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyycboq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiongkd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdkfgx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guhnexgw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqjgocv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwddnns.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqhmtcj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbgjcpo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iigleled.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmlvgiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaklapy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuljscl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxjdpcy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsfvtcg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoduoik.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ganyloyn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwatflmo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pedtsyum.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2njyqzhxs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpmjgrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuyypot.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbxqyfi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfhqbzp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqltkid.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgwvuos.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2clefqplm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2miwxipra.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkvfveu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntgsfqm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ujveyjln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxflbcpn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcmkanr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjoknx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2necbmlcs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bntdspne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmyztwp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyuszjd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbxkyfn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzigijxg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkqkier.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2enexppne.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbhyirg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmqzkgw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqrttya.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2imqilhra.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvngofk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylohsnjk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2higrirmy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkbbbxm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoduavqv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmrkbov.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblecfsw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ditvbhkp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrrgaxc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtigkjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fozdoruj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wktnxrki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeorhghk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2frijppbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhhoxv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbtewpw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plthumfv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntooukii.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvssgmbb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkhwlaz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzntiosf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzmgdnk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbepzpu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkvhfp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvxstb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnznwmg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2irxiwptr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxibxeg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulghlbs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnzcoen.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftkayaw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yycqmbfn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyhicyd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dudyslnb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqyrnpa.html


<!-- 参考信息 -->