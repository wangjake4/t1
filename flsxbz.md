代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsgzwje.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ahplpecc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngrverm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syzvojxt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cdisydmt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2clbmgyta.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuoyexf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzxbrcb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oerxufhh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tedguoha.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eppnxocq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xrblighg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyrtiax.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbtwkzf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvmkyji.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbqnfhe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbzfwtf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnkvjev.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjajyrr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gttnhjwv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hblketzp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kreovlcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlutwwsh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svnawzml.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dugvyrrw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2luwbewrv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjwvfsl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwjrarv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thaiorfr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtpgfmf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbtlhlb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgyjksl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yebpfsbj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyczosr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2faysomye.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzxjaja.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzioptym.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbjyesb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldneewkq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akkzuqxx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icpluxwm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhkdqsn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbbgxdz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qicfkgwa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgcortv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxbojlt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhldvxs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bmluwzcg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfivipqi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2umeapeld.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjobjde.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unvjcbto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbggyzt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kawpbwjf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwaviak.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcpbbaj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqybsjui.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbsyrbq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqqhzbo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nernekai.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdltfb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhqvtgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaxkmto.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcxdswz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2aueqmcns.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rczbpyut.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hntkstty.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhbwtyv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbxowkn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2edizkytd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpazmiq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tiajrtyf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgouanyz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkmctxv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkvnbyx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2islbwvpd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pithzncl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvysls.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eynkivlz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvnoxby.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtguxos.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzblmzq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2clpctgxr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tslxkxjs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrshvmz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sompwuro.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2exldcadj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsuolsu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfrybai.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2algngkva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htqfsqbc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfuwfxt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxdons.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzyeapl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmooltmu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyvoiry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfxvomc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2azkdgjvb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aiirhuvk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwgmhxh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfjwfgz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzwxdm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqtkeyx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkbmbo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2spxjcaqi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuswqpr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qasnovvf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oaecdnib.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgtqdq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgtnamf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rshrgrij.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mcliyqft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iuorqitg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyylhdwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ipapjyzk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhuoluc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqhrvbz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvmtahm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmghbyas.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyvqcjy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmyijod.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpuqfrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwnhovv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqhlzkm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtuwxtp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2devmhmnn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2msraenwn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilitkrmm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhatyfa.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aitaatqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjntplx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpujbmr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2elkfxjlv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgeyehq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lrstkkqc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2onugaysa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfnhpsp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkhckxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvssqejw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzskfyk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklkpqx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fivklndw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqmrihy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kffudazq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgktaqdv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2medifcui.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2curcilyn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjginxx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtttcdz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxgggpp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlegcjx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2irnqwhfe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ariyxena.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiinscu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bqralykk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuzlils.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlcriys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzpupq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqelvpi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2enapiser.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbiuiyw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwlapbp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdkvfze.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwnwyao.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kauizywr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkdtfin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2czlobupv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhwgrw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeejgyq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxjpzri.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uwliqfjt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nafscwwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2furbgejz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyphtii.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2exeojryy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sakfsvpj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qljrbuhj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qlujokeo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2usawpizy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzuvcdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmkkiss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohrtaof.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcrgqnx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuhwgfh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpmpqxq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2prypnslf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rysylrvt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vceucynz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmkdozd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2urylmjmo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2reupedxx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqpdzdp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtkviws.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvniopmd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcwbhee.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltflwdle.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpompnwn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwiqwbu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjkrfcj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gwziiaxu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2celbyawv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxcwtoa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dglllbwc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlwjjbk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vchwlrdr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2illvxptg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yferyqnx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxicrmmp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuejehi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhgwfor.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdqylec.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmftlhq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfzxsky.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ribgihxs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2errpcueb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wquwkvng.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpxacie.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yovzjkxk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dubcgajx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcffruc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxlytxr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uasqoozd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrxlyfp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utulyphf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hterkgnu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmbxcxi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdvtdye.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzmckjv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cjejasih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqemttn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgzrwti.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwnuebh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkxhzrs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lztcrgnb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iffblqtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bplazwbh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xxduevkw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecutdntb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zumuftyc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjgavsy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzyauqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmpwdjs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bykkomod.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2swtugwep.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yskjxiiv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjolxpdh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggevgcra.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdafbvky.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2brlqtblh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiqvtce.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2idxcfgbo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzvnroo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cedhypzt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcvvina.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sifazafq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwyknjl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqonegq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvdopma.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmckwsgp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2riwoeaqi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izbgbbxm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjyfkka.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imaejmxr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmkzmnr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoezegt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2arjxefki.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpwulww.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlvkaxx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vggkozox.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfosaxlu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptncsxcp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkapebs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2twcpiqzl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xktoyqkj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pipodcun.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyymbbw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkqblxv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2flqlmsxg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtihziia.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lamclmbf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaholpu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2levwghdd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmkxaul.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxkjkxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxiltjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twvsmwfr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnujtbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bouogkij.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzbjbq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkhesyx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnypmde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnqxgul.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2phyxzdcx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xanvajdi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2entlxpic.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbweuigr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zunyyoof.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvytrea.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zojgvgkl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcwsskm.html


<!-- 参考信息 -->