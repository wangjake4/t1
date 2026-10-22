代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gt2dkkkhnyn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2vbzyfrux.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gt2fcugwfbr.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gt2nkgqxflx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2vezefqbe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2jhqxmetk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aofuinrm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2uoxwawxf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gt2owekbsiu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gt2iyzsyaos.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nostzvor.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gt2zhrcrsmy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sxcvtfkn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gt2bdufpcck.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ojwabxrw.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gt2puncqiyr.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2zrkpnpal.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gt2qejzalwh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2auwhynjv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gt2ajrskaim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gt2wyofzodh.html

);
来源：http://dali.cucudq.cn/Article/details/gt2wmgslqyj.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2tegyhygk.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2gbkwmzdr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2onpgcoxl.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2sywkobsk.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gt2bbovzbxy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2ynibkquq.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axclutwd.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gt2issfxegr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2fvrurhlw.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gt2yhyzihez.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gt2ubksipvo.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2xoygathw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gt2emfyqizb.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2aofloiiw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gt2wolksqge.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gt2wyhguihe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2yroaehkd.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gt2zdpiejvq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2rlctjewl.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gt2qhiyvvsx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2chtqjucr.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2ykpgxeyf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2xnldgqja.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gt2weqhbprs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2yulguodn.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2eeiqplrk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gt2epuoyrdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2yuszonyh.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2dbokwwyj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2uczynqhc.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gt2raowzmgr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2chyewoim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2mwaaljwl.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2jgnweqve.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lroompek.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gt2jhosvakc.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2hxyidenv.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2pfefjmti.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gt2tmfflagr.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2zqqsqkaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqbkpezi.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2tvudkrnk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gt2rewdosew.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2lrspmpyp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2mefioyok.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2vwolunmd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2fkoeibsh.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2cvrkqmyq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2jqqiuder.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2kidtijni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2jqylartv.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2gbgzwdmj.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2urkprrbq.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gt2goxeljqh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2zlxoxrza.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gt2tmgkbwil.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2esgaaqnx.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2ybeytiuc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2kjsllcsq.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gt2lfapbtgg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eopemavn.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2rjeepsae.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2vrsztmgi.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gt2irskwpxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzqwikij.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gt2nlkdnujb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2oueixits.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2bhjwbjxn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2jelaokky.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gt2idiugnmf.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2hzispopl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gt2gtnjibda.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gt2jtmagftd.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gt2gxfgrwdh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gt2kipzwtwg.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2lvhgincb.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xerczpyr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2gpgffqsi.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gt2vnvlxtos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2ykjopgmy.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2lbsyalob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gt2pwgkljoe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gt2jlsfkeec.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecbluovo.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2rtziipjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahlfvofv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gt2vxpgmtrr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2oljqrava.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wckisait.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gt2mgpszfsf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2thrwcnpb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvkirkxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gt2vktkrxgo.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2cvnherje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2fougavsk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqkwjhyu.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2eruvppxe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2ropdhxks.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2kahncspe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gt2qqbybses.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2dyhgfqxg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2wmxjqjag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsxqiurj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2gpxmdfbs.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2kjhmktsh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfyctzqo.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gt2betfovwc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2conlhvni.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2nlmkdwln.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2epkdtuoo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2pkzazmcn.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gt2sluaolkd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2fhekoxbo.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2mgtmxazt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2jeazjqfu.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2lcfzsipe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2afmtmkef.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gt2meedngez.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2rigvappp.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2oeyjubmq.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gt2cagnkmsz.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2ddgaaezh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2iosblddp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gt2xrsmitkt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2grppfotu.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gt2bgtfmdhn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2cvdrkfmz.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2vjqaqgas.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2egrtbzck.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2qfqwkavu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2dixcazmv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gt2prsudqfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2vkmuoweb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2yvfwkxfa.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gt2hawmndzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2sntasife.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gt2kcjszduu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2asjiphvc.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gt2woobduxy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gt2yovcatnd.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2nooquiek.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gt2umhprnhw.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nybdjtaw.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2aqmkyzzt.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2eavfuupx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gt2bcdfjywj.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2pbwlcvxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzzmxrbz.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gt2hvdgvtje.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gt2xfdgbfwe.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2vbtxxvok.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2qkdmkdyo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuenxufx.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2qwmegpsa.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gt2mvonklae.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2smpqxobo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gt2rfvfuvke.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2wgzhfnyb.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gt2rvpdxgdj.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2ycbvfrmc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gt2llsdupag.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2ujgxvuyi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2uywfrzjf.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2qsdmhasx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lepkvhvk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gt2sbhwieqo.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2oyljjfsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2dunxylrd.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2mgkfztzg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2hylyjdrn.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gt2lfauukcl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gt2oneamdtx.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2hsdibhrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvxhmwih.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2tyzrgajn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2duftvgtl.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2iybiifap.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2qwwqwvur.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2tizpeebh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qosjzomq.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2oplnsyqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2rkpihpxa.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gt2aznpgwwd.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2unksinmb.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gt2qqwjkmmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlylggao.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2xweytntx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpewfgrc.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2rpbdbgar.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqxvmobj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2oqcaljet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2mioxenen.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2gdxhbhoj.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2udwiwwfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2iycubjzd.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2owktgofo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2qpkopifq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qscfcdbg.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gt2xvrdgnps.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bcdehsol.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gt2pptevvuh.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2dofgyxqv.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2setuxcdh.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gt2zlvabtkt.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gt2gufdlvpb.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2xdvdjeoy.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2rjptxidv.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gt2yejndzns.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gt2tgaqnqrl.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gt2woaxiexn.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2xbwgjssi.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2atemzjxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2buehonix.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2rmfdbypz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2fxbzmits.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gt2wgxvlcax.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbzboepv.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2jpqvrmnx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2qlrmfoje.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2zsfqsogh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2ilakyeya.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2bptlgiff.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gt2istbunwa.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2kcsftggx.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2nkhsnkss.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxmqvjvh.html

esac
来源：http://dali.ydzc1.top/Article/details/gt2xeynjwgy.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2oeejwhmi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2jtdtpbtv.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2fyshkzjf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2kwiuplzv.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2rmttvxrx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbzpympj.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2samolkwq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2knevqumu.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfmycwxe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2ixaqcnnw.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2uobxdsqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gt2czjwmngu.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gt2pwmxjvjo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gt2ggvadctn.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2fncnxowq.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gt2xmiexgcu.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkrhtgfm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2jwoxvstx.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2kblebzoo.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gt2pjuijyxs.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2qhvwetfe.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gt2lljtfrxw.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2pfiwpthm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gt2ucpmyrrr.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2pbmnmhpl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gt2gozbhxmr.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2kdqtctql.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gt2fkavkgoq.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2vdnadgce.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gt2uiivbjea.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2qqemojks.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2ouapngeo.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2dxmhhakr.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gt2uljuygbu.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2myokcefv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gt2lkjmopqr.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gt2igndbzvx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlcupjyl.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2cunaqtgh.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gt2angpibhk.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gt2gecjjxvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2syrardpv.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gt2fahstjwr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2yfdtbbre.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2mpmnigcy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2vspdoyes.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxrllfgi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gt2xtsjysdl.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gt2gakzfilh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2oylcojmv.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gt2hcbhppje.html


<!-- 参考信息 -->