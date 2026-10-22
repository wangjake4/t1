代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2azdfbswz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwayleru.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeaqhdp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqambjd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqesoodj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmpakrl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlquykp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmpdxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjpxptg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hihqlwvt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzyyznj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbswjuv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzqyutk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlmfhng.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oenphuuo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2buzbomgz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wglcmfse.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxclst.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxycaftn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccgyby.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbwqlat.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwoqgqa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnqifpb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hgumuiap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsvniwo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbqxxrl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eheetbxt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoahqwk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfhxwzz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfsbhrt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzizjvf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2akjqjnbq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpflkesr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ovycnazo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svnqypft.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2outsjlqw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbthblcv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdmrgjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbvprgf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gkehzptk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuodomy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjnjsgf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeilnhsl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cocjvsjc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkbwoax.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfiudf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eedtkdgv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qskhtjkx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzasnec.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqedueg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmappxek.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnzhcyn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqgyicj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyuyvfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnygejz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lskusups.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnnhjhd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrydvr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtridwu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxpudm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkalmwyv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2esvseihy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zggdqoag.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2thxvhuxw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2abndwcum.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kaavwcnx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxyzlpb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjfnzuz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpfvzsn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbifcnb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwkxmjr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbhrjuy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwjatvy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiknfql.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2duyggobj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoyptcg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2geowkrcw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2amsoojtz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwdqpxp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nutrfatc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqkyysq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjdzhg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvoety.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyndjti.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2voqeqwsv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjilfgz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zindsbuw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2youimbaq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kdikpayy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bkatkjtd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flurwmfq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtonib.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szzhxzzb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqjvqhq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnruzz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdldnog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfodbfu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnapcvaq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtffkggn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xytfiwyf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzwdvvs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbihxhxi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtfdlx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2guxxmkuf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2idnzehap.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqwshri.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtyqive.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrvnfrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kuufrevb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcbcmia.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebimfa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lblksdzb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dobrpcjc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cixygbap.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gchjkerk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2spmphyqp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hkolofuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrujhga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jepcfzdl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyikoya.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2himfeblg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxsgnww.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2igsspjrd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgzeyup.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cavtgjyl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmiciqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2enjwuqod.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgtgzh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2stihhytt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gidoslvg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ostxezlt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2briaeubh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfurmxr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tenfxksm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlmyzvi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcwcbfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqntfpbk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgvepzf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsmbxlw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxgygxv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckphvq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvryqsuy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsymoxac.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tshxgfcr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dtunwijk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgxxoqx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjiptex.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiymzohb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvxulmh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlhlgyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cizkzhhs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkwalxe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jolkyalu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2glzuhjsf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlltjijn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zbknbpns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alwjxmsq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jatlltzq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwmdgij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkqupvp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmjrqzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyvddlp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqazwkq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kchrkfcl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblhhpks.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cwazumli.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsakrjs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgucynnr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwwtrpa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ncljrqnj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzddhnoz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbsdav.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bowpcflu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhteudpt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpftqmo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsgcuze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsysgig.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqtthyt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yolzrqaj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaclqpx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwlcbyp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2knurmqev.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2veyzsjuo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swufmtbe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhorsqjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvdpoig.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcbadmu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mszhmjqa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlpdrdy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txzvynzq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjlukwd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uraaings.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2enokleeq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtebzzp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsdcqns.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtzegj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzehcom.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhogak.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqaanls.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2llmbocol.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrinfjou.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2shvbioaz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtwftu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmmdee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbczpsk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scinmrhk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxalmnml.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iticsejo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlamujg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnymkezs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2egkahbfm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgjgisa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2otjtswsq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfqjpwf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoekadq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ljehzzwb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2atbksuen.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brdplkza.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftihpexy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyydtbyl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuklfdab.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrlqjhl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdovxkfi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpcwgja.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qekemfsp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjecfjs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkpyvgw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhgvme.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fykiotwq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpwtomq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iauzuqtm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dopvdrlf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xedvbvbv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmxkytl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmboklr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdaiwoo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmpbebn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvjkhuc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpwysxz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oofjetos.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkbcltk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xarkxuho.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jobswevc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2myodeikd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgemavfj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjtwlx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lknroqgx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueptmxor.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkoquix.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkootgv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnuboyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbfoskd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2etxtujiz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcbnnyb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ishmsbtx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpovvwl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kowluekb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybufhoed.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlqofio.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqeqfcv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihutsohs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqbytke.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vddofzlq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2icyitwya.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbzwrcd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcnvuwz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2flqocqno.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lidtecta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwgyoel.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmtkegv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjdtrlp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfyskrk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqevat.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ragoadgu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwtivf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnuhrmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswjxcxe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqttuvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxifkau.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqypsaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlwhkea.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdeemmk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2itmuofte.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2skpxvrbp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjjzizi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqozgrh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeztbye.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2quvuqcpt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdaidsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzkaofa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuugivq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avtnbdde.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orbfrphi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcgqgvg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yivppkss.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xekxusbb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2opktgenm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwkjxcz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2efmutgqh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xndvrjri.html


<!-- 参考信息 -->