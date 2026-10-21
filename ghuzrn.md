代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtcsztgaxz.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtmyvwcjvr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtsesaywsd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gteumxiyyw.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtmwpgmwxh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtkgbszzst.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtastvwebv.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtymlasowi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtdqchykwe.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtihwvhfae.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtdwgmdjon.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtvsnavxsr.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtkzwonrpw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtkqntsjpl.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtpxjgetfb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtmfrgutyh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtoouefrqc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtxhowpctf.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtytpvbhnn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtydnnontv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtyatzmatl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtgihuujch.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtcwahrirc.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gthvmdetvo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtscbixluz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtxkknxgkr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtfctkpviw.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtyqlkgpfv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtjoiioceq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtcpoxvjut.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtrqchsuez.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtlweglrxu.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtzoibvqch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtylwhuuzw.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtgxgkxbsl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtjspdcwcl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtnxzdtpbf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtiqhkspks.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtvprvbozo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtgbildlsg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtmxbbcdlp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gtoshgmedz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtrykkfrks.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtdbxhddoi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtegaaxsay.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtvauttsvs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gthrjgweja.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtmxgxazhl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtkxfchzqh.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtxyjkxlcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtduiowxmu.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtptqzwlip.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtfuwenaba.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtmnuklopc.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtbyhtqwop.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtywfrbhil.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtswdujkya.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gthewzpsvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtkyvbudjw.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtbhmefaqm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtbsoimtbr.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtwfjlqmgc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtgjrbfikj.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtvgetohnn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttqnvzkwg.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtjmygsbtj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtdnkfuoqq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtsmmxdqli.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtfxbvwbmd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtppdqcxer.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtdcdgzdfw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcizkdphb.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtenwiwebi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtlgdcqorm.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtnlpwoshk.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtlpgydihk.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtwrsagrox.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtypcsypvy.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtpclfzyiw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtlctfrxxp.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtjwqttqwb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtqagvotoy.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxogkglll.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtvqhjngvi.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtjiiauded.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthhvykgn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtfwksjsvh.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtvxrqagpx.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtcvhoegsu.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtkknvnbqt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtxxvnuobb.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtmhwnyumd.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtoijyfzzx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtbmhdvgnt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtshullpvi.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtrvcdghwr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtbesuezci.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtpxiucojd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtagnqfuag.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogntyxyj.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtmkcnxetz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtjogdpgqd.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtaruyfqcx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooydmsrb.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtekieztya.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtygpxzpxm.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtvsquzpjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtikefigia.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtxduepljj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdbxpxsfj.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gttmddlqvy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivbmeak.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtrumktcbf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtlncmwwye.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtlingfjxy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtohqtvxhr.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtehcuhnkv.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gthcupnxdp.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtvptmblyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtufbdibwm.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtyzudpstl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtvepxqasq.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtaokwlfzk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtyfzghoze.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtkqsndxfo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtpdbxixeg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtffwutpxt.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtxikkqfkr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjwsrdd.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtrprcluwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtluitaqom.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgpcbxgwo.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtwlujyfti.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gteudyieyr.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtxbohbvng.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtrfdipyus.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gtgyextbvc.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gtqembckad.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtqouddlyi.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtaeipskqn.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtwgukmepx.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtsnpmdkzb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtzaethdsx.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtzdkyvkee.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gttxtyzseo.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtkhopyjeq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtnlvqqmce.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtmqocbvdw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtpwdrehns.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtjmzkfpxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtrmgrvghr.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtdgahlwna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtxkzjxjej.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtwtrjbvkg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtrmkxkvgz.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtntppevan.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtstsfjubm.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gtnpnjhnru.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtxttwoebz.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxmyccrc.html

esac
来源：http://dali.gzhubu.top/Article/details/gtzrgmeeso.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtefbauwcy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtjisrfmxg.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtcvcjrmvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtyywlvcun.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtfzwvfkym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtwpjvrtcd.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtlfeqyleb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtwshsoely.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gttiwjasgk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtvlfqrofh.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtyjzqcswh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtoosbkzid.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtfkxxacbs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtibgwxftp.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtbvnhahys.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtvctoaanb.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gttvhbvhqc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeyabfcb.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtbrtzashn.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtyplbejxc.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtxakoctji.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gthcrlmlje.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtfefxcjow.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtoajfosja.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtnjdyhffq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtnctvfcdw.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtbpojbzdq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtxjoetfla.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtqiphxgpq.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtyklstxwu.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtypzvpkde.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtqqktiwqz.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtplixqjkr.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuozjbpv.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtetpretby.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gtzaswwuee.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtakgfldik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtvpqsugmc.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gtlbvvweio.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gttsqqmnxf.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtkdfldsxb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtgrvklqqk.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtvpszkcxd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtnsdafizg.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gttnefkzlt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtjneewlcz.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtugalbnsa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gthvwriqtd.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtxchbmojf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtvzcyxbjf.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyypioobm.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtccfsnzrl.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtxkdrcjlc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjmsmoiw.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtjajppqvk.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtclwjfovg.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtjidtvnmt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtrtzlecyb.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtswsaqnlv.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtjpqatsxc.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtttrochgd.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtdsjkioiv.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtbdkmvxxs.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtvezsfqhz.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtlyhuoicr.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtcimhlwks.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gtodjcyiqn.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gthtehxmoy.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtxylvpwcz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtwrtrihnf.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtgajlyzui.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtiqiyjguk.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtdiqtscda.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwezowugs.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtlhazgnsn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gthsdwpbkv.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtraldomrh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtosapgtli.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsdaorwr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtoudmtkdd.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtltoirfdd.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtjmcqziip.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gtjgjwrkdc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtqfdpsczd.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtxrxyquxf.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtbtzhkbtj.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtlxizuojq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtompmxhdy.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtugivprfv.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gttskydsne.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gteywovtkl.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtpzerohae.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtdclpjpdd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtflpsvyvg.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gthlkznais.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gttdrvrmnu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtfjxgjkbp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtgbqahusk.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtarmymiql.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtgnkmbtzo.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtehdrmnbn.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gthobiyxdi.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtzdpqbcjt.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtjplotgrr.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtaguhackn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtisqskqfg.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtnmezovmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtaczrkkiv.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtvjnjawxc.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtfoecaoxr.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gtpijldkba.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gteqskshah.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtyvrbyddt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtneajhxpc.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtbtoplpbd.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gtyyknldru.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtzznepogu.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gteroponlq.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtxrqloiji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtltdxlhmj.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtbcphnuqv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtregnbryn.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtrdiugzca.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtctcxxqom.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtrdghqagg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtizecbgta.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtilrdtosp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtvswzrjpy.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtlebojvcp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtmzchjhks.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtrsqfadkg.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gthjkxxhen.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtrfnnoelq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtxokziogo.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtapsksfqv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gteozimqnl.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtukjwjtzw.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtxabdsjsc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtirtbhnuu.html


<!-- 参考信息 -->