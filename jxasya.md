代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtqxavanup.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtfoyfvacm.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwampggj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gthicsdlxf.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gticgmesac.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtngmxddgf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyvocnzk.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtbhfhehxh.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtmhldghyl.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gttjojjtkq.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtogbezhxu.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtflzvsege.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gthdvxqkdn.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtwyxcqypq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtihvqfqbg.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gthimsxqno.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtyezlyydd.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtintcjeao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtqbywovqa.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtqptpxrhy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtyeattgvx.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtqcifueze.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtruknfmfa.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtnktcvixj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtdwmhudxc.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtxlspewhl.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmkzzizyn.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gtfdonvdzl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtxrvjwqar.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtfhsvgioz.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gttpdmdnlr.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtvvjoflxv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsbnhslmq.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gthhkephff.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtrcdmlrmu.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwemdwai.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzzczfeue.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtknrfkygc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtebjvhlua.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtmqjovgjf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtdtaaviwq.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gttobhagwh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtrinmnppy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtkqxoewwg.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtsnpyhxvi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtzgrepugm.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppkamazt.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtscnjdlcs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gttufvnvpr.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtogfmsdse.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtvglhqonm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtvwwarhwi.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtygdtwsdd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtciluoetz.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtzstpxess.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtapvcjydc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtpmyzfpcj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtnsojbevu.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllgjaxwt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtsfeaccbg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtnvslbdno.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtwrebchel.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtmtrubotq.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtuzeklajs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gtcnsestgq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtifskubcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtzrmxlrtg.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtezgutbca.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtigiyhhin.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtuuyytvcv.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtopipqrba.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtllvrvbvb.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtvizriabt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtwasdtqcp.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtqkucjtzv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtghqebjfg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtjrapaaff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtmgkchoba.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtxgkwajjh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gttwijfotw.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtenianyic.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtkwitwhsr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtdtlpveii.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gthqbsppva.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcnafmcy.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtwcaoczrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gttgpjqqyj.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtlinfyrpe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtzpemadtl.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtwcycuzcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gttkyxevdh.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gttdrbtnle.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtlvbagcdz.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtrxourqwf.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtkcexcpvb.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gthpxvbcyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtksxuopzp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtvnqceuri.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtzprlqppa.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtlcgjxiet.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtardglsij.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gtybanfato.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtsufnpnbh.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtmiakecgw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtqfxxdzoj.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkgvoqop.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvpymwod.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmgfsmtqb.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtflnorjet.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtrqcyfrif.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtuodbcazg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtcdzohacf.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtoprhyaph.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtyraaoxwg.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtxcxmyvww.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtdcfijxph.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtffkxjnwv.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtdwqqlztg.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtsoxzcbuf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtcjcrawdw.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtbccxcxgi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtveurqfyo.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtezwrppsm.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtthakxasb.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtvxtxbesf.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtqldqexpw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtbgggthla.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtpgnoldch.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtnmcltnap.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtrrbjtglh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplbljaye.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtomxycups.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtfjeobutv.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtdufddhoh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtgkxmlrsx.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtlbddevfq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtonxpknme.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtulcfzlow.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgonbvliq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtxeyecpnr.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtpanxoyzn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtfeksbjqx.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtagfrywvt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtdsfsbdju.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtsjqolmtt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdoeqwrw.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtwwiehanu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbagyvpd.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtwkbivuio.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtfvqlduch.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtsgukmvja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqyegeody.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtprpsamkl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfyrjzdnn.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtnpzmljbv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtlprlwycc.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtnozabudq.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtejdjedzu.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtzdnsbedz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtmmgdtbzt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gttjcpuwrl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbvghimi.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtlsmahesz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtailyrzop.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtwepdpteb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtnawyzvbe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxxzexehk.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtdugnqvtj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtezsljwks.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtjrctefxm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gthkgdqayl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkjzyfxhv.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtvvcpyruj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdbdkjjll.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtgzyaklif.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtjcpndndc.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtkdopsbny.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtowkbejxe.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtnuatxlib.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtlkckajeo.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtwahsrfja.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtkymtqzgm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtzlhtadtd.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtgpadcjfn.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtkgungwum.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtkhdqkjso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtgbqzbjgy.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtjtisujyy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtdnhpmoql.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtmjrmeyuz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtragsjprv.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtxgjacjgl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtxuwxzgtl.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtfjydzssb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtdlqxetif.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtdubfdzre.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtckjfbets.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtacyxrzij.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtqlgrxcfu.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtylspdjrh.html

esac
来源：http://dali.zhixingplan.top/Article/details/gttizxikdi.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtvdpqaaxx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtyhutyjdl.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gthygyaith.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtuynewjiq.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gteqvdobho.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gteevplfgm.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtztriyykk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtlgcjbyyc.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtpoycjxxq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtilcfeprz.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtdnyxpmwh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtrdltzamo.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtnpeheers.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtghxrnbyu.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtfvoucgrd.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtmjjelaxo.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtcgmsajpt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtvlyfrwiy.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtjqqtpulf.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtunnjefhh.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gttrbjmavp.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtranwjicg.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtqgjoxkdp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtyavwfmmt.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtrwyjdpxf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtvplcufct.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtxvbzhjfx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gthkaqlqmo.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtdihucppn.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwmrvxly.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtoqbkenyp.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtdwfhfksb.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtbecmzrln.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtjuuzvwoq.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtplofcuxi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtwuxorzoa.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtuudbfgvd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwllvzxh.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtlzemwxnb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gthvwfdebt.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtufxboaaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtcwsbrnfc.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtscklkoxb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtzivkpzzs.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtoicnzces.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtvnblntpj.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsytdqoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtxftieahf.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtzbqwxtzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtflvgfwnu.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtmbvwctbj.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtizmhynsb.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtqdzkfsec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gteaquayww.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtkszkbqwi.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtwjrxoyin.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtndefawbj.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtusujcxmq.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtghnztgtt.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtrafkwtkf.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfalzpqs.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtxyfmwiko.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gthqtbzyrj.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtqcdgkydl.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtusfzmmin.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtooswdhvx.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtwnlxdxqw.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtqpbnqtrl.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gtwhvnzecq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdaxwbvs.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtuzismdnu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtqkzvyrcx.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtrkxuvtrd.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtsqcrvbdw.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtbnciprmt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtaxzkztyq.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gthlcuzxae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gttudzhlyy.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtsvqtrxaq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtpqnjqgjq.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtjfgdjwlh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtamblpqdh.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtnujblsfs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtimaikkdr.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtpeisbpbi.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtdhatbdxw.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtfrmcxwez.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gteidhsocm.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtkhojthyg.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtopzhlkjn.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtoelfqlwd.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtzapeiogp.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtxbobudxw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtsnjpqgkr.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtgsesmzgq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gteccyokxj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtqibqtfhy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtmhpsxggy.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtlzyibsvb.html


<!-- 参考信息 -->