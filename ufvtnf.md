代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2hfjwfujf.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkqrwzey.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gt2ggsveywz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gt2nyaszcmn.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2yakwudks.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2lngacdun.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gt2bnjghpjw.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gt2bkqzyewv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2xriewqdj.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2qaenotjz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gt2jnoaiwad.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gt2zbqgbivd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2rmfubkyi.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gt2jzhkwnmf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gt2fpqqdjmi.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2bdlzlbdr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2erlspbfg.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2wsiqutrf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2bgcgjkvp.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gt2sjjppdzc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nskfgnuj.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gt2remrsarv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzoxypqc.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2xqxyabtl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gt2uiagetzp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2zbokxvyt.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2lmvghrvc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2hyyjqnks.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2hvuggwpc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2osragzbp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gt2elpjhwgo.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2bmfrdykd.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2wvxcpnqd.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gt2hxtaicfp.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2tpltpnjq.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gt2pibcsrvz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gt2rzolaegs.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnyumyge.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhzfyuoc.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gt2urhdlqzj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nifbxppl.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gt2trudbgqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2bqtkfjxx.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gt2hhqajqjf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gt2emwvdvrk.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gt2huinahbt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gt2brzqxwqg.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2aziuhehq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2jdftnzyl.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2qtkewgau.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2bkbopzkq.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2nqbktsri.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gt2apevnmca.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gt2yzdepzwn.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2hybmgbjr.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gt2jtrchzdf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lecnecpl.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gt2grhzkkbw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2drwuwjdv.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2lmgmpzzn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wqlgdmqj.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2uzqdgjrq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2zfkalcqo.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2efiqejfd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oojhpijx.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2pixeeztu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2ukxedvnh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gt2lqyozkjd.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gt2npazqyym.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2idcikryr.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gt2exlkjqvy.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2skkbieoq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gt2tvemfkgl.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gt2ofdpnojz.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2xtllftfu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2vifpgfix.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gt2ppjvbsbx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qypbslxk.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gt2ywpswhmc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gt2pmpbsluf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gt2aljpefrm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gt2fhyonzdg.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2nhdnygvk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xowdyzhz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2xajjfqac.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2bnilpoqi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2kjdvarrq.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2mfnkncfk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hptbsgmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gt2nwvilhib.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2wfzpjive.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2qsftarka.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2jbydfnxx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2xhyfnmjo.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmaqihox.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2tapjytxr.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gt2ejorkwhe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2wabougyc.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gt2whejnwwp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2meeocifp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gt2hgvrjdwc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2jioydnua.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gt2cnarokcn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gt2krwgaeeo.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2ugvyetjv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2esfssall.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gt2unzjjtsy.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2etatjuol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2zklmrktl.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gt2ylwjbeud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2vjtwtrig.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2bjzmvlje.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gt2tjtqevpu.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2kamljpat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2butntwwp.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gt2waoelzee.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2kjyptxsd.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2rspvmiqo.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2ddywybkl.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2avfxglqc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2jarwhmie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2frcastiq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iykbnzud.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwxobyvh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2rdvgjqxj.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2bixgrljh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2azsprmob.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpdnfrao.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlhsale.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gt2nnsdfkez.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gt2ckhbazwn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2xneztnkv.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2ndtatzrn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2yjneqmmg.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gt2givyrxbr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2aedhztjc.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpuasobc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2tohxknnp.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gt2fhcxqogx.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2smnwbadk.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2qvsyfyyq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vootopxk.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2otzjezaa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2hozzhxgd.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gt2ikkvydxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2kukcmoar.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfepckco.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2npoqedzh.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2nsweisey.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2lvoyrsos.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufueplbj.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2lcqsbgdf.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gt2pbsdeppd.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gt2jpdgvgix.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2fcucbkey.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyuthqfb.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2qpyjxriv.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2zfcevcyc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2uxjbtrzk.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwyabrej.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2nvfypoor.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2gtbmcuft.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2onbobmkm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gt2wpdtgavs.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2iyhpennb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2povnoxyf.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztuxuxgi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2spbzkdov.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2otkkpobd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gt2gcmbgsll.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2gekgscyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2rmhttjea.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2eazhavwr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2vhvoyixn.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2elvkqqru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2grdokcxd.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2cuawgret.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2lgxoivkn.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2pumvujgt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2josdfowq.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gt2sbniqxlx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ltlvprjv.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gt2rvqjuaph.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydtelyvp.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2byynqicj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gt2rlcfkrcy.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gt2pjuyhcjh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gt2nspkpksn.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2ltaooeor.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gt2iztjhpkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2wljrretk.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2mgunzycf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2uffqumlz.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxyqrhrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2xtumlbpy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hdveyvdx.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2iliiaxfy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2iiozybvg.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gt2trxuggvh.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfdxenpn.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxvehqsb.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gt2dlockbzh.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2cisjbqbg.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gt2clyayrvd.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2xziylemq.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dockqwqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2yvzvvozf.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gt2ogsxdjuz.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gt2nqvjdohw.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2lyusugpa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2shqiibde.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ofygqdhg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gt2okbprfqc.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2xtrbmdnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2inxusifh.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2gpawfohr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gt2usbklpwi.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2jddjhokp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2bstuwjop.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2xkkexzcq.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2inhgacvp.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2xskjkbcl.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2znioggxq.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2vvxkbxwx.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2nabjyazy.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2qsesyscv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gt2ocyeabto.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2xharmxhu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2dsxdmkzr.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gt2uosvbtve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2wmphsaic.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2cgfkhduh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gt2empwnvzv.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2rowrctbz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2pbqtvuod.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abtuxcws.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gt2nzikzfas.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gt2zxvqkqai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2dchxvnmz.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2nubwvgmk.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2upnwekgo.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2krdnzoaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2gkrfhzzf.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2jllwoqbc.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2toqztpxj.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2mzghmrbt.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2dazewnqv.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2gglukkim.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2wmpauera.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2ppntxnke.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gt2fxfuhgiz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2fqlsxbjk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2vgwlxopi.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2jbajwtji.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2lgtdxeso.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gt2pvalsxns.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gt2uzmoiodz.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gt2kjlpgwsk.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2xzbebenn.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2jqaojcui.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2fsvjmccj.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mczibbuc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gt2akkbjone.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2gtjlgjma.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gt2cbkfnsuo.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2bgualehj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2axiqkzgn.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gt2xgnmzrjs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gt2jvenbqdc.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2rsimqexx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwchnjej.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2vhtpqozy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcmwfloa.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2wprdtmyb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2rspvuekg.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2pcsjyknz.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2svodcqcg.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kaisbark.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gt2sskklkpl.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gt2awzualay.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2asigrkgt.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2ynwailyv.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfzcoinx.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2inlvwagu.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2phcyrfyj.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlggicdy.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gt2anetmrnj.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gt2wbrdnsnp.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2ndfteuds.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gt2salmebzz.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2cfhamkkw.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2iopzmaax.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2bvyiavqi.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2agtecguo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gt2nwdccwtt.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrjrznzw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2mnsiztfr.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2fjviehle.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2tfkqwhlp.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjqckhfi.html


<!-- 参考信息 -->