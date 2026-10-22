代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2boeegwfb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2kharlhww.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2efjlaukl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2hfwhyekc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2qgijpomb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gt2nxfbzmlk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2mctwscsw.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtatuffk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gt2pukvwgjm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kriyebed.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohpkmmhh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2ovhmjuxh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gt2miipganh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gt2ozumxunh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxvotxre.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2wlbsxoml.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wutrwijq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2codsjbjj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mgrozlcb.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gt2zbimowwr.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gt2sxxtceie.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2kxfdpjff.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2exfourbh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvzzkqrc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2pxeimrzh.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2gyylggim.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2zojqrlwq.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gt2smpmtqkn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2pxjsrwgo.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2jjngsrgt.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xagpdzae.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gt2zjxcmipt.html

);
来源：http://dali.redwolf501.top/Article/details/gt2izhvkgfr.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gt2ahscfaey.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gt2ksebdsgl.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2zzogxrpc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2uskkkynb.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2fhdbbrow.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cquikqcm.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2xezfxtfb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbwkrvto.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2mhoouqey.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2qeuddzwq.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gt2arxexmos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gt2rcortovd.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2thajnrzh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2ubwfkkqo.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2sbkmvykq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqbpzqbj.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gt2cwpfwseu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnjhqhzk.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjdeuqzl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2lschckfs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2cidoblor.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2mqnvfcii.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2pwazalwn.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gt2ztzaplfr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2wfedvjjj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gt2eoxdhbul.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gt2oqogibzn.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2nhtldmbz.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2tikpiuqh.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2etftrcju.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gt2ybyjokce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oodrytuf.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2mnyuvezs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2tmqfnpjg.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2seyovvnq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fykvazun.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2hsftplun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gt2wkmluacp.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gt2rggxkylb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2lzoebshz.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2keipdsmd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gt2himnhnfi.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gt2brlwojuh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gt2trkvzgds.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gt2aljdwoui.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2itlfryqv.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2gsifbcws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2bdelehvz.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzvgxtoc.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2hkqutkhw.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gt2xzuinopl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2lrustrad.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gt2toarfbbj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2blderymi.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gt2vbqbuqfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2dcaqodks.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2itveauav.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2ldnxvgqm.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2nvdvjnnm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gt2neifczca.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ddpflajk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2kojwoqzq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gt2uoxblvqv.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlworvac.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gt2voaskpts.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gt2trbzxprb.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2mlluxemj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2dbnjehhz.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gt2dnxgwcoh.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghlsttnn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2uwxdceiv.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2wsjtsscw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzspzsyn.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2hpnufhew.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zibyrrjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gt2zlrdhdbf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gt2dqiheilb.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2znqtluzd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2cifoxaub.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gt2teoeqadb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gt2edaqwtsn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gt2ypwiiltf.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gt2jvkroeds.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gt2ucugzihu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2mnxbdryv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2qgqntekr.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2jckdpzcg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2ssdnuobu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gt2xhaunflk.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mukauibv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2jkcioism.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2vvewowdz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gt2dmpbcoxo.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gt2cwkhdcvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2ricgikxi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2uqxrvija.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2kedhiewo.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2mbnxosua.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gt2zrvcqkwm.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2kzhrfgma.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gt2rhovrzlu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2zokcwrds.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2yrwzfvyb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixescbvn.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gt2ovlmvkzp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvyffamv.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gt2nfobbqhh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2nekmdpze.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2aucurgfq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwyupbyj.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gt2chupefzd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2gqzdwayj.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gt2uktzlevw.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2wfneuwbu.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gt2fvhobykf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2zzdoeoud.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gt2bihbttlr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2cydnraqd.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gt2aekxppqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2hughlcpw.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bljwmjyw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2bbzkfhiw.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2jfoyriox.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2tungzrdp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcbsuqk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2hxyffzxv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2zvipewqk.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2drspbswx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2qhygrdir.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2pylheycj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2zlsirtzt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpggogxo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2breieczc.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyamhwvv.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2mhbiprnk.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2ihnlsnwn.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2jhdtdmjw.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gt2uvbaczkl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2mrnugbrj.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2srzolnvt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gt2zjotkjux.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2ftosabcm.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gt2mafugdrc.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2yeqcgjlp.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2higqobos.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifsacivf.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gt2vztulfjp.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2yfhkrmnk.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2eixzqjtu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gt2qruiddvp.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2dpiomdfg.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2zghiitlv.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdscusrm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdgzedfb.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2brzsqzcx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2jwrmlzfb.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2igftyavj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2hylqjndi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2yvzbuoyz.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gt2ezscylev.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2cnhurqih.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gt2wvubkkbt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2lfyaumhj.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gt2siegisct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2slfmiici.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2xjcvfjok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gt2kwxjxvjg.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2trggiqlq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2lxpiznej.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txtmbwvn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xtgpghld.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gt2yodebzti.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2zptrcuvx.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2bwwikbwq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlfviraz.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gt2jwldkbyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvcppmv.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gt2pbjvpmxq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2bftkdisk.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2pmxwazfv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2bamyszim.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2gdepeghq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svrihhve.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2cgoavxux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gt2gxuhjitb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byrplgkr.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gt2dghxmsbc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gt2mauavjnh.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2daqwaafu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2kmajukaz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smhrprvc.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2lfziixbz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2srysthzv.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gt2ypwmluir.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2txkpkigk.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gt2prsveryo.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijsgpskp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrotswh.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gt2sqpdzuqm.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gt2vqfwxdxr.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gt2zsyspjjh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2esuxewtj.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gt2icidezdu.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2wgjgplyy.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2efpktvkg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vvosekyx.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gt2niavbpvx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2nxdjtmez.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2rvvoivhd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdqquuyu.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2ceosfupb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2kptkcaea.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2qfspoxva.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2dhlrtjck.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gt2jhpgynrg.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2azpvwydf.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2snqnciap.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2debrqysp.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2qfnbstyd.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gt2zohgauaa.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2tkxykczi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2gzonjxdt.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2oalbuqoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2eacffyzf.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gt2ahoxzmot.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2qouhvotm.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2wmftvbgb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2jkqimhdf.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2emgomooj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2jcujokkr.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gt2aavbwpoq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2qbrgbeiu.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2oxmvoqsf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gt2wzmeexup.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2cagsnjjo.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gt2tqxxcoef.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2ejnqqihm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2somnpgtr.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2rxtypawe.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gt2ubeibibb.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gt2vuthztql.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2vjmegums.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2eumuwbzk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gt2ztoawhbo.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdwxxxpp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2yrxicqtb.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpduerng.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2ukcvmprq.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2gicykjuq.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gt2wjeryldc.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gt2rerjhdvx.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2rvhsldpn.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gt2zorcaemi.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gt2samrfpjb.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2jjpedaur.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gt2hoirmqzc.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2vplhuxuy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gt2hqgdgiag.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gt2ovkcuncd.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2poauzdeb.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gt2jvecjbot.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2suonpxuk.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbwdqdru.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gt2dhmjejto.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2hwtleodq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2nkhjgjcl.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2ghsbuqfx.html


<!-- 参考信息 -->