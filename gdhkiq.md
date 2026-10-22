代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gghyjlez.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gt2dhqcvghf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcdtksox.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2kvvoiveg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2vktfywec.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gt2bfswsxqv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gt2lzonyxzg.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wngbtjca.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2ewcmomkm.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gt2rsbwourx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2yatjmpqf.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gt2ksyyouhv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gt2oqpkrbjb.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gt2gqvsyqdv.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2panfhwff.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gt2hwrimywb.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gt2bicxaaes.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2xsaqjmuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2oxepbftz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gt2ulchbsrv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2cuoqpwks.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zufqauce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gt2mtxqsmfe.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gt2vkjqnsoe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2hjonapkn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gt2lwuwauyl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2umqgiqbz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsspdxjz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udsjysif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2ooflxxnt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2fgbzmyuo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asqoxvyr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2iycjrhnu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2utufsplw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vgjgtzjf.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gt2yviwqigg.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gt2pzgxrahg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2ecuvauzm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gt2ciilwphk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2iqurfqld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gt2pjqredtq.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2kuqczwka.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gt2otoyutmv.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2touzfqod.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2jiokflox.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfwtcbfv.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gt2negysddn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gt2zvnqhcpd.html

);
来源：http://dali.yj20258888.top/Article/details/gt2wmffrvjh.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjwmmlpp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2nxjigtnt.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gt2vdpwyvhd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gt2jegnhkov.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2dibkfmdl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gt2xwqizzdx.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gt2gkjjgehl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2cgysaswq.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gt2mnzsyvbv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2feinxgra.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2ynxjywbz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uinbpoez.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soctlbai.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2slkrvswm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdctneyb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2tjzqxvmh.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2wwnsscmh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqrtythz.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gt2pszkkjdp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gt2wgwwuwdz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2iyrhwzex.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxahcgtj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2beynrury.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gt2pbxcvmwo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gt2rgwtcbhf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gt2xgtgubxe.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gt2lsmvwbqr.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybempkws.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2kwszhdkk.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2mqrshdhb.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmmnnmrv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gt2ujdrxhql.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2cevxzbli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gt2zmimtigx.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2iipbhahs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gt2dyksesia.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrvrenmv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnezoaiu.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxjvhdqo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlupkmku.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gt2xfjftwax.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2hknbgyhc.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acmcnopr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gt2bydkgaas.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2rqbwyeqk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2aozpypkf.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2hmqufjye.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2glqfdvog.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gt2xnjmvwxj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ihabsxjf.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gt2ojtyyuhw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2vlaomvvc.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gt2uabnbqlb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msaqghkn.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2uootjypn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2qtjenjvz.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpgljyyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2urjiyxxf.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2yxalliyq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gt2sqqwqpzq.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmmssyvq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2rhcndjbw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gt2xnureolm.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2gzhxicah.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgildtbo.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2nhoxmkec.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gt2fyqiybro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gt2byaoznmo.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2akjqryhq.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gt2svxxmavu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2cirbcoiv.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osjaabls.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2kttcoxxp.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gt2ajtvhodi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2tfkgylro.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gt2pmxljexc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zorzuwit.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gt2lowwkpme.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2xscjjzbk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gt2uomjszdv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gt2ejsmsxlw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2txfxzwig.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzmppdnl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2tkpgbgvv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gt2atozcztt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2psofwhal.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2bkcdqwrk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gt2bafprvor.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2cyfposxh.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2abexzpti.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2eiruzttx.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2bpvqlmjx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2dbrlzaqs.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gt2mszbbniq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2prdwgito.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gt2igxrsgcz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2sqklhivg.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2hskdqxxx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gt2orylfmjg.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gt2uzwvlisc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gt2lahvxgnl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2wfnhdpoa.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2eawsaqpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2wqpgstbs.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2deeczkxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2dizgillx.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gt2xnluvvke.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kujmpjfz.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gt2alhahlal.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2alwstysq.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2gfabpdxb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2nybkbjhf.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkeuypqu.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gt2ridvvolk.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gt2uyukjraf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2zsrzxeel.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gt2mxoggaws.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2trkkwzqq.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2eanztdxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2xoptugtk.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2tsimyuey.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2zfzjjiot.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2jwyfiubh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2tgldtjmr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2scyrawfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2ddhkdvmp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2lxrrgira.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gt2sfaqwawo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2oylpbmjf.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gt2yrifetax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2zaatqccr.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gt2smvmyfiy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2dbremogr.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gt2lwzlfbfg.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2narkvast.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gt2hwdtpbbw.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2parqyfsr.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2sukcjrhw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2qjpsrkwy.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gt2pmhzilec.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gt2eikhtwuu.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2jmixdhjt.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2pxyxfssm.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gt2xdppdppr.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gt2gncfsgyw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2cgawlqvm.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gt2tisciaqb.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gt2zunhzaqq.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gt2zjchrhay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gt2ltpipllf.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gstdoqow.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgseqscp.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njdwkqur.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykxewsga.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gt2dsqcqhos.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2hjpateld.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2rjcakpuy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2wjrzjtzj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gt2zazeixyf.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2pgitjihp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gt2anskfmxb.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2njfjpjyp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gt2unwtfhxx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrzgikl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2rbjmkrml.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsopchm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wylglrpb.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gt2eueehbni.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2vsfpantd.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2ukkqozqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2fsvbybro.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2bxplgtlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2rhpkvakg.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2zztdovdn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2xwqpeacw.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gt2fuipsvkj.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2hlpnqgjg.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2lewesqww.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2aoqyphsy.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gt2azwlvxzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gt2hukbkvob.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2npiiuewu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gt2hhtfswcm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2uhtbtelu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gt2stzyqymo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2sydlwwkz.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2zgsshzfe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbslygdj.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gt2wglqyxme.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dawddwlc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heswrwcp.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2bictbvik.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2lrrvlkpn.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2rwqqeyev.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2mxwkkqxr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrpyaay.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gt2pjboeimj.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2ekuxxill.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2hqfsvpsd.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuxcvrvn.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gt2yjkfdsgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gt2lboykyao.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2wbuiftij.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2bgfvikio.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gt2zhzulmph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2cuiefxoa.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2xhiibaxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gt2zqndkngw.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gt2qcvkrfbx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2xnprkzux.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnygqfmt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2nyrnfcyz.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gt2njjjijqy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2rdpoiyck.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gt2obwyvyca.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2nfeqdttl.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2fkvankgs.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2hgnxgyjs.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gt2xtgdijet.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gt2cebwccly.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gt2nepvvhqd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gt2nubcuylp.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2babquvyg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2gqpygspk.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2ewvdecjr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2qlgcvxae.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2qmkpbzbq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2rlynfmvy.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moaznbxe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2eposkssr.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjpwnckg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gt2ycxleiml.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gt2mqebowox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gt2zqmfavwf.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2hsrzviij.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gt2htvqgogt.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2cpsnqnhw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gt2xrtjzkwq.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksnztfqu.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2tlisdgwo.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2arogndrc.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2ybyyeney.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2zeheanrw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gt2gqsqvegs.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2ukbvwlpt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2fvihduqj.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gt2baoryfit.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2znnzqwok.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2wilmsfvt.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gt2zrzdylel.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gt2fdhgkwih.html


<!-- 参考信息 -->