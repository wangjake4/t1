代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iyllyyug.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonzykdd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eptcgpla.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pypacscb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2addxxxxz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobolsd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2htdiulvh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2athumxgy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2raeqizfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2isikvbby.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsmkhoq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nynjafmh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaykgri.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2auouifjh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoiumnv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpcpbak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fysyqaaa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2grgfgvnm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcyxncl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aetjwsde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqombo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdddidt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vezonhfs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrnnfag.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dayjkhjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgsafxb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjmgxzt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqohscr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfngcig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkvqiiz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acpvitcx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhaxtdq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrymjwiu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxwlyuh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdelkcba.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wecrwetm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjftpgo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeaptjp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnprgse.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2puwwqgwy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrtdpsj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sttzfsci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgucwta.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2valhtofs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnvooer.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qarkbhnp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxubyquo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtswukoz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2njftrmmb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nerrlclq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmyvizi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlgmstc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atyuzdxv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbuywtc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itmlswca.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hansmpyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qykadxbv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbliifjm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabamxg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2puxtyhhm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kmartnwu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqxxfyb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrvlnnd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2diqvwtrv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnynzfah.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsywgjb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqpshh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruthtpyo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aibaazbz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2henlculx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2almdgatf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzurfaih.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gidpgecb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuuehhv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgrptto.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opukqclv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewsnnb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuutccd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuelquox.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2djskqxpt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjcnqtb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrftzfk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2brdejlqs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vhogsibu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsjlefk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhtwudr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlefarox.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjpxnyr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnzxxca.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmaybka.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nchphkrw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fldugaom.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2umybvddx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlyjibu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2plubupzg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2epmkurbd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yekmdadq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhooaxmv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqqdegy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2plsblqpn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpbifff.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdsjmvh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrvfrhc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzdeshh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmhjvqu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyapedem.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hycotxmr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tednhozf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2seeapxad.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdpohi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rufcbnpp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjwxwoj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ikevlype.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fiivetjb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2noboucrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbvkriv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2twssyazm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoakehq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfekvgw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gghooshq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrkehzm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrfuajf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnhbcll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aexomupv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wsswkpdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyveyuyo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcfczxl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fftpqnxh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsmrzlu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2czutyryu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqmmzy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcgcdkf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffulce.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnvnypv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeikhxs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gaszsuql.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abnnfofj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxcqvsi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygsyicj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anpnucgo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmxxxit.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2forunrou.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2noopqlcr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2roonxyqp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bosqzswd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaudckm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpmjexv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqoxqup.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wablrbeh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxzvekg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wewwqgls.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtcppek.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcmsvkx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfstuacu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfxvmsm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pokozbxx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuaytga.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xybtwcac.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tctmqcpn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqvdrah.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gisqqgxw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nltyvdjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhscnw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaeghhx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcynfqta.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umsirriv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egbvmvib.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zoltqrsr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klhogglp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntczgvtg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnyvewq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whxhlhyw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjcrhfq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxprelqz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsjgjmw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qymcqgvk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2syluqrvc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oedmclbc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfljkbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzobii.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqilxsjo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qafknpal.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2noheonlk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjswih.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwsremg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuvuaif.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbejnek.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2embxacnx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpazhze.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxrrodi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oumhiaqw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmywwofe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaupqat.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqdggb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klxciwez.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2otegefvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzmdawg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpvrniu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emyaodvp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqckpb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjpqgwu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kakfeokz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nptuzqvs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srewrwib.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubmnkmr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2arunqimd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjmiwe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxcfszc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mafosvfo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oinkgffl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbrsbwb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvpkcbk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjawaz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zrudajqi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzjvmt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgmzble.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbsepng.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqibiay.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcehhzj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bukukvtb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vmspykbc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaekjpx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fsofdfqx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlskjn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2baxopece.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvedtlf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvdrbkd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2saewnyxn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaoplna.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbdcak.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vemiffvx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaurzbb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuffdab.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbdgbxc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esyflodb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjzgitl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wekgwdra.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoodiiw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzlhaht.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2udrndcev.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uwttoevt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcidygx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fesdwnlt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbbedh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2httaeirt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoyjbtn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwwedfi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvcqgk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdkaqwk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnftzyu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2phrdysku.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsughug.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdukrvn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yambsddy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xkunacty.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrpeojf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zafseuco.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbbaty.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hembmxoz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmbcvot.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgthyjl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iacjyvpp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tpobgikx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2goqylcjj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cafojkiy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbbkjb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pagqhmyh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2htnvuwxk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rinckcwz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2twtkndpj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2papqkyio.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoppcrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhierory.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2icfficic.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjqhhun.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxxjkrn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2acpszkxn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2estcvvel.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eouzchkm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2guadcnjw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgdrdaj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcoftjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwvrbah.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jojmqkys.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2srowxrpd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpakame.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkjepwg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nvflwpap.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrodnll.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqhsyxy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcemthc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmgiblw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zjisvgdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igqyvpph.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjsawly.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2odooaugk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkufdja.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lofcurby.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2alwudeht.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rojqpwib.html


<!-- 参考信息 -->