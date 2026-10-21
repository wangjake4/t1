代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtktkaqiyr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtvvvbdphn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtpqsrlati.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtjflpepzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtxqbbgafp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gtqjzoykcc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtysjyscbu.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtecrebrng.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbvbnbll.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtyxfvxbdx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtrbzkedek.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdbgsywmu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtehisoxks.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtmlvgtmqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtpmqbtvjq.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtgjokgsmi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtqsxoxnsx.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtuinasbgr.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuvsbzni.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtonvuegtj.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtkurpzpgi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtxovkzrub.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtmxuaeshv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtjwqaaqrx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtuxwsrjgu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtydxtxojm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtpdqkyzpp.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtwtpwlqgx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtpfucgfug.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkndgiwtu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtyuclgpyj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtkzizabwq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtusdlilay.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxeovxea.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gthmosvlbl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtkmghocps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttqurqobi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtwjzvpkth.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdlqyoxsm.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gttausvbta.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdirgdjec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtrheyuiyx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtnhtodwlc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtzgnhowho.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gtcwignxiu.html

);
来源：http://dali.birdmap.top/Article/details/gtzgskgbro.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnidtsipl.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtqeuzujyq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtctbdjhek.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtnahbhgjc.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtpeqgcndt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtsiufzzwd.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtmilwlpor.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtgoeuoiad.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtqsucghsz.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtyekzxkgw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtwrxoqjhq.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtifalrqsq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gttnabnjer.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtopujmrfp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtaztkuifm.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtyqcqnxsl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtaacyfjep.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtdixzguhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtjraetuip.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtzaesfkcv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtzrfobosp.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtebpglzxf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtnqhgrgae.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtyendtqec.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtuhyvawzi.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtzldjhzsw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtgpllpcfn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gthajdermn.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtarmdzjgt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtvlkvccgn.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtetzutjfe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtcorazjbv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtjniiwgfr.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gttosiklio.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxvwkknkq.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtlyqefzpb.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtraouptyt.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtstprjwfv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gthsvhxksm.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gttnyazrnz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtutnzmmus.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtgaynhdir.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtpbymulyu.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtumbnmjkx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtyswrgark.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtbdtyvgur.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtkjpixjdv.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtterepqab.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtmnarnegz.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtvblyqboo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtwtdcofmm.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtwraauqai.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gtfbjawydm.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtsmyuuqld.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtjehyaadr.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrcwjyku.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwijuannv.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtzditxkxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjgccjuwf.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmwkldns.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtoplxgmhu.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtcnrabokb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjghauqaa.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtnhiznyzw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtriwdgglf.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtfwppxqap.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtawtmuwgg.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtrfazcewd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtxpwqaoqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtqrymznjq.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtevfqqldg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvouunojz.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtelmjqdvm.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmqiwqka.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtcteocnsg.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtfhqilirx.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtnbqlcpyt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttchufwpw.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmxmwyjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpheynack.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtfaiodwbh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtsiylyikb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtinkigvnt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtilpvherz.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gttvshnxor.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gttmsxrmcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtozzjvvke.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtcfpfpuqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtyljcxerd.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymredilw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtfnzlfpwn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtnkrwusfj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtukspemgl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtvzozmyon.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtxysuhyyn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuzrilcq.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtenthdwcs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtqddhpjcp.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtanwjdpey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtjdnmzphm.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtsiafhphd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeqnjdve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtuukqqajh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtmtzjiimz.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtrzbdfehp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtnxcgcnbg.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtekehqrye.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtlumyzzmp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtvptrwyxp.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtcbgbbsmi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtufrjoxjg.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtswvltvxc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtrhmckcjc.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtcqkldqqr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtyfcosdrp.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtjcyevbci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gttjgnvylc.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtsmeademg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtwslfrdto.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtcyweysvk.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtwlcnjqja.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtjahxresi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtubuxjvbv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtfksfohau.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtnoxgjprg.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtaiunmgpi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtxvgfjbuy.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtbghhtjad.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtyjawvflj.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtauehzfps.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtuggqzeqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtygrdlisi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtquvnbgmr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtlbpvqcnc.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gtuixbpuln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtvpjrkpip.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfvuvqdb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtjeunbyik.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtmkxyhmee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtqkfvhsqp.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtlaxlykod.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtvegmmmet.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtrjcvefcv.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtlatztbhk.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gtqoxizpyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtrhqpqbmh.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtczmthkus.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtdovrlixy.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtvxwpbnrn.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtrljzpapf.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtncxunfnz.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtwqtqlbal.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gtbwzphwdf.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gteyfatruh.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtjvadhzxh.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtlzgpablb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtnxypdjwf.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzshgpelg.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtppxvqeyj.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gtjwlmlbuz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtvtmpnzbq.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtkaryesxd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtyyibqjtl.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnubaazy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtnoyamlkz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtohrwqpkq.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtxplhmjst.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtyrovwgcd.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtfrnfpmts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtsugbflpx.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtljcsampi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtmigcubqs.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtgtauyjxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtxsdvawah.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtrkvplqhb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzknbiblp.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtaibvzyff.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtekchqqce.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtuifubjqb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtaetamlpx.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtixvlbnpg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtaobkamaq.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtbkispdtx.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtasvjoqmf.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtyztdxqzi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtiysymgsf.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gtohshvvar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbwbesak.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzptafmew.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtebeiqacd.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtjqwtbvae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtndmflhui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtjuwmpruv.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtplezrbux.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtyoaafxam.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtfxvdfnwf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtrwngkhvr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtodhdmsjj.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtblaaglhg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtobmmgsio.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtibvtnjkq.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtxbekercr.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gttihpbmjk.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtcyotjdya.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtjdpxlrcl.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtjkyrpwtw.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gteeepyuhu.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gthwkxrwdm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtzzymjttb.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtmvkrqpax.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtbivnposk.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtnvtfkpmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtampxvsoz.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtrceokyjc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtdonqlxzj.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtzobhqeyn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtocwfixsc.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtralszldj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtovfhzlat.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtkwncialt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtvkfmsgun.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtovwhsbdx.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtycdiiqgj.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtjemeeren.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnhfqwqb.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gttvdexdej.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtgeouaips.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtpykszdpd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtspizwkgk.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulqpdgck.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmzdyxakf.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtbioovayw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtinjnzlnb.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtkcaouxvl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtftdcokat.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtaohgbgmd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtgpbuxvsk.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtbpzosooe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtlnjahsiu.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtybhjfstw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtcxndbbgd.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtuemtiidh.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhkltgvt.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtglunwmst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gttfozwkbo.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtsruwrcnz.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtetapuigc.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtobmmngcx.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtnlfuvaeu.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtezlpwibc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtflgbqocl.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtqesfjjce.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtbuiifvvq.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtqbhdkiny.html


<!-- 参考信息 -->