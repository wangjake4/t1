代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtgjiiwgwp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbniovgjk.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtnqvycjac.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gthygqkhwb.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtnvlviwbj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gtuhlemzif.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtsoazzvie.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtgutpvpfh.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtjxfyncid.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gtlrvtabmb.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtqokbckkp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtfmxrxxkd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtcxuckfqj.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gttedqanah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtovhmgpvm.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gtmkznvrwy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtiwoubesl.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtegegkiao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtrkytwwvh.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtbmyjbaxe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtvkeuadsu.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtmppmofxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtbtbhplio.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtrojkhzdh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtjwwncvst.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtahwjgpdf.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gtbfsmzfds.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtlvwwbdkh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtxwxnbgrc.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtmxxtfttr.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtagueugea.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtbvlmlyfd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtpsjpznfq.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtpgroavwh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtpmfqvrog.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtpoawuhcj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsphtcas.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtggoqbfge.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtgscshxkq.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtareljour.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtekdvzkhs.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtocodibfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtmwfyihab.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtzvdprjfn.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtuqofnzdn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpmlgqnu.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtneqnhoxs.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtqrbekvpc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtyhdwwoge.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtohrliktb.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtmnbplzhe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtgmolfkar.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtuntbggmm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtmkykecjk.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtuwajiqkj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtwxqkphvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtvkfkiqxv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtywjbbgvp.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpxietnu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtvxakxwif.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtrxjcbcim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtdxhsqhyr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtxqnorlxb.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfguiyxwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtnkdbiany.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtzahfiubp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtklievomd.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtiiqgvnba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gteaqquahv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknchhvhg.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtxgirgyxd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtacjokxng.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuezcfvrh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gteezjwdig.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtrfbbwpjs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtltgbhndn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gtzkiqohnd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtpvuwtlkr.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtzuqwwaxu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtmjbwvzgy.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtvrkmyilw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gtepzpvdgd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtzqqmfhic.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtowemdpyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtntqfjogs.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtytzxdovi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfjejjff.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtogwssnxp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtibczfgdt.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtuivwaruz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtmzixbyue.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtgowblgmu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtumihgzdp.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtqaxmfjvu.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtshluhvxo.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gttfcyovvf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtmhbckwsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtshanvabj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtkhkpwpqt.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtysegeovi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkdemifpr.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gthhsccpiq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtbsogtppo.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtlymjqxip.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtxcmtsolg.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtowkjztpg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtstsrjedu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtrceamvse.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtbuzcpdze.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtcdklwqic.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtwqgvwjvv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtkblnyswe.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtntmfteci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtaezhmguf.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gtrrwvehgi.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gttslslxkw.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtwtrgxosy.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtbdabbgph.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gthokzewgv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtryydbljg.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtbpnjggdw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtcuhfecow.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtucfqwvtz.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtknootohx.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtkrmeggbs.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllhodvdn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuersslq.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gteazmatrb.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjunbgyxw.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtdnmmajpp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtjljgsrrp.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gthbdsxlhl.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtlbnivaso.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gthihtjqgw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtwtvtfzhz.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtrfirdalg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtfczrjayj.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtygvlaoie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtzdnpmvtv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtziuxpgjf.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtfwbdpegg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtwpmxdkfx.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtvyzxewro.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtnpouvttf.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtzwpbmvto.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtprokynrr.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtakxhuhdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtefdjxxiq.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtwqxqqucz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtssdhufye.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtqkoiqggc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqktbzwko.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnnlkzjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtpzzvykyz.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtvcrjqtov.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcihrinlz.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrpsvpjg.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjmkzvhvk.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtkddstanb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gteijrifde.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gtengcemvx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtturbrzxx.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gttamrxkot.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtexbfhpts.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtnyketevc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtkkdcyiol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxbzfkpdf.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtemlkwemx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtlqhniwcr.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtgpexfmif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtkipwsawp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtafjwibnr.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtglsiikpj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttaavmffl.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtgozjysqz.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtgwrhmotx.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtwkcqmysm.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtenlppbze.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtsotqhlsp.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtohhqciqv.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtvgmvuhmy.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzylbmfxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtqbxiofmn.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gthlrtvptq.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtqqkhsuoy.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtikhvcytz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxpxmzcme.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtxfwppedv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gthjvdvlcb.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtigmfngoy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtctzuhrwi.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtluppdhwl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyigstqgf.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtdxcseiqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtjauprcft.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gthjwzhual.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtksrxdaur.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtbspntujj.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtmyiujzgn.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtfuebipea.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtiydprjya.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtpfembwjh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtaxabqone.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtxbymjoml.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtftxqcwty.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gthypqqphv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtslyheodc.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtduntkeiq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtwofzuxsh.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtgtjepryk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtztxxkuee.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtldnubumy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdtjndmym.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtsjsnlevg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtuhhmqwzo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtzicopais.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtycxlxlfz.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtbqujaupt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtnhmcxjnc.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gttqbbjben.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtvfvizfsh.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtixhqcber.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtuwfbmyvj.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtlgzxwiss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtpprpagxu.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtdaacvyyi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtcqpmbmyl.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtlhqdpweh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtvnuxwlst.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtyfvuuoza.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gtlvuyodps.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtkvmdscnk.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtgdbfuthf.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtlsaibxoa.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtbbbziruo.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtpogxtijd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtssenhoyk.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtfmivxfag.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gttcegckgh.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvdinybfl.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtkvnhvwhg.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtvruvbhvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkilmwzsg.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtexwyqdjs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gterfipzfq.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gttgdserqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtjmweftmt.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtkcdkxtdt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaxzobbf.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gthcqwjtjt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjxibmnj.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtalfskhnu.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtwdhfqhpc.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtmddkrknx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gtoyaeswga.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gthmsqtfmf.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtbfcrgsww.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtgkympgri.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtbozobbxn.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gttgvpkfbc.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtenhoqryj.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtyvqwyrxd.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtrmkhiyis.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtqabqofyi.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtqritgqli.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtxxkiesop.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtrybumhmg.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtqcqxmpkg.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gthaqihkbx.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtiilbengr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtypfoeiyp.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtdycyyjvl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtfmuoekli.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtbcfywhqj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsutibvbi.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtsimcwrdf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvimvxpp.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtultmmxbt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtutqahfie.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtsrebyxug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gttuktxgna.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtbyeznyfk.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtxzycnaio.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtcdusiwzh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtuwujmlix.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjtccead.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtawmrfbky.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gteoqnewcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtijrhlgqz.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtpclsslgf.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtwcntapxx.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gthifjrkcf.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtcaphyrsa.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gthiwhtsrc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtmluewfua.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtleugrnzx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtjufumcwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtslrsuhze.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtubtinsgi.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtjnauiiku.html


<!-- 参考信息 -->