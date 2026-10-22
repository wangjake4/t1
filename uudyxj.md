代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2csbqospp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2larhkgsu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2wjpbefpt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxpcrhbe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymuplted.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gt2rgadyyjp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2isoblztq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2bebotyla.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hnkftbwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gt2vvkuzqbg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nfhrhukc.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gt2fvawrymm.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gt2mshkcgxn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2hjtpwyfq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2otnanpvw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gt2uhnwieno.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gt2apcybqxq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqgdnjb.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2qywizunf.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crgosvmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2anrzknon.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnilrtdw.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gt2hpqmkwmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gt2mxdohqhz.html

);
来源：http://dali.wangdashe.top/Article/details/gt2vkwciwnf.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gt2tfsvpiqu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2xjlkzpcw.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2mnblbwtj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fzhhl.top/Article/details/gt2ifyfzmvq.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2agzfswie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2uwjwawmx.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gt2tppsrljr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gt2enseaxwk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2urbtckzw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gt2zzsnhjsv.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2bcwagwzd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2ghuvtwsq.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gt2wyuaahci.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2flsdgrhu.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2vmheyqqc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2yjkwrfwo.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcuvuwaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2sixasbhh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gt2zpxloihn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gt2ahrehorl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gt2dumgopah.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gt2ztfvvwal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2zadadeya.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2ifxlhadp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2hvuzbhkj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2tgkgkxhx.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gt2jwjumfnl.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2gldcidnr.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2zvqpgfiw.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2dhwkvoqe.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2lvgrhdjj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2dhdhaier.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2utoopzrc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2henvzpuq.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2yncwaanp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gt2jmazmcwx.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gt2dozgvetn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2dmeuxtas.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gt2befqrplu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2cqcoizcm.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2tixhepoo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2nifqeumg.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gt2qniyuupd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gt2haafbyae.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2lgfyqdjv.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ofrjmbgk.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjblzljw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2ycnsxzyw.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2vmcmoudr.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2aamujuvl.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gt2yfcjykfk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ljffyfxo.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2laagmrme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2begsjycv.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2anodhpvr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfasdyli.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrsfizx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2oculodzk.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2tavfovhi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ziglzcxn.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2fjtclabr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2faugccsp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gt2jaigreqv.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2tawnfjxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gt2ubvtdkrz.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2unsfmcwc.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gt2iihavmim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2rcnsjsxf.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gt2eupxbimk.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2kbccinzh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2nmgoaawz.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gt2ycprqdyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2ukjkkqjq.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2xsytgopf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gt2beekpmlm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gt2qqxfnvlc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2dswwxmyq.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2seeuaqik.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2jcscyxkp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gt2arysxfvk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gt2fdnzuhir.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2smvbrjpk.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2ahoxuxhg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2ydolrske.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gt2covucvee.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2cppesvjp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjazayab.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2anqtgqrs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2stcvbznz.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gt2xaazwdbv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2sqbntbkm.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gt2vrsxovnn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2mnrvdpfl.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2fleeqwzt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2cvrelyjx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsosmyul.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2dtsbnqcc.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2bfsxkeqt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gt2lqsoumsi.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gt2rvdpvgid.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gt2bbtbxafy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujnnbezy.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2xylrairc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2xaundmol.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldvmtvtc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpjcpsqv.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2wleizboa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2ivdgrdng.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2tpyvhstg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2rkilcmmm.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2ppstixso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2zygdophu.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gt2yejdbrnc.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2hcezbvwp.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2emiahnkx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2kyjohset.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gt2kvgavwvb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2fgjpjjci.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gt2keyfoxou.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2afrfjwew.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efnhsimm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2sighmzsu.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2qyuoqlcf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2revatpkl.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gt2lqftymbk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gt2dillqmpa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2weonzxbl.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gt2stkuwevx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2abggzakk.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gt2mvtbqldz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2ljboooru.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gt2ccfhqpcb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2vktrsupe.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujszorcc.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gt2mcrdphkn.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2staqohew.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gt2afnvzlgn.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gt2dxhqzuyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2ephzwfrc.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gt2cmppkqti.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzksaydl.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gt2xewrnirt.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gt2ugebdrno.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2fodvxuye.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gt2khxkdngb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gt2msxqlomh.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gt2zaqkzqvz.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2vaaibdqm.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2supxfkfr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2nrcvajyv.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqwtvkxa.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2zygtectn.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gt2gbibzhux.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2dwbvddxi.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2bagrjsur.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gt2urofbvfp.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2stvmclmz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2qsbiiagr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gt2tbnusgym.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2vwyeqhra.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oextnckv.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2wqgxecpt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gt2dlmxhbxf.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2mgaosgjg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gt2qfggyona.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2htejdkeu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gt2mkpbbcau.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gt2adfulsdq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrlhvzca.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnyvcojd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2apekvefp.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2lpvskvsh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erqtnxih.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2bkopmvja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2fpvucvyo.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmnljvpc.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxybzkaf.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2cmwajwes.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2opmqofuf.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gt2nnvuctwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2woqzsapo.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzldcmdq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gt2pqxacdhd.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2ucafywho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gt2ihcanfrn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2iqdwfxrr.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voztixlq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2wyskdkbj.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gt2vdgjpcpo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2qdupunsb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2arnvvram.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gt2dndpabed.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2imlinzwl.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2gbgjkwsz.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2mvrcalgg.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2lktzuept.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzrgrscn.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2idayrfya.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2uljjhjif.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2xygbjmrc.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gt2yqnfytfu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2ddwjiwoa.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gt2pkyazfsr.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gt2nllifrtp.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2qcykbjhp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orpkzdmz.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2nllleoja.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2pwugqqly.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gt2xxrtgnne.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diinmiqo.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2ediygbrb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2cdhjqcmk.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2gunsobjj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2gqaqstsu.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gt2bjnoedlq.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2hafpoltl.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbfmmteq.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfbahuhp.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2vwyyeodu.html

esac
来源：http://dali.sysykeji.top/Article/details/gt2jtjzdnfq.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ackihofg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2axevwpok.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kywmhyxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2tofnfwxp.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gt2dulttbtx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2ppugimhw.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2lydqfcet.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2gmoyfntp.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2egzrdwth.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2arabqzfv.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gt2mcndwmnd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2jcdivgji.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gt2gncbvpgn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbrzbypx.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2wkxxqviz.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2ynwupphd.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2vjetahar.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2ujkdjqku.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2avjcxkfa.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmlwvgtu.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2mlbztsuc.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2zjhdioof.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2hsaxcvlt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2psgzovfi.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2jcndyzjv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gt2emfbmohr.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2dhiuhjle.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2dasjsbom.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snqdkgkq.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2ishjurhr.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2ahfaqyic.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvevcror.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2fauglzhr.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebyedukw.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2uiudoejv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2gfeiokhf.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gt2akqwcvil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gt2quemhgzy.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2nzuhdsav.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2vlkkgjuc.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2uphagxvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2cnbcmtmo.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2vmqlrkog.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbnilbfa.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhbyfgki.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2yxslpwzp.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2acoxxdor.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvwwrgp.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gt2snkacnow.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2rtdasorm.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2ousgzhlk.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2zdisqbot.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2zodnlwje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2zpwyqeca.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2wkipjibz.html


<!-- 参考信息 -->