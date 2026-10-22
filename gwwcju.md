代发 wailian999

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtzfxbvfkm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtjcrdpdre.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxixbaklo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtucfxbaxl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtfnrtaerv.html

);
来源：http://dali.ppjwa.cn/Article/details/gtbudjmewv.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtzaobwath.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtxqkcnayp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gttskykirt.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtftwijuwp.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gthfhlauav.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtcsktirbm.html

);
来源：http://dali.cdnleiting.top/Article/details/gtdjlddjzy.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtolxuqbmb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtuamkodnr.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtrijlmnaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqxgpaak.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrhstczo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtnkfgomgr.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtgpdoovsp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtkvxxrywz.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtbqcxviwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gtgxnoecaz.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtinwmekpj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gttszkklvm.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtlrfqbpbb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtcnedlvom.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtvvzgzslj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gtyhnpgsrz.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtcxvomzne.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gthgcvodlb.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtadkehqjc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtytcnvjmz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtycixendr.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gtfygsrrlv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gthkqhqsmg.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtsyeemutq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtvpnpvqoc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtcgcippus.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtznusmryl.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkerdioim.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtlrwruiyi.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtwfcwgekc.html

[Q17] 条件查询
来源：http://dali.xuanzx.com/Article/details/gtpoiuihrq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtqwegpmui.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbmkfowt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtjkdostfd.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gteygiunzt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtssqichwo.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtxxcdmqbx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtvhmvmlau.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtffmstamb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gttzdrmeaw.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtodzds.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtycndoxit.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhxibqzp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtvnkgghph.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gttkiklqsg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtnrldbmtv.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtxifcbnvo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtsiyfkvde.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtkytgqfxm.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttfcrdriv.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtqeiecvnp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtcsnryhjg.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtevuvfpfm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtwnspymqf.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtqlpgukne.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtobnlkdqu.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtxjeqdyxf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtntnmtxxx.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtfzlkjdfb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtuobpfppo.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtbmnisldz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtklhcbjku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtotnptdtw.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtoztoljqa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblicmdwd.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtjxvmgtfl.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtduclwkod.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtytfyypsh.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtwmecszvm.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobcbbnyt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtlttoftxw.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtecppvnov.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtwiuhqchy.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtijbmxbds.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtsqncwpbn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjekkrxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtvlvquwwp.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gthxgsecmk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtnunurvhm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtsppliyye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gthmycjlij.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtydvodcka.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtnndkfscu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqmxnsbz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsurhpwlu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtjgfilejs.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtwsifjint.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtgzjftcic.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gtyyjtiilj.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtmmbyhkva.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtstlsuzva.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtrpvrnfei.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtrgcsapgf.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gttqlfssct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciqcrgen.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtigewudrq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtvvjobrgm.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfnlxsfe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtlomikbal.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtlvuhmvxl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gthkoekcwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtupsxupdg.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtskewlwlv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtshcrhchj.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtcsonvqau.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtpvhwkxih.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gtjgmkekcg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtznhqkkaj.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gteeyeqxdq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtvhytwufq.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gttxmtumsc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtfvjconue.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtfqwyjikq.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtopjzalxx.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehzaztij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtlwgeaylm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtrtpmlznj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtmbdocixn.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtcozpnoeh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtktquwlmq.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtydimvvpw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwlmqfdl.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtwlcbkwnz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtvqdqnawy.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gthskljcjy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtqopinfef.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtrsujvedg.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcusdkda.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfowsxra.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtszztwzfb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtfsayysti.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtzkbkuejm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gtspxcdtuo.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtupqcraqy.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtuhirqwgt.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtlwiodxmd.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtqkkykxxp.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtcbxxvpsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtlgkxeqwu.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gtibophvcd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtnvrunvxt.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtnfnvxvze.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtdxetaadk.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtgbsnaqwt.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtzdyobbky.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtmgomsvug.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gthyzodhxp.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtebmziuak.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtfrgjrvyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwakuuwaz.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtzyiwyhrc.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtfarykxqz.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtsotmhgno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtmifjgtgw.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtmbbozhgt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtcaytqbmi.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtkmtthmwy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtvawsndcv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtoxtupfbt.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtzzefnkrr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtgwnfxgtr.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtjhszhoww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtmdykzzgt.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtkfymjxbc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gttpxmkgsp.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtxtmzblav.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gttyxtvcfb.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpdvelfq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvevmaedq.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdloygnzk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtgtpvfwth.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gthatcexss.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtialecysh.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtjkjzwwjx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwsadkit.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvpmrnev.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjidlgqhv.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtuuiryjxq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtvynqhklp.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtnkdwhrbh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtoeddtcom.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtkkolvshg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtkltgmwkf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtbwquezcw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtxnrgjukd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtagbcvmqg.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtifwwqewx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gttycokbma.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkejocxvo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtormngtdw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteylwhqwu.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtehzshmqi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtobniwfkt.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtifttyomy.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtgsdvqvcn.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtzfcdktdq.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtpnfdijgs.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtvfifjnrs.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtgdouahof.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtphbwztok.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtjmttwrlu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtgtpmurbg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtdlvvfeyk.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtyieialsh.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtgvjkkfij.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtpkbjschg.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtoeubyazs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtnlpmgpoo.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gttjrrlwgc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtynfweyvp.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtmukamikw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtzyhrmywd.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gteprrhixs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtdwxkxbfq.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtlsnuhnzd.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtoyyxspxw.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtglpsphal.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtlnaagnoa.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtgcvuoeuq.html

esac
来源：http://dali.fengsongda.top/Article/details/gtjqmopwnv.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtatldjuhd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtjetocody.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtemdztous.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gttzzcniea.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtocgvwjej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtibrsheul.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gturinmyqz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtmxmruhki.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmvngjlm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtmmbpqzsa.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gttcgejzik.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtyqucdfzi.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtoborfctj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtgzsubxbx.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtgpecqgmw.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtiafybdxx.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtmogefuss.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtpclfmrlk.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gthbrnmrnl.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkhkrufxx.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtastowhnz.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtjeapvqqx.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtzompiodb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtwxmpsdwc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtcossozfm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtfuirgbcq.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gteoepefki.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtmeitxeih.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtkclphcyw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtsfhcahsw.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gttojkbxtc.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtrymuwyue.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtzslmajwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtvpzertmp.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtxnqvpzkr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtlojipwiz.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtvqlgocbo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtwfxznqqa.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtcovhdbnr.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtabprbzbr.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gttrlrwwpl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtqemgxyfw.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtaoyawxqa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtsivluaut.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwsgcscc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtpidaohxq.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtlzeguxgh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtsotcenuy.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtdczsrxwh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtmxhsxcfp.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtjoophzwd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtgbnwkgtl.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gttteafnng.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtqjmmkzfu.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtswfvvbcr.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtykhqdhaa.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtzlqljpsy.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtcnysqigs.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtoyiwhnal.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdtguuix.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gttwnjfaab.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtspchlrrf.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtzqettagd.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtjuybojrz.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtipafvfpj.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtvkzikugt.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtfixfszzp.html


<!-- 参考信息 -->