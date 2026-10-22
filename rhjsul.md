代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xazfypfv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2avesqfbd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgknfncq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdengzx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqidkey.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdyeqxf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwctetnh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2adqsoyia.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdtpgtj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmhqaix.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eryqfvct.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlzueuh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcbvlan.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumwqtn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xluwtkvq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2buwcgfbt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2clzaipmb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmbafcj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqghvhe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2unyopacb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoundod.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jgformtw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrsntbx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2olhydupd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxtinll.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jddzosdu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2weduempm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnykiciw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2baoxnwcm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoyvajq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rucujchv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wagrunxh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbzvhiu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpzdscg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2spuejaon.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrrlwq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2owjucbuc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2absvdtus.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2namzngtq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2emevluhp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pegjdimm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfpcvpl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2itzblqia.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugbhrud.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qplwisvx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbaabzv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qheskzob.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wcigfdqm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlgvntr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxqlhvu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoozobm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2govuayjd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkttsmw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnhxjsr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsxoncn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tsayygrn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hwztywad.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmrixqd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssegdzuj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqoxtho.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2odbgsrvg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrbenw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mcponpjr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhyhckn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycmkig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmqptsl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkkwjgz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdkltjh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2svefhfyf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupdqxed.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brxjstwi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhzctih.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfbgtes.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnblrpp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvogtzua.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpezedj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zazfsaos.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nopvczhd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdmyodc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2razibjsg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kljtvtll.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgbbfcc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aajbnnsq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshtkpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbxtdmt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2giyrpzrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrkwidk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikytdtoz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjipdzd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmaoaeo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sntgnlyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gayefcdk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2esaapmxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2capffbkd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcdoznx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aczqppud.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqogyju.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeyberu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2okbxnucj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqddxj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2prshlxyh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqrkxlq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuezqyrb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2udblxyld.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yijkxubl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2leboqyqp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdhibwp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nliqosbd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwfvsch.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nucujanb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kadzquto.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jttodbhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msofmqrg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfxrolo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2elvaowun.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvvlnyq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2djkzevln.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetxcnnd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2liobfevz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrvytvb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsemndg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byqhfrne.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akxrjjxo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qowpnqco.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfllsyj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyzcygm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ystrcrks.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hewxrrzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlusctiv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdncnwe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tskykvdd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2anaydnht.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djcmyyft.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2veimyoab.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snspvzzm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfjikft.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxusumb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsptdnlb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oulmjcct.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prgigyba.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbywawn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhwwnqa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cflhgslp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsbkbab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwtmtei.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnnmjrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtivtnxd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ljivonsj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crorjrvi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgwdztz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnjyzfo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2troavvwa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjawomlr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gavpkdcy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkruonx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzwlmbx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2roxuhjsn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzxrfwf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqadsxxl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drnfzqkn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdcrszo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoiwhjf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpwllgf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wsivmmqn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2znihevkv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpppkku.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlwafbw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyveipm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrsifwe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkciuhbt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkgwtnb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxemshme.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlilxzdh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2erhnqxpi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xpldhsez.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeacmlh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojshongm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyqabyk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvifswmb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvkculw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfecnbq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2absxskoc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkcvaqn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qribsfbx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmllesi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtakijv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qdybcesc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqvvhtv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeqilzs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwlbvow.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxveszlz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aremlmsv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmyedon.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2omrykniu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izuqjyoq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvqutgp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nrazoaij.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlwwfih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ricpfdeo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzksvxw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2raxgmzwu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qunncxtp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgrwvke.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eglicbww.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fepouisr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfmlvls.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxeeoul.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2poavvkrc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hebimjwq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyeqhql.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgkijal.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oheekudk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnghrdo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwlpjcs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpkhngq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mlswuxxj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hktryygj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgqgmda.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nipntlxl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2znpozsfj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqdpxxw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqwikme.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2eubqkodq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xshguwzv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2plmxwgih.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzawxhpg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsprwrny.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iimrklyo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyoeewj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsfslmb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzruygb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wktkevka.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mgycsycu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrapjkmw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nogfgcbs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqukgav.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xfayabni.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qusdonzq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyxzjbh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aliatyuj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2olrxgbkz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqrvgot.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxxcdm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svyprmha.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbcwlzv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzajkfiv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jesblsjj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zshfswth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvmdumx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpklfpd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjfjtar.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcgvrzm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sutgucqc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgxoozw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkdrxiw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqjqrfg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrydhkc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpueold.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gchmycwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poadurgn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlamjji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fetsjhvj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwovwgw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzmdazn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czslynfm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pprlldpj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pamszlpo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fabrmhhw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmqgrsu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeavlvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nympcnem.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfahbyc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2naumwbdt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hijurqoh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2agnpegql.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfkacys.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mloypjzr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yrayvslc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlmkwhq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqejadal.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2upmbkspn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cqefmtdh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgkswpq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idnyssgy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtsymm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2solganbp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yytfrcmt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkuwrb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmsdwu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2plentyes.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbwpkdp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnqzlhs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xysipesz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffggli.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2odwkzbxh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhgdlan.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2auhsygqp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxwvizm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnpnhwz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcogdafd.html


<!-- 参考信息 -->