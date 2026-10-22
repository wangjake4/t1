代发 wailian999

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2foffexqm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2dxzkisyo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xvdfdawg.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gt2tjxxuhob.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gt2jjeidqoi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2wnhoznne.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2uchgynte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2esizchaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gt2bmlnmtjh.html

);
来源：http://dali.cucudq.cn/Article/details/gt2lvhvelxg.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gt2xyllgvsl.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gt2jbwidisz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2rnbxzsgs.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyplnzbb.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gt2cdwegcqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gt2iggyxxjd.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2uaxmsjxf.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjkyxpyk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2xfaotmql.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gt2akzqkhpk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2qzyvajby.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2yofgpsrw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuoxcxam.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gt2revjbkhw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gt2pohxkyzw.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2qhinpwcx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnmxuzuj.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2csyfwhlz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxpturmx.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2tzjajxku.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2juyxyejq.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2noxjgjqm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2tyfobegm.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gt2qqxhpyrp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2vdrloxrl.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2adililgs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2jihatito.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gt2xtzzdsil.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edtlogks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghmncwzf.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2pmzeiaia.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gt2kldzrnvy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2lgznwkfx.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gt2zfkjwgbz.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2erfqrhvx.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsbihxhp.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mxficjcj.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2wzxssxva.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gt2vpyemleo.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gt2grfwxvlq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ropnrovh.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gt2gbsaiewi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gt2sgfzgmqh.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2ayakbony.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujopxzxq.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2uehmlaah.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gt2fwyrijjj.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gt2hgxexyvm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svccaurx.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gt2ptwshjrs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2lbvxifxn.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2mwjcxuba.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mcjxhpor.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2rstfkmhf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2vibjazys.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2ozrurnhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2tzyoxzpn.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2tfptiuhm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2vdfyowuf.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2ntooeajk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2cvbevwvn.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gt2owujdjht.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2vgyaacpz.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2fgwseqxm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2mvswkbfi.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2ltbrrnoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gt2ffqgtgig.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rbugnedh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2urmbansr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2rlgwowyk.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gt2dabrnynd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2pbqyjkuv.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gt2rlmzeuwt.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivgbjknk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gt2erytrcko.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2htpncayi.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gt2kwvvlude.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gt2gscgugaa.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gt2zunsynmi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksffbhur.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2krdskfay.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gt2hdbujxvz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utpzxche.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2pxkeqtsa.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gt2vgsewvpm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfcwxhfw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gt2tpukubgb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2rurmyusl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2pcxobcfv.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gt2mfinecjq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2tflytumn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2wgpmrljy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2tzhximxd.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnphnyrd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2dvlcowkd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2wncitlcp.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2mzhttfnw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gt2wffvduye.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2njvihnhe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2xgnkspfd.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2tchfxiki.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2afqiqtaz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gt2hadfdodv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2fkluzbej.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gt2wjawppfj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gt2kwdpfhhn.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2wsgpvklr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2cgxxduui.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gt2bcgnfsvl.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2epxsmoax.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2syawisid.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gt2vvrincwr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2mitzelzz.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2thmxeqpu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2orhhieuj.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gt2zalejega.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2irdqufpf.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2hsfimmku.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybfirubv.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gt2gajvymrf.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2brwqzhqe.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2zlspzcfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xatyemun.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2birxyptg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2dzpjwsii.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnwgnhx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2pnuejmxl.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2rklhfysi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2hzchrfpq.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gt2eplgloia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2namtwopj.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2eceqnrco.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2guimaesw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ifopwiou.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djczndpd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2ehgdxuof.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gt2ttizvamy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2jorrskig.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2svtlqnmj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2qphbyvns.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gt2tdpmubel.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eohpcebh.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2lghipkam.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2cejzhmla.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbmgbupw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eymyfeii.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfqtzdes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibvuxtzr.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2fpfmbonx.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2ggeheiar.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gt2zorlbcul.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2zejxjsgh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gt2xemyrztv.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gt2oddnfqgl.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2fansetpa.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpdukihx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2ifdnsvlw.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbwhbwby.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jzpcmlhw.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gt2oguliodv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2olybmfbx.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2qqtnwdzs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gt2fgbeqftu.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2rsjwcivc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2vvdaoefv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2raijwxzc.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gt2enhahhkb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gt2cbrrgdmb.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2bzasgsww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gt2dhcxpkxs.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gt2cuyzxdpn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2xgfgcgvz.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2hnitqpom.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2qurnphfw.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gt2cffudstu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2kajylfnn.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2xlphrscz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gt2nmudhbqo.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gt2ackcojhd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2iqvnebwm.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgfmohil.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2ftqrojom.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2wwdzjrde.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2obomzedc.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2frkaaxkq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gt2uurynzvg.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gt2dnzfnrnz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivwrceco.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2mlmqwtvg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2qgsgicae.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fijwcfcw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2tftdqmls.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rnnrgwom.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2jakzndmn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2xgmfjdkq.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2tatmsrgm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2wixvuxca.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2yypoolzo.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2qsinbxvm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lkuqtqjh.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2riviqxjk.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gt2hmmbqbbp.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2ubhdudpq.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gt2tnmpghop.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gt2gjhdvfek.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2opqtkeky.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2vlfbrona.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gt2jmuesfvk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gt2bpvbbkud.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqfklnga.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gt2cukmsvyi.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2zlquaode.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2urhygxkq.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gt2exblwmoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2mywqitnz.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2wsqdyxrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2axricubr.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2uznppkju.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2gludufto.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvpfcrsm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlhjvnaz.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2lurjgmcn.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjcoyueq.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2launttpe.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2yeuuuwxg.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gt2rjuhmkqw.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzrvunua.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2fopyoyir.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2mhpmjqsi.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gt2btklazqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2mdryewsf.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2jpgptlsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2pouyykwt.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mofyfddg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvpttrvn.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gt2tptblnow.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2imtmgsxp.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gt2mzjmusks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2yumxjdbc.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2bysbdfkz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2cvsdyeub.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2oafijmxz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vysvaxcb.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gt2lrfzxljo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gt2kgbdfwef.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2orbnkkxs.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2innkbcny.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2mcyahsld.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gt2xxnxjfqf.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2ckvqnrmh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gt2wqeecxff.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlfshacq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2ksqfckyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2ingpdfwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gt2pwlednmw.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gt2siibnjlb.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2xtdjdack.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2skauzelq.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxtqfuog.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2iylwhhpi.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2exveqfdq.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dufjkuzi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2frphyltz.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqhpxoen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gt2oaglaxmg.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2rtntmdqr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mueuujpw.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gt2kqkumtbr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2sfphuigk.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gt2njvjhgtj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2rupktroo.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2doxsmpqs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2vtpiyrak.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2bvczfwrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gt2twehzubd.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gt2uhyxgqbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gt2gandvifj.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2eztfqilw.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gt2lwclqbsm.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2kwmistik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2vltebzsj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgzgowxb.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2nyevzunt.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gt2zxekwybf.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2ycysmokt.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmljsnuj.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2fdskkyru.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2kpuzbmze.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2rgkjexai.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gt2kjlrveic.html


<!-- 参考信息 -->