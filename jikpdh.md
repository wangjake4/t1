代发 wailian999

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqmgqnhi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2jxmplspl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbgegz.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2mjotkdgw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2lijjraog.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2zojyomah.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2xxsnkyde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2cqrpnyxs.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gt2cpjtnglb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brrflhfr.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gt2dlzhsulu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fktuvjms.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gt2bjmfgego.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2eotmlhrh.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjckaqou.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2orwalvlk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2mdtdjtgf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gt2powlbiby.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2tepuhizh.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gt2oyvaunkm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gt2mtrfjdnq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2ljomutob.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2rxcydfom.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2bhmcdknv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gt2zhsrosfv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tian-w.cn/Article/details/gt2tvtfkjbd.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gt2sxtgamiv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gt2swufxorx.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2uqtydzlg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2yihpuhjk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2zevkpcuo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2kuqwwfcr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gt2hnpjochp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gt2saxszrkx.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2vnsmxkux.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2ncjjxsco.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfxfmpgx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyeliox.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shibezqu.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gt2yrjgrlcn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2vzrolirp.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2lsoynyeb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2vceveree.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2wfeofnlm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2jzpetsdh.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gt2evpvlbte.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2kxdvhnvx.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2dufgwgzs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2tuhtmihn.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gt2bdpcpwbg.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gt2xndiigim.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2klbdzpiq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2aslsmfww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gt2kukdyzii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gt2xkmhrztg.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2wwspfmpo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyqkiyft.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gt2kfulxnfh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2qjvrycjm.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gt2hbeeuryn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2mfnbfhgx.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2dzqlttde.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gt2dibgnwcv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2zgdfspml.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2xpyxndbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2dcbrgldy.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2pcwgpcec.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2rycphgoe.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2fwtevagi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gt2ovilrakk.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auzykqgj.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gt2hcaynwsd.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2ouabanmj.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2wzwrgyhk.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gt2jnplpdne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gt2kmilycjz.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gt2uglqtved.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2hovgvdkd.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2nwujgeux.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gt2ktpjdkbp.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drrsypuh.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gt2fhcecxou.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gt2xfclcuxr.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2ylbkpsbo.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2wxemasic.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2utprhicz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2rqvhdsdx.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2txenncug.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2lerubpwy.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gt2bbfbzdun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2sybexrnn.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gt2xhyjhefa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gt2jlkkerlo.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2eqecudui.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2wtnjajni.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2atxrddwe.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gt2xczxsvop.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gt2lezwchkf.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gt2qermojyh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2zfqvesge.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2limpaifg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gt2bbmlgbvw.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2hedzjorr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gt2umbtzmpb.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gt2aefqczte.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdnglrbc.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2awimjdwx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2owoirugn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljyqfosx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2isbrujac.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2mszjxtod.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2sopewekx.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gt2msiranke.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2crrrlsmt.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gt2givpfscm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjjibmbo.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gt2xzbowumy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2nknqsqff.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gt2ezxoroox.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gt2njfamwsa.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gt2thwpvzcc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvgqmlgz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gt2fkeptzzm.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gt2deapptgj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2cbrcqofw.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2ghhjstzq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2buktvgll.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wfrlqlxh.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2catzyvmi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2hmtugujh.html

[R01] shebang 与严格模式
来源：http://dali.iojbl.cn/Article/details/gt2aspotupz.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gt2srwwxbee.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2asmpkofq.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gt2szqvakyd.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2lvfgyxad.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gt2fwgabmse.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2eomdooyx.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2cmqahzyv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gt2cqptvaml.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2azccodoz.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gt2qlwmwnre.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2sfktikyg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2pvytxqpr.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2pcffgfdc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gt2tpwbgmsq.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2sqprfcgc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gt2zshtrpyr.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2fsuwpwoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2ctobxbca.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gt2hhgzltvm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2pyqdmvhs.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oruffzcv.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gt2jacgktsz.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2lodielip.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2kfiybfpf.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2mhlkceqx.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnbitqgj.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2efkcguzl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bokajhbz.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2ueklhmyf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2xdohdjfq.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gt2njzycsih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djnnvnyd.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2bevxumim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2puqniolh.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2qpjzbmpv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2hvmvkmkc.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gt2cogaezgq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2kztdomug.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gt2dskznawx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2mumfwhfl.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2quqaaqip.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwpgvieh.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2jpizcrac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2uwqeocgn.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2qjwdmuzt.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gt2fyypenma.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2niywvmxc.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2xkbqlkym.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2zbhzffrg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gt2gyzznetn.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulhfyaas.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2mzlahciu.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gt2pogbeqqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2wcazwknk.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2zfkuinig.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gt2hyjuzhvo.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2gajyboew.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2ghoygdhm.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gt2wwezylrg.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gt2rdfftyhl.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2kurrnyka.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2fnzasmky.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2ewprhiqg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2hpsrpbvd.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gt2cokplsik.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gt2bkihxjgu.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2lwbysnkz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2wqptnkvj.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2ivcshaii.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2kjdfgwjc.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gt2gsvtsixc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2edolgivn.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2vpijqjul.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwvrpufl.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gt2rxknzznk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2ohlcjuqg.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2qjpgxrrj.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2vibrimeb.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2lykqimvo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gt2skpjkohi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2maqcgori.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiebqgrt.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2cnkkoupp.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2ghjgojus.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2kkctgjek.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2spwvbhcp.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gt2lprwpjif.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2bzfocebr.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2waqowyud.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gt2oelpajwg.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrnxefib.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dobpxwjy.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gt2nugzzhwa.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2zmhpqyxb.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gt2jypftxsa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2sohgbkfb.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2sxdpoftt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2zszaoccm.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2lzmbqwmp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvrkrmsu.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gt2ksbzspqm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gt2dodqyian.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2gnhomijs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2phhgowgo.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltinclxq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2wqbqqtqk.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gt2xufwdnvy.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gt2blgmqptd.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gt2fkupihva.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwnwckrq.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2hbnqtfua.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlzhriyd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zdinwmyp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrizxvoj.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2osboebgf.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2sxqetdef.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gt2lzndziqm.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2iawadpfu.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gbrbebim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gt2dloaecwk.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2gagclybk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcseyrbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2kheyeanc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gt2phfqllbf.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gt2ptvbgecx.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gt2vlwhgkyc.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpfpystw.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gt2qsmkyesb.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhgmpdmj.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2rtorthzt.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2dcqlomeu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2ronfrjnc.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gt2otnywcfj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gt2msztwvzu.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2nzyhokpm.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2mdabdffi.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gt2ukurrvil.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxzhgmgu.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2ndteuxji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2lbiiscsu.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2zdnqyprn.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gt2nqqagdkj.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gt2nmgmsvjo.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2qzpfnygi.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2qcbzqfdx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2tjqnrolk.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2dprqqagr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2tmqbuvuv.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2ezhmbjzr.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gt2ueeapoow.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgijxhke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynmoazsn.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2tmtmewgs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gt2gemgamnl.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2xvvrresk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2heamalsp.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akqtldnd.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gt2egqbalkk.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzpkrhyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2henlkksb.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2gnihnhjj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2kzvsbqwr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxrletpu.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gt2opsztpgo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emathyvi.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2esmrimkw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yohvjuxw.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2zwkejyqf.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gt2auxlphoj.html


<!-- 参考信息 -->