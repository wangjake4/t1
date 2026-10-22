代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtnteidaxr.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtrfepjwmz.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtqmhprusk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtlzwcychg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtykzdurqd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtpkeqvktu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtlukuqcmg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtduobfyxz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtrcbibyxh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtashsulef.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtcwdhmzzn.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtipwrjtpz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtcpsrndkd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gtwwyczraw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtwvjvpncj.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtameejxep.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtkfoclhxm.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gtjrurstef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtuhsjvpfd.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtdhtxxwll.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtxubobijb.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtsmqvqjhr.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmbkvkzc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtwmrodold.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtnjjvkveh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtwiyqtxnw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtdmdhtcmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtbjqfntjv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtwbhuvyxs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtaottbgrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtechlbyna.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtkbycthad.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtzazobvzs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbqavwzxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtangtgsvz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtzthhaqcu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtxilwbwrs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtqpxpfvfd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtcmjeeppk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtjrygqomh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnmudtfaf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtrlzhivbo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtutrvkxnq.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtciffruew.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtbutfjtbi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtjlpyhuat.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtlgkzdvoz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtisfvulfu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtzwthelep.html

);
来源：http://dali.hywenlv.cn/Article/details/gtbdmvpjpj.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtufkoatcp.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gthjxewwrc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtfkhslqyo.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhnljnuz.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtgtxlzchf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtwrvoviri.html

);
来源：http://dali.smart0.xyz/Article/details/gtvqnyaqvo.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtvwflpsaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtunboysto.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtwjuripcl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtszjqvuzm.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtuiipnndg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtdfauboml.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtgnjdsykv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtlgbuehki.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtlsdihehq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlydxpril.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtscjifidu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtnhcdkhpv.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gttkxitssa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtzxoljkyd.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtbsequnar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbsijysf.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gtzsdyfbdy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtrtvwcwmf.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijrptqwm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtvbedqley.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtdckvwmbu.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtsxanljgo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtybvbaeyd.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gttnuklxzb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtvzdrpjxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtlgegfcsv.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtlpffcklj.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtstwhhpcj.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtvuhxmaeu.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzpaplzbf.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtcrkfdemm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtxutydovq.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gttssakemz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtsstikauc.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtnojrmeyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtbraofelg.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtldalbohp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtrojlczwj.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gthjfuxtfj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtsykvkqdo.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtcllafust.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtdkorpnkf.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtbaolwnsx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtbkfdjqbv.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtksrnvstx.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcilycevq.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvghgdrnj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtujzygrzb.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtpyfqhzcv.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtaftcriag.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gttqcpvrxr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gtcxeshrps.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtqvrzumhy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtlbzwjhvq.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtxudyifzm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbubgnbng.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtlfdroydk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtdlnwvdii.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtgbtkvqrd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtarlmmehf.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjrfxceif.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtfvyayelf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtqgnzdinl.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtrrrbjwxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtvssekiol.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gthisgpead.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gtjjvvsudc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtydofgxur.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtavrszjum.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirlcowbp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gttsirnpua.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtlimhmglh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtgxusfzag.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtivalzkoo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtgmdgzekx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gttddiigbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gthyxuysqp.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtevywosxy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnzagbsa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtpobomtzr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtoiynjefh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzwtxmrv.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtuaqkywpj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtwqirnacn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtmjnqlmlx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtwzwcmkoj.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtnzycyvly.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgpigzzg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtgwymydiz.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtfpcmeimk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtguotfejn.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtwzkfybvq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gteronsrju.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtgeakffaf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjfrbowb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtgowieyvl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtsbekzsgg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtdqyspswl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtnzisxnvt.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtcqobverb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtiwdoea.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gteeryqkkc.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gthetugzew.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtsvuramse.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtmehlztuj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtetqjmtji.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtmcyiwuld.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtqljeoxck.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtokkawmru.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtnumyausf.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gthcvfcfrl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtnokiuity.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtqcawujij.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtqkietkme.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtshzhoxju.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtnzsvqhps.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtbrkrydpm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtcatdsfks.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtxssjhziv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgpckdona.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtjmzmqlqc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtudnnzwku.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtkkynonde.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtulfwlrjg.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtmjenpfdz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtbdtomooz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtpazrqvpd.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtdvftocok.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtteorwvxk.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtleptalej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtcayztdol.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtmvrdwoze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtjmhspqjk.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtjxehfwnx.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gteoepozzn.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvixgtsyh.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtdnmtpxbo.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtmfacsdpc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gthffkixoi.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtspdsrryp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtfsyzwxqt.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtkkboiipn.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbxusxsl.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtkduvlijq.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtajuqkkfc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtfdldjbqg.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtwhulgkyr.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkxghilqu.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtxbhwvbzi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtowouahto.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncevtun.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtyerwuwla.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtudrmfuuu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtmjnwzzhz.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gteaggzkmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtwlljeqtq.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtacqsrems.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gttzxfiumh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtbrrwvick.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtlbtltyfu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzxvduih.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtnfufijvr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtwukmtauh.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtuipmhdgu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gtynkhcdqh.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtdmehtlxk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gtqylckmfi.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gteflyuiyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gttwdoawjg.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtvjlqfbsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnefyduwm.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtculdddoi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtfahuxoie.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtgtzjszqk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcfuitioi.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtzsawpzok.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnpdugjnk.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtxrjfinzz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtgtyrkpha.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtuxlyxrwv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtodqipscd.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtxlregchr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtusaivflx.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtqefuflem.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtwrqfqfvl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnzklelf.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtyieqrzlt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gthlyixklp.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtaztvkffe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtgrbprymi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzugpquux.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtufuwghkw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnuquxaf.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtqryctbds.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gteufinxub.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gteczcvrsr.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtwfkqifhm.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtckhhtahy.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtijabdjgg.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtmtelzzlg.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtocyljadj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtavpxgztq.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtrfuqakdo.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtvaqdpwme.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtjxxcvclb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtxxplinmo.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtzvwmymfj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtxpzunpud.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtumakjnei.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtoagyogpl.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtfprkdznq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtziqpkxde.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtninrqscc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gthtpgofql.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsqntqnx.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtcdmmcgkm.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtbitcstgc.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtkkgegyfe.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtaquyfokk.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqohtoglm.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtzdvqbokd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrilpdzd.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtpidbnipd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtqbesndqs.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtqvmrrkbh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtkwgjbcum.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtmqmdrsft.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtxfntqqyv.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtafhmlmwa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtoqppfked.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtqyfizxkk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtnuswrmme.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtvfcbelcc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtcrrduwdh.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnqgzwjs.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtxctxtzcy.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtxzcqsjau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtchdemnay.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtoftmoenj.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtegvpzsru.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtqtvtjxuk.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtdkfhrjks.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtxgumypyo.html


<!-- 参考信息 -->