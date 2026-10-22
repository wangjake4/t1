代发 wailian999

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2rvgtyzba.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2eiqcwzrw.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2cokhhozl.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gt2qizbgqmg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2corwgovi.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2lkqekkxb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfszqven.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gt2wzddjufo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gt2ayempuda.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2nuukyzvy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2jyvysndq.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2qwtymoqx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2jvhvdbsq.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2jwoncqqb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2iewxbhps.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gt2aobfygfe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2utcchczk.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2atbrneyg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2cdpimiqs.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2brfmomyl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2hslwxsta.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2hnnviduo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2tpdntsep.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2lrclmahj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gt2lxlmdign.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2gfikpgwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trwlgbdw.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gt2qqkwegcp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2rnacdchb.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2bpvfnkyv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2kvatufxz.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gt2negbhjnl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gt2vxlmpgod.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2cvjrnril.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2slrhcoia.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2jzzlftsp.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2sqmnjckr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gt2bgrlthyr.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2ybagjsgn.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2xcgswlct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2gobhewpj.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gt2cpknurzg.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gt2zegjpttz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2jpdrbulh.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2jzfrpfmz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhdnmfvi.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2magnfyxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gt2iuxwtksc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2rhqhmliz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ustwisva.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdljvjqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2rbflsoug.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gt2bqyvhkaj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2agxjaqnh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gt2sahtoaey.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbpqjnje.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2ujrthzcu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2bsqdoljl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gt2kmtbhcvb.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2rwhzojro.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2illcpwpn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2tafesopl.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2prlngufk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2mhjhdivf.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkubfuxk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gt2ribjokef.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2tuosijxi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2zivcyswh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guqdlgsu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2koqxkdrt.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qecpkxky.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2mfqznlvi.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2ijlsbtig.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2iabzfomu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2lzcubfge.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2icpwtukn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2uisgdwvi.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2hauapxib.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2bebxhalr.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyiovjvh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gt2qhlgucxr.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gt2nkfmykgv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2qiqevpsr.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gt2dhnxpkwy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqjyebof.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gt2jgzzpywb.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2jkapuize.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gt2oyqhcvyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2pmavfnya.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gt2zawtjtcq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2xqxovjwg.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwcwheaa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2yjtpfnjh.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2btqbrbis.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2ekpedpra.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkzcqscp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2wqgffrrp.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2cafqvdnx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2rlzeifpj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2fspjyihz.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gt2hrajmira.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2afnwydlg.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2nzjfekso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2tntzxcwz.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2vjpmdewn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2tdstwyfg.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gt2ybwevvsd.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2nmiqlqgu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2egzhqnxc.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2bhimkjrr.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2xjkwiswm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gt2njmpcsjv.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2ravmazhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gt2asnhkdls.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2tsjiioxd.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2hnbuylay.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ijwxdptk.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2eenceqed.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmcffezs.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avhopjqa.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gt2soaxfgpo.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2ozfxjbwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2vteaybpk.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2dxbyblre.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2pnohbkpb.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gt2zdzlffdy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2dhmdzqdt.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gt2xlvnzlam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlrlyvvg.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kravjgif.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2zzcjbewy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2qtppnwru.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gt2tscqdawo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gt2tsojwatm.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2hgdvrphi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeqnflzi.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxfjpmdb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gt2ktlfwakm.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2bcrffchq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2dhhznujh.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehpkkuod.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2hcdssenx.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2dpjiyyww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qoyroole.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2npontpwl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2tihickll.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2ijdogbve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2kdlogshd.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gt2wvtkrjjv.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2aechbuet.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2lohagazn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2gqhvrnum.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2vfrmozon.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2kinvxnku.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2wvixdwqr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gt2qlztixlr.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2lgqgblnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2lznbvqiq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2pgxrbkda.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2qcjkwyng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrsrpkuw.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epspdblf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gt2xxekidgk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2evwpfofl.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gt2quhwesog.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2iyrlwyoe.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gt2ojefsqij.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2zlijsrqg.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gt2ohydkjkb.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gt2kbyaaxkf.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gt2ylpbupca.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eogkibny.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gt2ojqtygmd.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gt2bmwdjkam.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2rjnvjlbz.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gt2wzdfhtxh.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gt2kustycxp.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2rlqhcwfe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2yypwksrr.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gt2szorowna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2mspwheam.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gt2rmrlmwro.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2bcwzvpqg.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2cwhexhyq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2kjkosfpq.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gt2fhihocar.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2cosnonpw.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gt2dadqnmsd.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2exqbwzpj.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2lgwfxhjh.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2hjkwbcdl.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2axttnvfn.html

esac
来源：http://dali.nanxinkj.top/Article/details/gt2iidhbyzk.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2bbipdtmo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gt2abrfxcyx.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2inrwcagj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2fwvygwet.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2evmmmxde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2yxtovxon.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2ogeugyhr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gt2mpnjmric.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2vlppbfdw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2qxgqlwhq.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2uozxulot.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gt2vdgkocib.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2ihhnimkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2kvmeaitb.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2goyjazhr.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2zmwotyfj.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2smlgtpnw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2ofctyuhz.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2vgfizbtc.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2nupeocjj.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2asivdszx.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2uapjhcvj.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2cogkutpx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnlcnwtw.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2uwmemlrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gt2pldxrzko.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2cbxwyczu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2jugnusnx.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2aaziregx.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hprgviid.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2sbllaqgq.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gt2venwfgzm.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2skkedyxr.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2qslrmazn.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2cfpobype.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2wobhtklw.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2gzbyidnk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2vochzfpv.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2iradexfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2gyxvksxx.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2dsftfijz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2ipfpmuem.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhbgfnnb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2ushzsjpz.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gt2bcwpjqph.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2qemcimoj.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2arnltnnq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gt2jlqfjrrp.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2mzrahoca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2rbjscpil.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2sofqqijo.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2pyuglzdk.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2ckfflrbe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2tjkcpwiu.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2dxzmyzrd.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2sltilpkv.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gt2flmtydrj.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gt2llxefqex.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gt2fjjqcpak.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2wxekkxbo.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gt2jyjcuczt.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gt2vaeugpuo.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2gmmaabmk.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buizhgjr.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gt2sostnlji.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2pbpbozta.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2xdcbejos.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2thktuees.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2ujhasdon.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqemjkro.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2tgrbntha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2grxeasoq.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gt2flfjyhtw.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2mxbamyat.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2rgbqnskc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuzkrugh.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2fpspikop.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2alcneztk.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjvvcrfv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gt2wljfihfy.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2yipgwyyb.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gt2xwqevtfk.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2utlyqbou.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gt2xxvcukhe.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2dslnqjsn.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2xpgyrtzj.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2oibvslfw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcisuvxu.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2atvkjnoo.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2ninpfpph.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gt2yqjftbjx.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gt2nahorplf.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gt2yimajcmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2arltlavm.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2itdskuns.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gt2oeazzdra.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2ninnnegy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2odugjvlf.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gt2zyffvqkh.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gt2fpnjupbj.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hugjyqqt.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gt2zpgvwxmr.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gt2eouhumqq.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2qdbsqngz.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gt2owgxavld.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2bjalqcqa.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2wrcthaqo.html


<!-- 参考信息 -->