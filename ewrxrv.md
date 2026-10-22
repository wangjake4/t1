代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gt2wlprcraw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gt2nxfzawpk.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gt2klobyhtn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2witluyao.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2sndjzfcz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2xchcsliq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gt2zfdfzvyx.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsrqmanw.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2zbhuejzn.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixmfifyh.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irxbupzs.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utkanxqp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kprofvam.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gt2ceutbzkj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2hllvzopj.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxvvtqdj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gt2vqinnwyk.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gt2nbbwzonj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2riivlqpd.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2tjhktkjn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqmkzpwz.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gt2adlaaplx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gt2tskbgpir.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2qhujcugl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2jndirbhn.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2xzxjynqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2vqqcyqzw.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gt2goshtjif.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2zniadqgv.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gt2gjqkahax.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2fyvbfedx.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2gbucdmss.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2aiankwat.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2wnzxxhyy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzzzkkd.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2tvtcvwsm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2fwpxdcwx.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gt2jaynwqnc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2uxlrqxej.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gt2wytyqfhm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gt2atysnoqp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2veowihtg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2gcgvggca.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2lihfruub.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gt2kzvknxok.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2vosglkqu.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2dopudwsw.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2ylbzduys.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gt2lkenevzp.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gt2ibfwodpf.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gt2qjozgokz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2hhcmhndk.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gt2jpjlmkgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2hxathamc.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2zqtuynkv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gt2txfmocax.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gt2izhrmjqy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gt2dxlddzii.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gt2apzdfohi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxxyxvza.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2wmtftotj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2wuiisapm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gt2uwunbraj.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gt2jmrezgjp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2zduvcedg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gt2luzezqpj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gt2skuarxgi.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2djtdvrjc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2ywopwepa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyayqnmh.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gt2ajjmaaps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2qhcfkguv.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2ppyskgwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2ezwttfzr.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2wuvqtroo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqtshgbc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2ocgzlfbr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2ltwrhihh.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2ntjmfair.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gt2rgusjvvv.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2bsksbbgx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gt2ohqxwzbw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2nbbtiajs.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2opfhyegu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2vlcmlooh.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2nkpblzqu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2jqqtaulj.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2kavxpozs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2tpoapmpf.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2auugdxyg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2pnnifacc.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gt2rbsonedl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2uwoqrcuu.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyfqpgnj.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snfcbkur.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2igslbkpy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2fwmaqdvf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gt2bcfxrwdk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2jytqskpe.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gt2dgzoewhh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2ptjmwoqz.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2gpubkzto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2afksbcbg.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2iblrhhhv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2adnaztlh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gt2xzcundzg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2gugzqolq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2kdgdkjdw.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gt2jydvclqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2agzsmxnd.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gt2sfjphvug.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2czeszfvr.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2jgkakkdu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2corpkelu.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gt2xzphuaqw.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2njybakss.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gt2itosfima.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gt2uivqbaqn.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2cpzftdhj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2vxjonggn.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2gdqpsops.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gt2yvwbfrib.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2bgcpyvmq.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2bfbvldef.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2vjprepsp.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gt2bkrnubob.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gt2ciqdkcok.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gt2epqxpfvh.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2urgshkkh.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgoweuyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjvtlkep.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gt2xmgdwabb.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2sebwclsn.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2ojzloqdf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gt2pbwxnfqd.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2eblyizjw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2rsyyrkkn.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2eifwawit.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbumpoxr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gt2oqdaktou.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gt2bupafpyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryzketnb.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzebwafu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2rtdedyhw.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2lrdjtbsd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gt2ufuefgqv.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2tsoyjcct.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gt2eebckiek.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gt2wilximce.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2zpjobimq.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2hootapoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ddofxeox.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2wfjooyeo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2lqjgxirb.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2nqmfiuqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2omsjkerl.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gt2nfvcqhqg.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2isaauwur.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gt2zohfvrjk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2wrgnfqji.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gt2yevwzjkr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2gawdjkiv.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2sidovsae.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2ewixvgft.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kabvgdwt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvrkgrsm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2jrvcchvv.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2dsiranay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2pexxrvwk.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2bdoxbixs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpsnxaol.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2whebnbkd.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2rqilutvv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqswihaz.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2gjeypvqn.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gt2zmaxnbrf.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2nyrqzoct.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2mnyonnky.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gt2nzicagrl.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thmfzvgg.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2qaorlsug.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gt2tcoygxhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjhpcomv.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gt2wdjbpddd.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryolbylk.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2sjoqskbr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2htcvuyhe.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kkjwyuhy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2fxrdfdmg.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2qzinjxcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxcjhqkt.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2tzibdrnp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2awhysvbr.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gt2duruypvw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2oycsmsts.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2jbopyxsw.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gt2bndpcoce.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gt2blwzzsex.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gt2uwfcdser.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gt2wqyisdvc.html

esac
来源：http://dali.yvedp.cn/Article/details/gt2bjipybxr.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2fmsxhfcd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2wmocugan.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynbrticq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2pavkdgay.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2lupbqbgy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2qfzlaqwp.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2iigaqcmk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ignkxknf.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2bbmjtjgq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2lxsyfdtq.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2nmtrhpyb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2jxxvktcj.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2bistdeva.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gt2cvebrxgo.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2ozltdutn.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2ycbkeqlr.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2dmjfdheu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhezovfp.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwhvfazg.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2bnkvkfro.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2clqzjrqd.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2vzqkxdog.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2bewyhchx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2gsutgiak.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2gfbnlzwu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2iwqhzhvq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2mwplxltg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2fdgphxdk.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2yrzsoyuf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2bbizsqrw.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2fvlyjtsp.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gt2swoppzdo.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2xhjhcovi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gt2njwtynmi.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovnfpzqr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gt2npnlpkzp.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gt2mlsdhski.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2pesvtbrp.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdciffwb.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gt2uvjcoois.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gt2lwzksqiy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2adfmnxjd.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gt2ajijbxtn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gt2bgstwddu.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmkmdzsp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2seewcdhq.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2lrhooecc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gt2flmgierc.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2xkhssrbp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gt2usckuxxi.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gt2scrhlnou.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gt2marwuglf.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gt2dwsclqsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gt2fdkxxpdr.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bplxjsgs.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2cuwdomez.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2gjkwmdpd.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gt2mjxqhtgg.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gt2isvffvfz.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2xwgzydiu.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2zjqrujvc.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gt2sgobhgwu.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gt2ardymrug.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2djclubmt.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2quaccctc.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2xjdkgykb.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gt2rnevdokj.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gt2mmphoeyp.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2ajjkqdga.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2rpvlwzvg.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2jqxjbmsx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2ticfiwym.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gt2vgaixpek.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2qaajkfbq.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmhzmnyi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2xknvijdv.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2aoimpuvg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2pavptdqu.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twxxmotw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gt2anlgngui.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gt2zfisiius.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gt2ebdpugij.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gt2leuwscjw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2muovfdkf.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gt2rwglpbqi.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gt2gcpcgtkb.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gt2andmyrvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gt2swubhgjh.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2zysfnlud.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gt2ftgufqzp.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gt2ngdkxkca.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2ckdcocle.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2sezsyobw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2bxkchyrj.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfuyiguo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2ekqynrfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2niqdcfbw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gt2azemhcls.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2krlktsmb.html


<!-- 参考信息 -->