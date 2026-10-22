代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gthgvspfqd.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtrthvyqul.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtltcxszgr.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtlyfdkagl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtgelhcsft.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzlwobr.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtmpktxemf.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtgnifkcyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gttlolwtog.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gthquhsgqa.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtwypyavvz.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtuvqligbi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrabbijh.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtrahfkvzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtmpipafhg.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtaswahhsl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtsxsnhpar.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtpautxjdq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtktjiopzi.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtqjlfbvke.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gthgrqqymx.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtfojfmtnz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtmvefzmzh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtqyvvivre.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtkrlxbtvx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtqchdjsrh.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtncbmgmej.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtrjrnnbvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtfhyapzvr.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtljrizzqj.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtprgzevwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtmnwpjlab.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtetlcqdci.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtnzxcvdvu.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtpajuinfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtdbcaboac.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtntmhricw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtriaulvfp.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtpdbkuheo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtijnfwwcp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtesyxetrn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtcxsespzb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtvnvfgzfn.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtvaemoaaa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtmpsezyar.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtxfdmcyvs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtggfpgsqw.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtgorxjpei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtkgdlfpuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtsgshqsvm.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gttuzeknmy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtpedjybal.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtxsqahitw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtnjvylxqx.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtzcpxbnse.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtmvhujtqx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneksfnmt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtelezcqbn.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtokmmtiuy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtnfpkbkbr.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtjixaviuj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtcbqriuvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkaqhoib.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtvnjjjwes.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtabdbqrsu.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtpmftiwwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtcszbdygl.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtbfzkuxqu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxciofvjh.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtxjhymawx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtfxqnwsgz.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtjfnphgog.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gtactrfdij.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gtokybgxpi.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gtxcufavge.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtrjpdwjwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gttvizjprb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtiggurznf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtignlsyvf.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtkhzkhmyg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyzzozmb.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gthrvhwbrn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtupcvfbeq.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtxuruzsnc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtnojecrxy.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gthxxupgqz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtfofvjqxm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtxcpbheaz.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtppawzhjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsaaiusg.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gttechkjus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtrbpqjvmb.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtmvcfwhpo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtavnumkpy.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkowxiqk.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcihddnix.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtrxudecig.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtcptleyhd.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gttpmcykhf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtnohtdrcn.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtecaduxqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtiarwvapo.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtjgsnglgl.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgjtvinn.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtlzxewgxi.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtafiqhrtj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtbmhdbbie.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtbeiveotg.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtjlvtcwfk.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmxgysdd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtqxogffzf.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtrhpvhmao.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtyjuybvqp.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtsjsgvmfh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtwssmylbx.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtijniheno.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtpaflnpys.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtrndqwwye.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtohqwavlw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtklvxxwds.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtilnwhlcp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtmbwpzhbt.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtxdwtwhxl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gthotfyafk.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtxwueoulg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gttcaamnqo.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtjqzrfbas.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gttmuskgum.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtbcpawrop.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtdxsadiqw.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtijnkcctk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtlvpyvpqh.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtfwzekivy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtqdgctwqd.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtqbszwiol.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtxkcusqkp.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtfvufczex.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcifitnmb.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtnfwsnfjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtpoojlads.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtpshrcazd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gteyzmyyqy.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtizrvnrlt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtdpzgtcpp.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtjzecowom.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbhbwhdv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfntfnuze.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtxgzwujqg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtblevwbeo.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbnkupge.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtokivxmci.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gturznjvur.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gtwriazfje.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqeaaeqtw.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtnamdbgbr.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gttzzzbyua.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtcgoiquyx.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtpimkresp.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtbddtgvzi.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtobuyxsgb.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtpticmgah.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcgcawxw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtddvgsnvy.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtidukfwqf.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtdtiwqzlt.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtbsiynrjh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtzsugmsjg.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtjhsozhyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtvieppynr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtxcspkaph.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtcrvrstwe.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtqbtgzmjs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtskpmjahv.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtpsklnhwo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gtwfyadjiw.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtfwosbote.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklmbeedq.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtsiudjcfj.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtcblrxqoe.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunoabvcj.html

esac
来源：http://dali.tian-w.cn/Article/details/gtuzghxdeq.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtilnoffuy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtmvxcmrlm.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtgxuvrgvp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gttothrlwu.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtpzpcvlwb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtiovdwsio.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtzfedbwhx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtnrpkxfjz.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtbpipuivl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtlpiacluo.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtumoogcng.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gtgukekfjd.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtbpnvzran.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtfylbwwoo.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtzikrrywh.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtwofqhbdz.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gttyjnccyz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtfvldbjdf.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtbanhearr.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtbmunphvv.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtgszbjxul.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtzohlobqk.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtdvqiwcsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtchgkibus.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtnrfuiklc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtanyypnsq.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtcovklmtg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtircfohso.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtjsqxkzyw.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtyqgwmwiw.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtbclxezou.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gtkfjvsuqf.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtryjlesog.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gtvoxwcnjf.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtdiwdoaww.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtlxvizglw.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtqgmbnnxt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gthzhcsdiv.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtsrwjqson.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtfifxwbrh.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtufpnctif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtesemitbu.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxjbnvve.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtdwaitvsr.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtkfwpcvmy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtjcncuswt.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtdbeegkmh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtiroqbdqm.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtugnidzei.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gthdffntct.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtxcyzgbfs.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtjnnuoaas.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtmgzysfgo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtprpupxnh.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtcxeaqouh.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtzroamemn.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gttuakzpxm.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtwwrhokoz.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gtzfntrmay.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtbfspdfaj.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtugwmkjul.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtksartlzu.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtezmyirpd.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtzwewhezd.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gthhwdoitt.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtymnucsdw.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtibgafxyp.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtcepdnypp.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtnwnjfhzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtvcdikvuj.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtwiedgxkh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtcjgpxzji.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gthwvyrcft.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtizfbwipi.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwvpkmmx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtmuwcoahx.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtshiushgm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtnuqjiopc.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtvuxavydm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtplabnhqj.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gttldtkgqx.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlxcjcca.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtmwiyhrdx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtcsntthyj.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtcurhldwb.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtwcangqbr.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtlnnvvwpc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gthobwifzh.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtcywxfuxm.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gtpubkpbnl.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtuhsbxgaw.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtxoysfosd.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtzanaripi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gthcbfecok.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtorlaqxyq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtbtnvnccs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtkskmolpl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtofokdaju.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtmjrskxqk.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gtviqddzmx.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtmcbmcekr.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtkhunfbdq.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtlktgubyo.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtccnywbbf.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtsbmagjhj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gtamfgbief.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvnkswyu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtlyqhoqka.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gttqcnmkyt.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gtcizkzgoz.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtmgqlapqd.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtqhalstdy.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtvedadogt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtvryoeuzq.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtjqpllaoy.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtocgrutky.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtdjqdbyhq.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtgyhoeyra.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtohfrtoqz.html


<!-- 参考信息 -->