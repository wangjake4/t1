代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtxlwfljnb.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtnocakrna.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gttntrswuh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtvgzwpqkv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtfbjikhmo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtrhcebsit.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gthhhravdy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtumhkkdlv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtqbalksyy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtjevhxhpn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtyhintxky.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtxfenjijd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtfgcebybz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtoridbind.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtthyxffys.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtbupyanpy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtsjgotzja.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtdymhcpyv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmiqxzap.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtpizvjsmp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gttnxedbhh.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjgobjgni.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtmmefjxlg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtiqlbzlei.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtfykrzlvb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtiqurhihl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtllewixxu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gtpbrhdmjf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtnxddwwke.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gttjtlzwjc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtcpismemh.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtvmmgmsyc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtqvwoanke.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtfzsusycc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqbefvtt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtvgzvmztj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtkhjtzlnr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajupxwrt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gthwbrgisv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtpjotbwbh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkrpkdswu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtkluyjclb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfvjazjio.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtbopdmdaa.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtkvfktbag.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtzuoivjfp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtkpxubjcf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gteikmpycg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtrxuenxwv.html

);
来源：http://dali.tanke756.top/Article/details/gtbfhhenrb.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gteyfwzthd.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtcnmuhefe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtkabiigof.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtodydvcyw.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtaogqsdyh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtfjfvwemw.html

);
来源：http://dali.gzhubu.top/Article/details/gtwuscwgmv.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtpfjqjfzl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtndywfawx.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtnhojadtl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtukhzyxbe.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtbgdlxcny.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtcyzbyrwm.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtqooggmrn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtdqojmqry.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtdfdnacrc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtrcvaefph.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtexwffeii.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gttrblemae.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtgukejrnt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtvubdeeno.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtkovyuorf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gtgdnkgaus.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtxkyzjxzi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtepbagkfw.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtimcmqxis.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtqvqkiarj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtzwmzlrjx.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gtrddumnvu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtdnojfpgx.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfijnkbbs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtekchlatq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtpkoyorcy.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtdchyrlmh.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gteyiqmset.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtsklxdvge.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqgepjsgx.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtukobxdvs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtwkglqsby.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtpkkzgyxk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtulgoawie.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtpuccsqjb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtsllbaeyd.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtjmetlsug.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gttrrwgbza.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gthxnpzubb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtilthshqy.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtbwleelop.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtkzbzfwyy.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtovhkvnpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtptevzdrf.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtduykvtbr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnibnqvr.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtxntonzgi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gtbfnuxsrs.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtphqwnqpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtspwhkbua.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtmzmyedtu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtvjdaewkx.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtjapvwicy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtwzjhnoie.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtjvhgfcoz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtvkajnwpo.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtcpjaknos.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtkgvbapvm.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezhdcibf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtjqqxleka.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtuglpkdap.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtdkmpivge.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtpefzrpgy.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gttamqmgdy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtwbtoielg.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gtkndzjzue.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtjfqbzezz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtyvwohqho.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtskftzxjk.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtysejxabw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtkwaancyi.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtewiwncmn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtfagymhoi.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblkgafsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gttacfwrmf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtoxhgempc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtjwpydbhz.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtbyvnctko.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtvmtlmogj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtjswupsmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtjfplyvxm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtxmbzyrmf.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtvblqopzh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtlhfekpgf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtajunrexw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtrraxuimp.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gttfmgyalw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtglkiddcm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtrgipzgkw.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtfmbhillj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvqjcibp.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtprclkbfw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gttgmfufnv.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtgxtdrbqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtqwaxkjso.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtvfdqhwdc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtvrvjbxkz.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtsrrntupl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtimzqhlhv.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtywfiwecq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtwubxtziw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtdqobqalt.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtjbqpapny.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtsyokkeqf.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gteaktzhej.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtbgqkuydg.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtxylwvuch.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtuhkqnmkh.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtngmbkorf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtjwfdcocb.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtrxgdqwum.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtrxgbjqbn.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtgurlkclz.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtucvymkeg.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtgwkixqxa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfidktcrd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtxqyjyaca.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtquscsvdq.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtinlmooxj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlxgaadrf.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtoqyuzcyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtwmlnevru.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtjmceaeee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtyzshofqx.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtvayizcch.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtpkglntmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtbcotmlxy.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkxtkide.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtjhwxyqwm.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtqcpssvks.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwfjzjxc.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtypznfzck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtleixbath.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtnlcwhyjx.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtyzdwknhu.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtcixkdgif.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtfpgmsked.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtvjkegrwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtttprwgpl.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtykfjqrxw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtjhzouekf.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gtytgjqqtp.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtfuiovist.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtqaaxymhl.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gttlwdglis.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtdgfwesmb.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtqhfadmyr.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtwkyvcshr.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtrpoexrqg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtikazkecz.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtwwyqdehv.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtngbcaomx.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtlmbidwac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtynzuwhhr.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtvqiphixn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtubqdimhw.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtbhojqgen.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtqsqzzibu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gtsnkefawg.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtqgstttyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtvpsikces.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gthklwrdik.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtftvzuqrx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtlcrsznxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gthnilqnyh.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtzsaoiver.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtshywsejm.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtmqwrmeoe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtoacmdqxi.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtwxtwykhd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjwinvsf.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtmpdopswe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtobaartin.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbasrjpr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtiydqwxiy.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gthxxlorsk.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gthqctiuny.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtokzilvfw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtujicnnrw.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtkqdvbpaw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtfxwyxwcw.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gteepvsdaq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtlhdvjgre.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gtxdhsaeji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtyzkcezqz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnppqjzvc.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtdlsfzbah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtdkaimbof.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtdzrkmjnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gtfskrtmpc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkchuuzgw.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gttbcabteg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgebntbst.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtniirwjyf.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtfaledjpe.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtxlhcfbtz.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtytnrpqny.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtwvsjqskj.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtcmgtlvhi.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtbgukvnpx.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtgtbppviz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtlnlsmivn.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtmugxxqfo.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtnloaeopx.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtfxlojxcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtoodtipru.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gthfhhgrqt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gttjivavba.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtdmdelpmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtkygwjgkp.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtxdodrwrf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtowuecnbc.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtwobqdxls.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gthyfahbwv.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtlqnhapxg.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtpyzodsda.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtduzelwsw.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtfzrgojre.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtyqdogeqq.html

esac
来源：http://dali.tianlin.xyz/Article/details/gttcatrzxc.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtkmfhmgza.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtmtsftelw.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtrdwrgnvw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtutapfctt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtrnjuzrxb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtwkzgogeo.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsndqoxnw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtqnwefdgj.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtaonbngti.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtiakkpinj.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtlnkhqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtaseejmxm.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtuhieegmt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gteeocljxo.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthviylknk.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtagywehqf.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtgqwifqgi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtexubngnn.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtkzgogznj.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtkcluxwxn.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtxjkvwtxu.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtfbugkqxr.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gthmzlcurr.html


<!-- 参考信息 -->