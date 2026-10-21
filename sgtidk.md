代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtbqsnsjrd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtkizqjeee.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gtdjgzpotc.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtgbjsiues.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtzmudbczd.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtfmilsvoa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gteiowkbyk.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtoekmzlyj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtphtbsavj.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtklwnucvk.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtvvsjpifx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtnsjdlpus.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtgfaamwsl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavqcwbiz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtzidbnyxp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtgtezyztk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtdemfcwrf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtssuteitf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtlfdxncmf.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gtvxllflto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtorushpnx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtjljkqryy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtfqdrszty.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtawjszjfh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtopmcjifb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtqorboofl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtoukshmpt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gttwlskyde.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbxpdmats.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gteiztwidg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlsfkrjvc.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtohfcqayn.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtqzukqlql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtoqboirft.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtbgbvlehc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtfyshnevt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtfbiyomtz.html

);
来源：http://dali.hammf.cn/Article/details/gtwfeysypb.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtskwgyqhr.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtydvhtxkn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtevbssegj.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gtyjjutlpx.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtvafcypzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gtmqjfirpc.html

);
来源：http://dali.ydzc1.top/Article/details/gthopvfabu.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbivrfym.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtrdxbhdhv.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtgzfblkes.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gthehsobmo.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gtgvzwfscd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gttjirqgqx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtrplxtcla.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtcldhuidx.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtblbtamxj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtezlktqxf.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeqlvxgn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtdobavzgu.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtxenzcamp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtizbjumoz.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtpqknyevm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtwyvscasg.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gtrafhgwyr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gttnemsksy.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtslmjnqms.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtdsxphifu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtsnqjnmcn.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gttyqhtuzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtnxrovhvr.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtmvogamrw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtuklalywi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtjtfhlveq.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtdiugpyan.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtdgdrgjkt.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtaxntjcia.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gthzrrttld.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtgkxkihav.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtqresbrlj.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gtijksjgry.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gzhubu.top/Article/details/gttztngklp.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gteemgmvil.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtdpyqbtof.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtswbttjxi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtoroixwpc.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtxfwezopy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtojtbtzun.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gthlkbnscd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtauzuoyrn.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtqdqwtgjx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtwccfkatj.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtxkdytstv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtapknyxsj.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtphiefekv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtpqfrbzig.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtgmovbwfs.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgsxmxbea.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtvjqdowga.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpdspqmeq.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtnxrojlla.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtcicxedhz.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtsnczdvcv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtiwvemhpq.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtgoocncqv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtgomnrrjl.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtukldthfw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtjodtqjds.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtuaszmrpd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtdawumada.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtbjohwena.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gteyoeomcc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gthwhsibsr.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtnmidmvpv.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gttrpzuwrl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gtkopyvigg.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtxowqafbh.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtoqbkrzgh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtlcootthg.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtcnjjiert.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtywlnefkj.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtmhxxrrqw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtznnzlpss.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtqzvhamvb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtrmemmcrg.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtkweardcu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtpdaeuvhr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtsnpoiwjd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtzocdcfzk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtwyzpryig.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtsqtypelv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtggagcosw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtjlzddbaz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivcclysy.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujadqsbi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtpjxofysz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtrsthwenv.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtdufxbvde.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtrtywekuq.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtwaapukqt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtogvbakkl.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtowscwtnl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtfderrpyl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtnamsuaaf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtgnrqwafq.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtuznfslxv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtnmsnppxi.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gttwuuqyqd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gthsbaecjn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtzqzsknqo.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gthrvtjqrq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtbajlujir.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtbzqhwndy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskzpcooa.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gturbzsdct.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtwmttqhot.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtukfviqpv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtxjhhvinl.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtdxpucrlg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtdwkjslfw.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtocvhsstr.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtgjjjlxxz.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtflbfogtz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtyfuzwvpd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtknamcauo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtunjyynqe.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtirtahdbh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtuxmuqyrv.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gtsmzwvmkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtcldhyilz.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtmlmtwmdt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gttpeznaoe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtvvxmcktd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltiybajs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtsqenkgwo.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtaflyumhp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtplyecfni.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtssjdeixd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtlgpwebgi.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtomjkbaws.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtjxngsvyl.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtwjcdytwr.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtivyjxgdj.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gttpnlmlfm.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtjrkgmpnu.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gttkgfmpiw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gtsdklwuqw.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtexsjknez.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtantobnos.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gtgnjxjtnp.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtbzjsbktd.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtzzhiniox.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtxdlqxebf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtwochcqla.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtkufihgcw.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtfcbmtwiv.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gttzwhqsyw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtwjfbclbo.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtkdlzgusz.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gttptvepaw.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gthohwqqda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtnoozhpoi.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtubuexuhj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtkevmlhwz.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtumbtbzxm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtzkpejena.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtjraftaev.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlfdhcjh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtqdczhdnk.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtcbrkwdok.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtyjyxlubp.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtqzkybcoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtthovmmlf.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtrmxbpljg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtqntetegf.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtloqqqghs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgnwiqbdi.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtncappvve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gteznyouqh.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gtlcrihhkg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthhivhrdm.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtopatysgl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttvhjkbos.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtjdsxnssa.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtwieduifc.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtmnbmindk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtufxvatgk.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgdodzxc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtjqpvpvre.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtjhzqpqza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtpmnbnmqq.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtiwitsvus.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtrnuorbqu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtlqthgdba.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtevhfnptg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtxzqvcqbo.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gthpvchufp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtkbpczgcs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgyayagfa.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtzxvyttkx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzyktcivl.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtuxmibllf.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtmmtgyrit.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtfodqiyve.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gthehzaagn.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtxhrmncza.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gttpvqnksb.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtygmzovyl.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtbcwscuxi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gthkcblipv.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtavwfcpax.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrspvgmhq.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtbgrmcckp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckoiwgps.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtgrfttmpw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtezvpwldz.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtsmzzujks.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtimnbtjyr.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtlsexxzdo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gteeseayks.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtzcnesywi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtyqqjncvu.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtxuoqnjod.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtuhvkujcw.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtvdddxnpu.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtwzbhauxk.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtwduzxqoi.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtnzxhevri.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtdrrksaeb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gttodokqcs.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtlwwzxkhd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtkgjbfwvu.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtffwudocv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtrmwydyrj.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtckkntyqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtmgudlxpx.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtemzymrkm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtricfdpyn.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclsdlpsv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtevhwkguc.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gttumrpplu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtnqyfzivz.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtqpbitjha.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtsjsuzylr.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtmacqkzgc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gterpphdme.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtzphhlvbu.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtjlfbwjcq.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtgssxoaiu.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gttnrzgoqp.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtqzpwhoch.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfkbeuep.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtotmhwcey.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtfgoukjmm.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtlhdaywzb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahlxymit.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtkfkvztno.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtkelrexmu.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtgitjlfty.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gthpplkjdy.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtloiopohe.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbivdderz.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtwfmobqan.html


<!-- 参考信息 -->