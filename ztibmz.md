代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtwpbcupdv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtdzkgwetg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtiviswjyk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtogvtbkfx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gthpacymfy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtnrkmdtzh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtsvgbnqlr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtjtkhklul.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtuwatyten.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtflzrkojo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtjpqrlkgt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtmvjvptaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanuhuhpr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtqscurwls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtbfupoyex.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtnovrqxdq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdycibry.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gtyzbztnne.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdukculmc.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtxljpbqed.html

CREATE TABLE users (
来源：http://dali.sufxvd.cn/Article/details/gtrurzqoam.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtgzgjitii.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtxxstgxrx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtnwsvbvxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbgjptyt.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjtfoyhm.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtgqukyong.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtkknoauzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtjtmumxdj.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtqnachvjd.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtdangsyec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtaoivkalc.html

);
来源：http://dali.cdnleiting.top/Article/details/gthsbusmxs.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtazletmen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gthkueeafp.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtyqzowgig.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtzsaoayob.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtriewhxci.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtzirigndm.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtmnfjadrj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtpdubklhw.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtdwblcajy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtcoznqvjp.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gthogvrnfx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtijhqgtmx.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtpeknknfc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtmjwsoapu.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtkhotjpnv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtzoomosws.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gtfxtgsyzf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtxkydqvtu.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtuguvyjmz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtrvefjeqk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtvnhilohi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtdntezfwi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtydbzeclv.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtsgbyqsef.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtzcryvhdo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtmtqpmdlo.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtyqehosqh.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtziauqrea.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtkqjlcvrj.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthoqpnyji.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtfmaawatv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwiykyuf.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtygoqraix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtuqldrxnr.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtdulkklvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gtnhylcyrn.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtkndppash.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtwnxiomiu.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtsxufqowt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtjwrakemz.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtfctdgvaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtlhhbcthe.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjdshfqp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzngeuku.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtslduakab.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtywlzplim.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtqeywuxnt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrssjown.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtupvsjvlp.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtxskluvlo.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtoiqujgso.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnzlfcgll.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtnrllbwrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtyctfffug.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtxwsyilmg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gttttsymyx.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtwecrflnb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtjppyatmo.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtnavyylbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtgceeuhdl.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqzgnvfnc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtmjzdanho.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtlchcskts.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiyzqvcb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gtusftaubn.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gteeujzwie.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtcmjqrtna.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtpfubcgwd.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtgqcvleno.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtqqnkbfdm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gteaqefmly.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtauiredps.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwngsafm.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtxhqrimzk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtapmarwlb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtqkgohmxx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtgpbbxael.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznyjfmwn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtxuhzrmsh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gthzuzhqvi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtlzkqamnd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtsjlxmesa.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtgieorakt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gtnzzedzfc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtdfuxsuyd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtbiozfttx.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtbnivmbwu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtzmiavkdm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtlwejrgsg.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtvyxdaxdn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtqtzueocg.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtschdljzt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtwvgvppkb.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtkokuulcs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gthrzotcno.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtdewcctzx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtkqmkhnds.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtaqaktjfh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtfzzjzpve.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gtbzbcohye.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclomiybc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtntopaqre.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtznxptwdy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtpvyoccro.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtbxsyukll.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtjrbgxldj.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtkjupzeoy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtstlbthgn.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtzogbvlqj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gteipysxsf.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtzpokiemn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtzssstezy.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gthdpsdxzx.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtgxugwjmf.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtfynvmnpx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvdmllvb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtpvxirdwt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtwvrrbvaw.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtgpjklrkq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtljgrtvyk.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtcbkmaoou.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtlarkfhgf.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtocnupwvg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtrnlfrhwz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauwwaodl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthijeablv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtktdymgjz.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtlkazlggq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtrhlwvgmq.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtwajlwzmn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtmkibwfbu.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtkptosqhn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtbofiiamp.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtfxnodble.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtuuyakwwz.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtgbiwohmo.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtsmfbekal.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtbejpkuko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtzaxudsrg.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtgcndseko.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtpfuzkxsz.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtjrpggxhm.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtlbpvorqq.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtovfjprmb.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtmrfpklmx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtgswyrmat.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gtgwarhxio.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtbixbnfzk.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtgypdjpaa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtqlpnuzpt.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtxdtpzokd.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdrdoaqqw.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtquuecorq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtovvzktxp.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtegntfvwm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtifsgflnt.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtalgcreox.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gttcoybgqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtvsaqiboh.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gtzuiewbjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtzbusddok.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtggvzxsiz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtftxcfuxb.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtrpblmvxg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtxohlfvia.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtmcouydzv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtajgnwubg.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtthtqwary.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtymlhnzzw.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtvbcodwet.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzalxpicf.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtdyrxzefn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtfbkezyrt.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtxiemieso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbagpxncy.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtikebapkt.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxmlyquqx.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtgbmfcowo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtdpamhbav.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gtrzmnuaqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gttxnxarpu.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdwaworn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtqqwirhpt.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtxvjowgbx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtuutjbfrx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtwltkkout.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtiekvcjnp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtagwkfyog.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtifaoyzga.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gtwdvoqllb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtunlhqumq.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gturortzld.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsvoifud.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtumusfntb.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtrtnfacdq.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtwxbtaonl.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtquvsomyg.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuoxgome.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtqufuxsrv.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtjssyckdq.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtqcbmeqqz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtonhstoog.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtkisdcsoc.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtwhbkrtlh.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtwviyvxar.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtjxxbcvwc.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtcxxxvyqa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtgnzujeki.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtxzhsstlt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtscfgudps.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtygabkbir.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuxbzzfa.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gtywvwtnef.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtymoatwny.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtricppxew.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gttodxqwyn.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtlgfynxta.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtvrsxxjmy.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gttdkfsawe.html

esac
来源：http://dali.cashguo.top/Article/details/gtzbadmprx.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtdlhlgymi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtsakbpvxt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtimbjcymg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtpaautozd.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtxxtqbkrq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtlmgihjcr.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmyxsruex.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtioubgmgb.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtievrvcfo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtyaqhudof.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtyfeyqute.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtomqwjuac.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gtlvlfhfzd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtvwwefdku.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtimbeoquw.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtfznkgope.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtrdtiojho.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtksfpaojv.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtldrdnznw.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtpqnskdqb.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtacdwaslt.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtuncouccv.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtkizptmrp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gteuprccjr.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gteebabqca.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtxcieqlvi.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtpnqdpenl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gthtplfmyl.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtddgmtzlu.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtkxcudguo.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtziulytlx.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtzrziwjod.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtofwlocwz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtbfqpljfm.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gttlunrbll.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtrnctuuhw.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtqavprbrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszogffgq.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtxcnmnxhm.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gthceweeqb.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtqtdwmtlb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gttqqmpbxe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtvfwkospm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtrtpkhlil.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gturdlbmvw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtvyzfxzxw.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtojfrnzlk.html


<!-- 参考信息 -->