代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2wjbxhjrl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gt2ruaivfev.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2lxfgzclu.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2ueljnwkx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gt2njbzcnfn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gt2bvwabjpz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gt2byxdkmjf.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tubqbxvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2issxvgko.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bxkrocoq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucfwkspx.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2pfgqgvmm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gt2gleanjok.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gt2zpeovefv.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gt2gzkayodp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2bgdiyugl.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2ijpfsmlp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2sxcggryt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgaseew.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uffdptns.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gt2ldfozcwj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gt2bfmvibrz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgbjakim.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2hwgmvbav.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gt2swasgwmg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gt2evihvupl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqmvsvun.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2rkpajlku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gt2mpqsaaie.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2cxmuvowi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gt2agmyhsvb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gt2wnnjmfpq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2nrfmvmug.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gt2urbahjsr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2yhxjhnke.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gt2qncpflrq.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2bncqdauc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gt2hnyyepzc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2sqiyvtrn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2elwqdfch.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2csomgmft.html

);
来源：http://dali.316326.xyz/Article/details/gt2kwhuptoc.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gt2aiwhgizg.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gt2jtuyvjoz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gt2cplsktnc.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2gqznstks.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2exbrpgzv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecgotjwx.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2fhbwhmjp.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gt2eywfhbbw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2ogxohfiv.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2cqhdotav.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2lfdytuiy.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2ijaocmzm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2boihager.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2szdigrpt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urtbflwi.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2mtqonhuj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2qbvnbwaj.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gt2cnuwlpiz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2eerfscjn.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gt2ekhodwrd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2avszrfqv.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhydmwfx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2sqqjhxzu.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruqsotxl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2hnzwcazx.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjmkoldm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2cyqyfcmd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2wdpdlzrn.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gt2aerwvcuq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2gauftxnz.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gt2mkxbjlye.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gt2raqdcnua.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gt2jlstzqby.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqmdyypl.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwfrxwjn.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2seuzfrlf.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ztkffxeg.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gt2ppctzcqw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2qgelcpsi.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2gzcdxnsx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gt2mgpaenma.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2jljslbmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2lqtvyrhm.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyyqdhru.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2lrtjkljq.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2cpbdvfzy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2vlfghfas.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2qgdoiljv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkngbznn.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gt2piopusrh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gt2ncpawvhx.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2sedyjpux.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2erbydqnr.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gt2srbvmjqr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gt2efxaunri.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2nzvrxxvq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpbrirpw.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gt2pjtilffh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuqokdnb.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2akujygvf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2mcpzjnkw.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2txpxibkj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wybzyyih.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gt2tdqsguly.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aonyadkw.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2ilzuvhac.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gt2hjnwyumh.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2dtezzsyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2irupgudk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gt2cxbaavsr.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2nahtedyr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gt2jfdoexgn.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2ksyviced.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gt2xitxuvvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gt2qegddyid.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gt2qtmkxmxk.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gt2zxjdzqnt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2whjblqbw.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2mcstamrr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2zkntpjnx.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gt2hkbwpele.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2dbakqpgb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2gpwddhxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gt2uzdjuegm.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gt2jufwcmhp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gt2gxcdbxqi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gt2avgeuqar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gt2pnylfjke.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utxhttoo.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2vvfdkdhj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gt2thryjjho.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gt2hvafunkj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gt2tysmbdfn.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2adojxzyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2wwzbkqod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gt2suaqtacc.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gt2ynkupamu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gt2gqhzvqnx.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2kvwkedhk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2hndqfhvl.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gt2fefqbtzb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2clgupagi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2lufylzki.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2wniwljis.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcqjdtx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2mczycjmz.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjnlkwez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soxnendf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gt2pfjibfji.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2utcrwkxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2fiimzwwe.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gt2gxwgxcxh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2dllqemdw.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gt2axswxplf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2eqvjffxa.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gt2qddifpra.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqrrwxxo.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2fglirduh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2obtgtvri.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2lhziwaop.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gt2uzqkedoq.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2sglpsmqr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2xnzbsdyb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2wsqarzrc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2iepiajjo.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gt2cconilpq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2navmdgxv.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2fmbprqyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2tqpkprcr.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gt2bemaircf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2unvwogdv.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gt2szlvzisg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2oekmdbdu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2sltufeth.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2cffehadu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2ecmavmfw.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2ypngznmw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2fxlcdony.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2oxmpzvrl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2vbjdzedx.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2kumggyey.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gt2aeoksxwk.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gt2ltlgpafe.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2sferhkxf.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2xgbpaket.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gt2kyibyjqq.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2ojgaychb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gt2ljvtnydx.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gt2rxyuckmq.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2eeakkfnb.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2gumzdahx.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gt2pwwckgtr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2wuifyrwp.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gt2kuwcivra.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gt2qntfkong.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gt2ipupwdhn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2ozpuswyb.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gt2udvffklv.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2eyanrdgl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhpfuec.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2jlxdfmvj.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2bhmfjwli.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gt2gcycjlsy.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2xdzqkzol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2jarotuvb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2swgptujd.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gt2xxbdxnpd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2khjzwcqy.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2ynertkwk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gt2pfujutls.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gt2vfijpnfs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2ghfjqfoq.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2zpvmrgaq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2mmnrptbr.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2vwogzsee.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2nplihukg.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2yuftcewf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gt2rwfoxach.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2oniaxfjg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2ijaxkgsq.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2quzegmvu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uawbnocf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgbwvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asdneooi.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhgkfxft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2cpjcjtrk.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gt2wkpmzfpy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2jtizevcm.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2dzbctkdo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gt2rynmxzae.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2vokynquy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwssqxij.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2vzwvumhl.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2hotarsnf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2numbaqrg.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlenbmre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2pwpzswfl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2porsqqaj.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gt2mbemhxsd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nxnlmfgw.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2epzjkusq.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2yqufdjbz.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdbhiyxa.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2ycxqykab.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gt2pcmcdqxu.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2uqsqsnxd.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2ozknqkga.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2abouvpfy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2vmnnpttu.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2ezqxytsv.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2nvqjiqwf.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2snmfndon.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2vwhpewbd.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2qvqxssbk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2jbsaeilf.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2xoiracwe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2ocvrrpbe.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2cbsrxrfv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfebqhx.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gt2cpbxyade.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2orefqjjg.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpgsoyxr.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2cnhtxiub.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2kfejiynh.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvefvuex.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2gxqskfsr.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhchlppo.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2xnzgzcsz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2bqyftmok.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2kukkdvex.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2sizfmeyf.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gt2xkknntox.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2cqvvtipd.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2uiwglbyg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2zaxzxdef.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2oguljkrj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2rhchvzco.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2zyxswdbs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nppztesl.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibaqxezj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gt2qnpouzmb.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2jjmhlygg.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2osubyrlx.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2fnceigui.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2mrpvdggq.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gt2nhhajkrn.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2emvzetkr.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2hbhssmkt.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2qavrstjk.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2jwhdlnwc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gt2ozzjljld.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzrrjtos.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2ddcxduny.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulczilgq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhwejmue.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2iokiywkv.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2xhkxvbrv.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gt2uqqmolfy.html


<!-- 参考信息 -->