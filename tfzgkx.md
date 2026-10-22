代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkkyizq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uocpoxso.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aarbuyhs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2prrikgxb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kshvjnes.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqgpsxs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nutculmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baekukaw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nkluhbqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxwjfsx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfymcb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lrodxppi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sxckywsn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2csmxbayn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjoydnf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqqplfo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxfllbt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azgmrxey.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2seupqhrd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2monsqbtq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqinysa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ychdaaoz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlwjapz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbfdtc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrllybk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrhsili.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeioayq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jeluyfpv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoowmqt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgswzjj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfiumy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhajmtx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeyarit.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2slckwujg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhblchcg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hymzusjk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2alpoggdj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwqciew.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjojshwy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2arhlsnmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcppbz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2euukfdbi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeeogkq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xztlvawn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbwbgmk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yldawfeh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdtxhcf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmslunux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cotylgyc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2itmjlwkf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kulgvpth.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpumrbeo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkjdnhc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwdvgau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxeqcxs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2intwhxzj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbthrfy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjyvxop.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvsfljz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnctclxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2heumioii.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xemqyuvc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sspxkccv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgznpte.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atusenla.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lspeunna.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjlwvwi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwzozfq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwfeaag.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhkrnrh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iviovzhv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekirqkfb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhfgpyh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2meuscpwf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbmxhjx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlgnjux.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbkxols.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hfobgumf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzombsfq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjzulbg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijmdyd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrubvyx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fceslczr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqiclse.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwquhyrp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdztmtbs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeddplz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnqabqe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rseboduz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yuijlvyv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sderrrtw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uiadmybl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2blfhyezc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvtzrob.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrykaam.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlwzypf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhqwjia.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iodnexeq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoybwfa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mllubwik.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hraurzow.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcxhdnb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeimiwr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2axiweoeb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgtzwrz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgqujvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhwyvlp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xromuqry.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxypbhya.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyaeivl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iomrbcjr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgpnstz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jncbsujf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfoishj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvymyqy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmgaaoh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoyrjgr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgixtwik.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2axbfdhtp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gczmuawx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2arwwfauz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbjflor.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnptrvm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdxjvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfxcxec.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cfshzfhm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nduanclj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwefmfj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxfhgfx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whjxqkix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oalhfudh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lutjhcft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwqenzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfneaxc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvgnyky.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgosrpj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eboeljri.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjugccg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2atordqwb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2osrfchvv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfrlpwm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jduqcblj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktakhwy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bofkyipn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeepyeu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pcppzibn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aropgocn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzkyvbt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qclhregh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrbidkz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofegigxs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpilnlj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzctfio.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2txueyjqr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpykvk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2inxctohm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavoxuv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pftpbfrq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfishqf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikdoop.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfxclja.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hifypedz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjnufsg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtuvxdl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrkrqcs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epokblbc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqmztob.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbkplno.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiidkzb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vohqcgrl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftegewpw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tfronyqe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaaptne.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rwivixwl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ifezlcve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwxbaah.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2shusafug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxykoyua.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qznsfpuv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxhwczq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wetwewbp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaycqvh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlcjlwq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owflxahj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2caibqsjr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2swbrifps.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmdtefd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoiruwx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmraek.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2byvcpskt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmxqumt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoqnpym.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqwqbdh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2flzidwsg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzqthpf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiscfmw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdalxer.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdykziqt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtahrvf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfrydnv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnimnxu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfzwrvm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2knkrhmyi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvehibuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2scklqfyj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jrecbxen.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdondga.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2htlepkti.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2erccvwwf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfvvsaq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvoxbcd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2giwsddvj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjshvyxi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchdber.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafkbzjf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prdyshsg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvpbwnf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rripkdsv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkuuvzl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxjupgc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtbjpum.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2alndlhwj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2logxpcbx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgwlmfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsfkvme.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yinvovnw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxgouq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kopusivv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgmgiax.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzosqlw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cegyecyg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghufxmrs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgghnlhw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzjkxju.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngitfsss.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gppacnfu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmcrdvp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiapeze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkccssah.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2prtltamj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjpbvto.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzeclxi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2femxlzyf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtqnofp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rsefbfwd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgdxoic.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yekcgmva.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2czporlzs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwzfelp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaiagmr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2laqeiror.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxxmmnr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkqdzg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcwlyxm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cyewteqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aditagzt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zhabrqvi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhakzpmc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zinwijht.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvagdtey.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffolywef.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsdlkwm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2meiajabu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvghhdmx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrxxflj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xefaqfgk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsxdyqi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2axkrhbwv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiidpsb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvgfkum.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dyusmhmt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkgikua.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oydlsnbr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrvltvr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dfegrbbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtesxta.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhznpch.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwvdrlb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puenxcfi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxhsqhd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuvzehp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiutnqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vprbiahn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2annrhepf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2acuahvql.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfwwifs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpdmtws.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jtanqznc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbsxbsx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ceishvka.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcfafuv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsvhxnw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkouaawi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lllqhmkd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzbthaw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwsgxba.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxardaxk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeukskkn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoyevza.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyaunnv.html


<!-- 参考信息 -->