代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2mbzxlltb.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2ravcmsvp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifywmcgt.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2vfbnfrzu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2mzfnfvxy.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzbjquug.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2eqxovpcp.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2wpecchby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2hndbjlrx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gt2mvolhdll.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2xormtxai.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2boqnlbnd.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gt2zxkxafgm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2tmlgmxvg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gt2ruddbdki.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gt2dcacvioo.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ejxyevbb.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2mcdleudz.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2vmzbaoli.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2lghbfqao.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2ldrehihh.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvoincyd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2eygheumw.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqmlxcdq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2dngonfiz.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2umnjjkjw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2kiuigyrv.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gt2pyqlpvvp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2iieuvteb.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2bmqmjlwl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2hhevyrml.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2uhlujboe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gt2kgpjmxvg.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2rzdqzzoe.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gt2nlipziea.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2esrlmrmp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gt2mdomfidc.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sftxrnmq.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auctchdk.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gt2srrojtaw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ixfbzaos.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gt2mfsvzaeb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2hvnkyaku.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2qofgdfns.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2zqnuasjc.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gt2xeczyunv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2gpilepeu.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gt2bpzqwciv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2nhhhuuus.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2lwilmhzu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2rkkjhtys.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2awtoxkui.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gt2dcsayrjy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2esmlzyaj.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2zscljadv.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjtnicjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gt2zleqlnel.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2ampudcqx.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2xyihdhqp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gt2pmbuwiqa.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2eifezpva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2yepxgxqa.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2rpiphxxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zceizobt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2uuvfwnii.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppbkswib.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gt2tmzrjmpo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2pysxxzul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gt2cgznnfym.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2mcngcees.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gt2prrcxmnd.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gt2peuuakdn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2onpslmqr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gt2vcjgodyt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2utkerqon.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2ywvjlrkb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2ikgpzwhw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2wmvfzxsx.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2ktkbqegu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2oxzyymsn.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2plnlvkrd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2bjiasswb.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gt2xhhjwpto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2etncjymt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2ubgexmsh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2ccsyxtob.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2voircbvl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqhhbfpr.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2qoabaycs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2xksoybko.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2zlaorjmw.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gt2hxxrajsz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhelfuae.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gt2gdsygalv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2azeqsoym.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crkjfovf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2inkcbriv.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgfaycpi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2ziwnitly.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elfeocfp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2xtglcpaw.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2kzqsjkco.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2cjmueqls.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2tsevayvt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2jrmvycre.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2jrceczqi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2allgqlox.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gt2zcrpcntx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zzanclse.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyuwhpsb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ihwoubnn.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2hzpiheoz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2ztucclio.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2hnqpdrrc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gt2cjhzlqbe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2nhcaiqja.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gt2ospxnpco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2ytbyluht.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2itxcvguk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngukieua.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gt2jfzwhpol.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2goikjlqb.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gt2rvfnaocp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooevwezu.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gt2hcadfvng.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2qpegmcml.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gt2ituukxqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pawnkhfv.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2tjtexkag.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gt2bizvwdzw.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2fehytuyl.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gt2pygqcvba.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2khzhqcoz.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2fwaagstq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2oaifigiv.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gt2gxjotdut.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucirxzvo.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcdfdapt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2ysieglkr.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gt2uenlxdsy.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2svudaaey.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2wkfugwwg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2jahzyfab.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2ciwcbcje.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gt2nehtnfcf.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2mrgifyde.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2scipsuja.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gt2anwlttgi.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gt2ufyhykkq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gt2oerdsfbm.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2dhgdgvzv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gt2iqdymyao.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gt2ybbgtykj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2ehxawpno.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2bxangxst.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gt2ckslfnce.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2waeunzji.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2yuescmvs.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2hnnhxdtz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2vcjxiauw.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2xqfmjiak.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qopcqpep.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2alkodpft.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2owwopmey.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2rvkomrfd.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2gkkylqiy.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2mjumdyxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gt2pdnlhuzy.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gt2wcgsfsmr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2uxjkdxrw.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2oocxxzej.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gt2cijgppym.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnkpctki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgeksonx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2emxhxygo.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gt2onphrxzs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2tsmkwtfc.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gt2tgbcfcrz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gt2rmaebcvc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ysvoosej.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2kldgmprq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2naysyvea.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2anhbkizg.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2uokdmfwv.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gt2grdekvuw.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayuyhpde.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktyegmgv.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gt2wxhewezz.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2cmujctal.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gt2bgnyhqpr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovapsuwm.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2rzzjgqhs.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2djepjydd.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2qblnajbm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2vamftowj.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gt2zhrzotiu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2gzjefvgn.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2adnzrsfz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2cikechih.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbunexsu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2lyhiodrg.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gt2ewjyydwi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2kcmpdhqe.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2wsnatlli.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gt2gnaywnvj.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2scrddxkq.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2yapmeffp.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2fnmusxvv.html

esac
来源：http://dali.ydzc1.top/Article/details/gt2vijujwav.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2utrqzdzv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gt2mfmddozz.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2ydicnhds.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2yttxpbfq.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gt2vdjcnnhg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2obomgfbc.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2wwlxmwik.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2inthijjw.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2bmzgkrew.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2tmeoueqv.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2avfuloqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2sdliraxj.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2ykaoubba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2yrzdglgi.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbbzcjig.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmaljcjj.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gt2zxxbbxbb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gt2qwblyhjw.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gt2mklwkvjb.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2fjfttkwm.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2csxdmbft.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ndebmvoe.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2sjshdxxq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbjezzoq.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2kkdgrzbx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gt2gichekxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2qxbntqbm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gt2tihoyzhz.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2jxlcqcdc.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2owhligas.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2wkvjbvmb.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2spquvsvl.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmlsrlil.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2cupzvnun.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2ikkryesq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gt2yosauipf.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2peuohjyt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gt2mebzphjx.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2chzqfuao.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2wmmddfvr.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gt2plwinzqm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2zblcmmfy.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2igoofpyd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2xqflftzq.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2eibfpxxy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zczjogzt.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gt2qljvbeyl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gt2njgpdzlo.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2klysgpjf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gt2roptcgax.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2ohxyydvp.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gt2wvvooaui.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gt2evuoxtam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gt2gcgukcvg.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2iovoewis.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2trneonwq.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2azimdzyr.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gt2ntottncq.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzshbvnw.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2ajbbankv.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gt2avmcwyfk.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2tvwknqqi.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2ewckazmt.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gt2vmdkabad.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gt2zqsbqvyi.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2onrludqz.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2poyakvnh.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2goyuybwc.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2uxsbjgxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2iiizwstq.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gt2qxsvorzo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2spkxplru.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2zszmkknx.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2qxavgsyn.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gt2kvxkdajm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2pcqrqlqs.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gt2dvgapgmr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2pjfsbmga.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2zdnlrpwh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gt2uosojytu.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gt2xbhqqnul.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2qikikimx.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gt2eeaxkiel.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2buepnetq.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gt2vukjlsco.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gt2brusdjxz.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcoiaamr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2rxqbbphe.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2gcprxzeb.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgemydqo.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gt2dngrghph.html


<!-- 参考信息 -->