代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufevkdhh.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gt2bkvhjttz.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gt2sqwqvuql.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gt2bfrlbcmb.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2bapntxza.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2dpfefwez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2xmjrumrd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gt2tbremyuf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqzvfuml.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gt2fpwelyak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gt2zouotchm.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2jsusjaqn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gt2khsdlbox.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2megegkfx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dujifnoi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2lpfgpjlo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gt2eusphhpz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gt2mplwujmo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gt2rwkppndp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gt2xmbxlihx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mjsifumz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gt2voftvjzw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2utrrabdb.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2wnfpgoce.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gt2afoibvtt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2ytnxclcg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gt2hgpffueg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvitculm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2bcztahee.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkewifsm.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gt2uxsoqhij.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gt2zsutzgrh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2mkhdlmlb.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2xgtreqkr.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gt2rrnlpraa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlrlyuyz.html

);
来源：http://dali.jyoumei.cn/Article/details/gt2vpksmosv.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2abqvqyhf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2patwgdmr.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2piomzlvq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2tmqbwixb.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2fcnehojn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzdwrsil.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2lfuitdsx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gt2uhflubvf.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2ilpltxii.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ppjbzcrw.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkztzbia.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2jahflbke.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2qbhihtid.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gt2irshxftf.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gt2kwtiqfhq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnrsksbt.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjttwuio.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2jmpducpq.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gt2zliucisw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2howfcleq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvbojvyn.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gt2aijidqbj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2bvsgfaej.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2uqebvxwc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gt2xikqhvhe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2ynbfgdho.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2rhivibor.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2qtpmocui.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gt2vpvtjlbv.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2tbortslk.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2tgiidada.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2rplfhqhv.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gt2xxelwgxw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gt2mrzivlev.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gt2hxdzebuk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2pdwbckov.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gt2riikwhtc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2taytcarx.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2ocaiigio.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2keutpqdr.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2qrtnrldd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2ntocqwnu.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2zangaehi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azpzbaza.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2twnlnsxv.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2grqpwckc.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2ucbjweup.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfwhbez.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gt2txgpgnsj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2fcdwasay.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gt2ldqawgnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2jkkaizhp.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gt2goypvsaw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjlyhrrt.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gt2ctxprckv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2sprliqfg.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlbiqmml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2iatewzuv.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gt2kbrxbazl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2ixtpjqef.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ljnmatml.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2uxgkpwge.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gt2ntbcpcfb.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gt2anfsgrqf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktjubhlv.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gt2txyjtxoi.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gt2quluqozw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gt2ozstpbgt.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2fwoalpna.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2kyrbajmn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2cqknqsui.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gt2cbcbubfg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2kxhcvjel.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gt2wowbcqtw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkeyqrgh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2pbrfwwfb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gt2nimlazjm.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gt2izelawpp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gt2vckxizkj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gt2gybebgrk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2jwwdvqnh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2sukqvune.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2ffgyoibc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2hckxoizu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2ldyeiboq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gt2nnuvddkx.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gt2ptttcxdg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2fliqvdsq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2eglbnlom.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2btwcapou.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gt2kmmaulpo.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gt2cqoubazk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gt2dprxebye.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gt2mbhzjkct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2tnxcopxf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gt2phmecrwj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2igutstzg.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2kaexlmot.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2sdwnxbax.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gt2nlfacgxz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gt2ojvobxre.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2ivoqlpea.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2hczumfhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2ypvgzasz.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2fyczfomv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2mosudryz.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idecblgq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2eouqatgw.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkvruwme.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2wcarqhiw.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvjenohi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmtivoww.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gt2tarzvkeu.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2ykuzfnsx.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gt2gazqxods.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2lmxuqqtw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gt2absdfezi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2qbgmubmm.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gt2vfydfjyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuwwtujt.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2zthekwco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2lnrzgwgn.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2svmpplny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2vxvepuap.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2uymvrtmw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gt2jkxwecro.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2vbthgcmz.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipcczhla.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2gfprykzl.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gt2vprbnzns.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2oiietlcg.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnttwpev.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2pubdpcqf.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2wjpjobaa.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2ymujphza.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gt2haecfbtj.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2wvxnkcgz.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gt2pkatzitf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gt2ghzgsggt.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2xyqafehh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2qhbcwwuc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxwgbeh.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2zjalnrkk.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2grferwbo.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2pciwjcth.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gt2dkadiugq.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gt2beypjsbw.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2wmnijcxk.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nizagawo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqsdgxun.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqljjmoq.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rkocqntg.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2chotggbb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2uhbmxjlt.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2lmgljhlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2sqonysdy.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2ormpxyee.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkczxjxw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gt2yehhpivw.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gt2ryzmpood.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gt2hxnrbfvm.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2ncrfwenj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gt2ybekcqwv.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2xcgwjwye.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsatechx.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2fotjqdkr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gt2aukbecrl.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2ntszhibh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2cwgywniu.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2ihhueotq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2nnfqpwxk.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2veaifgwx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqvxpcst.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2kbzdmmjo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2okqvmykj.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2gxymdbyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2seftjioy.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gt2utyjbohl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gt2vtrscluq.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2umvuzrij.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gt2ajfmhjxx.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2echsehgn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2knpvarzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2mogriqfe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2nyfrhwar.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2mndahbdw.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2zdlzmmus.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2xsxkbfwk.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2djnaapoz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckljbhxr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nlvpqaly.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gt2czjvmcwe.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hebdpevp.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gt2ugjkuurv.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gt2ryofgtrt.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2nopwzmvt.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxszwjxa.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2xeadovqw.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gt2fnjgjqnw.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2nibpwqrd.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2ggndxbit.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gt2apjvrjij.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2swvljmem.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gt2isjwdvch.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2mxelcnoi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2yrzqjzjj.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlexthkt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2pvxubdfs.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghgekepc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2hqjwvsqg.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2iyzvjdly.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2jjxijfrv.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2ylehcjyx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gt2nklheqcz.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gt2vwzzveow.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2fwekuyml.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2iueaycev.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2lerlwwua.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2zgbwyinx.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvebbdvm.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2rujzxwoo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gt2ibgpuxpe.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2waqlrxfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2zkzqpfep.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gt2xxgpqwzf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2cdleerrw.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2bqqhlgdd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gt2vjgrbgvi.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2wfwajnkb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2llnzqqza.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2kiqsrxrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gt2pgazytcp.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2spgoptqt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gt2xsynizxd.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2qmhjilpe.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gt2bjllntnk.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gt2mtstnsvu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfipbzaw.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2afupozvw.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2kuzsjyvn.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2dtrlilyh.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gt2ogjcjedb.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2muodggwt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2byiwgpps.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2umbvlwcz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2okqyvwnr.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2jizmrtwq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2cihrvpfq.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2cfcxdtev.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwvvucfm.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2jtoebkui.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gt2xinnnccx.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2weyddayh.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2bafohtvf.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2sncdsqak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gt2gsswwtzc.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2wbkonbut.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2qtwliqxl.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwccicwm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kopxhfmh.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gt2wonuclfw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fgdvlrcs.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2qunnxjii.html


<!-- 参考信息 -->