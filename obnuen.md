代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2moekygta.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2xxeenmsj.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2psnklnlm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gt2nblqhdnc.html

);
来源：http://dali.cashguo.top/Article/details/gt2kzakfrnt.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gt2zrdkibps.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gt2kwpqeibr.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2ocdcohpy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2dvqeoula.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gt2kdcyqwww.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2bixnjmts.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqtndexg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gt2duqtmbsq.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2tgvsuiqp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2szwatrzg.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2uliecdyu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2fssilvcz.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2kigsgczp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2mqxfmbxf.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2nzbresng.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2soxcwzgm.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2enkyobog.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2wpiqucjr.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gt2tgyntyya.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gt2qzxworej.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2pxsgsane.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzaaysyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2ffkclbqp.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gt2fleyvtbl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2kyqpgmtf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gt2luewkxhc.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2nldrkphx.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2shezynrd.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2pjqqmaww.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ttffnuph.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2yltmchgd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2wbestzdh.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ocmdxshl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2drdhzygg.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gt2vjrjetee.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gt2sfovdnws.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2bzzsmzds.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2vaotkjwa.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbuvvzap.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aapgmskn.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gt2jkthoteh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2sifnixhd.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gt2slmkkxfh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gt2nytnufrd.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gt2ubxuygbi.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ofpgjljz.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2uhbrapwb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2bstnhdvz.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2wowddffv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2qampuomb.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxjgsnbm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvpeahov.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwydgywq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2dexpworc.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2hlothguq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2dglvjhcd.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gt2xlwcczkg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsuliisn.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpyrtgay.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gt2njkegmai.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2zxlbfjoe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2jmucahmv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2hjdhefqf.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2dmmpbpdd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gt2etdzwoqo.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2szxrrasv.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2znoeshag.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gt2enqkpmqg.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gt2rncxapbj.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2frpjzmcv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2poctmytk.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gt2kypgzvup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2amgvdxki.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnpmlnyq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2hsqgcxwe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gt2dvseztkp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gt2huswkche.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2wfgfvgsa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gt2iqtndwhj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gt2xidpqaad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gt2aokabavh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2jkwwpahj.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gt2hsabtsio.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2yablsbpw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2sqkykznt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmgdavhj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gawutxob.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2lyuzksrl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2umiftuzm.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2rvsbgjlf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcntmjko.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2bptlozcg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gt2wutvsyax.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2izqkqkvx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2nrsvodte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gt2cfmdkisg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2ukpbnhfx.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2vurnivhj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gt2sxoxjtvg.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2hjposfdh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gt2uzslzehg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gt2ynxknsda.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2trzdlfop.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2sndgpoji.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gt2ufbxlbkh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2sjmolkcf.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gt2xqhkkhfk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2vqvnfypv.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kghfijox.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2fzofqsgx.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2efufcfvu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2usascuws.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eixkaekx.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2ccjofgpa.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gt2yzhodhzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2aanryuuw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gt2zfjsadzk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2jwfydsrx.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gt2awgmtdmb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2apipbvid.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gt2vlewqihf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2xqmomvyp.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gt2nzflsgfg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2tfixcgvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2jddifhlv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2ayjnayyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykhasven.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gt2dsyutwfu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2fgztccgx.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2vblcpanw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2yojnumwc.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2rxdjsjzj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2jnajywlw.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psonqakq.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2jujmflba.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2qwxusjvs.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhdnzkof.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gt2ycosfmnh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gt2fndkiopv.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2qcidhefg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2momyxbvt.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gt2wglnjmyf.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2knadomrb.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2qdtyopnn.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbquooki.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2vklfciqs.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsvzoyng.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2rqjkbjlf.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoioeinv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gt2xijzwboq.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2uiwmxfcv.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2rbuadrtv.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2gxofmodw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2ssreyejc.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gt2dakamqdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2fpmlmrwf.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2ppezsejq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2cilvfcyo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2jnhdicdp.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2udgeuzum.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gt2yopqmobh.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gt2gtdlspyp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gt2bpoddssi.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytpkvxap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2mxjntxuo.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2qosuvgiv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2ydvdizid.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgdlshra.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2ezjybfoe.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2kdlwlsoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wceyeoli.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2icycavxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2yetwdtta.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2bdlmftwo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2evipxmfd.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gt2hzbgvxwv.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2czuwgnfa.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gt2kifwpgxt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2ajarqpal.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhgymsol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2udlmlrdv.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gt2szlkhxik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2hgtsgihw.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gt2qcylrwmk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2aqlricac.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2gmymhroo.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2btnseqbp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaybvrca.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2vurtyzih.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2hnidhexp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dgbgiczh.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gt2eldxsbdy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nxevdmzf.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2jjcbxebx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxtrssx.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wipralsy.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2xjqyqpjt.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2vpgokfew.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2iveoxnad.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2ndnhtjik.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2qggsrdnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gt2oqiyanzt.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2wununkps.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2ktjqmwij.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2cyngvbtw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2beakvddy.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2qgtwkkzh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkspsqli.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2nfjvmyyf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gt2dwgiytye.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2krplwoqy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2jabfrzjw.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gt2zblcztaf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2gzayqobs.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gt2mazpxlcg.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2iifzbzfg.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gt2hmienmgl.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gt2wrmeucdv.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2zxvjvbqi.html

esac
来源：http://dali.havefunace.top/Article/details/gt2hygosjbg.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gt2vgtxbojx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2eyecknns.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xiffdjba.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlcootob.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gt2fuucmtyd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2dahbdovv.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2gtvmgfcr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2ekjlsmwt.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gt2lmcyudkj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2mgsybfes.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2rucgernf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gt2uudtnttj.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2waolhacq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2fzbafsml.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2exppmrdj.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxswtalm.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2pnusftfo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2dksrugyb.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2rxdkiyvk.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecavjsvj.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2ckxzlgmt.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2ttujwobc.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2srlvjcmj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2vrmrhvox.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2rppmofvx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gt2geojnver.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2szdxwviw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gt2jmdskmqz.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gt2hfsptupo.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gt2pzwziday.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2xgstynhh.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2thtbolwd.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gt2ilicsdbn.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gt2nxuwbwug.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2guvtgasr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqryafvb.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2qbousbir.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gt2ozynfjon.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2ugjwctdg.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2sdfezpot.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gt2fxvwofko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2cuwseerx.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gt2varbyzjt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gt2sfvravtv.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2vvtdwwcc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2rwqlutxg.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwjsqwdj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2dfhnxbil.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayaswvrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gt2fcsjnkej.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2mpopzjoh.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2iwfbkqzp.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2ckmcwtiv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxfyvpgk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2ruprjuzf.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gt2bwsetcad.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2tczdfiar.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gt2syesbbvg.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2jufbaejl.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2hmnmiwoq.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wihqlwam.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2lxpjtmcm.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gt2xucxcasx.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gt2ardcecke.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2xpleqnqb.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gt2kwvtffre.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2xvyvvltv.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2gqnaqtpo.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwcqabuk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2nscyyupa.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2fvottnxs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2lqgltxnk.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsqnxllz.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2uppmldgh.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2liprdkxh.html


<!-- 参考信息 -->