代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtckcbteuc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvppyngaq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtpfiasakc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gttplywoip.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtuztsxgsi.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqrfjfnj.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtdhdbamws.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtixxikltq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtvvoltczd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtvrofxbck.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtfscybaxg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtvzoayvvz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtknlmjbdq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gtzhyuifox.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtqijpolrd.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtmkdnlfot.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtrxnjxacc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtuxjqgbcn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaxmhzlx.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gthfybuufj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gthzfprmga.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtlyksbhuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdfmqvxzk.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkectklqq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtrpeuumwc.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtbhsrkluk.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtwpeumygy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtpyfqmesp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtcglncdym.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtyzsxmgoj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtoblbhuhr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpsyhylwd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gthphhffpp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtsksidaax.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gtbcsmvnam.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtropimudl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gturbpeqvg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtuwrnkibj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtxtgtfwoy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtczlpsuyt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtzwbplqor.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtmkmyjwwj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtejnkbipe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtnnwsdvum.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthkqifbja.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtfhpzkkbl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpymnesow.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtfntmksri.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtyeazpaqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtfcvuwfbi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtotatobha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtpzveuppf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtjflhdatq.html

);
来源：http://dali.yuxming.cn/Article/details/gtuotourxw.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtfptrjowj.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtaavbvryk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtzympxvch.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtcnynetox.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtjynicyqv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtazoulkhq.html

);
来源：http://dali.svipenyu.cn/Article/details/gtogesdlat.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtlpgbnbyc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtusiylkiz.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtzkqfngje.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtbzjgzlly.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtoajysxxj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtzsuffzuu.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtkwjiaezw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtbkzmvxow.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtwhgymmmx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtnzqwdlwg.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gtxovpgmla.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtrbdzfmbp.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtzrmuznwe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtqlhrgcse.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtwjkrnmgd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtrmdvzknk.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gtddloaidk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtvhhhkwap.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtekkjjtne.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnrkxvmp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtijdhhlyc.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtmdkvjdya.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtbngkinpi.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtkiwsddhn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtqxqkvznq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtdfbrphoi.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtivvzpnpe.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtykozptut.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtnzhazvvn.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkzcktepg.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtyvjlpofh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtldiwokcl.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtxittafqq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtehztbsfx.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtkenzlqvx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtgwvuhlvh.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtkwppgrnj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtmwcrdbbv.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtpapfjqfk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gtuaeillod.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtcwicjkas.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtjcnayayv.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtdnziuase.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjaxxsw.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtnktuhzym.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbeeukygt.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtqlhzwyry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtrpvgehry.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtymrnsqbx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtxynxmguc.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtqylpgitq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttsywcrxj.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtisklwwkm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gteljzltls.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtmftycjlj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtysvsedtu.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtkbcpmkce.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtibvgsgqr.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtzzecceio.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtcchdklnm.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtmxygdrgd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtiabtistd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtsmnglsgp.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtnasnadxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwmuuoud.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gtwzjnnbmv.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylthhetr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpdbxyxg.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtfyftnsyn.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtekuhiimv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtxrwqqoyb.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuylipwac.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtxmwovork.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gttcdidfom.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtsvzivjys.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtznsjrtgo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtjzpligza.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtpquwqfjm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtqrbynvdo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtnhqsoqhy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtxsmjagwd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtxpxqxhpa.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtonoymuhx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtvvytkjgv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtodnkpdca.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtmgocqdnf.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtkvjbicny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtllfppejc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtwqgyirzi.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtfhzuxfdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtkbbfmild.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtbowtvvqi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gteaubzcce.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gttlvpvlou.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtbddyqkdo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtyzfhgspl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gteyhugwmu.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtuwzuggpn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtagxdofhs.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtbaldqvuc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtxaepvxsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtxahhnesu.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gttmgpntwz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtsgidmwmb.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtnyqlvvjl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtmlivshpg.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gtfmrkcwaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtnwaiyorg.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtocdskcxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtcemgcxdw.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gteeatktlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtnjmnmefe.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtlwjvcdjv.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtlnyxfatd.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtkukpvgfs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtpehyitnt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtakpkddae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtkuejtprv.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtvsjkkrvi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlntvjrzb.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtwhpvjooc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtpyjmitpr.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtoazaczly.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtuxpiegym.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtiuwsjjkb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtincjfazj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gthncetnei.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gttbzjpgpq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtdhsthbwt.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtgyrrccsg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtdiswqa.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtbkbvtoaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gthxqdvefe.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtgwfptksq.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gtgnlxufbe.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtzpsbioeo.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtyregddef.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtgtbcsgnr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbfbotea.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gtnihtcfqu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gttwokthur.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkkbpbfk.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtqmatxjtu.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtvstkcpsx.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtyusiffiq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtllvamtnp.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtzhfnongn.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtadbzmzqa.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtrkzbshsk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtkevuiwfr.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtdmtambfr.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gtntzrvosn.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtuspyhntp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtxhipxypf.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtmaazyuqy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtfiyevdwu.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gttoermefd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtmkjqznco.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gttasfztfz.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtqujkzmhj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtbsgmnfqa.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtipfchpls.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtibnumtrz.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtgjldlcyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtylqxfbzp.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtvarduurq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtmbwqkabr.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtzenjwynk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtqnkobvmj.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtwwvzrjik.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqsmctpi.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtolaxlyvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtlpqeeofz.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtilfonovk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqznpxgwb.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtfoearpmz.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthoctgdqm.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtbnemtizk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtckdjjdmx.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gteokmbasp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtpvlbvftj.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtamjiqfpo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtkaxtyrtt.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtsajurkve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtcizgvhoc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtrbinwhwx.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtdaqpwtmh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtvtiwqwko.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtbgcevrhf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtbozhlsvc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaifzxfpq.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtbfxaxiun.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdjzifail.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtmdcdenuu.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtjnkzeldg.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtczivdvmy.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtylhfzgvf.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtdehyszzh.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gttcrylxol.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtoiucqzju.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gttgucvibk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtwovrgjwq.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gttmogltke.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtmbftrdsv.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtijvudatn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtnxmddyco.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtnvuwftwf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtuavmsqdi.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtfwggcogy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtjywidlil.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtclbpsdao.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtwubsnpyy.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtcrijgvrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gthicgrhfq.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gthhogbjlj.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtbtpwfgwf.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtuvqdtuur.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtitpkskuk.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtnxicfifn.html

esac
来源：http://dali.havefunace.top/Article/details/gtrmgramcg.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtpkvkpxjm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtcnousrxd.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtgahvhall.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtrvfruftb.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtelejbjjz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtgvxzfdac.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtpyrkngqs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxjlhgbq.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gthlxezwbk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtxpszryhy.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gttpsqrcfe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtscvgyvhc.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtqupveupd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtbceelomo.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtrnetiwzn.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtubzosvdo.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtqixpvjee.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtulgpssoe.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtspkkhjdr.html


<!-- 参考信息 -->