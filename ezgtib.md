代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onmbtzmn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxfwyus.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpotakoe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhywla.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzuezx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2abaesvuj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2faqaoidv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2durkxuaw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqjwuix.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2osrevwmd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlutfjx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pofhoegm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inaahjar.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2awaxljdd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chxcihrs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuclkng.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvwkcdn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffynppxb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxiomo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcwcpps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tukhhyuu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlaoyvt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzexfbkp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcfjtii.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lykttgkv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjzjvlx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvhpmgz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jgabdvuw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgcfktm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2meurgwgj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cesdrzvm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evurjfjl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzplgzhg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkosale.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuhbkjk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfohcfw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edujuris.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2exonytgs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqpmeov.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nsomhwhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjuuta.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnfnhsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2inbsyzzs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yroouppq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2elkgnomo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhzgevo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mpriktge.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwfkquc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vydjjucu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpsonuk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhrnwjl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbokqcp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmpjyuc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxbzpim.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiawwyz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuwbhvi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pebqhmct.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lvycmuik.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igrfrfua.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgliezco.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeepbmm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjscaxw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uwinccgu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oduhmcry.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfdzyjo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsffzos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjubmtn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2llsaozly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkfmmml.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhczjys.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nartnzuz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpelejh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmibqr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgicxlq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaxquqk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyaecbo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zllzzrxw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tghocrqw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmuxpyv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sptsblxc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pebrgarz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehisxzfv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwyzgwv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eumricwh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfyfwli.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvhfgnk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zuepcweu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uviddbir.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ddimxlax.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjbpsyi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ayewyyjm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhianok.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvwfygd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxheuhi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpsfxam.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bieblgni.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvbnauq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fomecrbu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwofocl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqasdja.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wnexslqe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2umpqkkle.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vokiwuxc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzxunvt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jyejczan.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2enzqikco.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrankfq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuxtllj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxbuyhy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbophwcf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvcxwlr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qypwmokp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjetvfl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uvketgcu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tmynvwwb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkqqkhk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhclumz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrtfuyp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyfahln.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwmmai.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rkipefrc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmznamo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fajmehmy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgpfdxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qntppvim.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlcxhys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2forncxik.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xiphtfxj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkpoear.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2unamdmcu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiqiipl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoizjzb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpvzlpc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mslqrcqt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmcslvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fosauuye.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomwdng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjxyzje.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hesgmisz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwqsaar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjmjvz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ribwigom.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lipibvgz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zarsppbu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfwhld.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqbjocx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2njnifcbk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbdlrai.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxxjdit.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2anbclmwb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvkjczf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwefonf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bojsvlfz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhifvvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxdebat.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qteeliti.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqfrmmk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2maofbccw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpfdkfi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzepexpj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxcetnn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpymqiau.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwjmqpz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgztwsal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2marefblb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ohotznoy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqngxbpy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ijafcqpl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjfvhyr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmouatgg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwahekm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mchpzwfp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2midymtvv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxplrlhc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlvujut.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsedvqjz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbguiadg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzcvgud.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iutnvczr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwhchal.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvwapt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eujwnfoq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfenwoc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ptisoukz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpplgbqq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmqumfi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnqtgro.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlkcwwx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrblcc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnqglwa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2slzocvup.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivyjyq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfxfogs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tixuazmr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywdhomf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxhvsen.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nknsicle.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjtfjcg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sadxdkiz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcmiyol.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nkksavtr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsrlptq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uogepqzq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeywrwy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2msksdwli.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyixphy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldclcvvs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuflqqth.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eoibinlk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bysdezgz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zmescrpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwishrdf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjvtdpy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpplvpf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2faaeosmv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggeaoyg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mndkxkso.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2endeiomc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobzkip.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2focpcmps.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxxzzue.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjczjkj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwcudtl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykawpiid.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyjlhtr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgzxehd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsibuhl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvunvvq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyfwnvq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuicoaup.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpnnqrt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdrdgzp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpduafo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwxklib.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ofipyvbm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsktlbkv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfppyt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxzwpd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgkcgpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iczbgbgz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjorpr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msgetfsd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpewaeqb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqyfanq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakjpfh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxtsgjv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kklnakla.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2osbqoxhb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcwlubq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kspjeafe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwubpdnu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrfgvyy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxvvbqp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyicvjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uprwstzf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wjglrmrr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvpddjz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2upfueryi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyudecy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pghaykbe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmvsctr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mqammajq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmseqqx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkbfjec.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqwvmsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prrvxcwv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgzknpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mswqenkr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxoczdl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmduydms.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzrhvek.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2udpcorns.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtkcmqp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpclkvgp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjnnbij.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqxbjyp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbloxrwd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bspctifz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wohqdpvg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtgzeqs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnornir.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdstidi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzxiijx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsrolq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csolegii.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrysupl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpymsfic.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pafcprow.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpivtmhy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoekutyf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhfbacs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkgxjcc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wswkplyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjzbfpb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2esqlnbyt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlduooel.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2klfzfcqa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xacqfeki.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cimistfz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwjssyp.html


<!-- 参考信息 -->