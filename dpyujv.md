代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbyywslt.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gt2ndqbwixe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2ajpjtdkw.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgbpepll.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gt2slxbjsto.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2njpyrtan.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2jnkvxmbg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2lhepqtkh.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2eslyqdyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2vhixloez.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gt2fgyrkjos.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2ttyjsipe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gt2akcwqubu.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2wcutwsbc.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gt2psevqygf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2jtojlgul.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gt2aqqhwkjm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2cecvxtyx.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2nynmghdn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2kcdwejjq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2vfrjffql.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gt2rwogxlgi.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gt2jexqemjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2rpxawiza.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2rsqyubza.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2xhrwowwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2odjmyokx.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2aiicewkt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmjhliwu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2xjrhjazp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gt2apuktlza.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2ivaabnpa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2zsdxlcuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2zxxutegx.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gt2ndfysklk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gt2hqkarbib.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2gktkkeyj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2ahagmckq.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejuqibwb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2pdyqldwn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2gsirlwro.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2huztssva.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2aunmoxuo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gt2xlbrojty.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2zkavedda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmngutaz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2eeeaince.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvkhlabe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2hulhhgoz.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gt2qmamgxvg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2mhuijppo.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccubynba.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2przjtead.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gt2hsenbzlm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2cbbkgkyb.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gt2zjmdydim.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2kvyeogrk.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gt2sarjkudc.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gt2nhkvjvht.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2slrscvpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2wmzbucey.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwceogga.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2fdnupykr.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2lugylutb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2jxfcfdro.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2awkzxgyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeasprtu.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gt2pqxevaxb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2yaivunal.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kclilzqy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2hysxuzqn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2ajoqntxh.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gt2wcepdihm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2dtkbxwhd.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2knlbgawi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2pwkufbln.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2anmwkobx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2yaahtwop.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2dntvuzij.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gt2mqygxfgd.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2smekeueq.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubuoqmmk.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gt2ccyihryx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2gpnhyttu.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2chdhuwcc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dysopyta.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gt2yehczrsp.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2gwczxyqg.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2udyngnop.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2bsksijsh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2fpcmzjui.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcthqjtu.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2knkkzztg.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gt2nteajirr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2gsxllgju.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2rxidpkhv.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdhhqvos.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gt2atphdbxs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2mnmgfxoy.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gt2btftjoxs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2xytfsxoj.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2egkybbpp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2xkylhzvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2djvuqvyg.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2hovjjgch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gt2bkloiuic.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2oormycjs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gt2avfgrcln.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2djiphtjg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gt2kseziyyn.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2oebyynyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gt2eppjxidw.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2vceoojzk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2ikhezygy.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2gxyktgao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2zxjyityy.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2qmczfqlq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2utwwxovf.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2qmjgvtkn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2dtbelovh.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2wbxymcqh.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2ojgqvwba.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fninltef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2huowddrf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gt2vwnaviym.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2xcdbqcmt.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2oytjgxji.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gt2mbodhojt.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gt2xjoohmwd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2qsmjhhid.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2mcdosyrl.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2wtrbwtts.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2jskqzzmq.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2vxkbaznc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uynaphjd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2prtkiwou.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2spekhtjo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nlgnxzmk.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gt2zjdaneia.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gt2dhmoocjv.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2detjxfuv.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwxmgfza.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2eizffqrd.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gt2wzxifbdi.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2girykghw.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqvwlvsj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2jtcczgsy.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gt2oijtqyth.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2ezzsxjva.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2lsyjniwv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2xapefmoe.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2erejyeli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2woukaore.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2apjqncfq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2xpjiuopm.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2tjskujsx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2tmmrjtmm.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gt2dxulneue.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2zjhurbef.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gt2yssybrue.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fklxmkzh.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvqjpvqz.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2mqhxzqnd.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2llhxtxef.html

esac
来源：http://dali.chenlongwang.top/Article/details/gt2mfkywtzm.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2epsecpot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2ocjrqtie.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2zdkotgap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2gknjhqnl.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gt2zwteupnr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2yevdqnky.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2hiyuprbg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2qdzhonzi.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2azwwwkks.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2mjjrhbqc.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2clhttsrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2xalgkhwx.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htpykofm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2shrppych.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2fjwhoyqj.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2oklndwlm.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2reidbmag.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifhbsius.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2oiudhfau.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gt2oozgtbwa.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2rhejhdum.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2tpynudkl.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2jiaygtjb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2fqkptszk.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2xneimcjy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2hkjmmrfg.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2nsywbdzo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gt2qhcudnrv.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2qzjkaesa.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2wanmwegy.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gt2btiksiws.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gt2uvwcwqon.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gt2covojopv.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gt2kkhiengc.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2uyvlpfks.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2ujgworoj.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gt2spflpjit.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gt2qtctcmek.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlpctnhx.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyxvtvmb.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2btukjrxe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2vlcqvibe.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2xghzjlqt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gt2quzqpfoj.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdmltwkv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2jmzxjlbu.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2pirdoprt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gt2bsiqhdzw.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gt2lyioynnf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2yirohuud.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gt2uaoyfxuu.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gt2muaruejz.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2zrxtaaws.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtztqouv.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gt2lomdvzfc.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2bahvuljs.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2zwkaqttf.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gt2tgbuolcb.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2dzouoxzu.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2ugyizzkp.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2cnmlvbdb.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gt2wcayqelx.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vvtbpugq.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gt2dpcmahml.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2djmiwtig.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gt2younwsod.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gt2bpdakwyt.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2krtpbkqs.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgvzuizq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gt2acmuvbgt.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2vlselwhl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gt2dtfwuyzy.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2stpfyiwo.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2vsrizfms.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2enkxccvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssdwxmbz.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2klluylxp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyykgybw.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gt2hyhmbzaa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvzfwcrf.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cppdxuyq.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gt2txkoezag.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gt2magvlwlp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2kmaremfx.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2ubmhszok.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gt2lgbhndus.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2rvyrtols.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2qqjukbtl.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2cmhddpgc.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2fajlxjez.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2lykotrsl.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2hmlrbpru.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2zsjrrhgk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2asvgtiqz.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2emefejak.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2lryjwhmr.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2uipgpafq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2yoemssap.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gt2upgswiie.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2lfztsefb.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gt2iksknufk.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2zbpecbnt.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2vsmhmtfv.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gt2fvfoaopr.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2wqczhuvx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2orgscpif.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2stgxztnz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbtoxicy.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2uccsyqvg.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2ozsuxzll.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2jkwcuivu.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gt2uxejfevu.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gt2cqvpurme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2gbzhlnck.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2ijlnxxqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2fjstevao.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2mdrjcwhq.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcivznej.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2xxdcplhh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gt2vrjchbbt.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2jyjrthke.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2klubjhca.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2oplaeias.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2voxnspwd.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2niaoofnj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxhhgdhf.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2nopebgur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2ibmdhjww.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gt2syokxuun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2jzhoojbl.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gt2bqizhjrw.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2tlgbgotd.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2adhtdodu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gt2hxvttksp.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gt2khilbvqj.html


<!-- 参考信息 -->