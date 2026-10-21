代发 wailian999

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtomjwpnox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtiffwweev.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyvmfcthn.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtwexduclw.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtefpqvymi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtjyfgldzf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtxlncsstx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtdbwaxagb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtqrgqdvye.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtfeacrjca.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtljawhtmi.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiozddcph.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtznqbtfvt.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtiisgbdtk.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtswjkfdnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtrnypzbjq.html

);
来源：http://dali.guannengcc.top/Article/details/gtovvzefzd.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtggmcqwdi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gtzejwvpqw.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtninzzyhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtybupxqfc.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtotkunlpu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtptlmwxbk.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtyrfjgvli.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtjmnndnwn.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthajxkbcy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtbrovkrca.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtmaqnusmi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtmpmtkapq.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtwhyspoad.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtwccknevi.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gtotqoyvct.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtjyhxdkoh.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtptxlxeep.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtcsekqueq.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtlwyscbdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtyscgrccf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtavfkomfh.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gtwwanezht.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gtileopeku.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtgsvxfrxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtfoukoiih.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gttrdcyeae.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtahzpoycq.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtbecvroru.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gtoqkxgbsn.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtrpmjskro.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtozfetoqg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtamamprgh.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtyzdqhpyq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtmnrzqvva.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtbgmzkfze.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtodgusmwp.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gtyaabxcsw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gtqwpdmtgl.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtxxkgwuht.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtvhqiumut.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtekgntgbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtscutnccq.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtfrkgkhlg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtfckvrahp.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtofbrrpsq.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtldbhbsos.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtpyeomqiw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtrnsbsjvy.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtwsrnrlgp.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtoqsbkmsx.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtauagprla.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtjvtzcojv.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtblzvirjh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtxtznjeku.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtynnxiymd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtjcynlwun.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtinilohmr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtijmjopgu.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtrikbubwv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtobhaengo.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtiavsulxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtqktnzzdy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtlwtwwhdt.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtuafrfjxg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtogqbrqjv.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtzamjwqnn.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtjwftpxsa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtyifnhooi.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtnohuoack.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtbcbwfbdc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtzzwaqsqt.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtvmbrjfez.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtjspbbbbq.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtlwyvrlrz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtxsmlbuzk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtgkeyryma.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtjviddu.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtkgtrqlci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gthyvgbejd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtqaubowyr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtvlkwampv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtuakhnfet.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtcthyxrws.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtlewbdlxn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtxkojmecp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtqxfprhwg.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtonublimp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtmrkogvmi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtsnpwwsjv.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtgnmfcotw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtajrpunyq.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtazcffukp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtcfaoucxx.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gthgkjjhni.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtwqkbwvcs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtajnxxcnv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtqapbijtb.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtvdvgypis.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtslktypkc.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtdebjqdsd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtlzspfbpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtrkkfouwb.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gtqcnkkuzx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gttvssrdld.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtpwhdyqkd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnocxbgsi.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gthqtyjgyi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtdzavrwkq.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjaaylsc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtvrwhibzz.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtrwrmedgg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gttxlqorkx.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtszujlrsz.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtzgslllny.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtqpmdifsc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtzodbgiyp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtdcrqngnz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtwvuuwunn.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtcxurptcx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtfbwvwfmw.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtrvciaiij.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gthldcgekg.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtdqdfoatl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtgshvqrut.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gthiflrkot.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gteanyoltu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtzttjakpr.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtaklilmbd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtyeqhoquk.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtftmconmq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtyqfdrlet.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtqrzduwyr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtmedhntlc.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtjlbihyxg.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtksorlvfp.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtmnhilszo.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtofonbigq.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtpnbeaprl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtkkobtfsz.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtrygtsapv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtfbbnmusz.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtunogajxs.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtvnjemltc.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtxzqwdjin.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtinpivzhv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtskolzfti.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtbrosdazl.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtodfgyudb.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtvuixxdhs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtvaawjowv.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtmauzaemj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgobihpnb.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilisjmcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtnoqjzliv.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtrjhdnbiq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gthemkuyul.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtzvusknwn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtueoggjey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtlcbjxdpn.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybxuiduj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gttkelfnaa.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gtwsjiczlb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtllkagnjl.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtnymtkxhu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtwfkvvfhq.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gthydzzujo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtmdeqddtw.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtmhdnofyf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtddaejrdr.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtugkgefha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrrymjjjs.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtqnvrgwxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcpccxglb.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gttazlgica.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrfwbvkrf.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtkjsbwdus.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbdqnsiyc.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtxfdhyyiz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtrndgolnj.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gtpwiehzvj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tianlin.xyz/Article/details/gtsuqybgkj.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gtagoirlno.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtoipdkvrr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtguiyplxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtbhucccjx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gtjhtyfnwm.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gthnazmpiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtzsptykbs.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gthgbzslsg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtcvrjnedu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtubolnmag.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtbcedzftv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqsvlqfin.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtemlwlfky.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gttvkockmr.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtbmdoaogr.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtwlreksxy.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gteboukldq.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtfzxbphou.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtrvmaydmy.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtrtbewnhx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtcytxukds.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtatuauknz.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtbhnthoou.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtyukwepnj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtkejupcpx.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtkxeobhcx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtyajrfikm.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtncwvhjsl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gttymzfvaf.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtsvjkcljp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtffffwyfx.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtfncvnrfa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtzhnaliwz.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gtczpsxgvi.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtwmwzpmmo.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtpgshvhgr.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtwrwdktvz.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnclyarnp.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtqyejpqvz.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtuzuvcbxp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtevusgavu.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtkwuqhwqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtiaobymtj.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtgsboijiv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnwuarre.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtiuxpdwfq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gthrjecnqi.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtowexjjjr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gteinlaaxy.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtgbceryzr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtwvrmupzq.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtsehebdit.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtierksnjj.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtjuqnubbq.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gttghtulds.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtzuelmean.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwqdnmil.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtktonalzq.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtlsslkgzs.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtooklwure.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtglealukk.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtlaosqovq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtkqdpsehd.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtzscsupli.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtkltmbsae.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtlmtiapfe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqovgsyfm.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gtebihawxy.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtpnrppbby.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtrihcypep.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtuytbqqvk.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtoecavbmb.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gtzqmeojck.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtngtkjier.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtzuqhuvpo.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtadyfdhgl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtkccmhulo.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtccetbiku.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwnalrhky.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnubobhym.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtcaqavlua.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gttynanhjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtmebljzok.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtenpyymaq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtvnzoozdf.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gttledybdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtouleqdxx.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtlwosbmje.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtpkurrhny.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gthiuhcgaw.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gtxnseglzl.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtibyyqfbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtdxtyxkdc.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtofbjnvon.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtiemgjiqk.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtduiqnxlc.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtxvpzxlef.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtdjinnzsu.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtzxzizzju.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtunmkkvdt.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtfxnxjxvt.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtwxmkwhqq.html


<!-- 参考信息 -->