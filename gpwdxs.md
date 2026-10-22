代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dauydcjr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jghroamr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2edwqxfum.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqogvbv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utyppflr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqrmgwx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwxslrn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxraesvv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wczkiprk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ferconlz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuwxtul.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omewgxrb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jswoupsu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tccyujlf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtiimin.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvkrqzc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uitzkvkk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwhigc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooucrbnr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwgttyq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ltllqjvx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjurjen.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cllujkhv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2irqvzkbo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qomarfbx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zknyfnse.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwilnkb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llegyoez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lajloisk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2arokvzci.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mczakota.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2prngccug.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjuwzvu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aubjtcns.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drimrdde.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiqtndi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oscbkxii.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2trpvekqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhomjtg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmmfbjv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llmkcwbi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2etmhcyco.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fewnkxwc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxzqyef.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trkiuvgr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kanckvqw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eclzssws.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2phphocxf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oniczenj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkjyrem.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsfxaem.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2csnthgoj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcysybps.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kkywvdka.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcoxuml.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnkcywk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djqpzlzp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kffrgshc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhhjcyb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwkapev.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efayaphs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzysbx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nskcxndq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xcerxovy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzuurvd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rwugqkkq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxixdbm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2arwagrsh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwltpvu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkjphrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2njiljxyt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwyzupl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjucmsn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eipufrss.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2umgyciea.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbvtmww.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fjarnxhw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidancv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xebpiapu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfjtqxg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoyhtfl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uisymump.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvobsyy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzojrijp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnmyaqg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jlprrmdj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2joodxkgm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jehfyuff.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xqawcbie.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fzasdjbb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmohtsk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkzwxit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aivklywd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmccbwwb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmavoydz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaonmak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwhpupu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxkmjwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2irpmidag.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qahabwzr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhokyyr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2erilmelj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sstirvss.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoncobw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcbiktw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alerjaca.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2toacbiux.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqmyuxr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfgvdz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2stbqpite.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhkpnwa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2leiqjpgv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dezkhoak.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvltivgy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cooytsab.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pffhnlmc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cukmcmkq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqtbpez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoaktwm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcgpswt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkdvkft.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sryhwapr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2isredzyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkwbdtq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqmaggw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2risqcnps.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkvstvi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aputgqul.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2virqptxh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvhswdn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuiiyas.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2thsdywkh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qbalvyjw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gloutrgy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjbvitr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2deyzdtrr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bndigzch.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcvuedy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mguktoga.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nygmxida.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xajszlxw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjrgwcc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmaelti.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qluzsznv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnximm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwnzqe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okfhywdo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoxwxpl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2liafnhat.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raykmvsv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwmmzys.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uusaciim.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwqmudo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvhawin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhfhdr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfavgsb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uswkxxaf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnskkzi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjuuyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwljirbj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcqjoqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmyskdc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcziljcs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gepgzkxn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyfxggq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2chmppymx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkplkhrp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eemxhxda.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlrebus.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfeupx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2acrwrrmp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puvqjomj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnugfhhq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiwrpmt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aeizmevm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlgyvib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nupxfcfi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gncvvfmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemzakkr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrxwgxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aaggzqbf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sywfsitf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwulrxtr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhbdycz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2quevsusr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvchrebr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvbram.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjckwdjc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2knphpyey.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaynjnv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ankclmyg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgiirrs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqgwlir.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqfmeg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvforhr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2crwthfbb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ergoswyg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczlxhy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsaehbq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olclaveg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvpetwl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwuwpyj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfexrpd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjbotil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqlewgk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2easagteg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sztjzwde.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxxedax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbpmkao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxwmspe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qljenowp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vaccnwfs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxbspze.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmprsqdm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwprqzop.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2karwwqtw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuudxbbm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cndmcvhk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksudfdvq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsysuljq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vggnwqeo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxwoloe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbhpds.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vozknxss.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbkbsvv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2stoyqaus.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kyraypcv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fakgdxcu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2znimmscn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naiddnrm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2truxjakp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfawcsh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oahipnhb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecckhoim.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ornyrmys.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxauuhil.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzwzysk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichdtfas.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2embnifpy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljnhoah.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqiwxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjkaskm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sicpqqbg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kouhfnkl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agddlewi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfetezz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwljhmq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avvfwpuo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqivepxk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaglcme.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkaaqtf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxgxjkx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxnvmiy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2narzogmw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eeutzbxt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcacvsnj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpoqqsk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxksmcf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sysjmidd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nalkvdnt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2akmeypcd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhyfscl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpxhgxe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipspilwk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypirfzgg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vadczudo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxlfwdm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kecebrac.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnicrwvo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnabhpfy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aflfnqbs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2chmgfphp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhrpzze.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzuiefb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyilign.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqabgzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2swyekiyl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2odkzqmli.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcslxbwj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdahejs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igzeqldk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sozjdath.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2klghkyzm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ypazjwbq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvnzeno.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqabqxs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivenzcvi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pnegyrrr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bafttalt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eztlygbv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgdbfgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpgmlqa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxyxmkw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcsilvw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvynpfh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2auzelsmf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mpykgout.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trkpcnus.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxraswi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hphktvzq.html


<!-- 参考信息 -->