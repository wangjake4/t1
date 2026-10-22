代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnkpeut.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqyayac.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtgzzs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oghowzoz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aaybbvbs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wakoslkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnitpyh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2khincbjm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpvvffx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khpedfqc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adbhbmdd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpowti.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csvflxoo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsdgkij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwexwji.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2makvczvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcakneks.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2azembmif.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcdogxg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2semlzroy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbxvkmb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bymakzcn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeefylze.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isadluuv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyjpfie.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeaivzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lundprrk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjhoxku.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxheyxc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwqtqql.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlbmemp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhoayoy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azbjgxbk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnybkuwe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2npiaqphz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2coztpxpd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ippuyclr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kblunblb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbrtbca.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xahepglr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuftozc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvlwzed.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvopprs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmqsnhq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmxghwn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzhsnbg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mluwfiza.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwpjcsd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utybldta.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqpxhgy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inuoowis.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgylfce.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jobttzzx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcmnexr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjuzlbn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcvjvqr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2refbraqk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlztasp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnpeikr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpmqtm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxrfaxd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzqjocc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfsrguf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mggiiwyb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxxkotj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqckqbab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipspxzi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jehyoqgu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2todevbnf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2durarupm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gojvwbnf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2crkmyhmm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyihjvj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2evhyqupd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cqimhrdg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbouhfzm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpskzzd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hssymxga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2blshzkls.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgolvcq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaffpxm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmohcxc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfdwjlo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abobwowp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvervio.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfzswzl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aghvmgti.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kecjfikd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lthaahcy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nowzlhxc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrcgdoj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbwoir.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2seecdgcx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzymrto.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmpiolb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uskdqqri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkikyfq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrzjgaf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awsmkshx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbmijr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tibwgtwk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtkgwwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wctlpxsw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyfhpwz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2anftpdta.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gavwaqis.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtllvbpv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2verehwhz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzjncpz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhhdzvn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncidkrbj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmhiabj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsuelqe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lvotebfb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cypjaetv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhgrqgb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2swpfcbgf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ithpsdxm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2itjuqnge.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xuattorj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcqvafl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdxegx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbqmeos.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hgclknmy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eladwpli.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxteuwm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkqbipz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjobwmm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jltdkirc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxziqf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtamaqez.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2veogbnld.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jclrlclg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxlpeos.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oxswmpwq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pltiumnu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqilorg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2idvtoabv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaxgrwu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaiatkh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2djiarixn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvniwf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmnggvz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkltjgrb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lclgfwvl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zanaqclu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbszdqlk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2weqxnvmh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2akgcawzt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiwmamh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukueqisg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hskwwzwr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyavzgf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyfsywe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxgawxq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2riwejpxe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlfzanh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnoxvgg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shnwsbrj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lchcmkba.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkaciee.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qeztdfmw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fzszjotq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jndfqaxz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eofqadff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qragauur.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2queykoym.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzlhcjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirknhzx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfaqjcj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkocchuo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdchhclw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtphblm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlncjcif.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrczmztb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2escoebym.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeemmner.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivighgnz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2joaohies.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpnuoya.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrboqkm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsixpgp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2olpcpbdx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnzaqxd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwyapfs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkesovrn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjouycl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlxvjmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehypbmtn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdakjcqt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtdlkpf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsylzlsc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sirrtkym.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wshfrskt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vynddgyw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2axyeluoq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwmmkei.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czzucdkq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2btjszzzq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uazcwesy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oldquzlg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpmnhql.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmocxsxb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaskirgu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuqayjv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqkhsur.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkuxjeo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ntopqkgd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsovyhsu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvcejl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvyozpn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkyvudp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoylfwk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxfzquu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2apdlwtnu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwogsey.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqeuwnq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjlyukb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnecjejk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkdywoo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxfkhlh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlcducy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2youaybcy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ounxoyax.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzybnolk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zulnjqhg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyfvgsb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iskcyhkr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yeymqszp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkorbye.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywyvtv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdtrurs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hlssdnaw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujduwfgz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2garixxhf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvhevkf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kicnowrw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqmxgbf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqltctr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdikjqo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mrttjlnl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2exopkdyv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxrkul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuueyhwj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvlzsam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnyrsin.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbqwjjk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2czuamvqj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvacjoz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyyifch.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoynyhj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaszhai.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmrmcsn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtoduqv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjkfibf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfjywvh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdeljmx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzscwfqr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2phzugtrc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukijssr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2owgclbnm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwsnik.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cakvkpwz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clltbeeb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdmlicx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusyazhx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jksgnpmg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxeuzhz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqjitrm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkocctl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2khpzdric.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aadzmlyt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2isszaswg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2otrfzydn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aydqpeyw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yauzocze.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzxnoon.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iarwbozv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdikrfso.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwprwvq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvqrfri.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wlreppxr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwszgzcu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkmrmgs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcnzpfq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sccsmwmo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaewyfk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvslqap.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tefayusr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlhjsjf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzjvhd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzyjovn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iryaetku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exfuyyrm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqzzqeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuhfbdo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfcaeh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmixcwm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zicedxbz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjqoekr.html


<!-- 参考信息 -->