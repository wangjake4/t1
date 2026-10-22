代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtytaqzgya.html

);
来源：http://dali.snrcjt.cn/Article/details/gtszwnujqg.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtenoirdmk.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtyudbfhpv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtgvvhkdtv.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtqmggtkfl.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtuqeivjeo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtywlqncfa.html

);
来源：http://dali.nwbrower.top/Article/details/gtyrxoeixc.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgripycqu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtmdbupldc.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtuwlfcucy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtacesiwub.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtjrkrusuf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtgjphcvnj.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtoveqszof.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtcrrmabpq.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtgomnuuap.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtbtiruubk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtcfcdasqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtqnznsmbp.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtvezxothb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtyculrrbz.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtuhkzrdbz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtloajykrd.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtulwvpxqe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtknfypodr.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtlozdljsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtcqeoqopf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gthvcgwncx.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtcdsbximu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtkqjmghya.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtdneueoih.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtebgciiqj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtpgllkraq.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqnyagbf.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gteglsgomm.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtudolheer.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtleesrqal.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtxiobuzgw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtserhsypd.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtjyliqyzb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtvdtrityq.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtstkpsveq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtbrywrzmk.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtoxztyjxh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtudwgwjam.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtuxhcakif.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtyqsliyzn.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtmhpvxvum.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtnrwwcbtq.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtsygkxpam.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtcdrpwrir.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gteprexupd.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtssltbbta.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtemaoqopi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtdxibqwoo.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtppcafabd.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtmahawmhu.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcfkhvbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxyesxggl.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtoedxmtse.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtbqylvkst.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtszowgxtv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjyfhkfpg.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtovpidnlv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtxgomofst.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtqurnmiqo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtatgdozxp.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtuejhujcr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtwlmbvmrt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtonocjvye.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gttzidbubu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtfozlaefa.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtwvopqllw.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtsfgolkby.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxlpjbbu.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gtbzywabzf.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrmvtnzz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmfhswspk.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtmeubsgas.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgxvnvcl.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtjojmgihf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtlimbdrvs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtuajlaniz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtouejftyb.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtmarlfrss.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtajdogxvi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtocumumva.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtsqvddllu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtrzojjdxp.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtidetxduz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtufkgxepy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtvajtuwsm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbpirkxp.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvmujetq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gtutqtlnti.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gtmjclplzx.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtevctgpkg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtrttrpiir.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtyjvgpdyx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtwmbtqxzw.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlnjzvrtp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtsacflbha.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtnwnvmchz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtvbfbkrwg.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtijabwbyg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtpnyjulog.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtesiuyvwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtagpptkrc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtkelfzquf.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtyrpjfyhm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtlbavbruy.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtxprydsgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvjlioqf.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtxekcncsi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gthotfdacb.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtkakmtojy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtkmptyplf.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtajuucvtv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtygkeugau.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtwrenybqo.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtbynpfxkt.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtxmddkewu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gttzrkhmxb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyslyffui.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gttzsoufrx.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrrjnmun.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjvnnuiha.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtaydcmmvo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtsmzihftq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gttmqclmax.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtdtatrqin.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtsvlnefdf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtbbmhhlyh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtyjcqxthj.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtueesdxrs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtxpanoldv.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtejfcsnkt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtzvaukgea.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gtmndyvqbd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwixwlri.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtcvjspbsk.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtiwbpqbww.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtjyimelcg.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtgufcdgcd.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtfoxnuejg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtkuiouhje.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtxpdasffi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtuvmrecnb.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtdufdefjq.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtelndbwpg.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtnkgyfyid.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpezadjh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtyypunuph.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibhoscqu.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtycdvwcix.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtvnqsjajb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtjekvcfji.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtpxjvsjhd.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtlgnxowqi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtirozknzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtsgxcmlop.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtsoxqvdgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtkqqedxtf.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtzyvgodce.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gthssxnbyh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdyimzcg.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtafnzllrw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtvagubetz.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlmsfzwt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtkvnhiqfd.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtsbhfytfz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtpdxmarfx.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtilaupbxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtcrosoikq.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gthwpungnn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtotxhlgol.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtjatkquoe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtpbhblhlf.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gtsygkqaqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtseaghkes.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtpfrhxfwj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtkeoqowsw.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtzhxtbotc.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxtznmtam.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtbgrccgaj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtccykrqwe.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtdstmsxtj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtlkzqsqej.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtskmizdnh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtuiuaeqdy.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtiogdqrcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtpwovyrpc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gteevenqnq.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gteyctgsfq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtocaaxlna.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtoaygeoci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gticwfjtcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtczclggva.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gteoxwphgc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnnzaiuzs.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtvbcoogfa.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtaxnsukas.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gtjmyvbacm.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtpbfakzaj.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtmbwmbvlb.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpawtccm.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtsqkdppso.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtcezkvysx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtqsspnast.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtsjqtykio.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtpjawzafb.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtdplorjmu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtxldlxhlt.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtzkwsbwzz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtsjugsvuy.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtvdtlgmxp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtezgwhyxt.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtvyjlqpeb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtjqwbppey.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gttufbogtg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtnevauncu.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngbwvvdy.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtwjvzclxn.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtmjcjjyor.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtrwpfqptu.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtmtlnthgv.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtfgkchvqg.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtmpkjcvrg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gttqgbcrab.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtwnuqcnqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtxvtcaqlt.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtrlkpvvwt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtxlrgyjjv.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtehnngzkc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtkydiqgdo.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtiaadcivg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtbgrzdaov.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtrcfmnfon.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtgcoulhxv.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtlxbiqtnj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtazyvdciw.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbfsigrv.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtjlqzewyd.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtgpehqxzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtrgtmbduc.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtrwdetrnx.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtxljpymmm.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtxdyqcudz.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtrnsgzqaw.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtnoblhxiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtktiisrgq.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtnevkbzid.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtiivguxdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtpffgvuqr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtejdgdogh.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtrxyxvmku.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtlotpqqgk.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtpcepccpc.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gtgdjtucwc.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtfgvycrfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtuduuqhdy.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtpnfuuyrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtbvstinft.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtplbvcyot.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikxldiqc.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtnjukfjhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtaqligztj.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gteemtjbmh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxmyvrrfj.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtfntswopo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtegrisfcs.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtbyoyiovl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtpdpfpacx.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtzetcmzbg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsyotwnf.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtvlbwnicn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtmxjltmfi.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtoczmwcrj.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhulgoih.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtnekptzdk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtiabmxhtz.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtvhoafkwv.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtyudxqngn.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtbqhpvalk.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtdttkrpmr.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtybdzuekt.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtbjyiwscy.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtnfscwlee.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtnxibgjrg.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtniawaemj.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtccuscrvf.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtzyuwortn.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtyavjnhyj.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtfdfjtrwq.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtfstqxfei.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtgfkxkefz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtzinkdfxc.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gttcczdxcr.html


<!-- 参考信息 -->