代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeqtwgu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msdxtbpa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvxwobz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elrwkxje.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebchgx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gprcdghs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2enrnsxqa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbukvgkb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnolfugl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgkkpry.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thmbkrrz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfekdtue.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtcaaes.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdswwvdu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvfyzhf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeuqrqs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgehrev.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2expblyqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcxwgqj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svyebdpe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoiaqfj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkuttji.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmxoezf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snurrowj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pausnddb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xygpdcgj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjkfmdz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pccziafe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxfini.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgclus.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aezucftq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzhutpd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vakvsxys.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iofcbtqr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzpnoka.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaimstr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yoibdvmv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhughzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnfnlgo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaycalk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqunlarp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2chifqrxf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxmnnxd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2arxtiydh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2drsbpdhq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2prkbrqvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2brtmydtd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkfugmx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpxznaq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dybmfmly.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fofazdkf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwblsgyd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2polrxaog.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cixpmzmz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hwooiatq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2isjgkvlq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlxztr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkrqfqt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tetuvdih.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zytqlkki.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfoihai.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fipuarwv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oturmlvi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcwbvtx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2erzidygl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvzmtbc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnfkfub.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iexfdnxg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pokfwbmb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpdvpsq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzyfxhy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfmwvng.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwftepj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrepusg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qegjdfnp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqzsdhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2osfbgoqk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bbosrljd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhgeqnj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdovqhh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2upguhssg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbszxrae.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pajmbszo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpviwgj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fsniozbj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdgdlto.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtolvhln.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmfqqmr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uykaduqf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmtbeln.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkqoure.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nwskwhei.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsuymgl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjpyplr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kcktqiua.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2azgwqvnr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lffjeumx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qozyynac.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rmutjkzd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2incjvfbq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfmdesn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iflrhacy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnszayf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqzgqhz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqfhpdg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2brtmfbwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihaixsb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2razuguln.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwrssaw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hslgqske.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2howphjpm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2plahiexz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2odxthidl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gutehbyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snkxllzv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwdxcex.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uottrjlz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtmmcne.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jgumeepf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaldjfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpccxty.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gansfets.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qeokzpjz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fymqkuvo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jijbumqz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2irrygkhh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxszkpm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzkrwil.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdccepe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfbfwvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zujtyuyn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkrctoc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsfqtok.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmiliic.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkbegq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oxavutve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmwrebk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ehabemef.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rfazzkbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxaadis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnabawp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kivvpnqu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byncsxaj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzjrcxe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufooqevl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oouwmphk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rilpinxr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aznhhdst.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuajpjfa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eulwiprz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oywirllc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkgdsks.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxhkcul.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmckefc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmcptih.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxuxozd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2atckfoyp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksgyfx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjieqzf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsvwtll.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ariixqvn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtfwvyk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdhydpf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfymcjk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzzdbim.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsblrwsi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxqgrob.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvtbqer.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dminxsos.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2reupwzeq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrbksia.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atowzcbl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqprhsj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2spbwzlpt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvchlhr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aaamxjmo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoenbbd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szjbztrb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmbygko.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyyzyuy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpdzcal.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dykshbdv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmsyrk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlwktna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxcneom.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgizwfn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqtezbd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qbphgebk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrebtfj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpontkh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2buuucqsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdgfhjt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zycilfja.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eygprlkd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmorgxte.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2omnuuzkx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjujxfk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bovkmaxt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkcelhz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2entuhwoh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvujkif.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jympvujq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpblegc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnrthef.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xwukzmkr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgalirg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2acveqtbf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amvovwfy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ctylmatu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmkzziu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmfoej.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqtuoqa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetatnh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsmocov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgcskzw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcvdslj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoykczn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjpivxc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjiglvp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmjpfx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2irbtauva.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iytlkmcx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cnooxhpa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpchaza.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfbcdbl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yacidrjj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlhxpzx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqicjod.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttmjrd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsxdziy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylidndsg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iajxpgdd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hiksxfxk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mikhqoei.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlhknn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfkvafh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyzdxqc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svjjdoal.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpakpbb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euojeiah.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmlzwex.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfwxbad.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xacuihfg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2noeegwbq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzsuwux.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urgfyonj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuakehf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zezrwjel.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnctetd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qugokzgy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2druuwdiz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnlnncz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uddezodd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbdkpus.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqlpndc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2snsmrvfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdujdyf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ziismkfw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2piiboqji.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fettxjqq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kckgbqvg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcxsdto.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxujhj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2csoekofw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgytdfi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzcfoyt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqkddyf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sogzjomh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhyqvmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqubqygq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdemlvoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmqirrb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvapzhey.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibggumlo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prkzuxhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2svawuurj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xleedsvb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2blpbrwcc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlhdvgs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vuobfpkv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2esqxszat.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2npkhjxau.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiuagnm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jojfdupv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nihuumik.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetzpshf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2otsdgyfm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gavtrqeo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnirkfaj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xatdlgdc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afivayge.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hridoknh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2thefawct.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljmthbo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfztxqe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatnyvsq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2avvhhqif.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfcbale.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pssqobao.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyspfyb.html


<!-- 参考信息 -->