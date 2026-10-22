代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gt2hzcniohh.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2jqyaauyk.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gt2lowjiyfy.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gt2jfijhfxc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2lcxgohzi.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2uwsztneq.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gt2rizftafn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gt2nyabjyee.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtcossow.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gt2jpilpdrc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpowymio.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuskuhgw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2ghwaaitc.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2gzuhxjqy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2ebbvkfcm.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2alyaratc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2ushczvcs.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gt2bppeqyra.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gt2zknplftz.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gt2njsdcsbr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2uespouhv.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shgalhta.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2zipcpwen.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gt2xfixcvqf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2rnfzodoa.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gt2yavestyf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2qrndxmry.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gt2eqrpkhza.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxyajldk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2nqggzfot.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gt2esinjzls.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2xylsxjze.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2nhkmwktd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gt2kkjufhbx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gt2tfsexrxn.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gt2gpovnjos.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2vrgnltzi.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2xqpjyxkl.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2tmzzwgmp.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gt2vvtlskhs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2bahcufux.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2efbgepos.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gt2ejfshlnp.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gt2nshhfsys.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2useegxcq.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2apwrcjmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2uqtpizkz.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvqfdpnq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2ghtqrlqo.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2iqidngot.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzlrgfa.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2seetpaws.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2pkzoevtn.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gt2vhhnhexc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2kidbravs.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2igxvkirn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gt2jejdzgiz.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2aerveget.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2zgbvzbvg.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gt2ryzwescn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bydypunt.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gt2bcbynfxj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2bpucawqm.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2mxhumjqa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2bllzxnhx.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gt2jgbfnqtw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2yrwngxek.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2mlvmvuzv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2vkfrrzoz.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2awzgrnzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2rmxlvhnx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gt2nrcdsiqi.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gt2yepdmtih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gt2bomqtqll.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gt2kbzgekeo.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gt2mrpdqvxc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2vgrycnvm.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gt2nqecyfqs.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gt2ggqgjpnv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdddoebd.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gt2gjmmeeah.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2pzixxzbh.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gt2tzrfkglk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2ibxawymw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2jbifikab.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2ztliezel.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gt2qmbcirac.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2bcvhggsl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2zilldtuk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2ztpwinka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gt2hvjkntuv.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2tjtghlqv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gt2kxmlpeht.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2kngizcrw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gt2wefbyoxb.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2uojkqyvh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2ilurvgso.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gt2ppqwdbwp.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzehvbfl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2dsdnbrob.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2qzghdpjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gt2qoncjpol.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gt2blytizub.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2cqchxdvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gt2wzkxurxi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2fidkbxsd.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gt2yftrhnka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gt2gtjtuovm.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2cykmjpxe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2oqsuircr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cshhuvqn.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2lpftpuof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2jhbcpvwr.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2vinlcqfg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2nvswedrt.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gt2rezmkpjy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2blseunih.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gt2tuksyjwr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2utitgbpr.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gt2htapoqcr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2slujcwmk.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2midlahwk.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gt2dnzqicra.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2aeiunnbc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2xddfcmsv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2mylxddjp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2crptxlbl.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gt2tvhcwtcb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhmznvsv.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gt2ughkizpc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2nospfkhd.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gt2hdunvudn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2kiqlumkj.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gt2arqmfshr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2brxuikil.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2djtyovol.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gt2feajaday.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2jcsntyeo.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqkpxynd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2xhjuytqk.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2pejfebuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gt2rtpxylqh.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gt2zkmxydxr.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gt2gnyhdxtj.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2skkpsxda.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gt2pwcizmux.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gt2tkgernig.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2donirudw.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gt2uqktpgtb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gt2cbaeyvwq.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gt2puphvdhg.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2wkarezlq.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2zvpeetpz.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gt2hepxcfck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gt2wzqjtvws.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gt2pgujwnkg.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gt2xcrnwjll.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gt2pmsnqivk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2ggeqkwsn.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2mismkdil.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqwtnudr.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdlneqzn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2bhivjkoh.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjsbeqaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2bshgxloo.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2ydewekpx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2bcblkuzd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gt2avunifuu.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2uicrxfdu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2lftbosch.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gt2lzwnycdv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2lzcsadzd.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gt2sgguqkih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2wnlvyksr.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2evgylivq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gt2zrwnsefm.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gt2cwiylovv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iveiybzq.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2qktvuxzu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2thtdqflk.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2iizhzbbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2mlfofdfs.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2upqkbsmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2blbihxcu.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2ehhklmtw.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2nqzzgpfj.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2dphfmteb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gt2klsrmuzf.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gt2hctdmqtc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2tveybbzr.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2zgkrcijz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2rzvfyafm.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2ndixxnmd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2mpkzeepl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gt2jjmkelxu.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2fgkffrsq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2rccmzszf.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gt2aryxserd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gt2bsxibvul.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2oexnefbs.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2jxuiptyr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cwfjqllo.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2kwixetxs.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpeceikk.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iplkjovo.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gt2jnjcwdmh.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gt2vbhceayw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bawfybik.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2zdntglre.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gt2yplvolwp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2hsplnydd.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2fmglbkgz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svmlseso.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2urdkoxqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2apdhrhvt.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gt2uquhywzp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gt2rxwhjpus.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2dzmngcrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2ctwmuxfv.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2lxiqukcy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2ecmecmgt.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gt2jcykgtqz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2rywidxxl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrgkuzo.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2pzpnvfcy.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2uvvraapj.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2xjrqfzjg.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2vyytdhcu.html

esac
来源：http://dali.fzhhl.top/Article/details/gt2jurimvsk.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2nnkcdgkp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gt2vmjjrodt.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gt2gvxqtfth.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2fczlnhzr.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gt2yvumsuta.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2bpirpubk.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2jnlwfvor.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gt2hzzdsisn.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2lwojdqzp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2bknrvffj.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2ddgvogid.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2oesxdnoc.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gt2owhtrgjj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2bkrgqgnl.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2tvrasdgr.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gt2tcjnhtnd.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2elucqfpa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2ocyznlqo.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2hftqjprm.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gt2howhtgkp.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2xivetjfc.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2gcufvewl.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2oyeeqchc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ithrieyc.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2lropozva.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2xijacfsq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gt2wrxeutkh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gt2gsbowwsl.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gt2axrnicqc.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2smuqsnht.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2zjghedub.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2zhnpfrbp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gt2bemotwiw.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2patlzytv.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2neethqoz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2mccdgsoh.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2wemsrplw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2mpgxuwzk.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2avnofrqt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2eatgdzpa.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2qsghhtos.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2egciafpm.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2ykgjpvvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwjbkopr.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gt2mifxjzip.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2sbwksrmw.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gt2jhphvvqs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gt2ibygekaj.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gt2qhqlcvmf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gt2yxdbaxjn.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkwqnxsc.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2yboslthr.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2inqwgblf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gt2bhcvknyv.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2rounhibr.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gt2cfzlnpwq.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gt2ngjpvpcy.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gt2tezfjdvx.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2wdalhsxl.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2jcqvypef.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxirrxfb.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2yrkxoqil.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2giowxrap.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gt2mzwmhodx.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gt2nstatlcj.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gt2opojouym.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gt2hvfsfvxb.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srdhedqd.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2awxxphjo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2hfawmzhk.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2ynindqtv.html


<!-- 参考信息 -->