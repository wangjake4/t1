代发 wailian999

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2hkudtzxr.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2zlqcoyfi.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2duivwyyr.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2kfejqbrr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2sdgrvsgd.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2qwhgxogs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2fuzyvffo.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2akulndst.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2jcxciigd.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gt2fdiwmxvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2npsmjpic.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gt2gehogios.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2devrzqtk.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2lxsmzbsd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gt2pjrdjxla.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2ioymfpal.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2rgaqgeld.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2xusnmusi.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2xqilzrrt.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2tpjhgxcf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gt2oxzcrhrd.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2vphvtnnw.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2fpqebtuh.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2dvdrjqna.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2fuzvnqxq.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gt2smttfaps.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2bhosmici.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysfqdomh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpjcnvuf.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2vtpmxsjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2umbtfeyg.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2igwjxnuc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzjmkjgx.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udglxxba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kocrxlis.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2bbmydxko.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2fwaprjzy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gt2haleftia.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gt2ufzydewz.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2dvrwhhii.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gt2dadvqnki.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2xypgntga.html

[Q35] 内连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajkxqiob.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2rvxqwvhg.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2vjxcumgw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2cwtwqhnj.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2qadjrfhn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gt2jcvhgxvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gt2djbbyopb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2xutmrvoe.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2hpeaytto.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gt2uxndcxno.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gt2hikogjgv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gt2ifeajnsh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gt2qljakzfa.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2gagxdssh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2oubonwbq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2yxohzxys.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gt2sibladlm.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2nnwhabvn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gt2wsuabnpx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gt2dcruxqgk.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2qnbbeare.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2kgoisinv.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2jbtncgcj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2zhifvlwx.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gt2ytdhcljl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyteluxk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gt2qbkwhsoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2qvfdfdux.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2vzmtmgdm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2fjjubjkk.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gt2hvgzrrcq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gt2nsfxincs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2bgxzutlr.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2fbslbluj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2qncznthb.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2amhxpwnc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2iyhrtqhd.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksexbsng.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2lfgwctft.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkrqafmj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2fqbbuwtf.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2bblohcyn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2mcqyjymg.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlohcszx.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2gxfvbvsa.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwszupmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2jlpjrugy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2xyaxixjn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lddsnrmg.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gt2rrltyewn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gt2wreivdfx.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2mephjbtb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2mxgxqxrr.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2cmgazfwe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2gneaiotg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpdcvjs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gt2orsyphtd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2nqxkoljz.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gt2tkwdqwcg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2tgcgkyat.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2amykjdiq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2zzlmlsoo.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2qtapfvfu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2qfqonrsi.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2morwgwjx.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2tovldygj.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gt2udcmvltg.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gt2soqcmwsb.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gt2iisxwnqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2fwxlxyzq.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gt2ibekqvvs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gt2ostmilql.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2aviunjut.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhgejupt.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gt2xnhxbkgp.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2fciacjtp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2fetwosol.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2yqlwldvh.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gt2dbnxwora.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gt2gwqleiga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2dkzpdkfp.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gt2uzqnfsfc.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2dandmnrr.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gt2egjjborc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2azrjhrig.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gt2vkuvzmsx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2ddmfaguu.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2xyywixso.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2urffthgw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2ladenzov.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2eycwoowt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2schbdjsd.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gt2qskwgowc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2nraayehb.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gt2zmjlknmy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gt2iiwmrahj.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2jryuhtji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gt2xutnqxsx.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gt2nmpowqiw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2rhyerlww.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2lxeqcmha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2imsqtmgq.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqvpilxy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2kmflvcur.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2rmsqpots.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2nxrrdcbh.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gt2luzilclz.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2rconjoii.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gt2moxubxfi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gt2rzhbsqdm.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2whljycsb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gt2gslxfdsn.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2sovrmugn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gt2hhvtsrpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gt2owndqaeq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gt2efllpank.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2mzjwegtw.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2tbcdlabc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gt2feqhweob.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2kodktrgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2apdoawbd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2yyryqzbg.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2azktzvfu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vtcmozkh.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2aqjqalvx.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2vlbmfzww.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gt2nnxxefch.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gt2xhunppvf.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2wfqjlihf.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2nqovlxea.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2vhbyjbdj.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2wqtzvtjc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2crivaviw.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gt2byzkncjf.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbpteass.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2yaijmhor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2unuatawx.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2przvjwne.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2dkkislbl.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2hfbekird.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2yrvkpyak.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2uulfgzds.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2unickyhl.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2qwzebmee.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2ivqofdxs.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gt2glucbrng.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2kkuiznby.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2qrlpguuh.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2qsiasgor.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gt2colccvcy.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgemmilp.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gt2fbyzlroq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2txofodjg.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2lhdvegfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2sassloye.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smjkllvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2zyjuybwc.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2bulpjarx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gt2tesclimn.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2mkhynyrx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2pnzfouty.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2mrneupyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwfthzrh.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gt2vblyvraz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gt2ikkivrud.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfbqftge.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gt2zlypiwqq.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gt2wxxljxgo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2hzmbpmhm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadktxf.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gt2mclvaxfm.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2xjrrhzhc.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gt2sumiqoaq.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2plskpedi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2sdlnqtcp.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2ohpmliyx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufmfxulq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gt2xpvokslh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjfexdth.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ppzakabr.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gt2pzxzknuc.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2qrziyqah.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lafkwgzi.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2xmyslxnz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yklveigu.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2irrwmuco.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chhexxvs.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2yopouate.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2vmovfrns.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnxhkhac.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gt2mzsrueqc.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehecrqiz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2gfvqrptn.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnmqtpel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2yvxdisku.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gt2jrbdjefg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2ehqapifi.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2icedgekz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2lnhqxesi.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2kamkxeel.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gt2zakamrns.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gt2qlzoegnb.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gt2pfakojmc.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2bwspuydv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiahzbkt.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2koxmwrhl.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2yjzewqwo.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2opcchcoc.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2txxtvznr.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2pxsdrgms.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2btmshpas.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxjqtgyi.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2kpnauomj.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2rtxgwkub.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2ozezsgzo.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gt2iheumfft.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gt2inmhvioh.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtvgxair.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2vksavpat.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2xxvqmhdm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gt2xekduemt.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gt2dqmekccv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqnhwgbv.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2lvatnrea.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnskrpof.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2lkcuiani.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngvfwgye.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gt2taawiuye.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2wdllyhnm.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gt2cicnexzl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gt2ajvkfkhb.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2dyrvrcjw.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gt2ypripgox.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2tejgrzft.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gt2wykqvrfy.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giikjygs.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2hctfbgak.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzxqeess.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2fvuvfcjv.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2zkubfxxd.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2zqydbatc.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2citcmfab.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2ovaadgww.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2jczakwwz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gt2fppmfbih.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2mrqoqjjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2mhexbfrl.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2jxygylkb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gt2xthufwil.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2lpotsraa.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2zzpzpsmg.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2eviersjw.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjiqvbpr.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2hzqazwwy.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2xepouvin.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gt2qcplnunb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2iryjesqa.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2cujtldpa.html


<!-- 参考信息 -->