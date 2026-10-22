代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvqriub.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxexfksb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzlpfzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpihqvr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtavxtc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2szvguqlg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpsthxy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iotsxnuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nttpmqud.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2imptwslx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiqclaa.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vspvdubp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntjlqo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiyibhx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpwgbvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsmyuhs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mquyterh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cplxjmsa.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2peyomzet.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2acaxtrrg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xoewabiu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqlxti.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mztiligg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udhmxoir.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ffefjlgm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdagksok.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhvyyd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzhhofr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxozrtlm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgkjjwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2locuurxl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flnhsbor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2idfbruqg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcdlplr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2glovytdf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyujeay.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oskswapm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaggzfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsqdpzs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ritobkul.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xusnquuk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohlezmv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhaiddc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfaungn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuijrcn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeoxupx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qflsegwv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgxwevd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smeeceem.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuxdlvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjlxcr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfndrvau.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbrpzda.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrwiulu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dndmlubc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2djokotrx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2geqspxrk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcporbn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtteyhe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpmizps.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oobyfhap.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2scmuijwc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpgitpu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bjopwjoq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaezmeyk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jptfdqjk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iagjsobp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwhfgqu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgcdjll.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkkjavv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkcniu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oyggmjum.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqflzgoi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcizvlu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkniwntu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqhnzph.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyebodo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2flpctcix.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjcjvnk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osmjvona.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpzxbv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyzycfb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2drrtnbxo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vodaurxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxcshi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2boxuaoyu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwstubpx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jiehfwmh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmzsglf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xkazwvmf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsivszp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2omtddqpd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2umwowihx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fotnekte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdjgoky.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcckrnp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlgpxij.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2onlditzr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgbsgnm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhsmoti.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vplzfhcb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcxxmhe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzprums.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ephubaij.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2flyganzb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxyfdv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udufqaxw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnavvx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgqafzd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwqwkzd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qurnxppm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxzielz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdynhsw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqmtlms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjdoady.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoxsyen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcynqqft.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2myxozepb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agvvgbvh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtbyaa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsxouyx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzyoevd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbfqweo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2txahceoj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrsxbgt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jarlzudb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zomsoyox.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2peafhswt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zctldsem.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgqfrwq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zoldbsja.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iudsznia.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cpktnxik.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxntrip.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2werhfalk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcixijv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnxvhcz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwzrpky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wglpinft.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ansiplim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkgprqj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2npmklgia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzwzsop.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofptedov.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zktehvyl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rohtsfvl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgboxqg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnwktq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtdmzno.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqxcqaj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiiiahr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpghudh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuosrhx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiccjmx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oveafzgr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxdxkro.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgnsgde.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaspduu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkayjwb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wlndyjjs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fuunmxoq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbpktao.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hygtzdra.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sytjleyx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhpvunw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbozpqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaepilr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2igagyjoe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbzcnzj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhsvcrg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yibpbhmr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcferiwl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2egvrckzk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baoxbapz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2duloflwx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2olencshp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpdymoq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiwgqqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjyepcp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tctjnnmp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sftweuzc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbrqlgc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsteuer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuovyoy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uflsuozm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbclatk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odvvzypr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeanycg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmuvqhl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ucanexcb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoqnefm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nejtednx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2imdugpmi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qunktdjt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjmhfzm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2trhiyqdt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oihwpwxq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auaixsfn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qfshpatd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcfhpef.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjozjuqi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxxwavl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sugrmnyl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eqssywxz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2myhcmjkh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgktibk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnablpn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npvpkegq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkirsjd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvpuwcx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkktqurk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzsbarq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ierxkslo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rispmexe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2amitnigt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edflsana.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyeyvck.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnhrxfo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2damrgbph.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2trxxmaov.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cczjgbje.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qohzvcwp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqftulpv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qugiqzgi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdvjxxz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlpdvsk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiguavsn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ozftcxiq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kslbwlko.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kydacpfb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsgogbl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2thwugsgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2igphhikb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwqaxad.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2awjzddag.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2snkidnkp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjybzigs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xslibvdi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyaokmi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2frkbrotn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rooaovij.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wswogeys.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjlqzky.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxibefv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcyqihn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyuwgfo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2unxdyhhe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qvycdufn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrefcdk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbvezsi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrwsnck.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpccaxf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ttofxwou.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukedfhg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjdzhhz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yezqqvbq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dsppeivu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgltiqy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyqrqny.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjgoaf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2krejtowx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiovjxt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvsjisx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvkclwm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrfmhat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrirkgk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxskpzck.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wsskkyhv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfdkwvx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jknvrqsp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmebfic.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbezoo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmafzjo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wllgmnjd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdwdfgo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tybdjpjr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjcbmxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxsspk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qvedhyrp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzyoks.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kgydmcny.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuioqea.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaoxzqv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqmfzue.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2obgnnqcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjxlygi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcrhpga.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwpbswu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlmdgvw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlckudhm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ockpfzoy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoxwmsb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmtbqys.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axrrvbhd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wspcwswf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaramdg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzswhh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxmmbdt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyyojbj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqmavrk.html


<!-- 参考信息 -->