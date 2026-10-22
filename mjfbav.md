代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gudvlzmk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvfjwhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dljeawrw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2receokrv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drecwagg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxrgqym.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ienohtsf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwwigsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rscvsobu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdpunzq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxyxvvz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fybfybjb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hivnekfr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyyxffw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpwvccq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxvmdzw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cavgmbdy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fretjmpv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2poixqmph.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfdyzod.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiwifyg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvaabb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfqltkr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxoolss.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqzeqkt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzjwtwq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shkszmlh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuavhll.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dedbuizu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnyudof.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwagfw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxwwpia.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbebena.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zclmrgxm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nxacszek.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unulpnqa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzurhis.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvozzv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwygzhxj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2owcnkgey.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjosjfsh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkemwyzv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqhwzst.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpngreea.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodrsol.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpubhcc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmfryea.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jeencqdi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqwriyc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfypybx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfauoor.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xclhkwxz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzddiwob.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2niolteks.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2leedhvql.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwyviza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuulowr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbekmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxqzkog.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neirlalt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfvubjl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvzxvjr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcbtdbo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhbhdwg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmzuwca.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlpaqjf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jshcdads.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xycztevl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bycpivzw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhccwj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2odesbple.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obxiwcjo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohltrke.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jshhfmpf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2clkyjzsa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnvmopj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtrkyld.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqliayg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsezhpz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxvjzcm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjzquce.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlqzfps.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxaffdn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzetapj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2szkjlyie.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2amrahfif.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uegwbekf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsadltc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dftccwln.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqeerb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkaurrr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpydvaag.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoxfkpq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2djaznhro.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcswgfkj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfyoafa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xvytmcsf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2csxtayxn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crtqkctw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aexyldyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2thtaancl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuklyurh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmkdqan.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaltwxo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuxttwc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awetcnrh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoxbuqd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxzowxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywbmkg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkedwqq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzfpgeu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nhedppjr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgyrrxc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcatmoa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahwpqy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaotggb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrihskw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2esjoftiv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuxigvr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2akeqtwej.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ibffmosr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hduzasmw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fbidzbyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iplwsbtl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwhurlg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqkjzlm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzzzqpw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfpfhth.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kdotxdwy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zargarps.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2droqciug.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aagdnqpj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnxydhs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2afpbbkmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaynqzo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtwybjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwdgoda.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dursvlqm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ceedgayd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgqnajr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnzgaax.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yurycehk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrcarfh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpdssni.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2crmnmqpg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrxadmn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwyhqtv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyydzafd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lerhejxt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoedzqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yikwjdyn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2crrldhyu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvvbsfc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxwfigs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmzmooj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mccthclo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhydglh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjssdqf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhsyiry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gceowgtf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jsknqhpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxfbfmk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhkehml.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dguhulgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvxpeed.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdbmosu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sszkjknn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxtfdun.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsnzbpv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lipzuxbi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2byrjkxaw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2boeggrau.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2holkiwsy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecznoemx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ulehviwi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wexkyelm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrsrcoi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrfcuyi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2naeaedqw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bmilrpoa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqbbjib.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xghprmhi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlkqdtg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwuhoaj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2abwtxyif.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubagazxm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcavvqel.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dehazpuj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlleeurq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuqrexl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhtlmlo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2koqomhpr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxreijpc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gezlxzwy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2osnnbxpv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqkxqc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdophgp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyloiql.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lopxlout.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lomevqkd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2crnrvltk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxltzxf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjmffg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xznachhd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtefwdgl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2arexmmrx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hecmxyjx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkcrptu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoenshzk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tncsotrh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnrnzbf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bkprqgxc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlcpbha.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpfcmpc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkutddfn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdzoyg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dajmsttj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2snztjwuh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2avnhyuei.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swpriyaf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2godftxaz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tofscfbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpglbqj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmmhzlg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsdoxqi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2llarmkfi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2incwrqjm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxckklas.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sedypwxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzmuouw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnklvvfs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2scjtapmr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ydllotee.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjsldqm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpovhlt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbcvfan.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqhkuer.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2okuxifvz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2htqblgot.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sasgiygc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkvkuao.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuskzdq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2egrxduvl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsgpzkr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdbnhdj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yehznobj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbookqa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbpmfap.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foxshoks.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylybobkn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjxemuo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtjlpse.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiorzcy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuzcqxb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yhycvgvz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2schxoalj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ewveaeor.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2afnxvnfc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfcxdtk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knmvsklb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvgkowg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtupbwm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsoupua.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwojfnrp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrdxkco.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sswaqhlr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2htpdysmv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2keupipxf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpfnnpb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nepphffh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2grvmfrte.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeemruk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brclhtqt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhbltdt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwyhkox.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obbtqmzk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhusklp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaovgdj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhqzcwk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2memylory.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grpottrb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2llnxqtst.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgprtqmr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ncczgtvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwedcak.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ahctbfad.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpnpkir.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkjhqyu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rokczmfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdeqyg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2opebcmcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olxthgay.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gswwtgxd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yojgvgka.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjqidqm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kvstpkes.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fromtsmr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yobvwsml.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqlydon.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyehclcp.html


<!-- 参考信息 -->