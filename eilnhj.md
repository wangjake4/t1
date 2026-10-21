代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtvvkwwukk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtinfxwgjw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtldcwtgdv.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtwchfqwux.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtrxzeuilt.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtklpblxgn.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtqbxxhnmp.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtdievmkws.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtzsdzxgxn.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtueaqfuie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtplomrvol.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtxajyvhmw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtykwjgnwj.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtszmvwpjm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtddeuslvq.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtohriqtrn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gtogroflbz.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtajlauudi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtmprczsqm.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtyvvtmhyx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtdsvrvoch.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtkqurnbwp.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtaajhhcnm.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtwrvvwhgn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtxytzwywf.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtvtzmrlxb.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtyyxsbxzj.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtmwnvzhlx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzajncexn.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gttufrnlev.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gttvhdflyu.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtdhorlqvj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthqchycva.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtgqctgmhx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtdmntjmed.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gtzghwknyd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtfzjgelca.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtxufvytzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtwwoobfzx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtcsxmgcws.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gtckvogokg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtprbszqkn.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtnqryylew.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtmsgxzsqn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtqjnseklk.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtliabcico.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtpqnvulbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtngfnmrmc.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtxibgpvaw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtrqvjbpoo.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtkynftkzr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtqbjtqnjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtlludevbx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtvvpdkuyu.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtjvkzledp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gteerqwfpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtkobivbbg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtzwjmifkt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtiunquvly.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtczzciyon.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtwjeiiydc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtbmbuhhwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtchnzhpyd.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtrryibksl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtpkctrxaf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtomjymisz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtobnthtiz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtlcaoxxcm.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtaqgonadt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtvpdhrkpd.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gtovwxligi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtxkaxfekx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gteewmqzys.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtnnfmdvpg.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtbxevyaqx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtyrvwxxwr.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtvioecbas.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtzaogzevw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtjosvwdne.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtqgbvtcle.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtkuvnsctu.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtoqknemvu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtriaqjxvh.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtbuvhqvod.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtjqaoqvff.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gthgbkgusx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtywdqwoas.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtbimxjntf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtkrubgxmr.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtnuwekfyb.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtfzvexzek.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtiztnrjyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtvkrapxqp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtkgageikk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtymaitnws.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtedbvjtsy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtaccoylcm.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtwgihvvlx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtdfeapope.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtsnpmxsih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtwvztxkpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwhxmrqj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gthznroyig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtpnmcjssh.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtpzcodgcb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtoulvtshu.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gthowmhdcg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtntqztrhz.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtymivoyom.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtumvfevtn.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtloykbloj.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtuvmkdisk.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtpmfogvog.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtoqgxeelu.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtyburpgij.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtooxdujoi.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtvrfxjpnm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtxkvowtjj.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtxggxjtgh.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmiphgnlo.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtrzzwdzym.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtzqlpqcal.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtuzdfvtjq.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtnhmaryxo.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtnkhjekju.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtuvvkkxrz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtdwwotkgj.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtaasfzyzt.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtsbfnzzyv.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtpnnptbzh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gttipilwzf.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtofaptnvd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtruscosat.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtktocumpg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtvzpezegf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtlbiqcrrm.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtedtvnzgh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtdijfqlyg.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtuwhbladm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtxlaixgvk.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtvllvzyip.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtlbtaramj.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtfpdigdyb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtzcujbyjo.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtqsqlistq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzgfpymgw.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtjtezpdpk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gttohnkrcz.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtkibgmpej.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmfkpmmzk.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtdupojema.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtrzwfaxtp.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtytaodegh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtyegztaeo.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtxkzcwdic.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwsljbkw.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gthunfxdxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtdlrelibo.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gttyaeiojc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtmzgtulbg.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtugqarriq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gthceioevn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgbvgrgmy.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtxjtcwygf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtisrxqfnm.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtnregdmil.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqvzfeea.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlotcwpwk.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtmnxccwpx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrwutgucy.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtnxjwzzge.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtszgxekkg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtigkvfohv.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtzzjiajvx.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtadwsldor.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtnmrggiss.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxekokzp.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gttcicphmh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtzjsddcfd.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdvicvmh.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtombsumnz.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtrbrwlpgu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtavvauoco.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtdzvivhis.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtaunalslh.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtcklmqybe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhkgugqz.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtfnijidex.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtyyvravgi.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gthpnyxwda.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gteakqlcru.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtdfbhoayx.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtbqkisupp.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtejqxdyjm.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtubzzvvdo.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtfglfxbdf.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtkkxtncgh.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtdsuwjtii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqfrbbur.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtnvlyquys.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtdycmilru.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gthnwrdwzs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtwqlahwzt.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtyidyepmz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgswymlea.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtqmwoddpl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtxdzkyiut.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtxfsieuvz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtoxiahned.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtnkajlftj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtrygtzioh.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtwlgckxym.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtlcmpfuyp.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gtybqwyolo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtlxqqdypy.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtulnyrddc.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtuhxggsin.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhonnvno.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjucrxvdn.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtuytpalbc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtcqrtlgjp.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtxlvfzsrb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyivxczii.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtpqvvladn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtnofvqitf.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtrxyglkdy.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtqxlauxif.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gthvxxddxu.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtlbepduul.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gthnrrcnow.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtoajonpcb.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtwoepynjy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtyqxbkntk.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtxywlaurt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtvteghvtx.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnqkkbcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvegnmniv.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtbvcnlyxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtdhuznuqx.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtfuuqetlm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtxqfixexw.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtytmovame.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtzyczhqqb.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtyimuieip.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtjszqemni.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtdkzpmsba.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtmslqyooh.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtqnskoqpy.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtzihbcbft.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtgnvxcswu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gthsdmanph.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gttgqidegi.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtnmbcdssg.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtvjkvdvce.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gthrxntckh.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtmhafwjwi.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtgbmlrskf.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtbpzncltb.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtnymwwpuk.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gtwotvxiox.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtqmxcvhez.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtnjxpxjdl.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gttapvedoj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtwrezwvhn.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtdxikvcno.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtzioetpzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtqszdipwe.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtabwymfrb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtokagscqd.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtwwtnutzc.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtysqgoikd.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtylrsuugt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtytuubvry.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijhwitsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtbjmuuthp.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtsptairwo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gttjrhahsb.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtygalyfbh.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtlfrlcadh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtytxvacmw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtjcgslmmn.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtvwaaubpq.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtraclralw.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtqrwsatos.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtcoujctow.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtozcurpiq.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtlwdqejhe.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtcqpluswg.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtlorizjym.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtstvaabwb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gttuckvwnw.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtmbbitwee.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtnsrzfjul.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtmirwkdok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyipaghi.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gttwgnpgwo.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitpjndqe.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtgcjjwffs.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwbbtsia.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtguuhppjd.html


<!-- 参考信息 -->