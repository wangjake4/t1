代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtqgfarnze.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtbrilvfpx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtogzazxrg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gttfoaqxlu.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtcwoedauv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtogzunexa.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtozyiogpv.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtvwqycrrs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtyafmqrtf.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtkmsobfbj.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtdmuqhrlf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtuszgrdrf.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtirypcfup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtvwukhwka.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtpcbqfvda.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtavmmdjiu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtadllrewk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtnuvqbcit.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gtvdvgykuq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtzzevdurn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtvfjlmqwo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtuxytcvyt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gthzvrxsup.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtcpucpxtp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtchywcrmn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtzzmbgpii.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtumdrujzn.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtqolhiuuz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtluvkkvch.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtggbbeidb.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtbxqkqhdd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtyjhsdcsm.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtcvjcewcn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtlniwneuk.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtgvtuafea.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtemlfvkyo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtjfyiqxkn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtgsymwqjl.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtwyaalegu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtgdpjccgk.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gtlnapfipx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtvuixgitu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtningtlay.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtzybrppqs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtxhlwelru.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtdxtteenx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtgznxshuk.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtwpisxoto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtnzucyapt.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtjofxieih.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkxeqqah.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtzuaiezdi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtvdfafnbv.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtumnljqda.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gthokziuga.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtcykjnsna.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtrrrtsdza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtvtsyiacl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtkbsnkrsq.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtxhjficss.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtzypsedpt.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtzohljfgm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gthspxrody.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtbqopqptq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtvssgyema.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtvqguxfjx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtzwymmihl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtjciegybv.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtgudjrjif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtkynyiw.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtuhtnhzpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtpcnvhgsv.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gthnhpvfjd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtxeirfyrq.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtoutomuhx.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtcbbixkwy.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtswylltfz.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtkpmgofma.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtsyyolnds.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtypsyvsjp.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtdafunpyc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtozejvdlz.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtmqzjxwch.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gtlwaqubih.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtkzisagky.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtaqbjufin.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuvxeewx.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtwbphykbo.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtwjkgzouf.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtgvirlotn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtptzqnstf.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtmvscesun.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtokwrfrur.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gteqfpsnrw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtrdatjtcb.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtbwyljjbn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtebbwwvhp.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtmukqzlsj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdmlekytk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtnavdvudq.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtofveoyot.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtjbdpvygw.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtpchpqkxa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gtirgmsieh.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtlxqyjmjl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtegbkuxms.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtwgebhlut.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtestkaeya.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtyrpteyio.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwosduakd.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtoslkcwuh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtpcifvqtc.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtltwibcnr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtejlraxop.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtktuqfiqq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoadamasv.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gttmepdqdy.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuqrdjrao.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtcncepnov.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtpcbndvsz.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gtllvdmvwz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtefwpcztq.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtizfnvwmt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtglcvwkju.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtpdyqtbvm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtzjefdwso.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtiqgewxcm.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtxkbqqwwx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtctnlkmqc.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtwjchuonq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtbfcfpahk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoqckwlps.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtiaiyffkq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtljllpzur.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtfazpvcaa.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gttoqghspq.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtihnpvwnb.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtpqzjjvch.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtdqaihetx.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtunwfjxxr.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gterhmbhdl.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtqjqikljx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtwifvhfag.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtpzbdkgwc.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtiquctmem.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gttyxmcuun.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtdofsdqxt.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtcivmpxtb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtgikagzmt.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtabfspqgk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtofdluwpe.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtftlqkfxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtweqihbet.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtbvjmnhyy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtwpddhnmb.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtujepsgnz.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtoahhnsbp.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtlvzweqqs.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtgsnzbxea.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtiqimesxl.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtvzmhvbgt.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmbozoilg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtgwqtgwdj.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtkkhoaetl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtovthcqrg.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtbpablkll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtorarowws.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtjnlwtuxr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtvrjxucoa.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnuvavec.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtvemlqfck.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtxiccggbn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtckukzrpn.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrsojcmk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtzisuqqeq.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtactecqvo.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtogpandfw.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtirhvxwqd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtncdtaedx.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtmwwkcppp.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtsjvrpove.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxmgdhnu.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtbdowibsm.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtqfirhmha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtaefszzhc.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtisohpill.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtsrdzsbmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtgxyboakj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtpqhuhyuj.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtqkfbwnxz.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtapdnyeqy.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtjypesaby.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtttuqvcfc.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtntnazftv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtmwuhekam.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtsolqturq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtfjdiqish.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbputciv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtwyagyaga.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtcnmirxom.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtsddgwwhz.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtvvdlqngo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gthqwmleyp.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtvfmcsxsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtrxabjpbs.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtntyhdufu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtulmeeecj.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtcvqvrdrb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtxvtvijho.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtwinphybw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtodyzbhnc.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpxjvchw.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtdwmkmsmr.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtflmalqsp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtmbetqwzz.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtecfeqnjx.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoquxhgii.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtbvjcksdc.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtjzhqqlog.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiljbenx.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtkfrdqmap.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtxafhiuau.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtuumpgzlu.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfxueemo.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtzbkaivfi.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gttbrfmufy.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtovaqfrkf.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtansuyxue.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtxfccenjp.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtgrtlnjrm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtmvtlyquk.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtiljagbge.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtabragsjo.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtqfuhvrpv.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtzghnnbqz.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtychlehgq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtkycjjivh.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtrfsmwmnt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtallwjtnc.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtxsuwczqw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtgchhvihd.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtrdqxamrk.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtmlssxozv.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtufihwiem.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtupkkhosb.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtboqwszdp.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtzaluniap.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtfhuhtddg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtzczzmsdj.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuczutxe.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtwkgvjkmo.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtbbplrhgn.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtlwrqkfsv.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtzsuiixmm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtnpzuwlgb.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtxdyzzxun.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtolfgivlz.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtsabrhlnd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtfaabghad.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtjncpnxau.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtrhsaklua.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtroxazkqx.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtbvnhxmex.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtsmchwvlt.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gtreyjdnan.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtpcheztrv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtmfbppcsq.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtyxnphnqj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtonjrotra.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtanmnflne.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtijxvnmge.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtpujwtsft.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtingljftq.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtwrdspmcs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtpobfonba.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtdxnbkhey.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtjmiyprrh.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtofbzcixc.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtcwadpenl.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtvtukpmeu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtlkdxvrmx.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtdcughdnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtnewxmzcl.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtgiszmmez.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtagxxnmim.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtjyvlklmr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtdqoykhfn.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtmhtcnmgd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtsehfuggm.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsoctvjp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtneloyiex.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnzeibrh.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gteobnelrn.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtwffuylla.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtoxuakqte.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtnwfnlzqn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtozvagxcx.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gtvqadxwif.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtameavnbj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkykrfofj.html


<!-- 参考信息 -->