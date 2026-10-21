代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtvxkebsal.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtuqfcsfls.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtpyqdtmqe.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtifyhcmic.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtjulgulja.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtmgcwmltb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttdtvltxl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomkdjpiv.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtevugjrbe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtcpdylntb.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtkgrrhhoq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtsanwvvrw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gthbpmwikq.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtermtzyio.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtufjccbel.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gttrvkpkzr.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidexuzfq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtktrtiuyw.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtfkjvhgqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtbqpibgpn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtwmrkxahl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtxnfzgwjm.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtxsszjude.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtrnpxpsxk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtcntcagsw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtsftsnigu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtxgabjkby.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtbfidwuyj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtrhsvyzcw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtlyssmsvf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtaavcixia.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gtomwfskei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtpvnwusrf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gtghktuxhy.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtibljlioz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gtnpetrsat.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtuohaqbht.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtohcpgqkr.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtkouelhmv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtbmgrouhl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtfcqcjjuc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtvopxnask.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkkjeoaw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtqzisvwyj.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtjmuwmoep.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjvxaimt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtwygbhlxt.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtmavitbnd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtbncewaew.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtnybwyvlu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gtfewskfrh.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gtgjojwamw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtoabfcjpy.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtmntrzghh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtkvpnlnko.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtpotqxjca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtyjgfyxwi.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtpokmwhlw.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtoyjstktj.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtgweyofiv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtvegdnkdb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtqbkctkow.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtwfibceps.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtuxqdvnps.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtlkznmpyw.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcmoqozh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gthpvqmzad.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtmnnitotp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtyelqlrco.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtmqrtydfh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtjvqdujrm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtznodhfom.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtdurgikcj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtzhbsnxwt.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gttikpbmjb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtjgrqtjuk.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtwhutjbha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtcmwqtrxe.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtrilghvtk.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtfzbmmyii.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gtsvxcvhaw.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gthvpnhzwg.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbicrtym.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtawwprrol.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtiyipmlwc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbnofjdw.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtdcluiymf.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtvywuzfhs.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtfxihzfwo.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gttejkgldy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtnhwjapjj.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtknaueksp.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtrakdsgrg.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtzylogjso.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtzgexeerg.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtdyicydtf.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuvrzzcrn.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtsfxrccse.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxaxareq.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtqqaekmdg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtcilvqqqd.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtbzcfqoot.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtgjthoojm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtqcybchyp.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtsyrgamrx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtmidagirl.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtgigrunwe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtxcosrmmq.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gttgkpjerv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtonmrizmi.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtirzpvkyn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsbfkrcq.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtsmyozctd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxahjtrgv.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtevzfusbf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztqtcfyx.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtvlhjiawh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtuymmniok.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtcrhhggjl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtuaedbrkw.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtradsyyym.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtixlzgvvd.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtuqdgxfrk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzywsvesp.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtphzzsxin.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtxzqzawgn.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtjnboqlit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtdpogpcsp.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfijnphkd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtupkzwmxr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtfpufpfar.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtebujiuyp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtrwgwtonu.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtynwkghow.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtgsktsljb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrvfrnqzy.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtdtwmgxxq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtczwuvrgn.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtmdtguays.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtarnuqptu.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtinauicyl.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtlfbrqrpu.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtwudhqsvz.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtkutybqtx.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtcfeljgrx.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtihwbzyvm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtavdvjevp.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtysbdnjjc.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtjqslugyx.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtpyshslap.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtvmsberqs.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtgquktpnm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gthggoszmr.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gttpxynodd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtvfltoxcs.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtefwjryyg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtmhzqzujq.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtvzmxjyhe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtmslyzzck.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtehsvuzcj.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtotnwewkw.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtmrqpbpex.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfassuukv.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtsvwgxtdi.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtubbhwkfp.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtuzmipglu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtnvnwogom.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyrzgwhc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtpotgvexy.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtnxxmbesy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtikbipnfm.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtesoqxuqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtlcridppm.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtdkkiuhoz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtyxojnycn.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtbneuxmow.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtumkqjinj.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtiglsrngf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtdtqpogte.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtasjwbtmd.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtlkskpzfg.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtestuqcjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtpxpgsqtq.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtakdjacgi.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtfapsybia.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtmisfmgbq.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtzjtewcvg.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtbqysraqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtefknrtgx.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtejgysspy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtwpqiryrt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhvxlder.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtzemlbebp.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtahbxgzue.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtfncuzrtg.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtnwlnmadk.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtsmuminrb.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtxbwvtjde.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtdklpuviv.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtejturxot.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtbcjiarau.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gttzasfgrn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtpjwvocaa.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtvxveqzgu.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtyyznrdbh.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtbkkacley.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtrbpqfkxi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmlrviyo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtenmvjjgj.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gttpifptkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtewohyiff.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtdqbydbin.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtbxeufxlo.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtbyddosry.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtbyaanfoz.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtfwpebcql.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfkeoztp.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtfousedxg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtggbrtxbp.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtylvpjjhv.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtumpvotlw.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtdjdseghq.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtrgyulhde.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gtoclnpnst.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtffhxwdtz.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gthuadcwna.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtcvqdabrn.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtpooolcbm.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtpkvqdbrz.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtratxuojk.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtbuqwmvkb.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtfhsowcft.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtivokpvqs.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtomkwdspq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtwvwxuxho.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtmgxgvamy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtxcikehfh.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtmdtyezts.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtowhljglf.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtatwjyulk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtplwhboxo.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpisgzhr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtfszeebtc.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywvcsphk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtzmpplbkq.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtuuwaizkv.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtzisdvqze.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtvrwiiopw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtqmhorffl.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtepobgdfp.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtjgwqcygd.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtqhiclnkc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtllhbzvsk.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gthimrkzjf.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtjqujuxaa.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtmwkycjnu.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtgcgxotsk.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtlqarweqq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtlkggstil.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtblkxnhpj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtoleexajp.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtescmocdw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtupgyuhyv.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtgjuldmfz.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtukgdgsqr.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtwvjdttmh.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtawwvvplw.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtcgocgjqc.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtorkqjled.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtawzuxqfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtrwrbjlby.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gteqvpecgh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtcrfjwohv.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtbkhuqqlj.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gttiqekxch.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtxkcdhlju.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtgrhttduc.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtilvrnxwa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gttwmdvdxb.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtnfruiocb.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtporjiexk.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtqwtjoxsh.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtqrebtayg.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtepowgtli.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtzmhmnoej.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtwvmwgsqr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtlinbpeaf.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtlazravqe.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtjaqrmmzr.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtakctfwbb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtrchugsen.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmzthckb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtgxkbalem.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtxdxqtgse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtiogsyvjt.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gthiwphofp.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtbhrcbkxi.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gttaaswpaf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtmkvhedxt.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtrhssuxfq.html


<!-- 参考信息 -->