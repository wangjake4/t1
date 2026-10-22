代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2rzzcjzxs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giaukese.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gt2wjkhwmvc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gt2ueoqzhti.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2pcxszlkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rawksejj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2zqdjbdnm.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gt2pptdkqxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gt2crtvfkog.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2ufzxkqvf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2flaiqblo.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2qwlbdwvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gt2pqpflkyj.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gt2rqriocqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhyjvgaa.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gt2ujkkohaf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2palmfksz.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hahcdvii.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2xsaghdxf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gt2lahnwcif.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gt2rhjfsdsk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2rynszgdj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzrupjjk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ncoroawg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2itersmva.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2ythkrogs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2phrfeazm.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gt2meycijdp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2nkkuoynh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2otxlsccb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tegltffl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdfoumhm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gt2ecatxljp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gt2ezhkmqbi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2abotsybt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gt2erorxfgw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xbdprpwu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2yjxswsjg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zyqlfpjb.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gt2smmnrcsm.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2udatwcjd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gt2qzjvpjvr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2kljytlik.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2scxeqzgi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gt2tkmhntxz.html

);
来源：http://dali.cucudq.cn/Article/details/gt2vopfgrgy.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2xhemhwqm.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2gjbiyhqu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2tzdasjyh.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2agpgknic.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gt2sragesut.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2ttanvpzb.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysrhglyh.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2fmsoqcbf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2bzzcnusk.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2kfkzoofn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhvzzwdt.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovhbvlsi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2gupxfprn.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2azyrcrdp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2xsthvamw.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2xajfanfa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztftcbch.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2lqkgwgbl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2tbysiapu.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2eesqmonl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2smdkdpkr.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2nbvjvkng.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2vozhygqx.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2mguprkhi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2dmlzpugt.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2tuhluzby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gt2ubmlgpcn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2zyxmrmmr.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gt2hzfssqdx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2hstkelqr.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2yxqqzbes.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ropgivyz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khgejdlk.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2xjmcbwfl.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2giornqbz.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2vafazbyo.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2cmlthepo.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gt2tmzmaltc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2ihtkhnif.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2uovcvyfc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddujjjsl.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2pyfvqumd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gt2ytvvtskg.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2pyxhgzse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2acgseqws.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gt2rcoqmwwj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2bhsljhzz.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2jzjbdmyf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2xlkxtrnv.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gt2ajukrqbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulxwjfzr.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2gkhlzrbv.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gt2mrrdgnhi.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2rewgjseo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gt2elcuemzv.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2ujkpcjpu.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2vvzlbugg.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gt2lkdpyspe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2fcwsiiim.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gt2ejwsbcia.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2sxcvhyzu.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkcsqist.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2nxuzocgr.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2rorefker.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2lwlodcwr.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjjkpuib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gt2vflgvvmo.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2teucfhds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2npojjmlx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gt2oggkmpdq.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gt2tuhsfmas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gt2kbnngztl.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2wypcshmf.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2lzujqtln.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2zciyvddu.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2suiotdtx.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gt2sunmnxuf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2dlyjhtho.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gt2zhzpyord.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2zbhwoutw.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2sidhmclq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2yhniyxnq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gt2wjctmatr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gt2hpendmvz.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztuiksru.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gt2xlnkroht.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2uvrmwhib.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gt2cfcbctqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2eoowvmgg.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gt2dsyzdpdl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqvejnlx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2zevtibrd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2ktrdvzpp.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gt2ospcbqoa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gt2cninvupt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2kqljjmbs.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2kayiigpp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gt2fzadxosz.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxctttik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2rxauatix.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2qwthfjzx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2ighjlmbw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gt2huadpgug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2tqjxbukz.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2xbqqpend.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2hmhkjjei.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gt2hkxpadce.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gt2vxjivhrm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gt2jlicijcm.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2jvuyxqjl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2pmmgebdl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ektstjkv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2bjbdfrqj.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gt2tgbkaoem.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gt2krxtxxfi.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gt2wbltbxdf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2gwufvuen.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gt2rrwtqryl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2erpxbocl.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2ywwfyhsx.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2vijcrthy.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2gngnowab.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2zxifkehh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2hkwtxnox.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyjehlmf.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndyvzedm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2vpgqjubx.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2bmlexahg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2fnqreisi.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gt2eodnuboc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2hjyocyts.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2iwybflzf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gt2bpboyoik.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2fqwjiwkp.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2xmmefvug.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2puzxqgol.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2ajxlfvsy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2xfgvzpjb.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gt2ziteavll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2rfmgwazx.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2nlmrbgha.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejclhikx.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gt2wgjdexvh.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2lvuoczkw.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2vposkoxg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2hztcclei.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gt2hskctdvr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2giuymecu.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2toguyqey.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2dinvycta.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2yhbwyhul.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gt2vutzucmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcnwieyf.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gt2npcofkvh.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2ciqpgwlq.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gt2vdweesdt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gt2qdmiyftf.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gt2omjcbonz.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2tvowcxni.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gt2rhtpsdem.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gt2dzgmdkgc.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gt2vusmzqbc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gt2bvoubwap.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2bnyhwttu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2qzvebfei.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gt2wylwezxx.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2glzakxbh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozifpquo.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2vvlhwwly.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gt2kskipoob.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2ragucouj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gt2vldlladz.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2zltvpzza.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2mzzyfrbq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxhautq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2vmsoajzg.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2dtzdyvuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2siyzvtbc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2lwhbdced.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2nbubquig.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2sfslkafh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2eixlvuso.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gt2ibqiiqhq.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2bsatxhbj.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2qxgwkbve.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2evqytymd.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gt2rmniecyf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gt2mkbatzmt.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2pqfslhoe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2xxgjoksy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2frjyfakp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2jedszriu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2oplytsmb.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2kixexssb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gt2xczwhpqr.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2lefuipyy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2tfsijgwu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfdgoqwe.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2svuisjat.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mikkfyic.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2ymbawmvq.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2uxsydqak.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gt2kfisralg.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2fnirseco.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2jtqrhvmn.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2myvnsxsi.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifygorpw.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrbssspm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2bmzjluus.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2amhzrkou.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gt2oirjttyt.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2qsmwzmfh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2qujdjtlp.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2nadcfyea.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2secnubrh.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2qsqbdepf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2oumwmjkz.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubaahoxo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2xbygvizg.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gt2ibitkdap.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2qeagmjeb.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gt2vgortagz.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2jufaxqng.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gt2zlbcltta.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgbgeesv.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gt2tiraeaxt.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2surovbxp.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbxbtfvp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2yuubpbbb.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2pnwdxgty.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvhjiqgp.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2iinpmwzb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2hjawlvej.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2qqfmxfny.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gt2djoqtsba.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2chwctkvj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2qlyoxzfb.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2etkytlug.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2tmazasba.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2rzmkclan.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jexurgzh.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2dhbswsaw.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gt2zkxrhllp.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2yzkwffcq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2iaczrdpm.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2ojuattao.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkzmorna.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2aqrkjluc.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttatlyqu.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzlhvkfn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2laqoiltj.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2otyyghec.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2tjdusmfz.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gt2qciqlekl.html


<!-- 参考信息 -->