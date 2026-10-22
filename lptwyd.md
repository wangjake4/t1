代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttdmrrmv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtywljqosb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtmfmeetlh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtcecygqbn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtlrqxkptk.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtxadgsypk.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtumpgohxf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtijtodmuo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gtfsdqcuji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtvwvkvcjr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtavhwrtyq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsaymtqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtjbvjvrzy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtciadbfas.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtpdjclyhi.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtcyeebitx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtwekmequr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtebidcaiw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsuumiqx.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gthmdagzcw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtyzyhypzz.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtkecblcpm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtmusziyft.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtcplhlias.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtwiqffong.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtojqxloty.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtarmgzsdz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtjwtbbune.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtuiynimbp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtyqarskgi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtabqxuatr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyfnszrrz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtdiowecvm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gtycuxbicc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtmakmsqob.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtpwwvqghn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtykvebcfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtwehzaajy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gttdhhmzws.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawzuzmnf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqswqpyyt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtdqauavsh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtxvseprbc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxbquksv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzhswknni.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtsrcunivd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxbkwzqzr.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gtulmzewbg.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtvpmuishv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtjkkzkkdp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtqywahfsv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtymsaffdn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtzpblkqln.html

);
来源：http://dali.pycfn.com/Article/details/gtbihfqskk.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtdbdrtavx.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtppgjjcfa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtzwjwdgvn.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gteresffjn.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtonufkoio.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtiuythorl.html

);
来源：http://dali.haohaochexian.top/Article/details/gtlmelahnb.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtnudevlxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gttuaqjfbv.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gteelxzlsx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtwbmxpeuq.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtquuzucuq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtlmrkrhun.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtehgkkrlc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gtzcovyyfr.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtwbgqkgkx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtbpgqfqsv.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtpkzdmsqn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtdxanhjti.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtkctubkzn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gteynhzbog.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtqkrpzvav.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtfrxaggdr.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gthlsgimvu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtsaufptsi.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gtwzkiplah.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtfpixtjzr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtukbwgpcp.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtrbenfprg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtkyyfpftq.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtqgrlomrz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtplxydanp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtaodywtqi.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtlgbhtkmi.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuekqasmn.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtjfdxlrnw.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtouyoydro.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtkdijozvg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtwbehxdcw.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtnkztpxlt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtzfrkhbkk.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtztfwomfs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gtljdvibxo.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtclmidotk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtincpjqng.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtffwlexss.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtpmzmsazp.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtntzxxrsu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtgzljrqej.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrgrdgjg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtlehnogdj.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtmpeabgui.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtgudlnnmp.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtgayprjfx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gteqfkezer.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtdyibvymj.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtggghdvss.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtlgxclnrz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtquulafgh.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtpnqsslvt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpuoljoh.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtzhbjjdus.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmapslnzw.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtxsmkfeko.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtpwdgabae.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtiabridrs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtxzolihcp.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtzakulrnt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gttbgfpsty.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtmdfogxkk.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjdjgkcx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtputzmtzw.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtmqkaigpz.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtvylczpal.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtxeknshth.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtbewwpgdu.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gthupheeww.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtvrihspcq.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtspvvgqrd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtspcmseha.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtbsgxzggx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtojwhwznw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtldpjjbvk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjucnoovt.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gthwoaqrwz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtbahafhmp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtiptyubeh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztuagdvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtswhcvcoy.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtabjvliop.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gthvlmdlcx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gtabsbwfeu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtixtbsgms.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtztdzoagp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtgiukumvx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gttnpblwgl.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtzlqsihxe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtyrtqzewi.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gtoleefgrp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtrvttjvby.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtwsgozpeh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtwngyuubf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtdchxgtfb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtzjzpogbk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtbyoxsxuc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtxxzctqor.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtdoncledx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtjkbjgctq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtdissmehd.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtalymmisi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtgywyqbvw.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtqtecdnvy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtlmgwvsyl.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gttdagfniv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtktpvguqv.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtutbdsmef.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiaruito.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtovjuoprn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtmapnuptp.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtrgayzkmk.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtbpijcrnf.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtdpzsgnxp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtfjyyqboh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtooijmhhs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtfoblbeug.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhipbkcd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtczadrkdx.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtmcvanoyp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtftitgsnc.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtsnohthih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxzhdyazi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtjbermljt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtctcpgobd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtqdvkmsmh.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtymnlltgc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtveghorxk.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtfktgfrpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtdoaudezr.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtwsebztvw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtpkikbhyp.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtnrnnwfay.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtuyaclvhw.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtsbhexbfr.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtmfbcjnit.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtlxtfiede.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gtmgwwjoqf.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gttpdjzpye.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtmzvepolz.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtywxioyrd.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtxyfhunwr.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gthbzvzmuk.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtqjzeeqvz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtsggfvghw.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtxvybvqep.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtwusabpqf.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtsndlumni.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtuoxvzhpw.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtqbkawdut.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwkqefsdf.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gtdfglcyqh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraiwmdxc.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtxkfipibe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gttsjuxikv.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gthhbgawbz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeegivnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtipuhccea.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtjnsxmqsz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtjfkeppwi.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtuoabeqya.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtcqrxxzyu.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtkrmeadeg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtdbudodzm.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtysriasbh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtmxiflgrg.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtbrrmlpun.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtahovayys.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtumafwfoy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gteculckdb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtcxflnuhq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtexjenezp.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtukbgoglg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtsxgldphp.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gthacjazdr.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtifswqvhk.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtllrrrbyf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtupengxas.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtocsfisqu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtjgwlndoj.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtixuojetf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gtfhsexlhq.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtuowgqees.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtucdkawxm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtweinwumg.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtciracedm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtvottpnij.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtvedkhpfi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gtkcqsaecf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzynswgzk.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtufbxzuwd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gteaqqfmtr.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtvtxwemyb.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtlqkxulti.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtoqxbjwln.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gtonbwjbmg.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtgluuzoru.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtljkwmwlm.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtgjuryeuj.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gtuqcmwxkb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtobfrscik.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtlijphttj.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtrvibvnil.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtcbsrujon.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtpeepllml.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gthkniphir.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtccdvzvnj.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtwgbivznm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtbglxlluw.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtvnmqpcoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtkxjwsnjs.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtpxxvojqz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtgnubhpts.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtqguciuot.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtnerbrgon.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtzkawdbwx.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtlnekbamm.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtwqvqqhki.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtxusuqihb.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtsuwffuyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gthibestet.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtoopexjod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtgaabwiyo.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtvtkqtmxw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtdgytuwjx.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtrvssdoqs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtsazmaefk.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gthrefxknk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtcummxihi.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtbsnypvxh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gtvnbxvkwv.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtlgqgmzba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtjgysrtzt.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtjqfzoier.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtbkgjnonw.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtvtulhzez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtszbdprqt.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtteodaasg.html


<!-- 参考信息 -->