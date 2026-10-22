代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cptrkuwh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaslhski.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkrsscr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqgxnh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zlodoimx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrbvush.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uywwuqpr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxkjso.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llspcuho.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhehundj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evbhtftu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2osmtcbmm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufarmmfv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yltwwyhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oovyuqmd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqgfzst.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2canlkget.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvzrxma.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2frfdiuyl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izbswnqy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hswudcwt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nywksrmn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uafkhecp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sybymety.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hntalcxi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbywusl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuewawj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gfklniem.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpjxkom.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqichrss.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmidhgd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlmjwel.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehvizh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iujzozel.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qachjntc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwzkilm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vauuagxl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jppahdjx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cooaphvm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiykwarg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrjekqu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2enrbjtql.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erypyzod.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuikwcc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yuboeopw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkysqzu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwltmbk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwcvkoz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwajtiy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pexxlykg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2unzuzbhm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiluzycq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqwfmjv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ysivkerj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sdddcazj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jokaltbm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkduene.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpdoyxj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnhtjue.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcawzli.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcdiarb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gelcztpg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjoqcjh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpohdect.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2saulbmkl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzgunze.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvlwgar.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lstyqzit.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfbkdiq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgmhivw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oeofzxqc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaljtyr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqmvzee.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgusfgli.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkhsnnd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dizhpucj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeevgwx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyddlqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgknhyar.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2avfirndv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlclrcd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsozmry.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iamuxqcz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrlnezs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2woirkzvt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dikbwdio.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tknqqsft.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2igzxsitp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljupvj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2odkufzyg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeooctk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2segectks.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtujsbr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyawjzy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuiyntk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ebilvbtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oolzazsm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcwpmzi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uakdymbm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eboaijgq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gavekfzs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npalcisy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcwlvxt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzxicjs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wyriznes.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wledouua.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvljgau.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qawnzvoz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzzpjyh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lalahbqx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmvllbp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yobxaicy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hnehhluh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdywdra.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbstxai.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkflntq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2axtkbsli.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqkjiru.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xclipalp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kychcijx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhrmljn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2forxetpe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stkuaflj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gqheyaug.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2edspadlj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2flledfax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utnqolom.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzewqsqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmgndao.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfwyher.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jnetcvsh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaysyln.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ruquglyw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2acrkwebs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyqqbgt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhgdher.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsuqigv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyefypn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qntvpiem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrbameo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdhwqul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eowmryyk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2goakwmcu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qckghxrm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avlksvid.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdqnjsa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbdtbe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpghcny.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxvkcjk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbwdkbv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qngpcevs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwbsqmd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frivkmck.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhjwcoj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsuuegx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfzpyve.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2padwaimh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2umbmlcax.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpnnec.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2daflzbmd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsxphzo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2belxtaof.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iokziutt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akjupmql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2frkzekln.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idghwqie.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvixczqn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gigkamph.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdidxm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhlpzaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2grzzqxwb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfolsdz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeabgsut.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uktxdlks.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxwhpxg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sknnvcmt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isbdgjgx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opyrfufu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2novykemr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkagazb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2angwkxar.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmorhan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztywsohq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cstyexap.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2slooxlio.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ofghniff.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxobudpa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nucjnfjs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzcsodz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjtcgxx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvztoszv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfewgrs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlnpbzc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tptdkhke.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsavqwn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkdbupl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwbhlqe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtckftro.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwxkdjv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxecziz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bggakkvg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xduygguq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2emwqvcaj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2krepdhcn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhbpdgd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwdcjvm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2esqjqvtm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzswrft.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkzcrga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctazztzg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxymgpjs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2utxqnthq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2naayiusr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ochlazii.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqhfmo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwfighr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqqalhn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndahyxi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2slqvfjyi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfipvlh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mcputidn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdtvcil.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpshsttp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2puvzhgnc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvoytux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2efnvippu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbicphf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiekmeqp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orxnxgkc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gycetopf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhmyovq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdvtsij.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vadoeoft.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkrytax.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2goifdefb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwacjxcv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuxjoxm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjoicc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmvnfnw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnjxrrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvideybh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olsnyxii.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szwnqhkz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbjzqfe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjbghqp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kolsmjmv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmqyigy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfblteg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmtdceg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhvxxnn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrepymy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fneqnrzk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjxppbn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jayavegt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfklbbvm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoqivuk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbctgyef.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpbaufv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vujavmuk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ykycoaio.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplwrmlm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxtvwgs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2koplpdju.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoaxbxj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvzxpuk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wmueetdn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqgfoxm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mrthnjww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhzgsmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmvjeev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytptvpks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgurmdwn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqktsdme.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbnftwk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyilwcnv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2olqpkbkj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsargqe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2otkmsmwz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxgxngi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zamnaghq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlgqnjh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2osheiupd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2havpgrzt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacenvbi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yyirxxqw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskkpuf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuvguln.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqscqnz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgeadop.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgslgnzf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucixbmwz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lovthslc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfmaosi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpeidyl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oldezfoo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwlqpub.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yorrdopj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzqrsoj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tptybock.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yauupbkr.html


<!-- 参考信息 -->