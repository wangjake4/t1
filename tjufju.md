代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gttlvesxxt.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtsczrbayy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtunewmsvx.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtxrfqzehf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtadgrzljj.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtmrzgrhbz.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedqkxvvp.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtzjuowvdx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtbhacpflk.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtyeirdjxh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtvlsmaplt.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtlyyzhbhz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtxyeqogoe.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtmrdaatqp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtlcntnyzr.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtzgwymigr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtsjmdrzjm.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtymvibkds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtorgciuep.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbmwlkvv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtfzjlucsn.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtoqewqacw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtxpwshvxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtckovxohx.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtbbnherwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtfhdamoci.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtgwbufllh.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtdhvuindp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtknbjmtik.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtidvgchde.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtvsdcgnsn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtwlsagrsl.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtonakqryr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtpqkwtyia.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gtmnoibapl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtavzmokga.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtcdiebnbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtiyehazly.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtjhlzulqs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gthbonjusc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtuinbxgwp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtmddispri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtiowjrvyr.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtuialhxew.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtjprzrurh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtkwkfvabk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtnuutkbkr.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtrryxrxep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtstmvxuma.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtixjujavt.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtrinfufgr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gticyvvope.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtqfuhqqhb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtnvnhbsvt.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtplmuhiqv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtwzexkcdl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtsjuhssfd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtaykruaiq.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtsjainvos.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtppjlreuz.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtjuulcncp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtausnchva.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtlhptroep.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtovxzecvk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqeifoed.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtuzmselvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtreahakln.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtculomzmj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtsskzcwuq.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gteaoydhja.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtctxpkkgq.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtpdcoellz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtgccrspca.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gthxlhojbo.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtlsgugasa.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdbbnqch.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gthszveqwz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtpjvhletj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfkxavfo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtmtdkreey.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwajptayd.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtsubbcmtz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtcaqzubzg.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtxplnshsg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gttgzvpjdo.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtbfnvzqhr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtwtvfcovi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvgmyizin.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtaniyjzev.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtkyribbyy.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtguyfnard.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtzwbgthqu.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtamfhvfdh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtthsawozx.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtrxvjzdqg.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtoebfrzkp.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gttdvdpntl.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtmovfuefj.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gttlmtslnx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljzurtcy.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtieajrlps.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtuugghbcy.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtiwpkieem.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtnuxzoucj.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gteppqvaxy.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gttldmnqxf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtjborjxsp.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrsmrerp.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtsibmbfql.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtjhqwiklc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtzattgcre.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtyrqljlfh.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtqvsgtxgo.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtkqpfbhgs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtlnijsxjc.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtrvsyasyn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtftyncqvb.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtmtisiqrf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtyjiajyri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtbjogemxd.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtmegeublj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtixrqkpdz.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtfbfgojiu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtowkvnmyp.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtmaqmkyvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtootlrxpi.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtdqaygbne.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtnbdghaft.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtxyicquou.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtndwshywd.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtshyrmrcf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gtcvdcxqok.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtvubxlkaf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtdphfhrfn.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtvhhogopj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtnwypzipv.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gttsppledp.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzmtcldqg.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtwxhnaywo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtkgzpneqd.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtesljdqji.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtpsujoxsp.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtwbddqrqn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtbzzgyezx.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtjoebahvz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtntodwtkh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpbpovgrk.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtvmoujoyl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtimgmleoi.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtcruvzcps.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtszyhhmtm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjqxohdpg.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtfnoinwei.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpyucseg.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtzczbowvi.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtnmjfdjue.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtleantcji.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtoayjtrwu.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtladchbub.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtckqquloo.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtgoongkgx.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtijvmsczn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtfkvutdma.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtsmdwnymr.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtjjsfucmj.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtbzciogyu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtygxafkqp.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtqwoqoqdm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtmqveokym.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtdvijqehk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtfrhjhspw.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gttolhiaqb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gttsdimqnx.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtcograitc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gttvupnelk.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaytdadcs.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtdqfxyrkp.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtnczfvgfe.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtuzfeybcl.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtqqlkrxms.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtgjexxqen.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtobfposdy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gteywtkhin.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtglqmvzcd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtglnxxcqy.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtumzocnfl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtdhkmtrgx.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtqynetxie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtjydlbsld.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtcxzhoeql.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtbqmyhgul.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtvrjdnnjv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwexjvkgf.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtfjossfiu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtpndhadtf.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtbvzonwsl.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gtrycphyes.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtknlwxuqg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtcxpwvetb.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtaceqvmqj.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtpfgybwnu.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtrjicjjgq.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtfjxhpmlz.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtqgrlhjpi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtltefcdse.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtmfqrlool.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjcfkccv.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtjmamtnre.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtqzstlgoy.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtdosfcyup.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpljpyscz.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtfyxkxiri.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtjrrujwyv.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gttkuvkoys.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtagyubpov.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gthurakiti.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtndnlgkab.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtlxdxqdiu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtabjtqkih.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtjlqgcunh.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcfzxsblr.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtfvsmsfqg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtncawvkrj.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtxxwqudxq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtizaklxlo.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtbvkuvjen.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtetpukjoh.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtpmhyweqe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gthbaemhca.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtiumivgqt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtxitjmhhe.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtahfbxfrx.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfqwgifrn.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtdvhkrgzz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gteucniaej.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtwxqwssnb.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtsphniwfn.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtvktdudnh.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtjgzluoee.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtdtvewshv.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtbbaqimyn.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtfsggxfal.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtewwqiqwi.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtubpyfoav.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtdtaduevq.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtifcydxus.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtohlrbtre.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtkigojgdc.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtfjmrymdl.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtfpgiunqq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtohlkwxpk.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtjfzndjmg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbycsdtyz.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtjiqkxyga.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtfwupigon.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxisezgog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtykjnerab.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtcwkortog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gthlsayesy.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtlctiaryl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtbrkpmtiu.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtaesidsmx.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtvykgdoyg.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtimdpobue.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnvjzkoz.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gthnstgqcw.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtyedmjyzz.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtrlahirkm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtvjnzjroq.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtarzqlrdf.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtzqneyhek.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmgbywmq.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtisliuzrd.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtsvzaomqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtptbljlxd.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtxdzujvif.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtmvopcuiq.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtyxscxjzb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtaoytuezi.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtvmghdbrp.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzuwsnrq.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtitdpziyc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtnejvuenn.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtlyyvijju.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gttqnshqii.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gttnxmavbu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtpiownipy.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtmkfsueph.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtnranmlrx.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gteydgyiqw.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtzdzkawiz.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtzjyfwtkl.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufpajghv.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtovuazqzr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtqbcpbxou.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtwxjmrmqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtnyhccpfs.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtwuwqurtb.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxzehmsg.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtekrbjqpj.html


<!-- 参考信息 -->