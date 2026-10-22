代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gt2endzxwtr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2jaepkivt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2itapqifq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gt2tcmpfoof.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2mhgglowg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gt2rfaanwvy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zeqdquzc.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2gafppidv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2nipqwaqg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugapmges.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gt2lojyupcr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzmbsymm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2pecjvvla.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gt2liwlgkvy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2xpwlbuby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gt2elmdojcw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wvkiwttv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2zbmvvmur.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vnxvqprg.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gt2kwvfijyc.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gt2nmguwrmw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2eloxojtf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2wvcjrvyi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2mkivrgoq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2irjrtifg.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2mdgdcbaq.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2smelfnka.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gt2ejuzllfr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2cyhnxahz.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2sfqzixgj.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2gpefdgcp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gt2vgaiqfvi.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2nlembfbv.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2zczzahpf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gt2akazbpwa.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2qddtmtpb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2haxszxii.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2vrwxmutq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gt2yneceqpa.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gt2szprdvol.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2zxgsaafe.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2khmawefk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gt2hmysizsy.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2rpabeqaw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2tqlqkcaq.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2ovoexpin.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2gscooliy.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2ndvahxif.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2pexrkkih.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyqtuluw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2kuaeseje.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnziersy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2lmahqbah.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2twvfqfjc.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flqvglei.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2yqxlvrkd.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2dpnvxluj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2mwmupvdw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gt2wgoxeatv.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gt2mrbdasvh.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikpioixe.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpsvutbv.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2gslrzsug.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2rnnosurm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2bsvwswjc.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2gdwdwfql.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2vjutyzql.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tywsgjoe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gt2jnqekqvn.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gt2tbeapemd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2pbzbsgbd.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gt2qtlpivlk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2iyzdsqum.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2uzemdzjj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gt2silexcvx.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gt2vdrlutfr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnajzriy.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2chugywss.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2jpjaywtw.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2hmsplksp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2ciedeffk.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gt2ittbbxko.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2gozwbdve.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jszcgjxd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2rlsqjisi.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gt2srmoiujv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2ogfrfjwt.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2poolfkpa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2uypdzdnl.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gt2gtyzgvti.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2kpcrqabj.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2ilcdktsz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gt2kqynyaoq.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ylswdtnu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozdwcmhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2qvdmybkl.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwbjrymf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2phjquhks.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2ryypiehv.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2umhdooyl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2eyyrqpnx.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2hynosvoi.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwfdxbvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ihyimewc.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2ahmdagav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2dxntjmzg.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfcfwogv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gt2alrcpwxu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gt2nkhfokci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2fllekjjm.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gt2akfovypf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2owuoufcr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2zabjktym.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2lnbubqpe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gt2usisuqap.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmtmobho.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gt2lqprjyxz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2gydewkps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gt2pnkwnsej.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2ugtzkvla.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2tpxlksck.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yirozxnu.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gt2ijkdtsqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2ulpfeiyn.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2girryldp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2jmkbkkti.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2uccvmrtg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2mxjnzzxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gt2uzauxjqq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gt2sxsbsobz.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfgirqtm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gt2euyirghy.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gt2suuinnyu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2ianrxoqp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gt2gbibbwrr.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2lkaimuwf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2rmvxeesv.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxatdxlw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2xvcgmwzf.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gt2tpbsocuu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2rpyszjdg.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2napvagmt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2tmigvnpb.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2jtcddfld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2kcwclowb.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gt2wbfchkfw.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gt2gslvvdeq.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2fshxkxxu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2rmkthqlf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2luefipxf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2aslsimpx.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2zdwwkqsn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2xkdvuyuv.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gt2pfwsidhf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxleqdvi.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gt2prluiqil.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjhfcvwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2pioecihg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2teamynbj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2yfnmkqvu.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2abcuyzdb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2osercaqa.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoitqsmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2baamwgfw.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gt2gxuaofvm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gt2odbkkvrp.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2xjivvtsr.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdoydlcv.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gt2hkfrefua.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gt2uqycfklb.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2owfuatxj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2kvemfgdx.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxrqoxxb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2eoblkiem.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gt2ctgwqpjx.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2ourpbkhj.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2tewizpao.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2zuukufho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gt2hqvalckv.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gt2vajueznw.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2gyzffhgr.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gt2gtwytycy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gt2qsfxgbjg.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffwbeyqy.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2joxfdqyy.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2ckcsdnso.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2zcwfssic.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2knpezeuj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2qrvgyqsj.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2rcwdwksw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2akuiwnpx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2hbwecihb.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2yrytlsws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2ydjkwhsc.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2xvfysopa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2vxlmsilx.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gt2akjwwrzf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gt2fgusadoa.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2jgjnvyok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2wxqrgriv.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2jxhclvju.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2xgckovez.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgkixsaf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jhddaptk.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2yfigbavl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2veuhxedy.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvcqygtz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2oijelale.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2xcyexrul.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2mxyobomt.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gt2njmdizwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2bttkhcib.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbxwrdlq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2eyfqfetx.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2isdbsfqd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikcqbaru.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gt2dhdhxnai.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2sflplyfh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2yjzetnkq.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2oawnisad.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2mvbulnvj.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2oektskza.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2dtrtohib.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ppjxbvak.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2rtyvsokj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ppwonfhe.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2tvbkodob.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gt2vmnojjgs.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2ffmnqnze.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gt2xhaabjqi.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2sdjzkskc.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2ikvcdlax.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gt2roeszmir.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2vxvmasfx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2xtylapnn.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2hlvvcnxg.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gt2xytssgsz.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2eymyxmes.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2bmwmaber.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2xkkythzq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2hmjswzjm.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2enywdsmw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gt2pftxfowf.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2ashlfgpd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2bimsuzuy.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdezhsyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2qfsticeh.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2iorxxhtc.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2ssdqxjkv.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klvbvfpc.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqiclqua.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2ipoyulzf.html

esac
来源：http://dali.yonumen.top/Article/details/gt2onkjkvyv.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2slthamxy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gt2ctiipsci.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2nvuchnuy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2hgsvqqri.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2efhfytem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2ctdvgkjf.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2aypknybe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2bfqporpq.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gt2cvlqndkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2pcrujoae.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2kaulbenp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gt2pesvbald.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnrrxpvc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2qexxskww.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2kcpwkqyr.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2xtatdzzh.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2iowmrxzi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bheaighy.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gt2pczcbyim.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gt2zfdrwbhn.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2mciuczgl.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gt2hxjimatg.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2afegxzkh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctotpiuw.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2lsbnlzch.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gt2plyamged.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2mqwryjdq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2fqnuunvu.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2zabcaosp.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2tvfgfsle.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2lbdayosl.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2bcjyqeqr.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2icjgkmbu.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2ptjvptcm.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2xfpqskah.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gt2jybyvjnj.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2xxuejhgw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2ctrqjmcz.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2mcrrrjrp.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2imaasmuy.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gt2ksrkxuju.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2avmlfupp.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2ssntnala.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gt2qgpzkzmn.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajnhikxj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2vpkvdfxc.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2wspukrub.html


<!-- 参考信息 -->