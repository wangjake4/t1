代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gt2ghfjzmwi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2shghqlll.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rygznijl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ybhvxitc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gt2jvqhgugt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2gzxltzni.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2uktwwdkm.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gt2jumhhxit.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gt2lfijqivz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2chhgwgej.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2avnctoys.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2hhzbwkeq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2oiimdfhe.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2ezkfnffg.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2ccjymzhb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gt2defpgzom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2phxbkizu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofdubuvp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2kbkcxnkz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2cweymtuz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2exgeaaxz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbklalbm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2mafoamth.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gt2liyxwniz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gt2vmyacnnq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2efdjyabz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2dntplgku.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gt2nwpgxttj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2fqbgezlz.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gt2fgacfeqb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ruasgdsa.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gt2kzcjuuql.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2syjraebh.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2vxlbliot.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2olvajrkf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gt2tutzhian.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2zrpvgiun.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2fadmnxij.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2powjmkiz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbwnkhqb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gt2nqdartqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2wrixfjme.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2ppuilaao.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gt2divmrqql.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2emjwblhc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2rlwxriti.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gt2jurudlua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2igktiuwi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwaskhyu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gt2cwatnaxb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gt2lahvhzxu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2hnjkqgxh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rnzzhwdo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2ypuzrcne.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2osmmzexs.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gt2wglfofmt.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2vclqlfiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2qkdjjujt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2yffkndhx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2embflfer.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gt2aycrquaj.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2eoglgjax.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2afwjtkbj.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2yzckhmui.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvnzhuj.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2ttxwkyss.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gt2qvbdfpda.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2vzifzyqj.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2krxyptsw.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gt2hcevvstp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2efuseynw.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2ljsqyiwm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gt2vpnzmcaf.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gt2ydwrcmmb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2scstqckq.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gt2ppnohsmw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2kpbkvdvg.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gt2wezszvuo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2aisepcht.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gt2jjkhjuxn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2hfofdbbz.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gt2fyslcbrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2rabtjkfb.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oknlxogu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2mcgnpdzz.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2rfcmejqz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2zxncgasy.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdyygijj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gt2ikppiufk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdvkkiog.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gt2upwvrsjc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2nkrfoeae.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gt2mvmiiujx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcrtmluj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gt2xniadozy.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gt2jvyixfwf.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2qmjlqfkf.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2pcploaby.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ohpnggnk.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2byesonfi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2ewzwevmd.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2vxqvpyfe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2coqejaiu.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gt2jlugbdzq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2fkvstbon.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2cumzglmo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfyjsgcz.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gt2armhrhdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2ykrgopzg.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjawajuy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2apvxmgxe.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2jurdfwph.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2kabqjbbl.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2nzsdcqbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2bnckdoje.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2ohgpvacw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gt2lvwedqui.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2eengaukh.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2zdnrdnpu.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2pekwurrs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2opjyexuu.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gt2jsdcdwpi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2ekiilgcf.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gt2vtithdsy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2vjffstej.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvmgwsmd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2hjopikjv.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgebwrpz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbfezxgs.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2vxrvefaw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2cxggwsbb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2eiikoufb.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gt2nfupqfpv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gt2whhgajgf.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2asjsxydy.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gt2azcjrhmk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gt2gibqfifk.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2ovvlmuho.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2wjdopzhq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2ucaryopn.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uetjulez.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2rdohwzcl.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gt2cvykknza.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2cphuvtqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gt2adpieper.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2mrtlyqyp.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmcviwfj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2rjsgxoab.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gt2vfzbfetx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2bcoisfsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gt2xihgbzej.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoajuvw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gt2gbvqhlnn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2sersfmkq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2vlizbqeq.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gt2lcqzbchw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gt2ddgrqkct.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jurlsskj.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2zafpbrwu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2wsmrsowf.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gt2jqrdysce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gt2lykirlhr.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2jdsoeqwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2jskhlxxj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gt2vokzvpfl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2wwziqvvo.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2gtdgsqms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kllienzx.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gt2wpdwufwn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2ndtvngba.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gt2vvasfuqe.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gt2yuhduvhn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2hhrumaqw.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gt2dhlmiarz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2lqmdoogd.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gt2kprmsidm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2rfwwearj.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gt2efeahztk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2krocintb.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gt2cqkljfrs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gt2ojseddeh.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2jgrgeulo.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gt2tmsfjtes.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2njcxpqpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2nfyzxdxy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gt2dccfwyun.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2smjwdmyv.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gt2iodfypcz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtvlvhjy.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2xsbdvemu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ehypuddl.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gt2ufocznkl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2rofyxkhc.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2vzmwvtan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gt2pgkvgffz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2nkjnvjbv.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gt2zvnxtunp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2kwhrmlux.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2dtecakgl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2coesbeuu.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2dovnedfs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2ypuhhweu.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2puwfmdst.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gt2vnbguebe.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2wvqhcaor.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2kdhydejx.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcaaqwuf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2maoapuuq.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2nokobeul.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gt2sqozzggu.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2wxvbnbvx.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2wpbgwtli.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2dargufjm.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2wslebuev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkntpjkc.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gt2kjqcuvrz.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2vsspybge.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gt2cxkbicsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2uobzzoqo.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxjxxhmp.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqpacyrz.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvrtjtjj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2znsrbarj.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2famlfjul.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2swuevgas.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2iolgnrtu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2aemycdeh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdiechmz.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gt2ilttvzof.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atnmlued.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2wwjbccgj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2oevrafxe.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2nichfwyh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwyrgwif.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2enrrozlk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2hyazymev.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gt2whrzezxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2ncggccox.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2sjjtualo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2gptgajxj.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gt2atdtwdwf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lysahmte.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2itthnxau.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2nbotxcdb.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gt2toiifgmt.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2fxtbrjhw.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2afhhlbom.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gt2uengfheh.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adiecwrf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gt2qxrezuqv.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2zxwhieae.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gt2vmfawwuw.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gt2nvassvyv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2xubpejwx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2nyguexdq.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2oflrbivb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbsdvhyw.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2wdkqctrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gt2nhgkjwhf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2byleeawj.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2lzxyxdkl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ybjthxmi.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gt2wiuyfqjg.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyxrfqge.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gt2gjwsvfwl.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gt2juyheovk.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2updsqmfi.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2edevswjj.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2eabliixi.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2zvwvggpu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gt2yadkfisa.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gt2urbjiann.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2adiebpbu.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2znckqbmr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2qloyiveh.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2aggvpcnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gt2rvvsnjjd.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gt2yijspbec.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gt2gjpmceep.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2svreqzhp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2dywhslkb.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2rwaldgio.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2eeoqqhik.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mswtlavj.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2ahbnaedq.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2lybghskh.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2bcffqmkm.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gt2jjxgwfhf.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2mbdlogfy.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2vqcuknjg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2ejhrzgxu.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2njqkuhuk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2qyjkritq.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2zhycetje.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2zilrmofy.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2oujavbta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gt2xfhloomk.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2kuyqdsge.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2zgsywwmc.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2uxxeiccq.html


<!-- 参考信息 -->