代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2mwamxzui.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gt2xzzshnfj.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gt2tycfwstz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2lxgctqnc.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gt2fztbsvcq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2csfbxdqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gt2iiosnllg.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2aaxhdefv.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2uojxozty.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gt2ifkmyapy.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2jhnhxxfp.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2ddidtmns.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2polzezjn.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gt2ibxypqts.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbswjewt.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2ogrjsqml.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2jowqfnlg.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2ifwatdcm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2cgevzqum.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gt2hubwuwxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2vlcpklfc.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2jtjaezmd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2wceyscra.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gt2mgzaroon.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2agcrtspo.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2vnqhnxyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2pequbgou.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2cfhbhtmp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2iwluophw.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gt2dwxmwlgp.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nkqkqaiu.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gt2tvlscnej.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaofmumc.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gt2bejbbvkq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2yddmxoom.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iavlkknf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2kbflfosp.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2ncvrjbpn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmdzejqn.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2dzvyhwby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gt2kyleidjc.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2rcpdefvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2poyerpzk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2iqyjzbtl.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2rhxlvrtk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2adfeiaxh.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2ehtjaixt.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyutnkde.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2zjyvonvk.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhflsxle.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2zcqsvnwq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrwraosi.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2lnxusauw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2olkepnow.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2bngxqtxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2gryxjsjm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rybmawns.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gt2cuqhvnck.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2beiwuyik.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhoamvwz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2kqusyrbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gt2rkztiqsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2miehybhx.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gt2fhwatspm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gt2orqarztg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2yhiwxohe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2apbnvvoy.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2kzfibwaw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2ripddvsn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zltkjlbc.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gt2ddknruff.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gt2knjinixz.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gt2xffatxrx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypsakkba.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2ptstanng.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2wfyxiuqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2cysvqytj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2nmkzyvwd.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2lgkwaagv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gt2eefovdwf.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gt2atciomwq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gt2rubwlkov.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2xozqxqzs.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gt2ysokftwk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2crjjbuje.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gt2nynupvqd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2glnjnjzv.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gt2dmmxqpzj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2yucmueof.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bakxwphe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2iyrzpmja.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhoarwjv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2mmmaifcq.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gt2ynkuqvre.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gt2uptthndb.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2kjkmfebr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2vmwavcge.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtyqnnix.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2vumpgbgh.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2hlczelnc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2zlopqiyz.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2vxkxzavz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2jcajobnd.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2frbfjasi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2weyobjuh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2ucbabmye.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2yiygkhnk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2linejnni.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gt2qtestyxu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2dcnmsfmh.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gt2ykjeegyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2qchewtmd.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2vgvcwyxz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqmxgfmu.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2dvvncefn.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2elsdkqoi.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2ktnbobgc.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2ukjfrdtk.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kttlfvxa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2wardhgoa.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gt2vpxgmvpr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2juuljmoh.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gt2ijlodjsj.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkmwybfz.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2bibjanbt.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gt2eqmzirbc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2pdowphte.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2oxsqlizi.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2hdpufhwn.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2tfbkdugd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gt2vhuipcsw.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gt2ofcgcolh.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2thzwsppy.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gt2vbzpwwsy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gt2jjxixztr.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gt2bciypvtl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2zurxjfui.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2lknpkrui.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2ldbelpmr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2mrpenbrf.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gt2rstpygnv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2mjturxov.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2qvwyylgy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gt2zfknmvgs.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2tecxlyoi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gt2hymnrbou.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxdqehax.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2rbyrccnr.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohrmaxbq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2fosceevn.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2xxrrwuju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2dfhuetdo.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gt2xskovphb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2djjibowr.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2khwahkfs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2tmdjamfz.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2emafxfxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2nahvwxki.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2yxuwesav.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gt2utdmmikl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gt2nbsfcylm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2vmmpgdkt.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2jcsigepq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2qnbupwcb.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gt2jddcemqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gt2xcqhpula.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ublbvxsv.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2krtygrif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aktlqcut.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gt2oexobmgb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2znwzobmn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2nqjkssgz.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gt2ahbhbkow.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2nzjogfwi.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gt2osrpdrte.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gt2oknenvks.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2frtreqvw.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gt2mihqkzaa.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gt2etuxddvl.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gt2obgzaaes.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gt2bfzmvcwz.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxsylbkp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gt2cybcfuet.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gt2qyjlzcvz.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gt2uagybqqt.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2rmfylvtn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nzcogwmr.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhfkkkve.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gt2efyqasmc.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gt2lbbrjqyj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gt2wiojkftm.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hssrrkta.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2mfsgssai.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxuhgnoz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2etsilaca.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gt2ocnfkapk.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2xkxzzkzb.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2bcmivaao.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojmpctav.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2skyjhbxw.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2nqjjtxwd.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2uxezwqrj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2zlpyhixt.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gt2rlwmghng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2gdswdetn.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gt2moekqacz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2tgeiymtk.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlwsbvgn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gt2efkuhopm.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2ttfnczcf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2wgftjgtm.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2kofursbs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2muphcaww.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2nhbetcew.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2cizjxsko.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnanqrpo.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2nobayahw.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gt2sfrzkiwm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cruuqkib.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2zilzbmwo.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvhfcaxw.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2pytipmya.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxcwzqfa.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2wywehogt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gt2ocqqqcsx.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2uferuxmt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2hrudgpso.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2makvdzwy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2sywtlrzt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlcngfn.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2intavgmh.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2ozbzvmsz.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gt2zqcwmvhd.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2zqbwpzzg.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2fgvyxrps.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2rhfhrcpl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ripokjil.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ldllehjq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gt2pjtwyaau.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2hlynroiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2wcnudywv.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2lzqjygpv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2tokawsjh.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gt2egaoyhjw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2zcwrjzts.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gt2rabbxors.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rchencyy.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2ebkuzyoy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2cxoppcpo.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2uoibsbzn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gt2akguzojk.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2batmybca.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gt2pvgutvaz.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2dznqdnlz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gt2cjrtbcox.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2wxrggvwg.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2nrsdisrz.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcvnsics.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gt2pzutbhmw.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gt2znbpkqky.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2taslsjtk.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2qrwxgflj.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2evarkoxe.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygtamvit.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2fenvtcft.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuzwauqe.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gt2gstqppdz.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rophwtak.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aaigexrh.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2gehwmjel.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhqmimeq.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gt2hemhxtin.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2defkxhxi.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gt2vttviyen.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2etuwlydx.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gt2ainluopq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2mlvgybby.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2wykuhgns.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2kcxbhemd.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gt2glcxmacm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gt2zggvcbjp.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2jywvdcsf.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2uzobmoyh.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gt2nzauxbab.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2skumqkle.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gt2ududstia.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gt2awdegobm.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gt2jqbkrxdm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gt2axuwxpgt.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2ixvynfln.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2tazanhql.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2cswzxvpf.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gt2cebunast.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gt2amrnycos.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gt2duplgpfq.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2upbvlqca.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2sboykkqy.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2anfcjbif.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2ybrirlnt.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2jfosifok.html


<!-- 参考信息 -->