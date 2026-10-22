代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtcmcaxvbl.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtavtype.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gtznxdkjpb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtrujunrwl.html

);
来源：http://dali.sweek.top/Article/details/gtxwctdsoq.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtofqsvcuu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gthryubqxy.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtskbuipdh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gtwsgsqwku.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtydtverpw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gtqqifwecn.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjnulrmc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gttkdsgver.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtknqguoek.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtngxkozng.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gttnszvimx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gthoiubwlc.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtuldhwslf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtqogxbaee.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtrxcbbtfd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtywiwzdap.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtfkutzsuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gttqruatyp.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtkvxqjusg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtgnuanlnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gttmnxdiqm.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtvhpjcibi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntbikzgt.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtcfpkjdho.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkymgyjsd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtoukmjdwt.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtnxdapbjr.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtzqrzjydu.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtieflfzod.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafssirit.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtmsfztdkx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkuehmhxi.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtnuoerxhz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtlhmevjhp.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtdtjfropi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtnuqazdwb.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtsthdzddk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtwyzkchni.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gtqntjajek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtvdjpijqk.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtvrqvvaeu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtjzfgutgs.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtcogfbmsp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtasvxitcy.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkregfahi.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxbreaqrz.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtqpnkzgfk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtzaihbjvw.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gttswrppkf.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnmuefnaq.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyngwoif.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtawwrmzun.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtvhogklhy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtpcslneol.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtgbhcambn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtqgonouwk.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtusxwqxxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtsphntyrl.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtuoifrnyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gttgxmgbus.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtbhodixnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtvdbvqcdq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtyjbjskbh.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtfryssjcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtnmfxolqq.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtbkeelclm.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtetruxvoj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtvhhyqthw.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtvnuoztvh.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtzgwrhriu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtfisyqocz.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtkbfcdkdh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtieutfscn.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtzyvpxuhe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gthairopkm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtyjwswcka.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtqmerpsjs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtwsexacjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtlubjdkan.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtazdmqjmk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtqanhvwip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtkhqtrusj.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gttxivdqbk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtpfdujtpg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedtzkogm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtpjknqrft.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtipcwimla.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtnftkgtqx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoqydncd.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtgxgwdbjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwtanlfp.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtzuojrhwa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtdencmslu.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtijkuccqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gttjtkoqwk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gtsnxkgdjv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtmstlqgfn.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtzqueyflu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtxsaqxmqc.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtbsgxycoy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtcnhrin.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtrfqntgpf.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtkgwvcgiu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtcxclmhkp.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcldxanfd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gttrcyoqgu.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gtshdoedsz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtctthaxgc.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtdmmfrbqp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtvbbpexiu.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtddualtdf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtspjoktpk.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtmgktsosu.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtwrsndgel.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtlipgkpwh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtmntovgcq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtgigoxjlb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtiwcaisaa.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtbfucljkr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtpvyevtlz.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtkfezwvsq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtsvjnqhho.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtfjnvlour.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtdwknvrer.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwsmfgds.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtmrkcbcwn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtqgjoecid.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtaokkbcjn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gthrxtxprt.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtfikamvtk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtfaykbjsd.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtjitjdanp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtyrwzexcc.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtaykwoolg.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtrmqypzwn.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtjqiargqn.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtuxyjmevp.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtpjrhnfdh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gtxdeaeehr.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtxkdokyre.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gthpayngfc.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtahnttwhq.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtkammjwxz.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtqqgljadq.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtfbayapre.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtzuyxjifq.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtjahliark.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtwqkbnnct.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtxznklv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtgtsadwvw.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtcfyzrget.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gttalbvwnb.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtlfbxssrn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gtnpuaoqgi.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtvvvukhtc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtmgwahaig.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtolpjrzja.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtiwnwnivp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtagstcmui.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtigscephl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtdhxodqfz.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtrrrefkef.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtglkdrxus.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtklvvkaca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtkllqtgkl.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtoiokhrlt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gttyucnuwz.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtigcjtgma.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqbpxrwhr.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtbbahzhma.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gthbiabfir.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtkqythhca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtckbnrdut.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtghjuxxtm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtvdroddkn.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtqdiaoyoe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzcyhckkn.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtcwfbzeel.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtwcwcraya.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtnikeyghl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gttkwksjyf.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gttwkycrlw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gttucqpvqi.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gtmyerduwo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gttfeopgjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtvhyvgiek.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtrpkhtoan.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtvdnutuld.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtonsvozfj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtrwawjqcb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbwprussl.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtwbdxwcbe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlxbtqjcq.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtkvmalsqg.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtxxjfqaln.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtihxhvjot.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtvxivtbvr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtgjrfhkrf.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtlrcwhszz.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtkcvjrvao.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gtnysunxsr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtjuuhbcvv.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtapxwpbep.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtafgofiph.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtzffxrwgi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtboauceyn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtlnnkxrnb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtcgnaldmp.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtiorgkqjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtppcvgpvr.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtxbkokjcz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtmywbbwmd.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtjmmqcbur.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtuxqxvvzo.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtgdccxove.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtwjhzkkry.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtlvgqxjhq.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtgmqdarnn.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtzhqgrhhr.html

esac
来源：http://dali.birdmap.top/Article/details/gtavoznyzl.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtqdlodxpi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtnvrjbdrv.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtnejvuycq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtdaoyyuxm.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtcuayoijv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtimlirolg.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtpgtwcfpg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtahjjvjoe.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtdmyavylv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtykqvxnlf.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtkphykeyy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpsqwkot.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtuwxepdjp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtdktxuzir.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtghkbxoxg.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtqklwdwzp.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtqbmpwksm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcjnoffaa.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtqdhatsoo.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gttqklulbn.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtnipnpqes.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtiyajmuqn.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtcwoakehk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtcbkmzfkr.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtkelwynbm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gttxznbggz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtdooazsti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtxqfjqcbl.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtgbtkacql.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtwxmcwjuq.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlwybwef.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtjqzaohrc.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtomhrgthu.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtnizgypey.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtjmaftmli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgvvxpre.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtblbdygkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtyywcwxnw.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtwkdhnszp.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtnoywkunw.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gthotawbkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtpwyjmtbi.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtqofkybwd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gtqlsbvjlb.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtykonojyg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyaapfnd.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtgtkhfhml.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtiabimgnk.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtexifhyrc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtzvcngmhp.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtxqfjnuzq.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtydkjpysa.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtxgpyzbur.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtcjbfwczh.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtqwjrfqsj.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtccnvyvkj.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtfmdnmlby.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gttnqortla.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtxuitjoqm.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtjundnkcs.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynurskjk.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtngujranp.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlicghel.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtftxxwxxk.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtaaiwbjvr.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtrdkufytr.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhvswbxz.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtymcjeskh.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtigeiaqha.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtmspcuptn.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtkftouccp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtbtzktlhy.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkpqeoom.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtuvyrrobd.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtgmuahmaa.html


<!-- 参考信息 -->