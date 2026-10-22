代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gttpphhtnm.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtrkmngkby.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtkncapiwr.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtjxoytoyd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtbbcyoqxi.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gteikoelwu.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtejkjfusk.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtzegsnrnf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwaeckrbr.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtqrjiajlz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtcdkkalel.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtbbsyukih.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtrbanrgpn.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtrvdqqzir.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtetiyharg.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtteinzthj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtcsnkqtsr.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtwgmdcuuz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtwxypbgap.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtgbgpzqbf.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtajkswghp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtggqotsjk.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtkvylbrar.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtcnjjmrws.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gteexrfyxc.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtucrszkix.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtazwzrist.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtwuxrzlbf.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtjtqmpljx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtsfeehhqo.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gteqxlaoql.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtjfzddili.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtuqbjzjpx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gttjsjnpbc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtwgcbgioi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtjsfucsnd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtxoivpxlm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtrpcwehwe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtvakhuzpt.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtbcgobgxs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtqyodwrwe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtloplusrr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gttyvzspcx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtimhuypqp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtyswcmflf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtvrnhjdqf.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtmpfzfrgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtqkkzgalz.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtuxfvsjje.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gthcbgncmc.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtjuihklim.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtkvecguup.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtvlpvnoqu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtfxpghbok.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtetwgogqg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtvenjeefm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtdubwzqgl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtxlvfgzwa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtzofxhlwf.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtjbnspdvl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtixvreijz.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtnijauzeh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtaluffssp.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtytfbqcmu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtlnvcawfo.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtgvgrnfnk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtagkwzkwd.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gtpvrxgdrz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtrhqntzww.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtjcagweev.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtkebxbmmy.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtxyfezbzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtxeqpgemw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gttrktoowg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtyexubqeq.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtloqqwfgr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtxzzghzmc.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtkjpftuab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtoexqykup.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtkfuadstk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmrtotcgj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtmullrzze.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzdspjhw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gttgrgculx.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtmzhlwamv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gttewngcqq.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtjqktpuvr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtcqiujoyu.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtxvxmwbgw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtijpvotkl.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtshltjypg.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtprlkaysn.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtohtrwgxm.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gthhmpecak.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtogldiyrg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtmodapfhd.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gthlqrugbz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtutamjcyb.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtcihzdehi.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtinlpimgq.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtstkvcvti.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gtniyhelwo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtedmasice.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtuyjisvko.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtfyeycxdh.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtabarayhj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtmapiirlz.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtcwtnzixv.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtuxusqrco.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtestyqior.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtqoveicgf.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gttezoswck.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtozjemmir.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtjiwkcasw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtpejcssac.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtxmpggnpo.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtxhpwvdpy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gteaiarwcx.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtlsxioriu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtlveucwwu.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdakuhohe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrcpjdfs.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtmtsbbdha.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtwlensznr.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtvxbjnhci.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtmkbuhelv.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtpstotvkq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtmmmwtelt.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtdctwahmw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfcxycefe.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtcsypgake.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtihgmjplv.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrujzrbjs.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtbgooiwyn.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtjwpvqvar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtfdxlkkpf.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtvcjayfqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtjdozrnnh.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtcyihumuu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtpdykcmki.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtvtyspjse.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtiglcbadd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpppfqgh.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtrdajlejt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtvncfocie.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtvxdqfsue.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gtankotjti.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxbdllyej.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtxrnfkhux.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtksldhzgt.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtefvkibwc.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtlwheopqf.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtkifugyuw.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtltxmrgpd.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtmpxnxbmq.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gteuyvovbv.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmxxlmkl.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtprvkakhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtoazqljkd.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtifedtkgj.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtzatffblq.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtmbvrinds.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtemcjdivk.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyltdvfck.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtvmspjbcv.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtlmmgecbs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtytdyrrnh.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtunylptod.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtafrmtrwt.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtibswmrlv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqxbguos.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtfyfsvcvs.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtvdospvvg.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtrkfwziof.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtcpxhtmbg.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtmsyfkadq.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtftlkjvbw.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtbceqsigc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gtpiyswlwd.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtldlhtohb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzubiyumf.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtvbhikwvp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtddvrcizp.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtzzphrpdj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gthmukzyrj.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtlkefncpo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtyxwzjgbw.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtbvtxkxzq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtrzixbkns.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gttkbctxxj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gthagwhbor.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrogzbqw.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtorcsifuq.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtwiocoprt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtcphajhwz.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtokxyoxch.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gthotaewid.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gttrjixzmq.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtgtrfmcem.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gthvyzkocp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtdncanmjc.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtervefehh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gtmabstbyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtxvkadgbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtnkuhomxp.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gthhdetizb.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtbyygrmny.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtfiexampy.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtoqkvkqts.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtxzpxccov.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiynlwmw.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtagpvbudb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtokvxmmed.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtzsznptsd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtykfcjwzo.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjqudysda.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrdvptzr.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtltvgocoe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtbghaiatx.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtfoptauow.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtnhgoflek.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtefrtcbok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtwscwdqfb.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtnoswemvm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtpsrzjstq.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtufwgqlvr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtgonucdem.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtzhxiolpg.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtkzqafjfe.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtcdbonuxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtarxdkblb.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtevgzlkxc.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtxulclcez.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtaqpkyrhy.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtxvgifxek.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrbhcyyz.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgjfxnqq.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gtvfazhycx.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtytprjilg.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtnjtuejph.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtbuvpexvx.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gttbuvguth.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtrkjtsfpz.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtpwrrqbsz.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtakxdeknd.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtyfprsdze.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtmzdzrwne.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtymzhpaev.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtxmkljusg.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtyzgtqfen.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtenjbcrah.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtnyabejrc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtbngoscab.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtptpcpqxs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtfmuenxgh.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtwzttopdf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtepbpzfnf.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gttykywlmm.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtwoyqqdqi.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtyatlfmqe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtwvkzcswn.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gthxhakvmk.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtokfkqhjm.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtuksihpbm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtpzohxsdt.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtustajkjc.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtzyowmuvf.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtlqorivou.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtkckhvxhu.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtzyxxdcby.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrokmxco.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtmxevjubu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gttekhophu.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvogzrcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gtlywzhijq.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtffegvpci.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtqchrkbgn.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtibodigvk.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtfnxmokqz.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtnayueojr.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtzbzrlccd.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtgbwqoift.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtjsulodzn.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtmquyjmvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtmlguequm.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtmnywzipl.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gthcwzllks.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtmmakprfb.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtxnkjaolr.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtbvdxrbmi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtzxpmgkwg.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtrfvgkvkv.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtwhbkeasg.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtgaspbggi.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtcchznfsw.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtgtnrcqwm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtuwkbizct.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtpkfzzlxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtdfhgyzdy.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtycnekzim.html


<!-- 参考信息 -->