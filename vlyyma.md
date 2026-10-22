代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfegulf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phibhvll.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmvzrza.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqfpgwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzirmaui.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2quhmgkqb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrnjytu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlerktpu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bodyeawf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpxvunl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeltrhn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbwlelc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrabywp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2allhfago.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqajbsj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvqjxmt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwygozu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgkwvch.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdlmvnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrddzqs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjddipdw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzawjtd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyvdlad.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtxxtsm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqskiphs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmvzryw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2illzoplz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqroade.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2atbibeja.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzijeulz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nekhpmaf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qszvnemm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsronrj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkzzoop.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcnnmtn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtersy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxeruh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmaoenq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2twikgfos.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfgquhl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhsiqi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fazouliq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsrkzld.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeicchl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtvzgsv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnuwtaa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfdqkb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfpenyh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aaffyzca.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrprwwh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2piobbduq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2buafmpij.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2faptgtfh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrmmmaq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxbrnyz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fciqbeyf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqwgoqd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhvdhfi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyxyeqi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaufdfu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tucnjgor.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nyedxxwu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjzrdcn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvwhsmk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdlwhlz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobdiur.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpgkroe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiakzepv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dizxuyyb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kppajjjy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2usqaozkl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvdczkr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2frfdzuqq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2arhgkpxu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcbsed.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxlcrnk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeojzwi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zisgylig.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbrghap.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpufrkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2akjzvttv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfozgmm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhvrtok.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzdgxuv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgpxybo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfqlyqr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbtdovw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcsedll.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tvekmbjw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2acjmaxlo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcpxmya.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xypnrjrn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvapgea.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okwurvvj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrqtjv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cktxmbhe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gklyeeqv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzstcjr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrnxkpd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhtlubd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2euqdwkaz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxrfdfm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuzolnn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnckomrx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwybktv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wghdhoti.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bagaesky.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iaywfkcu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnesdxs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmhlxfs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywusjj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smdxirka.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrgwfxa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wghiofgn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdhkiec.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaihnou.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2oaspqdoz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpkdrct.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsptvrt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkzbnvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2emmdbmdr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwqkaxa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfpwdye.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2airyepod.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eubnxyar.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pmildpxq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzfcmte.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgylgqn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adoggvbb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnabwki.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uexcykyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lithxmcf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyzorjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiyapne.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnbyklt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aeykoqtb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqftzbe.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyqymxg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzxvuft.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2byjkrldx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmqwezl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zotcnivw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2imuotaey.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwgornk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdcyubd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vuygihlx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nrccqmoa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvktzgr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcphbmzy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxmivmg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbzbaqh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tgliayrc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iaurknnc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkdwzgk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpltpzke.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhfrwyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjswout.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktcgcwk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vshupthr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkyyzif.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrjeqzk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfflvhap.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dicxehsv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2erimagoo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdacxeqp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxsuqrh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjsysro.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsdmvsi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avfrubkx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uujwjmxx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vicurqma.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmwhchj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxfhnm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dksjjply.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wypbrjfs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlpvqxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnjiudt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwsrzou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaafulh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhhuvsr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhkqlgx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2poqedvez.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bevovtrg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbgiku.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmaypym.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxioir.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jugivpxh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxydogw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhanzyon.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjubxuoc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atpilyla.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czzibutj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsaieow.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czqbuqjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsxlqql.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbtmeo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmnlyqr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfkqusy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2coubvvgk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzyrssy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxziqdp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqipfykn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okgahxon.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2idjxiusy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hempieys.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqzxjnn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2olpppkgo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgrklyg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2itnspgqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krrzlnmt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrighu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhjfjto.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfcouun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeixrzcm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfttarc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvykcie.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiiljoz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2stggkekf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxxcdlb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsumpyio.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzngzqgv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpesgkr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzassryg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2prscdgfa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jswyelid.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yozjoktv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wrginlkj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krrtgxbe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhhzfcj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnivntmr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqaqfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbfjzhw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nknfrjcz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrokohxx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuohkwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqfiswk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyfrvdu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oprkxtxo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszpijo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjpysnh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxgpmr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjcrzmm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oajnkall.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyjohck.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etpllygl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2evwsanhs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcffrjgm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abuneiku.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpoita.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yofmfpqz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2malpruwm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyrtbxh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuakfhq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqzuwmg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eujdqbxo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsehqlu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtxcjha.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2omdfsvfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pygrcwah.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2syzmgwkf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2drxtvqpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srqqbfvu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwvxmuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvfxfgp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpeywgi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvodieh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgghrzyj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnlrsjp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uurwrdqr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2exdwhpxn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmmcbcq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2urjyrqrx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwvular.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2akpkojef.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2woffpzuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuuhcsp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbotidvh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgsvcwa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2syerkyry.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxebkpeb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swlbenic.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoapwvz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhitprxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vowakrry.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2npukgegv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuicfxam.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwoupxo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfmfoa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kunllxwf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqbjkft.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fucsruty.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrdbxlv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wqegjemx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpeocev.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pssshglw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuupijw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2izpdldxo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwhkxfw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyedqfz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxgipz.html


<!-- 参考信息 -->