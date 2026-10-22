代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazlbvl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krwqnfke.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fphcuzeg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svtvxcey.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqknqcr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbywmly.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplpoun.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqxpsrb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmplpos.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mpygzopd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaxxlnk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrkzela.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2alrzinsd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhlejh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryedvnep.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoggslrs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkafdbk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uetpdcvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2auuzeaax.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfpnmyj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrtonxs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nybicaek.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bztuyeft.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geppxamc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkxexs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lecrjqra.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjveheqo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2weinzsnt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyujaunz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmdpxwr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxbmsxx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjtqogm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxylucd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mafvpxnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omygbzrz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gosmvocm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqrxooa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cepbccue.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wirsecgy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvcocfh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzfqqfg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awfylqcu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omyxgmxz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2exhsdxkx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnksejia.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkfjywf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2obfzdzmb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfngpzs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqkmhmw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfzkxnk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2trpoldur.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hamvpidr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocivcenj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cilpyykt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuughib.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnxcouc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snnomufd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbzwvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfyetmc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcckuxr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxmawui.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pheuuzbc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fenpmsbr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qlanptxe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnetuuoe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxntgnmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvsbgoe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dodmqqem.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irygaavj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfxxmez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xuowycuj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqsewmq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2elpsqhzm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2brcvzser.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zewmklpx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2stbffgsw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dezpobpx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fswgihmh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfutajc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utvdvqso.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2birmbevs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2quyrayof.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kohjuxof.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2przzpnlm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsrexgv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2knaadtuf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlwobhs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdtwuva.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyippoe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfolhwxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkremoi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyjlqpf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ayslwgym.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwrniv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdkmhvk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpxjxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqbupe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzirxc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfkuqny.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmfcojh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtacxis.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evlosjdp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anrfbcki.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fdltadav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhocsps.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2btibvncx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvypwmd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyhsejn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhkzddd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuraknty.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2luggzltd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmordrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcklcnf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfgsamr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjvrltv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sndeisrf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxynfvw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbwnhss.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlauqrg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcglrjd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcrpfut.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dnplpqby.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuxdojb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uggobwss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gchavdja.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuyzrbj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjrtxxt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vbumabwh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlpjmwq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dareztzh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmthcz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eifhmsys.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmjbbta.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gugkujai.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcgdqrx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rffwkmvd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqebydj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjxhqkc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgohqlfi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnajasw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsviyn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eoydzlgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wltmxuzf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjkhgyr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tclxlfqo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aezibmkn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ibffciil.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmmvbjh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvpyvnw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pylgmwge.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocruqjso.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyfivit.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaaemva.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxhjtuc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gddojbhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ommfqbwe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lclhmgoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umfqidmm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atsfwxcj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kstxmnzc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptqpon.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mazjnfxp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiemqeb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocogmfoq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlazlazg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoebotl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwgpkyl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azwgvwof.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgfmrcq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqefrivs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnfvvsj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdqpjti.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tquagyby.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lthzoeqd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2smkgtzhn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2moxovaea.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jefannny.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2piutwosw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcmrpvs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uixowdnr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqlrpto.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpvrdvz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsznuyn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtinhkvd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfukhxyc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2itnunjir.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqbgbkc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vczrxnnh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2crfwwkjb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnshahgd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjjmjfp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bdasoxmm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyomnqkc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2niyevqqe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwaoxsr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwejdlzh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjfjxjy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phpmxjma.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdlhbv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opbjkeir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtshwxt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zgshgavz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbkafus.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiawevi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnpiotz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvefpjnh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzwqdhi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqtmcey.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnkulqb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ziheqptf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zizzkssi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wntaolbz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2slmoohmk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmckvnoi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqkfxnq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zikgkuhs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zivdjfxo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaplzrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcaddge.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdvkoqo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbifhyw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oszlbpmz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2phjofvse.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjyltl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mhelqtxk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcvsqyl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpupiwd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfnxijl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkmnyac.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2liahwxlz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpedskl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hymoayqp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2glnievvm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxnnsss.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyanxxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqiaouz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vaesjqzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwrtvpf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpsgnlk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaoiama.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsbutkr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwwjaqn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvbwlvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iomvwogp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiihpggi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbbzmdo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arxaulev.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxvhdsw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lcelwtas.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcffvotm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvcume.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qehigmrf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyuivwg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrniykhn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzyaeec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ituhhcko.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vpikmele.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrabfkw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tahwmtbd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxoqfgq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpdxlsj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdajokic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnjqlvw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvpmdmq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnymawvw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgzdkjo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzitlgyx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fboaorwq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhjgyxe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsnmzgt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqsbogd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crpewppl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezzrolr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyavdkn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqmwptp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mskvyvrk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plbemika.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsgfrxm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvdzjd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrovsbu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuubglj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2swdotoot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzmefh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nifloudu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnillsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thplygjv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kezjiauh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egolxsuu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzjbema.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhilyhf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyauxsqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbatfjt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuzqstp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywonbkxh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2whadfpnr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wggbirya.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvevmkwy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zstijoir.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsbkele.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izixayvv.html


<!-- 参考信息 -->