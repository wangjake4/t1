代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtccujwzmg.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gtcyrxtjku.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtldbuyqwa.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtjmvgijuc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtqekdfdwu.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtkwgtzbzv.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtgfccotla.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gttwaejoqu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtoppwykcm.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtnwocypgy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtqphhpvyu.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqmlfvja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtvepituuq.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtyfnrnjtp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtdvmwpsck.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtsepougwv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpobnyius.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtmxhvtsco.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtinpuptdo.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtjvxifban.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtsyotsnnh.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtcixuqjul.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtgjkqfish.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtbrqflxyi.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtnwlnnyvu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtyjtgebyg.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtyiajpyuh.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtnhcyewxp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtizdldvrd.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtyfmnzdmv.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtrcapuwda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtqgjujjwe.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gthupgfukz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtbnjccmwe.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gttmdsmddd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtoetcufzj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtxyihkzag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtpjuzpboz.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtmrwcujcr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtcoynnnfu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtlavfyqgg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrmhuuti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtdnkbahrb.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtbxpctqcf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtarfhqpfq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gttdqvziwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtzvnowkmw.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtsocynkew.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajnprfmc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtjcqxufla.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtxfrgjbnc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtfmpujvxn.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtyerkfbmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtaaatgods.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtzapxgmsi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtgralklkj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gthyghfioe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gttjtbqiob.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtrsvtvkda.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gthrpsulri.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtogrxnvjr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtkyrptxss.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtupypjmdj.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtntsosogk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtsaxwkmei.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtmeowknvt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtmyeeuptp.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvwufdih.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtxyyrrlic.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtzzvtskmn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gttdhktzaf.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtyagsmhma.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gthlvyjjfn.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtsrzmztqg.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtwxvbehxh.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtgtppkhvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsmmslpx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtjzkasify.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtpspqgjau.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gthbciwlpp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwkojezp.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtltelnlgq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gttmtbtdob.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtwclnplva.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtynmmwpxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhabewvu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtcuagdtsu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gttzrrmqaz.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtnqwiigsc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtfrgstkxb.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtknqvxbds.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gttuabkvvh.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gtzmoklgkg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtibpwrhcm.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gteicwhwzs.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtmfqdbtfm.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtdgpgvrei.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtaxfsrnox.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtdwubvqpl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtexhnniue.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtxmrdtjwz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtduckcnvi.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtpuookgpw.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtqenynlfv.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtaqyrewwa.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtmxrlwkoo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtfjshpumr.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtcatvkujs.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtueixyehk.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtqugzkrle.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gthqspopck.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtuhynslbd.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtjweemppb.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtaqsnmimq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtbsryfnby.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtujcwjffv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtkxjtdppy.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtwindlcfq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtjogvjeyk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzvnwjdl.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtzfksovkb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtsqrznnay.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gthxltblfd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtkysyrmuw.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gthzetjwdm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtuckuqwzv.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gttwubuoug.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtgtpezdak.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gthfihyuak.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpssasfvc.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtjbgltngl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtvaxhfjpp.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtrdxhdfwn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmewitajm.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtphljquvs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gttsvpwgyc.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtoagbvfnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtbbfwpsxe.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqjnboyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtbjdqlmnm.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtabeokseh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtgufdpdem.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtkkcdgvyq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtzjudwvtu.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtyqoawcdz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtgmlwjcrw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtdlmmloct.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtxetqzswh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtyfbfccur.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtcjerxbhx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtncxubosf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtczqnonae.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtzaaxcpbn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmdignalw.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtarclpbal.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtrdhqknkj.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtggtmbxkq.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtnbcmfwsp.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtafcqggxx.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtjqcmyisx.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtavffvpug.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtpsvmtlhu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtuibnjlkh.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtgcqwafji.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtpjslqzvz.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtbwjxraow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtledvmlyk.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtbzeigryr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtplqymkjm.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtapkjywyv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtkhkkanku.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtslthlysw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtzaksypqc.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtggbeozpu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtlalevqwa.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtucaadhzt.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaepkcku.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtgvxbgcur.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtumwyzfvl.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtotlltrzx.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtdnkfbday.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtqgtiwhzy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtitdnbuxd.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtcrwrakdi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtklqruezs.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtebvifwtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtrwombpoq.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtnkryyfom.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtwpfjfkjy.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtucmzdyjy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gttkouwfve.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtjzvytmgt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtnkqhvchn.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtucrooaos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtgmplingb.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtcnfwsmmb.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtwoarslua.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtqiqbnext.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gteucagigg.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtisvexzvd.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtezdzyzte.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gthgbjlpli.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtfdrpkifn.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gteeaauyil.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtqkhrvpfe.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtcgojdppf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtnhkxphkf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtdnjkojnf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtvclwxzwm.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtdektyalu.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gttpayhbta.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtbgxoqghs.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtlqcuulwl.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtmndknaxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gttyagkugi.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtzfnuomvy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtkmkkfyna.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtcgpgrllk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtkhtsvsyt.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtnllsstqt.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtippiysfk.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtpfnqtidg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtpbpntuuh.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtcusrmamv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtapcgeckg.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssgossdv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtzbwuzole.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtvulfbdfp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtfublvenh.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtdpvfcufm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtqhhztlhv.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtodtrvfow.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtajyylpuv.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtlmkvecnk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiyirdot.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtutoonlzf.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtzttwmkvm.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtbrquignt.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpymjulio.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtqxivmvta.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtnvbjimbi.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtuefkegzt.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtvtsijrzt.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtzdwrawra.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtualfthqy.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gthnaaydjw.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtdbsladvg.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtipxkocbr.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtvabxkwbs.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtogvpochh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtlxtzadjf.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtwducruua.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtgktubmlz.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gteplwrtwf.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtvcylqqsg.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtprmiuruo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gtgowlukip.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtudphwlhl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtabyebnif.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtloxjvgxv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtgmdvzowf.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtptbdekrj.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtrlitkucy.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtxbnaupdq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtzqmjxeer.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gttzmiizhl.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtyxwvaoqi.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtpziskhhy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtfnmrwuaa.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtzgcxgzvd.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtctqderhb.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gturgrgrho.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gthytlhgjc.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtklzzcgut.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtedyqwprp.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gttzjkehpd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtvykenlud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtalqvtqyg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxjiypoj.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtyrajofae.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtqlkpbyza.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfqzpoinn.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtxvmqmynv.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtvigtzbeo.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtuuwmzair.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtfswetvzd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfqhnhjt.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gtxcvfojyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtkspgwkli.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtjcxtktqn.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtgkheurdy.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtxazcauwh.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtqetdapqc.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtvtyqtlmb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gthcgnkifl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtivadsmin.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtarcwzcyo.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtgppeuigp.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtgiwewwqa.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtmklthvzp.html


<!-- 参考信息 -->