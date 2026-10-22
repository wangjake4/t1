代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtvvnlunhc.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtgmuitpom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtscnyprfa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtrxhtekcm.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtmhrjzvte.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtocqgwkkg.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtmbczukqj.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtfsubkhrw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtoznqxnri.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtfcahssnn.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtojaavaaj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtudhupeta.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtbzaqlsaz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtvzxzlwwm.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtkazauhkm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtboqvmhaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtgnusjire.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtmbcbtdxp.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtdtuazyxz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgicvsxb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtuqhyvjmh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtopcbtvuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtpbysiecj.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gttdrfxerk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtgngujexr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtygdjqdbp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtqumfyotj.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtaavcrfjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtacxgrmpa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtwnwfuxta.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gtfokvbkdl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtfcinitbi.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gtstroqgto.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtujfbcxag.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtqjsurtyx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtxxbplmhe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtxutqgzcn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtbgxnvwrk.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtvpqnhrqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtdpjzfsup.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtygtmlgqt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtpwdpuisu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtwfkwgbdl.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gtbdpxvbkk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtjotijduh.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtthozijjw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtjgoyvkhg.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtcamhownf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjazxibg.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtgbluufvs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtsnqvetsd.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtombxtgux.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtxhhmsecu.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtlucivuhz.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtsikbgsjh.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtpsldvdpt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gttafvfoqu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtxrouhwsp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtbzulmdqu.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtcvopijlq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwvrdnqwa.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtzewqblii.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtxtgktyjg.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtqtjemqvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtaovaagkz.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmbqtdkl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtxcqdlzbc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtiihodaqe.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtjwgralqm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkwiwjctq.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtlmfxkdaz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtkkkjmrlg.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtekmdwuyr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtldspgcni.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gthzazhqip.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtwbibzgjh.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gtvmsistlr.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gttgqqhdvp.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtkmdqauor.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtfbbqevjb.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtoaatglxm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtpidusciw.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gthlynshat.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtxkneyhbz.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtqiolmooj.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtkagtruhu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtkgkvtogh.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gthvlctfci.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtwjtpljcw.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtwxpxasrb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtezgokcvz.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gttnwubkzb.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpgfoxwnx.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtmbzmcoji.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtnyjsylsf.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtdgcwtbsr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtdefulzrb.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gttjcuyorj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gttlilqxfi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtrwurhiov.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtanqfpwll.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtcvhmqhic.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtxqtwemen.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtsetkgkad.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtfpzrzfyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtyonfmvvy.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqamvpkt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtfozsevle.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtdvksoegc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqbqsdiyh.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtisjxfqgp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnfsinasl.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtpaomndtd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gthrqtqroj.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtuipaxuve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxtiwqcyb.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtxiaxrint.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtobqeoula.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtelnqmnbb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtnuigwfcm.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtwrkgkybt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtmruecijj.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtaarejxeq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gttqirtjte.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtnitqmkyt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtliymwbqk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsrvstlps.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtsbxynhte.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtouzzivde.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtjqjslukq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gttokvnajb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzmfnxulf.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtvxliogzw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteqaradpu.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtqljckuup.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtxulgzuso.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtnngwzxjv.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtpiievegq.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gthsefjeiw.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtpmiepiuc.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtllpcjdvn.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtxdjqoszl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtbwdljztd.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtnmgflnlb.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtgyleufzr.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtzhymjesz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtknaikmyw.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtjuzksjna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktvwgtuk.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtlzkhxvds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtpzkwztud.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtuoozknfw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtbodxuphe.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtwjgiodsk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtoeykjixr.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtdemqyeab.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gthaatrpqf.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtlnymyouo.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtnmkaozkp.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gttilrkjjc.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtxjyoxfbb.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtxgluojmv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtpenbvrti.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtoytbozfq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtnxaooybf.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtpsehlikf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtlxwssoyh.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtenwtkije.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtrfrjxopb.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gthkcvyyjd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtwcyvxirk.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgciklms.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gthytepkdz.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhcojuhi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxbxbylz.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtrnwfulcg.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtvwhsuszj.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtxnrbldqg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtmshnvmpt.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtgygevsfo.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtlmzojnfx.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtcbyfpnhg.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtitkpgtms.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtwqdycuzq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtwcotnjlk.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtgvdfgklu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtoeatebkr.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gttzlhxrxj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyryutomg.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtpdpaznuh.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtmudnitlu.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtoukfimgo.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gthndibshb.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gttqqxpybr.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtkseycnsh.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtcguiktzw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtpxcouvco.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtcxwuonvx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gttmkjxabj.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gthpjxffgx.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtjqzwqumk.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtjqijozni.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtzzoicfcq.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtnbswhxck.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtiwqlzerd.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gtgpqdhxjl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtabmepyfp.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtgsompsok.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtdenfgisr.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtormvikkk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gttcsncdby.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtxxefvcmg.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjidorvi.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtvmbjvbtx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtcyoyhhph.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtprcbuyof.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtgqqdyygb.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtxlcgvytp.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtslyikodc.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtrmynxqig.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtdcpvyodk.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnscsqnf.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtkucnfqdu.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtgraludgr.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtfxguoddr.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaverrtd.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gttdhwzcwk.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtxjkhdecm.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtdrnifsnh.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtoixlbtjo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtyaogcird.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtuljzbxkn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtiifxqlii.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtmlotypuu.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtxywhwobt.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtzusvfqtk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtigzehmgn.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtrphkydwm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvobacoqf.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtcynmcuud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gttbtmqpro.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gttuyarfyg.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbdugckol.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtyromsneq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtmtekpquo.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gtusupiory.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtcoywcpil.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtisjgomsd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtowwhfwrd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gttuukzdsk.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtbofxpdgh.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtlixxhrmb.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtumjwtebh.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtmidgzhll.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtqkssfcdo.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtizauqfyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtfrdyxvbk.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtpyuzrlxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtdehydhvd.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtqzogbjhi.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtulzpleii.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtlicutjiw.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtbiqkkbec.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gttyzdwabd.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtmkaofsgi.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutshavua.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtgclwhsga.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtxznvakin.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtntuuldno.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtdyirqqsd.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtnpixzmdc.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtwdklymya.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtnkuhmlsq.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtfuvrwicv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtczfxhwdv.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtbzpfpmuo.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtdfjwptcx.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtqkwcsvww.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtsdxdamod.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gttowkphjg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjraoomp.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtekslwhqg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtxyafqksu.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtebviptrb.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtiyrhqzxp.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtbgolppzb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtpgpscshs.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdbmogtbp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gttiaqhugc.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtjutcwsav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtfeucwxaw.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtzqwcmxcp.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtcnccxbrc.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtxjdhkmny.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gtazkkrcna.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtjoalzser.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtfiwvxgxx.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtuamutxow.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtjvktzadn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdmutihvf.html


<!-- 参考信息 -->