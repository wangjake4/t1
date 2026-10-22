代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtjtfowdvq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtczwuotzm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtljgwqmjk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtbdlaiaqu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gteasyegfe.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtxlcbfano.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gthsllzkbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtstgdxrfn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gttmeuqpwa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtymwucmcu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtfwfibxrt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtzepdmeze.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtwfeskjuo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtkfdwxbvv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoqfkwjo.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtwxlcwlhp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtksxlfyzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozrnpfaj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtkjkvwyyj.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtarhrofzr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtqaypmqkv.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtyhnibjfs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtgvjqvteg.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtqegnizil.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjehchiv.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdefveglz.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtmjvncvto.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtyznmkltk.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqzerkxm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gthqxxpuzp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtmmxudvde.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtvbbfxavk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtnjsimifx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtxbjvtrhr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gthtlekilc.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtqpwnebxn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtmmcakvpq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtqlenbzyj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtdkjaxseh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtnsatpppz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gtuqjhuknu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtfsxgfenl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtghjwkuem.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaorarhu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgsgxseza.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gtvtykrmac.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnejvgbhd.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtpvrwjopf.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtgsynxnel.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtxaniekko.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtudycwhfb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gtuuesddhf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtdmimnkif.html

);
来源：http://dali.cheryme.top/Article/details/gtlqbzgzoc.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtybhiivcl.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gttyxtlopv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtzidhwnbz.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtqyaipfmy.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtbebmuyll.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtobapfsds.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtilxszual.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtwszdwdls.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtbenupmhx.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtpdafcecz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtlrtloxhr.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtwfhnbxmx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtovmfsgyq.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtpelmwizk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtxvolyhcv.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtmsrjrroy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsycficzk.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtevkzevfp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gteiucmili.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtmpuywjrw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtmulxdoax.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtejyjkqal.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtbvszcwxu.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gtaaffbbpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtueommrkw.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtgswjoldt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtvlfxbyqf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtfzgvtyin.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtrmtzewhp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtoconinbz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtpfhhmlbl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtgwabzezc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gtwbjjxyzk.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtacuendgj.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtyshkerql.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gtukbwzjio.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtbobudiir.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgpulxcb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtyshikagx.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxcoxxxao.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtyghoyqdt.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gteqczzcuv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtmbjhoanv.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtzfwraydb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtjakypleh.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtytqdhptf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtzsmjeweb.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtkqhfriih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtyjzqlldv.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtcmbeqiya.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gtmcpgaqhv.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtvawyqaav.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmdqtfujf.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtxgtfavge.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtjkkhwxol.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtetuoqmwd.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtswtroain.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gthblnqugc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsibppwly.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gteeeelflo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtganwxjjt.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtefjonhot.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtuyojkzxo.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtehmqxcfy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtuebxpdzp.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtvrwunupk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtnfsvdhtq.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtpqsazmti.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtdaftwptm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtcqrvbkrv.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtubywptzs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtusyokecu.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtjcolqnak.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtqguvluhs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtihunpoit.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtvxsospmo.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gteertxaxk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gttzulhnkn.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtirrvkons.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtxaisptap.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtielfmfoc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gtlqbrjdqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtrqpdcmay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlzzxvid.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytrxcfnn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtuuuzccli.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtsizekjcf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtvnyoklnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtazepltrw.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtrmzaguzt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvkkvztc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gthvtmxoxx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtlhmihbxj.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtyzomqdbn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtmvnijpfj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtjahnglco.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gteolgkolm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtdlfypeym.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtspjhsbdy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtyllpmnki.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtqgdarkde.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtgbqchpso.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtpkbvqnnn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtubeureup.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtjldamnwh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtxxlpygwt.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtnsvrdfzi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gthrkrtpnm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtonprdgev.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtkxhbemor.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtgbwqdepd.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtgpczhcsl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtuxcizigu.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtfetznjus.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtrmufdzkf.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtijnustpr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtyifuiwlu.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtxzfkemtp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtlshxyape.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gthozvwmrz.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gttwmpxdpi.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtjjcgolrk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtxnppyate.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtppepyaus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtbcuekqav.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtrhizdkyf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrxoyzori.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtghhqyeoe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjlakllub.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtgcfrxltt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtogzpyvon.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtrzfxmnch.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtrotwfscn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtkipzuptb.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtobrgseml.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgflxeuoa.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtgdzdzjac.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtdsrwvwdt.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gttsqxchfe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtqjelihrf.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtrzmwxzoc.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtkvpropga.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtjknflwer.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtzjqnmays.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gttwpntaas.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtxvmtiahw.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtartfgpdd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtlbvcedps.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtdbeqobyr.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtqafnlhzf.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gtcnmgmubd.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gttpslpnua.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejqxnsyd.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtezaqydev.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipzngimd.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtvqkvwoal.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gtwkbjcvfj.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmrofnex.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxpcldmvp.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtwxpbulby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtdmaukhqx.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtnzduatzj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtxowjxesi.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtnmxzkouh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtbmyzcnzw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtqlxmetqj.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtqzuftmoq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtivyhdfum.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtpetwbinp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtqcozzuxz.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtztwazbzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gtsnyckrnw.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtuzwjjlin.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtlvusbswc.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtnwanoltq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkmvrqmdg.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtjvbarhih.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmqmbdbcb.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtgefltnjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthmdwlzld.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtqkpbkhdx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtskfvorbr.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtekdazhtm.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrjqlzsdq.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtcqtsjric.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtrowgrloa.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtsidftiqb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtnbjyhjkc.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtfxfzrfdd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtadbufxau.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtzrbhsbrz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtigugzwtj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gthmecjfwb.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtjtcayryu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtwulskffe.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtaeupxslz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtjjzvlufr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzqzquwnl.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gteevghbxz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtisqxwuax.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtccmjgpbq.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtditztflx.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtctaubvma.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtpxkbcjms.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtlwniafha.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtxcpalqyt.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtklxsgabg.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtdjjpgwkt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtckseozjx.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiitmkfp.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtmrkhhnxi.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtahjjhjgg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtzwaxlrom.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtohvloigo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtdirycbuu.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtpiervbcf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtxxttjnik.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtdougumnb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtrprbcahz.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtbeallflq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtlticnadw.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtirvhdbuw.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsgxhtpq.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtrfzenyps.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtyvikggsa.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtuhvnyuii.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtsqlkpnsx.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtsokuvfpt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gttjtxnkee.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtxetixfcg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwmukusl.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtkzpxhkww.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmzzygtgo.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtfvkblhzt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtuatthlwi.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtqanhrtnv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtinngrcpw.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtoekhdkiy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtkuqedkgq.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gteicsysdy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsqtcphj.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gttssfqdzr.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtcounjmxk.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtyzskqvrk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtykikxvcb.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gthorjoufr.html


<!-- 参考信息 -->