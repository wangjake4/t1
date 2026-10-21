代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtmuacjfhi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtllmrzmqr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtgpaejkje.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtkghfjlzs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtpmaynphz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtywcsnaxe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtstpzvxkx.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtywmmreym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtzqvzwutl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtdklnrdqs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtiawfdvca.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtbvdbtkwb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtzstunfzb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtyvjjrzil.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtjofymclk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtmshrevvj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtctyvjfgb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtsbfihmgj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnmwfwnbi.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtabgqsiud.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtzltykivc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtfwygixdw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtmofadwok.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrvnscvc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtityafsld.html

);
来源：http://dali.xylfe.cn/Article/details/gtpiepktty.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtedueekpi.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtrgzgtjsv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtoiyklkrj.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtportvvzq.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtirrxgbyd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtxynyertk.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtqyrvjuvs.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gterdouwpc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtwzanjrgj.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtviqqvcux.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtdgugvoet.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtidamvqwj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtvavoecvh.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtdmfpshxe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtogtgfdow.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtoywzwkre.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtcgszsqci.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtodajpecr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtkstsdhgs.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtdjmjzjbx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtoswtsgnc.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrjuzkoq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtngxcbzao.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtkkxuzmxx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkztvutv.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtlegwobgh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gttboyydtg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtcxznifou.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtjlrmtjbj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtfygxqcim.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtwbsmirgj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtoywrgamk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtynjrypiz.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtirciowhq.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkuathne.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtbkndwibi.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtpigjxghn.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtitiecdqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnnnqswf.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtgucktsjb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtdhafeefc.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtyjidkido.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtkexybaei.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtqyyjxiqg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtgxrgjdwg.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gthmvhmdwf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtrvbyepwg.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gtwqssktbk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtquoymeot.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmksmhjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtrnhrqcgx.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gtczglbwfl.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmcoxezze.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtgakggprv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtuevvhsdk.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtaspjhckn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvponqvdl.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtzqoarbqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtdbjuwmbo.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtbjpbdfku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtchuduymx.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtkmomuocz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gteuqevbpm.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtujyusckq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtgoydqgeo.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtthmcykgg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtanwapkcl.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gttwoqczki.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtksttjdfi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtagyeomos.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpltqfmkg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtjamnepht.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtwubamoki.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtplkzzblj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtsfvvwuyh.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtggspyueg.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtbfkkyjli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtqlfbfhmq.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtfndahbhv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtqwxtfiin.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtysjyceik.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtpxnloizi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtwktgshbw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gttylpuhuf.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtenfybngl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtrihzejft.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtcffhsqdj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtciqwwmdw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtaipcsjsr.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcucjlltu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtyxjuszud.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboiistht.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gthwkybmux.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtsxowsdft.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gtqbmcaaev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtebosgkqa.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmniwmuy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtkllqcswp.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtriokwvvi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtxujycygj.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtxhuqburm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtwdkshiga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gttlqowdse.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtnowplqnc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtecbgjqca.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gttnhkdrep.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtxzevkzfh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gthslsrjlb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gttqktrupv.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtuksatqgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtfkinyizg.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtpcqfdtyw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtdjinrgaa.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtmfxjgrdo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtpsuomzxo.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtadbrwnzo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtfbqmivwu.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtqaepkulm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtigceyvrv.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtnerguemi.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtjadlbjoa.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtaulclhcw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gttqonqvjt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtxremyhef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtaqhucdel.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoycxsnwn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtsinsfyhp.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtxqhtwuyy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtfjqorges.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gteekxxmkc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfekvehlt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtmifyfsuh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqikavsb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gthlgerhia.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtlillzvgs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtfwzjgmth.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtfxmqyiqg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gttrudifsu.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtyuydggmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtycfczttm.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtezryczem.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpssljhfb.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gtqgnuhpib.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtrezzgzjr.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtmcdgkwac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtqtrbdtaf.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtukpfxlwj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtcwurtmzs.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gthgwwcxcz.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtwyjifwsz.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtcctrlfmk.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtttheyanl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtqlxradky.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtgiivdeki.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtcqgyrqma.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtxuwwkkud.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtkppnecfl.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtrbchunmr.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkhnueezs.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gtkecbrtru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtekraoczy.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtqmdgfayo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtigxrtrvf.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtiihgbpzk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtbzqxropt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtdosyygix.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtbzzwbose.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtghiotbzr.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtnmqjjhrd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtydhbcnbn.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtsyhnuwnz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtykhlvubn.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtlqmimkue.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtleybsfpq.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtsfsaqxfs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxtawjkli.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzuhmxqr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtebhllvfa.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtfbbrcdan.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtelkgdfjk.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtfuupxynk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlykywxl.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtupihcijc.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxrvljzgh.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gtszgoiknv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtzjlpbwuk.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gtfjyaohyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtbwoalnbg.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtdxylsivc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtsnkhxghb.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtxlrlxhdp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtjstsbfnt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqveqsfwz.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtfrvvhjge.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtehtwqxbh.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtmqejzaqd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtotlqkonr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxkoniiyw.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtebqzqjos.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbagpzvwv.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtzlyfixms.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtxzwxalqq.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtztkgpjte.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtvsqlrqhl.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtxjpnsvxc.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtkogdweyg.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtsnspaulj.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gthplitqjs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtejkoflxu.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtotdickjf.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtptnlqcuq.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtfkkyxwew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtuzhabrbl.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkguzol.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtldcmgfvf.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtaobkucmi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtvztsniqn.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbkrbhez.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtumjfjdkx.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtbrqdoktz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtufvlhzhd.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtzmjxdnjz.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtjthlmzhz.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gturfcukad.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtaajqqvdm.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtxcuxpzpn.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtnlvshqda.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtczatiifd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtnsxqrtsc.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtzjlmwapi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtgjgmhsrd.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtgekdnrqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtslkisrhk.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gthnrvbvvm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtggpuybjj.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtucdlaodi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsujrbsrv.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtpqcwagby.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtaiwwxlar.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtshdcpwnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtiexmrzhs.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtgnyenkuz.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtwinualfh.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gthhwoxyxp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtrihaeuwl.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtdvzyqtfc.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gttzppfmyd.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gttudbybhp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtgwoqsade.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpbyjeja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtnkwdtvgk.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtigwmcuji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtrarfxtfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtdeydwcfa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtuvmpyrak.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtelfjozko.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gtrbbostby.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtjvbcemsg.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtaniecvuv.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gthcfdgiwn.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtjkqdqmie.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtusjvclay.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtjspbdqrp.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gttncsyasc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtiftnpisj.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtbbhatsrz.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtztrwjpia.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtmhbqahkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gthqruxfsz.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtqfiogple.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gttxaujciw.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtzpxgtxmq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtkeareiev.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtedepcyfr.html


<!-- 参考信息 -->