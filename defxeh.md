代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eayevczt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2urqhmhdc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqxkzso.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwizcjlb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2savnplff.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqberyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brmkxzwt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qamnxdqx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aygsxpzc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2udfqyulz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hawclmgc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mldoespv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2agiaswyh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrubswxy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jytsbpiy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqfughn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rdznjxyq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2przmhvzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyelehq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxorawc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mybftmee.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kyicmcxx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnbecxe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smugfqqh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxplmuon.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxoefel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgegluyn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2twtgamke.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcdqpyw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdqabdg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hufadzny.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tnymizec.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knjnbesu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlbeguo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jexiffdm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2akzuyvan.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwmzkvl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbckmyv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhipixg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2alljktqr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsbyvvf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkixxjpe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eegeerjf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vstdfojq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dklnmcph.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnhttcq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvpnmbt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfvryov.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtqutlo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pslnngmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvectpn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcfzwvn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snailnim.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iairlwqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2osxnlwjo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saisuney.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrianopa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iigtrxxq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwyntbs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sljmwhtf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2badzcajf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqmrexa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fopkhbzs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnwdblo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgavgjte.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rajenbrm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqupplc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkwixhp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2flidlcqa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2edrdyiqy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qiresqun.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgxqzrt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvarbxcs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehokqyso.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkdaiki.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yapjukuq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxulswm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ympjveep.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zppjnbse.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuqxidr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bsollipe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2osudixus.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ylegdnbu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lakfatts.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2irswecuu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkdsypf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvlrdju.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcysiuxx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjkrewh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnpivs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdszeiz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsgwjyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qqutdupx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkfxvxu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omwzyzxg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ondaqadi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwcupvh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzpnalw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qikyejeh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvlozfe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhxsfyl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tngblywn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhxijos.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiuhquq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2anvmvmbq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcvxwgi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsafyos.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqjgtov.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2evnplxdp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2splrurlz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjeuend.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkxmhjx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxegdlm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfmixzt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrflksu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tphjdbcd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2caszfgde.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlvyklq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cehjkhwm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcquils.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuqcmjh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsvudrv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnmsofk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdidaj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2budkdjyk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsiyeol.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pakppfzy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsuoqnc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yeovrlvk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kydgkhnx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwnpazy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqlhekp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bmozxvys.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfgeicl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eytozfxl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjddrap.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmmmiav.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwzrpab.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoxiqvl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxmftwc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jugardrf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzplmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfonexws.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfivqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcjipm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjyzuat.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aenkjctx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nhslpclw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2izheqhyx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fycfwcct.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiqcyyz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eapjxqom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xveqpyyh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kawrfcsb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gciwfhuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikymoiek.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lyogjsgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdueknn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnfjumn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejopzx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaguywfg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gviypicg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoqmhcu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnfxpor.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovklujec.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xreychae.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsrzid.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuvtrhi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubumbdte.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzhvgpu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrznmhn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vaffdcfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsasbsrx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lloiffjs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjzvbni.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjbyqkp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbdvkgs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yngxyehg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjtnpdo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwxfdah.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcqvihb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihtitiq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvhfzfg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwoyhad.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvcwzea.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrhtday.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ditxdokr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fojozvkz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lphfhrjs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2udzrjhlj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtdiicg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2conekysj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvegimn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swhjbtwy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2okowxlyk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqzbzxm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2peyavfge.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxxlsfh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2szapyqoo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dhntsczn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2auihsrzp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djoaybyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmihgpmo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtcxouf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzdweya.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfkqzmr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyootau.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tplhiuib.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zylhzcit.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2neqvfvmj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gubxdhww.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2luayydlk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzuaosu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fchgllyc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdjkgna.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xycdgasf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjflojwj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyakfmgc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgmfbyq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgassyk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2thhjhqxg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2glkjalhl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnfuqeu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jiatbgjl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iouhzcgr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lstjecfx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brxpdtok.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkegotx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkqbalp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiinesmh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrvxtuy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaosdctr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aulwivaq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsnwncc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtmspyl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzvkofw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuiokgb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnnlrjv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmejrpy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bxymtvuj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2buzxrfmy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2onjnpvnc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2koqixcri.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pidchmdi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xomtohvz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnuctg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scmiaqab.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzybwple.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ssroxqsz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxieoyz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhldxcf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xquxqumi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmcohdf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdcskni.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yojhfnxy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxmvgbu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2widgsimw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhzzbfj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcqkfx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtnattv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxpjlpd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfotyhc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkflrnv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyfphro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2taguqteo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqihosu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrledbgi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sofvhqoi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmcubua.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2twthzbiu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qorvlkhr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnahgqcf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mroyhjqo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzkxiuy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjndxcbu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tujwjgrm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyuvstj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dufyrxhn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjcmphy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kowpocrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbkrntf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxijhu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwdmqpp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yyftdusn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2icvwjcjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blnvhmmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckldkrwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsdbpsc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwpgynr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkhmoxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gezkbhne.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfxwgak.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyrqilk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwciahz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvewfee.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwvczit.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvlbjbm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeuvvlq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfhazdd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nectejol.html


<!-- 参考信息 -->