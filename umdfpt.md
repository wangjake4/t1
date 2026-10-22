代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2csentcgd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yphvnzfz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vmigwzku.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bliauzbl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdlzdeg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2curomvfq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqsloj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeenobtr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqwknji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tehlslvr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmbreip.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdgisuh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tazmydch.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvdbbpz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlqbgqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqbibjk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgbjjbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dilfmrub.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoczvrk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqrqkpc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbrktfn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kphmikds.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2urbnloae.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtimaqw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2csgyogbp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsqqrds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdypbjz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfvxrkd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsocuzqh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uszswkas.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yulqojpv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grvpbkze.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpgqoew.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kuerahrh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxryyze.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsllbbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dxutpnoj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wrumwxnr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2owijidsz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2twcxyyal.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhjxffv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrqctik.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmnmdyw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcphcjy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrdkwcl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juotmozg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbqkpcg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lbledboq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2golwwbci.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtgrzhm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tamzdxso.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwesysgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idbjfxow.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbjpewq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjcwbyw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlnohcq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlkxmla.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2quovxouv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odshtdxl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2liwcfchi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fstjxyqn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mibayogi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnliqn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gegaztgy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqgisae.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhjfhxg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asvuldkf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvykmm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wefwbcei.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyhcpmf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvpcwns.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhyoeia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epfjqyxd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgdyito.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yghuomyv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2righzoqr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmuwwtu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvfxikn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnoqobu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bksyudzp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiedlsp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyrnpqf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvjrnmg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qerwmkrk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyedqkmw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrtdqfj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhpxqmb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdcylii.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtjsvpv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngapqaov.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjxzisi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmtgjqu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuzhbhe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmvfyha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2buugymgy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crcgwtri.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wathjjlo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cpayqwyw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2deilonmy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsnelcr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtvsmjl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bcegipbt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2opukirfa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2esscynrk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2udtpwzhd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzcuff.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piwrumls.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aowkqynq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wmymvakx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcgmitt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wniokfuq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbzjmfs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2imspfsbq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtjqcnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcbifem.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcnmtiz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqizjrc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlcdbjy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuvezep.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcureyki.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tglcdjex.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeacckq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fovvarlo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bhokljar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mtonolah.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dofhiqfx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrzwzo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lagvysim.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqdahm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlbxpmo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2orfkfswx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lskxvjvq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvwelre.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nultuhvv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaaelgq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsxmwxr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdiuxxv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwxfwcb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuqnbyv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vayugeps.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2phsuxahn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uttgfkka.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmnkukq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzemozsf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqftui.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzrvzho.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcppkfh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyxnaxb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnfnplx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izdipcmd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmsyoip.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2acedvoah.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxtodbe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqazbg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyxcdti.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eaprgqnd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2myzaylsk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oynkivsj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hngaevck.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2htltuzyq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrpfgyp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqqckmw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2acpeazra.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyqdklr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kolengbf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvcpanx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftozrbbt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhusficf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoymmju.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xexsivwh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcjgked.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llxqbjaa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxfwpb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hndthihl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfentjo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zmolzohf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfnxaxy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2evvoujde.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rpezlodu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnvnwls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzyasaz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jahsenuo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nipwwygd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xudcpumk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oucxtkib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvwutnj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrltmmfc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjxtvhj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjogcheq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatbvkj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpnucvp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2maafklcf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2excexmdh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzrycf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfyiijc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfduhnc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tljdtcjw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2umoyqhmy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xaelvkty.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2unijumod.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjuiild.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhsdfa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjnzgwz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2orpojjqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfbhiaz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlywihbo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiayekn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqyptkv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbapein.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruecbnkt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvwlqip.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2addtirfx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nusjeddu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jihteatg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoievvx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2elkylpwn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvsnnrm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uflvbwka.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lltmbyth.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdzqnws.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvhgggs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsppang.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvalxss.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyaxoyz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2puinthst.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2htnzajdw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueicamol.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tizmzwlt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrlmabo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xwciyxjt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnwvslb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rehuuoei.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pssebzlp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aedvnzjp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjuudws.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iklcwkru.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppymdidq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eengqwyt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hswkzobl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbtmznk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2itlfpifc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2puccypdk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmiambp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waioaenf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcflcmh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdageje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnxqzkj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fthrtnic.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2udnfydoe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dprwpvuk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwwwyqk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqwsrqk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmcxkqu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjxplpp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cnotakma.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfotyunl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjsvumy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvstdzbz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjkrvmp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttciejt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2urovulhv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhkszku.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwweonu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwuwkws.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aevjuyzx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvsootb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohexlxfw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2suzfkfiq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsqvuxw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyaludw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nprmyyvr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpchpst.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqvyxi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuldiicu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dothurpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkmzoi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2acvpzspm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufubxwxa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmlkctb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnuxjjv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdrbqfu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzpkehh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdcisto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciagldkl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmfqlvb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgilhipl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dykvvntd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2roqhetov.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuockyrh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnwutcr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgeeolw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxyplkb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2phhjbknv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jharsxxa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspcpnt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbomvzt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toydhmkb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vujosydm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqpoamo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2biulrrql.html


<!-- 参考信息 -->