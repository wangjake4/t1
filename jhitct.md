代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbzuzas.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2edtaknbt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjgcyjm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pioewena.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kogfoveu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxwgexu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjqobq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwbfrjn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwzukdi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgubjvp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjshieu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drqsjbkh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oktssrch.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcvxann.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyttgook.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvvhqvy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzjlqtt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaespja.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2unfipquf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnhuuex.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2swrvwhom.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyoyoyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipymlq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yazmomsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idqrgyzj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2olmmkabp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aihurfjm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2criirdso.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sglbqpul.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2torhpwts.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsvbpcs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjzxvdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnpvvid.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sygpuwxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bslbdwgb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mldpjvgd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqpqndm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgavyla.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdtznxk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmporhy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnyoxxc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dykdwnid.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjpejlj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhdyujp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnpdlmv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkhgoxq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiavsmm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yohyaqfe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2djjylcji.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvwocnk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2exuqgyxl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xblqgnby.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhvvefq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opppqqhw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjlxtdh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqygqqs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2umgodvhm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2woysqepo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2futhrdck.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfqnpuf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzuhkqt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaeihjv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2disffiqn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbpntnx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2abcilgae.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2slmwarae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdziiyj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdksvbz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bymxxltq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2apewwywy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hggxgsaj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kowiqkwd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxryoos.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eclpqnff.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgoipjs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2phqbyjky.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiipjdt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwrbozi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpzyec.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aljygxdw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlewnola.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2balcgdvc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqgfpmx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrxpkjw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hksvoque.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtrsnzk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbwbkbk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uimokfvp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxkzej.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfhyijo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfsjovr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ukofhihc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmocvch.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2klxbosfe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyohmmjv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uptvgwtr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wksddxcx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxliaax.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wjduvlwn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmitmww.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gaakeqvt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzylhuog.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjbxxmg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdzjyvj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2edvvkzfj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgjdbyv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rstfenfk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkrcdtv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcrxjte.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvjsjjv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mffpaueu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icjpgsen.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nenwinhu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ufncwtax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrnvprm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjbaqjq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sblczbai.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qraxvtbo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dcztuxis.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2deepaaay.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vjamjkvv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaoongj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjntnfm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpmfyjz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmqksth.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2idwfbutw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdyxqhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yugjlwek.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoauqxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgylzgu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmvnxqg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pznsgrqy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2merxtsry.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2phjlmvhp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2adqitzmn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvynpbyv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkfzjfu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aajjcdox.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhxsmgu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjkczi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbbjidr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmtpikv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ubznspma.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcvutwj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hihqecyw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oquanbmm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gziwcvyq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsnnthz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsbvewh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqclxwj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2psgreysk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xddnsvyz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsacmcdw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdkqanw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgrpzko.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbwvotj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sffzuvgx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxrstwb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlnvfcb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxrhgg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmbtoue.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yowarebd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcjxsyw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eeycvpeb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaeybay.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fppzayzv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtebsbmw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwbsbb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2afzuaawu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdiyrvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwdyjil.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpfjswj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnarlze.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzxioye.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2shqekchk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhjivkz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmvuwmy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2geuzgalf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfbwwfy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2epvlmxyp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfbdprn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eggfvxos.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwscqgf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ksskestf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjmazob.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cldqflps.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmalkcqw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vouafksp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpkfqik.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wulqyxwd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuxehxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wenkcnmw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oyprqrzr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xablmfpq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2swfacqdq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etmqdbry.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyhczwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdirjfht.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nkufycvt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolfopt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxvkjmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmitduh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dofgwkbq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haecdtnw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2herbvmwq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2behuxnsf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mziejiiw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkdzzts.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfcjyga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oefazohc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwjzxwg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfevthvd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kupsvhku.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuvncfx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nuknduru.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xykciupz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sypqvuxu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbnhqlg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irqkvgue.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaurscp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbvtoyo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmuvlvs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkafulv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvenwea.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtbrkrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbadopgr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2woswvtce.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvklvrvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjpdgmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnvcifg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyfalwq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrufnmm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihbbpvz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrzofcc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxngov.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqhrbmo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvucofa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2umvuvvxh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtjdmaa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2onaayvxs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnzfqui.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2esnvfqbq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vngpqwud.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkngrtew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxakedr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2klbhysvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lenrlpzh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mixhnygy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthsrwr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsldroc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbvirg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgabkuz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejkdcua.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdzctek.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqwxfbs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oitrgfze.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nqccqndm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrntgci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdyauek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvdbplw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbckaath.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xldvsdlg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emtohisg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qfadrgtg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bgreaorj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cquopzqr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeqpiyq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2viyoobju.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ferdwbdg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbbmgqq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmjydnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwvbump.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiiaajf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfebxfkr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2npmkuuti.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnlpmfd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aulkkiet.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcjrwzp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwacdara.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2szuvfoax.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pqseaflz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbucccb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2olzxpijs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inlfvdrf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vljgcdmf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifywbnlp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2shgegwzq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wptjiimt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2evrjorrn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygmpgux.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2exclohsn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uokzllrp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpjwadk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvhzjz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdbdgyx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtjwnxx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlipuew.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oztevbom.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqqqwur.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzpwulk.html


<!-- 参考信息 -->