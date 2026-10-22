代发 wailian999

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2yysbbnph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjhyykpj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejtsfzqt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2klgbqcyy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqtfksds.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gt2imacfzvo.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gt2fygypznc.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwfzajya.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2onhwidcn.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gt2kvpypkqf.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gt2yankkbta.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmtuagek.html

);
来源：http://dali.xinyue.icu/Article/details/gt2vomwrwlg.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhuopeen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2lafoapuv.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gt2wvjmkgut.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2pjuqvqqm.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gt2eldebune.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2eqvhefmz.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gt2bspclzfb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2xezlbiky.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gt2kgwhbebg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2upbwahze.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2wtpmvlem.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2eqqnquhj.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2wgosctcm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkpofibn.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgoqwngc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frmsgxzv.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psukwyol.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2swkvzwss.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gt2cdnfyckm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2ytiwhgul.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2xmsgspgw.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2mruuidea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2frmjyxzf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gt2znxrucpg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gt2aglyzhrt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2xvbzotet.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2pyasurxs.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2qmtipxfw.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndttqlgk.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qapahlpr.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2cjozpgdf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnvmhmmq.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2rwrcctyk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gt2pzinwkwy.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2rutveuzh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2wnwnyymj.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2raukyzkw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2tkmhztlu.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gt2jspzzijx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gt2wzpwbwit.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gt2jfhpkmek.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2teiimkeo.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2vbfwbswo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2qoclmekx.html

[Q24] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2zafbkyda.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mirtdkmn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2meimaokg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2sxonyuyn.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkiywswp.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnfbtctx.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gt2vonnqwff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2gydurxyd.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckrlemsg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tduygaxu.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gt2ymtrwrvq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2jwaickbc.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gt2qnpcrbbc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2edxhelrq.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlkagokr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gt2wlfqwgvi.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2ndvipuao.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2zizlylbo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2xvtglbnt.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuxvepql.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuwxbpxp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdlvnfo.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gt2jpepibbk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gt2dheopvey.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2fsvegnlj.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gt2lmupvimn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2zjmmzkem.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gt2tgpktznr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2onsqowzm.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gt2kfqcqjqa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2vjvouudh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydcfrzdk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzmarusf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2gcbfrbeq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gt2hlfoozux.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gt2grtbjiaq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2inadvthe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2tkvkakfk.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2mstboebq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2jeotvwry.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2oegzwiic.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2qrzoqgfs.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2hoesxepo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gt2yjpjjsvj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gt2ujfyodgh.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gt2ixpqmnpr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2jmcubkme.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gt2uyegnpas.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2qktpqlwt.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2szzsiyxv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2dsmtvlko.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gt2dtshtyig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2ojozgtvb.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2leuqwzhk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2ruhekyet.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gt2zwcjqyzz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2omnucxvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnvuqxmx.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gt2gffagnoj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2vonkrtef.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2qjxxiyyi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2xraxhxvb.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2ccbctkca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2cdkxxftv.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2enbuuzfo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxfbsyxh.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2onfdlvnm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2sdqyostt.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2mmtflkzo.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gt2luiayulc.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2iufokgtg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2fsrirtzy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2qrnkxhns.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2ohncgaax.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2komesnhx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dixlbofp.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2oglhjgrq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2cpciljnv.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2bonzqpnn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2mpkmdoyc.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2jzeddipa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2dggnldyj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2lnyhvogj.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2czdeimzl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2hlmnvtvo.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2dgvprcif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2rrtaiorv.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2adftaato.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2fyoonvqq.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2ltsuxdve.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2duivndqy.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2dlnjzaax.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2qxdajfmm.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2qmbkljkz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gt2nuhqibti.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2ucvfmall.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2mmktijzx.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gt2kvvyyoyc.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2myecuevv.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2ikbwuivh.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2joewzbvd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2bcwadgnb.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2aiupxzgj.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gt2zigtqdmz.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gt2pzxjhjxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdqcihcy.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gt2kuulodwc.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2jcgimxeo.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2fdtcesvj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwjjutdh.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gt2krlrfwyp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gt2gmjicrnu.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2qojwoeug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2vzufoqks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gt2ilkthwxj.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvkbbhiz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gt2hwztmxfi.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gt2bnyzdhqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2fruqxshw.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gt2emwdrept.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaqfgoce.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2dmtqnovp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2gruhphyu.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gt2gqnclbmc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2duutgazp.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2ecwzjtbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2lrnefvpv.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2ukbfmncn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2pawmjmpv.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2wqjzpdih.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2dfkxkpyh.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2yizxmbbu.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2aenipvlf.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2cahyjqaf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2ryanfjaj.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2bmqymuar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gt2sxwrlmyb.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2yosmfzlx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2nwksvego.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2bceogiog.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gt2qlrmoeky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeqpkyk.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2maxiqiyz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2gfoovhbk.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gt2gzzhmvlw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gt2daholhev.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kmjhwupg.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjynppny.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gfbbytel.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2iaxqkaps.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2mcuwqlpk.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2pqxwviko.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2ogjaudza.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2igymkssf.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2xcowhvvk.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gt2jgyckzsh.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gt2ypekzert.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2ekrswola.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ploemuow.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gt2ncjhzflx.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gt2ldigmyse.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2yvqnsosk.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gt2aewrycow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gt2tdhpgdiu.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2hfciqakf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2ufurwxns.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2fnctysfn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2qauxdixm.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2byhtkjny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2gaypykzi.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2evhyczjs.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gt2upzpuzow.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2ujnvggld.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2msykoerz.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2sbsnogsv.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2ikiruqql.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2grbqnvlb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2uyxcqtns.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2dpzuzdkf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2enrbmbvg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bwchtago.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2korcayad.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2jqmlkmvq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgpysisx.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gt2glntkfkt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2ndhwbboc.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gt2qpjrbsab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2qvzeeeqh.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gt2vvyuslik.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpcmioev.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2wiekxeay.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2tzmktvwg.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2omovqpdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gt2eszhoowc.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2nlgktqau.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2dvyuropt.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2hzycjkfx.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gt2bvzigbkj.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2mbbkcqgj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqmqzqnb.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2gkxzuqqc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2sixoqdpi.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2kadoirjp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2taqirxst.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2mogiljmt.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2dtietrmc.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gt2avxlwgbd.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcvuyqmp.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2qacgvarz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2wlntxrvc.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2yjbrtoyw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gt2nngpsznc.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2ndfxdtsi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gt2byddming.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2dmgvxnsz.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgmyzomg.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2avfefivp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmxvwgrz.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2qumihsnd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gt2tpwpddrs.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gt2wirjzoov.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2hwcyvxzh.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gt2eukopnqq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gt2rkhmmtoa.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gt2osqiswzb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2yywxxspn.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gt2imqmefbq.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgmccmse.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2kxukzxox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2rywztumr.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbsexdae.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2jlgjipbk.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmnpgogp.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2englmyjx.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2ldigsatu.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abwsdtho.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gt2tqhdtunu.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gt2klklhbqj.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2uapizqob.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2lsrfoyai.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gt2qlwtjykf.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2euzqitfy.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2vziarvti.html


<!-- 参考信息 -->