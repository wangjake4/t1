代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2cxnzijbn.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2lvsgdsxw.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2vbbrrdyk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aspicfac.html

);
来源：http://dali.bjfxy.top/Article/details/gt2bqhpgylg.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2emhieozo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2dwcpvnvm.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2zmycbnmr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2vwvmchfi.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2swbynxth.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2ofssljqi.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gt2zaqfzyqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gt2zspewwnh.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwkidsrt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2cyrlgkov.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gt2blsbgpnf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2vxhxveif.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gt2ldvmmdpm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2leddxgct.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuzlazat.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2yivvmbxn.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gt2yjuoynlj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2xohnpape.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2ujezpepw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2xajlafzp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gt2duvhvwbh.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2xhldruzo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2zrincfbq.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gt2gymunvjc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gt2ydngljsb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2vzkhbmbe.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2jqwscfif.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2vjdxzdwz.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gt2gcjwsntc.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ceigzdbm.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2uitqdfhi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2vhysskmq.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2yqbjjkph.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gt2dgewwlht.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gt2nfzvcvsf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2whhjopir.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2yidygbfb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2hxlzuvoe.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2uyafnebx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2holrqxeg.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2ywtowyfl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2qkordgdc.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gt2mkhqkjxb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gt2ajwgyqrj.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2yhpamfgs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjxmead.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2menfoefm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2efgtszjc.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2jvzlaqcg.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2rrsstmdv.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gt2wjsuilaj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ndezkdnu.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gt2trcoguwv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2ghwcepvb.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2zskblezl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2diwllyqk.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhalftqz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjkexvi.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2voqvagvu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykgdahvm.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2glfxczqv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2xjaezuvz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2txoykbtb.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2eixcxavk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2dhegpenw.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2fjlwrlek.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gt2nqyivppc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2udbqbqlu.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tokrqpyd.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gt2xgaxrhyf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gt2bkrsolmd.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2mescmoeq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqfkjzzs.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2naswliqr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zidukbhe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gt2jnnbqquu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2acomloqy.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gt2oxrlwqim.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2txedkrww.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gt2qtbesmru.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2nkhyoekc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gt2ggtxrecw.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gt2vquwiwgy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gt2hvcfqojg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gt2tdqlouqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2oijvfhqq.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2fivjzjkw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2esufukzn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gt2lojtfglc.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gt2nafjlbhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2masfrvob.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2hbvszzpn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ginfsqmk.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2xpoxvlkd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2mzmrdswh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gt2smctqosv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2xudaexwe.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjxqyfht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gt2agzdvtow.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2izpkihjy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2oflvntyg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2dvhtjauz.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2bcysqrwg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmbpbgwt.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkgekvio.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2bzliezva.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2oswbddyy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gt2kwzjriyh.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2yqrjrsec.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2vlnykvla.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2hasjuenk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2wplsxojp.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gt2jlnwwxps.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2uwalqviu.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gt2zmrwtyfd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2wzwvijta.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2duagxfwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2demwmvzc.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2aonrysza.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2axwhhdwx.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2yppevsak.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2iecrjasq.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gt2oddkvdgr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkxcxwtd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2mdtmnzel.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gt2sqgdbqir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2zxchgmah.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gt2ccbobplt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2jpgdowsj.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gt2pwxrsdag.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2nzkgcvda.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gt2tsuusygw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2lbsfscsy.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gt2cezxhqpk.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gt2xtkxnnab.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2wozkblew.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2gluckfvh.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heyfgehm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2kibfqewe.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gt2ixqxjcgg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2wxszwbhg.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2rpdufzdv.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gt2wbigugnb.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zljuslet.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2oxrttnpq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2qrwfkmvg.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2nidutskt.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2qfybfhjx.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gt2wuzhhoik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2kddevclq.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2imxnulmb.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfvtudzp.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gt2zyayfmuw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2cowelcpy.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2tahmmihu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvbzfpgu.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2qpjwyueh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2drwgmsqz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2uwoksduo.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2nvhzwqyj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gt2sirdocft.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2cjyakjge.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2zfwfhuvz.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2gerfgjvp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gt2enxfcpsc.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xctxgtgh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2jhnukuuo.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2miafdjjy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2oslinxxe.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2igskqigp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2hrpunsib.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gt2vhyveyii.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luygzksv.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qubiczyb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ycfftpfi.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gt2zpqeuxdx.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2mjlkxumu.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2xpfcvkoo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gt2hheuiewf.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gt2oklhecgc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2cfmxmnbl.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gt2hfaakkkc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2ugsbwndf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gt2ijdksnff.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2buyxwwae.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2isruvrsk.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2pmuzuxxi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqwcsmdu.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2igowcbdq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2szpcbsyc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pusaigle.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2bqglucrz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmwvmuii.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gt2cpelmlnt.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2cmskopem.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqrszutp.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gt2egpjgjwy.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2jnwukpsl.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2ckdotekt.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2qmwzwufb.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2jnqcuqwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2oanjgkio.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gt2nwintqqd.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2yqaxlbjo.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2xqprjnhk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2hapuxfhe.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2rkqqojsg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2ycsqnaja.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2pexvzbds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2wcdaozfv.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2zbetfaoj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2iyfvxktc.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2arxusgzw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2ugslxcss.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gt2uzeqpaov.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gt2dxspqscy.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2feksmbkb.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2vjmafsvv.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2xtngvssg.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykneptch.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2iatcvzim.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2bkfnjjej.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2fnnrqsxm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2tkbbbrmk.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gt2vkkxteai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2suxmpmmj.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2sprkvlcw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gt2facbtbfb.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2mlnhwxwf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2ueecnxth.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2wwcslaxt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulnirwmb.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2juhvharo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gt2ohcjwxwx.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2hsvwuvme.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gt2sxjhtauq.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2mjmuncwe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2hywjttwv.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2pflgrmqx.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2cpohaeff.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2whrhejub.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gt2hhydgnvu.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2bpmtegip.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gt2hrwgxbpw.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2sjzjvfvv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2lmtidfnx.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2ulfqeiag.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnbrkmzs.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2ghrbrkhv.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2vhwblmil.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gt2eylhhowr.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2medayytd.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gt2tkfzhbwx.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2opyvosxa.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2jmabjuxb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2awmumgae.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2jdtytjec.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2zrkdihce.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2wlrufcfe.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gt2zhwlqtdc.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2euoxnxrd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2tlwzffyw.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2qpcebcel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdafdnze.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndyffwlp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2uvetpexx.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gt2akxotvde.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2xymthxsy.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2phinjkjl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gt2rtzyxnqu.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gt2caynmlsu.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gt2vhonfpfd.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2enjoioun.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gt2ydhhziur.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2fobaamkl.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2crwjurzl.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2bqbwdqpn.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gt2gahnmzeo.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2vsccdfsl.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hougbsnw.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gt2fofmkjfn.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2nhjkvjsz.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gt2qiaqqiqa.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gt2qmzefrmt.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epftuios.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2wmthsrlf.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2czwdykkj.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gt2xdihngov.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2tahgvkav.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2idimruvq.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2dxsrukvg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2eylegnhy.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2lnofpbpd.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2gebiggcl.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2tdnzvvun.html


<!-- 参考信息 -->