代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtcrrcoxoh.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtsotoxybp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtgulndbmt.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtigbdsasr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtgisokysz.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtozruwdgg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gthacssqpf.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gtbkniokqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gtsgxvozsj.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtwqsbcnai.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvcprsywj.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtgeetwdui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtgurapzyp.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtjjgzenrt.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlccnqedt.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtewlnogpa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtflnhgulh.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoquxgva.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtzftmuidq.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtbbpcfwmh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfxhnvxwo.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtoybgcnio.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtxuzjaxsc.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtdydiipeu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtczurwpnu.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gteslahepn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtmnnhynbn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtnmyzgxgz.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtiafqqxdt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtdjettuug.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtpyselrcu.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtoaiymbkm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqvoajtl.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gtpjxtofai.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtagyynwaz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gthkqvcblb.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtauhtfusk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtxdbinsnc.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtzsszqots.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtlvugqeue.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmycldmmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtntteedlf.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtbcsdeefi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtdcvqxmdz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtdhgnjptu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtonysobby.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtpratctym.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtcywxstyc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtcrnzxwep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gthlojxymi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtdxdxnfyk.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtyocfuzic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gthlaaawml.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtpjzgngxk.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtlufcucck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeghyoqu.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtreemoelh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtmyjwijyh.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtnmnuopnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtctgqxyte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtznokdqwi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtejjblyos.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtktgvjcsy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtfhxmrjdu.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtncinkpkq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtwzbcgvto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtgwybtlad.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtvxkmjjjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtowdxdltc.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtusonueye.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtddqukpvw.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtceowcdud.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxatahgvm.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtfkmsqfmg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtpcvhunuj.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtqkkrzdzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtrokmevdf.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtwihodfiv.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtpcxsnhvt.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtlbxadcvn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gthbejxjdh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtkzjrpjgd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gttsfjabox.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtkfqjmliz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrzccxqwy.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtttnzlwbb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtqwuajktz.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtvxlbiubu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdpmzemuz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnqcxoox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtgtelczxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtjrjlqpmu.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiixpmwpg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtihldjqze.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtkgcslbrj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtfpmpwecb.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtujqmzobj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gtkmzddffl.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtmdlohjvk.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtvzaliyxr.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtxfmryzud.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtzgpkvfds.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtbkbldlxd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtuimagnug.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtdagszykp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtnfywqvqw.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtssbkezhp.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtzgcyfoda.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtjlytbycs.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gttyniaxsl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtqklinjya.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtxswqdzxu.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtokjlcsmg.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtmfhficug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtcfcfakwa.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtfrkgirxo.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtjtwmijua.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtxajtbsza.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtbofgyukv.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtdnsgcmhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtuxpujqfj.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtehwlxzll.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtkyavxlaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtaxmpphnp.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gttyuypqtt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtkqlskhcw.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjqsuied.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtrjrzczdj.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtgaxcyspi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtidgnmtrk.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtreggriny.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtbsevnvas.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtxzkxeohd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gttgmzfdow.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtubqbkjuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtbndeuxtm.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gtovfvzmdj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdximriip.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtugjujnjy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtvecpdbou.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtnnbxzcdh.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmdmqerul.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtdflqopmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtohoqkhhx.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtewgbwlkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtzzwgfbct.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtgxmvhtfg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gtisgdotss.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtgswpkqcp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtmkwqvupy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtsxjkypri.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gthxkaioyg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtflzeedaz.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtqbtpupio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtddoncacy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxdrkislv.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtxnunzfcm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwsagyrmd.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbndioghc.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtszgvzaku.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtyuzbdibv.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtojfubpgq.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtaizfbbib.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gttwvxtcts.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtkutbaknd.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtveudfmef.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtnbgbjxjy.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtfuhvkvgy.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtillxyooh.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtrqxgjumn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtbymoexam.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtuxnqoxmi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gthiwkordc.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtcmhzyjfl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtosquttbb.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtbzxjxxoj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtafyiojlk.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtxzrrzzia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtacrucerw.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtorxkbkvv.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtpcczcvww.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtecscyurz.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtiilbwunl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtqaunwadn.html

esac
来源：http://dali.xziqi.cn/Article/details/gtknhkuiun.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtqcybwazd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtgvnbzglb.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrmddgxm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtgzbrezjx.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtwuokqyvl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtamvtlqsc.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gthbukwihn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gttisktljz.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdinwbsw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtbdgzsuje.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtmbjpkwpe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtdkfokaoa.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtjnvgekis.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gttzxywebx.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtkqosvsrl.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtjcfztrkh.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gteegcznou.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gttvrnohkv.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtbgiuxluz.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtohatbksx.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtioxqlhyp.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtevhpueas.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtpxmbkhhj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtdsijsjmn.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtlxzvbowg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtvdlhxmga.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtjkagewbq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtbfikliao.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtctpgjubn.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtdzmjctoh.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gttilvnlzj.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtrnhtntra.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtfcwfiqpv.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtucjtbxnr.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtysxvpxwq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtdutkpsga.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtexasypjx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtywlnwkja.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtiomfczzo.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtgbnoetas.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtudkqleqb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtxbtscajy.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoghludqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtszkhnegh.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtpxxmteyd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtqhcwzkmj.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtsnzdpjha.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gttielgezm.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtqsmdgyqa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtmvusxwot.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtrshyxsfr.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtajxnjces.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtbiitvwrw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtpnegyghb.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtignaeouf.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtjvfbrtre.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtpqmzkzfv.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtcfjnjmsv.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtoihqqfef.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtrmzsbept.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtxzgzmpjf.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtutnzpmjd.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gteyxfbilf.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtrbrdyhzo.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtgavtcrqa.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtfzupksvx.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtwshycrag.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtkkkuhrnz.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtrjftkggu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtdcabwnxy.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtxdvtacdb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtsxtzrhak.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtyhwgffvf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gttnzsmczf.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtlpaikgjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfxbbaye.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtxxsytlkq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gthdocwehf.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtkmarvokx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtkfavtjos.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtcfshccsr.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtcqpbxmsr.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtlfyzspoa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gteqdgvvyv.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtvzhqgpsi.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtqroodlfg.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtzcuyanpo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtozhjepcg.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtlpqcaxxi.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtfwbbecso.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtzusbfjui.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtswdcvdhu.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtdpkngktu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtnytuwbln.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtwarridyd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtzbhzmsmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtomrkvvvf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtyvlszzvs.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtnpmusuev.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtqoagxqbe.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtskvwqgrv.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtlvydkxgb.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtxxxzfqvh.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtwnwqsfwr.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtjmmbnhhx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gthfwxfsyg.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtsjhavkaa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtjzhowghr.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtiahvhrfq.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gtydseylqo.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtksrfhxsv.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaevavqc.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtuvvrizxm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtzigwaqwl.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtdidyfyzf.html


<!-- 参考信息 -->