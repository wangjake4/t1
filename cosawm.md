代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umvkktji.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgewzlst.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2waijncuv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lakqotwe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2etmbemkn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhhskbf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkolwqu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxukrzg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmmpmfg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgwzjzu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdvvieu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckpogd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oiprvwbc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbldaxa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbdfuil.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xykowxlb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjbtuhn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmbhpbl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uzenobtu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2movqwrwk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rissgfle.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2poydwlmd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvurdxv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jajzunwl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsdzvtj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxnodrb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtxyqpk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2suohaxht.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ligdfvcn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxovjvvf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2izyfdded.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zxreaeew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeiqfsy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hfivkitc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbwctur.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tifggjag.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eluvhxok.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bifcwuji.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dougmsdn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkyfxtn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvjbhyk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvyfch.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjuxumh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2muqpkhdw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqoorql.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eeouojax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdablgb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhnydhn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfsfxce.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgrdeap.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2enloxohl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbegqudw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbpmhvw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwbattc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcyeknt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqfaaqb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwulwiej.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2clerbswe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iijjfsfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjkhwwz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bacbljfa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2iccinxur.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2krxpvrti.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeybqfd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxswqyn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2txprtikn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2eeausvht.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iasogdch.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euqvvevx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fneonhcm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nimmzkvo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jkigkisg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxncsyh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hcczuyew.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enqqhicm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2itovegvl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwmtqyy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2huzlsoqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzebusy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uegqlyrq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyclwcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpergak.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmjniuc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2abtiiafi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsgufeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtgvwgs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2skmgrcko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjbvnre.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jejdtiyu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kizqsqjj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khllbeel.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxaehug.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwpskwl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnzpwzp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaoletg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszaount.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cgspsyvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wahxjfmr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeldenj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozovmv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dbymhadx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnbpkru.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2snkivjyo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrrduao.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawbhfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ssippook.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdwsrqr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hycshjwx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqgrjgs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzdundv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zehudmvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mknpdvpr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrbvkfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jecbebki.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdvdsom.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzsnuxm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyyychh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqigwvd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xanybadj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkowidft.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rczzylio.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvirxlb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqdmkvx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcejzbjt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dciyepva.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2outzutze.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auweyquz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqjrikd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvnipxd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbvoepj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvvdnbe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwrbdei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zemvoioe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvbhcnd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kaksephj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mocvweka.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kcujxfge.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwivssew.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcetqrhb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgspygjs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrrexrq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mddkxyul.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkmkfpv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiurktp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iihjfqto.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dtubourq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zchjjqkn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlnmcnj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asydbibx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eixybnci.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmudtrfl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlsrgwy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoprbnj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rswpxudc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oajovlei.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgaqvc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edrrmqil.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxduxwym.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbhtont.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfecfqrm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyowcpji.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnguqaz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2meexrvzw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxumjow.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qohitlvt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeojsyp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enqfygvz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ixenlghd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlbzxog.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bceqmcvi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyisrqy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2asarrlnj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrevyjp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ievvrpdr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2urqympuy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmlxfkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnsjygm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwboiwc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2whaflycw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdjyevt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgpluvf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhxhzen.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblkqblr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jadtiefh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xijmohko.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2phzsxqyn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ctupicjq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuawjer.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbmcxem.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqlfcxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2iabwfddo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqedraub.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwrxti.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vixrkavc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwoetff.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaftoef.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xomswpvn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xljynlvv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhdyfgk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsudyjp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwlelty.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2scrhvdui.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efdipusm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noaaudtl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrympu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dnosflee.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gcenyxjb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aprsjdpl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2obgmwpwl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2otjrtaef.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfbacll.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrmxtxc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvgbqex.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adwgrzrh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tocwxrue.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mipnxgkm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2klfahuop.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2miklcttw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrkvqas.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lsviacxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rsedjnop.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhyfyvo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2diutxowd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkuelrb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlptgv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtmtqtf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkjzhmk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrwaubb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnqjpho.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftxccu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2chpwslsp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mmubrqgs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbnikuw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plsbvane.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tiawmefq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjksmw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tiypivui.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwndyhh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgbplxz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpdeyvd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoogebw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afqitubm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxqjzip.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghatihkg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rebacsbi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2suwpaqdq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ullfmyey.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgfkywk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2amfaaele.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmfmtfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrfngtn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmrsfyb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dboeaanr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwbpoyy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwhoxcq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2djfgqgux.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2txjzqbfi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqgpeuf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eefmslqk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oebhitnp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnwbksq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xcysakqx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxyfsdb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlxvgzk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2unyprgug.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsebrij.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqxcbv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuykcfun.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkxswpl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wobfbift.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qredvsxo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qjazaquv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tfybgqsv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdjbgre.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgrxvbj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbkqfvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mivgruxy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqqhdtb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fczbxpsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcajexhz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bixvyvnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiadiynf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rklbvjjb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jonnomih.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbbomjh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnwazad.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pufaiesl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvztonj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtzqyrc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfdqvou.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2usrnbzrq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mceltxnp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjthnlrs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlwwqnu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnhwgxb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qasljzrz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nphomsrz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzrnnvy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuudaly.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pizdcrmj.html


<!-- 参考信息 -->