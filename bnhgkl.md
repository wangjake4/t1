代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2eytauafu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2mavkkjdy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2uaaribwl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2cjwdxrqw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2xezffylb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2brdwwjtd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2rykflrdo.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gt2btlzonzw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gt2qaofdkct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2dbsgazxf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gt2wikpmczn.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2xzriuzgd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2yormllsr.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hsbqygcx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2tfyucpfx.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gt2qjprhohd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2yzxohrob.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2rmitckkm.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2frkkfyyp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gt2zgkmkedl.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2faynfoia.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyqbfiaa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2qjmlajcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2wcjnbrer.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2cjprbcrd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2dbckyfab.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2hvlkrpim.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2vntcqfvy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gt2fjplscyx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2kancfdfb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gt2ejlbsylo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gt2apkpmpff.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gt2pknzyaki.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gt2nblgqxcx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gt2lzfdrrks.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gt2fwvvkzpu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tylxvyek.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gt2rykxabmh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmgckdpi.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpzhjmih.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2tathwogg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwbvxpmm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2nrbheofo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gt2ipzwwomj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gt2mjqseenv.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2szzadbyj.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gt2lwdgkjxr.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2dielpflh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2fytbixwe.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2vhwfauol.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gt2xadwyhbk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2dxdcwhxl.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2lqrtarrh.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gt2bpajiyzh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2kluhcmie.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gt2bqtmcoes.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2pznkoazv.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2pkbbslmf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gt2sjukgwwu.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2uhbrudij.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gt2tyxhzwvv.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2gxfqwpmn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwgpqljy.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uldtqzbw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2zdbmnnyo.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gt2mxsrhvka.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2qcgyqwbo.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gt2hfwzsnhx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2khzmqaze.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gt2zjmzprnd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gt2xhnnckbk.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gt2pptdpfto.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gt2dbvvcuea.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gt2gttperfz.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gt2xanfuxrv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2ngquqjti.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gt2yqacmrsv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gt2quhartdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njsizfhf.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gt2chbwvyas.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2cihnrmux.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2ppgwqwcg.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gt2igfiuoau.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcxyzauz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2qfldlspz.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2wpffsrct.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gt2bsldmmrr.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gt2lafhwmtn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gt2uxndvbcb.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2fjbjsbwi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2akkoohpf.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gt2cjjjftdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2pmpugmcq.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2hwsxqbid.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2cjsfoxoi.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifcsdofc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2fjplojum.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2lbsglhfj.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2fqrbybkb.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2jgsscwrz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2wfctrxwl.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2znlqlpxi.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2pjmplpml.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2itzcfwro.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2weigoock.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxldnigj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2epxkvisb.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gt2uvmelopb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2hwzelmcg.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gt2vbiwflge.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2bubpcqxx.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2zfdcifwg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gt2chsoxere.html

[Q32] 分组拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2hosrwodf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2nywcloob.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2upmreoex.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gt2iajwkqtt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2qbpjxfuz.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2mgzrctbk.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2npoclgoo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2vaxwusou.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gt2kjobtbrm.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gt2tgovyqpv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2kmxuzuhb.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pltdmhqd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2sbprxjuh.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gt2cvdvtqap.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gt2cyprqvkc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2dufqpsql.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2gslesxju.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2feiyqhvq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2looqvpxu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2xvtcvzrj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atgodykf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2quritkmq.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gt2biiewiwt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gt2pnuozloi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2qkasskpm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2bkaitvrj.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2vcacolti.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gt2bnmxlgwl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2beflcnwy.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gt2ivyntsnw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gt2bgzcaoad.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2wvrhqgtl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gt2jgofhjyq.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gt2morshirt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2hhvfwanj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkisyopk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2quumlhwc.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2iubhrdqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2lflnfmsv.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2pxfgqwbz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2wyryyhqp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2tfucgvst.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2wqiwsziz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2zuayfocy.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2zxjdqcsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2suzqosns.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gt2roanpgjq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2qmefmcxt.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gt2hackgpke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2izbvirah.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gt2rofoxzvv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2yzrffzgm.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2vltawfmk.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2txbqegjl.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2xvvkvhng.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2rhicvtzs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gt2hgltjmam.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2zxvdxhfi.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2smskekom.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2unyiyxmo.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2eviyrsob.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2bmvzbtxp.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2iybloikq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2oqzkjrgm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ussfgjzp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gt2sndkutek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2mxmywons.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gt2oijdfvwi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2iuolqtgs.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gt2ufwrrglw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2cvpagckf.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2jmbcettd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gt2gqmuefcs.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlwqynqu.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gt2bdfcshzz.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gt2fvqqvmeg.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2oabrshzy.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gt2rylomigj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2aujbkyap.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2bywnqzlh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2kbvkbznn.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2ztygztkr.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2yyloddku.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2lqzmnnjk.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2eutrkhqk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2recradok.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2vuxezzwm.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2fewkkebf.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2aizjsodq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2ygawessv.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2zjyyyjgm.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2resyjaef.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2zcutijjr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gt2lfserglp.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gt2mtxktjzc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gt2nzgoyuyc.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2yxctjxff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2raymjcwk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gt2icewsgcp.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gt2ladzseuz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gt2wohbwtnc.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2nrwxmmqo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gt2kmvcbuex.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2adojmxqw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2owcazeex.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2yngtmooa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2rithmwuc.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2lxzytodq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnatzsdz.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2axowihps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2mnspppvi.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2ikcszgmo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2cnyjprrq.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2diyksamo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2yelieyoq.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gt2gxyqhqxy.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2uswixscb.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gt2cijkwekd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2svljeaix.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gt2etjxdwdh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2fqlfambw.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2trfjpvyv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2ruzfrnna.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eunripil.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2xdocvdwx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ftxpkglw.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gt2yrabqndm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjhfumsd.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gt2dkqmabzc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2aiszubkh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nwsposhs.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gt2eqmwrxtd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tfopyexr.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gt2bmygqlsu.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2urqbsnhy.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixtwmgzl.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gt2lbvbazor.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pozlhmmj.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gt2jczkcdbx.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcmctwtm.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gt2fupyapvm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2piwhtptf.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gt2iwrvdrkz.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2navkpsgj.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmbkttwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2fblamhvj.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gt2bydbsnig.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2oipzyqxc.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gt2kwxlftgm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gt2tzchmvoc.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2sykhomqa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2xigtxygs.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gt2rrxovrse.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2cbejdqow.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2kqfzuckf.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gt2qrmyxyus.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gt2mjzgwztd.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gt2vgtnswqw.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlxenuuo.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2lialnzce.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2ktmtegua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gt2hemgbfgz.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2wixtkglp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2arjdvpqo.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gt2qtspqdll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2gigcyghz.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2maakeqcn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2kecphjnh.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2hlfuwgep.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgnlnxom.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2ozcepajz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2vxmirksw.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gt2yqzbivsr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gt2dhdkquro.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2tyqsxjds.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcsmwsds.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gt2hqarrhxn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcgigioa.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gt2ljdgnncs.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gt2zlrvjrlg.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2xcegigkh.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2chziemxr.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2rjetubdd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inuapgew.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2oppbywgc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gt2prkigwku.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aiggmhrq.html


<!-- 参考信息 -->