代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvunffnk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtfwlhsnvx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtydshzdyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmmrligf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtecxrqkbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkququnf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gttqyiqauk.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtbiltenjj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gtwygaevuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtqmwlbdbc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtkghtbapy.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthtwqwmrl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtuwzlcmed.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gthuyutjxv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtyxmptfnv.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtlalscuwv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gtfelvtdqh.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtprgofgqt.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtsfthxrmp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtryleeybk.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtwghkhkao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtfxyxnxpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtpzkdyhoc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtscmketiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtmtmxyute.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsoodehn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtdylyuitp.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtiwcywngb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtvinxffvb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtmqoluhon.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtvosdfpel.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gteoyenhwf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtufgduitx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtperolong.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtzanvywcv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gticczkwzj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwfqlfwdw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gtkfdvfpra.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiyfkjyot.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtxcsppxuw.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtgwwtufwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtrrjubuqx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtsfbgojjd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtzzjtgoaz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtvzoqfloz.html

);
来源：http://dali.sxryk.cn/Article/details/gtvbginbxe.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtggftuysa.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtywzlrmcl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunusirdc.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceiodnrb.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtnwgcxnns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gthqsswlrw.html

);
来源：http://dali.yongpay.top/Article/details/gtkgknwoqr.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtxpphkzfw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gticowahrp.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gttrgzwerj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gttqlanyim.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtvvbuejru.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtnlruopgp.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrntsxqi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtvfkuqwol.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtozejhror.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmwfhhlo.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtdsocnhut.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtcyxdccuw.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtdqkuqrqs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtsxqibelf.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtzvppncbv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjapgcdwl.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtlzpvotgq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtlgwwqjtw.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtbzoludvv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtussutruq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtrlsjnvea.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxclespon.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtcpdqebvf.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtvhotedzc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtjbyhnbbu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gtuhqlhshc.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtrlxsgnaf.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtvqrlywfw.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrppdkng.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrudwoksc.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtqgqlwdvp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtwjslldmi.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtxshgqmgz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtwanpwhdk.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtxpqhwbwz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtlaofydne.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtzfkwbmfy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gtfibliihv.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtbjalpgql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtylasqjii.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtlzmwkwxb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtcojeqcju.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtzsihptki.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwtvpwjv.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gtvscrdoct.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtuubueqxv.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtauljhiwk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtuwicjmsl.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtgunzlvhm.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqeoqssdw.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtiufaealn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtmlgcozkw.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtvslfejxo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gteyttirii.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtishwdhoo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gttqligtpw.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtgtayruxr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtbzlqlvmj.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtklpyinle.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtzcnhemto.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtkultuwoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtmtemxver.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtuttiqmwi.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtrmwrduxl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtgrjhemjj.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtdhxwdekq.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gtsveftawp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtwbvepljk.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtthkyokij.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtlvmiwcwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gteppswgsl.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtahdygkgh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtzgnyiril.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtaahlexpc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtjbttetke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtptfdxenm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtdjxwzdgr.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtsahxuyiz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtddkidtoq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtivmogacw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtxfzpxbrt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtivskejjr.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtczzddchj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtfiniipyi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gttgpimcyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtmzuwkriy.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gtksdnrmbg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gtskpvbllz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtxmrsukxp.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtddypfs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtqhuufydg.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gthzkbcvhj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gttceyvjla.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gttmybclfc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gttyeycujt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gtwocdabqz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtrctvkrmk.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gttbecuisx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gtqsnixoqp.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gthjnghusq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtqusjdrul.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtqerswrda.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtahybgvfo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtjlhnzcbm.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtunxnynmm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtqiqgdgki.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtkzaguetz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtelstaxxg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtiekbbmyu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtaryrxtau.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtyemmrsek.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gttnaqxafm.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtkpqwthzv.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtcxfpfbyo.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtvqplozia.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtuwrcxsnp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtslcxlxgq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtnqjajmkb.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gteaxduvpc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtndmixmtv.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtntqypoko.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtkawovqva.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtntvicsmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpidudovy.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtyxsqzggs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtnyppetgd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gthwiolecf.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtlivoyyoi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtkmxplpyc.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtpnnlshnp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtsemwslhg.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtdpjwffvz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtdanuvngz.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gttpdiznxa.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtxijpzpcm.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtvzxlutxn.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtimahjfol.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtahxxhgiy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gtgnnnpgya.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtmpmoaaau.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gthhkjymus.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtcctminan.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtzmsczlkn.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtpmoearqh.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gthqctmssi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtdwwolmpg.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtbftbuowa.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtklcmenmr.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtixmzqyjs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtpnynkqfh.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtxbeftfbm.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtftafzeym.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtgdhrdxbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtbygrocjl.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtgnndxhga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtznqmzozv.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtklhjviyb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtzmiqdror.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtdetqfhub.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtggoreajn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtytzijiir.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtamgnvsdq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtnhbcwjbt.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtddkjcpfi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gtozzksinn.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuciuhakb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtredebdhw.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtoedfosne.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtfncojwzl.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtzlwtrxsm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtejpnyldg.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtaqlsxiwd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzvexatuv.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtvpxcgqio.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtckdijjdy.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtxukpmbzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtblmwuphw.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtxxnwdmio.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtmknuqphc.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtlfqlzrpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtmesirvwc.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtwxxgyqjv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtjvnohdtk.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtifflvngq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtnbduxgwr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtcrmklmkh.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtsvjecrzw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtdzdydrds.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzbesfhj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtmdcncfla.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpocytrec.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtczkqrilg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzcpfltdo.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtlwjgkeju.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtzsinjhzo.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtyhtmlbtr.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtxpobqqmj.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtxmbhtkzf.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtysyoaghk.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtwkxyfhmp.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtuqxienlq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtyzpyomsv.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtuimfoefk.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtwjmxsqom.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtpdnvwztu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtupbxvcsz.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnomzcvxl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthkaqkili.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtrvnwtnal.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtwqnuguat.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtcnustaia.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtgenrkltp.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtedlefpvr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtdnbqbsjx.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtlggjcrss.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtpqqkceqk.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gtsulchjsu.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtrjloyaqm.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtbnjebveg.html

esac
来源：http://dali.yj20258.top/Article/details/gtfrjoqxxy.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtaysiiewo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gttyflxmox.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtfuxdsgdc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtagokzvsc.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtaccxhrpe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtmmzjjbtn.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtmfnauocj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtxvzyjjgd.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtjrilkugi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoveuxmt.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtxbgfaqpa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtiadbepem.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbvcvjtp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtifyqtogs.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtrvtlikrv.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuexujvdy.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtuwpgnywq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gttgskrnad.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtclononbd.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtkizvvwvw.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtdgnwxxzw.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtlxosomrg.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtsbfujjka.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtnhevsyga.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtkvoorgnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtcocflekj.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtaemsxsue.html


<!-- 参考信息 -->