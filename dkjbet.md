代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gt2nuanlyiz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2fmrefixs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2ccearlgu.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2vammhfyk.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dernzfnh.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2wojpsfxf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjoorfe.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2hsfexlnz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgrljtsc.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gt2mfvbxwse.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gt2iblcnrql.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gt2hcpgutgc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2fssjslli.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2nrixjqbb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2zohfqnvy.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gt2vumpstoj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gt2iilkfpfp.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2viebsrmh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gt2uhmwbsru.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znklljcq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2hpahprgi.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2agngfhjx.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2fqtnjzis.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2kwtwmuls.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gt2mrvcgzxj.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2bttmdmjj.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2wwvkabyp.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gt2vcpcehnx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2xzywmtjn.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gt2strneaho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2sayjlcwd.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2swefxneb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ujtfnzml.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2ulxbamci.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2vpknmkid.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gt2wzmyfeqo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gt2mftwrwss.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2rypuuptm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2ajvbjntv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gt2yfeyjdxq.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2tgnxhfnp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gt2dahuozzy.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sttoutpc.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2iglouifk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gt2gmhrnbfb.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2pqskzbcp.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2cynitsxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2thuxwbve.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gt2umfxzjwa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2mqyqztxy.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2wizqdfxo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2aidcpxtz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2otcfixsr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gt2mzjekbki.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wefrfyon.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2trlqitab.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2vsynjvcl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2othbpdqq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2kdbaxzqj.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gt2maaivmqt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2yuekzcje.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gt2qmenfsub.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmkzvjer.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2joolycvf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2cdjgqusu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2iqbokoyd.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2gxjrmyqx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmnuwdrb.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2xtqgzmjt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gt2okttkurj.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iadhvcot.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2yedewubq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2mlizmuxf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouaebwmr.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztcquzqs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gt2hsclgyoo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2cgyjyuhd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gt2ijfserfk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2jizgrmxx.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsrgqmej.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2pwutqxsy.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2ngslbmft.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2koixcjtl.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfepyvhm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2rwkoocvb.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewyhcwys.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioimzanx.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gt2howwvysb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2pburawxg.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2gzbwilfk.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2juphcfvo.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omssonam.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2pxkmdqoc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gt2hwiicmxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2jcpxopbl.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgoknzyt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjakbpui.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2qlsudnzp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2hibzklle.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gt2reogbscj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2xjngthoh.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gt2gouapecm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gt2tucyqulo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jridixug.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2nekxkjio.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pshebdkr.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gt2tragaemx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2ogcdbdkn.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gt2tsawnied.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gt2rzsrozij.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gt2jiioovdw.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2xdxdytxb.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2cxnwfcty.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2glgzvwzk.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gt2bjtgdakp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gt2jjwjinzo.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnjmjxzu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfhddkrq.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gt2ntseaxux.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2ujakgdfh.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2vkjgwfuj.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2xzvcrehd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2wsmimwho.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdeumblm.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2icntnzmp.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2dbrwughz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gt2hgxxsuvn.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2bwrvktxn.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2jfocijdx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqyxheo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2ckajeoje.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzeqkpid.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2bzgcojld.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2lljriolk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2eauwmkeg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2enofrzlm.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gt2uasiaaag.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2rmexhept.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gt2xrxacydl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gt2yhkxwbrx.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqmkifty.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gt2coqkmzsv.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2ybmosyms.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gt2jxiwlxho.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gt2nvxdsaol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2befywvmi.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2hspbqrsc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2dmruxnpu.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2mvjkhrgj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2lcfmojoh.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2izyqhiwi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2adbhckoc.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xibgdokn.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2hhvwkqqu.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2qsghdvgu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gt2pjowyrvk.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2pmyfolwn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgjktfqk.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iicqurhg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gt2gwudkpjm.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gt2pspjzhfk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gt2tzeoljrg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aolfdhfc.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkvjvmno.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2fhbkhxdq.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gt2etawfjum.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gt2uhucntbc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xzcteyiw.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gt2khibwjbn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xhznpjiu.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gt2hpcpogcg.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2vwlqsrpu.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2mvuxjrhc.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2bwludztx.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2btxcxywh.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2dzjrzjfk.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2bvcgytdl.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gt2rnblxfbf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2jfvvuflz.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gt2svecttre.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2nzouflul.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2qrbpclnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ywaykczm.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2daxkgbss.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2xqrbkiaa.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2acifaycz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pionlesb.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2gnssqyxp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2vuauskcz.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjxqqajw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpiozgfu.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2ddsuvamz.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2pedjigpg.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2vtxxxfir.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gt2judbqtew.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2tgyxdgks.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2cniqatmh.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2hyktjxyt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2cudkujih.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2qaktvohg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2kxjjswwh.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gt2fpobimxw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2uwxrcrce.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2hhcmhgme.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2vmjvbfkr.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gt2lmsjufjn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2osiamxcr.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2zxnnxuuj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2aprzsykc.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2zpbkkmmp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gt2ctqdisem.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2luvfjvdw.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gt2bgilrzkb.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2teaawshq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojkbrzti.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2edldoyxa.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2uprofpiu.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2fgiofzwg.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gt2klqgkihx.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2pviexqgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2gdakbutr.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2muwkzfte.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2kwqqasfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfwnsfdm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gt2lhywghdb.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2bbnhqkjm.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2laitjwac.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lvczujuz.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2urjaunob.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gt2rnrxbdhb.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2dpvokmpa.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2ubjqlejx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2bgdxwprf.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gt2vlipucay.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2ayrbjirx.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2gbfhupyw.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tegdncgj.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gt2ebmozeee.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2yurtwejk.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gt2lzqhbjaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gt2elmpwnzc.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2lymtypmw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2myplauxd.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gt2bdxzwmiw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2bjnwbjhi.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gt2akfwvxxi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2tufeuxog.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2teepnvrh.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2diwxctlk.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2bmzjxuol.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gt2wndyzapt.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2ptdvexmn.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2urlutdom.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2qweifdlc.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxbvzmzs.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfmuquwh.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnkklxjg.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2okufuwyq.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2rjdmzkqu.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsnsbryd.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2snlzbeto.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gt2vbjjmxro.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gt2vielcuix.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gt2cdwswbdm.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gt2oesiroha.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gt2esftbsef.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2wqrfnwyd.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2xkzmpzcm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2gbfrucgv.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gt2ngyerfee.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2qvhfdudy.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gt2npkubqas.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2inarqzjt.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gt2xqwhfqtc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2umsdyaeo.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2vrhppzlz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdlpiqfa.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2nvsohxhz.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2bwejaezq.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2tihkfugz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2skhifokj.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2pwgnobgr.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2prqfqbzg.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2hirurpfo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2yotbrvgc.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gt2aqwienne.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2wqnhpisy.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gt2kgohhpvg.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2dyguthzo.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2wahwsuha.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2ldatdlva.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2tniowvjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2wclftfaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2ixhyusef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leyhzzwm.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2brxpqobh.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gt2csawawsx.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2rshueffx.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gt2zentdkyt.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfamgrxd.html


<!-- 参考信息 -->