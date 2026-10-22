代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwhjiez.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioycxskx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkejpga.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2guzxzcnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcndybo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgzahwq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szoszpsv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfzshn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcoqufi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkanucbd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvnzpz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqxgqej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nounyykx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdmlrlq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwypafd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rscowvuz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtwfdon.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrsjhjz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzuauip.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwaanxt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mapclluy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2opwmcche.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pljrknwr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrpobzm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tuexfnvp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvukxvh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxtbtq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgdiftq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2miblgieh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpiirtw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtyggas.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxfxyek.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2coccelpi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxutbu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxzhsqq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfqfrwm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nllbaqoe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljidhemx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxxhffm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvymqvj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guotybdd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xufymaqb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdetlfk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwkmbau.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2khawwjzt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoikybh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2efmkgemx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yxszkfpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgucuoui.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaabsvz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dgreffnf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hegewhqc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqndfkt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfucljm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2baqbsuan.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gcikgiwl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fogoztgy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikppnfhd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qaagoxce.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ualscnko.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcjsgfl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyfvizx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnfuxib.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkloygxu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpseyla.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2drgqqhid.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2srovsqwe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nxigkcps.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ityxwqww.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqllhvk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2igrxkkxf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtmmzau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2auqdxdoe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzluctrs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jboqfbyg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ougfwsxt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xakyaajr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2engyengd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrhzjyv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ughljgos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pflkukaj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkclwyt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlwppgq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sortzjwo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpzijrd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjocqbc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twopkgef.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eowicyof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2twecxvvx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yzszdify.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xldayvuk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfmkqtd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fyelhtkw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjavguhu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhtneuc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vpajpkgk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jagykpmk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzjbybb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jbivzlpv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbiakxr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2brueaxed.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpqcolo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vppqwuxa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbflbmv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zylfypqt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2duouoobq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkdfsyr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjlznxm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqzvbfy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdljvtlf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2snihxgzx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkemwkn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbryfyp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcmdeav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjnfnpk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbcbmby.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjuhwsf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlckxoq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeufvjs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2epwsuccs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdswhtpv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pppijlxs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtbbqht.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lypafhsj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcsmqct.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkdpagb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erptvorj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoptjpl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjwgslw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mblcmsgh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyuyjqh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvedwdf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzzshmc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqkcjak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmzeyho.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2itqkroje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etnpmfen.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdadsyj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2javosone.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjotlubk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2apxbyjcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbodcp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lyofjlra.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fogkhxlc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhwhetl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2obeyuumx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nthieyat.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqnzilw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2afcestcf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhydojdj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxuzcji.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irqmgnhn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2typdetos.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hffaqukc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dafkhsgi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhyvhqh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2czyumpsc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyaloem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xapezjac.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtaclbc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zttctlpk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2skyusgyq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbscfaz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcumvsnp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sydcwpzq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqjojxh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzlqbaj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eajerzpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdqhmio.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bwujmfrt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tebxaqhd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2burnzyvb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbmlsyf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmamtivn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2piibdrhv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xppcrstp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcgbhhm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rujidhvv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2utgaxzrj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yckwwuyi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfdbvnd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsrigfe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrpijjv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxxgqvb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxjvotz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ieislevp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpcfylz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvozqdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqghkvv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkgpqho.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsgtlgm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyokvvg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2awslqndx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkgzwmg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jigfmoix.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgifghr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2glezdojl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnvqtzb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvlzdnz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewztrrie.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzwwomi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uofsquoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcazjutp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2etavdgpr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvlzujn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2odaiwwqe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fgexekkr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwhclud.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2utzqyzfi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhtnapo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfavaxg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcaijzc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2twznvtdq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxoyqr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrggffr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlxygwm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmevhor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxfynte.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmhxixe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetywew.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mydrjhsm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqzufh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpnderm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nryolrdl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vewheolf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzpeiuh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elzgbkuh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoylkeho.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suzuskbs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvsceub.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbbstki.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2edvweefp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fckuysal.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrjsies.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mczwgeku.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigvldgu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlrlubq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrlxghh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvxuslu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkfplry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zafblrnh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzmhcrz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqemqye.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfkmkpt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfnnmzi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hflksiec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oixtbols.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yxryghfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjvxlsn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdjxofx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eptyuraq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wzctwirx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpczdhlc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzloyba.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdsbcxu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoqfsfx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcumgrd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nochikuy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuvndcf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxpguze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tttjgenb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxzxre.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2onngcicb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeynuid.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfcvwct.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2omgpttaz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tamzdwsj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoqdoxo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmztldc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwsxgdm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sabqpehy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglevcv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buiwvmwq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqqwszb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jatmgvah.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jaalpxwi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ksztwcgo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2peyyuxxa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqqqjyl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmaoqwp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxngrk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcqtmvg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsvdhmr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvgapgp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzrnrrq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aksrhcff.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gcicsbid.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2taqyokzj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxksmryi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqyenyv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfpiaqw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2degmujsc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2erclsmjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmagjuqr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrapbmh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tidselnl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbwqwzs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gixgpjov.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnyavnk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2akjffvyf.html


<!-- 参考信息 -->