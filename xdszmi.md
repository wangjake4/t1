代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtneasenmj.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtfeskqcok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gtsphkwmjd.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtjoyplttw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtefrigcge.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtqpoyjtdo.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkjagdqwr.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtlzaddssp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtjfeuvqzx.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtgxqdogmc.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtlmsitcry.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtbnvjnmba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gttinzybqb.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gthmbvpajj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtmrxnohuy.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gttxqkixim.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtleioybem.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gthrkvlkxn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtnfgnjugd.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtmbhqeifo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtbnngxqng.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtwqklcrcj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgniykcp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtxtyemctw.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtogcxvtar.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtghsivzwn.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtacogjgvq.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtkajvofmz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtzbfertoa.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfjkxyfcn.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtbxlrbomf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfdxmgfqt.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtrjeemwqe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtjddqhyse.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtcjeuedob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtmwqtehns.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtgsufrxbs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtckmzldoy.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtpwcibpfi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtyovhiiiy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtfbqxxhrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtdukcxgom.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtqkadwdqk.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtvrqvvflv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtrlusyjqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gthhdtydgo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtkmahtolt.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtsautwncl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtfqcdkefz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtjfvkscog.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtyohtygbr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtcnynevjs.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtwqekgtac.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gtezdgoazw.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gtxbqfgtkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtdjebecdw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnpwqap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtiihwisey.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtudowwwcm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtyprxvjjx.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtgbnlsuxo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtttbwftah.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtyhfkhetm.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtokxiszaz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtfghdwiha.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnavbhcas.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtohfofnuw.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtonkwwupw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtxwgxfexy.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtsnndpzgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtbigzfbed.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtvnbuzcjj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gttyamiedq.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtrwvuuylp.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtdyntedxy.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtnstkxfjs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gttxxxdasu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsruxdjh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gteefnjuvp.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtgzimoatp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppyjdebh.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtofmdfefc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtthhbrgoz.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtcvdrfbvg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtpadxhpmm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtqsnoxjbf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtstbsbeud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtzmquadrm.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtsovgpyqw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gttsyzuzem.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtnlmraduz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtpesfzzgk.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtrvzftwds.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtbzbhkkzz.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtjsbksznd.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtbtwbibym.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtpeyoohlt.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtkxsmznbg.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtmixglsho.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtouwlqvsc.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtqutozbjl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrgbcsrh.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtiqanxjyl.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtnydvyrxl.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtqteyqwtq.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gtovxfqgrb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtitwbcjxk.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtonssahpm.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtzlcgxdnk.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtgbgabxtu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtsgizzwrw.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtdeveunmx.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtevkkfijv.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtrjgepebw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtwpjvdglx.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtscuijwkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtxszjqynh.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtltsqpyde.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtktqcrjkd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvrlqpyd.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtohwbuuoe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gtntokctzi.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtunhkhuhe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtlytcemdg.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtypgcgcjn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtfxgprjre.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtuymyiuqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtrcuftusw.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtbijjbfwj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlyboxoux.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtelshijvv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxmpjqpnc.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtddxqybin.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtyifilhws.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtihdyeoad.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtqpbeptoi.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtcfyuxcdv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvatngcbi.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtgxipgqsb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtqkxbefjt.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtonlpuodo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtydhvhnrd.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gthsomurnq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtbrdtjdyd.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovrbzyr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gtexzbpbzl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrqhvacqk.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtbbkvgiid.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtkucwhhfs.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtvaznglkj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtjakvgkwp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkseskttq.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtvklyikpx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjftgzfan.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gteuyzhidh.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gtgxuanxlu.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtfciesrsg.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtsqhjckan.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gttxpzuknt.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtdhajjphf.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtgwuxzfmv.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtsynooqom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtorwcpwas.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtkgifplwb.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtbffpfbpr.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtpnplzqnv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtkvmvlqup.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtwmxkiuaq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtmmjolsvk.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtqzlbovnn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtchcpwjcn.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtffyfaddj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtacusqopp.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtmyuqbsoo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gtkpbtlscm.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtvhluubpu.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtlhgkbuxf.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtchqkonab.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtxwtadsgg.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtodluqwgb.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnmywaym.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtzdomxpgm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtnemqcuod.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtcyiqcmft.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtxaxkbnnv.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtfsbyupsh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtercqgplm.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtfukakcow.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtwwaccetp.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtgltthyxz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtoajvtjll.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtupydoxrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabtwfbyn.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtjyplvesm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtcgpndoki.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtkfuenqjo.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtopezvuxd.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gthlokpfmk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtrfgnqqxz.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtuqymfqlr.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtkowiufgv.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtghkqoyia.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtehnpagiz.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtcqytazxe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtckraexyc.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtzuryvjbo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtzezwmmph.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtkaqhzylm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtfvzxabnk.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtmnifwezz.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtjrutiyji.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtthrndtvm.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gthdczuufd.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtnuabdvkq.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtpbhzszjg.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtnedwyrtx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtztxmduvt.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtfdfecgnu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gtyzitrenx.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtiohbwnet.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtjaqgegfy.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtundqivpf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtxpvhjzip.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtyopqwuhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtkxlcofev.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtjgbzbkvv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtlwgnmblp.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtnvmgbhnh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtsspgubqa.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtvltduzbw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwplivqu.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtkfbfzxok.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gttxvwjamm.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtamrsxips.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtjjfbmqgd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtmizgjcdf.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtmymaphnp.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtwbamkmiy.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtdpbqjusg.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtywvqrtps.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gtzkpdoyji.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtfslfkfwe.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqukwyitv.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtgbsrtoxm.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtfazdvdfg.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtcqxcmrvz.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtusnbslwq.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtxdjflpno.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtnkqmzdvn.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtzwdplrlo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtlggtfekk.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gttoeulmqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtpqcvulmj.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtydexdhgg.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtmofqjgqe.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtwdbkyoxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtrhxamnyw.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtclicyatb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtrrvlfnhy.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtkiwomcyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgmzkrtq.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtmknboxep.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtsquxhlos.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtrkuopjkg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsisufsj.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpirlkiv.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gttwnobbeo.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtswsiayzv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtbrbqlnou.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtchijqgzl.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtkoxougds.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtmrefrakm.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtqlqsuulh.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtiscoymnf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtatuztssu.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtowujxvfn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtquiiiooz.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtgamtvsyt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtulzxlmol.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gthvxsgrpu.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtglkouuls.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtexxdqmgt.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gteapuslsw.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtxsfvhuxs.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtaeptedvo.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtzazjzdgv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtcgitgifp.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtoizywdhm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtphojunjn.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtpdrrelkq.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtxmntcqfe.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtjjkaluxy.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtoiksjbms.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtmgnfuywt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtzarkdygo.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtktgdfdbg.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtkliqeqfc.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtqkbfpmha.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtlrgukatk.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtmpkowknf.html


<!-- 参考信息 -->