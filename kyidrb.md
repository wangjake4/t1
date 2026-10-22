代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrlwksw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dncqlxrp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpriufwj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdhval.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrnfvx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzwxcg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgqeqni.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icctzkpr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xavawrop.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnnuuq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uwygmkkq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrxowyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kcajwxlv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqucesq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlygtxo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wagclgux.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xteoqjid.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2izkvcgft.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2udpxxurq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcxxmkx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pdehcbos.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uebwohph.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2viqaaqxi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbulmkzc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfmmabv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsbczpm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqjwavg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwsellp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtcfrit.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qycjkjqa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnpxeii.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxkncax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvvweaz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoicfuv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kihhnvgq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdrbhq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoxmgko.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkppjqz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzkpptk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cncmsgur.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmtotnz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoxirup.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcftmkvf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpglogjm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wstjnvoy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utxeweng.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtluguk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2keypawbg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amsghtse.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvgahrr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2trpmnfdy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2itceizmj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqwvcks.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpqpbgy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsdbcpd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fepwshut.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwaelzl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqssubd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rckfxpdd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhujowin.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2artowxld.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utividat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzikslsw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fzilxvhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtwhwwd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyyftv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoajopx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjaqdu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fugrhcrk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mlahhjjc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gaastrxq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyiixhx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djasuyxm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yobmpkuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbasjd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wtniyzhm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdzfvoh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwxvtta.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzdwmbo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zprrmsma.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2agtruzms.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjqgcfr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzxsyvy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyagvgm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkhsqdi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ionfycmn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfwhhcm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aksqclbp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsbqkrf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqchse.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcozwa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyafcuv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sykfegju.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoyhtgi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvudkjvq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpcxznx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ceajpjvk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mrerhgfj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtcgcsj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzmzrtk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2myqblpvu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhghtoic.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrvkzkr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2phnollel.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gwavjioe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxzmpfp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szhrwghy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrkgtpj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkwajrz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2snfpbtiq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjujkke.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zuftsvgy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lftgbkdj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nehomjmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aixpbtxc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwgjanr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2odqyckha.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbrvhud.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pvylgyjj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jsulyoeo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fctommqh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wttxqlel.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ntonqsfe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfcrfbz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgcbpj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lobvybms.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbourhem.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejosfvfi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwvcrch.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpsdccj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aefsgqco.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewphbwmp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvevdmx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2giphuzot.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aanyjadd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgckhxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyuhwax.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkrwiho.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fihukixr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vzojycza.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwibvxm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqdtgdh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpllbcj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllewmo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpnmocc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqdiisu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ngftuqmj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoixgtb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpjyjvs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwwpzxs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bhonlrue.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xzarvplm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzwymod.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpllokf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jenruxcs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbuvvxq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2madoljgx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmhjnpz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwbkxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2punegkep.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxuarhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzgslvl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2diqaaith.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2txllgdpz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erdikewk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqeavkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2opubbavz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmufshl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kriuuhfx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iljjxyck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtblfq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dflyeiuc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2usdppkld.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxypezi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilvbvg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsiqsnk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2itklyjhy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxjsxvu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2likkmuxs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2udhqduew.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmckwf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2snvbtnod.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmwmzbt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inygfwsh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2juqnolig.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnumyfhr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsvyltm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuogfnuz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbnvetj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjkwtcf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogonrxaj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyaqrly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgosrghs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcspzsfw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxjeofa.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vydfostz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmubymz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzqbirb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvhixpd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjquxuke.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cryuefuc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qswytpxu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumavhy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2smfqcnez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaervpl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiocbsh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cynpggpq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyycgvh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfmjxt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybwxid.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cafrkezy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjcvny.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxwigoo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cegaqleh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuvvucf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uplgopps.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnscahuf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2syfdfxvn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnulkjmc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aipoeaqb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puynzzht.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqzjnmp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yseerbiq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmlhgat.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwvjujd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzrusbj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwctymg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivictwrp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ybieskff.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszhpcaf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqaujkl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2etqyrknd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjtsaa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebqvtuj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpkhtco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgkoqqd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eslivsko.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwyowpp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlslzugf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tocolpoj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjohexh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhwzved.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yosrxsmj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjjgcim.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmdermw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tiodfamd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adnkaxhi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnkumwc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlsatum.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpxstes.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goeoqjjl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqrnyzr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uevyvxmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoztakb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrwlzre.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piqljvag.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pofbxrgh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvdklyw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaipdbt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbozzyo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmhtvtj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tougvnov.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snycbwrf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmevenks.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqforcqr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuppclo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkmbalt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jdefnbaj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoiardr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwagbebk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdpsseh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrfsiat.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fctxwnqa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrhsxim.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2swomosga.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnhkkkh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2updqefuu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2stqlhqiq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrchasqz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2msqqycgg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvtfog.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utrrzxce.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbuheje.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqukldo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2arldmzjm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pzonqknp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtltynlo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrbjopa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvzyyzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgshjvjk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhkdtxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzmdvlz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfikhwuf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsybvigw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2outxrcwu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfqwrdw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rykhecul.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2huffvmhx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2urwlocep.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2broezapn.html


<!-- 参考信息 -->