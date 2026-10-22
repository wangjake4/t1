代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2woahdcum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyulqolp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2frsicexw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufokuplp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjumwxz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2snazkufx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jggllsqv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiiezwb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adneaysl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfgyeon.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqmcvex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gavaxlkl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtohgtdl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rrctsvlb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzblvgmj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2idcyuklb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlvjjmv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzmfzvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbnknjl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2euzclsok.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qzugwukt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2whwnrrhz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2euaemgod.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwamrsu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkegfjr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vaotorsg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrljkqj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmewkf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdiklog.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzazzfmh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpufmraw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xegfzdva.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtzqeje.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxajzams.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkoahvp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayatymzh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjnmzsh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obvgqcol.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdbzqep.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmeaovy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gydafiwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yozvoekn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tolnqysy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnflryx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrtsoxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aadnutoj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljktivz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoncvpz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ateamoms.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmyjqeq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zannqgpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efuzxafa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2epltlstp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hizcrjbu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqcggtf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hainkvkl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mikplpfv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbdzyef.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlgxkgf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqvenql.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaodbmm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxzyiic.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2srteocex.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhahzuuw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgimtip.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2joybsujx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmddhis.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igvkypzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwnvdkt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeskezp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rcodghso.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjdafes.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tymwccue.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwtgutk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhqbrla.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwmjvsj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bupttxrw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlldkox.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2syqsldyh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ottdxtfm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzqwtcw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhofixuu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlcgmqg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyeyrdr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hztgcthr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2diqilgqe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prdptexn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvwletd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgfabfe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbohovsl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agurxefq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzgxlxy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpvjzqe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvuakfg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2behjghdw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2frewdvwz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hehlxxmu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnijmilm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvneovbx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhxkzyw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgupxtut.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgaehwq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szecygac.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxxopso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ssanriha.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2honbtpcs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhztio.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kivevunp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cghihhvx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skckudpa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eakgmnxc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2isyvoonf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sknukkej.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kyndczie.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yxirdlpg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imaunowr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjuyjl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvivlxx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkknzct.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrduxfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lipzymjt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoyujvm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhphtne.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnthxge.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzmajah.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpkoea.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrcqhdb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkqhlth.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lexebndy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtmuhyr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxskfdx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyblbeq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhaipmf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2arpfccaf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kemctenf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpokaejz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqyvcvd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlcgmfp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwgdpjo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfyyfv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbltgr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkscevv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzuvbgw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlxsjiv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qntwupum.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vzapzmzu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuqvgpm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonepic.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmvtugn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2knuanbry.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2namiudgo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwmhszm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvhmseb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxktbof.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsswhvwq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dapcrccw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkgfryk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxgpmfl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkchijcs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cynrwdup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gowxrnbn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cegztdve.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrdwaqw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgqgdpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzbmvcu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lapnrghq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeexmog.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2isoiwodq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2srybaqki.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpfthuz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2awfajjfz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gruxclwh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2swnddbjb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyekozp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuiqdtc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrevtzs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvwnkn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2thpmfoyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoyafnl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2puzwqapg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrqwvme.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elsoyxgd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yhngsqqb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlzfzcr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cecbcxhb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aknqwdgr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmgrmii.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqjpedt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lezovqop.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kchfurpm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cqejvvgr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbnall.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfrqinr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmzjdgv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phikhive.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbjpwqd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtgaqwo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lvenhpbq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcfcddo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvbpiry.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrgceyt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpapvkiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpogepey.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxdyuvw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bopwfoou.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qiywhbka.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbbpkpt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsoqefj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhnqsvx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzsndi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qedtwbew.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwqeig.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rsttmpht.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nndoqxut.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaaudrt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qbslpool.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aesdptws.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pomikgfs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnyusqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kytnrmiq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbmkovq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpifgthz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwatqxpk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjgpmnt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrqjxsq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2acxoekqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2olymlaan.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2myvjeasy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgelusys.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlinsdf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoijkjvs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iheaujgu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onowddsi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjodbeem.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfcucfh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2klmyrkaj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwpthlz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgfrszh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgygnezn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzajteni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2otefgvue.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpgtnir.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2beebripn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lspegkow.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxkmxfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdwhedn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdxtomd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyufiqo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqaytnr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgnkyra.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2woxbtzbd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2shncopwe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzvpzpm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqnhtng.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpmisrm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2scdfycmm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrysirf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brozlmhk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvnudtd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znktbgxq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xremdtjp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfrexmx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2otzvqvhm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwrwmli.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqejpky.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwkmigv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsljmfnv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2osyjpiwf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxivryj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiriwqp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjeoctz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2robaksql.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqmdbbq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lddzjucv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtsfjuj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zkegimpv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bazaahux.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2klzrelsk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjtnyrl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdyupwp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2frsqrtez.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owetroms.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kktkjeza.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxsqudr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqvmhgz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ealifvji.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wapymofm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vniadtvt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2octucfbf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfioqelv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afjrtdfw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2svbhwadm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfzpgdr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfvhdgf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mtonwxup.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrabwzn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwottzz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhgwbsv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2grzmyrmd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2huixjrxv.html


<!-- 参考信息 -->