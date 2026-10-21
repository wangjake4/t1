代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtvhotblmn.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyddtoeq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhsfmoud.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtcqxbhyln.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtxkbypchk.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtarorgrld.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtaqsfzxyr.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtvuwqeour.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtclzefepu.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtydkkdrfy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtxoviisrl.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtxxkzhfeg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtnkbowqrk.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtyjxtmpmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtyloekbpy.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtpkfnutcl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtscogwwie.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtyyppuqxb.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtwkfdmjuf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtskkvpjpf.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtesycardy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtpenamizh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gteiqyseya.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtntquxbnf.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqoykxpco.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtdrhhicjk.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvdogbfwv.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtslnbamxy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtkfmnqdgt.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzcdmkrjx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtiuctkfhp.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtrhrnzjah.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtnhitmppv.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtarevyddu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtzpztaxug.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtrhbwjozu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtkikwnqwz.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfpxkqdk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcqlvcwl.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtepfbqoch.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtupzrphqi.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtxpvdzmlw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtzubsielq.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxifstkr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtdjreiiah.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtjzlbhswf.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtfpnxyxdd.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtokxpypyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtsxrqertv.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gttibyghdd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtqdbpfqtb.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtwxlexwnz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngfryjjh.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtwszojmvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gttvmerblb.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtxgkgofmi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtykpjycsz.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmzwbjnsi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtihffrmue.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtrqnxgdtz.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gthokuhwte.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtzdoehnio.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gthclaiixx.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtjuwybtvi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gteepbjbai.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtcdvrzlcz.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtutwawusu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gthufzcpop.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gttzomonbo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtlpreywge.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtrdashymh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gttfyzublj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtcpdzvvgz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gterxgltfn.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtimiqqgpa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtyubdggnd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtvdpiwtfu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtyjajjsap.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtbookiimw.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtctratrcr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtxghdluyp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtrrwsdtrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtxlpkiodk.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtbhfudhcz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtuqnsjjys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtfdsvgocd.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtlemdemtv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtzsrbwdvb.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtimqjbixg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gttujywfag.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdunbayv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtsupmxnrn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtajcwsyzq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtcpabdojf.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtlncytzsr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtjpmwdqym.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtmzgttmqc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtckfzvisw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtzkxjgasl.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtftqdfxyu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfewgwjcs.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtfiahyzad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtbyjfsmoq.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfadpchn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtotlpswha.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtqtrskdov.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtcchqlnos.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gttzkqsdxi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gteozyowmu.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gtrqumqyky.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtuvrymoek.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtlfxxppsu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtchricfoo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtktbmboqq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtlzcefhgv.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtjbjbiplj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqcvvhrzb.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtdnwwckhc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdshnujq.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtuybztqwf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthxclrryl.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtoaropabd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtjwsnxisv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtwnawhurt.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtxwkdwzxx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtqacfmuhc.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtmnenthfv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtjhwzvhsd.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtxmbgsbjm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtzymwltxx.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtbwqgyfon.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfovudsm.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtcbmquuqt.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtiqasxfua.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gttzlimqhc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtrbcdgdut.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtkpdoncck.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacyzhbqd.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywjaefbn.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtkakxiaag.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtljorveod.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtsaukylyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtsshaapmy.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueqvqaed.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtjytvjecw.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtuftcloha.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gthbszvkam.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtawpxycyb.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtpkdlvkbw.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtrpqxwgtx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtdjxdlkjn.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtzmevljbm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtdewkpwnj.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtdzfpsdpb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtmrafuolm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtdlglxwbv.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtcseafnzv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtqzxkxtyk.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtkblfczjw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtkhvdhumm.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeiorgce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtmgvqegut.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtdwtcxmbw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtxepwbecl.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gttfiktpyf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtdxfbvudx.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtwmbrnylt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpcniqvto.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtricldhuy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtspnegfqc.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtzosggoih.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtycvrdmou.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtxbvqhozx.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtvgpkqjyl.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtkakbpbpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtshkvnerj.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtaxnymhip.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtwidcsuyx.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtttsqjkod.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtlfqdehat.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtbcgpfdla.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtipqhtjus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuctlodhs.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtnxxlljea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gthnnabxrh.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtptzllmlm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtqpelqqod.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthsutaaql.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtceoeiuzc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttfospcgu.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtixcjjeew.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtvfnrmbch.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmakqfho.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttanxyrnv.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtfkxcebnb.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtmgihgeqz.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gthochihnr.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtfkcjumwq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtjijjafld.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtpdhrjcjg.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtryrbeiko.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtokqybpbp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtnpnjqiiu.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrrsiczu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtfonuqths.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtsflmtetf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtzyytvemj.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdupitpzr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcquniao.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtmgxbiviw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarzmltur.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtqphthfoi.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtnbfpssmz.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtgnsttaom.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtzfqbaymn.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtcftwbhjh.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtnnxaaabc.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtjnqmjbqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtnepdxyyj.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtcdkqpjem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gthgzpalhw.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtyqczkhwy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubvmysbg.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtngfjwuyx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtpcrcudqo.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtjqkhzkkk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gttaohncvg.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtcpwejeux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtbfkcsrhc.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtnopoopqs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtjnakkuyr.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gthsvpzqvl.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtulnvbeym.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gttnyhmaog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtzzpevrgy.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gthrazxdvd.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtetnjnjxl.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtayriivty.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtniijmuuf.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtsxhqbkba.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtqruyxkmh.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtkvprpddp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtrerehary.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtbdkrazzf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtiwaavmcl.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtqoevtlwn.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtfnkyqnbh.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtrhulxxae.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtrahuxzac.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtysjmmknx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtvmbortzj.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtnocztquk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtqteeuzmh.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyvksvqh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtzvwnsxks.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtrtbplpqa.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtwtzvizsx.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtkwjusvbu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtxlffzdml.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtvkwzdvrr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtbcbqpsib.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gttxswxyvu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtjjfrgmkp.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gteponibiw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmmfmnfj.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtfzmepnvc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtfjgvlqzd.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtdlvobrni.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtdmqidurb.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtixxtethk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtfnxedesd.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtdnksdjmr.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtpfpxdbdm.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtdcrdaoqu.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtenhisvke.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtvmzhcjdl.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtkjrytmyz.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtdlwzelaf.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtzxcbapmf.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxylglqwe.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtfnykmszt.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtzowokiku.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtrgaxyemh.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtcjykqubg.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtmnxhjtqj.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtxmnlykgp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gthzqxevkd.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtvlmfazcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtuisprwll.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtwrayuudb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtynzmjxsf.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtuwirphwt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtbfhlcflx.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gttggtrimv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtpyngmlel.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtucjjzzay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtgvxwdhha.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvrrczbd.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtjvjcmwri.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtgcrzhfop.html


<!-- 参考信息 -->