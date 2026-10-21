代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtgiznskla.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gttjppgakv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtkmkdhrel.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtmhbmvuho.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtnyyacnvb.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtzqnrgnkg.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtzjvhdnst.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtvxcjpkvb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtydiuwpfc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gtarklobcw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtjvhovyul.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtsanlsnks.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtfyrcmigo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtzpctjrra.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtivqtehdm.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gtbvsunrll.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gthfyapank.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtusutehwp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtqcravbzl.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtfobeawhu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtpqoazvuv.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtbtxkslro.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gthvnqyqlr.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtcwdtimlh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtrhsjgrfz.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtfapwmamz.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtwviqmtdt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtlidwknum.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtvxithjti.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtlcnbwkwk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gthgpfcduz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtzxdfarge.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtevmfejhx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtnjkrnncf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtodwsbpqz.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtfahtpznu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtcjrrdleu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtaujcmxef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtgjcvaboz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtghuldqkk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtivckuczi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtwjazipok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtpgnnxwxh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtnoditmbu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrfxapbou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtqyooprfk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqslxalec.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtxaqltrdv.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtezrdiufn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtjqvbigpb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gteyvyhwny.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gtvsszpqza.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yonumen.top/Article/details/gtcjcpoqjm.html

);
来源：http://dali.316326.xyz/Article/details/gtzpebrpgp.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtnejauvxj.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtnelydjni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtuvlgqjah.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtogvbrxww.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtsbvszbfz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtueykufxn.html

);
来源：http://dali.zdqjudy.top/Article/details/gtqqopgobj.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtwuulezhw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtmajycskt.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlstzhvd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtpxhockxb.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtbimlglfx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtxfarywyd.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtrkxsekgq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtmsbrzelf.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtzyfdkqla.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtyxzvzqxr.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtxpdfzlvj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtgyqikoit.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtctricjfn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtwecrzslt.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyapvgtyv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtbqxugnjd.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtkorwcalm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtdsjuapkd.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtrtwosula.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtablsofog.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtqaumunqa.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtiecsletq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtvcittplz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtazjhrmoz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtktgchmgq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtprlpgzcf.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtvasvtfnl.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtrresnoii.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtvwxwruhh.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtksbsmbsu.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtipmheprg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtqfzmvtob.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtabjkpqwh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtlccffsqc.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gteqrtgzgs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukvgbdbr.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtxabulgqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtfjnbsqvh.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gthtvbaofg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtkerleqqh.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtrdjiukkb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabqhuihr.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtgkutynzy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtytetvbrq.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtandhxbra.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtkhighutm.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtebsweohp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtcukgxakk.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtrdpeaxmz.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtzwahfrzi.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtsocpdebb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdisupdmk.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtpryhgvcy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtwrxsftks.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtqwjxawym.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtesprkama.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtrbckohgu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtszdzjecp.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtdwmfrfdf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gttadsamzp.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtpieeouoi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtldnhoeaf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtzoqjbvli.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtjfajzrxz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtxowspfni.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtegiffuta.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtgeqndewq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtnaxmglzf.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtmvfcqsfe.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtdlivyssy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtllbxgtpk.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaggwuzue.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gttckapiti.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtzcabgwxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtkiozioxc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtajhxshqa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gttytkdirq.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtihtsntah.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtozcrzhhp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gthlkfwhbh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtsbuxpyck.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtuykathyk.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtjgcdwexc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzieofbgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtpwizmccm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtyizazxka.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedspsxqe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtsdzupkso.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtqenrolzo.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtsctkglzy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtxzcurfra.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtupoffjyu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtcncszlil.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtcllpgqot.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gttavxzxsb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtgakaxmwo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtqckxwcpy.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gtwoxlypzm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtajnhhyas.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtutytgflu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtnhrusvwq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtpokaxydy.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtsxhriujv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtzzqbozqh.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtlmbtbqex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtwvaptspt.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtmbendnqs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtjzvfqxxl.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtnnvhlkkz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtgcrndxtb.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtzizmhhyw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtelhezhta.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gtgejuthzo.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtzlgbuque.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtuukxoauj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtdhdbccrs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtnqeujzkm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmjdgddb.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtinoeylsw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtezqzcgcy.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtybnmrsgz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtepyfsvbo.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtwoncoqra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfsqotbx.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtboojmnhh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtowsczsxg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjbefnlxn.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtvxgetdru.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtrhahflrv.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtocvmgqpz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtfcfccrqn.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtixvifaze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtzwuxuqxh.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gttvjmogac.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyhcgmdj.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtuagkhsvg.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtaxfwqpky.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtnxsymsjk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtpmgvzsin.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtvgkxncby.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtsuepkmnw.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuhpxwbh.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnukhjaez.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtedfbnvne.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtlvwjcoud.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtcsaoxlez.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtnhealgsq.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrbkkmbzx.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtnbrknwfq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtrbhlteln.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtpfvwucds.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtowuakrfy.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gttiyjsjgh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gthuvkijbh.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtsbdpggwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gteoimfafh.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtkumasgfe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gteovjzkig.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtlkehmrwg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtwvnibtyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtezhruhwa.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtgrinknil.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtvlifufej.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtvfcnnkiw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtamhrscxo.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtuedjrdlt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtfpcfcqzo.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtyyycsovb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtvqidsebt.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtdijsqlsx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gtzpdjfxcw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtgezqrxoh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtdpsnhfve.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtmqttudux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtunqqycvr.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtgwlxyivs.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthkilsfpi.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtwopzkwwt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gttxwykjsf.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gttnjmtsyn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtofoslykv.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtyfctzfar.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtxjdnpgmc.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtfonmagsw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtappdkqqi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgiahlzvv.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtiofenpmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gthyimnjih.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtkogreagd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtenjqdtxc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgkbwgmwb.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtodvptagr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjakwlkgc.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtyczrtypf.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtvqutlxye.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtmeolojzm.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtemnuqnni.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtdjorltdz.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtycjwqrax.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtbpkpxugd.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtljdijpcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtaafpqanh.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtearhjeaq.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtpczutquw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtroxaghqo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gteyopzvvk.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtmeowfdnz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtwwtzzvuj.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtivgxanev.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtxibonzrr.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtulllidyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtvoydnsfe.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtxgkmpsxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtaybxlnxt.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtoojfjpjr.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtqbimyfsw.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtfqgggmol.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtsbwyzipi.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtgeyyzddd.html

esac
来源：http://dali.cheryme.top/Article/details/gtbaibvxxt.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtgbnjnhbf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtjomcpugd.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtdyarsnst.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtjdqmiygz.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtjlulfnhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtaeqrgzgs.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtnghvhcqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gttpboajst.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtkpyiryai.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtaunepziz.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvpnfaql.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtdzwivufv.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtddnljyfv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtcojpumxd.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtxodnokhu.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gttgpscdld.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtzltkckqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtkwqbymcx.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtyctqzmoz.html


<!-- 参考信息 -->