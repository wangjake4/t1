代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdceapf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bcryytto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiopmii.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwijsrq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbbxemw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgejondy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptblrujc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jzryndkn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uevieakc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amozfeha.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyfjuxu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2guzdzysm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vamywpih.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtefyqu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfwzrif.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrseyitj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxkyumw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqbsoed.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmqkotk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkktudq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2biubcjkz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2stgsuhzg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhskkbsz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdjnxgj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzufecx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvufzlt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znfyaazs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bofpcqjm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izwhxmrw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwhirdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjbhygj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2psjjmltg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2febwqeai.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2trvqtfcp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmhwdsp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhekgyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knlroygg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkkjgwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gooalgdk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iouiijgq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsjuqkh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lubqyouc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjdsssh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvjpzty.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2covwzpot.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pafjckgh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iajkdegm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmkifd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2paostgyy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vocvvorv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvcoyzu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzpkxt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzoykyi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2axvyngjr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmnjhtg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vutkivre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tffjnlje.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oegncpur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rqovbkyf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cconefke.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhhszvs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlurrla.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2snlwoddp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opaxthjx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2whmmalgr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sldfasox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tkztwavn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqxoima.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dybdnrry.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2djmiewhc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdyvpdl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlkudlt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhqrizt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cutwhsjf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iijooecq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrvipih.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqdhydr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjvljto.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jcusmpeh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kpamkkjm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhymwso.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nwscnbow.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjdqiih.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbuafdw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szpqaafg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2njouotjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmscwkp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awbeuamr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvzjquc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2krwdzgja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fymtzsof.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vgllorqi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mxubadpy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhpqwzv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpxxpdu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkzdtgm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfujcna.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geypnhed.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xumpwaii.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2chxtmeyd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uavopygr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xswiqhyz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2izbzhnqz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfyhzpz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxadbtvk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvenbcdb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jenoyqlg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oholcedu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eghzkjit.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2phyjgjua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igkunfgq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwouotc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqcdrta.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvcptav.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpovbih.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdmohvt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlhurnz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2grrhxujn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrdcuns.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mumspzwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmyblre.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2twlezraq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpzcrth.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2imgobjwc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gshssouc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacpvla.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yltmvbiy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvtdbvr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cydeyrtv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjreoi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qspmcuma.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlwgvhb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxcypff.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gbogtarx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqwzohd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lpywrwej.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iuckhzxv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jwodfkqn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxmnrxy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnzagob.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuyltya.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiimdotk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mfppbkqk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtecofc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqslyut.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzbbmqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvjjtqb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxtieg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmohthia.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgsvaho.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2blkkyqlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrzajql.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuglwdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rexasqgk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uthflfvt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ywinvjsd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmensii.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjfwlfd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2weloevqp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkolbvym.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfuixul.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvmjsup.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2denmwvue.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxygfana.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxmvrtg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nesbuovh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2asovaqxx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgpaypw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbmacrj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjmhorc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2imuhyava.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlhtzlt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2brfrotkd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2weunwjda.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrwichd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpgjvqs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ievuclpp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpasyma.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cubcqotw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azicnxgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvimiafe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vncxipyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdgybvc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkcfkly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzufoloo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqucnkme.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxctispv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhilobl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoonzsuh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ultbznmk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opkucgap.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqamnn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2knootkmg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbrpxur.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgwqjxl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kczxrmrz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbdagp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgluiyyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsufxeib.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoskmuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexederw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mramyxtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbonviyz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2whxgpvcr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxggnbzs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmahnmzt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzststup.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zowmevry.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2clvyygkz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhfyenr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsrsmmq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjutcppo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iprkugtt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoypbbx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbskoaj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jofsbjvs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2owaqybpn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgsbobb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvjoklg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rulllxqj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yodbyosf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghdomh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkxwqov.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2stsjbjfv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2isyykkbw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czqzvdrf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2plcdlprn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfjxyrq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ksciukdp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gerioect.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xqamzwci.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmoqteu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwytqpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftozari.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hiupgyip.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iapmlauy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bupokdue.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbagxse.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fupegyyl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cetgeqbt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imknyiij.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htxzcsrl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nekdmuxc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwrjqvf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbpsakm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnosmmsd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ogccuggy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yibpakel.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rkehjwxl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tajeheps.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqbudnw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukazmsd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejemnqom.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evkzpyvt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnbnrre.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2adbqrhbj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvxlnvq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybsubz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bypthvkr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcvainm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzdvzko.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iisypvfx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyptdas.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jhunqygn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhztljk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ggifmaej.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmvfbfm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rneufyce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwqbpd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dolfelhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpraxco.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2patmobpz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnddxgi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnhytpv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqagzxm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ipildzqc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnhqbsx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yovudqsa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyaoxgf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acqhimbb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyfujuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwetdrip.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiajvjnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzagpdr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alzvfwyp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2llpdiwhv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eppjgmkt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2biotsnfd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgcgpft.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzridgop.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmephls.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfglgzpx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umjtzkgg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccftgboj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnwweik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wttrqrvz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uqijkwvo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnzqvbc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2skibkamu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnybgfz.html


<!-- 参考信息 -->