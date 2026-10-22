代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiwedls.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoyjbkq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2akrhujex.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpabbahp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lxismlji.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjylosc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmtchug.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcasndm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupdpki.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2enhpgrce.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfhrjdp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iezbpgvl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2punyboxs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvruyqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcztvyr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwkhzpv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeqtxri.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vreuekuj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pakxvjyu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiivxwr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowalos.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhfnmyo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2koduvoyg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkfljgk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xddtoztr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyixbkm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aypkokys.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uowulavd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsslzxg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtxcow.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfghira.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfodapm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzegxvf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiqmvfy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdbjbgf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfahjqwj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjfrqdm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igtikvji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edzcirkr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azktjrbm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btusvngh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cakpdyit.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emgvienj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2buyyvsmo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ektmryhg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqepfhhz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2saochxmi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuqkbnv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yujulpfq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcaseft.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnudbxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hoikpqag.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmtjudh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imgvcods.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2scbsbeou.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kggnmxhu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrvzxwr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2htdmuhav.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqokmey.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaxjrku.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azfovrtx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwrcsoj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lonqafgm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nabgltme.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxaofnu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wjluencm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ainvdoeb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wvikbbva.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wokfcgip.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgotmdq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2peystkht.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgyytrp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2twfzyhim.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjibwhii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbvbdby.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qotokfsn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgezcsxh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwjhpns.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfbxtwe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2phgzqxfh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rflixxlp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzkjqja.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdmiddw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqimced.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhujlxly.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yliegbdf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opdymxlm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmyrmli.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpsonmr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2djbevetc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lscvhnrj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzobvvb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sfikwakd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhycxtxn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhqilcx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kduntbow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmmhyls.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mghrfrpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpojmvh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twxmkuwb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvszohz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnuqnnm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrvhnxo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sumzagas.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhguoal.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2raoysmpx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbudgay.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbuewce.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbagtly.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtdaicq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxxqjc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zumflsjd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hedkdfdg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2glnwfgxy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvzevp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tccpxrvs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqlshid.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjwiqbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdqnwml.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ofejwmfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmcoevn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtguffj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtvyskv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvljmgtk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2upmmftwm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqpfwdv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbkjjwc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vejxuwmp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqbmhhf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkeppxz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvofqpme.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgxfbxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zvknpwui.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaeyzny.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwacfnr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxjbtlc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqmrcp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfjhzgg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvppzdc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbjkla.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2smhwrkfl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gudycrff.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzyibvm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxkuwdg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2faefhzip.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2arjxvgzo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zsieibsp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpxkwmj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jokflyuv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zanspezp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhevtwyq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oroedcpf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxejubwt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juqtdgut.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcehxls.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcxhlvp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2muyvwvco.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2quxykfct.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2osvgkfnb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2beamkaly.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzjsofa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaystlm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mirtfzdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaxkhin.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpsjwdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scqqilaz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bklckcqt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvdkgpx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axdfftrz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hdypvjva.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgoqgif.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcijjew.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjtbox.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgjsfps.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxsyqb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwthtot.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypxszoc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syxewknx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpfswmx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnucfwh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cotgkekw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmcbsdl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbszdfs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktospaqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ontojopn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxsgujt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdfavv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcwynil.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zisygcrc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgmncxk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzkedia.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpclewez.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnlbwxz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hocacsdc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2enzxskph.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrzbdmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nydhiwqw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2behdkrfk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyiphcv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwqrfbs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqaigku.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brmnxobz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfywxwl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkezvja.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrcivlr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grfhhsik.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjksawvm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uryvbgkp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uheadwfp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pejnebiw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtdbfi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eksuehkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nslxeyzt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuqxhnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yelruwhz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiqsrvo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mexdrijl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fiedyzas.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oveevfsm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2duzquvqs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lryfmzqc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbynopq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jubsjlxx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opifgahh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaenvdl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzgfibk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvziovq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrxtnjd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2awphtdph.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhdjlyc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2togmbxvw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhezlnra.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtvrpwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sckuxyzg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epbyxtfq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjxvrpe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcbbgll.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwqjksh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsqpoez.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdkcjjs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oeprwqjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2peaeowas.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2actenrui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyprgfx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtgcyfv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emeujjwf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlbzxxn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsxxbws.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nearhdqc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2omalssvp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqqvyfc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdemwuqy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeithrim.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufemwzit.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdgvfgr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xibotvhs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnolted.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zorigxpy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zgubdzcs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvanmj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwvosuk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrofyuvz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ryibjkqv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xksjqray.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drcwerxz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqjfqzn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psuykvbd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjaakso.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjserziq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpikeela.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsuftcx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxothxvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdqezha.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngipbsdv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2imyusmzv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bbarsuie.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecearqml.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcuhaqy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkguzgt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wwegrybs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxjpfb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmdzkes.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwvysjo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmbgkey.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiyfbqn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjarnvfo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgfdwib.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkgmrk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpgfdly.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shmxjzuz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iltqagbp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2auapgwba.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gybujxev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsnxjho.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsabpza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkoghtu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnqujff.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaeklss.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrbtlka.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgimdta.html


<!-- 参考信息 -->