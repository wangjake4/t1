代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gt2jcaqwapt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rbzltnpy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gt2qncvhsca.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2jtztkakm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnbxgrnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqndzzuc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gt2inexgiyi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkwjznb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tvritmks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2unzsjspp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gvvpotfu.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2tljbseno.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gt2camkcxng.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2yyonsnpb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2sauuaaen.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gt2jldflmec.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gt2dgluvlml.html

);
来源：http://dali.tanke756.top/Article/details/gt2sxmqkeli.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2zvjvzyrw.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiqllzuf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2rnodsrll.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2ccjlehaf.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gt2ewwacspi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gt2douzdmgu.html

);
来源：http://dali.gzhubu.top/Article/details/gt2dcgaxsjn.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gt2aphgubfu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyniwqpz.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2osbkaist.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2swheltxx.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2guyhuqzv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2jlncrkna.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gt2wkqxqlib.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfwvswto.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2yaomoduq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2klduxatw.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2ffgwqzxn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2zovdkoog.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phjsgoaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nencwhjq.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gt2tdactblb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2nhgwedfu.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2xczstpae.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvxmqnip.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2rhbtdbis.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gt2qvldwldj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gt2qfhibalb.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gt2rxcrkytp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2finqxpmv.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gt2liwvnily.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2dqbiasim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2yajqalfi.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gt2rdmesmoa.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdtyvydl.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gt2jdjmxwry.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2zcbfltdf.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2ccrkdbfp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2tqqcxmdg.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gt2bfcsqgjs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebryrunj.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gt2wtytidzh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2keanwtli.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2vgwlkyvj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvjsbhvk.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gt2wfaiteaw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2prokvmtx.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2rendhxrt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2mvocesqt.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2wtejoikd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2mvgwsizt.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2mqhqiyoj.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2mprhndtw.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gt2vjfrbdeq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gt2sdnpglil.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2wadqvofm.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2rmqyuiag.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2lrlzmsfi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2emflendi.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2rvfshxqu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2gzmquudm.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2ikukjwxv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ppljvduo.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gt2wecstvyx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2agqcgwqa.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2gbvtlyak.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2ajuowxsh.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2rzsbsejt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2fcvgvwzi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gt2yyhseoal.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2kcslyowg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gt2jjnbzhwt.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2ejszgobs.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rznnrpje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2vlujnsnc.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2kywctazv.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2yxyxxkct.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2zllscqpy.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhuyxzel.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2iixyhqxp.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gt2iupwnuux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gt2lsogufug.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2dzfejjzg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gt2qshthrib.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2exrrhipr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmhqfhvu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wslszhku.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuhmaqsm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2clfaqdey.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2ovnxwufo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlrgngv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2raiaoodl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gt2xkvmogcm.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gt2klwkehob.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2vmstswyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2mtqqqgxz.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2domqqxel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gt2hhzedoqq.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gt2pvdniiix.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gt2nqtwvhaa.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2giuvyrpg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2csvgmpxm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gt2yohqzbbg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2qkdnmqrq.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gt2qfbnbfik.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2rvdhzbor.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2qrtcmiaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2ugaygmlt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmkowzce.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2fdktixoo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2nfdqylcr.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivieuncn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2qjmkukzx.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2nwozyklr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2mbbhdmvz.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuqqkjmg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2gmbhcsco.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gt2bpzvzzmp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2ypkpdltx.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gt2iggunskw.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gt2kvcqjwig.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gt2valuhjbj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2qgytxozo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gt2ivisvelp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2bianhups.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gt2dxybbjxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2kxmyjfce.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gt2ujjvrkjt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtxwogtf.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gt2clbjtlmr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2aiaewcpf.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gt2wsokhqfa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gt2qojsybaa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2xscgbvpm.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2fugnjgfk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rguyyzge.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gt2szhsbkdq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2fnseltki.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2bjfahmyp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfuzuolz.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2mfmozjtz.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2oqrlsruk.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2cuxusibe.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2fdaknvzn.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2uoagzzks.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gt2rkvksuyd.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2rodmbran.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxcvixkr.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gt2vqwkhksp.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2ddmksnpa.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gt2ebwdmavk.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2obsvcxyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2iprvomdm.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2qezesfty.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gt2ghmbusrl.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqalqedh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2jpdqaoiu.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2ksqgxali.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2elwpvyyn.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2wvlntibe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gt2nzulqqjt.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2akijzkgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gt2zfykodah.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2nmtfyecz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2xvsxdtam.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gt2qarrraqr.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gt2qbwhcxys.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2oqwcevma.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gt2gbrugmai.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdqumimy.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcfjpvnc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2osjiikly.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2vipkqtqd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gt2dzxklyxl.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gt2uykmrcrq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ujiqrzng.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2leqywmhd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wkbnqozj.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gt2lstsqucu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldywiulr.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2jiygxavn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2imohsopg.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2yphaczlr.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2vawxnoja.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2eliivmmd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gt2hmwsirgr.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2lksapwlu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2pqewcpgx.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gt2bzyjlhpt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2aeqahzrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2fyiupjtd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bylyyrst.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gt2khekjctj.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnwzbgav.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2lwzozrne.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2gnknvjca.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gt2imqzpbyp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xpcheluf.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2jhqpzzdu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kfwbnzhs.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2ldrigrjg.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gt2epmaugtu.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2wvnyaexc.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2kfrphbuo.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2xopmothw.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgszpvva.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gt2lrllqtha.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2nalcsgds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnkefbsy.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zerwuqwk.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2eiohmdjj.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2arvokfjb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2imwjqyfd.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2tgjhqqjf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2ksdjggje.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gt2bfcrtglt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2dqfoasnl.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2jkdzoayr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2nfdgphik.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2zwoybnlc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zyggosbb.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gt2zyvruiol.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2zdsoefuo.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2cbcmqfqd.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2whsyusln.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gt2kdtfkksd.html

esac
来源：http://dali.fengsongda.top/Article/details/gt2zcjxbtuk.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gt2matsnrzl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gt2ckluatfh.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2swnflath.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2fpkypwrk.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gt2jnygmlre.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2qceqcfcw.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ivsnlgzm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gt2vnynreyw.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gt2cdzdvkog.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2evrtalkz.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2wtumdsnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2txizgwca.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2rrywwinp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2bltmhesg.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2bilagijg.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiijqxbi.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2qchgjibx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gt2drfwgyfd.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2thtuehxb.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouvrzaaj.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2whhketqu.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gt2zajgzccm.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzeroiop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2nwwgbnix.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2xmhoramn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2clgjsyrr.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gt2jvgsohkk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2sadgqxdc.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2axmtsgus.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2kzqqrgrh.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2yyqqirsy.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gt2qqlngvwh.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2htbfduvb.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2vegxylkm.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2pckscttf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdxegtuu.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2smcufuvd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2ackolylr.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2qxwzrlhw.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gt2lzozcxnv.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2fefddwik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2shdpvcjw.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dogdeplu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2kcqsyocp.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2epqyrryv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2guoebpqv.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2sovtmvff.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gt2varyuqad.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gt2kxaphjgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2yayduuwz.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmeecdof.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gt2irqaiwxa.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2olfbkaoq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gt2xjhlyseo.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2qppjojts.html


<!-- 参考信息 -->