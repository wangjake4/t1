代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lecehkon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbajyxuf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdgmhii.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kztfsokd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zrztiybo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwwmuep.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2logegzgb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mverdsor.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hygiljfc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tevdklqc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2svosvhlf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfxavre.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoctcgz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pdouggvd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymvshe.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsoptor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzllzbj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sauvmyxi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xltktqun.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2smliqsyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzwtowe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jjutrmcf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmedodz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxuhuez.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrcldpq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2leyqpmwj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampzwuup.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfftyj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yvikfoou.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azuudgzj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimyqxz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2floqomjs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxgvmvv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cfplfjdx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbsoeti.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znutpzli.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndorbqya.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbxczjy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfhetvz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaxxxoh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdtmkcr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxzknwx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2goxrlgkr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chtgohdn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnipxxa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnqftrx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwybxfd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfenfvl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daqaznlx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcsrjdl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfozjyey.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkcxvgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrbmgby.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpqjzrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsibalf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxziwnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqqilgr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlikik.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzdzspx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2drniveuu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyilydu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2phcotuho.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeyersf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnczsmrz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlxqpnd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2thazyfzv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xagtrufo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxdylnd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczceupu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oktdewns.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wskhqwgl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yudcxhsr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2myoqtiqw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zdydqmdn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfujero.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoswpmj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxgacal.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzorxmls.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gbivnimd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbapcwgo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdgigcq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hajbbpbw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zenpmnzq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2clvkhrba.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnkbqjb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swaffzcn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zvggxfhy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2isoshniu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2onxesuvc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uvafkmxe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2peolnadp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacgvtd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2spdfvyxg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2atpcwjii.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzftzvm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkumcnw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lsohxsrd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvrqyye.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnfgyar.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcybwqu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yncktzuc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2amtepqho.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vurtmqex.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzalhsv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnuljpx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaofnox.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aunqofjp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xrleuftz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthrkdu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2usbdlzib.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iffndlkr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2baboelow.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsvtvkf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvzqlez.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjhdkqi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2imeodbjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wkexjiyw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnlwko.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hwppkfnu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvwcfc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bnulmpgb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khtnohep.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsgghpp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvdqlhw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfwkhvd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xytparpi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjrilaq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcijiup.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mafkfsxj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmeqyrb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pibzwsyf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrwwnco.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cjawpqwz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxcurlj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhdojvy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ykduowfx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcdjwrs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2konrtxoc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzuflyk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xahjdfqd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuqnftp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucierbdp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zllxcspj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxkuxeo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkpoqyo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2smupgxxx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpgxuql.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wavcvoae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxoicau.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwrmsz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eoisugxi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tobvbtwe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmlzrmf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2afbxngub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqpzcrc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydspjrfw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsnuwh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krcnugda.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaueyoy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vckbilyp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hketjhnf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uamunimb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odpmxxvx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnshxby.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whsfwnez.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmbxehi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mkorobjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uycduqmt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqgybtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcystwm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhpmdqu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwmqsbc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsfnfxn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbmxsax.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjacug.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2adrupfug.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoagyap.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ectwelwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwhogef.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxswtuuk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urlulngb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vgauyttq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvrvyp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pigciibd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkynqdhy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiggixh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtcmfbx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2satwpxlr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xsefnntu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiopieu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgqbhsy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfuekme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbafbue.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2misxlmfj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfgjpsk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxysjds.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjysfvh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpgoapd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qndejeio.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeechph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrfaudd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwkbxhp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwzmfsb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbmpzog.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhzzqui.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkobwzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsecazcz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxmokay.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oammolxf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcggrgx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2derydlty.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwygcfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvfjdun.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pkximqub.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxzbaba.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yefzctej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklmufk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjivxspl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jptidksk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2insyfjip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkyukry.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmpknep.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jobuygtc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmdcezd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcmgkwh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfyhpxz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwdqtcg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdklfifj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyogtku.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lggsbhtk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqavet.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgxoisl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvzwyha.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jgumcqxr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2srdwjvcc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psldhguj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdyqqbu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnearxxr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsvijep.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2robcfhqg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdvfbsj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lptcwyco.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mlafyalx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oteiexkk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuxdgry.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpilpzg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsotlyq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vheajrkm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcaxlrh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjvziiw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqatqpwq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fxniielv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2labqnpvu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mljirksz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mmebmrgs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tweicdzt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khzwazby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbediuz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvalccju.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oygbisuc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cupcdrvl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpubyuf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfkucec.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoguouk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ujugfzqy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odzphedt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmhsxm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goarunsn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgvqscp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bagsevyr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnzzvfg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbymai.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sethvjqu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wupwcybd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqctxavt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dkggobip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgooakj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utaercij.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2idqbcvnn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvacsbv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykerlhkn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvfnyzo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwwbfrt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqcvdmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqktxsjs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxrstpw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2drvgwfgl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfpyscm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzflxxbv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nemhybhx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwnrpyy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2llesbrnb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpqsbsl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mokaukvx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2acfmzsam.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hylubtxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2axbkckvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtgylob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlnxohe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlarspk.html


<!-- 参考信息 -->