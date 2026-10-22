代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtdnfvblzx.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtbwuxyiin.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtyiysimkm.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbdhenvu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtohoplque.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gttxmergcw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gthkfcyrfq.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gthcxswjnz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrlhpbzrw.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gttaxedkbs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtocmcydeo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtewbygcae.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtpdxevxvh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtfaenkggt.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtvpwiybmq.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtcexjearw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtjjsdkmfx.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtrmnrbmkp.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxwghdki.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtpeasbkpx.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtmzragtca.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtjmdkwuuh.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtwhfjivmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtmlsfsymy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtzhxwwrfw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtygmtzgqo.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtnfqgbkdt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtbudykwyj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtjdpsbjhb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtefmjyljr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gttdyoxixn.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtulrurozm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gteywdmvay.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gtanwhnfvh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtuplbosnj.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtdqlvkoxm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtzhfdkbmq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtqatlvmgs.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxgwoiej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtanhjgvft.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gtqalclzmm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtmwxqbkug.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtyxkkixid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtqtqvpnnu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkxbbvpn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtpfbpasri.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtceqjadwd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtixrbcvdk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtpbajzmsi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtnxkbcpxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtqqsaifvn.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjizpvjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtbnbgoiwr.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtnvxdwcsk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtlebmdxhz.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfikarkc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtolpvemqb.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoewpdeao.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtdomjnqpb.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtbwfkonhv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gthdwpvfvd.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtdixjbcuq.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtmqikggdo.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtqdducihn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtjeijibix.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtuiqskoya.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtkwvwwlmd.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtyrwcprku.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtfspnlqwz.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtvhulqvbe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtvzpdbgme.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtvblykxkf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtkneeipax.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtitwbboly.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gthkaaglkg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtknevwizn.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtdmzlqhwg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtcezwbmps.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtvfsiadsb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtmjwqyndj.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtplmvqckj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gtnwayeubd.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtappgfcrz.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtbzcuqcam.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtrwmwvwsp.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtzcoqyqwx.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtpizaacqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtsutrxqnh.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtoxshuxrt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtzzxyjiut.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtyvghunwg.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtlnomqkkw.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtvqyktlgu.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtvdiheyqn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gtinuqxhai.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtayophszu.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtigmhzmmw.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtbdcgljjs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gtuhplfszq.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtnzzjhoou.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtcyivsjkd.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtrmjfmpvd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtmulcvxba.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtrpubrqyd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtewkvpkll.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkhqkjtxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtzxbwvazd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtwmdcfmvq.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtnlxuzpqr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtkfyixtyi.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gtqyneyver.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxsskokt.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtaxfbuisb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtakwbjjfl.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gthurhnznt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtjjbwmedy.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtnkpsobqf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwzmruqwd.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtsecrxebp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtfcsedtoo.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtdxdbifdw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtohamtkmq.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtopkcyqhc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgtqgijkk.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtbwsjoqur.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtiacjkftk.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtjyxhmuxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtlcekmwio.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtrhbdmyic.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtawlijhyq.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtfqlrxxxs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gttxygatfy.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gthrnayojf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtovizeshe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsxdibde.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gttcpviakp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtadchbzxk.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gttiynurcs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtlwrcovug.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwdhvzezp.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gthqaoddbw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthynkjnad.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gtcjysynqv.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfnauhnc.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtmrtduhsz.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtvqauufyz.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtnxbshpiw.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gthlyxbesn.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtefnfczhh.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtkthiwxie.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gttyacwrpj.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfzdhuxc.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gthkztnatz.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtggzculkv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtnudtyoek.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtkimadxby.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtulmvkuvi.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtdumswecu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtgykqurgn.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtatjsxztz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtvcnabsww.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtvtjmgptc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtsygtcpwv.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtsflivabi.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtibeamqgy.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gthwfizedz.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gtgdvqyjib.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtdwvjcvki.html

esac
来源：http://dali.iojbl.cn/Article/details/gtovzchlve.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdcsmmuou.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtmcrngvrk.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtjvvyumjo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtpixvojbo.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtntkxduqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtcawrbpbm.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtwflmbrnl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtddarzptj.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtxrrowsmd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtgysypewj.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtethdptil.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtmnzceptb.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gticqofwxr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtoheldsnt.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gthrxojykk.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtwkvafeyv.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtuuwmqrkg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gthqzgetjj.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtrdfelwzu.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gthypajmqz.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtdadqokqp.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtsxsccpiu.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gteriesuaw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtowpagbcf.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtbxzvypov.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtgugwfsrg.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtniorzqpz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttatrzqgs.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtozmupgpf.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtbjaphfqp.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtmrtlrrol.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gthvimokdy.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtwpcswczq.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtykqiivkj.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrhkmebal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtpabfhjql.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gthdiapfto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtpbfoynad.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtdgjcbnqt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtcychylwf.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtrgqcovku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtatmhynkx.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtvxkbgxxb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiimodxip.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gttkzhvhjf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtlmilszme.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtiiagsdxj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtnwhkejzz.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtnnvycksv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtqkwqrnlw.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtacrxgxzd.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtmpncbosl.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gteoffbjwo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtipbyderx.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtiqwhssta.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtyvhahtbv.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtqsanhojm.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtwwozbcgu.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtjccomnye.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtlzhbcrho.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtpvwqcula.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdztbmvtj.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxytlohp.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtwynypuze.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtzomejwws.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gticnjsjdc.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gthcfyegxu.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtwplbrupu.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtiafgcstp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtzoslbgdw.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtfayugxzf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtbtvxuqyh.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtbhejigze.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtdfunhwib.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gtybtepges.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtuajquvfz.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtwnxcchbf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtjdbgwabx.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gthjncarex.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gthpbcybtp.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtrbfewzdp.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtjxyboxgt.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtesjtteod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtkuvvkyzd.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtsquaaosb.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtzewglzul.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gtcvjxqgst.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtzxxrbdwe.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gthkbmmgdq.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtrrcolqoe.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtlyeczpkt.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtgreabgkb.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtotjvniqx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtjazjluvp.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtbyrprqqg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtlscudcxm.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtxzocpopy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtwfldomkq.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtojagasae.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtkzxwlbvn.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtnmnucach.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtcosyoacy.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtttdxuqah.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfajoaoqm.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtkqonzqdk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtvjgbafvx.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gthstwmwei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtttoutikp.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtjvxztsss.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtfykmwooz.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gtmlspebau.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtxdjpmrie.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtcxpziokr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtnplzesoq.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtifyhkofy.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtmipbjfkz.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtecladyrv.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gttwnllrsm.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtdoaoklkr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtlvhvlyqh.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gtnlsjxiwz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtwanrsyjm.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtoneybsfx.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtatqdrnzr.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtkgiqiupu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtjjtxguur.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtxukzkexx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtzlrmhemn.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtzwzgencb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtjxtyabqc.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtnkjrsznu.html


<!-- 参考信息 -->