代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtkpfmhjlk.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtnzibqzgi.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtzocqgxcf.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtvsgcomys.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtrnvsepfj.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtkwjrvvln.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtvtroxhgl.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtpzvnneub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtgdziuibe.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtaxpzuxsn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtcjjtzquu.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gttthssvbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtucwclkbh.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtbhixtvjv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtoinznpdp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtfnmhtupl.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtzznfzbtb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtotixqyqk.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtikookium.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtydbtrzth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtgwosimka.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgypgiz.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtnosmwzul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtachmlvtn.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtoshlgujz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtyzrhmvhm.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtlaklyxpr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtpzjfssyl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtdpklfpxa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gttulolmcp.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtlolshuul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtekacsbpe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzstdwqui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtasrpklez.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtzesiyswl.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtglutyqfk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtxnawoowq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtihmcrzlc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtwrjvxsqx.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtekucgvwy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtbzxbyzqy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtxclywstl.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtadmyshli.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtshjzuphw.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtdemrzacw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtstbselhx.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtuzvfyxmk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gttznrwgfr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtnhbssxwy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtabvxupxn.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtqmkcaqjp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtahftgrti.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gtbzbnuowc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gttgvbwyrg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtvsxolyaj.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiijadljo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtqzadrzpr.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtsompozug.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtiedagefe.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtlexggqut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gtjbqkcffs.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtdqfhhkwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtjfznykwz.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtvyoqxdkb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtwdvtbohg.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtqmmdaqsz.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtqgszdbdt.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtvdeigusu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtczjducdb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtqtvljqvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtaljindei.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtatrvkslq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtjowqxqfo.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawjxnzux.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtmxgjumpa.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqbwjsuy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtzadmkfmd.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtmlzxxtdb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtjpcvmhyo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtceibgdgk.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtedntxptd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqxqpkglx.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtpzdirtsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtnrkykxmy.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtfgvbkluc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtnfyfniqx.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gthsclbfyx.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtubjdbjbt.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtlajfosuh.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtkoitesss.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtlunrjrjb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtbkhvbyfr.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gthkkqwfwi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtbuyimkvr.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtkniiqtys.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtjilgtqkx.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtzptxodwh.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtrwttzept.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtdmzhgfiv.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gttjkuklql.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtuyzzozov.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtfphejejt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtfqtijynx.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtdagngfyi.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtszyvvywd.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gthiodncmt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtunumlpeg.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliyvbkoy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtyxutpnym.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtirdfpptv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtamuerbku.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtrugjzlas.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtbubmkrzk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtvrfpneiw.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtwigvuxrp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gttxiburcc.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtaxartcci.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtksvcwpng.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtqyaszjkq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtkfxlkgyc.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtusvyyyev.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmgthzfvr.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtkympmykk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtbxoubzkm.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtazkoyngd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqtyhcmrg.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsjrjkzt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtelguvnge.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtoctnbmbb.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthwpkusyo.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtsuflsqee.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtdghlruat.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gttwnllqwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtjnjhvtvn.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtogtmmaoa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtrlsiclsg.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gttplwsovw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtemaxpekz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtkpofmwef.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtsxevpnvd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkighbxq.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtqvyvgjsv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtlnmfpkff.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdrgmdcio.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gttzontpqe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtovkhlzux.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtswptcbfm.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtikwvhuiy.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtcsqvslho.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtskjesoqk.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtoammenur.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gtmrxbkuwy.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtzedsuzzb.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtbzjckvzy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtfraargmw.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtbzvstwit.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtckdkagtr.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtbkolquik.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtffhijkxg.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavdsgxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtehxsnlqo.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtyzctytcq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtlyetmpew.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtkobnefvh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtyrtizozd.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtylipfwcp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtmjngayes.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gttxaxmgjb.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtwzjvryxq.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtcqlidczu.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtnqwvfmyu.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtdgqzqdbk.html

esac
来源：http://dali.ivvv.top/Article/details/gtaajbmgdm.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtyaxzgqkj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtnbomrsmb.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtluaaxcof.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszlbmbje.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtbfqkgebs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtsfgbvqdn.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtqyhmdjak.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtnpfshhys.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftjoczhu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtkahwquzp.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtogkrxifv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtmuqatfqy.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gtapfkwrbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtvloudkwp.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtcriwwfql.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuggvnsek.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtokyvrpjo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtftgqbxro.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtgxopobru.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtylmlzkwb.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtdprdgyke.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gthiatqetk.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtmbmopnoz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtkulchbbj.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtkhwwpzud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtfioqxarw.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtizlbzwve.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtfqmyxqvq.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gttaenvdik.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtrgkryude.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtddxsympb.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtelvuqtyq.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtcitzxajs.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtxpauhefv.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtkupvcpqy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gturmtcroe.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gttehdwpys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtazwqlrmc.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtjgirlaed.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtedvprcnu.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtimizlgoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtrnbcdbfh.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtepfjnkhf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gttropyuky.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtpmkkbyff.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtdhxdprxs.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gttmdinmag.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtgrkmlmit.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtdnjvouiw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtqyrqcopx.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtwnebfntw.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtnewptupi.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtjossymrc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtilbxzstq.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtttageamv.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtiujziaop.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtkcyiwopw.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxeinmna.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtyiypozhx.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtfshhalwn.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtvxewrhkj.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtrkoceixm.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtzkxselde.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtjhmicyfe.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtqzmijzvs.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtddtldrtd.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjkmtidw.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtgdtvowie.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtdwksgzwh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtqgkojsys.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtlzixbawn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxbwshxt.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtvdoueosn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtswkvcqcr.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtxagozbvz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtkygadshq.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gttuynrfky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtbxdgedro.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gtynsidvvb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtkopqpryh.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gthvvotkos.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtmjvcbhdt.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtdsqpeemi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtmcnqnzci.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtxymqfenp.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtzqjmfuse.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlibiqpiu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gthiwlkmav.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtwddgnurh.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtcoztlaar.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtklsomekz.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtsffaanoj.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gttqfbinap.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtxdozhiyb.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtyhwwmozg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtzfhzwbmx.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtawldrgee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtxxbsdzks.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtxywyajnr.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtuhgjjlhw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtengunjbu.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtupzjcxme.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtehbhpktx.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gttxwcqyyj.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtpxuvskan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtftjtbvvc.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtfcpancnp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtyafcvpqn.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtknxpogsj.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtaouzaugk.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtitfdpsey.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtbnobnpib.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gteyygmibe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtbkseynns.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtwfmarmqy.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtylzgkoji.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtbgaxyrkk.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtycwbfpwr.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtzbvpuvmp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtxnbasgqw.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtpjpiemsn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtslbjzamv.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtqieornri.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtjzhfxqzb.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gthhbuvqya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtstrfkdby.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtapouciqb.html


<!-- 参考信息 -->