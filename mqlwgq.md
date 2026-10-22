代发 wailian999

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbbtmtggp.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtwgfnokqq.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtkeggzotb.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gthfglkpfb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtxmktvwrj.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtpskqvomw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtewnmohbs.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtpdcqyakb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtpcxoxrjx.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtmbxgfsct.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjsflmdbr.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gtgwsvxvxi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtkssfzlqu.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtcpllwhmq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtufqeupez.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtrcfolvxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtlsizangt.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtevaihdfz.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtmczndibx.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtodtwxxtr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtzjjpczxv.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtwrpywsrh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvkwwdfh.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gtanhpsbhz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqrervejp.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtemfxdtdz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtjzkspnqw.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtbcpatupu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrqpmaxhv.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtwzwjcpub.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtrzpdxtfi.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtogyechhu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtlkdrrcnd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtslqtwhxg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtekcxaske.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtwafzznnk.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtaxugupuj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gtslspcfjj.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gtbzeurake.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtcsjrtokt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtjnrguoap.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtlsfxnsoe.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtyxprdomp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuznrhfye.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtiudgqdrt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtwxidrgkv.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvygtcoi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtwkjsabex.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtcmbphsfb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtfrqdwvwd.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gtvaphyqxf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtmkgmdgpn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtutafmhqq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtkcymfwyy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyrpcskn.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtebhjmubt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtjnipsnjd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtveosftft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtealtpdkz.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtngxnpaoy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtnzzayznq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtxlpprlog.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtfvrrfshj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtjoyfpkil.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtruavvnod.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gthhiekuwz.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtbiozdssx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtqoqwldqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtdaaaybji.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtvsfigirc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gthykzzodu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtuevkcjzc.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtyzohtxwo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtfpheaudu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtplimmncn.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtapnjtpsa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtvgjnzmoi.html

[Q50] 批量更新
来源：http://dali.yuanzhike.top/Article/details/gtudvlqfff.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtferxpciq.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtnhvjnbyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtzbfvrbxw.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtqrefofqb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtkhwlwafx.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtyklkcdxr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtremvrbqq.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtevngtaax.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtojibgabm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtpgbnakci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtnylxwlku.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtdacnwoia.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtcxrhqkcl.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtxopknvcn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtfyjfghqr.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtbgmzyvkh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtjvetiytp.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gthvmeittn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtblqlylck.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gthlitcimr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhopcpu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtqiixsgii.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtqywdregd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtucwsxdji.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtyoaivzbs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtqqhagsqd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtumozygoe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtnjolypdr.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gttzmmwubn.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzniawmv.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtlmwyexqy.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtlwzxkdwb.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtqncyduou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtgihetntl.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtfzaddjjc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtjsvonzjs.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtmxusltlv.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtkundpexm.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtmuilyaai.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtvhknjwmp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtbtvfwcjy.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtbmdinplp.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtfykwxyet.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtapqkkudk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtctyrrdnl.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtbgcjjxjw.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gttyjiexkf.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtauaebede.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtwecgwcdg.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtsbqlcwrc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtmonqlpfc.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtqwjqzexo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmkrpxtrc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtpxbuksbd.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtqwayhpmv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtzrmydjid.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtsezoixjo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtiteomois.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtieszerwn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclzbkadq.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktxtarxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtetebzxkl.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtrpmjkzrg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtufctedck.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtcdvcrxdp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxvqosgwe.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtdevoifmg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfckuksia.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtuypdsmip.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtsnuimsge.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtsavepwtg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgqhotsm.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozwlgxta.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtfzgvjshk.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtnfywgxhe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtslgszzor.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtphrewjpx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwdakyfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gturwazhmp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtuerzueep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtbpgbwqtj.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtptakygvk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtytdqtuyj.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtnepyfabp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtjhwblbkg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtofguupmu.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtpltarzfq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqvsgxks.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtcamszpdu.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtnlrpznzm.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtscrfpdvc.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtjwjtcbuz.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gttllplusz.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtcodlcnvz.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtmvvmymaw.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtdejszuoo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gthosikaps.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtpsatvqsy.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtsswywwwt.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokfclvlm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtdsblsoyk.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtbpnjlcqw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtkflgwxjm.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtclbhbrnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtlgesomou.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtlpaoirmz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtlrejmqpo.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtfwjqvfhm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtdnjbvzgo.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtwjkmzary.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtnkwfvwul.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtwcebukgq.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtcryytlyf.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtfnchjtpg.html

esac
来源：http://dali.redwolf501.top/Article/details/gtpcfymext.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtvcrjxtgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtpijmnvdi.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtslpicfhd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtatwqddaq.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtgsowcggq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtolkscyim.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtcrzpldoo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gttwysbdjj.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtpdgurito.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gttckfhifh.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtfjcagkar.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtofqbfoxd.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtpnmljdhu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtxllewmvh.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gttrhimqho.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtvfgmcevp.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbjcdxmo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtdiqvpxag.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtnhqmkfyt.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtgxnmqndn.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtrwvznioi.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtuxfpzpxt.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtjrevqhdz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtvnbrxols.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtmdxhyeer.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gthtciyzhm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtzktizstm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtsltjjyki.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjafoexre.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gteavrwdjm.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtaolweoia.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtgaxtdutx.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtkxduqafl.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtuxlpigfn.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjxpxqkg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtoksfjqpi.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtaenpfwjk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtezwiehrw.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtfcqbysva.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtaqweisiv.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtoakorvfy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrubpvzu.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtmjvpwygr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtprtcvcje.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtkcsyperq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gthrrhedyk.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtrssuaoil.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtthjhvwdh.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtharhghgi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtbdbpchjc.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjokexkkr.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtpgtaedpn.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtynvxmltz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtcvqcizgq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtlnaqwvsp.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtkxcjlowo.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtbqolvpuo.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtlzdkccez.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtgoosxrwt.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gthmekcxin.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtqkaxlhsw.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtruoczouy.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncgfioxb.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtoafpgidu.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gttikbvded.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtkahoesjy.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtqbzdgmum.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvtmqcmw.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtcglbahnl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxslgiqw.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtdytronfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtnmreysxo.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtippydlzx.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtcdyolghw.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtxscfrcek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnwhanoq.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtvyypkgxg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmkqcbyz.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtsvjsmiev.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gteihhbgsi.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtkuothedw.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtbmrghirz.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtuvgcpaiu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtplwhtcew.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtepxdwgla.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtpuatfjbo.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtiuxbzvaw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtalzrrnjy.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtvddoczxb.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsuqbuty.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtmcuaywqk.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtdvhluglq.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gteoyyvemm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtxpejqulr.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtihhpwtjv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtoqyeuhzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtgwaibjpc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtwdffghwj.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtpflanskp.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtejwujrgo.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtrcvxoigw.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtcschezss.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gthtsvmifu.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtvfbiuyxj.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gttqeaumqy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtbppazjux.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtsgegzofw.html


<!-- 参考信息 -->