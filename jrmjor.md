代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnnbfen.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxeuzbc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhxlcer.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddirqkqt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzdgtvm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2srsargyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vucayrkt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2poigxmwd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrerwal.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmyktui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fouhhasp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvreuky.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlgkxvf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdmlyge.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjnytzv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vilqoiwi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgurzisj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2epgyyzcs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nddeyjna.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqqfatp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmskdufn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaajofx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbzkfku.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmstobyw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yctenxra.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kehxjdkh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axhkptus.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmdntzx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwnifox.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcldxgdz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvfycn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ztszpezl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2roetgfrs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtzxkwr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2odeiyogg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeneoqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvddgxe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcpwew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqozcmwy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpsofak.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svtlenkx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfyfkgi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uipvlpot.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyyecqu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsvyplw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqfreyp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fhixyhey.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2twnbiqli.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dodbehpa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxmvdff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2knbkqchu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jncaiogt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxmdsx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qngmpwqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgqrufo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2owvgspap.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2togsjear.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2abewttlt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tynlwais.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iusmieyw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nokavnyb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2emntauji.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azvsqvcm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzycpgr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bftjmnvy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2khlkpsni.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2osdhcmyt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2phnvnqld.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nvckohrc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gmogentw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ixavbwdk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhgfpyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuirckg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcjdiee.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twohfghg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxyxgya.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qgojooat.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2igqtgloo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mswmauid.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2snciyjgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndzubf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2heizxind.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfbemam.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ythnirof.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhedwsd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixectbal.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsepzqzy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzsnfck.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgokvct.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdydxlj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjjtczz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwquqlw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cppczkyv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byequzen.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xakwbern.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2foqjtxkc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bradhwth.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgzlmlc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgeirvq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgupoqzt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvtzlju.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqfadar.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdcahmc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxyomhi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fifmualg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2khuoxknp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgdprjo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yedehagr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvduoux.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvndjcli.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jvitpasa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizuxeg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2guossdsu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzafppzm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhalmxyh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyinnan.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cphcrmqx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2deohipbg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvakaje.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvsxedj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfylzrym.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjtmlbk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpymgyw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhduji.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtsrygg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pitislob.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbvtxaw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ratewqys.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fodphmnn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zohkpvyv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfgaexv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wesccytu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wmopwjdu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lehbcyhl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcceumu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdjcrzc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2taqvqifw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztfyfp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2crlnpamg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqnicou.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeljghl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oylxmmoj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnajmol.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsgvgjm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbronidl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2arxpqejv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzmgno.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhwrwtv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjojprnx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkvptip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlrycnc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adcilncf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxewroqm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwisqqtm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tgplfnsw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbzvsoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2faowwfzo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnciceb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjlpxbk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxawbut.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqlvafh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cuquvuhv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qklopxdy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkyrbft.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpswsdtt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlfvuys.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqptqlvn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qytzuxbp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2douxmdby.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dysonrgd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2acfqwtck.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiqdnmh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouylnswc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwmmwzf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnetepvc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lubzshwl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzynaxs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fikcyzfo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaekhag.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eabkmyhk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nptgfbnt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoiqvhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hblrmxal.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnjlgcu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvcmgqq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlaiygx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwihiuhu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2asuerwlw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxngwf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kviahkzc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzmfvnf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vjusbzcg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhnqnea.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2msiiehwd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2goovbvcv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hujblafg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpionrwo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqeazji.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2forgfqkf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilykwbnz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2msulsozs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsfkklb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wellxuhf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwvxyoe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hydiehmi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kusgzrfq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpwimhz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyrxycx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcebuif.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwpnqve.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sakcgmyz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvrtibg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2abszmxzk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipzani.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hnifbqfo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfriezwm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcfdzbl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpnmjrh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcveozl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhavqsab.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuxfgxz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2flpefsri.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efqzdnid.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrgxkie.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2razgdsss.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ibafapxm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrfznhu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2attcukhi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dernjhem.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiammtu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfatjfww.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgiftvo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvxrrsi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjugekbe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uechckzt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrrucp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvajlsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiqgord.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmpgolk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lghujlcp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnnkcci.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxitltmg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cilgqdqh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvffhaxz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgxlivc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbnevom.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eakythrq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yupwjjfu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vthufyih.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2etfnqmkt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ablzgaog.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2smgljccu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethvdopv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyntlbj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjyrlok.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rcosnwjn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oouxtmdu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gazfdpnr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwgybtf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mxumhfht.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvbihoq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrrzbnv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhxjtrr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyyxbpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvuyasy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrxaewk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkfqvyv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzljttx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmzriyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqohxj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkqynvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyfaxtf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vorzzcvg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2czoebpyn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ratmrkci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2thgonssb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiookxh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrslayw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuxzkkc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fapyrclf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eevqrgtk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2akfiwmfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhafvkm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akhoidsi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zizevepw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2emsdhadp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdgheti.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzwfrce.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oifrljus.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnqausw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtsprbr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqopyklo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqklnksw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygxuvek.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ynclyygz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuajeawx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqjglhq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabxdohr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2icektcmd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqvnynq.html


<!-- 参考信息 -->