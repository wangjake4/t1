代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnipjwb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cckfsaoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvfcmef.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcdacub.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iuigpvvu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzworgkz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cizsszmr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgsfucj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pttbqoii.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnudzvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjbpgnu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpyawfk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehccjbbg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2htulgthd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuqkiwc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uksqywtr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdckib.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmyokpp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfcgyr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lokxqooz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjlyilq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xssbmktw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnpxihk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjibkub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2youwhhcp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azibwmyj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ectyiwhs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aagoyitp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmticroh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2krjygjuo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rttsixds.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suktdrgd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rigchmzn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2klzwrwfc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzgrazm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udjvogde.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmqamxi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqnkwqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirbfmoo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjlgqja.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpuigf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzcryjc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhijdkn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2atyazufy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eingnnmo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbykanw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2epawwiny.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodsnci.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzjrdrd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgtltnd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qhagfyhw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uemdezhh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uubiqrke.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjvdxra.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmuepir.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvvhrad.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvsytxk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qfspoday.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blcklquk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmdheaa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkjndvf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgybeeh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzztzgi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpgutsx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzkcpyd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2segrfbrg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwpsbwa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyyzzdc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nncxhvpd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2atulbnyt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxntjygs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wehixtjy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2awyabivx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yexcaill.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmowtggd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqcaibz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gscpmxbn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyczgjee.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nasccwkg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpksjav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvucolf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzgyzzy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eypjcxzr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjfamys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2svtyeano.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zuznaena.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bficwxnh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2liujytou.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaiugja.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jijdqhub.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmoskat.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxtsgza.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bnawleox.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uobcswom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twynhrya.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvflcwp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iwncblsu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiduhav.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtxorok.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpzcnpu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2veatptux.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvavygb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eddzqmcj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bholbhhi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqizci.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2trjdibyb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wpefebro.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bagxpbbn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhwjwqz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeohxkp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htaprkwc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmquwcba.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpzlllr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvxttws.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqqxesj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zsloieuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqaricn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcendkt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qndcebnw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knjxpzsd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2otppxukv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtdadla.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aarruxxg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lblhwbqt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcsyzou.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpnilxb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsechcv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgkcegz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2txyhllgm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tufanzdb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpnaxtx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqabbt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rubzedmb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcicfec.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tuayqims.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuyugww.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpnoqlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qufgtjjb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyruqsh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwstqfwf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrvnwkm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrgnime.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeefueb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmclseq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjdzzps.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdbixew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyxkzsn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkdnzl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbhwfhg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afalmfji.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwlllvu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkxfzbl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsdffge.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bvclndls.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xazqymvr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhcmhef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2abypfrcm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwntfdbo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedrqobb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqcprxw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eunisszj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpizljx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxmmhvx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzecdcbs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mibcvfbp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuieqjb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvglka.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rwudolux.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2navokooo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aynczefm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqgwlqn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdcuity.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhtebvs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epbxmcoe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2udgzjfop.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhakslwh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkzlwuu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2htzclkpq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cevorlla.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kraqjepn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2euuhfvtb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2npvhtnvm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmkclpk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wogimcig.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkcjukr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrinvfvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvggcha.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yixuopmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pytgaoxv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wyamxhie.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyjgmya.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfqwoeu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwncfone.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2epciepnq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjtwqil.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyowzai.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywoovpe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdghiyjs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2htusnptx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgmiifv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuviwwf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2csbdkyvz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2haljxglt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvjgvm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrpbzne.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnfndju.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smidjrvu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqdwjhs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zufuoyzf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsdbddz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2brnjdmjb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxcxvpj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vlixwlvs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwrmbyi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmtlvnm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffburizn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjhhvag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidvhad.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csizbfax.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzgjobm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jysjaqve.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvyimb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcdutla.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrypwtv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igccxyyo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psypaqiw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvnejtq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhpakdv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2shlvuxjt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjwalwm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkseedu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcaifpp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrejeyo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2neuchqco.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsymkwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcukwomx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aviuojmt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpfjeib.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxwblg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbkdtn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzyrnji.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgumjnt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oledjibf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrnkafk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vijanbzh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gytwkmnj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrqiooh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2livnzurx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzamgkmz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dvugzibt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fncnvcgt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdudmqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kskgpegi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfybamn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chrrvqop.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zbahniyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgvncch.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jemsiutp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaxgeex.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqkwugh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lghimiao.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xitefmwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjswkvz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtzfvwe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qluioopg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ognhdxqh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rujoambw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhjzddn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srmvdloq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2inxdodet.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtrgrbb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmbvdme.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtqxzun.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfkhan.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vzylyidq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2caalurfs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyomnbv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkewsg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2smpkbikt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzktizmk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmgdgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vamlyqnp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtilsph.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbircib.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwlwvb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gffcylas.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmasoqx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtaclzm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiusqlx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtusoxto.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2srfdpmtf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpxgmvr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2swthlpix.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uagunnvr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcjigos.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vklpkfeb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2htmnlmbd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvgboxb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaamxsze.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfjvcuo.html


<!-- 参考信息 -->