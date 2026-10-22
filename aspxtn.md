代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfygic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zpowizxn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieevcofl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2quhxlalo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdiainf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmaogxh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qohrtklt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzekxcf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bceuvwdj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsxeqjq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnyhsyf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2llsceorm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fylvfliw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzkzvri.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2athgmksk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyuqwzg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpdnzru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpcgxpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrhtrbj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ffthpjnh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jinyvoev.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvbihvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pckmphdf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxtryh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdqippw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2obwuaipt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wylvxahk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeovkur.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2srnijhru.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsgjwrp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjdlheg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gatnsqip.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyffxml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvanewki.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuqqhgb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bgovxvfo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwfase.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kztmzluo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkihvicz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yptgtlrz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvhbyf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phcmdjab.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpbzhrf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzqlzrt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfeguxp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkixpjvh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vyktbxup.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublcuoww.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfhlypx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvgcnlx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cahtydwr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkundzim.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wialkkud.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2unudkxuu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnurdxu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqhifh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fewaxlda.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocukqaks.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkmblyn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eealkgjb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqqemcw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcndeso.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzuzaqy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vkudwklv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxxhxuc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aztbqxen.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkicvkg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjbnsvw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2saqdsvpd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwugqhi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mibsrfnu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kwryixqt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2igbtusjl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2otkumeab.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2miqpraav.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dllqeldx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dskuxjbt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bijqcjog.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsltgcb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrqdwgv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrizzwa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrtbduo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2inuhiyqf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tswtkidh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yifbyphq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qposctbq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnkrvve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wttezlcb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaqmnsm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpkowtp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cefrvvpk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwivaau.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rkozlvda.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxelorfw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrplfmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nailgdee.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzteojy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ufenkevj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkxjlcq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2updjtrvn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpsbblb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2huutaspo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjvzyrp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2etjudxbi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ciguhaec.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxylae.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnhdnwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2novtpzhu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgzxaga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfzwqcv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2butxlbri.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlciula.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ascmnwmq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuhtmez.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvgqcrh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kywabhea.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjnqrx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tomcsawm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdeldhw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwyswlh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwgndll.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ietturaw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketvpvdx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxgpjrm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaeeiyo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjkicpa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqwatjx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rypahhcm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eilwaqbw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zmehbwky.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qyswbmvf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkitzyq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ktemymmh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmlegpz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxwuqvn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuumqozy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2asuflzgl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gymlsicm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tiufjmgv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2swfxazra.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbatuir.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzaqowt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yztijwzm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxlwzel.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxyhsdh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvgbmb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xurcdpnh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenkrlp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osnssyuq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahluepzm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thqxedpd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzodcjp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaynmmel.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2upixcxel.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyvmxog.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqcubsw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suqtbnob.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxiclt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdbdhba.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tegoicyw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjlgzss.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjlnfjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlrnmth.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2svweptrq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlirizb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxzzbeb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2evpyydsj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxyxxne.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgoezqd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2brkergpa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzwtiva.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2athtzfal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjygvpou.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdetkreb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeqpulu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqinkjet.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrqanwk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgrwbhn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmibsso.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nttaggog.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkwsyqy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qllttwfm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sumoelhe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nskbbclv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqbryeb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jecqzbbw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vetdfspy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgiefpe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zditiwwg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxhyhrz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pzctfasf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbsgmnf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sftrtpzk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pobqrdmq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuvpmpg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfjiyut.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrabmlkv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2feioeqnp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myvvikxe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pszyquye.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qpauxdle.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2coilxakl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnjkdvp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yectigoj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aofiqfhe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2svqmxnkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfhkwvt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2znycmahs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxeouow.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2brwpiloz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wweqqdwd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeaqzaq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjoqywa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awppefhj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxpxqbc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aixodszb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcljxb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gravzcpv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqpgolw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhillog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyuzupd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghofqxey.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbalacr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jfavnjmm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mzskhjol.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2geppmfec.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lyezoodt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mobxrevg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcfrbgf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pexhqxxv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfdyowr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvccsku.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nddtcyzh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkklabfb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkwbois.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeiwvle.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pmprgddm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqeaeuc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgvnxhb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtcaife.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2edasvyeq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvjrkhw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfykklc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kktjqfny.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zozdynaj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkruwilz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ijecrblc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzswsrge.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzspcms.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2puxrprtq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2algzxvta.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dtciyvae.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2huzbrypz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2flmyouzq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmlcnuf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mikmitdi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kunqeodu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2swzjddjl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2riluasag.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbvvvaf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2exycwdix.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjwcjdx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdzadmi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyuppet.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzpjpkb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxawoem.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2glnoijrm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghfuxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sjovxiym.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzsorf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvmxba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iulucpld.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thupsubv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrbhzsq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwvjbkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzuiojw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbghcgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sscewthf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ordpjpas.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwppapq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psrlycag.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrjvfaq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhrvdyd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyxeecz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypelhsep.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmaays.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuctggt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eotqmjzu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjevdmeu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrudkzb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2seodnayh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2erhmmikt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyuxvvz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhmhbuq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmcwwal.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2idvtbsqr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjhbit.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawzppq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsowncj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qznewudp.html


<!-- 参考信息 -->