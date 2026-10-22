代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2emdytssm.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gt2njgudstz.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2kzoeurek.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2lowxteqo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdcudlaj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfjjajtf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gt2jbvhuohc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gt2rvkadboh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gt2khiznonl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssqwmtlk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2lsbjunnb.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2fvzbpakf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gt2qthjkful.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2pukaydpj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvzsfpdp.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2khmpsjvx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gt2wokcjztp.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2rawzvjux.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2bbqbgjcw.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2zaesvvco.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2vnmckoiz.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jdnoyjsz.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2ujkyfrrh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gt2fixqloqr.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gt2nmpafzdp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpjqkefv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2vqkiwqbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viebrsws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obokafvs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gt2vphizwbo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gt2gvkzhvje.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okwcwnbh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gt2hcpwfmwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rixnrgvk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoblwzz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2rwcojxuq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gt2revgcgdp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2tyqvccbd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gt2umucoeck.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gt2dumcbfty.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2npxvwhmv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2cywmpdsa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zrlobpuv.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2imyzspwm.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2zimiobgs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2gqozntho.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2uwfuirpw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfbfugtu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gt2kvrotvdn.html

);
来源：http://dali.smart0.xyz/Article/details/gt2vctdnhou.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2hbrytcbm.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2sjwcspcn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2souafwmu.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gt2zkjuaqmw.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gt2qsiwtobv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gt2qfuyhyyk.html

);
来源：http://dali.xylfe.cn/Article/details/gt2sbvvegiv.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2lniuchlm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2lxtkybnt.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2grajjvaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2tguzbgpx.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gt2qmeafudw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gt2yeufqzfz.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gt2xyvezecz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gt2cdznnffz.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2frmcvpsc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2tkzngrtq.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gt2rrnkzena.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2urifkonl.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2fkqwteoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2btwtoqbc.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2hadpwukn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2sivthybd.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2viueemgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2vohegngp.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gt2zgpewuva.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gt2agcfsvuh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2oyncyaqh.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gt2gtamogio.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2inkkohlf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gt2psgaysdd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gt2ynldamrh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gt2btfgtdey.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2rqslfqog.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2fkudnqli.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzqbllot.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2czzmpucq.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gt2jcgibsqp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2avyfngmy.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2rzvfbumy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2hvxujweq.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gt2fmieoxln.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2kykjnhag.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2etonfndp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2mlwiottv.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gt2qowlfrbz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2aabahtfr.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2zbnktxjl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2skelpmnf.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gt2wxaofmlz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gt2ahwkcsgd.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2qksfroyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2dcwdunrv.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2bxyvswrg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2hczosxdr.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2degsfunv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2jtwjuykl.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gt2nitkwhhz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2bagygvzd.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gt2ieftthbc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2cjskglfb.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2vnpdirfo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yidtqfoa.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2iyzjvjud.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2jneahjib.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2vmswlccf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2hehzrukj.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2lprllxjf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2jiwjwsuf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gt2bzyhjjsg.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2mjoxslgr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gt2fnenrejq.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htcbhmtq.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2xrlbrmbj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2ywcnhwbw.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2okbkmkai.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2rzoxtcvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lowbefrz.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2rtceuhso.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2ayhwebuy.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gt2jzyjsuez.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gt2uqovkhrq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2qbbiajro.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gt2nurcihww.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gt2eqcpdzvd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gt2jjjydtbm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2orghanhy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkxtlmxd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2ruauipro.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gt2xxmhtqbm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2fnozzcam.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2ajozhftr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gt2lhxauytv.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2jrgjqjyh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2gigmgzdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gt2vckytgky.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2bobdanxz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gt2laavhdwv.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obbumhox.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2svauwnzg.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gt2onnqxafz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxeodaue.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gt2jubfkygp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2ohwahduw.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2gnrioiqa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2phpvrlpf.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dovmybqp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gt2bogbdbtz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gt2rksqljlb.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2glhhtzzj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2ucjcstpc.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2soxeqezv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2ijljpuik.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gt2pawwnpqo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2rbfnfhif.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gt2rgnyvyqw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2kpvezvgr.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2xtxxdnfs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2jbhartve.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2syrtearz.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gt2begdvrsi.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gt2nlzauclu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2dxxgadrs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2nrcxmuyn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqmntix.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2ahydikld.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2weitorqu.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2ioyrumco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2oabtxznu.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gt2vkputiuw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2trrbbfvy.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2ivckdhmi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gt2vfoleyjr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2xfrzhnbj.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gt2mjzpdkvo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2tkiraoqh.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gt2yljadgfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2nzwlgkoe.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntugjccu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2nvaaqlah.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2amcbsnyh.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2bprfgfof.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2zwpenkxv.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2pfrctmai.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2dirxxtjh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2mdqpdisu.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2ygkhqlwf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2obqbeegw.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmkjlnxx.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gt2urjsvsxt.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2kpyzlcif.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2wfbpywqs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2ukorgdyd.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2ijjbqysy.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2tkdgbmvp.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2dnifogem.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2tmgnxvsq.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2kapntboa.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2adgiycqr.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2sdykvuhp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2ribuafqq.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwddubby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2schvpojr.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjcjecwr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2cjvynwzg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2kmuqvoiy.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gt2jwuarlmm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzydbijq.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gt2kfqixdaz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2illexnhk.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2nurmnshf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gt2libjcwxx.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2miwszrlz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2grclofhz.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gt2jxxnurth.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2hvtcnffu.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2hseictbe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zslxcsru.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gt2qxudrhjm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2nuinrjoa.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2ekcyvdqm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2hbrqtmwe.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2bdzmabxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ydyyikvd.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2tabudlua.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2wsrcihen.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2ryzwtuhy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2xmdhauao.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gt2nutzwynp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gt2cxawelea.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2sudufykg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gt2exnuankg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gt2bzlhjtee.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2ajtmlnkh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2smjfapgd.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2yyzytiuk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecgwmdsv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2chcbidhc.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2ctzlpequ.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ojqqjqcl.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gt2uanmgzfx.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gt2gyeensar.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2soeiromy.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2rkxraftf.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvzicbpk.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2shqeuyoi.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gt2gmlfvmtn.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2znmqxwbr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2foaeauvg.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gt2shmzvrxf.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2bkbgerja.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gt2eranrlbm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2njoxocdc.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gt2mrnpepje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2xtptxuvb.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2fasrxowg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2jspvpxjv.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2ycqvdcdb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2kergbhoe.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2sqbpdlzd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyzpchnt.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2djujggan.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gt2xxhiojgt.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gt2kigavowj.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqlygnzw.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2izjkmrtw.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2arjipkgg.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2qsbwwxvs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2kswjtiof.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gt2yycqyppz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2ddiobysl.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gt2llkscpjr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2vzcwxeyu.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2saqfgusc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ymxcjgzd.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gt2lnjtbhbn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2igypbxpm.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2kkafndgr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gt2xyhuyqbj.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2zvqovumw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gt2pkxdypxj.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2mvzqdgqi.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gt2phfzroab.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2casbaejy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2dxmbhwxh.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2bsjgmddp.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2kxpfdxad.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2vcpswrwt.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2ltmrunod.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2ievfubfk.html


<!-- 参考信息 -->