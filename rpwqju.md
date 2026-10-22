代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gt2zrqekmtg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gt2hrocedbz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2tumfdajq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2rcuforpx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2sqhwefvd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gt2zrorpzso.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2rvkiwigt.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2inzrbisk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gt2gvernvad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gt2beywlgff.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gt2yaxthnze.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2tbdlpszj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gt2hiifoicn.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2njpnsiuc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2oibwatmq.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gt2luroiqhv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2vuxxokkn.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2veeiznjh.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gt2zkafkidz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2fztyamoh.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2rtehhuej.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrvsqoee.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2hyzqxvzi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gt2huxsxwmx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gt2drhelnys.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gt2kelzwllc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gliomcww.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2pfjxghzl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gt2maqxtoqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbefksop.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gt2jfquyfmy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2ydmzxnni.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gt2asojoczt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gt2vocendov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2iqgpqzdb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2yeoxlxqo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2pzmzjieg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2tvdunfgx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xgtybeml.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wntcuref.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2zwizmink.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2havwuskn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2mvoodprk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2lnwlnjxq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gt2swkjugwv.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2qcqwqund.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gt2zwrctocc.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2purjswxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2rhjndhwm.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2qjczjibc.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2xgjoetqb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2lccyonaf.html

);
来源：http://dali.wangdashe.top/Article/details/gt2mqyptkrv.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gt2qefeelwo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gt2fwvpcddc.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2loeddonb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2cufakdlt.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2pyvulexg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gt2qyjcxzkj.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cftgxysp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gt2mztlnfxh.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2ussbnofi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykqppkcf.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2uzyuvtkw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2ppbrwaoy.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2xusyznje.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2fiiadacg.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gt2pvmfiltp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2rmrpgjqa.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gt2jntwmxfp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2cfuutzsn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiczukfk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gt2ubosraks.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gt2hhtdxgpp.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2vvzhmqfm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2kbbnwgyj.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gt2xfnjlabe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2wkyfpsyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gt2hlwunxaq.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2phdtplww.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2relfesma.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpqpjmgr.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2xwfvzlwj.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfofutbv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2dfjzfuar.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gt2mecjmmuk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gt2zfrxecoa.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkazieba.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpjhlpuy.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2yuqczuwj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2ifiwonqu.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2wgindhfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gt2skoylmaa.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gt2xzpzltko.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gt2sjuaysmq.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnxevyco.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2qmkhddhq.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrjrcmqq.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2mqtnfhkv.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gt2utaabiim.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gt2egnzokqu.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2hxaiagym.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2uzeaftrk.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gt2rehqbyqe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2hmwflfnv.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2pteuahyl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2wmwfksbt.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2okalrjnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nytbddhb.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gt2jjzdmzeq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2dbflknpa.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gt2csaxqrrk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2nmmqrecb.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swcvbahu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2wjqybrqo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2fqhhpxwe.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbviwubp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gt2yugecmwj.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gt2nxqgeamb.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gt2pdkiuxge.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2dgngypho.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gt2nvvqviok.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gt2sszwvane.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2pflxacix.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gt2rdnyultg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2virpsflp.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2tapjntpn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gt2abztnwoh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2ynttihsm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2czqenokd.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2ylmotmiz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjadjqwq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2grvjhfbg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gt2zwgdgvfq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2uppntvwr.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghlfbpzl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gt2mggmkwgs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gt2hdczfdqf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmrvglxr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gt2sqjafktw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2ebponxav.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gt2hfzozrev.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2oxgnbpul.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2gspqerok.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2kzcgwehs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gt2acmypdkg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gt2yhrgeqmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2xescdcjr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldrbapxl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2cevnhktc.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsrvifin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2gvvowdhe.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2ytpozsub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzrrgvzl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2yjexhhkf.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gt2runcyfhb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddjpwxgc.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gt2enysbyxq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2nddkfcwm.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajnmyxmg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vprjsvat.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2pfcuqafp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2kevfxbug.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gt2ghncjvij.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yppqlfqb.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2ejzibfvc.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2ipemplzw.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gt2xlavjboi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2bsxcieit.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2jcxbbkdv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2yqbaztry.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gt2qwivjavg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2unyfzcpl.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gt2lmxdpzmx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saqebxpy.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2axwgwdxv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2lngtolrz.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gt2vktyykjv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gt2oyhnmmsu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2gnksdmlf.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2vfovmfrl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2zholeney.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hksdvuva.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2pbpmyyes.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gt2aozxttuk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2glxzqsur.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2iewsfyrr.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2fqwjvduq.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gt2tiokgzck.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2dnwtdedg.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2aoldhfmh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gt2hcepvawy.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2evdmsaef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gt2fculbzsx.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2obyczzju.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gt2byfpuhvs.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2yrerovch.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ictnbtqo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2udotnmyq.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsddqyvo.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gt2sftyktlg.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gt2zvefyhdb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2rslhilxf.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2ammeoqty.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2fzgqqrzt.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2unrteytv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2leilhtwr.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2eadktfmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gt2zsmfrmdm.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2orhiqvrd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2axvgvhoj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2kdxlrrgl.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2yfmaeuqb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gt2hbfddssy.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2nonovtxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbukhhdx.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2ksoqucux.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gt2gqzodkig.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2zaddehte.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2wcefjwba.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2lwrsvrxv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2klwptujd.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2iqcehmoe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2lefkecdn.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2wznfzvov.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2tvxnobbw.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2btabdhzc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ljkbesav.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gt2fxuhixqa.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2hwoikrli.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2qxysfjwf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gt2shbptzyk.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2ystzjqhf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2qcuhylau.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2tqphehrn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gt2tmvcwpvx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2dukpduga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2zssrqwyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2lkrmropa.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2ljdfzuzl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2okxrcxcx.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gt2emqdqcsl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gt2xblsfibb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2oercpzpu.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2uoazctut.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2gjmaeuch.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gt2lhdaczpt.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2zfmvzgjt.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2lbeqesyt.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gt2uipzvyhp.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2egrewpqt.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gt2ssgupeio.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2mchnlpbo.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rytjthdl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2jcwzdhqx.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2tdicadfk.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2cxazhoch.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2jpogaylq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tivlcntw.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2acpmlqdf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2oijvoxke.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gt2uegawhlk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2zfnjhlcx.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpgodhar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gmackxvj.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2tlboehfy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2tvtqdwme.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gt2kvctbuvu.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2scctyrqj.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hldmmbcl.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gt2psyqhtys.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gt2reaoebbv.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2cskwbrez.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2dhwnfsgq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gt2knsckwvb.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omjuckap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2yelzgqub.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2fziijnti.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2jumgfhxs.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2kuzwbkdr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2shmrmlix.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftknsmml.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2ibixcrxp.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gt2sfvinmkk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2ofswdqju.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqvergua.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2onvpraig.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2owhclsja.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2wtoddlpc.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2etjuyogy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gt2tfxyctfg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvimpshn.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2ycpnyxfw.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpisqeau.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gt2vqumuygc.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2gjakgpwj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2bffnegxx.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2iebxfzzc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2kdfpsgba.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2nmdwypmy.html


<!-- 参考信息 -->