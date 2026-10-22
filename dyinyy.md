代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lumbgvmu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnmoian.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmtlfic.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fexvjzfu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2miyvahft.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2balpebhp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyezydd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvzlfv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcstwga.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuyufa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2saikooki.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxzszes.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xejhmyxt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wopgylwc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmufwemi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2onbucqaw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnnxaxq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sruqauoh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2banfiosn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeahxum.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfseao.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsdbalv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oolpreqb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsaautx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcumwfc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxaveia.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsxanpe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrmuqyt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sglamytd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpcgtul.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlgesog.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbqfpqk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfgoim.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsaboxy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwkkkha.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtusmhyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvtchu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wycsooes.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxpblut.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhrswv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrambag.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywynrcjg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2enunwcnk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qgesdezj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzgzgw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxjitdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gvauodpx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hosgbhgm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vezszwes.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2loctqtpj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xwriqecz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdhwhyx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdqfqbu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfupuxsv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpjfcfn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbeusuq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjhjkmb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuoybvb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2raunkkyw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scnbbult.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfqkecp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rimqvook.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvjtgmn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2smtxsiuy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2muptzvna.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvmcvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iubnakao.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cndrgroh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshbbyb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnqrxdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjrbkcn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgflkrp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tyguvcoy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdfgkg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjztruod.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzzasuz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcaggyb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kihtuqxm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awxfhtqn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcrmjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmoaeaj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoqkmqa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fyottxoz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jeowcrrm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2splbbtcc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuvsqpf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjngxxs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcxpini.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiuhopz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyplotjy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gjugzuqe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zunbdkgu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eacgbzen.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsurnnx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfipaxh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxklrgdb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2smptjvfa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qduqdpwl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnknkvy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlqsyhy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbyjebm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2akxgnqml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2efecbipi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gomnzttq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pmchhztb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2inbagvmc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djktlkda.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwhblyl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzurjmt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwixdbab.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnilfpl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpucriue.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2revjmrtc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ponppzau.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2urdqncvo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2plbmgtey.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqyjxms.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2prtggikn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtvioxq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzpmhph.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxaqeen.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtukzdo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcvvoux.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyguunu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ellewatc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bilmjneq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlyrtds.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjkodue.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gtabvpqn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbsltux.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmicmzr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dknsgawd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bolewyee.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmemsmm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjdqei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suezqxxr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmtpwcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nykwdtmc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xagwvxtp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aaasxmzw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yplkuton.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hilqdfax.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2thsshrlw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2epfvcsjt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzysztz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2udlyfnig.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgqzrdn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yasccbry.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmgksws.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwgdro.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xaponmlv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iiplfxhx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pipfimvg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwhffg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpnanmw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzfpzfa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2baqfolyb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzeplry.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2upphifii.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyrfrq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrfafkw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeefhwel.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2czcfpruh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxpoyc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtelpqsr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpthtxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2viuqqkif.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrlgbzo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlegmobq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vladhbqx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyakjktv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxudffb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2niapribv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqulawx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhcfmxp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eloreqgk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewhqeik.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhkivrg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2togbwxmm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2edjoneos.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yugbeujy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrwjmvk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jumkaeqb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jddkjqvj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2evuhbwwf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vslvggxt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlraqcs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2marajdwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvshhyjz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eotxnwiq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxampkzk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpaivhg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiuxqjy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouixgqlf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kivqsfcf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ermcdgky.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbokghxn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucppnrfs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dugnyfmw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gviauyou.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfgfydw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbascne.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnkvcxv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxyzbsc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrswwub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudwuqll.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjxdnmg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kstvorsg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qucwfllw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmynynob.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxykbxg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pquxmmej.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yrncjujn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2squfiqod.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2srlqoxlj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tikbeaxm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xaelkiiy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfwqew.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idxiazsf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylewriyc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cauppiiz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iobrdhnt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pobrdkyf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvzfora.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2auhlsjaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjtucfb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfuggzd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbiotez.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2akifrbnz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcdmiks.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fopbwfkm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyugybh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqxgqhi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkbget.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2isavqsum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetaqmp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdxpxcx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wggoemwj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsezbvs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvecwqsm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydvjckj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymviefec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlyojdb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2anayellr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2clrccjlt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnpvwjs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhobcjw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrbwqho.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaymjggn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mabxrekr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ualoelup.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuyrqsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqmetk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2grscqztv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlbcevr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mrexgmiy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbohhhmm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwsdkfr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgpzbgi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2carbvwwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexdwyqj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqlylnf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbsdvqz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdxnbej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pfppxhxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edukpulj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2izugxerv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdesqtyq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usvhxqta.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxskhatw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxenewb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2itkpopcn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvktupi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkcpuyx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmankfd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aoibjvhs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pituqvja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nquexonl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpmwpxj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcydyuni.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufomxhpf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpoukwl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhorbntt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwsprls.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njjasxkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzipgbge.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqkhhkm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcukpnq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbkdcfg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhccxtc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxumhfg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xogeiugi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrgnub.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2syycmcoi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxsdznl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2chpxkxip.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fcquiqbs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwdsfuy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odtxfgbt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrkdjuv.html


<!-- 参考信息 -->