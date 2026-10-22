代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwmzqhw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhocjbcu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgytgci.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmfchsa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuvfvxa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chcsrvqx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2baqhwfcz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eawmuosv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2myrtthna.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxlgix.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqqfhac.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuzrxia.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnnvrza.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzkroav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sswardek.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfkrnjp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyjhrlx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2asyymtar.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htjsvxby.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnhzxoi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icflubze.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlngkgq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycedbrav.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhwrnau.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2katvyhlq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtcalzw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzyynwk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kblqoaqm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlgywsg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2epplwsdi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kctmjrmp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uixjovhc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvisvfb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdfjhqg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkomyce.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjysha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrniupl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqkoiff.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnegqksj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbjsyjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpiaio.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pniotafa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzjpsbx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrzmuwu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhutupav.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vkccqqex.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsfeyxe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iczuibyu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cneqzhds.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvsnre.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmklnkor.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zitnpfdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cexfvxut.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rccnuniw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcoiki.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyrgjuo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zqccoupw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwfxkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmbayok.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxwatoe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouibixsq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oupknsnl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkppcj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxcdgvx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhmedvg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zslengyu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdlpaxb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnuvojx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjwbnyg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyekuge.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lctfnxcp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhzdyps.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzulngzr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzajzzn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrdhxrl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nryvecrw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlubydb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oemxdoco.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdhuzmw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkctdad.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uizwplgl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kwudaaxk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rleqfhtp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdotqkgc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhapbyke.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrwsvrn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oehcyvid.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgcqfej.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqjxcsq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2onpravvk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfngjpfr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2omgomouu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjjjjlk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ragyslsq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbjrfbh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmuqffj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdaqmqv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eirivsja.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdzontd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vftymaje.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmfzok.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqgils.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nedstbwp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlangrv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdhcjec.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxjtjhl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mgebzxxb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgbxpgy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2avqseyjx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2absedufv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjvrbds.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcmkbc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2olubbfyd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwuqglo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcieheb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqgkwty.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zynyooiw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2polrqrwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2berthtql.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrudode.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nemxndlu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdzfjdj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vuevyvwg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyttqxs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yaadxpaq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgstbtlj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpjfhny.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2edtywhtm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tslyvlwn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mwboasek.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qirmeakr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgfnwoo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfyflus.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlafpim.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aublwuwb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkqkdhj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vqefrbte.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsartwo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cftdboev.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2snqhlivz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2okyjiwlm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxuosut.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzojyb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2crrwnomm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2goihccgv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvsfyp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pcscbstt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkpdcho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmnrxao.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfvrzre.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjylwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zitnbmnr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzalnku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdzynkw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjzuvzc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nurlopln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgjpnm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbknnjs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfqptsw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpurjqk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nntrlohw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtntiwa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwdmeqg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoxlqxy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwxjip.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqpxjje.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfyicva.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2afpohkft.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2emfasamu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvseowh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaymwwg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yxldvpct.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2npjkqgpp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwgzklh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlbnodw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byvnenen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyiugus.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqawpmx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdigrjdg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzjujra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyqoxts.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtkhtpt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjzwmeg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmwrwus.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2abtduzlx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbcgowr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vctekmii.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxpszjz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprmjyjo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2erczakgb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2grymdnuh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2juoldgzt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2onzdolsa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fykkffwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2txicmviu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsxmjtd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epjqvgsk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxerebl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvhybyy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwykeyv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2flonmuam.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xobhkqpm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2woqltsjv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnlpquu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kicufifb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2givtimym.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwnlvfb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2beaymeca.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnozuaam.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qczulozw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyfmrsq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcuxivk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xllwcmgd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdrqmug.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzqdwsk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fhayjuuq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjchaoz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zspucwkr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2egbresww.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kynqcbmc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2czwpukvx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loeixqnf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dglooqoi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdsdkrl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrdxwfd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooslgxqf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfhydbn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abxydwma.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvfhkjy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2layxequq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrsgmdt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqfdcbx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eaovmimw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtffdxxl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igdutbpk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewheoa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfrpfvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhpqxhc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thjgthkx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zerjksji.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnougagu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvwnrsh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwkiwer.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdadbycg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2axxlmxvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpygdvf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qlefwdpn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgnnspc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkjdtea.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgifacqj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcnjekt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2burycqyy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ftczwejf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsrgdyt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqdsnil.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzqrvfp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrnslwr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbpzmwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xchzlipx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2twqcyhtf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdsqvwg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcymhtv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2txfwbqqk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tnebnhea.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bydqnwtk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdlakyh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpbbxrs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrxiaoj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2msgytsfo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvocyrd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmgnnpu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkfoqfd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucroxtwc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfddyyx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwororsj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2obhqycjq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnrrop.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkobshx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjktxgrv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcprrea.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxfounz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmclunh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxojqqha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biseyrru.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uwykjqbr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nedrwjju.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cilyyklj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjmhbwy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ptavebqe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjbfgb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2abiewosk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ndezlhpo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zsremzyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnesnwgy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zlttstqs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvpevgj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dacnegfg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufydczow.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzluzac.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cockukre.html


<!-- 参考信息 -->