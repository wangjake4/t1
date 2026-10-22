代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gt2erzbjfuj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gt2gnzmfmlv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2yjeygqir.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2ywkegksx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gt2sclrjxet.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2nmyoriwn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2imspnfft.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2fvncyzam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2weovhoki.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gt2ofosepam.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2oiumzuul.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2rfkdfyyw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ttivmcgc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2bizuzqmx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2odovwhel.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpvuxqlj.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gt2fsnqpika.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2febkjpol.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2bwuaddqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2ajiirhzc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2wnbigxaf.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxazjzte.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eotbomrs.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2cjqsudjc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2enxbhvcl.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2ktgtmkux.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2zaaykuac.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gt2pvqeguks.html

);
来源：http://dali.iojbl.cn/Article/details/gt2dzqbbmeu.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2skpltdyw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2zbucjupi.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gt2bdkinmdz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2qutohbwh.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gt2pvhniexb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvsyrygx.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gt2xdgmriaj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2iqsknreh.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2mhbylanu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2itwzzqea.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2jtnqgenw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2zyugfrso.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbysrsvc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2dzfwwimi.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gt2vywfxpeu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2iewkadlf.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2vozweusp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2ekrnyksn.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gt2ihrnybzh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2kuaqdvfy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2rzicmaeu.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gt2cfmuezma.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2qwtzhoot.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2zoqnxvox.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2prvnmded.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2cweuznhb.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gt2ukqxujkn.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2ikiifopg.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2wyeuqpwv.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2chirgceq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxijctc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2okqmofdr.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2hlcrrrbp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gt2pyqymtbo.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjyckcix.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkyzpwgh.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gt2ouavjfdp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojmkytsw.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2prkmgwxa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gt2nekrfknn.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2tlskggrz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2oxwgaupq.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2viutdybr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlplky.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2xdixlqig.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2hrfevipy.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gt2qfvjpsgt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gt2hqevehmx.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2ivcwkwxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2jistxvgx.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gt2bsaakkck.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2cpkcmlfq.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfmiyygp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2nppivbae.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2syuoxbjl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2rcutblyu.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gt2ylntcdds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2juhppytl.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2wussqrww.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2ybfvmvmg.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2dglxegfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2mvndjyjj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2dyiaywnt.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gt2yrpideuv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gt2azyuwvgp.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2npclwwio.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2ijyescaf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gt2nrspexmh.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2dtznknqv.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gt2zsiuauil.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2blzxfrcj.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2ubvxuhct.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljoiasne.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2glnjinxw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gt2ulfqmldz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2wkikudxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gt2gpbtcmso.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gt2okfcuiei.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gt2sefdhgyn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2uovlkjnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gt2teymqtfg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gt2hjlwdrxu.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gt2axapsntn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2oiaechko.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gt2sqxkvykb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkmgrxdi.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2migtsjas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2mlnnkvdf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehvtahih.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2jwaigdra.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2acpzpzdm.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2wjhmetfh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gt2fkkzwaoo.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujqzdpav.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2etvloypr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gt2antvkluv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnpreebu.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2mkmrdtpu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gt2aohhahho.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2srjzrgpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srskfxso.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2ezsnfbaf.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2pzmyzsuk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2gspbflol.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gt2lvuhnkkj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2jndfgvhu.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2aofzfbdj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2mknvayca.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gt2dkefmwey.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2afgwkqjl.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2lpzjcwgl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2wvqjeecp.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2efzkswpw.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2pvnlhcjn.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gt2aohshrjx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2rzalosok.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gt2gvwminfw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2hidirkbd.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gt2rjlwqbfb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2mxycinll.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2zdgmifar.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2fpfyxqpl.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2evlzuhnf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2glrikydf.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2hzaguzpu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2ffbwxfjg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2rwplgneq.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2svhjhwny.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbqmvkrh.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2vzchrhaa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bukdrysm.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2etwzlhyj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhrupkkl.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldumvdwj.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gt2oahawnfs.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2nrgrhomy.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gt2rigipujr.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjtxjsmz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2glyfhzje.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gt2cuflgcje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqhpaasb.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2zbzfthlc.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2fchttsoa.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcuxkbdg.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gt2usojpqic.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tblerbly.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2iuqywgtv.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gt2ypgcaoww.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohhdaagl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gt2ojfcxzzv.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gt2hnlupwkg.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2jjywzuil.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2hyxporun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzpgjtgc.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gt2zicwwruc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gt2ensbxuzf.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2xalzsqoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmgorkid.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2vdpkhqns.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2ouuibwha.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gt2ivgxzqiu.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gt2wuikttqi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2idmnqwdh.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gt2fnmougsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gt2zumtcpip.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2sdqcfvxr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvmptmnz.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2calpruln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2jnookhsz.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2orzilfrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2zzhdrupn.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2imeypgrt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2zmsznkau.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2gnvfvill.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2orzbqiuy.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gt2fxaapahf.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2qavodsyb.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gt2qxommmyy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gt2aouzfblz.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gt2qxzcwmbj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gt2fsiyjtob.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2egjvjlsp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2almoayjf.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gt2ncqtdojb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gt2mfviixos.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2kzocdumg.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2sknnjltg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2taowqypu.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2tqheumqf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gt2xflwossd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qizknqvm.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2lgpfbgfq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ppzvgsge.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gt2ihpmfxeu.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gt2uouxzrxu.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gt2oxqbuiqu.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gt2grcaughm.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2wjulebdc.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gt2jwunfjol.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gt2nyghnjmi.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gt2hdtuvoxz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gt2oyuqktbp.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gt2unufpawt.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2eczvdbra.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gt2ffmtljur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2wbjfamkf.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gt2xotbiimv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2kizhkvtl.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gt2urvqumfb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2iuxxiask.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2zfccgdvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2vnlzidcp.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2kdhblgft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2xebcxhoi.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2etdypodh.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gt2hyymsudl.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2fyhmfkcw.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gt2ljzrzlub.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2tekewxze.html

esac
来源：http://dali.meibo888.top/Article/details/gt2ofkpdzfi.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2sflzryfr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2kayxffnk.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbxzwpkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2yzilxjnh.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gt2dtlvlyrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2drrbgzpx.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2eqfmdlal.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2zgvyyviv.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2uvwbedee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2awknetmd.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2sivqnxtc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2bkkgzvxn.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gt2kirczutc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gt2fkzginyz.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2zhslmjna.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2titpkmsu.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2sdcfxwmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gt2wpydigfp.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2ausiojzu.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2mudgtkgw.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2jezwfvap.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2zkhlxskm.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2flivmcyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gt2nwolfyhw.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2uulbuuks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2qnliounk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gt2wjkccqis.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gt2dyvyesjk.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2zcxwvpcl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2szhufegy.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2qekjmtgj.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2ikzkwdtu.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gt2bzldclkp.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2ehxpawuh.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2dpzjeyhg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2zsguwoqt.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqdnpgfc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2klqpuaqr.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2fcpqwmqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2jeakwoha.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gt2nkghgsir.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gt2ltskmibl.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gt2fazdnlks.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2ximwatgh.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gt2yydchkwq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2cgskwjpv.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bamhfxmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2iqprfjer.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gt2panybzzu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2wofpzwmk.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2cxyamawv.html


<!-- 参考信息 -->