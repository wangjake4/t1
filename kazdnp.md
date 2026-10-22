代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pckiwktr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2buqogvpm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwhucjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjedaetf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzlthkt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrkfmjb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxmbxqk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyxxrzz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbukbzj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ttslcgbj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwsgmrj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvyppzp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izufxqvu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lppxlvbj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcegndt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdxhyci.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhgbosr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2teeyhmcx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lewdfehd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2toljulox.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vakhhxzk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqhfqsq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjebykxo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdjhvji.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqicmuln.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlbkxzv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lgummgrv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxxlvpu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezncgb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2grgslsug.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgzqjdp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwyuxe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uctyvjwc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbaiivi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpeptvp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnusxp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msghqltj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrcxmwc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjstyhs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihggbyxv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2twiggjkl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaojnmxq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2syurtbrl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wanprgrj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fgehblwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiiqcet.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2raflqfas.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsoguwf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yddfardi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qixzmpkv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiqezur.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hjocwpku.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wthcgmdz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mynohwxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdckfbnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsylulg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ykapzfdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvcjzlw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfyrauv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2agxplvsm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaqybhl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iljvrnfh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnadasd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wslmpqgy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrtpyge.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tejketyl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfgpidw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtmxuyh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugklqodb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxsyoqu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpboaje.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoglaph.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2deqrvupl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2enkdffhn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rihboatm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iyufzwsg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhqkngz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoispnt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdtmnvl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpljakc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hppzzefb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmkslz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ambrxsdr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgeredd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyyoppa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsuvlzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqillxim.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aydoefht.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kiellkxe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aeginpyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtzmzgt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtkoxmn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scwwemux.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zajyuift.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvjgjd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrarczkv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzjened.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2huglmlmp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhbrvpc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fspvjrgz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewryhtqw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvqvieo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqhmjht.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfxhfqs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwvgtqc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rudcnzmi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeooasxl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzmpsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfsuzfd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlozege.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmswjzy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mermyurc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfbfxmk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaamgxy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlapaser.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxabyhf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgiondi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlbaunp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kulwenwo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uplrezug.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbeyvq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrjegbg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyudgbn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njdjeitc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jacgegwq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yirqjibl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txyvnlnj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2omoenqni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcfnsib.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsobynb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wpagdlwa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jimbyhqt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2znrzmdut.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwbdlq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yworncyv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxezfqai.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpbciqk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuvofgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnniont.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uelebmej.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uenrumgd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsfhroi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jxltjxem.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmmlneg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubriaouo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfaocwj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsdpnrg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkghthkn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2grwmhgmm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzbihiu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ceitwded.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtbvmur.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgqjlnk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbnisk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwognley.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgstkvax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpetmxx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnckveh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmklrbzn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqflxjk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2llmqeoni.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgisfdg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdidahre.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwxenyy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lxypqnxc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2psrvyquh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fysrvnam.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jyevegbm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nydxhvdj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcxgkcc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsfcglj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdsykva.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sftzngwe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsnrlg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlbqgso.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zxecggwc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2malmmojz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nggbegci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwfhknq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrpxebp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgzwnmr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qafziofn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cfadodzb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxawylio.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjwkitf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeksegpd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2brcuhszi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbeebv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxoyljc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfryhtn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjulzwbu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuavnle.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjcorha.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtnooiq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2inkhpazg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqscctbb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2swtwtfwo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2umuyqchm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfeciqz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgtztod.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjfbmzt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfsfnkf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qfndyrpu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ielvalug.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2execrajx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yblzqdrt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okxqdnax.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtlyupi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2digtskqk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjlklxh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkolluj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaactva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iobpcwoi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmiwcw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlmcmsb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2njwngank.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jgruqsat.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hqutfiff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkfbgnl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhcsdbo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoocxsx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rgehbuol.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhjbboc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egrcyvmy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xoukgmuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qivcdfxp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afisgxvy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aswvnvqr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpeghvg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2osnqoppp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuqqofn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmpjlal.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2txquyqyk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jcudtstw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnyetzu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2haonbbmc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rthszlrv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfledse.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zbffxbdc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2efkvdgye.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2krnprgjs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xragjxpv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbznikt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rychbsiw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsdqpbd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kekdmcqv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpumuycj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueciptoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2adoxcicd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2etlufnbn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywguvxiw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjxqbvs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxxrixt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2crghmjfz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeypmxht.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fttebyfa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2krfnriay.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsdgxdu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcvjder.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqclcwzc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2covoxupm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucevdxet.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldioowk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itndrvka.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2czsrdxlk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtoydck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooptlcbz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sikohpcq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjjkwl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qihcdvot.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcmumwy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gsooxqhh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulubmfie.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzbmplz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2djgltfyo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjnzdvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavxpkch.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tsibdtai.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tojahocr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fldderhd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwzneon.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnkasfq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2intpnmza.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjnwjan.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jybgetsa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvwsckv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzwwtxa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdndffi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihlatq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcpqnhw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fnggxwcn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjgqunl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjgtwe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwjssv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzqcsjd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqvamkd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xjylbtnr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjicxxq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhpptim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nglcajmt.html


<!-- 参考信息 -->