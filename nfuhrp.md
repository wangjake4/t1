代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpixta.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdlwwpw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2igysjdaz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2upbygrbq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxxrrph.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pweevebf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnvutyv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdtyhlq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhbtkhh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrutahuv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jojpxfls.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srmgimpp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfytngix.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxhcueb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yenaamhq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvxvzpj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdijpiu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aimgpfqf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcavfpqq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfrbfxd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsxucsw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usphpfyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvairpk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyzevji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fuystjpg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlpovwn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gztlffoq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwlrqga.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyylhfrb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkintrt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alebkgwa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmofgng.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxocxqo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqimebo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjhfywj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiwxien.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnxmrfl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfzzxqn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrxyyjp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmqcfdn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oylpdvlo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjgbgn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htulnabo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwlmvzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wincjfmd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tepziodk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoehmpc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qgedrbkq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvutami.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvhscz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oggflwja.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqzxgx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dirvzmxf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zldbbkpg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ntosgsiw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psifwsjp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuwwiej.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqysfik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwrhhxc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrumgog.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiipbfl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tksvlqfk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjysuho.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfukojs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdwssel.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbbzeqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjapbjk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvfceod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjnjezq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvbftfz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeiqtpd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quncsxyy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imivaipk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jevyhyez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2exazcegx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrmxtqw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hutwyuor.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwfhufo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhylqsxo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjlzbsc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfljgvgf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nffbjuti.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lozbjjdh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlpllss.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2giowwqgg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2miycdfvg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wxythzql.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2coyjinfr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eurekmow.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuzpcye.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2schllrks.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxjbdbs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jufvhhia.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkskdhf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaissaq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnxhuex.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vxacxchg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfbaadl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbkzsnj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zczlqczs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgtvuos.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucamwmtn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qaksldfx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdxstyh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uekyluxr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgavbsg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvacjaeo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcejmpn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rgykcqhf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxhgsnf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcvqnlz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsiloxz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwgjbcx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoohspvf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcxaijj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2adqgvaas.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2phpmahqi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxyylb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gloneftb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpebpxg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnqgfwj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzbinlz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qptaufuu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsbrzcy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wofmjgkh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfhiroa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgydwiok.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbkovpp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgawgpr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjvcooj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiplojx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnfsdqr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaubgvp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2crdseizu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpdtprk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmihdneq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgticun.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjmtqa.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2szpzldxk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tecwfdol.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdatcpzd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxdhvll.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awvyrkcg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lopsezsb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqryumj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzopmgk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azmyinff.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwijccv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2quuukpou.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buotntdo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjreolb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxesybq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfhmxqj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2obffhesk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzslguge.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqcklkg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzztssqs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmwmxb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2owcfqqzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zndywbiu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2asuvttzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haxlmfcq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hykhgjof.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmjflht.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnulhwzu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyvghls.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwqjwdt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgoqgek.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmuykt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrvosbt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2itfrtwyo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtmhtdz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnilalng.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2altphfkf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfoqmzr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tismtdyy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zudmzmbn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2suustdyr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uypjfcqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iapjxppf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcmrrfc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmrkovh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhycixf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrisimga.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlyktxk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aztecuzs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aawsuncj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsjgsmc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2olyftsqn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2phtsqdwg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwkovxn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbuiwki.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotpxwf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmrvte.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2khcctmfc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdpvfwl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqidkvm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfaijit.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhplhjhr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzgqjhu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygensyjw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnrmvzx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpwhxko.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xytetykb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2imewhagl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzskflf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvbehfp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zgytcfki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbjfopd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnqgadu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnxuiyv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmeseun.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2migywvwf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilchwa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxsxeyb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmgdzic.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2skxoinjp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2enlrgeye.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egzerjrk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvelwvt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2keiihvuc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdavxze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wogwwlhl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kptuxdfj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2upmezshn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jcelaqnc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jsabxzdo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vozgdgcz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xycwdtxx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvitfept.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmptzam.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjtntyr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsfjjfo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huauuvcx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2enweeqsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjyqprt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbpwbft.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznksgcw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlkgdus.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gejoians.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2urpbmprq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvrgqiz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkhscm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kqysokrs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbtaskj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sciwnwbw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tdycglyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjefwp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inpnysvt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iruiymqb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjyzqxd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwfpbzj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdysgvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvubjqjy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iliivliy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrtepdl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiiokkz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcoiwed.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wieulhaq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvccod.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qawsmnfg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yckxdrvt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paqlsnkz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmjdgpv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbufhyaq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jprcqfpq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzmlumx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkplcrsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mipmcfpu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyekgxc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2phcixlzf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhxjmpr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfqyfsr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nljosxvt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2whsvrwwd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qunhyvtw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlkixwz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rfesihup.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2afrrrgby.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2azqcxjbq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmrmjsm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbymnbqm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaujgew.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlpsgfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyquttdh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tpatnaaa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxibimfq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dfykmoko.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2finpbfga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwidqgjn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhqankk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcivgcez.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prkohibb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrvxgzh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbgiiks.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkunexq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbykdumf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2daypplfk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgverht.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwdueug.html


<!-- 参考信息 -->