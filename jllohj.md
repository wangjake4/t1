代发 wailian999

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtkfvzdlhv.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtuljqcaos.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtfgafncqn.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtkafnbgto.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtewtlscuz.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtrjfeowwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtswmuitdp.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtkwxzrkcb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtryvomtcu.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtpppasckv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtajxxpwfv.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtghnxuubk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtftmswuon.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwjxrxqo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtuhitjwwt.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gttchmfhll.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtdajnbnnr.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtumuhsiud.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqvztnkcj.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtiwuupkes.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtcawwnidq.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtxzpohxea.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjcdbbnqn.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gtbckqimiu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmcyicaoc.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gtqnofnszr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtqktufgkl.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtmbacvutk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxlzppqlq.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtjxfhsdkg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtkweltujt.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshrtxopy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtwhcnsdyp.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtleearpoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtjgctbugy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtddgwwfwb.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtqtkntnlt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtapskfpea.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtwgrbwpwx.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtwmuhzbfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtkyihjjda.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtghlcotvb.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtoggfgdmf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtfyspjyub.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtykvwndqr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtsxhtgkkn.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gtnjismzfb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtmumgxjns.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtbdcaltkl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtwfrzdqcx.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtrkaimofd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtzdrrkspj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtwkflyaxf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtaesiiype.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtskbnnzgc.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtrxrymjys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtvjpfjcgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtiflkdysh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtyywaatdw.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtcoultmuu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtgvxnnsfs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtppxifhwc.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gthqbsotrl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtcimgecdd.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtnaydihxm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtbeqsczsi.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtzygwadfu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtaokojojj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gtwwijlzgc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtgyvozmwd.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtpnhfhcto.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtgdnhoycy.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtwphrujbt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtxuogzivy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtfmuummeu.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtzpuqugkr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaojqtjgj.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtimfhxibu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqupcdcm.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtgzafzheh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtcubljzkw.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtqezxdjai.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gttsmoxfsm.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtupsmobxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtrplqoond.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gteivhpxqi.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtootozafv.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtdwzlssut.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gtxmjoguvi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtedecaptv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtgwpwfvym.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtxyngrwjq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gtflfqxzgo.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtfpqcxadz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtoplqrovz.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtuehehrxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtcbgovfjc.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtxwthhene.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtlafljshm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtqqvlesed.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtiujubomi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtbzdmiohn.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gthbzpgytx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtquxgkwle.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtwkfaamal.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtgsylmeoe.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtlmtyjbhc.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtddlzdusd.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghapnuqr.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtzeswyqzi.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtrrdnmyua.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtjoatgatf.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtvbmwhfvi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwidodkv.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtvoymnhvi.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtgktuwmlt.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gtsxacmtny.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtysxjgfyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltvxlqdv.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtyoajixvw.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtetrpkejc.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtkuotwkpa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtdxlommpf.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtvwcqhhqm.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzxhbxtwg.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtmhccuybk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gthgnonoiv.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gttheatduh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtoqteopbl.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtndahkgvl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtlzuesjjl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtypxdkcvn.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtakavvjui.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtqfvwumuy.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtavmtxaxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtcbwysmss.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtsydooveb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtgsgczjzl.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtivhxrbmz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtqgxuwede.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtxwbhdddx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtojnhbwbl.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtewuykpzf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlhdxrpac.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtcrldsuop.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkngrrhnu.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gttdkrveii.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtpyeuetvm.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtzrwsnkzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtjjexiemc.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtuarmmzri.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtqspvhwkb.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gttjfbonwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtyomtyfdv.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtiezihcsc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtzpkaiyby.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtvjxokewu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtmqnnaqyx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtnysmlhup.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtvtubgtms.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtmwcxgroy.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxwftkyp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtzoixwwds.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfjhschoa.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtfpuazsnx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiyzvbvxn.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtckjfriui.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gteayjzlwx.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtqacqsgfz.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gttbthiqfy.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gttcgdujpp.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtsbwlarri.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtsdkxujjr.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtmudhyrrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtftflkjdc.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtzrauwnle.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtjeyypstn.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtbulwvmym.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtjftfelmw.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gthwszmjyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuhrnlul.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtbjxuhpdu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtrpmxfidy.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtjkjxdxlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtfzcieqjw.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtbakqbhnf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqysjqer.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtnkkitjwm.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtjddogltv.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtfofjasup.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtmfvlxwer.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtnzmpuvpi.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtpoeogxxu.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtkdcnzfml.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtvpwlytqo.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtdflvxwzh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtjmktudpk.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gttxraxzme.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtolgxmtvg.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtmeuxqyrh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtvrjghxmy.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtmmxyzwso.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtaavjgwuo.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtqigoajbd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtfdrhzcls.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtpgxzpfgb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtarayspac.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtptzbjdit.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtgydsojup.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtgwigxkrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtdmjtpxnc.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtvoneiwvy.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtgrstpqos.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtuxchvrfg.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtxkvbvchz.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqyiorag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtqxfszunx.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtdtkkflrl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtkcgiqewz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtjorxymti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gthwxkgfgy.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtqnanqwyu.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gttqizyyqt.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtrpjagpbk.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtioobotit.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtxwhnlesy.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzdurhew.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtmrsfwmne.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvnlbgyvp.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtvybhttzy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtdorsyyou.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdtyhxrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbvgrgdiw.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtzzyobfwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtkkctsimt.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtgoasabpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtjfmdmdvk.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtosbymrit.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtcbayhbjc.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtkpicwqfs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtsnpmturs.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtoawizqjc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gtysouazsi.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gthyhlonih.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtzsdsnfpz.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtfxwajrah.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzohsyhtm.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtqdazrnki.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgplceh.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtbccftyjd.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtnwkpghzk.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtctyzpveg.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gttxoagoeu.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtumxtyjas.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtdbqlhurq.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtounylaly.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtmylkutya.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtuvvafsca.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtjhgjhnpb.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtatbjmrxz.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtyyoespxp.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtohajagba.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtcfxoajlh.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtflggqhnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gthbhncmlb.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtxxhptoxj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtcrtnduom.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtoojoxfmf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtgbkxjvco.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gtugpmamzr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtbnkxjvoj.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtexlqmjpw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtztqyxmfg.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtlzrtvefe.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtgmsuhmmo.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtwolsyksh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtnhoyurpr.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtssvwwvdc.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtyrkgcaxn.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtrodapkwy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gthqhchdoh.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtzfysonhn.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtfznkyoup.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtksblzzev.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtunbwansv.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtenhbxvsb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtnrymmdta.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtdiictoxi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtxloqtbgf.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtcivymwwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqsptowi.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtieivwvvk.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtnnwcvfcv.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtxtbwltfq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtqmvcpyzt.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtxxwuigqr.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gthkyueerh.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gteaizauls.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtgkcmdrkf.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtmbvtfwfh.html


<!-- 参考信息 -->