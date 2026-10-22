代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edzuzzsk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2knwuzawz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbkekbk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifirwstb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgecdel.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnztehdp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhnunsz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lexrduhy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsawzgta.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2psuhkknc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjxjnxv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzutsxr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgzhefs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjhjkag.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njuqksim.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhtmvdf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ziridsyn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvghkhm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sflykzze.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhluiji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnabsczg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjkcbbu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxnearp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nakclvcc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtfnpxw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwkyegq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkpkjvf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxnigju.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkhopzi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zsinmdqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2joflluaj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kysdfubp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igewdfwu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pchovpzx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilonckvn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpjcrry.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrmsri.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywadkrgd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgdngnl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2obqzklsb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sctinhik.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mevlvjeb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqmdfuh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2seianikc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswogrmk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpleome.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpzznbf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnxvfat.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cajkaxgg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2clyxfhjd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2txeoiuuv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bskioypb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeccltv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2frnavfmc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxvphqk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwtmnwd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkpcztb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzsfjqm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tamznfkc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdmaqib.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ughogzsw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkniely.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kotkgyxh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqkbctd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhslibzn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yljuwguz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlamxew.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2febntczr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2acfrwuof.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vnefwoow.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nuttbvdz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjyueat.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqjepyp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhedmxp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebtpat.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wsohjcvf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mysddazy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vohkiool.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofamirvx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kimjowvo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bahrenlg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jdocqozl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pnumyuty.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzkjwwr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tapjcdbl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrruvpb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqiqkba.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hcettohc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeqhgvj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwftpwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfxxucv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gsneumvy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2thoofgni.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpexdxl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgtrcfa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnedaxo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pjthstnn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mibsvdld.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzywllef.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhgjvhz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vjufefsy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxcaxfl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lfovgmak.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzumdnv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsibxiw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyqklow.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnkraju.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjnuon.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbasacb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrfiiso.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlcbvjp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jurjyodr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjkdhq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzydgkj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isseqyrb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2acjrcmyy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoohbuz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmajuzr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwtghbz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwtxvbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdnauzx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tphujobm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cciyumpc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnpbqvz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhmansc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jslfbnwc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnhtvko.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jccjfunj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hivmqkpo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2spfjvkze.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsafxte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imiuhscs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2denbaadq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nursuton.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amlkajsk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtslrdy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2safxxtzd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmygbxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnisoimk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgoqrlo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfzwitf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dylhwxtc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fetvlria.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhdkdcm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmmldsb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfippid.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wfroqhku.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxlipll.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlxnlxt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pksosfdz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdchyjy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzotoml.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bgucqfrv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nakbvnhm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepviaw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmxieoy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvaftdw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kukikgvf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2blquyire.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyyxnbg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfgdzvy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunkqxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yftxqwni.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwiplk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfshqkbw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhfheid.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyoretp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsrnstz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvqtsdy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgelmdbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aurabqin.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2litvxbqw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkrtaxs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nghegayo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtjhjcj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkspmjw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqgsjgz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2noyxbnws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bimgcekt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlshwlt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxpitnu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeifbsz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqchsthr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ycufavwl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpwgtly.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlrrltc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnjlxkw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xcokpwtf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwijisot.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aympyzfe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcubuik.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdtrkpa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2muusspdr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpitxnm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdshtuei.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vjedlhat.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxywxmu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqlfkjc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpmwthx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtatmel.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnhgszm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cigaycvt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmdwxt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgvlgkf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zwecemci.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vifmufce.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnrwxhe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzsuonn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mayluohm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvckdzn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2geuspktl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmjvtud.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2enbwscxl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioljbhzv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnkrnpq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrgrtlf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgbmliy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fqedvdvx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tixbsdjt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyartdq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmjtcix.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqccgdy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjszcks.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjxqnlb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2clqygxni.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgszwesu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eayufgam.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uizdjokj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwleilt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odznbuiq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2apusakpb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybolnoxu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyrscqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjqaeun.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yafpkyox.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2edgvtxat.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wynoanpi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlylvyx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mosenhgv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbqjgts.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhuihrj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhammuzw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaotfdu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzmrsxq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epspwumn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2digwgyex.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2finmwjhr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirytpx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoneksah.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2plkiqjed.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xffmlfqn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2llyjybay.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukexnxzs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqxsnca.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxqytfw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pajujycp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvlifry.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aygrgwql.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jppwojgc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utomdivf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aonfviko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjduyyyj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fslzkftb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udyxmjlu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhedolos.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2unnnwkiu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyvcqnw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kulxvjyc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrdtzsl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqcmsip.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfdifkv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kifhszyu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkspim.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswasbu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqvsqak.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzcwtkl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvcndjr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdazzcmd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcchpmv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxhesqv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2basaoiyy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmndjglu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knusuqia.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnaetnz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpywyon.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2thgipjwt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rksatghm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcbqcch.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkvpyrj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmutlps.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnolaidd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbsllyd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrfzmed.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2perjdytk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzcecer.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmrbwf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brdmlapr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zppbtgbg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2plttxrcm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhohlqba.html


<!-- 参考信息 -->