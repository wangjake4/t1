代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2wjtntatl.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfmuqzen.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gt2njysmktm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2bcrwuqpz.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gt2gptrsnrp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2sllwajok.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2erqsikge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lequqktk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxwgzrvj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gt2shmwzton.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxjhynno.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gt2kzwynxun.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gt2bcqtphok.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gt2iqrftjiq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gt2ukldzqxx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2jradwvkb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2mqbtqpeu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2desrpspg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gt2opspatpv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2mtentadm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2loiusrun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gt2cmikohnf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2wqofdmlz.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2ftsmxqud.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gt2segxsana.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2zidpjeht.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2ockipsbd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gt2lqwgccnn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gt2dvnctcew.html

);
来源：http://dali.zycfv.cn/Article/details/gt2cjhbedbj.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2csofwsmk.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhcfzypt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2oedvjppc.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2iccsvhig.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gt2bfyjmhxs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2kmhxdsrq.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2asunhiec.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbouvtum.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gt2cwepoelr.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gt2nhuqtxzl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2jqhlizun.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gt2odyvkkku.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gamxcius.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypfqzbxc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gt2vkfdridh.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2gzeynozv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gt2hzkgdkzs.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2xwaizufj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2mzpqcqyx.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gt2dwwvgrnk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2dbdwjksf.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2tounuict.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2chjhgjmo.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2feqahdni.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2hsjunqis.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gt2gpartqiw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gt2ncmnocte.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2lqosnvri.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gt2nazmajqg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2gqcrittt.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2hcltntxt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2tipywoiv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gt2xjtglztw.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2bfzsefqq.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2gqdimequ.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gt2skpiahti.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2fqojzjrp.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gt2mbnjcqfq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gt2kcsbyihb.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2aaxdgrqe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2pcpfpmgf.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2xhhjxwfc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emizkicw.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2qtarmrlv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gt2fzdouxrf.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2vvjmxrso.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2coliwkkh.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2npzssajf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gt2euuquhhr.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2usnmcfwd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqkibgop.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2txicfnxc.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ewdwxtrw.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2inzvasni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2briukure.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2yfrugxsy.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2lnthyptm.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wicbsovp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zaqpryjr.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gt2mqvrmzle.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2wxcjtiac.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2cxisickw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2scudqelt.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2zjrchgtg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2nkeasoit.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gt2yszppuku.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2yfpmfyse.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2oavsskqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2ihjshjho.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2jwhgbrlv.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2xdvprtfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2hwhgpouk.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2wgzszbou.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2qnzzufpu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2lpektkiz.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gt2uqlmcdsn.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2twyewdyp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2kcoapvzz.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2arxhqurr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2sefkzzhq.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2nljqshpa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gt2puscqwho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flnavfxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2ijswpzol.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpatqqms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2kkahlmyk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gt2obbpnhpw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gt2bbvlvgov.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2lfpwcixe.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gt2aryiafks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gt2qtzujcio.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2vvimingd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2ovxoyfve.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gt2ooqufumc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gt2jhkubcuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2kqsxyhaf.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gt2uucgjyaj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gt2csryrhhw.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2xvolascz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2oxbynjpz.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cowthcqd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2hzmwhbkp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gt2jxzfvfgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bresrmqr.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhdnbcud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2phtemwia.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2qyehclrn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gt2ouzyqrdu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gt2mrwjficm.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gt2axpwruxb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2ecmkbkxm.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gt2yyubhytz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2djyfrsoc.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gt2jhwiboxf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gt2pbbsishp.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2rejjuioe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2yhzjpcmn.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gt2bbowzwlh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2bmowhndr.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2hczyuxxo.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gt2dipzgsud.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2mdkrzwnu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2frjyggpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gt2irmodyuo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffunpnfs.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gt2kltjwzyo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2bpebklvq.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2qqkdivlh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2gfvwwlqp.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2kryihchz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nisqcrtx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gt2hetfcods.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gt2pupufbae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2nkgotdrn.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2scupggwg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2ahjihspp.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gt2yieamzhm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2gntosjmj.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2biftshob.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gt2mmjfrqai.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2aoqszeua.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2sxnzybju.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2jjfvjhzo.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2iplkddiv.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gt2qgydavdk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2gpjpbuip.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gt2pgmwxsdi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2ahziglyd.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2hptvubvf.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2pjwchuiq.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2rjbrggwx.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrtofwkj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxexthvz.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2birqbpxr.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2mxilvkbb.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gt2xbjtlztw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2zvhyaqlf.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gt2kpkyzeit.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gt2zzbsfijm.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gt2wdsrrzxf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gt2nzxczuda.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2gwfmzpgj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gt2txsxlqjn.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2ksnkfiqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2bixakzmd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2uexknlcr.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gt2terlsbzq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2ranamlyy.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gt2njaabjvf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclkpps.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gt2hftahufy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unothilh.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2kzkgmxik.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2embrmmgq.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2souilxer.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2kukgjiwx.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2yshhphux.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2atolkzjx.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2mkvriixe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2vjewcnyo.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2waqresgu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2jvtoppyc.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2dtzytuxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2mngdmphw.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2knejecgq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2sxsszmwj.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2sphptiog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2onvjjfeg.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2mhuoqjdg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2oyixyqqb.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gt2zfyqhqxs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2jkmqsmil.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gt2oglgqnwo.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2mheqndvj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2gjkxqtsh.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2ymkworut.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gt2eydplmzy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2medacudx.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2douibfov.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywekvhqx.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnccnmpb.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2mqhvhjgh.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2wyxmisok.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2mordnkvj.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2zaofpvxm.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2rtzfrssm.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2bpvaplpx.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2bkatjekm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gt2eaburbhd.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gt2odsihwnj.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ritzijeq.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2hctgspho.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2peimghjl.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2eayswzxb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2ynnvfgrb.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2qosevxus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2ahdpsmbr.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2lxeslwnz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gt2bcsteohk.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2jqcybknk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2ojxymnrs.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gt2yhliehlw.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2qxdjrjug.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2llzcvklt.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2gcncwsnn.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2sljdrpzw.html

esac
来源：http://dali.sufxvd.cn/Article/details/gt2kggncyfk.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2marirxrj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2yvkqcjgf.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2zvbuwyev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2fdgvpcxr.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2mqdedylr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2tsffdtau.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2xquziryi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2kacipavc.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gt2nyvodykr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2umqpooyp.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2eshzylqx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2phjaajtt.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gt2edsejjda.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2edhtsztt.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2przxtaig.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2zbixqbhz.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2nixrmlnc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gt2gzyfmzxo.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2opggokwf.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gt2sqkaphpr.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqrluxjd.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2tevjvtev.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2prsfasxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2yxizwrbu.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2hiftuthd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2emimtymv.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2jglfdyuy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2kdbznizp.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2qigzznhm.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2uehqzlwn.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwtinmuh.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdzyrojz.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pygzztxr.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2avjzncpe.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2gbleviut.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2gksayrym.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gt2krajkobr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gt2najkdcog.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2nuphqgen.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rpwprsqp.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gt2okqqurhc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2zgjhlpnl.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcqejlxd.html


<!-- 参考信息 -->