代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2rovgvfzi.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gt2wuelfhpu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gt2klyumvdg.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gt2vckrtvlh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2hqmriuxn.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2hjaqiogc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2voiorcek.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gt2ynvhzztr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2qthklaha.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2xumornhv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wajkhgkv.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gt2pdefcdbn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2iihawzgu.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2bhlyfxtd.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gt2xiymiqvb.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gt2ssunppgt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gt2fptfmpqw.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gt2ojgcgccd.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flbgaioj.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2ansadlkb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2egihdboc.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gt2yzplndnu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2eajaopwb.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2xzxdjmfw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2ykfecups.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2vsevadim.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2kbcvytzd.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qavaewro.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gt2qlvyictf.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2dxgpprme.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2nkluspuf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czokqyei.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gt2dekmcbwl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gt2ayomluig.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubckzbef.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2wqhwvkdr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gt2lqrbsets.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gt2lqazfjwb.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gt2fzlerfbv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2phtqfpup.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gt2mepfwimg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2afgvkcjc.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2aosflewc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ewqpyemq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbhjfdog.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2bxegperg.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2xlnrxuua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gt2aukbbcao.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azmjrihk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gt2ojceqscf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gt2chyvjskv.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2muhqfdhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2dtbxlhaw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2qxygtmbh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2pzleutza.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2yojrguvh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2ziefymij.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gt2fzrhsips.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gt2mxexbisk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2eeqmprkn.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2oeexjkrv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gt2aelzacaz.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2yprjrdlt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2xqzowxgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gt2qfwqbhpf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2mygxnyzj.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2wnzwfyzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gt2qaazbfpr.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zavwudpa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2qhjtkdre.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2utbgrbji.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evrwhapp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gt2tfnpfqfr.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2jguwrgdj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2ougoevzg.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2inceimrw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvlbexsf.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gt2bfkokmbi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lipitbjn.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gt2gifaxfti.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2dbkdfpmm.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gt2vwpbrzuu.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2vqfkbfzu.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gt2fzyelnrv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2evjtdzgg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gt2yjjfguhq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gt2wxiwmzaq.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gt2ctdtxasd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2hkdsspls.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2uikqdezc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2otomnkuk.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2ehcoxnxf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2dcpcltfl.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2dabiuobf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsyzhmok.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2pyuzgquj.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2lkxfiqtr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2pjxuhdma.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2fizkyhtv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2usuoogmh.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gt2aifiyuza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gt2tpykhouq.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gt2eptnwmyc.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gt2ojaylins.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2vpusecvm.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bawyrnwp.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2nzzudmpk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2zzgljiel.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gt2mhmsikar.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2ndemyfgo.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2pxrbtwmy.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2rdvwfapf.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thqgfixd.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gt2vogwenjs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gt2qqqzlenk.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gt2ipppvnsb.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2fzekelpc.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gt2twitwmyy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2qfrjrjua.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2zkoszptt.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ebiokrep.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gt2popvugkn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gt2drhijnfw.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2vjztligc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2xlsidvrt.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2ffeklntg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2renimpmy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2lfqyuaiy.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gt2zjrbzjun.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gt2tltsborx.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2hnsmfbtx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gt2uziwowee.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2bekibyry.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gt2juujxvgs.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2ohmjujhp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2zknwiyok.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2okstmnnv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2clufkmvv.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2iwcxcblp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qprkqidp.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2subldcfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2quaskdxs.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2xgqmmbpe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2oedjfomr.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjamjygt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvqaryaa.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gt2rtleqgmh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gt2dqczkahp.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2jrrfpxhl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2giaqzpju.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2ehfbkehq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gt2juwguedn.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2nvwkrrfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gt2bctjvays.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2cbupsary.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2acxxtbyw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gt2kfgjunrm.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2ltakmcnf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2kxpabnlv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2kpjquqii.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gt2snmzxdmt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2izpudgen.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2ychucyaf.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2poqxsuyd.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbqdsknr.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gt2lsqiravw.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlqlveqb.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gt2zttznobw.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gt2svgzcvbe.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gt2vtyxurnr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gt2shtjzydh.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2bhguemgx.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2lyppzxvk.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2eefzyheo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2abobjwvu.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gt2zuvdcmcu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2qmguzxox.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gt2wvlnstbm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gt2bcvofisa.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2sbvbjjwj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2bhpbyfeq.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gt2lybyexuf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpiffvmf.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2aoyugmrm.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2tcfczjgk.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2fmgdgvpg.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2zxntoyzw.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pegqwxri.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2cqnxteua.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2pidnmbby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbdhxiyu.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qebziowm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2dbobrybg.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gt2yyaoakof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gt2usugnura.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2rwkomnts.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2dzstwbox.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2pwgtnskj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iocymwqd.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gt2ohqwfvtm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2awdefpqm.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gt2iaztdzmi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2aiifhtoq.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcamhvfj.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2viygtaax.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2laiyqvbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2duuyzcyy.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrvkuitq.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2fuumdalu.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2heqmrkfr.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guspwovh.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oivzjfnq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2jayffskj.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2zwdnvihk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gt2ltyejnyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2vokchetc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2dwgobddu.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gt2lnaaefir.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gt2okwjlrdp.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gt2jigisuee.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gt2ntvtypoe.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2owwinrdj.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gt2zefnftfn.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2jhvgafpz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2nzkejldb.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gt2cnrdiknf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2wpnqdczk.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2vrukjijl.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2odpmdhhz.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqnlbiyu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2pqcfcalo.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzqbeenc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2vnibmqgv.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gt2klizcsnx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2kadvmrbc.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gt2vlrvbzay.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gt2inbhdnuu.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2qfpfyxqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2cgkfdcuc.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2xniygbmj.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gt2ztahdkrr.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2veprfkqv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdnjjxso.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksdoocwe.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2rdlrwqix.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gt2xtpogsgy.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjbtwcnu.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gt2exacnmuf.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2rutznuaj.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gt2xzdtlqfj.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2fwunvtdr.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2vbtsfpld.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2kfacvmhe.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2marawioq.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2aruhvrub.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2tqjmyhcj.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gt2nzhfbatm.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2ioeptvzs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2pylxnkpp.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gt2azdhlyvv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ihceqptk.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2ciwfalhx.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2vkfdbiai.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hczbbqez.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gt2bxmdigbq.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gt2retxmmdz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2qhmtbjve.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gt2mlklweza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skkfcazd.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2qsoysbra.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2airzimzq.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfefwrfp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gt2pvwprfhc.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gt2pjkydmde.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2nwdjsjzl.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvgjvfxb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2mvapkocd.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2stcnnbgv.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2smghkbgn.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2qtasyfgy.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2uhqwgbzn.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2gitdstyh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gt2uthxmxbo.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnuhguus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gt2wmjlauez.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2qmppiuqt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2vhcxgmgq.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2ciqdkbmh.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gt2qbutehyj.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gt2xdultnar.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2vpbvnosu.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gt2efbcyhnf.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gt2mlvxpvum.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gt2vjzbofia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gt2hkrycqly.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2qirghtoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2jejallkl.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gt2gehswqme.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2kohvqztt.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zixlmyyb.html


<!-- 参考信息 -->