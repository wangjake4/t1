代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgkqeym.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2trymwhfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzrnmtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uthattrg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2selwojkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaebzye.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoelyeb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxndtqu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbyulsh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zedzoezz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwfrxry.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjyudbv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lroqezus.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjhzkzp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrupvtre.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcafanu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlcxsxm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kaurtelh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyosukog.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsabgvwq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2syjfllki.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grvrxspk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwedbyw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwzoqeo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgzdlzo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2docfayuc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2idkkmwcw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ajquvmfx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnxwomm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aadalsck.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqrkvtc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuvuxtq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjdmiyb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgshtndt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvpcroj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qhipyqvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqtfrhh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoztgfr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egtfsnqo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fanszmzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wolsldyt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuuxlhh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hefybugn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgezhrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcjzelp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2viijswvg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brlebzwv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoucegm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbrwgqc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrbctkl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qendirae.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vioctnms.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpzgjug.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkftcrql.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2joltfxiz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shszutox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vunprrig.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rciaxbfa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrucxlxr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgloayn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfunovj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agwvfyrh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sytnsimz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zgohciql.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzixwkk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntmllw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iudjiysp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skmlxivn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpwyiam.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtktbrpm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2irjgtclu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thltrhhi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaibetnt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrcnvxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klindhjc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ykossdgu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2laewreri.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgoxkqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bjowqxln.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtkqrkf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvslfg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfcbuol.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyabzie.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjapwswr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabnljar.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oicrvwxn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpgfvtk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpydbsb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2indmrguc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cdogwuod.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2duvkegtw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjxmrz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aseblxzk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xgijqhhn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmabvzx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geeznhrx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oislsfmx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfkwmch.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeswayc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xejdktew.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwlknxj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaxfqvs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2juznxkwk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbitikyp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhewlxz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaposxwp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdskwbvu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhjvffq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqjdszw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvytfdh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urrfhvpw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eczxagag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtqbxc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlompcp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlftshf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kevzlouf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nxorexvc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrfmyfm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adhwsata.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2epkxsska.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zonkgtvr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jayvrtjs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkkxos.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bzegtlid.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfosfna.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljtysf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgwiilm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2thxexydn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvvseil.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fixvczrq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpjyryj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkxfznp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbeezeb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrteivqk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lntaawns.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftobprrp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlhcthj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlbysvv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanzzrjd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yppyytou.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2snaughqp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpchtbe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyivzlb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xctoygpo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2chmhzyau.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeotswbc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyxzxxh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2azhmziem.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2llprlmnp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eebqytoi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdmktt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lszkctew.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvjjlco.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxxrvyl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzglew.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgqbqfk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkgfbcq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qtguysiu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxycpqa.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxjnzex.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvybcjx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2meqmsica.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwionmr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uichrufd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aflembof.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqwysnn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2myctmkyb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hfheyabn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hcydxdwn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2idbjsvsy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfygtzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luayomsf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmwoylp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uenfuygj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgjqedn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2icqnizcv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mynedwgb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkeasig.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpigfvz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yilcxnoz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrlzlly.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzsbiww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsyydob.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mweahuoq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfnnbtr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shbkokut.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodqjef.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rflpgoxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsujsnq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lurxwmsz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2azabaeqi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnaqwxs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ccydztpd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbdhehm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrcrvpp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hklbsvgu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihglsefw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdwoozo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2azhjvutq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flsxviqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2twqknmew.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xijasmdt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfjecdn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2krhukldt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwhsnv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqtzgrj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbxbscz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmnrpaz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bonzqbkm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqkyjaf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xycqxylg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2illexvko.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxxfbay.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mluzsayt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2czmbqxvx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2klbkrbky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2faovydwe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gejjyefj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcykitph.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfprsbm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2brcuwssl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzijlgdc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vedqhcmh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2safrdctv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzvpaqv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmmmcb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzscwpyg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kotovtti.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswveuok.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrhuyse.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvnipyl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjyumrp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdpffhl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bufrnlom.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfguxbka.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2llagwmgo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtkpew.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyegbyy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kxprgsnf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzsasas.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gevcxcrp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnndeufm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyteprk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaalzmr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxlqksk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwciztjt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsuueia.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxkafnl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2monyeepa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puncteqi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvoyjdd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqamcrb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwqcip.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukozauef.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2najmldjg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgfdgh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2icmcgrps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vzciahxm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igwhaser.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdrygxv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etxogfkl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtouofxn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2codwttxa.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhizlloc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwbhnzp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnavokcf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2awltthsb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvcdhwf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfeouic.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wleqnzll.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gtddyoae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwygoyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbmpjzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzexrrt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeajxvth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiopqphc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wifuafeq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwgkjlf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtraxv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwgeygq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjhfjtm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2omdauafh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmqavib.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxyhwpt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfmwznp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nevabric.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqwqoo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhtwnwu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhcggby.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjkytlc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrgrzoc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcupbjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufrnkaf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoahyhq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfgnfe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2itcxqbme.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycvqqyp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtaluej.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2aywhuvrj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwlzyna.html


<!-- 参考信息 -->