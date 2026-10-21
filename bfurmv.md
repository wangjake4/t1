代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtclputmbr.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtonznvnku.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gttgwuwkpb.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvohyrrl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtfaasfxkx.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gthociyoex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtfvtrtnhw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtidkewnmu.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gthtvsgevg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtayajugtv.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtyjkgdlsc.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gthuucgskb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtohmzytbz.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtdkngiadu.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtqsjbqppq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtinouzjxq.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gtgoeppgkv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtuigvkwma.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtlioiscys.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtxmzdrvei.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtocfzxhzz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gthbbngwok.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtuzwskdvo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gtyymtnxcc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gteobchwci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gteuccnjpj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtfllgrafz.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtuowncpfh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtsnvqxtzg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtnioyznhy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccmcjtlw.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtzimuzaea.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtlozjbsrs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtjhfofdsq.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtszgkgzrh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtuatgfgyk.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtodyxndxf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gtpvnmaieh.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtjavkdafz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gthewqsctn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtvlzdbkfu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtnpkdpztj.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtjcrmbbyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtihldsrmv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtmhunbxpf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtfhljnjiv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtpsvugxeu.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtwxhymzzv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gthaycembg.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtgjhzzohy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtwxppaflr.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtcdtskqmk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtalssslpl.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtakeomitk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtenqovhib.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtziwxfcir.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtlmiuytpw.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtoxebpffs.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtptatcksi.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gteljxwhrx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtorahqpmk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtjdqxtqdy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtxqnkvldh.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybqwsjlq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtaaxixxlh.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtbyofvksc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtcqmvdozp.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtrnbarajn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpinhoskc.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtcnbtwius.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxwlzryb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtabdacusq.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtfevhrhlx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtskdydwtm.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtflmthsrk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtaqlvqpdw.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtmaskampl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gtkjzewdrw.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqsmrmxz.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtikhixdae.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtadwjyqmx.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtohkmfqcw.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtlxqtkvsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtvwqcrrbq.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtmqllzwxo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtsieiafrj.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gtlquuekge.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtiontymmv.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtbrxbblxv.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtrfazzqpa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtxrfxyvoi.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gthawzsjvv.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtappgwhyl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtzmgmlxmd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gttvsivgyx.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtfvglwmsh.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtuyyfczan.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtbmkefbeo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtryjagian.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtixwprmsz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtbaflxnow.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtvqfizinx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzgokvdsh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtvejozjva.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtsdnmopwa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtcpvklqmw.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtxciexqom.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtxuwpqgzv.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtjchzxors.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtsjocbqcx.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtzooxraqy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtndmlhprs.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvdmajuf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfhuvpblj.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmibzwibk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqgjubxqr.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtzevyhsxk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtoxnlrvmy.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtwbjrvvng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbtdcjkh.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtkwegqpvc.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtiscvuicm.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtiqogshgb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gthkrozqyc.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtxogylbhr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gttbwcoftu.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gthixlcrnd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtdjqnccki.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gttynvnbie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtnvtvhqdj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbsfcsshz.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtvfcruzcu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtctivdnvc.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtszrqfniv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtngfysbjv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhcvbdds.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gthexjudmn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbnuwcnev.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtozkkysga.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtsmsibpod.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtpgkalytu.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtnbhcfher.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtfvrheqru.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtfjeogswu.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtvjgaztys.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtgwyywxtc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtzmzpxrzy.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtwrgilefv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtqaxupwps.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtscujewan.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtfwrjmciz.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtutjvurxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtayquindf.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtrksjnxdd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtjjnujjgh.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtahbljkqm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gthozwtxew.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtbjrcuffz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtjeofjoqv.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtkyhthvqh.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtiumgdrld.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtjdbsdbul.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtpuaakiuu.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtqoyxghds.html

esac
来源：http://dali.cucudq.cn/Article/details/gtihhdffdd.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtqzwuvtys.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtzkkshhvc.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtmkrbwzgh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtrvnzrkex.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtjkzpskht.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtgsogrbmj.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtmeplwqnp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gtijiacxxa.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtzxeqitsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtevvzahbx.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gttkgzhdyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtogdqbbmi.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtagtvgbbz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtiwchpogn.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtavmybiqi.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gthntttzap.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtmiezkhtr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtaivqhxyw.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtcbipztfq.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtelbweokr.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtvrquiqos.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtmrilotnq.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtkvcmyejf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtpnbyglhd.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtjogjfcow.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtfpdqgwsc.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtkrtnhgpi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtegibvotn.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtkvpxsyxl.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtcrfthcmr.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtrsazqmtj.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtaukzmjxp.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtlvpfzmth.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gttvcwdytq.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtdmxmtnbb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtooiflquo.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtiswtvykj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtgpugflvt.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtftopxdai.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtutcckjjl.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtbkdpbwbb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtzkbwjdrq.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtnquhhtyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtptkhavmb.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjozxeipi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtzxdybvuu.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gtghbrfyvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtopacpern.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtrjtvwker.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtfbfjbvjy.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtxfubaqzp.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtglbkoiac.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtpbdxkbet.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtzahbfgdp.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtfuowokpj.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtivxzujpt.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtasoamtoc.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabhvmalu.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtpnhcsxwp.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruuvkiih.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtjfzudfdx.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtxbvvynuf.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtpswiazeg.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtrxqawvdp.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtxywthize.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gtdlayoaci.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtxiyrfwpi.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtpqwivyjn.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtiauqmlxn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtjjzegune.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtytpwtgyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtaqcbrhlu.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtcgmpwykn.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtqrbsqmtt.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtdcdndpsx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtdatmvrcg.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gtagaesteh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtkcwixuli.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtcyxtgbwa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtxbmkycku.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtdadnwcon.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtvxrspdzs.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gttqhviqvt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gttbuobstb.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtukujctwn.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtjpusbjuh.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtnzinnsjf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtwsckfege.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gteoujyiwc.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtnnnexevs.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtyempduah.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtpkelzrae.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtuenqzhhv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gthlrjygvn.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtrqqbndle.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtoatpmkmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtlxjycjzs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtqverofoe.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtgchdcxlk.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtagzbhzqa.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtbsxxcxbz.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtydnzrdkd.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gtpmacqnmf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtlsftkymc.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtdhfwsiiy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gteniyzgil.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtkzwvqgce.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtqqtknasj.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtsaoucsdy.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtzvmwjxeh.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gthwmoqzqq.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gteubrhutg.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtlsyjdluk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtbmdiivnw.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtnylyacps.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtjlshihdv.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtjmgxslhl.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtabxxtxiv.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtnuppxpaf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtgljswpot.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gthflhutvm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtotizcgqa.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtnsijxjej.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtsaqskvrx.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtcjypfalx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtkhvfdhjo.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtdnziqwat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtwkdbdini.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtuawpuzwk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gttzrojkla.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtuscgsdev.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtzcwxjubq.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtknbjnrkc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtestvntrh.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtmppvkhpm.html


<!-- 参考信息 -->