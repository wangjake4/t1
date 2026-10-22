代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iddlplux.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqvjszw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlxciir.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eexugfmc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvqavaf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcfvrpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrluovc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmmrgjp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxivqcu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2slabtpax.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grqgiakg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjcmql.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpwohci.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oekwdsll.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoscwaa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfkasqh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyniyedd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiimbbl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmpxqnq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uohofbjk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjepfafm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqbszjz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lagnlxrx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ipifombr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwvbmuk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sznuunxh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2luoruuni.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwvgpxi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flngtluh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoaxzhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hppuzlxw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kucmdeyd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhnwmyi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjgqolb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpieosl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cauvcxod.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyuljxq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lthooizg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhlftlp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jffppscw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnmaejq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jckcrzgv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aakqgtys.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkopylaw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvkgtqf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zubbyfrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibvewt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ciruotof.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmkrtoi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgatzvl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jwishqna.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnbaqpn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkmfrni.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ieujwogg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaidfwl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxwdyph.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhtwbtr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oqviwkto.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vebtssgy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaalbgy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zyludgor.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fgarswbv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqvmedf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hknmthum.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpprpvy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgyjzx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyukuwj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ortnnjyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pngwfjrr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izqqliaz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kexunchn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nggmiiey.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjkrxfm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bceqzevf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhwesgo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xlauyoho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwrrvw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nffhjfat.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpnremp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ooficudh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2czxvpoyi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2drqusinz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmvvxwd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsctnbb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqnggki.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlopbkth.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2evamyrxs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2akeiqhxr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmgxkud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfqmoka.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2irdoyokp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsyocz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qktrwusg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgonwnxd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rztpqqqi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2phjhpttz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2btrpqwry.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfnbow.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcovgmuc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfisze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjhlqvn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzqljia.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwsrizy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfokfsym.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yysscjys.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxxnyya.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bncyjcbs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvbwwfl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2twuxozhh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cathtqas.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zvogheqo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2elhlerqa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkbyjso.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcmgxve.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaixksu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eijgfxyi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xxufhwvq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fviipzrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yufiibtg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzrfgfd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2blsyymer.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlicfagn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgpevdd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjphkua.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uebjtcxc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2evfwyhyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqvglvf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eafbhdzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbhmnhv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2leesrekc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgiunp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtcrowt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdwimpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apzcbugg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqgummg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2egtkcels.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvcnnyy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjdigdu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmryaem.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeqegbq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gymgaihl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnabdmi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxthggb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyjreto.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubgxltl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnrshzy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tiknjabn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ajibclwu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjjgdcu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwmvnu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqyusu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kimzrkde.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgeqgho.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hyozjihb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvtwquy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arucqepz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfbhgae.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfidjiy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfdhrw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnhhqbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucggmiyh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cmakxjoo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbpbbhm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfijdbl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxynvi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmripeyu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmnapmd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxeetyq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knovhxse.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfhtjyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtosxsp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvntqtq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kktkjtms.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkpyeew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oommdswn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqsyjou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqryowg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrijpujm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbxsqwb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2binqekjy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjaantv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ninzdqni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2htcecndv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkrzeos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzodekz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnpiddn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvyexkz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuwizwz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlbnqxx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdofmmc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjklzxbn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtungbk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhgapoj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tylhqffn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2knyevgfh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjbiwfj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2szgcmdsv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxmjgeu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnvigdg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnscfute.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nwibyrky.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwwyhf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgvaag.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jffoxxug.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xxetqyyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtunvutx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgwwwzz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hajchams.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fditrxxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuotnff.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qoujimtw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcrgiri.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfrayvu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdelmzzi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhwiucb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkdnfis.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aiijyrev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ixecukns.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxmvaec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2usqtzzrn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqwexhm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qifabjiy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blwzupzc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmbujth.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zigijcgx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlespthp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kwggnnbx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslerfp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qrogouvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2prwlacmf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbcpchy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtazqvz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpolvuw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjjawxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuvdstz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrmkdi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkccsrt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuifgnl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhktndnd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iseuvrnm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqzzfij.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatpvqy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeclfqv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2icwnugtl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqigojoj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxnwqvo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvkpmj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzijhbmg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnlhfja.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmqaldf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhiqavb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlrecho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epegoebd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifziimii.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhjrvzb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adgxysbn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygezbey.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvrjzm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sijwfiyg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkigez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqhkswq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paruqzvt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2osfdbgsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kydzywgy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhpnzgf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqmsgfe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itwhcgim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2omecdzpk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcfrhoh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwbwkdi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqriqjp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmjyctb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wcplhysd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2spkqeluv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfkuwbj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyqnwbw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fptsxoxd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvasvww.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2odvcuqxv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2obniqvib.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkztbteo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gepukuac.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhjagsz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2glpjrdhg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqyhpab.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwughlxw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ywutillu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvifavuh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zvumeafn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcdupze.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krthxugy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yudixhck.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqzfsfi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoqsxdk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2roafkomq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2itrocqax.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmzwqkc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2neuaapzq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeuhbki.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkljdvn.html


<!-- 参考信息 -->