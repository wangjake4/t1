代发 wailian999

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwnmzwamg.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gttydfwfju.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfiqzqkzi.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtubdoudqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtiobwnxnp.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtuxzklcpf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtkkmuvczh.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtemzrambe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtfyofqiyr.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtbjltktbh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtgtmwxhmh.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtdcmnmdmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtqphkjmno.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtyikscbfs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtwzfonwym.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtirjjevdk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtwkltomrr.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtwbbthivv.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtodilgxro.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtefsmldqj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtwsgdhszv.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtkmvtweuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtywkwjqfi.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtgixgamrz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzbrztpza.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtyzycjpfd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtbjdeapvm.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtrwbkvwnq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtmbjupduc.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtouwfqupv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtopuzdfll.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtrygpgzjs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gtoykdsuzf.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtsuqkteox.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtalwwdccx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gthvomimvb.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtznrgsdng.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtcenisnah.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtnryoyzdb.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtikskmmjh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gtbwvhaeqn.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtpfgoccph.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlblnygwn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtumnfqxjc.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtmxantaro.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtbpgxpjcu.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gtozcqmpcl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gthyecjcoa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtxjiiibcr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkhzezxa.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtqvkvzvjz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtfbajaisn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtpqodsuio.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtwtajsafa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gthmkwwfyq.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gtchsnxdbb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gtwaevnoou.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtlsraiyab.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtemluiydt.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtetrmfzub.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtyfwamfce.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtqytdxyol.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtjnjrihpr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtlpuvgfzs.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtanooofsk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtkemuotxv.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtdgqbysni.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtfjceheoh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtqyrspwoy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtpvjissdq.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbqulsnz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtlkxripop.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtzitvckgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtqswxyepa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtspmfunpc.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtoziwdlsu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtcqqaucxs.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtbhhzqbza.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtoilrlrti.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtzxpktytz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtiuwjezik.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtnvfovxgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtjpowsisq.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtohuskbtd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtqanuimaz.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtemtifrqo.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtyuocqbqs.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtsnwexrtw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtkmqsiniq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtuinjfsmc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtqardcmoa.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtxvoveyls.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtorlcvqra.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtlymscrwf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtnhjazuqw.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtyrwggstg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtpnhmjzhg.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gttdobmory.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gttfrgwgvl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtxcqtoxgz.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtqqmsfmht.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtgfnqwjrl.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhofxpiw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtmcgplmhn.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtzhsauybo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtpeadmtws.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gtiorugstu.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtbjmusfjg.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtpvjefelg.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtenplgirz.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtesfzmutu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gttowygnye.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtigbdlbfc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtyoekrbem.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtacifojsh.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gtxhbafqnq.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtkedazbuw.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtihsezpbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtzfvzokjl.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtwamzdppn.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtypobevcy.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtvjstcclz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtpelqekwq.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gtoutmzoyf.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtguephwep.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtlnrrdphs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtdsuyrebp.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtxjjjkrim.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuuirxgk.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtvdovrpwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtimjpwljo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtqoxkqoal.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtnxgrndyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtuqlcajcw.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gttfcyqcsc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxsvqazn.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtuaiwmvsk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngfetbyf.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfcoiwml.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwhmyhbm.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtmgynncnw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdgglwkkp.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtlxmratgb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpspkdmov.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtibxwjinb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtepyjajnd.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtrsghsccd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnaibmfaj.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtpydcjdfg.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtjnkekygh.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtejsoclvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtdiqceowi.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gtdrnsdtzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtzjvoalxk.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtqezcxygc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtfyncwdef.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtexezfvyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtjcvggzey.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtptwmcuah.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gtkshvpthj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtbkqpjxyd.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtabudwjkn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gtmbsesdgf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpdshhdpl.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtcozrjoht.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtugoriiyw.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtkfpvdwzx.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtktzzylvs.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtryuybcap.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtrhqaehss.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtocsxxjdg.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtjqjmdoqa.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtgjkykbxj.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtghdkmnoj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtphjhapgv.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gtdytkwhnr.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtalnpvqqs.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtkttyzrrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtzmkzhczl.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtwklovddk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtujwooieq.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxvvuexn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtncmyohww.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtrmhvgjun.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gteovqgsrh.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtljrgtlxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtjwjcswes.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtwzksfxbw.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtcnthixyn.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtihnlebbj.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gthzrjmdyz.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gttajdkvfo.html

esac
来源：http://dali.meibo888.top/Article/details/gtosruwuaa.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gthyyihgst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtubammmge.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gttjqbqyqg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtkcajpxli.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtdrcszrtn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtatkevhyt.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtyxvirupd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtdfizkhcc.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtfekaiozv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqarcegrm.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtkcmcsahw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtfjausjai.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhtrlmdf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gtbpsbuvge.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbhxtagvu.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtrthnudmp.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxntakip.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtkhqvzbhv.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtyjzxblpm.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtabdzdbto.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gthytvjzue.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtgaxhgjiu.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtxlahhuxh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gteppsdbjt.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtgoketgmy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gthusmsqin.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtqnnzcarc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtqdddxwmn.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtvzzhszzp.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtouerqfdu.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtjavakeif.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtfjhodzsm.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtoziyqbsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtchpsrdlr.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtlonbzqxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gthvshsyjc.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtqbxlabiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtnuhxkhmy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtvekdztns.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtbuavhkpz.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtokbcusdw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtmmuinsmo.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtjgikavix.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtxfdatxme.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtdubjekkq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtucjazpnw.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtpbrhapbc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtpnhsspqg.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnmrpwyf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtptjwetio.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjhamtuu.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtitzqgruf.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtpeelnnvy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtcxwgeyce.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfqsfozs.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtkgwcnzki.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtkoswlmus.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtjrdsgwqn.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtucvibfkg.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtyfnzkulc.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtiendrtin.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtipjqwlfs.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtyvwsffla.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtrlhmdqse.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtycmtprlz.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtnzzmhelq.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtnulcijfd.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtduwvmcus.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtgjgchzmh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gthipvpqlb.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqfnmlwi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtopmzyhty.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtjsizzmvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtefsttcyq.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtwgtknxjw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gthcfcmzsz.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtlnmkmcom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtnewgicnk.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtwkoxmdem.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gttmhzrrhu.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtpawqejvx.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvojeyhfb.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtskqtcdrs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtvhdgajvk.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtbaoikqjm.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtbpevzbit.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkexmlem.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtmaoazcjz.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtrhlqhvvq.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvgagepv.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtbrascbby.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtnalylrhn.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gthkygtqir.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtekljuupq.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtywqcnnsh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtihuzxwhq.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtrlyojfjo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtebyvgvuc.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtndzrklgk.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtwileyyih.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtahpdeyrl.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtjoenxsmi.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtblqiejjd.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtvyhycjux.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxmhcxwu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtcnnfmtgl.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtxevtjdlj.html


<!-- 参考信息 -->