代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2sqeccuwp.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2btrvbogw.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2onnhxipz.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gt2gascqjvk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2lhbripnm.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2ejrjxsgf.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2aexqldjr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2ohznusih.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2yiwxltqj.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2bkjnpjwc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2vivjatez.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gt2qpbvymhx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gt2ymussjvz.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2ogjaeqga.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2qsinmpzq.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gt2qodmptbk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gt2vqfrksaf.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2ottpmyno.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2tpcitzut.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2zqolmbee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbjfaurk.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gt2typzpmqm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2rymanctl.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2xskflycr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2unkmzjyy.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2ggqfkqfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2mzvgstdw.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qycjpeme.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gt2atcijjyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2dditcgxv.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2njwlrzyz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2rvlaehyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2mlgcbjsj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2wouhwkjz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2cpnbcvec.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2rbonwwtg.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2mchurcel.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2oguwhbpt.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2vmaismwz.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gt2aacyzpot.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2damylzux.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2crzhgdgi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsdwwast.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2tgxjlhpn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2ewpiifqy.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gt2hmnutrxc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frpkgjvh.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2shhnyobi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gt2olfzwfyx.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gt2ubksinkk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2wfrpyxui.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2immjpegb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2byudcyqi.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2lytjjehb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2jdznvhbc.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gt2rixllcwb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gt2hlbtworp.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2rarnydqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2tybqjalx.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2fxvvbqff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2jycjtsbh.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gt2vcruello.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmwdbvzo.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2kmwrvymt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ntcnvvlt.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gt2dwuzmiin.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2rjlwbnro.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2gmnjseas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gt2dfreoqnc.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zbofvqvv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otvroefi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coerztae.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2dnmrnmjf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gt2ejrcdfpx.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gt2yxpdulgu.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gt2awglulxv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2sjsghjtb.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gt2otdeozsy.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gt2sjjhtkgk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acivcfhd.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2ddqqplpx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2eefekloe.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2ldndslfd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2hbkrmrdj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gt2ywftjpao.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2espycxrt.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gt2pfeaoujb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2qltkklbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2giwfeygu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2unjdejdp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gt2jkfbiqta.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2eyhnwpzo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gt2nuohnpzb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2ppcjygah.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gt2pfljqtpu.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2qzxsncen.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2qksewbzz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2txqecxdd.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsbuxknw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2mavnqxzz.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2xhbmorxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2galfdzog.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2saozjtrb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2lmiurvlh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gt2ujzmprcc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aspxdhte.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2tolkrfrh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfgtmdrw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ljmnnqay.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiuezjdg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yorovsxh.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2vqpmlbfz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2rsswpfup.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2xnsjbxfi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2lhxkfivd.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2chgmozpe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2icqjjvzr.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gt2lisluwsd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2dsshtpkb.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2veztqlpk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2eudifcfh.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2rygsscvw.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2ywnrvbxg.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2ptzgsgol.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2wasyemny.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2kfpcgbfn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2cifzpqeg.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gt2crurfiee.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2igfobiyg.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gt2boufpwdy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2kzoeswbb.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2wngvolgk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2ckofzvbp.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkxjjovf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2lrymlbju.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ydgoyziy.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gt2ueowylmt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2peqejlyf.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gt2blznfjex.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2vdrpbrgu.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxrmjogy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzzeohgo.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2qeyzdemw.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gt2zuiaamrt.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2fjtelfyc.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gt2auglrlyp.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2vzwdewad.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2wtnnmnlk.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gt2nsrbnbhq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gt2caohtoqr.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2vknhsipl.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2nrppelaq.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gt2kziljqps.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rblspcur.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2xokwrdhy.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gt2vbwgcuvl.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gt2ujnlbysl.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktiilgzz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2bjtvgizl.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xppgocqn.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2mbhqjjki.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gt2suuwwxrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2mmmutshx.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gt2rkfzzrvy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2okiydelj.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2lzibqchn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qhxqpaae.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gt2alhjrsux.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrskxzx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gt2sxbfvjgj.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gt2fpxjuuib.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqlbeazl.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2grlkzmgw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gt2dnqaldbj.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gt2jekkhqpy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2rindrudy.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2xbayqeso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2xbxwvgis.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2ubxrdpmi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2tqtsimts.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gt2nhehrpgr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2vruwzucx.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2qdvbkuja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ugiamvtu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoxhdag.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2cdnrblbe.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2msndhdfk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2ookdeoie.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gt2hkjmapdq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tianlin.xyz/Article/details/gt2eieyxiif.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gt2ogyrokdu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gt2bcouljqg.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2iewtufmd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gt2lcivgmor.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2cpxbasiw.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2lvslrmgn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztlxhnjv.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2znbwszak.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gt2louldlge.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xiccbyuh.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2dtyfvaei.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cygyyqbw.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2rscdysih.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gt2rsycprkx.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2yxduhudx.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gt2gycjmptm.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2pusknsai.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gt2xefqfrzc.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gt2psrmpupg.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gt2lpxiaqts.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2izigfvtj.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2nlbvnnqi.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gt2sqgurbbq.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gt2koltuhgc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2bvundugc.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2ldgxgzei.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2swsehxgl.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2ztukxlfn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2ocdhqoeq.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2yuphlyei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzejthby.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2xmyodorq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2ogpaomxz.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2ylkkqwia.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2gxrfkuhp.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2cucragtm.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2jogcmsks.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2zcbhmkos.html

esac
来源：http://dali.hammf.cn/Article/details/gt2ermfhoac.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2rlybhqxm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gt2hwbphibi.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zprhjlxs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2gmvonmwn.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2fxjyokyr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2vrulisgn.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2hxxmayuk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gt2xcgeajyi.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2zhdzzocp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2zsassewl.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gt2podbxiqf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gt2iqfilzdl.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wddgfsjw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2jadchddh.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2nareislk.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2gbqkkakx.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2csycanbr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2zpmgzdyz.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2lkckmqhx.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qadyaaxm.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2japoyemc.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2vizatybn.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2gksbsmph.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2syhggusu.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2bnqyxyzs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gt2ebcqcezp.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2iucykynf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gt2wizuzwpz.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gt2abvubkvo.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2zggjfnxk.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gt2jzukuxko.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2wcxxqdxt.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gt2zlzoulcx.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2ouislebb.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryvrywxa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edhvhxcw.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzlfcqnf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlsytwhy.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gt2ezrfxedc.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2xmqkjxql.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2tuyyqutp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2fpfanvor.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gt2yustlfcu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gt2pyucizyr.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2awvotqur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhsgumph.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gt2nuqjhikb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2nswkwlsr.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2vlcetoqg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2nnuzzdpr.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2oqqifage.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqdomivh.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2cbpmgesb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2gloeydcl.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gt2mkainvfe.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2xsfneodo.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2azvxovjx.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayhzebxw.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2kqvwgoff.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2fcilssjp.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2xpwzjcud.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2xmckxywi.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2qxjyotiw.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2xfddfkfp.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycurucxo.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2dxmnlico.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2fqedsutk.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gt2woxyeipz.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2klmidsbk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gt2ybppzzju.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2imoevjdy.html


<!-- 参考信息 -->