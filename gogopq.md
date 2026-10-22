代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjnbmp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sotodmsl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrwmviu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsnlmst.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pldpgqkf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxasxdf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoooqkf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ushpmcrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2afpywsyn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2riycnaab.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkgqtun.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2astrooxi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkddqnk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrgmdxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuzqxrn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ouffxgkf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhyalsi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sofhbwlp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkljffb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2spmnjteo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzpzmqz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvivlpoo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwsscss.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tkieixfz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frjzdobm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lplxcoto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhzeyct.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrjqsua.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utplaewi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2maolmvgn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfdevxw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2amiknfvs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vedefite.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtskvbps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nolqzigp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ykezspvt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yndzdspr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjlocgp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2orfergeg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzwbmvp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stfzxqca.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrafukwd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xohfjotu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ostdpvtd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amtcuslr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbamojdi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgbyjux.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kzulhqhd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjhaxq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwheugnm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnwavuj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuxaxra.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrxvopf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hciczbob.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjkhqdj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivayaumn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlxzzgn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xytvgejy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2njfxalvx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wejrzcyv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biwwhitm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlhlwsb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnakiay.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhwvkgs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xcujmfop.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxjsttp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvuzgxw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuzdaeb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oymaonxc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjuezlz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgmebgk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xixlojxp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrjotrz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdolkph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkitpeh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyzvxkr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jgufthgr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylssefkc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfjjsyb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uezdcfll.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qlweogls.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gojqfljz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlytfvvk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byjhdaky.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyhikgr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcxzrrv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbtrigm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2opbdfpxu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ngumynza.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2blrdozvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeinpvd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmdwlu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzzbbbf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbcgot.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2trvhjbwj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prdrlvzt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyiwwiw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qhseuhvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmtetkx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdctfzr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2suvefthq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2clcqpsgv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oywpdvsk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiawugs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgollvm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stgmcogd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmljftw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrwwawj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxkyqky.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfcloyt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbpxghb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrpqlvp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sldcadld.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viggvheb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qqajqzum.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqgsnoz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmnohjp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjkisbq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2katiuzrs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwosnrj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwwglmq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpmbkqy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mscsnfgw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nowotwgw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vswhphax.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2idepfbes.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxkqpxc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oebetotn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxmqkbn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsjlllw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqjuiny.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2juvlfeli.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dsstyael.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhyydpv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwsadey.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqjkvc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vxefqaev.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzognew.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvojyhw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kysemlsj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2prqvrkjb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgfplmb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtkcwuj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfnvco.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2krdjjuno.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jvldqqhu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klpkzpbi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxmdkco.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaldflh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqexkhf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yonemmas.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lauetfgu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ennznpsr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdeblx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qetzavyx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsbqpxn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgdllvs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oszxxnkb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzkrjzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swftqjtw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwljkph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cggyssoo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqohlvl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2widiirma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goigaylv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvqcbbj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvifvnd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xecuovvc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytjler.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vlefawfu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvgkglg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2huixczmy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthboelt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjombas.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2flhcjjby.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdstfff.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdhzjsa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hbezktrx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqadmriq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvfxvxs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxwhrwz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wuexckkm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiuubqz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhufjft.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aazbnepa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2veyunuau.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaswxnl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gywofahb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhuteto.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sshhjjbl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bunnmntq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hazhjfob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvdcidz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gstslgtz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcxphq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hudaqeda.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rntoscoe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ncznuqfv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiyawvi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkgriup.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nttxocpp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtsmkzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2heqpazrl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oehxcqmb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oosemtzi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmuojry.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdghiynp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoblzay.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxzbxnz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsujcui.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmupnay.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2twgursoq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksctlxnn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbpydeg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2unfcbxcy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eycfzcvf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmklbzwx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdyzokk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfwpwwr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzfjrfs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgurbzg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewioeywp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2trhrjsjx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvajwpi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bosifsmk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqkbhbi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lhefywyw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjddyib.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iehqyjqj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpibrrb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaodino.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hthkxmhf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2alnyzzqc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqicgiw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oueojozi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkgegvu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2umxdmnts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozsclc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgtgrdi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oerlaize.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zteaigam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdilwvq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qddwwpmc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzgrtla.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stndtwio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmdagrl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2frucnefm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcigjmsv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kliqvgmk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2glrsnnpc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjzwczl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhextagf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rmezlnlx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2irjythkr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2icoivrmd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbqyqyt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnbltzs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vheliktk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2icqjpyql.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgkvrcu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqqntgj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhmzhcu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvecowci.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwlydmc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2caxaczhf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcxnoak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xihnuvkp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2trmokpgl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxhugwl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ieopzblp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgsdnra.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2utzbbunu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmswrqml.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqdwunl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqqtphu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmybmqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrupcdd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvhfkxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkkmca.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyxwuir.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuukljx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vblsmkca.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gukibtvn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdcbmkd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgflvgs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwajcon.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hixlwlxd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yziczvgs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2regakqih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvjlfhe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eylbwinq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ketcakwm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkvukaz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2efleilqg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fasfpkuu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnlgra.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kmntvxbm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmndlioq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmspyap.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlkpqij.html


<!-- 参考信息 -->