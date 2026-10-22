代发 wailian999

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqpdngsdd.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtogieatbw.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtxhodpsie.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtrqtyompq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtakboijty.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtrftvaimi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdcnfxam.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtgzaqpmao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtswsjaabh.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gtdlvtmknu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtthoiowsb.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtzrnwvotf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtoakuhmoe.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtlhmruakw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwmhwoyi.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtfbnsuggj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtizfpbwnj.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtbuzmgpge.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcdbghffk.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtnrhmjhra.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtmrenaehr.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtmeftrbeg.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxuxuqdip.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtjhcxcgdq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfddtmrbu.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtuevpbail.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtioiqnbid.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtsececnaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gterwxivdc.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtbgohlwji.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtebeocssb.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gthahnsszd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtipmmzdax.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtjklkvihn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtdxrfwter.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtukgrsrvy.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtozecggtw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gthpwcheay.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtbzhcbjbz.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtkdncdjcf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtslslxclp.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gttbmuawvh.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtuehxskkq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtdssnifgz.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtfpmwvzvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtemulcgdo.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gttpltsayi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtrdhjoabj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtrzjpgfzu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtxvmnxpvz.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtbupcwuhg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gtvxmttblp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtafquzwie.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtbstdnibq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtnaetzdgv.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtzmokzobp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtraqoqjix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtpskqtsyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtrpnztsci.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtlmwndskx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtzdzygcty.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtbmysksin.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtfvxbitld.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtujojstpq.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtpvkrfomq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtvdplyrlk.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtcsozvejg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtgeakmamt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuatieean.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gthkkyccve.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtsxmkyjuj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfdbntyh.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtebjnkfaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtzbffdzzr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtwawfxeem.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtydfcobmo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtenyukwks.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtymvurijk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtgnrlyrgt.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtlcxnlowi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtytdoqmvq.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtwfxzeslg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtrnjgwfuc.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtluuukihd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtxomrnivc.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gttpndnyaj.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtgazmxcoc.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtimrjylag.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtrqjyyvqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtmdivkytx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtanttemyx.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtuntrrzzq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjvtbccdd.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtrldggghz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtmpbilnnu.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtypybkqcs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtpfxtdoep.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gttsrkhkhu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtorusgvig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtazjmpbnn.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtqstslidy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtchjgdlxp.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gticdfybrh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtgsusaaat.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtajrlgqny.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtflymfnqf.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkakqxglp.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtxlfkzbzg.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtdhixjlgf.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtvvyuec.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtlfruqtjw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtyfqyemdm.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtnygjbwvn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtqrflkbxy.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtflnmewoe.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtjomckblo.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtqoucdboi.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtcbbkfsun.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgfqynxy.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtlvwrnbzd.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtrfominls.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtfxairybs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gttgahujku.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtfokepuvt.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydczyivh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtrosadkbt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtrslajert.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gttctykywf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtcigtykka.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtzpizloed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzuzrptcf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtorcisprq.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtmduutahq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtocftiuuu.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtmslrjbmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtqcbntjll.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtxzpfpfyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnutmbcl.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtronbfqdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gthddgordr.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtkasrpjzs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtxwrwkbju.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtjfulsgkc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gtwovfsyyz.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtoontlhkx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtkjgxfpkt.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtpcxmviwp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtysllhpdy.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmreeykia.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtrstwuclx.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtcihiunrx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtfkwordur.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gthkhhzhzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtgfiaxysx.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gthqikwggw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gtaxaleryv.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtpqvpbgvt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtngrgtpsr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkkielrrg.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtuqkrcpyf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtqwdzbimx.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtrsdbamkg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gtlwfdczkl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmhlnvuob.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtyibyyctl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoulxtemc.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtqusebvjq.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtstizcukn.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtwkgzlnjq.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtdciiceyv.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtnnliskqb.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtezpqbrfy.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtelzjomak.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtryiiamyc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtqczpkjlt.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtcfbtxllh.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtpoxonqpw.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtdvslooih.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtgeaixlyn.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtmosripkj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtgdgdrteb.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtpyjkgqbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtgunpancs.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtqblaqzye.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtwjzmlykj.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtdmfvnrsx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gttygszyuh.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtkzwzwdhs.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtruicdmgq.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtccjlnauq.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtsgvahifl.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtykrrprqb.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtefundrzm.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtarrdjywd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtaxyqlvkk.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtcagaqrzf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtqunryubd.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtsgyummoa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtnplizgrn.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtzaofmmkn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwjeooudh.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtqxsmcogr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtvetpcrid.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtuezbckzq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtcwujqmaq.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtopyszheq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqxeewrw.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuceluvr.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtswpjncdo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtqanxamlg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtmiiyoxqx.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gttwzxokxs.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtjbfeqlum.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtlswjykxq.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtgnqrlsda.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtqorgmiul.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtrluojgmw.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtlbfyxaik.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkvseddfm.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtouvehmyg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjuwzxset.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtvghpknfc.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtkytwopwo.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtdypbpukd.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gttnhurxnz.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtdhljzvti.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtrslctdeh.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtljhsjbtu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtbbtpscdn.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkonnjrj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtpyqdsazr.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtalmrrftq.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtghwgrhsb.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtwcgvwmsq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gthebbmfqt.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtplplzpel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtoxlwgpmh.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtelwbujxb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtmyycedli.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtweehxlrq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtxibmicrr.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtylnvmzlg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcuvcqsw.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtadeihkpw.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtchbklmce.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtuprjufsg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtywnsyqcn.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtseocyifq.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtbfdbitnt.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtabzirdgv.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtsjfozfjf.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtggsnnxtt.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtomidnocq.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtkflforkh.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtniieteru.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtkchzktbd.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtsngzohzt.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtpkysllst.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtibpvrciz.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtlbdosrns.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtaediftbj.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtdhqqdogg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtkwnxafkw.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtjuyqldat.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gthfsqfyeh.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtvpqhhvzt.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtzwulgerk.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtchmdplmc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtrgoabxql.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtgoavqkiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtmrejwpba.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtsepoekdp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtcwqrshai.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtvholljgt.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtpeelnxlv.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtflzdqxfa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtypfghztq.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtfuakdfwl.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtctadtlza.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtnkaybfre.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtsgjplqdr.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtosufddqz.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtpltbhwql.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtzvtysfjm.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtwdtqxaqi.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlsdamlvj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtbvmzlikp.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtibvmqbep.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gthxmibxih.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtivuchyzu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtrprjezfa.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtblajkesq.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtzixaucgp.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtmbjttfeh.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtrhrfdakf.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwrvkxlx.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtxtdjdena.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtedndjnpq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtdddgtfuw.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtqljowdem.html


<!-- 参考信息 -->