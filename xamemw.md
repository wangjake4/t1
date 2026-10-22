代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2vdhdpzlr.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gt2mfidpcmo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxyldoah.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gt2osjoxkoi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iolafbhe.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2lalztjku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2wgakuwmt.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2doojegcb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2exzstyzu.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gt2bmqtbxra.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2usxfvkzs.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2pthljvxs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gt2mmzwkawg.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gt2ltwnkvqi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mquqzilo.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gt2qqihkyzz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gt2ulozggha.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gt2opcgzfnx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2voimkrbd.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2htktwklq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihqqrdjs.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gt2idkbkltx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2dlusricu.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2lrfhrjct.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2rugcvoof.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gt2rgsnfjbk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2mncqkhof.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2csztmwtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2ewapyalb.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2bchzxigz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2erxtlirw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gt2cftpnlzx.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2ohxfzfnt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gt2ffwpodre.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gt2nlcfzlex.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gt2ngjrqebb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akovbjrh.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwvmztcq.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2ovgenwtb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2kmmlrfly.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2aqebqiyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryawhsxy.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gt2dtswtuws.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gt2iibibbtl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqjogxky.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxdcljjh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gt2mrcdmooz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2avsxpect.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtcegmev.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2oekkwayl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2gpcntsir.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2qgwudlpr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gt2rjaafjha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gt2lgrmlxyo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjhkgons.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2vsybfwud.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2dwpfkiww.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2avxdnlse.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2chogxmfe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2hfxrgsvn.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2paqnckyi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gt2gowuxowp.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvaztqdg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2sgxzqoqb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2zpewyker.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2ykmgivxl.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2thocxasm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2nalznncn.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2uuwqesxv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gt2isqusndg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruuaidyd.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gt2fdcxvyhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmobrrts.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xavmqyiv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2etylmmty.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2zcggxdez.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gt2krwfiouz.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gt2tkaxtztb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2wctcpato.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gt2icyjsldu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2ijyvpmvy.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2cicftarh.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2rxugauuw.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2viilxnzj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2nohhddlc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gt2nllntcyb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gt2fjqoiicn.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtojwdgi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2tcxgemzr.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gt2olafibtv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2vsnlzfff.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2tbhxsdip.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2gvckksjb.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gt2afagtyfq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2toxljbxm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2dukhnyzn.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2lgzlcync.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2vdnjgnps.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gt2hcdjfvuv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2yjazlxjh.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gt2thpaemmu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gt2ekcdulhe.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gt2hvimqyzd.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2lrzccafv.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozvifmuu.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2yrousrfe.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gt2qmvkcpae.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gt2coonfzts.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gt2izewwwsg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2mpsaqjtn.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gt2wbdwmzif.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2xsewazhy.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2kpbuqoyy.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2myxzjyql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkxakmhs.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gt2aswayfum.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkpabd.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2ogwomatd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2otdldxle.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2psyarsbg.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2yomrmpry.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gt2qqqvnsjy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gt2qzocjucs.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2ydsbfpoe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2fwfdqgwh.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2dczftvgc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2ecyafhbd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gt2pxgljxeg.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2nxlwxzno.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gt2xqvzqlls.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gt2rwavclhg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gt2dczznnnq.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2lndojyku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2whnqljdn.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2znwspzdc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2ugawcbpe.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmcrgwmj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2nzsnbkuz.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2aykaojrv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2hxisanpv.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2tlvfldqu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thsscedr.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2ztluekqp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2oeymzeyf.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2vtlqsyrb.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2znzsynmv.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gt2snmzimzu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gt2ynzwegma.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddxjgken.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2mydjrbty.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2phjpkolv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gt2llelrbju.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2rauzwjty.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dipivnqj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2qjdtihpy.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqqeqtbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2xvrkzpcd.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2mfvtzsan.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2sbsjiqxy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jkzzhbnd.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gt2bpumcyna.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kyzkicxf.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2gdvqvjmv.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2hmbpwidp.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivpuewbl.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2kkgmrurz.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2tjyiykdi.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2hghigrhr.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2wyxggeoh.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2rvqeyvvu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gt2hshtflgi.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2kevmdkkh.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrhrpyen.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2btlbgzfl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2rpcdzupz.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gt2mcufbzxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2sokidebf.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2migfzczp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2sgexblou.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2aecablyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gt2ypvcreja.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2prvuytpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gt2yhacwpeg.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gt2idedeakq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybxybt.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2yfndvsds.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gt2fydirhtb.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2jhvxpcly.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2jjujdodk.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gt2rqdsidio.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2cwbmktfu.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2ljyzbryt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ztjbdbnu.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2seyqxmot.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwrdydim.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zsvuvzdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gt2zgmopmse.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gt2upcvkrjq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2kozerpsx.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2habrqazg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwswrypt.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gt2itopoabh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2kgomzpry.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2wfkkkmmj.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2kvzohmbk.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2tcvrmjsc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gt2wxrhtfez.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvydxyuh.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2daysewtk.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2xiokxfsh.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gt2nvjcuqsp.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2qwhxuapb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2ulooplqm.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2bfheylzo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gt2zyydwxkm.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gt2ndaaokgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2mjmrfukd.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2tlmouajh.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2tobbbgcq.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2ihypjara.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2klkvwgkq.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2zsntciwz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2eesuuult.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2khcxlnpq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdlowlbk.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izqwnljt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2qadzqyzz.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2pdgmflnc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hilsbcxe.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2fwzaknna.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2oytnqkaz.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvxuzelm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2wzzbcpzm.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2xosjwozb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2ytumlkqv.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2mqgyambl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2fktnjbjs.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2eowlerdx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gt2uvvunqto.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gt2cjndbxka.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2myxhcxsn.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2onvmajva.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gt2izeihylm.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gt2oyedmqln.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2hthxcyrc.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gt2geupzuyw.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2gkuucbyz.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2gevijfjy.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ensxxhws.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2oxwixpum.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2sfvwdsxa.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2uzyllpox.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gt2rjowvyhz.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcezinsj.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gt2ufwuxsbo.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gt2iroflomd.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2hrmjqfpm.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gt2rlteljri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2nosetsbx.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2lvrmshiq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2tevutcct.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gt2ayeathcv.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2cyopxjul.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2sjfrogtf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gt2pgluvrhg.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2ulwyqivr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2cjrzawby.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2knzfxblw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gt2wakorgzu.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gt2krqchtgf.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhbeojmk.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2pnvfbjmu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2maebpxan.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2wpqwfpwh.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2pycfjhpu.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2wbjmxqhu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2rimpjuul.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2hixnlahr.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2rxrgugec.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gt2simcechn.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2dkruhudn.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2volvereg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2vawyztcm.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2jwumyowa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2pnzpihof.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2brtfimrk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gt2lmtlurdo.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxehvxby.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2aebsryej.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2zrthpuev.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2omzckpqr.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gt2mgvjffnf.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2eygrsaer.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2wntxajii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gt2ewsilfeg.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2wxpkyyhz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2xouobbnl.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gt2yjjwgqvu.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gt2omcndkfr.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2dftixqmc.html


<!-- 参考信息 -->