代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtaetbocfg.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtdwalhjng.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtmmfeocqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtrevlvona.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtbtxgbdiq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtcjvobioo.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtvvrdsynf.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtmernkmyg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtddfrskmh.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfostlwkq.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gthexgmgga.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkverehv.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtrzxbnizs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtdxhfbfdk.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtrtaackdo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtgmgssbvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtqfydqola.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtefxfsefb.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcwibrnl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtyjqlqglu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtjpxqdvuc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtyoxgucws.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtwmpcpqjk.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtihwntped.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtlnqrbicd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtrckdayyu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtpyfaswom.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtdwuddnvp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtltoytjht.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtxbfewwbi.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtoqvhvtkj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gthhmjjrlq.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gtsfidqueg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtepvfpyex.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gtakbwivxa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtvgbelkfd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtywtmmeqr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtkvpmnhkl.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtyvupofxq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtyhuowcny.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtfjazlopn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtotycpobs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtywqpagzk.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtcxkmqrkv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtcdnsxmur.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtrqpghikb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtjajuddju.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtxkrqigzf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtveikougq.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtwrklrgkk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtswliaqhn.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtsnqanhqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvukrbtlj.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtzvvzyaxd.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtmpniesvp.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtairffljf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gthhhxqjxx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtaxqznaht.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtwftttrfj.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtuwlismlh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtzqehdrno.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtguzjmtyf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtldjapnaw.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtfmxwkrrn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtxyuotdsp.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gtdfazopwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtbtdpcjam.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtzojcywgu.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtbgdrskfv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtxlivjxgg.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpicudy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gthbbuohtl.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtvzilfwau.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtcgebvvnh.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtkaxfxilb.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtyjqzyohd.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtpzfrdijg.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtpiqpoosm.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gttidakbpj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gttdhfbtez.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtspnlkxhv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtasradyft.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gttombrnzd.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtfhvrulrd.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtaidezojl.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtnceoazxm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtvqfmtiwc.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtljmmjryl.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtayxnxtur.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gthcpjmycz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtredfiqhx.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojcvpong.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gttlasrzdz.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gtbahpslyy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtsdxcvhzq.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtmfevkkvk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtguuyrrqn.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtxigpygqr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtmsyvqivs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjhmiiyr.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulavtdfe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtnueuurnp.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtaqyvqqeh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtnsoxhafo.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtoiyxbtgc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gtmqpdsmfs.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtddyyqyhk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gttdlwfviy.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtjgiaqqbn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtxtrnqskp.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtiszymccv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtxelklxej.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtamfnbjyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtntxwtjzb.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gttwnrkwws.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtoncatuoq.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gtizddpdnr.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzseifllu.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gthllkwijy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtwzxmmgyo.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtyzcglqgl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtqzjqlbxp.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtcjucthgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtkiwngvbu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtlzwhdzgn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtazqgsafk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtpnrxgiqy.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtgngoirpf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtydyffeei.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtgbwjywqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtcwqynpbr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlqzcpfng.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtykdloeqt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbvzpeync.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtqmysaqko.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtojnulmai.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtrzyuhkjm.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtzupevjui.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtgxgblpjf.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtkbxvxtmw.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtjpmfegye.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtiuiezehs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtzoaukjeo.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtolorbnhg.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gthhmzrbas.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtqlwnjxqu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtydlzbadv.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtmugfoomm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtpfzewkge.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtxkbfxwxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtrjzhoybx.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtaioaqhgy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtqdutrecr.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtgjraqypt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtztgpzlmx.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtngicpfwb.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gteyjvgzwx.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtfffoaoex.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gteuaklhrd.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtprlpfxcr.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gteetrftif.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqutauepw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtngbywiwm.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtwjycyoqd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtqjctepha.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtwfjmrwln.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtqekyirrb.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtaembbbwh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtzluwqbgz.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtjzckbmpj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqzfmvsy.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtourhcfhb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtgmamzekb.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyozxbid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtxyjopcdk.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtypnqtptw.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtaneqcotr.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtmnwjffaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gtlpbqjpiz.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtuvyqzovf.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtgbsvjqjh.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtdrzgguln.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtbbeezdpt.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtgiqhgsbl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gtlnxgjxaw.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtqqhqczft.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtijznzhfz.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtdfttudbu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtibohfgmu.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtdumopmrh.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtqbtfnqmf.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtmhbxewwf.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtkpdamznf.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtgarmvahg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtqittjryl.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtzaxxqnyu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtstcafqpn.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtgihzpzbl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtptrvdvrt.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtzdmenzos.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtapgrbflu.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtwytbzpfi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtnsrjnnuq.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtyyucimxv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtbprbjtja.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtuddtccdi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtvcqwulhl.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtphaswewe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtjmlxqbpb.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqndmvju.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtbkircfap.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gtpwkdgcmh.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtjqodlxpp.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtzbsavigl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtkhzoefes.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtwsmoexdo.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtdrutqsfw.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtdtsisuac.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavyyruoa.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gthampvylq.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtkvtggfnb.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtxkazvskm.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtaitzoekl.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtdbbpsant.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtebvdhtba.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtdnmnqmep.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtckdaumzd.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtgoxcrtoo.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtsvxxtsoi.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtuasvjqyd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtsetjsoew.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtojafywga.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtynaefcmf.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtfkrferjn.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtbtsojivn.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmddjion.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gthriemofn.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtuvepdtlt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtqwcwhmas.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtkshvsgms.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtocvnhqji.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtiokosjqb.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtuxartfxy.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqzkqmvo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtxbrtjidx.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtetzqyica.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtnzaqnbjr.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtjklixapw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtwqljiokg.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtoafuabin.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtbshkenkz.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtmcukjuyr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtwtfxqgjo.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtebtksflj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtpgyxoboj.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtmhnjewgc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtsrqotjji.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtcyxmnfab.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtiqvhcieq.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtnzgduoqw.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkwlcqes.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtyqwdjohs.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtdrxorzra.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtuohbsfgc.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtvkuolkqq.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtgpbldbhr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtjpsnluzj.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtwzsqsmxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtruhqsbib.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtpxqgyrvw.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtozcrszmj.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtthguglff.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtmfeaiopy.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtpwwsvdcp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gthmhqfayy.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtnjovxbpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtjclryvkd.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtzwyvdfkv.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtzskbszva.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtcgsegpfv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtyegeqawr.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtgymfkndl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtusbfynus.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtppyfebue.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtwdrjybjj.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtfqnuionn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtcjhwknxm.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtgrzhpqcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtxyxxwtca.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtdpyvokok.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtzefdtaji.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtpaocfefi.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtglalmvwb.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtcsjqncze.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtshbsbrza.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtpasqxqxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gthgrkjhqo.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtugwdisvg.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtvbmqysaf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvgblxuzw.html


<!-- 参考信息 -->