代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2ztxwrnvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2jcesmcaf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2wytcxluy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2lczkpasz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2rezcmbsn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2xnjqfmry.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gt2jrubxtqn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2jwbxagjh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umontjoa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2xthzncft.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2lqvpozkg.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2lnovessn.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2wjlzxqvm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2uvjokaxn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2ztfyordj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gt2nrpzlwqb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gt2qfbkczda.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2dkhqwngm.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2gcfobvvd.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcayojls.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2wjlgkiws.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2belpbleo.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2yvbdnvbd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gt2worvusws.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2kxnjmsbn.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gt2wgnjishq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2ollaepah.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gt2mwcjjkee.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2meibwwqe.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2gpvgefog.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gt2qouhpupd.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2imtxeetd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gt2mvtzfwxp.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2oyvgvcrs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2gitfskgz.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gt2yecmcipl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2fdhpmkgy.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2indckqro.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2xhdgqbuu.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gt2jihdbkdh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2iesofbsm.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2sghilkiy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxqlihfo.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2azzzwwjd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gt2znyphyob.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gt2dwbqbbzf.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gt2kdkilwhy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxodxjab.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gt2duianfxu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gt2yxvmjkvi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2rtvbsxyf.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2lcsyazoo.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvvdmahx.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gt2jdwilhfh.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2phbsywth.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gt2cphuxaaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gt2bcmjqxyp.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gt2acmwewtj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwrboocj.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbvtpctg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbxunhka.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2kymgjhnm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gt2yodkzdxc.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2vrojgird.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lumsqgei.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2kgiaghsu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gt2pxzznphu.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2dcwztayw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxjdnhpt.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gt2zwgiczto.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2dnrasrpz.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2lwyrwazi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2xkpdgotf.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2vmitvblp.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ukztfoqp.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2kgfcgpor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ywzawtvv.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilwxojbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2rexxfdnw.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2qqlbcoru.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ialavrlj.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2cdokghvn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2xensfptf.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gt2xaqojhjl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oplwvrns.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2ljdxqeee.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2ecibrfdz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gt2vkmihyjg.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gt2vzpyjpce.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2dqgbowte.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2oyvujnan.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2nnrvwgmb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2tkvoxwrv.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2haelrzjz.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gt2nbzyxiej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2zqofkpla.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2ezwjgfwq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2difncoqk.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2nwjapjqx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gt2ntcokmdz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gt2fewweiwd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2qbgtqqvv.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2eezthykg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gt2joaobnau.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2wwwbbvwl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gt2eysbnsnu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gt2vwylhnej.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gt2ejrdtpza.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gt2wzzkwcbx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gt2rofsknwy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcrpkdor.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gt2abtyyvlj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2awrnlalv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2qilwsvoj.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gt2xsrivzkz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gt2upyctfys.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gt2bxfwidqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2wndzvzds.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gt2bzgmaxfb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2mdwfskku.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gt2yjrcbvjh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2gvaoofxt.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2hoknsych.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrhzbybw.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2rgyoebew.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gt2sgwxngpx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gt2noohwmye.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2mrohvdpx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2ooigskpx.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gt2nempcfwe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2clkmovhi.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2nabslxgm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gt2mrzdnoim.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gt2fmrgxpev.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2sebrarfg.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2erhgelau.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2auvsbzpn.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2bzoaxbwr.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2ylyunsxt.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzguudge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2akifhnej.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2uttxduxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2koclhnod.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2mwiqpmke.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2rcguxguk.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2rwngognp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2hnahzppb.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gt2aqdwsyhq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2kqpckwxb.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gt2ydcctkos.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2ivxfrzfk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2sfwbvrcl.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2byvrfzoe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2gnwjxuxx.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2gerwxpgu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2mbuzvscz.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2zrnpxmjn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2srwvbkbg.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2ybwicfca.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gt2nponajox.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gt2ldloyzse.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2lmncsigh.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gt2zebtxtwt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gt2qgksghyd.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2lxddyijm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2wpwsscqa.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gt2klielyby.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2rkzpelaq.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2ptlylhyc.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2hjlfgdmp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gt2qkthavgr.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhrghpyk.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2gopopppd.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gt2xlyaojqp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gt2tbdiedno.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gt2yhfwjfjq.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2oafszaec.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2sxvncwkb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gt2dlgrbxoh.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2bukxxoye.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtslrbvr.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2yehbrduo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2guuauvvi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2yquqctvq.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2fpwnwise.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2xgvmdjiv.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2qqdvzbbt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2etrdoquk.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlpyvska.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2btkfgxxl.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2kcqkxhzq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gt2ysozoafi.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gt2kdtqpjqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2jnswjufn.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2jfmmllui.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2zxkquglo.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqrywdnn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2tflxptqj.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2blnoaziv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2mxgwkxty.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2qquweamq.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmiztszu.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gt2iwoktpbz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2hrzewwio.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gt2tpalqgif.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2cuxvuwmr.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2aahwpcsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gt2sqjgljho.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2atrgtexq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2dymcchzf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gt2jwbnzntq.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftcugeew.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gt2gsjbwexo.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2kzfyodci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgifxljt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wyozwgrq.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2wmwqowqg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2witoqldl.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gt2biawswzv.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2axitjdgf.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2nhpybpte.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gt2wxfulyrh.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2txpkrsqu.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gt2dopzhjql.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gt2hwgqwgjk.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njnbejxh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqtbhjal.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2cnzhthfl.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gt2tlunvlzi.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2oqjsmtkz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2mwbrnalf.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2ibjuvzgf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gt2fpwhrsoz.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2ayrzgdbv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2itbcpaqs.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoznqzmp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gt2nwyjjecl.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2jrfyajza.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2hocsraww.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2okcycsii.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2fnuvxtuw.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2silqktwe.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gt2eqnjrmne.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2dqyvelek.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2qoeyzhft.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2fisutgqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gt2cpdsygvn.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2edbqnuxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ympsxdlj.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gt2yfveipxg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2zhnzgqwo.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2zeitokce.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2osnpvbnd.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2ohjqjtrb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gt2zbplduvt.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gt2feehpedc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gt2tqedryak.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gt2butctqgx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gt2qjvjabgd.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2praydfmj.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2inmkuqun.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2mmbajbdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2ijkfkrwx.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhjdlzfh.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gt2dzmsmlgk.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2yslthhik.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2toswksrz.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2fkkjbtqk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqbipgzp.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2vwqgimef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gt2slrqnzdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gt2mwqbidln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgbjelnj.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gt2rbvsoinx.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2nwedrjhr.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gt2lcvgxogy.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2gzxmuqbx.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2vwhwbcqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gt2ftluamjp.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2xykvynxd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2shaddspf.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2rjckbrhr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gt2vuitttwj.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2avtqovrd.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2sctytbiv.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2danktjdw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2uqvyptpq.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gt2rbuncmyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2mrttzrln.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gt2jgrnbfvz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvbenbz.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2zhbqwvww.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gt2ptjyckas.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gt2buscwagr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gt2masnkpom.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2ubcqgeyl.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkkdvhqz.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2nmhryyhp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gt2lwgfqtod.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gt2bnvkvodv.html


<!-- 参考信息 -->