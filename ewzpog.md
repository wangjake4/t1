代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbhvxvf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfieuzny.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmawnva.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iieubjhc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlbaxmt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhbazxy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2epnowvfk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuvnkle.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2konyhfbi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpemicb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbobown.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjravkdc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2toaufjsk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hktmqpsi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bycuceuy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmbfmkm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgezijh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2buyaqjth.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxfacux.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qckrcsfm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfezsram.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkajsig.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mudmartq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yerpvnnj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlcampe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvjtgco.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmxnccw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjyidcj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adueykxq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfczfme.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2roaqeseh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qfquxbgl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzlqjtt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2idahdujf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcbzqkk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdceomp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaphuqb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbjqspy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmvdrbe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvkifoh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2evyigakn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dszlmoxi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzzkgb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2njphxiyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmmvvgh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvyzbth.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbfvfie.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitmtusq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhofhwzt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfqvzij.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqvgvst.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwdejvs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvrcfpf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjitnlma.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxnbanp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdypucc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iynzzmjv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsymsls.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjmzfds.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnsvvwc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqatzne.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mosaqxbz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yheyotxe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjsexoi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hviirini.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tejqsiis.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjztseec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgjhuna.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkahpof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhaqcgz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2orcpnzxi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kbytdzpv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvfsima.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfqyzvi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdafagih.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkvcmph.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rllpfuss.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnupsyj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpkxaeq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2afrlslvj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqgotpw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtexwkcv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuujdbuz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nakzqift.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lckcjtlm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srdxmyzr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhpnoah.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqwydkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqtkoal.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umtkmnih.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2adegmemu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2osatamog.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfktpwx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efxyeeos.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgjudym.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uilzrhxh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgudxjr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgivyiz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twlwfzlp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iegtzijp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkeried.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2grokgucr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2myqmtzsv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huczkrdm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxsrywp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfuleum.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iewsvdge.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtaphbj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwamekv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptghrtoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaeezfc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gornlygx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbobfmnz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzdwnlf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wimwhkee.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ruceurcp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2odpxotxx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjrzlqb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqqnxzr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtgpeqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjoqjsf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnyvhiq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlagohmc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ivemfbue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykksdhog.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jubycqiy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrlhiyf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnqivph.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhypxgn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oanrtcyk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uunglhvk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqpywsv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kepqpezs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwafqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bumakzmz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdveorn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmovurzn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfmmqex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczeyxwi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2noazwggw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2judfzevb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dumkgavm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sumfdeoc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fccukcpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxbast.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oirrtbzh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdwaepg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rclytwes.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnakgcev.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpedyua.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwxakde.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyuxvhd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2txxwlhny.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yruihczj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbspulk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcotmrc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcwkyyf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxceaml.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2recrsbxj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqvatng.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkoabzy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrgphmx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpklqrw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzazfs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sahqxphj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnqtppt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iahixeto.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeitthf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmaarlx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmfevgj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dugqoekl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyekicl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rkupgktf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2swmlnwkv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msmorhnw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrpfast.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sryafpgk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmungyb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgnyste.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhwbnhq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjzovyp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfivhokb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvfhtow.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwwgvvc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnvrdxa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2waibvzll.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2smjekkrj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqcndpq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2viyfiazp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyezuouh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2chjhooje.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmosgfh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyajqyy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrmwblv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rclyrdvy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gexchbmj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzedhtp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fehadwao.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjqflfe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcpomvl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nafalxls.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mznobrcz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvxkxi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcgkxxn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nglfornt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2smqnvyut.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nasaohao.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdqwdsa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jphzufyw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoivrwg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdooxozx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2czdkiwbq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsiwxtk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjfodf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tmclxnut.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vevmcqsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnweeap.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2beswsmci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccestgdv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xupogvfa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qchtgbay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2napwdesd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzgnyyi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvbpsfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkxfxpp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cspknnvz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivxwep.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgubsu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuvidxq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sviafrpf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egrdxfdc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2foyukdew.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpemthkb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbbgiu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaqtcxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqheqout.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxadlrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uadjdxwq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rozeryux.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qvebssia.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgzabtt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ermydsac.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oevxwqpr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2boblkkzk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmypsagb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sztyinip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdsjcld.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjcqwic.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2karqafji.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alqcaqge.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrzmdoc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiblamh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xoohcuvh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrjttwi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpefsjl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhaspfz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ffolxaeb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jiriispf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnogynv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzvphvh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfcwzzz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjcdzd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkbhwpi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhvwuvm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwulzci.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ooztaqqu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2imbubqrz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxdybip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoabpbb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2geinfllw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpqxjrv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lygbdung.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsclmfbc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkstgcz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vagpgkpx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyitknpy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbncxuv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimsqoy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2entxpcad.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqtpff.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmxajqv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhphtyx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnmoxs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yombhgyx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbardpth.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2smulvigm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2auakphwd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cclrjizt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtowyfu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnuovpr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhqvujt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yduiiuip.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbzasbz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zojzsmky.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cupyskgc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dykxhuru.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pegaubsa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiffeii.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwdauue.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbobzja.html


<!-- 参考信息 -->