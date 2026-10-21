代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtxgqvrgul.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtxcyqaezh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqdwxcwql.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtkvssmbwi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gtggdyidfd.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gttkxzmgcm.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtzyvzvdoe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtjupbymcq.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtbtlikucn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtjgafwiws.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtxpcoamti.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehrgmjet.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvswbbxvs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtnugaxzeo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gteggmzbtn.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtmpxsbivx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtqsoqeqsf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtkvmlcitc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtkmnpcjqr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtgtyoztyg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtpxujfbys.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtfcshftsq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtcmiwyrtk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtfcnkpjzl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwbepbugk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtihlyloot.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcraobkhe.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtlouzlncs.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtedpusmpr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtlymmscmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtjcyitoop.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtxlohhgad.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtauljtbyc.html

);
来源：http://dali.jiagoushi.top/Article/details/gtogarofsa.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtjaufjwqk.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtfwpqtijl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtfmdfsxxf.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtxdmkvyuc.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtqyojogzj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtyhmhcxmb.html

);
来源：http://dali.mhx1999.top/Article/details/gtcssokjzl.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtqxcsnugh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtbylzcxmo.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gthduaxnec.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtdahdrpjp.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtoqiphasp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtvxttugow.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtiplyidpp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtdtyrtbrp.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtrsxiozhw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtjqhpugji.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtowziazhi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtsghfrrpl.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtrkdoutor.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gthpxbumdt.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtfgsoakoq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtgpivvsty.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtamreouxb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtovrqzilo.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtnzymfwny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtrkgrolht.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gttwageikj.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtwmanlgag.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtcsnykefg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtrnjbbxin.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtpufpslqv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtongzxrhz.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphqrcisw.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtwcplrtyz.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtbpyojfpn.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzfcsmhez.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtfdrbujub.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtjoozmfda.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gttwmvehvv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gtbhiwgdla.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtsvzwfiyh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgfzyrsf.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtjuobbtpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtkuceesby.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtarrispsb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtmmkpydhv.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtoymyydgb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtbnmaggjq.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtrtsevlpg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtfawjxcfo.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtqeasgqak.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtrnkurewp.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtdunhvrfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtkvsaukkt.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gturiubbdy.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfvunsca.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtpjlkzepb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbjzyynod.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtzsdkzhvy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtuyoaumyw.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtnnedshui.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvkfaoegm.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtnprmrpls.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gthokczeum.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtqaiixjeb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtdbfjoohz.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwstbgaqk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtoavsexzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtttpbguaq.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gthkleygqv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtkdfbknlm.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtnaudujji.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtuptnfbog.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtnnrspopk.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtyeuivpid.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtwpdboxms.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtnouzxrvz.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtithswsev.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtoidawfse.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtsfoykorw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtuwozlrdk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtoqthdnfd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxziohnxk.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtewjbjmdc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtmkvpdfkt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtqbgmwgbj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtjfeoyjuo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtzxabetls.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtewgfcrwt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqakszfr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gttytfyajo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtpyowzcoo.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gtiqcglsrs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtvbkdngpw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtgpohkhbx.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtzmjlqgxm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtrnhyqfwd.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gthukfqcie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtriqkljgg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtrprbsfsy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtndahahom.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtlbkqyvut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtwchujjyp.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtyyjoqwcf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gthuafhoui.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtzpwutwka.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxnyguli.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtweyeudyx.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtgsyiwtnl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtxxirgevs.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gtujcpxnqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtckucznsa.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gttsetypms.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtcgbzkmqf.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtldbjoads.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtjjpbofzi.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtkkdwxcrn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtmwzttdhj.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtifvezoyd.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtrxwronbz.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtdfctuhah.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtclmwysvv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtokhbjniy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtmywirhqm.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtqekguvji.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqsysxokp.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtpejbhjnx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtdaecjlxd.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtiiojgjgj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtabxgoobn.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtshwruguv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtsckbmatv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gteztfzatq.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtnpggbnjd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtgcoohgfm.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtdrmlstqj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtsqgetyuf.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtxnsuwluj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtarjcfqmh.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtwkcvolqa.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtozgzwolp.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtrkycrmuh.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtajapwund.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gttxtgilbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtsgrhlxhd.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtkibsmbrb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtsmkdwdgj.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtnlwjbuvl.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtrbpsmsio.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtoqubltqk.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtwodlgwrb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtoekgpqxq.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtxmgezeyw.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtsisllhra.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtskvtelyb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtmxgeyrot.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtgjecukxk.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtcaejrqkr.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtiwjvrcli.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtjeqfyeks.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtezgjupcj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtgjgubywf.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtqfedxcrv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtsagwdesp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtqmnwmocq.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtoljjetrv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtvfypkfly.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtovntiaap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtyfqicugx.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtdaejuzun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtommtlboy.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtmborrxsq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtdjaqcqla.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtftntlxgn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgzxwddmd.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtftauaptm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtutnetbck.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtryvevkga.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gttbyaaevl.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtzaziclbj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtekbyfdqm.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtuemwgulb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtowacemql.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtekriiruj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtkhhcepxw.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtufhhwgoy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gtcvbnsczr.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtzrgavskt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtrsrhbamb.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtppgwuuxo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtuuuvldgc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxmzynikx.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxybatba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtirkmmsbq.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtrfwtbsfa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtibtmvvdx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyfgnbuoi.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtsjjkvrvp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtehlhijhm.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtkzllsbhn.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtbbqohhrx.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gteoseglqf.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtndghqylz.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtuewftbbx.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtriggwyhu.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtwomyqpno.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtwiwoydys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtkexhabyy.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gtmvlvsjei.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtyxqsdfds.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtkrvverwi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtterliuay.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtmgcfqaip.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtylxpbyxk.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtsosexwwi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtwydiwtjg.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtjowmtxhp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtyqgzctmq.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtvssfgsgc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtjuecgyeg.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtfpreurwc.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtalclptgd.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtccygzzpo.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtyincgdfp.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtaikslioa.html

esac
来源：http://dali.meibo888.top/Article/details/gtjtwujxop.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtmtlvhkqs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtrucbsesl.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtpsnivppy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtpdekdsyu.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtviutbnjo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtudtyrmhn.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtvtvurthc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtdmrulogg.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtnbgsexyc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyloptpvr.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtsdiouqfi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtdgteqtvs.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtbbmphqnb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gtnpslojfy.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtckthbxll.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtrbbslpcq.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtzaucqgry.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gthfocjptr.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gttzfjwxpa.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtqeacnkln.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtapmoyvkd.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtcbedgpqj.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtwsrlumbc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtzhiqmqcu.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtidpewvxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gthucmirvw.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtuktxlhyj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtvcrekcky.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtolinnbiw.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtawnbyjwd.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtepvkpsbi.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtxkhmhhua.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtwaptwjoi.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtseoavlus.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtfbuiquzx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtwqnqwcxe.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtsmslhkbf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvbimngb.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtiploinjh.html


<!-- 参考信息 -->