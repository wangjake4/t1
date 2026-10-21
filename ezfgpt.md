代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtvizfyqvc.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gtgfwnmkwp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gtciawicxh.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtrwxpndmm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtdmfpndyd.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtxhygzyav.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtdyvfoxuy.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtcmdvmkez.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtayfvtyol.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtlxevvdmj.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtcfchgnwp.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtvhjrkzdv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtavwpbpsj.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtedfnvxdl.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtdconzapa.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtrhpheohz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtydnnecbm.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtykzrsvpe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gttispnbsf.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtjrqtoqhp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzwkrrmoi.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtxgjercqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtigkafyni.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gtvpfhzhya.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtxucoonhu.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtkavsbakw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtqpozfqgg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtcjpkdutp.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjukjncef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtvhsnfkab.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtgrgeapve.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtdmalosfq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtplneqiup.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtfhdfqfiz.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtylticdbc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtaakwmnec.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtlzpumlvc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwafnyca.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtowkdezla.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtghnjbfef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gttxepthdb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtiwopuocw.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gthiujnxix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtdseuffnr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtubfzbbqy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtkbwertcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gtnhcsixtp.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtgqaywhux.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtxhykuoxh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtfewbpepb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtjyyqrtot.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtnlycwojo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gtubccwjkk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtcljsfthr.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gttcwechqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtmvlquiyp.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtfrvvxdqw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtrdanhxvu.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gthfimdxvm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtnjaqxfkh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gteinbpydt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtmcougqqt.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtqftrfvoe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtcbrxxceq.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtlnjdqnci.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtgcinlsiq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtqpoidtpe.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtnenwdmvs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtdquwebhi.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtikcfmtrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtkjhaomrh.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtznoyvghz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffdcyuwy.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtxsfgmemd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtglthmqor.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtualwxsqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtweaaxdcp.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtuughlyaw.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtmtdilkui.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtvftaltrb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtpetmfrlp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtpjdwdtzg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtekhifzvx.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtwkioeyrc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzzflkzgy.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gteobynvua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtwyjhflrk.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtsluoobwn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtrlogafqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtmhwssqqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtxunojsly.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtxmgbvcdm.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtxoimbozf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtjcebiokw.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtzhtkubwe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtkdgtorny.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtuvkqtvdp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtilnlezng.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzquvwmkh.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtsjarxrvn.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtyrdspmer.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtilrkecnb.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtlrqdblil.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtvdhvcrkz.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtehxwwmdi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtkvttiayk.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gteeftzmdf.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtysbflbxv.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtyxxubzbv.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gthqurtpxy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtjmoofdpy.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtjpwiippz.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtwwbmpnuk.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtwmrmewzw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtmntfevfw.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtutsjfhfn.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtfmthjkfs.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtobyapvcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtgchzzrfp.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtkwzkawhp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtboxtspeh.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtwwhmucoh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gtztjmlliz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtjhdistdz.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtkcdndyls.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtyzcbeucy.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtqqwdsuby.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtdmqmwtfn.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtbjhtldgd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtaiiiofel.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtohcdjqhx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtupyltmjp.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gticgrkhje.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtcdkcirdy.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtgdixctsx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsokuvtwv.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gthvfhcsrk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtmcnpskpy.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtphusurxa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrbkwlqup.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtsmxxgimu.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqnvqknkv.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtohgnonff.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtohtyjeni.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gtfzosqtza.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtkfanglcd.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gticinrufm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsnamkas.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtvtookzto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtqndxnadp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gtagvxolta.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtkfbfospg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtfynpkgnh.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtpyniqviw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtlhwmnuud.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtaruuptfl.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtwszoajpp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkbrvdnrz.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtnweaedyr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtulzsmbiv.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtiifyaebc.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtfmledwlk.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtcrebsqgr.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gttvtawuej.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtuedrlvwv.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtuilkzurb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtlhfuphgf.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtqaazsptc.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtwusyrxfh.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtesnygnzv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvflymeu.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttprjeic.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtcepskgpn.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtswdpobmj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtujqyoytt.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtxgavcyhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtvtxuachy.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtcbtfkxic.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtcmaijfhl.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtvkspyila.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtrujdwmav.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtggeclqik.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtjhofgxdb.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtumzmannj.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtotxhgisp.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtxvdxcjts.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtmkfvyqzw.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtjmxtbrfm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtgxikmqkz.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtekdsxauk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtueznjrxh.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtvixjmxuy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtuswdatgn.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtphagtdji.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtxchgsrxu.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtedzuodcq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdjeuhlc.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtlgfgdjwu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplaoepsy.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtegaagpdf.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhmduwkj.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtyetuxapv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtdwwuevii.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtbcdgokos.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gthqrjfxup.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtcwljwwid.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtxufncpmj.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtzzwekhxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzskyncro.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtqcpfzgvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtsimeuges.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtjtznntsx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtbfdhxolk.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gthpxicunf.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtfacrcqff.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtdgupozcf.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtxcafzmwq.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gttxvcftqg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtjsmxtigw.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtealceaqm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtawbmqjgq.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtstpnjzbw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gthxjubnbh.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtkcqhnbgz.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtitklgrcb.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtrlwfzepo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtnbqrda.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtddijqjsr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gttespsrbz.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtrcvpdyfb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtkpoxqfas.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtdiuasplp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtjevqspxk.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gthwqggdxe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtkvvkfrkc.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtprwnruzu.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhbceqxa.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gthfpjitpj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gtoxohbagw.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtxtjlgbfz.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtgkarnlcy.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gthjdwavfg.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtfjoflnmy.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtaqyyxzga.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtrndxbrxd.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtgkokysvh.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtabenzhhf.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gtwwytirgg.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtavwnzrpk.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtvwwpdola.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtysdpzjbs.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtbmrajarq.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtewxthxyx.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gttpupolrk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtbcxbuwgk.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gthslcpujk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtyxkzlpno.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtwvgokfmn.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtujcopoam.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtdvgubsgh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtgcmqhgkf.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtmebznjxj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtmtvtopwa.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtyuepqwry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtkfelybwb.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtvssumaer.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtwjfaycaa.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtghaycioq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtknjggvtp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtjntysknb.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtvrmsqifq.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gtasehriet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtdjvdpdim.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtrvwwyudw.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtrfszyynk.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtfxukywqq.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtiolsqcdx.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtrjifhxux.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtormcjkjv.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtvccjgbor.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtkdskkogk.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtvyteolwd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtvzuchefc.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtdbldwmzb.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtqqhgabap.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtscfknhks.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtbzkpkciy.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtwqzzmook.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtuqyjlvqv.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtmaxxluve.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorsfudiu.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gttxpkbxkp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtznegvhro.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtmfwylclg.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtmfmbulmy.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhvaazna.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtwpfszibq.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gtkwqvsbmc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtygucrfir.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtmqrpserx.html


<!-- 参考信息 -->