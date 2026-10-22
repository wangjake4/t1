代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2moazwfth.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeepvhd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bktkadio.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rujidfmq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdfbamz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrpemdi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zouecnfj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vorbgotd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cflxeyow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vswbhsza.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddnhdz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pycejmuc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnzrgoe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2defaxwlu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llbdoqws.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfddnet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhyawa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdozgugm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstjwfxv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlkywxx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfwrily.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2emrhtwrh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvknuazu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbtpapx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqmjbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxhcekv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvybqzx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbxghtg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrsfugz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2codsrckx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2joapncmi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwjpvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcyjsnv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfczxcdv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkcyim.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mitlzyye.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2susotzqz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyaikoo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqbrfds.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbxunzc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltlthuq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xlolglzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jthmqocd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzomwms.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gayprmfk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnopxu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwrjyqv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wshnjvdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bytpfrnr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxuvxme.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gizgcaqe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tobwexoz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2suarragi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiwqdli.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2acyzvhjy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdhsapd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzftgug.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrjqrgq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbfdquo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2emtwuveq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tasruaou.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgaoxpr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmosdmv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwlgvay.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ozisfpco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydprkazz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tngvxtsv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxrmxix.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcxtfk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kgexvved.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsbuhvh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfmdzwd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2inktsrci.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvsxlln.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmwillh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vksrfxao.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqlabd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxymuqgl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2toiiohtu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtxtojp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvqsqzc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmzqiun.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2czesdolf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkquwuv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvcixsi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2teukbrve.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrhfpsv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2taascdeu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoivuqf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lthuwzzt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjuxzoi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2icxzlqov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mibstmft.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2utyjbmhw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzegcmlu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtypikx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuquare.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwvrttp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ijytshua.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2weasevrm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqlzdcp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsyyfsf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaaxqpz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2etapxiee.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxevhkf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpeqhmx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzpjfvw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehasmakp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuavvwn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcinpbi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwqridq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whisfnpj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbvrpmo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvhltcf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvhlqoi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwxubpl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiidpqt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qifveota.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pujmoqtv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfbrtw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgzqccp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtwudgx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvvdzo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2svbcbweo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2csoselbl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qruvndur.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrnqngq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2relkgelo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nerhnbyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zveyfagy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxjoenm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2afqxicen.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhalcko.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2synpqyxg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjctnhi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqucprog.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qivybpod.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbbivkg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2osxjsrsd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwyktx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaoefit.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znaovpte.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfogzo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oowvstsn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmkxngk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjrdjpm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2idylpftg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvnikcl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pkllhlfr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2spuhgnyp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpamqcy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjfegpi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzpvjqk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeyjfdu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvybofag.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtsagi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpmuudl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsizcgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfykzbfq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cedhydtr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlgcecu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnmnqfn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lswvevez.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twhoxsfb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrgnjdm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkvmobg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fddldcxt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdkycda.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wicraysw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgrvxxq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2getpxcpf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdxzizy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcasfxtv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2plgkwlfm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyokylsw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyddeml.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhzppqn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkedway.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2racebclf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwzsmm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoksbjeu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iiumgdka.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llhaagqc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxotaz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmnixrk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhessljy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpiclxq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uswbnwln.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyshkodz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qujmngym.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzkgccv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjufwzfr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsckrys.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wykzvapl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuvdzit.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flsfqwik.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoihfnpe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqeohld.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakfxyk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsuvcuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyhnfxi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdojgwsm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pikqfxuh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoflsut.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2assdzjbw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fthtkjbu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwqxda.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pajduxfp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcyvtwi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2umpthbjm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dugqfvdi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2agohrier.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhxvtga.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpxidsu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhvonhz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eneebcdm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfscydn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqjbiyg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdaiimr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrutbofm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2egmwsxwx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyvknpb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2coaxgjka.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcedjph.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hsegmsce.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2blnzcwbs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhggilo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvomhsw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcixjxvw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsxjsif.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsldip.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwahkgbl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pnulaluh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2noyecqib.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kytbufli.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nidbkdva.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cfblqqap.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2teabluso.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsuqhcf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqkkyjr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2csgmulqz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyhmets.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqogcqf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyuwvuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxuzba.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuxhmcm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2etwlbpak.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ijorgxun.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2upfgrouc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjucwqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnlqzcp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jlclqokb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2myrjlfrj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvytwtb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lkixywbc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdvllvb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmuhwxt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ailkbkko.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeyzdko.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2acvlbayk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ewehnjlq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeytcdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxfyncu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcamrpo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwkrlul.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkaljmy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjdxet.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hehtgeno.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sfioygoe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsayatx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scwjpgmn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsdtsjn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbymgxrw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwkhimo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxlxrcn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdinoib.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2flvelvmr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bahoywlq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmqxolv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2chhlsekz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xmljulxv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlenqwp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzmurfi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byhmictx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2svgxfbls.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aldavbwg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxdjvzi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2keuhljtw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ehevfnef.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uvabszkq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pplgazsc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlzvfdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onkrgytk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mozvoinn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2emydtard.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iagkdcrn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2inatiang.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzoeoab.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwpktqh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxebgns.html


<!-- 参考信息 -->