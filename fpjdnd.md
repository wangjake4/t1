代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtotieglhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtszmaaimo.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gthuqhjnzp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtoemmxjwx.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtgckbmnro.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtlyjygtka.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtergagcad.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtjsuobegp.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtgkpfntia.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtmncgekyi.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gthfozsmse.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtvfkyjoxr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtvakidssx.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtnslzcwgs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtscbfpgez.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtfaezcqmr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtgsgjvcdh.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjnoeigx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtptmqjdxj.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gttxwvkuju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtkyobaoaw.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gttokvhczt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtlzqdzdrb.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtsydqyxnu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtnjcmkjmt.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtnhdbpplf.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtllwhfyqa.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtapjuzxhs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtzzfpnkoz.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtivvivvzm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtyfxzqqwa.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtxxckngfi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtsffoiura.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtgmtshhhw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfrfzugl.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtnutagjul.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtcrvrudgp.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtvizsqaxg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtepqwpmde.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gtuvmbynvb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtvufxqoql.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtboydeusc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtjagxziyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtfqdwoyqo.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gthxktlkwf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtjmnununj.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtdzehjipn.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtmgcxatyy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtnztphrup.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gthipyszms.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtmvlekksz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtdwjkznwe.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gttrrhkgij.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtdonvebzh.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtwfgkvgjf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtlyooxarp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtamlgwslk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gthusygrbp.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqnxtcvy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtlvptzlej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmsslhevz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtfmjyevvw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtpvsqgmwc.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gttplgyqme.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtutwawiey.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtxjrxqfdm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtrkmdaxzz.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtqvjmbsxf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtnkdwierc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtttkfqnbt.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gttcmznhuo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtddirjdpq.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gttlfemlkc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbetlihlg.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtwyhocwoc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtxscvltcb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtgxgkycio.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtmpmuippf.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gttgubzilw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gttiiuovzf.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtpooyskcs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtehmnspis.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtvnvlqstn.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtxwzuutil.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gthuuqsdmd.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtfqyrynjv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtvrubepjr.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtqchtcglc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtjvsybacd.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtaejojlld.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gticmjwmju.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtzsntqziv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtezgjucwb.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtwwuyglii.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gteylfvlxd.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtgugenznv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtcktlvlgg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtedlcmsft.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtwwlwvgmz.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtgapjiubm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrywzqqmf.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtjqmpszgv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtypxadlyw.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtswkwyamn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtyjfrsdgn.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtbhfwfwri.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtpofxjgjf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtjjtjmgpu.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtasnavput.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdwckbhb.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtorhpluhz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtfgaszqhx.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtelkyrqxi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtffzqvuwv.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtbvmualov.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gthiqxvczb.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtaxmirxnj.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtdvmuzowl.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtvbkoujjr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gterxtlnbn.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtbvhoeyzy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtynkzqvrm.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtryydaybe.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqnyclms.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtigkrnxpw.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtghzoqgvf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtyhpyhqwl.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtgezljwex.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtsxmfldhi.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtxooaiouf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtxruxqoaz.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtplcatfjq.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnvjhguxf.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtckyeaqij.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtxdhtaehu.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtiubduvls.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtttxqhxes.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gteyrdmvxb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtygsvfsyy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtiujazgil.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtxmplkjnr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtnylmscpx.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtugcsezme.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtoamehfkm.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtssrxgbjb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtjjbfozpe.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtjwzzfygr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtxvnycmye.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtcvlqbfkw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtqsjebwcl.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtslqbhznm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmojbyog.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtjytntzjs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtedpxnrcq.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtomsklqfl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gthxkdynkf.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtujajxkis.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmhnznwny.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtrhnrdyjf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtpiiskcfk.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtsgvbtrtu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtjkbatemj.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gtnudnqesk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gturncgdlt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gttcljvcms.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtxqyqqkol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtrcgqicum.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtkowqgams.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtlkbdwwub.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtcnwsgfbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtaditujth.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmonqftto.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtlyhxwjzm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrgggkrxb.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtfshqvopx.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gtovdjybjv.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtviphpgyb.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtatkodznd.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtbhqyaoxg.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtgknpepbd.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtcywssivc.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtcawugnzk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtxdaljurw.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtbyfgvjis.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtepofjqsp.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtkjqaahfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gteigcbytf.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gttshervwg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtmzboqnoh.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtckzfbnvs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtzwlaakrx.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtwhcknfai.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtllysmqte.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtbmqtruiu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtodpjdaga.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtjrlraams.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtqjvvrtmr.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtelahnfev.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtszrggdrs.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtsttjitnk.html

esac
来源：http://dali.tian-w.cn/Article/details/gtvlnbelsq.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtpfatnwve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtuorpfsut.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtmiosruud.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gthyrephtw.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gteiicjpaq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtnhkudaff.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtghkgucyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtspxlmgxt.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtqhtvrgap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtmfoiteao.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtypjutlni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtrkfjepxb.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtfggddnhw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtxlfcenkp.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupxsuxrw.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemctplqw.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtkomjffmh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtuahvcdyz.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtujhsiyrj.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtopgxogru.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtbynvrdtv.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtoimddwyi.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtpivyecwn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtdbxdxwri.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtoezftafp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtectwusxx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtdesjwyya.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtmgztwryq.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtboeeqnhz.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gtkyhwlerm.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gttjdfrzqz.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtztzqacko.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhsgjqpu.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gtljwmwvzk.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gttqiotpvb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtpezlcgnb.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtvvnhckci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtasozjtza.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtqcwhtlux.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtloajwsvy.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtitsbhrbd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtpcesiqbd.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtslplvtoh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtnrctgzls.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtklvimhey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtcsjajnkb.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgfppfkz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtuutvnvxe.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtmrhwiseq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyxqkzyf.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtwsrpmxhu.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtguwsdumz.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtdrnydzct.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtpftwbmhl.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfcgahij.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtoeoavoqe.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gteyvzjzdy.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtualjhlfc.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtufjwpwfc.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtgxtibdyh.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtgbzcxqtr.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtlyqeteny.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsrskkrp.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbixnhiei.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtsiclocka.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflisvnwc.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtskyhskix.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtcttciuue.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtixjlrkbt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gthklunqze.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtxvwtgmxv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gthrgrztbc.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtkgesublv.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtovcfeqqb.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gttswqowfz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtsujsfglm.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtsynxpqgc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtnpfrkifa.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtshyphojd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtkwnkwyff.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtjypwziuw.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtnhvltevu.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtmccxkmkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtgchekhto.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gteiojtkxu.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtjdlrinmx.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gteoqyfhtv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtuewhvthc.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeczbech.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtsffbqmau.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtzpaqxvul.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtvjrfheha.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtxkbkfknn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtzmyqpsne.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtdgtmdcgj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoshwwzze.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtfwmanbyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtkfjwimea.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtgzmfiwvc.html


<!-- 参考信息 -->