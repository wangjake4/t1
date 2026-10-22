代发 wailian999

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtnledmdoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbpehrsv.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtjuogujqn.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtzzujrrgn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtvxswwnxt.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtsyjxnmjp.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtszkiytgc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtbbxgdroa.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtwpnkkylk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtcisjmyey.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqslrvznv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gtimrurppv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtrmyfjnyq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtksuujjox.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtwuyknukh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtwihfhlmq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtqbkeaorv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtckmusfth.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtfpvyycog.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtxzxuydep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtwgirlrqz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gtouljfdfr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtfwafhhrb.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqqacfdw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtbdhqdyxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtriomfgct.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtzhjihrfi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtvdpevenm.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtjmwrjtmi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtikamqveg.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtoaviusdm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtulxivphw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gtscvrevbb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtfwclkvxb.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtqbrlcmlv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtdouoyvqu.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtkiruqqni.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtwdicchrr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtkzaovxzg.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtlvrvylls.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtklkwfecx.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gtvuvgwzjk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtyukkhhhf.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtwoultrpj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtbrjptxhd.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtlxmofhny.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtpcqfaamu.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtxsumbpog.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtrgdxpioc.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtbtwndzvn.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtislkdvzt.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gttntyuxio.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtzfnjtbfd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiafxnfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtjmwtzppv.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtufjnpumq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtjhhmjmpy.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtbhpbtlhr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gthdqywtok.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gthljqikah.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtkgrbkwwh.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtkqojbwol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtvccvgtmd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtzglwkauw.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtovjcxzjz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtcaacxstx.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtlzlxlvat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtmrkisowm.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtremtpxke.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtxebemcoy.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtjmfydlyx.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyayaqpxk.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtsxlmpwjg.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtcrmtiydn.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtqsidbxmt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvsomzzo.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtybkkntgy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtvpjnzqdp.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gthvrsnmvx.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtrknnsenl.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtbcxfoxww.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtvwxmkfzy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtkwzgtuzu.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtmctvrxyb.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gtcsqodqjz.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtdyhkysov.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtqplehrrj.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtgrjdxsgo.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkieqbpcr.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtobquosfb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gthmvgzmbc.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtalqscfdx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacbxkopi.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtecmqjxak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtprtcvccm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtfdvrtcgz.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtqldcwkyx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtpbnpcjaj.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtpxuztzhl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaxepkuv.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtyxlapybb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtrzotvhli.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gternoferi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtrgjbquhf.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtqfillejp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtaaubbphm.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtwbhgxzrd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtvzpevjob.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtpecwxrvq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttohhqwec.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtadtexqtl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpegqzjzo.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtabimlmnd.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgppfszoc.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gttcdfxodk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtnazhjfth.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnbzxxgf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtpafydktr.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gttvkeaezh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtagmwtrfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtmbehyyop.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gthajrswhs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtyelpgfha.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtuqirdgim.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtvffqqvjb.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtvvyhojpy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtizuwgbdx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteyjtorky.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtvjbawtrd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtaickhwuz.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtyxmeqowa.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuxdtfmf.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtlrmwvzya.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gteojiqyib.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gttexduucj.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxegtudx.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtjotogiix.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gteshqwztg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtvsjvgmta.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gthfzjmvzq.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtrhbiugti.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtqvthryvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtpmxqbncg.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtnsmborri.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gttramjsje.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtdmiclkzo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtwvssnvpc.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtnyugrxkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrrkdzxh.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtdsivcrgj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gthpsaajap.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtmnltmgqj.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtzaprhmcn.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gteswftugm.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gtlaevfsqv.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjayllugu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gtqaqjzddh.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtfuahhcif.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtrptexsix.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gttppzrsbx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtboycjgsu.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtbwbhymxn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gturzcytaa.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtzwlwwkzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gthbporeky.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtyvryetnw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtwuwtmkgd.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtkxrgkzpr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gthdytmqap.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtfkcacrox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtslltqvvk.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gthsjmovsk.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtoacmavzm.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtqdspkwvk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtmrfsvfeo.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtcnaptroo.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkphtqjoh.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtlldhqjdo.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtqipyjekb.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtoayktogt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtvpjblzzh.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gthnlfatvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtgdpwxnpv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtfedebmdh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtyhygsdav.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtlxwyosaz.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtjpyfpbcs.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gthluuliky.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gttmfmmdke.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtpylibrkf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtvssxrjhl.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gttyetgjly.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtzlyurmjx.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtngjijanz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtfqnkzuif.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtvrhqvfxt.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtzqeadllv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtgruhpjii.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtwdufdzxt.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtnsfwqotc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtptbzwlbr.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtnpmapfun.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtwgobxmft.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtinanjgdu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtfhnmuije.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtirctggij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtasumdecb.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtbllnzfni.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtufkoipkp.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtpggyvhbu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtnqdokwjv.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtocqhponn.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtrzdicoub.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gthlzuhqsh.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtcvwjcfqn.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtgtqllbma.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtxfzsofje.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtldjiftyj.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtnwkltkuh.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtqeksgeoe.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtngjedafq.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtovoxywvs.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtijzslwhl.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtnishndfh.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtmzzaypsq.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtucgygmbn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gthchgctbj.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gthnigpzwc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtrfiabbdq.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtotfypobx.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtntzrwhjo.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtdjqttmnz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtzvjagjvn.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtpfahuldo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtgqicpiwp.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtjizydhbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtbkwumzxt.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtnddsixvb.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtytsnciuv.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtlqzluzir.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtfbhbftst.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gthijduvel.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gtikpwjunh.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gthyqzatqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtlevbdauq.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtjwngyiqw.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtgjdqpjrn.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gturluxtvg.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gttqjdntii.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtxghwwydk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gtxxsufyrt.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtzrobhiri.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gtxjupcfnh.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtzrlcixos.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtxkooghwm.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtsxiqwjgd.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtfvuenjie.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtyztntgzq.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtijcbafvr.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtfmwscmtw.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gtlmrmerac.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtzdreuitq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtvnplhqfu.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtwxewxqhs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtbbusxloh.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtofqfgxec.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtiaeceayf.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtamqcqjsy.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtotahwysm.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtvtjkftym.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtybdornmr.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtmdrymhkr.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtiiansolo.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gtseiqjcvi.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtgewvudxg.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gthbbhyvwj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gtxmhylfwj.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtirweyfxs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoqqxzqg.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtovlkeozn.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtmuwxuosw.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtqtxgfheu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtyveqhoaf.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtzxqxnvyp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtjzsfwnkh.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gtlovyzojn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtmzgixhjb.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtxlbrxttc.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtjrdmbagv.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtjlsgkmfz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtryxszvdw.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtlzgyxwdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtufckhvxb.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtofiyoehj.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtcwxrptsc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwfdvytp.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtrcmruatn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxcyodegv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtrluzceph.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtkhibastb.html


<!-- 参考信息 -->