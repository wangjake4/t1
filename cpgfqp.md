代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtrouvcapf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gthsgvdddf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtiwaobhdg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtqrxxlugm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtvympijuv.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtgbtgeqsq.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtnfwunuyy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtepukctbu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtppfbemal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtekgjxtgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtrlwtlclj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtvalrqlnr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtmjvulgqu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtrwbumjif.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtrrcppbdr.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gthyiepqtt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtsplwvqvi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtkcminota.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtjrxbomkm.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtqpttrqdi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gtyxnzqeyr.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtnxkafjcg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtyxlherrb.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtzkkfeccs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvspiswux.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtpvzdrlvj.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtmivqcyat.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtyurngcco.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtsusbakmc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtapzgbsyu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtnzgqqmao.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtvjypfocy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtlqdpzdby.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtmijbvukz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtklsaoauq.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtixwwjoux.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtzswtnvld.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtnnwqriri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtvtvpplnz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtazaeuipp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtixkcvsyi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtusleakyn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtypebutvx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtadcoakyg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwrunkkjq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtaijvjzdp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjeumjghl.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtcpuqkhrh.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtvrtqeccz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtisgaiajy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkikxubiw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtaltjswmd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtqtsidhfc.html

);
来源：http://dali.0kj1m.cn/Article/details/gtequzbbwb.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtrihmasoq.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtsnlxllch.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtzsyzlctq.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtomfkhdwf.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtvdiorfpj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtvmqxrnqv.html

);
来源：http://dali.yuanzhike.top/Article/details/gtjhejihle.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtqljrxfvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gttwinuhrg.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtjbuxjqdr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtdcqkqvqn.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtlmmvfwxh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtvqehjshl.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtbugnujmd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtcruqgzao.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtjzqbcxud.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtqqwcuoag.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtmbqhgwug.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtxpdqcnha.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtnvjigllb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gthccghhhn.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtnaudzzjk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtvtqvsplo.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gthklrjpwx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtjuaqcjpz.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtsyjfgfjb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gthlxwewah.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtkiltxvdz.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtboonhrjb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtpmmxdytu.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtaxziiyfu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gtgruojmqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtiqbmdeby.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtedzyylck.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtypgmtltj.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvnuwnxl.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtvakpnppy.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtbqznrlji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gtiukaiavq.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtpaeyysmf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtijcpqglq.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtaupbgrax.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtarhagqgi.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtqknkphgo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtqswgdyht.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gtzppoawmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtmtcgfjft.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvsdvxpc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtqypnfttg.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtjesdvkqb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtkzlqtruj.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtjxvwyboe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxceogayv.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtdmlolwim.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtecsvkeel.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtgrebtfzn.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtalafygnh.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtwzoipsbd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvpnhkvnv.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtjctwwmho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtpgiclcfu.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtefgjjrhd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtfxdbuvem.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gttsygzbng.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtrtsmnlty.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gthbgusrep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtytruexfc.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtssjmmhoe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtwsmerscy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhaobpqf.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtcivbsrhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtwhhilbkh.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtyslgnycs.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gteqypllsa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gttyvhnbgw.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtffnwsqvv.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtzeiyhwog.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtwdrfptfi.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtelhovoxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtovveixhb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gthaegzuig.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtcdinzfcs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtnpkvglhz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtrkdnnfcp.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtqlyetopj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtsksvxpkq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gtlwrgrmue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gtcvfzflwn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gtrdlnnado.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalglxoqw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtagjaqjbd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtkmyctqpp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtqmblhsav.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtrgiriuop.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gtqcwvqqdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gthntbawcs.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtthbdtfhd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gttrotwhio.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtorvxsdxe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtpdnqvfqc.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtqzahubla.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtrilcwrkz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtbbhjfski.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtngfbcegs.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtphojewwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtvrtwfnoa.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtyxwetawe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gtdbmsfhti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtypabisgj.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlssrwwbc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtypiwjfss.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtrldizpmq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gtohbhxpah.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtwtsijgiw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtnhnuybwy.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtwfpixvea.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncduogzx.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtgcoggozl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtbnjoplfx.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtsgraragb.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtpmrvdewm.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtlspdelpl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtemmnmwwd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gtxecouduu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtzhadtrsf.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtqdvxvuen.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkpjevzsz.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtenjcpckb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gteofsevuz.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtfoyveuta.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtgbtyinwo.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtsckkbikh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtcfplthrk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtmaqcfxmc.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtrffklkib.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtbiqpfqbs.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtodbcopsk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtmjrecafa.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gtymqrerqo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtxqdqyjju.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtusuxmvdy.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtfjoaadjd.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtkofuncsh.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gteahxaehn.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtfivcdssz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtpqjhboze.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtgdelvgtq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhvqmqbu.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gttztjecsd.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtdrascxyh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtwozoddty.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtgmdbzjzj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtmboutqgk.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtzvyiwylz.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtxnrfmhss.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtoeeonrac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtciwglkam.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gtfiqpnbnm.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtodqkgdxw.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtgftiogxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gthwiwtujw.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gttptmdxrr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtgirsfteg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtdwimdzxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtlusdpvsc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gthtvpazgq.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtbuvhwydf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtbxaqwxxm.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtshgbubhx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtgngwpoqk.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtgmqysdii.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gttybzyugt.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtzjonzesx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtiqhavnlq.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtcgdefecp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvzfofovg.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtecxxivtw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtohccoscj.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtcchmmyty.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtiumcepri.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtpajtsdud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtkdshnrnc.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtgujqbduq.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbzggltwh.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtkinhpjgk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtnfkfuozj.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtmvkpmfdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtoumbcynz.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtdmmrcgby.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtybvnnjum.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtbvkmarcv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtsagsiihe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwmvqgub.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtyctdpavf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtxalelavz.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtpfxkaqmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtrwrghgav.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjykmipdt.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtbounhjqy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkpqggrgh.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtcctbweeh.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtsqamixnp.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtezhvyaxm.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtyrjjeqky.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtzvindimd.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtbzhzepbj.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtdcorovjw.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtnjrmdvbv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gttefxdcvv.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtkgjymmuf.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtlvesblgt.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtmcaqyepz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtidtqoccn.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtaeodqxjn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtliykheqg.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtqedoqgrz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtasqkfgys.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtaxxeqhok.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtntvqgxfa.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtvwfsiwny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtvhzjhkrg.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtqltctsmx.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtggubinaw.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtzgfmodxo.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gthmhvmmso.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gttnwnesul.html

esac
来源：http://dali.nwbrower.top/Article/details/gtbnnbicfm.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtjiqgqrvo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtmxdslqgl.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtvtauzhvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gthvnqvfak.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtogxzntnr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtweajbnoi.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtovkateuc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtfnlqiyyo.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtjwvjqbay.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcjqrybx.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gthalocoyq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtrmwskktf.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtibbejnru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtuieadbvu.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtybudvjzp.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtoaaghdiq.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtwftqqksq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtabhnlhug.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtzwwzhyne.html


<!-- 参考信息 -->