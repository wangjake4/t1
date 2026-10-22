代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tvydnipz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oltskqlq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgnaohh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxqqula.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgaurzp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevkaju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfgrnbn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juocdams.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgkcufh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srpgtciu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jiruikpn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grodktvl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnptync.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tydxjsup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dufzoojd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbhsdhs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyxuzft.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpokihb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgceec.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bekwzxau.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xttvunrv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxslruqh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwawhie.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcydpsf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqosvusy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzqvnba.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsahpme.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anfizanl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdhwpnc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiycfxwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftghhdmu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsbsjmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2basoaqjx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mifwrvpu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlawque.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gldnrdsp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfrhhqm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2edobjvyw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nywxptno.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsbiqzs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnvjtxa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uevexbuu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftregini.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcorvycd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grcmoopd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrokbkz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itbskfdh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvygrms.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fieufzhb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2quijjqhj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bltgljkz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdiikec.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgejxuj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrdpjmc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2djpsxffx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2durpgxve.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pypchntq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmibyhgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgythfe.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azqvviqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbtqeoh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjbxwhk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxrctzg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvnwmmv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2psmxudyw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hssfzafh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjrnfr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iggquald.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgenonc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjahuyge.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2enzqvcfr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcehahq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtglxott.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sqziiinn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cofymlqm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ztehubtu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfueooq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vaufhdpa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2szirgzjw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2euzyohun.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxanood.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oksxajft.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snujxvxw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrbykcc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsujsub.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2asbxbmcj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2euhyddwz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwskpcr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmsvjy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqzjiaw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtntkyn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhcxszx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdkkamt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkkujxy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwirxhsf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlppapw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2odjoxmlq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fybxwixo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chvymcko.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qssmyero.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqoeun.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzupjqr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuutiyq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejauqhjo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wngyksae.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqibjxma.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpphhmk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmuviyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjmdtyh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2udcgpigm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kofiitlb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2twqeeaut.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nedfgfve.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfpgrzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhwmhqb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxmtozu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iegpagxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvbiywp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnjzulh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hknvltqr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2llrfgeam.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hykbcrnj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rllfggyf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnjrzux.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfkwbzi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wsligpji.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2orgizsih.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvowkim.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jbulyrdu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nclpytsa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmfjbtd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmflwbjs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qcafrqfi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoitlrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umkgimid.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yycubwwg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bluabakj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2luybomya.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplblpl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnompwg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oybcielb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2thkaazqz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqackei.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyjnxca.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jiushdjo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oigfqwoh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwuuyef.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xujdzjnd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wetutwmy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsjfphh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlkebxu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjbyqqz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmitvoi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gadtwwiu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iliqsyom.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2akuinbpp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbijokm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmoipwt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2huehakcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnqeerb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cinqqxtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpodyxgu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwtzzje.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhhrri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqnzihr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwlcypn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rimzsjrr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcephhbf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mduqblhk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mhltttsl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfkettk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agpphmfc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oysossly.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2feitcfxc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeksuyn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iivlcxdd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwkejzx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsfbfs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2smurrfif.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aufktcsa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoyzzrl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdznhwrw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2avdsudrk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gczvyfal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2snwapkvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoigottu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmuasuo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjogeln.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfisqtae.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2adqotnme.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtentzul.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxaxgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2paovzaqd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lewklpvb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2csediulf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rxogmbso.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gstgikhl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtqclm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbxnnkz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnzydfu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtptpdz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgbqtix.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffghkeml.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qayeuuao.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupeabhg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uleizfho.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqkddpn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvzgar.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmjncrj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtonxwae.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfljzpng.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqklokd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wououpjr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxxkogq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2edamsdmn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxfniy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcaskpy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgraxvb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rumiaczp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nipxczdx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzhedl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyunmln.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrinmtof.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmjirmx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htsnesjt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrbuoih.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rfckydlo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbvferz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kglrdjlk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvlrchd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgewpjlb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2risfkyfc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhxfrvf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqvtghd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wvogvoed.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzkpimr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqjquxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsednjy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2blyewdnp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wctofefo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsqpubn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyfyyyx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjaklss.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tktnjmbw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sblzdcer.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rigiextt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtrwesw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrnifzd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpksfugw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eldivrab.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhexpdzw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnihkmlv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mwivlbab.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknrpub.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxmqgou.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lngeflyp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtvbnvb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovleoijh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kixpfdjj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrcahru.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zthxnoyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgghhpes.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxkdwth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbmkjgk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzloyojl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpuaoet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmyjdtn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jfanyybm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygglrdce.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgdjxgd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tadofrnz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjeptl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjljsdo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfoaikl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uokzzjhj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rniqedaw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnzvoft.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ewddvhmj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrclzdj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpalonr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrydqzf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmaxsek.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopwlpjt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbiqtdb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffazvytw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bifoccyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tufeiyoa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ebucvwki.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtvqpda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfpfoki.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znwrfvap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmiljjt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrwkjzd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eknbghgq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obwuotni.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqbhfsx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wwerqhbs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjdzaa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fptnuwsf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wehekmvf.html


<!-- 参考信息 -->